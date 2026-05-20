# en / zh Translation Check

This checklist lists keys where `i18n/en/en.json` and `i18n/zh/zh.json` appear to differ significantly in meaning, detail level, tone, or terminology.

Edit this file directly with decisions, notes, or the preferred wording. JSON files are not changed yet.

## Checklist

- [x] `appName`
  - EN: `Daily Money One`
  - ZH: `Daily Money One`
  - Note: `TERMINOLOGY.md` defines `Daily Money One` as `每日記帳本One`.
  > ZH > 每日記帳本One
  - Proposed handling: Update `zh.json` `appName` to `每日記帳本One`.

- [x] `balance.@`
  - EN: `Balance Sheet`
  - ZH: `資產負債`
  - Note: `TERMINOLOGY.md` defines `Balance Sheet` as `資產負債表`; `資產負債` is the shorter balance concept.
  > ZH > 資產負債表
  - Proposed handling: Update `zh.json` `balance.@` to `資產負債表`.

- [x] `action.createContinue`
  - EN: `Save & New`
  - ZH: `連續建立`
  - Note: ZH omits the save meaning.
  > Both OK
  - Proposed handling: No JSON change.

- [x] `action.trash`
  - EN: `Trash`
  - ZH: `丟棄`
  - Note: EN is noun-like, ZH is action-like.
  > 提供我en的建議, 這裏指的是丟到trash can的意思，但我不想讓英文時長
  - Proposed handling: Keep EN as `Trash` if button space is tight; English can use `trash` as a verb. Alternative if a little more clarity is acceptable: `Move to Trash`.
  - Decision: Keep EN as `Trash`.

- [x] `ads.level.supportHint`
  - EN: `Full support. Thank you! ♥♥♥`
  - ZH: `支援, 那次不支援。♥♥♥`
  - Note: Tone and meaning differ.
  > Both OK
  - Proposed handling: No JSON change.

- [x] `ads.talk`
  - EN: `Software development takes time and effort. I rely on ad revenue to maintain this app. If you find it useful, please consider enabling ads to support future development.`
  - ZH: `我被開發出來後, 難免會存在一些錯誤。而隨著時間的推移和其他服務的更新, 如果我不跟著進行修改和更新, 也會導致我無法正常運作。這些都需要持續的維護成本, 而我主要依賴廣告收入來支援這些成本。如果我對您有幫助, 請考慮打開廣告, 點擊一下廣告, 以幫助我增加收入, 從而更好地繼續維護和開發新功能。`
  - Note: ZH is much longer and uses a first-person product voice.
  > Both OK
  - Proposed handling: No JSON change.

- [x] `csvImport.fileEncodingHint`
  - EN: `CSV file encoding (default: UTF-8). Select the correct encoding if the file was edited externally or uses a different format.`
  - ZH: `CSV檔案的編碼，預設為UTF-8。如果您曾在電腦中編輯過這些檔案，或是在每日記帳本+中設定為其他編碼（可以在開發者選項中確認），請在此選擇對應的編碼，否則可能無法正確讀取CSV。繁體中文用戶若讀取結果為亂碼，可以嘗試選擇BIG5編碼`
  - Note: ZH includes Daily Money+, developer options, and BIG5 details not present in EN.
  > Both OK
  - Proposed handling: No JSON change.

- [x] `csvImport.numberSeparators.commaDot`
  - EN: `1,000.00 (Comma & Dot)`
  - ZH: `逗號及點`
  - Note: EN includes a numeric example; ZH does not.
  > ZH: `1,000.00 (逗號及點)`
  - Proposed handling: Update `zh.json` `csvImport.numberSeparators.commaDot` to `1,000.00 (逗號及點)`.

- [x] `csvImport.numberSeparators.dotComma`
  - EN: `1.000,00 (Dot & Comma)`
  - ZH: `點及逗號`
  - Note: EN includes a numeric example; ZH does not.
  > ZH: `1,000.00 (點及逗號)`
  - Proposed handling: Confirm number example before applying. The key `dotComma` currently means dot for thousands and comma for decimals, so the likely value should be `1.000,00 (點及逗號)`, not `1,000.00 (點及逗號)`.
  - Decision: Update ZH to `1.000,00 (點及逗號)`.

