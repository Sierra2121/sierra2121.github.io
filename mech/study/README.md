# 知識迴路｜個人學習室

最新版 GitHub Pages 可部署版本，使用原網站程式碼改編。深藍／霧紫配色。

## 部署
1. 本版本整合至為什麼研究室 Repository 的 `knowledge-loop/` 子資料夾。
2. 保留 `index.html`、`lab.js` 在同一個資料夾。
3. 使用研究室原有 GitHub Pages 設定，根目錄的 `.nojekyll` 已包含於整合包。
4. 開啟 `https://sierra2121.github.io/knowledge-loop/`。

## 檔案
- index.html：介面、樣式、筆記、題庫、測驗、錯題、間隔複習、匯入匯出、記憶卡，內建 22 道原題（另有原示範題）。
- lab.js：15 個互動實驗（火車、繼電器、整流、PT100、熱電偶、歐姆定律、萬用電表、電晶體、二極體、步進馬達、PLC、a/b接點、油壓、順序閥、氣壓缸）。
- 根目錄 .nojekyll：直接提供靜態網站檔案。

## 資料保存、移轉
GitHub Pages 是靜態網站，使用 localStorage，沒有 ChatGPT 帳號登入或雲端同步服務。原網站的資料管理頁可下載 JSON 備份，再到新網站匯入，匯入會取代當前本機資料。不要把包含個人學習紀錄的備份上傳到公開 GitHub Repository。

所有教學模型均為簡化示意，不是實際接線或安全驗證工具。
