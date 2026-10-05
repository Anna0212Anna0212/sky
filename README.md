# ♫ 我的方塊簡譜

純前端網頁（單一 `index.html`），不需要後端或建置。

## 功能
- 每個譜為 5 × 3 格，黑／紅／藍三色
- 快捷鍵：`1` 黑、`2` 紅、`3` 藍、`4`（或 `0`）橡皮擦
- 點擊或拖曳塗色；再點同色格可擦除
- 每列譜數可自訂（預設 6），向下按「＋」新增列，列尾「✕」刪除
- 自動儲存在瀏覽器（localStorage）
- 匯出 PDF / JPG，只輸出譜面

## 部署到 GitHub Pages
1. 在 GitHub 建立新儲存庫（例如 `fangkuai-score`），設為 Public
2. 上傳 `index.html` 與 `README.md`（Add file → Upload files）
3. 到 **Settings → Pages**
4. Source 選 **Deploy from a branch**，Branch 選 `main`、資料夾 `/ (root)`，按 Save
5. 約 1 分鐘後即可開啟：`https://<你的帳號>.github.io/fangkuai-score/`

## 備註
- PDF 匯出使用 jsPDF（cdnjs CDN），需要連網
- 資料存在各人瀏覽器，換裝置不會同步；請用匯出圖檔保存
