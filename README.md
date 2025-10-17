# Soonnetmall New Page

簡介

- 靜態單頁網站，包含 HTML、CSS 與圖片資源。
- 主要檔案為 `soonnetmall-information.html`，對應樣式為 `newpage-style.css`，圖片位於 `photo/` 目錄。

目錄結構

- `soonnetmall-information.html` — 主頁面 (HTML)
- `newpage-style.css` — 樣式表 (CSS)
- `photo/` — 圖片與素材
- `.vscode/` — 開發環境偏好設定 (非必需)

快速開始

- 直接在檔案總管中雙擊打開 `soonnetmall-information.html`，或於瀏覽器以檔案路徑開啟即可預覽。
- 推薦在 VS Code 安裝 Live Server 外掛，以利即時預覽與開發。

開發與編輯

- 使用任何文字編輯器即可（建議 VS Code）。
- 如需調整版面或樣式，請修改 `newpage-style.css`。
- 新增或替換圖片資源，請放入 `photo/` 目錄並於 HTML 內更新引用路徑。

相依與建置

- 本專案無需建置流程與外部套件，為純前端靜態頁面。

部署（GitHub Pages）

1. 前往 GitHub Repository：Settings → Pages。
2. 在「Build and deployment」將 Source 設為「Deploy from a branch」。
3. Branch 選擇 `main`，資料夾選擇 `/ (root)`，點選 Save。
4. 等待 GitHub Pages 發布完成，網址會顯示在同一頁面。

版本控制建議

- 建議加入 `.gitignore` 忽略系統檔（例如 `Thumbs.db`）。

問題回報

- 若需回報問題或提出建議，請使用 GitHub Issues。

