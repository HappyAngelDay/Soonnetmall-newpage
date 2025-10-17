# Soonnetmall New Page

簡介（靜態單頁網站）

- 純 HTML + CSS 製作的著陸頁（Landing Page），無任何打包、框架或後端，相容性高、可直接部署。
- 主檔案：`soonnetmall-information.html`（頁面結構）；樣式：`newpage-style.css`；圖片素材在 `photo/`。

內容概覽（區塊說明）

- 導覽列：品牌 Logo、購物車/登入連結。
- Hero 區：標語與話題標籤，三個搜尋 Pill（AI 人臉辨識、號碼布搜尋、高清下載）及按鈕 CTA。
- 功能亮點（Ribbon）：三張功能卡，包含 AI 徽章與提示泡泡文字。
- 操作步驟（Steps）：三步驟流程搭配示意圖與行動按鈕。
- 回憶集（Dark Gallery）：5 張拍立得卡片，桌機水平排列；手機採自適應排版（3-2）並避免溢出。
- 服務 CTA 區（Bottom CTA）：兩個行銷 Box（攝手招募、加入會員），含圖文與行動按鈕。
- 常見問題（FAQ）：可展開/收合的問答清單。
- 頁尾（Footer）：版權與連結。

目錄結構

- `soonnetmall-information.html` — 主頁面 (HTML)
- `newpage-style.css` — 樣式表 (CSS)
- `photo/` — 圖片與素材
- `.vscode/` — 開發環境偏好設定（非必需）

快速開始

- 直接以瀏覽器開啟 `soonnetmall-information.html` 預覽。
- 建議 VS Code + Live Server 外掛，以獲得即時重新整理。

開發與編輯

- 顏色與基礎變數位於 `:root` CSS 變數，可統一調整品牌色調。
- 版面與響應式：主要使用 CSS Grid/Flex；手機規則集中在 `@media (max-width: 960px)` 與 `@media (max-width: 600px)`。
- 圖片替換：把新圖放入 `photo/`，並更新 HTML 內的 `src` 路徑與 `alt` 文案。
- SEO：可調整 HTML `<head>` 內的 `<title>`、`meta description` 與 Open Graph 內容。

部署（GitHub Pages）

1. 到 Repository：Settings → Pages。
2. Build and deployment → Source 選「Deploy from a branch」。
3. Branch 選 `main`，Folder 選 `/ (root)` → Save。
4. 等候 GitHub Pages 發布完成，網址將顯示於同頁面。

瀏覽器支援

- 以現代瀏覽器（Chrome/Edge/Firefox/Safari 最新版）為目標；IE 不支援。

版本控制建議

- 可加入 `.gitignore` 忽略系統檔（如 `Thumbs.db`）。

問題回報

- 如需回報問題或提出建議，請使用 GitHub Issues。