- [x] `csvImport.numberSeparators.spaceComma`
  - EN: `1 000,00 (Space & Comma)`
  - ZH: `空白及逗號`
  - Note: EN includes a numeric example; ZH does not.
  > ZH: `1 000,00 (空白及逗號)`
  - Proposed handling: Update `zh.json` `csvImport.numberSeparators.spaceComma` to `1 000,00 (空白及逗號)`.

- [x] `csvImport.numberSeparators.spaceDot`
  - EN: `1 000.00 (Space & Dot)`
  - ZH: `空白及點`
  - Note: EN includes a numeric example; ZH does not.
  > ZH: `1 000.00 (空白及點)`
  - Proposed handling: Update `zh.json` `csvImport.numberSeparators.spaceDot` to `1 000.00 (空白及點)`.

- [x] `csvImport.provideDetailsCsvHint`
  - EN: `Select the details CSV exported from Daily Money+ (e.g., details.csv).`
  - ZH: `請提供由每日記帳本+匯出的明細CSV檔案, 其檔名通常為details.csv或detials-<數字>.csv`
  - Note: ZH includes `details-<數字>.csv`, but has `detials` typo.
  > fix the zh typo
  - Proposed handling: Update `zh.json` typo from `detials-<數字>.csv` to `details-<數字>.csv`.

- [x] `jsonImport.importCompleted`
  - EN: `Import successful: {{bookSize}} books, {{accountSize}} accounts, {{transactionSize}} transactions.`
  - ZH: `匯入新帳本, 共 {{bookSize}} 筆帳本, 共 {{accountSize}} 筆帳戶, {{transactionSize}} 筆帳目`
  - Note: ZH says new books, which may imply created-only behavior.
  > Both OK
  - Proposed handling: No JSON change.

- [x] `default.account.diningOut`
  - EN: `Food.Dining Out`
  - ZH: `食.聚餐`
  - Note: Dining out and gathering/meal party are not identical.
  > Both OK
  - Proposed handling: No JSON change.

- [x] `default.account.meals`
  - EN: `Food.Groceries`
  - ZH: `食.三餐`
  - Note: Groceries and daily meals are not identical.
  > 請再提供我英文的建議
  - Proposed handling: Recommend EN `Food.Meals` to match `食.三餐`. Alternative if you want a slightly broader category: `Food.Daily Meals`.
  - Decision: Update EN to `Food.Meals`.

- [x] `default.account.lostMissing`
  - EN: `Lost/Missing Adjustment`
  - ZH: `遺失或不見`
  - Note: ZH omits adjustment meaning.
  > Both OK
  - Proposed handling: No JSON change.

- [x] `desktop.inAMonth`
  - EN: `1 Month`
  - ZH: `一個月內`
  - Note: Confirm whether this means duration label or within-period label.
  > 請再提供我英文的建議
  - Proposed handling: Recommend EN `Within 1 Month` if the intended meaning is `一個月內`. Keep `1 Month` only if it is a compact duration label.
  - Decision: Keep compact EN `1 Month`.

- [x] `desktop.inSixMonths`
  - EN: `6 Months`
  - ZH: `六個月內`
  - Note: Confirm whether this means duration label or within-period label.
  > 請再提供我英文的建議
  - Proposed handling: Recommend EN `Within 6 Months` if the intended meaning is `六個月內`. Keep `6 Months` only if it is a compact duration label.
  - Decision: Keep compact EN `6 Months`.

- [x] `desktop.inAYear`
  - EN: `1 Year`
  - ZH: `一年內`
  - Note: Confirm whether this means duration label or within-period label.
  > 請再提供我英文的建議
  - Proposed handling: Recommend EN `Within 1 Year` if the intended meaning is `一年內`. Keep `1 Year` only if it is a compact duration label.
  - Decision: Keep compact EN `1 Year`.

- [x] `license.hint`
  - EN: `This app is free and ad-supported. Contributors (e.g., translators, bug reporters) may request an ad-free license. Enabling ad-free mode without a license reduces support for the app.`
  - ZH: `本軟體為免費軟體，依靠廣告來獲得維護資源，不需任何授權即可使用。但對這個軟體有貢獻的使用者（例如提供有用的多國語系翻譯、協助進行有效的軟體推廣、協助識別具影響力的錯誤等），可以向作者索取無廣告授權。您可以在此處設定取得的授權來啟用功能，並在偏好設定中設置廣告層級。請注意，選擇無廣告模式將減少對本軟體的支援，會影響其維護資源及生命周期。`
  - Note: ZH contains additional setup and policy details.
  > Both OK
  - Proposed handling: No JSON change.

