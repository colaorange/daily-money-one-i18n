# i18n Translation & Terminology Verification Guide

This document records the commands and workflows used to validate translation files and terminology correctness across all locales.

---

## 1. Goal Command (AI Assistant Workflow)

To trigger the complete, autonomous verification workflow (including automated key checking, placeholder validation, and sequential linguistic/terminology reviews), input the following command in the assistant chat:

```markdown
/goal Verify the translation and terminology correctness of all locales under the i18n directory. First, write a script to check if JSON keys and placeholders align, then sequentially perform semantic audits against reference locales and their respective translation terminology guidelines, and finally generate comprehensive reports.
```

---

## 2. Local Script Command (Fast Automated Validation)

You can run the automated validation script locally at any time without using AI tokens. This script checks JSON key alignment, variable placeholders, and core terminology mappings.

### Command

Run the following command from the project root directory:

```bash
node ai-scripts/validate-all-locales.js
```

### Script Location
- [validate-all-locales.js](file:///c:/dmo/ai-scripts/validate-all-locales.js)

---

## 3. Generated Reports

After executing the validation, the following reports are generated or updated:

1. **Global Report**: [AUTOMATED_VALIDATION_REPORT.md](file:///c:/dmo/i18n/AUTOMATED_VALIDATION_REPORT.md)
   - A summary table and detailed lists of mismatches (missing keys, extra keys, variable mismatches, and raw terminology warnings) for all 18 locales.
2. **Chinese Languages**: [group1_report.md](file:///c:/dmo/i18n/group1_report.md) (`zh`, `zh-CN`, `zh-HK`)
3. **CJK Neighbors**: [group2_report.md](file:///c:/dmo/i18n/group2_report.md) (`ja`, `ko`)
4. **European Languages**: [group3_report.md](file:///c:/dmo/i18n/group3_report.md) (`de`, `es`, `it`, `nl`, `pt`, `hu`, `el`, `ru`, `tr`)
5. **Southeast & South Asian Languages**: [group4_report.md](file:///c:/dmo/i18n/group4_report.md) (`th`, `vi`, `bn`)
