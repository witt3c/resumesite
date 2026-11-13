# 陳浚維｜個人履歷網站

靜態 HTML/CSS/JavaScript 製作，無需 Node.js、資料庫或付費主機，可直接部署至 GitHub Pages。

## 部署
1. 登入 GitHub，建立公開 Repository（例如 `resume`）。
2. 將 `index.html`、`styles.css`、`script.js` 上傳至 Repository 根目錄。
3. 前往 **Settings → Pages → Build and deployment**，Source 選 **Deploy from a branch**。
4. Branch 選 `main`，資料夾選 `/(root)`，儲存。
5. 網站網址通常為 `https://你的GitHub帳號.github.io/resume/`；若使用 `帳號.github.io` 作為 Repository 名稱，網址則是 `https://帳號.github.io/`。

## 修改
- 文字、履歷、工作經歷、作品集、證照與聯絡資料：`index.html`
- 顏色、字體、RWD 斷點：`styles.css`
- 手機選單及頁尾年份：`script.js`

## 發布前確認
- 是否要公開電話、Email（公開網站可能被搜尋引擎索引或收到垃圾訊息）
- 最高學歷系所的正式名稱（PDF 僅顯示「電機」）
- 工作日期、公司名稱、職稱、證照名稱與日期
- 工程案例是否取得客戶及雇主公開授權
- 個人照片、作品連結、專業成果數據

## 技術特性
語意化 HTML、行動版選單、鍵盤可操作、減少動態效果偏好、SEO 基礎標籤、響應式格線。無外部字型或追蹤服務。