- [x] `license.title`
  - EN: `Title`
  - ZH: `頭銜`
  - Note: Confirm whether this means title/heading or personal title.
  > Both OK
  - Proposed handling: No JSON change.

- [x] `message.confirmDeleteAccount`
  - EN: `Delete account {{name}}? This cannot be undone. Associated transactions will be updated.`
  - ZH: `您確定要刪除帳戶 {{name}} 嗎？帳戶刪除後將無法回復, 跟其他帳本內的帳戶相關的帳目轉出或轉入也會被清除(但不會直接影響其他帳本的資料)。`
  - Note: ZH adds cross-book source/destination cleanup details.
  > Both OK
  - Proposed handling: No JSON change.

- [x] `message.confirmDeleteBook`
  - EN: `Delete book {{name}}? This cannot be undone.`
  - ZH: `您確定要刪除帳本 {{name}} 嗎？帳本刪除後將無法回復, 跟其他帳本相關的帳目轉出或轉入也會被清除(但不會直接影響其他帳本的資料)。`
  - Note: ZH adds cross-book source/destination cleanup details.
  > Both OK
  - Proposed handling: No JSON change.

- [x] `message.confirmDeleteTransactionTrash`
  - EN: `Empty trash? This cannot be undone.`
  - ZH: `您確定要清空初帳目垃圾桶嗎？ 帳目刪除後將無法回復。`
  - Note: ZH likely has a typo around `初帳目垃圾桶`.
  > ZH > `您確定要清空帳目垃圾桶嗎？ 帳目刪除後將無法回復。`
  - Proposed handling: Update `zh.json` `message.confirmDeleteTransactionTrash` to `您確定要清空帳目垃圾桶嗎？ 帳目刪除後將無法回復。`.

- [x] `message.confirmRestoreDatabase`
  - EN: `Found a restore file ({{datetime}}). Restore now? This will replace current data.`
  - ZH: `在應用程式的目錄中發現一個資料庫還原檔案(日期: {{datetime}}), 如果您剛有啟動還原步驟, 請按下確定來進行還原, 或是按下取消。不管那個方式, 還原檔將會被刪除, 並進入應用程式。`
  - Note: EN emphasizes replacing current data; ZH emphasizes restore-file flow and deletion.
  > 請提供en的翻譯
  - Proposed handling: Recommend EN `A database restore file was found in the app directory (date: {{datetime}}). If you just started the restore process, press OK to restore, or Cancel to skip it. Either way, the restore file will be deleted and the app will continue.`
  - Decision: Update EN to the proposed wording.

- [x] `message.displayAutoBackupDatabaseInfo`
  - EN: `Show last auto-backup info on Home.`
  - ZH: `當自動備份資料庫功能有啟動, 且曾經完成備份, 將在主頁顯示最後一次備份之資訊。`
  - Note: Home/Main Screen wording should follow `TERMINOLOGY.md`.
  > 我修正了TERMINOLOGY.md, 一律用Home或Home Screen, 繁中都是主頁
  - Proposed handling: Re-check `TERMINOLOGY.md`, then align ZH UI wording only if needed. Current ZH already uses `主頁`; EN `Home` is acceptable.

- [x] `message.displayAutoUploadGDriveInfo`
  - EN: `Show last auto-upload info on Home.`
  - ZH: `當自動上傳功能有啟動, 且曾經完成上傳, 將在主頁顯示最後一次上傳之資訊。`
  - Note: Home/Main Screen wording should follow `TERMINOLOGY.md`.
  > 我修正了TERMINOLOGY.md, 一律用Home或Home Screen, 繁中都是主頁
  - Proposed handling: Re-check `TERMINOLOGY.md`, then align ZH UI wording only if needed. Current ZH already uses `主頁`; EN `Home` is acceptable.

- [x] `message.exportJsonToDirectory`
  - EN: `Export book as JSON. JSON is a portable format, good for backups.`
  - ZH: `選擇帳本並匯出成JSON到外部存取目錄, 並支援自動上傳備份。JSON為純文字資料格式, 相容性較佳, 讓你更容易保留或共享您的資料, 但匯出及匯入需花費時間較久。`
  - Note: ZH adds auto-upload, plain text, sharing, and longer processing time.
  > Both OK
  - Proposed handling: No JSON change.

