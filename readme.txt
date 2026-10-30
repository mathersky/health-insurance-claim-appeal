健保門診醫療費用點數申復清單－自動填寫工具

NHI Outpatient Claim Point Appeal Form Helper

中文使用說明

功能

以單一 HTML 檔案在瀏覽器中讀取核扣明細、補填資料、產生申復清單預覽，並可下載 Word（DOC）或列印／另存 PDF。程式不需要安裝伺服器或額外套件。

開始使用

下載 health-insurance-claim-appeal.html，使用最新版 Chrome 或 Edge 開啟。

按「選擇核扣明細」匯入 .xlsx、.csv 或 .tsv 檔；也可將檔案拖曳到匯入區。

在「機構與送件設定」確認醫事機構代碼、院所名稱、審查科別、負責醫師、地址及日期。匯入資料能判斷的欄位會自動帶入，其餘請自行核對。

在「補填與確認」補上缺漏欄位。黃色欄位是建議補填項目；同一案件的姓名、身分證號及傷病名稱可輸入一次同步帶入。

若已有補填資料，可按「匯入補填資料」載入 Excel／CSV／TSV，工具會依案件識別欄位嘗試合併。請檢查合併結果。

依實際上傳紀錄選擇補傳狀態，確認每筆申復理由。工具不會自行推定尚未補傳的資料已完成補傳。

在「表單預覽」選擇費用月份與聯別，逐頁核對內容；再選「下載 Word（DOC）」或「列印／存成 PDF」。

可使用「下載本次工作備份」另存 JSON，日後按「匯入 JSON 備份」還原；也可按「還原上次自動存檔」。

資料與隱私

HTML 內沒有附帶病患名冊或實際申復案件資料；內嵌表單底圖為空白表格。

程式沒有呼叫外部伺服器的資料上傳程式碼。匯入資料在瀏覽器中處理。

預設自動存檔會把工作資料保存在目前瀏覽器的本機儲存空間。公用或共用電腦使用後，請按「清除自動存檔」。

JSON、CSV、Word、PDF 等下載檔可能含姓名、身分證號及醫療資料，請妥善保管，不要提交到 GitHub、公開網站或不安全的雲端空間。

不要將含真實病患資料的 Excel、CSV、JSON、Word、PDF 或畫面截圖加入這個程式碼儲存庫。

重要提醒

本工具僅協助整理及排版，不會判斷申復是否成立。送件前請依病歷、健保署通知、補傳紀錄及當期規定逐項核對；亦請確認所使用的申復表單版本仍適用。

English Instructions

What it does

This single-file HTML tool reads claim deduction details and supplemental data in your browser, helps complete an appeal list, and provides a form preview. It can download a Word-compatible DOC file or print/save the form as PDF. No server or additional package installation is required.

Getting started

Download health-insurance-claim-appeal.html and open it in a current version of Chrome or Microsoft Edge.

Select Choose claim deduction details to import an .xlsx, .csv, or .tsv file. You may also drag a file into the import area.

Review the institution and submission settings, including institution code, facility name, review department, physician, address, and dates. Verify every value, including fields filled automatically.

In Complete and review, fill in missing information. Yellow fields are suggested items. Name, national ID number, and diagnosis can be synchronized across rows belonging to the same case.

If you already have supplemental data, use Import supplemental data to load an Excel, CSV, or TSV file. The tool attempts to match records using case identifiers; review the merged results carefully.

Set the supplemental-upload status based on the actual record and review each appeal reason. The tool does not assume that an upload was completed.

In Form preview, select the claim month and copy, then check each page. Choose Download Word (DOC) or Print / Save as PDF.

Use Download work backup to save a JSON backup. Later, use Import JSON backup to restore it. You can also restore the previous automatic save.

Data and privacy

The HTML contains no patient roster or real appeal-case data. Its embedded form images are blank templates.

The program contains no code that uploads imported data to an external server. Imported files are processed in the browser.

Automatic saving is enabled by default and stores work data in the current browser's local storage. On a shared computer, select Clear automatic save after use.

Downloaded JSON, CSV, DOC, and PDF files may contain names, national ID numbers, and medical information. Keep them secure. Do not commit them to GitHub, publish them on a website, or place them in an insecure cloud location.

Never add real patient Excel, CSV, JSON, Word, PDF files, or screenshots to this source-code repository.

Important

This tool helps organize and format an appeal; it does not determine whether an appeal is justified. Before submission, verify each item against the medical record, the NHI Administration notice, upload records, and current requirements. Confirm that the form revision in use is still applicable.

Privacy review / 個資檢查

The release HTML was scanned for Taiwan national ID patterns, phone numbers, email addresses, IP addresses, Windows user paths, credential-like strings, and embedded content. No patient roster or patient-specific identifiers were found. The only facility-specific sample placeholders were replaced with generic examples. The embedded form images are blank. This review covers this release file only; users must keep real case data out of the public repository.