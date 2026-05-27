# i18n Translation Merge Guide

This document records the commands and script design for merging `<locale>.dev.json` files into their main `<locale>.json` files, sorting keys alphabetically, and verifying the result.

---

## 1. Goal Command (AI Assistant Workflow)

To trigger the complete, autonomous merge and validation process, copy and input the following command in the assistant chat:

```markdown
/goal Create a Node.js script to merge all `<locale>.dev.json` files into their corresponding `<locale>.json` files under the `i18n/` directory. The script must deeply merge the content, sort the resulting JSON files alphabetically by key, and verify that the merged content is correct and uncorrupted. Execute the script across all locales.
```

---

## 2. Script Design (Recommended Implementation)

When the goal runs, a script named `merge-locales.js` should be created under `ai-scripts/`. The script should follow this logic:

### Deep Merge Function
```javascript
function deepMerge(target, source) {
  for (const key of Object.keys(source)) {
    if (source[key] && typeof source[key] === 'object' && !Array.isArray(source[key])) {
      if (!target[key]) target[key] = {};
      deepMerge(target[key], source[key]);
    } else {
      target[key] = source[key];
    }
  }
  return target;
}
```

### Key Sorting Function
```javascript
function sortKeys(obj) {
  if (obj === null || typeof obj !== 'object' || Array.isArray(obj)) {
    return obj;
  }
  const sorted = {};
  Object.keys(obj).sort().forEach(key => {
    sorted[key] = sortKeys(obj[key]);
  });
  return sorted;
}
```

### Verification Logic
For each locale, after writing the merged JSON:
1. Parse the newly written file.
2. Confirm that all keys from both original files exist in the output.
3. Confirm that the values in the output match the source values (with `dev.json` values overriding `locale.json` in case of conflicts).