- [x] `message.googleDriveManagement`
  - EN: `Manage your Google Drive backups. Swipe to delete or download.`
  - ZH: `這是個簡易的管理頁面, 您可以刪除或是下載(在檔案上右滑或右滑會有選項)已經備份在 Google Drive 裡的前99個檔案。您也可以直接使用GoogleDrive的App, 提供有更多功能, 來管理這些檔案。`
  - Note: ZH adds first 99 files and Google Drive App details; `右滑或右滑` likely typo.
  > 加入前99 File的翻譯到EN
  - Proposed handling: Update EN to include the first 99 files. Suggested EN: `Manage the first 99 Google Drive backups. Swipe to delete or download.`
  - Decision: Update EN to `Manage the first 99 Google Drive backups. Swipe to delete or download.`

- [x] `message.quickViewChartHint`
  - EN: `Add charts to Home from $t(screen.balanceChart). Manage in Preferences.`
  - ZH: `您可以在$t(screen.balanceChart)中, 將圖添加到主頁的快速檢視中。此外, 您可以進入喜好設定頁面中的$t(screen.preferencesHomeScreen), 對這項設定進行排序或移除。`
  - Note: Home/Main Screen wording should follow `TERMINOLOGY.md`; ZH is more specific.
  > 我修正了TERMINOLOGY.md, 一律用Home或Home Screen, 繁中都是主頁
  - Proposed handling: Re-check `TERMINOLOGY.md`, then align only if needed. Current ZH already uses `主頁`; EN `Home` is acceptable.

- [x] `message.quickViewSheetHint`
  - EN: `Swipe left on an account in $t(screen.balanceSheet) to add to Home. Manage in Preferences.`
  - ZH: `您可以在$t(screen.balanceSheet)中左滑帳戶, 以將其添加到主頁的快速檢視中。此外, 您可以進入喜好設定頁面中的$t(screen.preferencesHomeScreen), 對這項設定進行排序或移除。`
  - Note: Home/Main Screen wording should follow `TERMINOLOGY.md`; ZH is more specific.
  > 我修正了TERMINOLOGY.md, 一律用Home或Home Screen, 繁中都是主頁
  - Proposed handling: Re-check `TERMINOLOGY.md`, then align only if needed. Current ZH already uses `主頁`; EN `Home` is acceptable.

- [x] `message.transactionBasicModeHint`
  - EN: `Basic mode: Allow unbalanced transfers between different books.`
  - ZH: `當帳本不同時因幣值可能不同, 將不限制轉出跟轉入金額必須相等, 請小心輸入。`
  - Note: ZH omits Basic mode label but adds currency reason.
  > Both OK
  - Proposed handling: No JSON change.

- [x] `message.transactionInitialModeHint`
  - EN: `Initial mode: Set starting balances. No date required.`
  - ZH: `初始化模式為特殊的帳目建立模式, 在開始記帳或新增帳戶時為帳戶設定初始值, 無需設定日期。收入及債務類型帳戶會建立轉出項, 剩下的帳戶類型會建立轉入項。`
  - Note: ZH adds behavior for income/liability vs other account types.
  > 加入對應翻譯到EN
  - Proposed handling: Update EN to include the ZH details. Suggested EN: `Initial mode is a special transaction creation mode for setting starting balances when you start accounting or create an account. No date is required. Income and liability accounts create Source items; other account types create Destination items.`
  - Decision: Update EN to the proposed wording.

- [x] `password.currentMustMatch`
  - EN: `Incorrect current password.`
  - ZH: `當前密碼必須匹配`
  - Note: EN is an error message; ZH is more like a validation rule.
  > ZH: 與當前密碼不相符
  - Proposed handling: Update `zh.json` `password.currentMustMatch` to `與當前密碼不相符`.

- [x] `screen.homeShortcutManagement`
  - EN: `Shortcuts`
  - ZH: `主頁捷徑設定`
  - Note: Confirm whether EN should be `Main Screen Shortcuts`, `Home Shortcuts`, or remain compact.
  > 我修正了TERMINOLOGY.md, 一律用Home或Home Screen, 繁中都是主頁
  - Proposed handling: Re-check `TERMINOLOGY.md`; likely keep ZH as `主頁捷徑設定`. Consider EN `Home Shortcuts` if this label needs more context than `Shortcuts`.
  - Decision: Update EN to `Home Shortcuts`.

- [x] `screen.preferencesHomeScreen`
  - EN: `Home Screen`
  - ZH: `主頁設定`
  - Note: Home/Main Screen wording should follow `TERMINOLOGY.md`.
  > 我修正了TERMINOLOGY.md, 一律用Home或Home Screen, 繁中都是主頁
  - Proposed handling: Re-check `TERMINOLOGY.md`; current EN `Home Screen` and ZH `主頁設定` appear aligned with your updated rule.

- [x] `searchCondition.maxValue`
  - EN: `Max Amount`
  - ZH: `金額小於`
  - Note: EN is field label; ZH is condition wording.
  > Both OK
  - Proposed handling: No JSON change.

- [x] `searchCondition.minValue`
  - EN: `Min Amount`
  - ZH: `金額大於`
  - Note: EN is field label; ZH is condition wording.
  > Both OK
  - Proposed handling: No JSON change.

- [x] `searchCondition.maxValueHint`
  - EN: `Amount <= value`
  - ZH: `提出或轉入金額小於金額(包含)`
  - Note: `提出` likely should be `轉出`; comparison wording may need alignment.
  > ZH > 轉出或轉入金額小於金額(包含)
  - Proposed handling: Update `zh.json` `searchCondition.maxValueHint` to `轉出或轉入金額小於金額(包含)`.

- [x] `searchCondition.minValueHint`
  - EN: `Amount >= value`
  - ZH: `提出或轉入金額大於此金額(包含)`
  - Note: `提出` likely should be `轉出`; comparison wording may need alignment.
  > ZH > 轉出或轉入金額大於金額(包含)
  - Proposed handling: Update `zh.json` `searchCondition.minValueHint` to `轉出或轉入金額大於金額(包含)`.

- [x] `tab.homeMain`
  - EN: `Home`
  - ZH: `主要`
  - Note: Compare with `Main Screen => 主頁` and `Home => 首頁`.
  > ZH : 主頁
  - Proposed handling: Update `zh.json` `tab.homeMain` to `主頁`.

- [x] `title.resetPassword`
  - EN: `Reset Password`
  - ZH: `清除密碼`
  - Note: Reset and clear differ.
  > EN: 本意是把密碼清除，不使用密碼，請建議 (key值不要改)
  - Proposed handling: Recommend EN `Clear Password` for this title. It is short and directly expresses removing the password.
  - Decision: Update EN to `Clear Password`.

- [x] `transaction.initialTransaction`
  - EN: `Initial Balance`
  - ZH: `初始化帳目`
  - Note: EN sounds like a balance value; ZH sounds like a transaction type.
  > EN: 本意是利用一個transaction來作account的初始, 請建議(key值不要改)
  - Proposed handling: Recommend EN `Initial Transaction`. It matches the key intent and `Transaction => 帳目` terminology.
  - Decision: Update EN to `Initial Transaction`.

- [x] `transaction.initReverseValue`
  - EN: `Reverse Sign`
  - ZH: `反向初始金額`
  - Note: Confirm whether this means reverse sign or reverse initial amount direction.
  > EN > reverse initial amount direction 但太長了，要再短些
  - Proposed handling: Recommend EN `Reverse Initial` for compact UI. Alternative: `Reverse Amount` if the UI context already shows this is initial amount.
  - Decision: Update EN to `Reverse Amount`.

- [x] `transaction.noteBeforeBodyHint`
  - EN: `Show notes before transaction details.`
  - ZH: `備註顯示在交易轉出轉入資訊之前`
  - Note: ZH uses `交易`; terminology prefers `帳目`.
  > ZH : 備註顯示在帳目轉出轉入資訊之前
  - Proposed handling: Update `zh.json` `transaction.noteBeforeBodyHint` to `備註顯示在帳目轉出轉入資訊之前`.

- [x] `underConstruction`
  - EN: `Coming Soon`
  - ZH: `建構中`
  - Note: Coming soon and under construction have different tone/status.
  > Both OK
  - Proposed handling: No JSON change.
