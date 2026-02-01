<div align="center">
  <img src="logo.png" alt="Logo" width="120" height="120" style="border-radius: 24px;">
  <h1>App-Download</h1>
  <p>iFunBox App 下載頁面</p>
  <p>iFunBox App Download Page</p>

  <p>
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
    <img src="https://img.shields.io/badge/MIT-License-blue?style=for-the-badge" alt="MIT License">
  </p>

  ### 🔗 在線預覽 / Live Preview

  **[https://app-download.clozhi.workers.dev](https://app-download.clozhi.workers.dev)**

  ---
</div>

## 簡介

這是一個精美的 iOS 應用下載頁面，使用 HTML5 + CSS3 構建，包含以下特性：

- 🎨 現代簡約的深色主題設計
- ✨ 藍色發光效果和呼吸動畫
- 📱 響應式佈局，適配移動端
- 🚀 平滑的頁面載入動畫
- 🔗 社交鏈接（GitHub、Telegram）

## Introduction

A beautiful iOS app download page built with HTML5 + CSS3, featuring:

- 🎨 Modern dark theme design
- ✨ Blue glow effects with breathing animations
- 📱 Responsive layout for mobile devices
- 🚀 Smooth page load animations
- 🔗 Social links (GitHub, Telegram)

## 使用方法 / Usage

```bash
# Clone the repository
git clone https://github.com/pxbug/App-Download.git
```

1. 直接在瀏覽器中打開 `index.html` 文件
2. 或部署到任何靜態網頁託管服務

1. Open `index.html` directly in your browser
2. Or deploy to any static web hosting service

## Cloudflare Pages 部署 / Deploy to Cloudflare Pages

### 方法一：連接 GitHub 倉庫（推薦）

1. 登入 [Cloudflare Dashboard](https://dash.cloudflare.com/)
2. 進入 **Workers & Pages** → **Create** → **Pages**
3. 選擇 **Connect to Git**，連接你的 GitHub 帳號
4. 選擇 `pxbug/App-Download` 倉庫
5. 配置設置：
   - **Framework preset**: `None` (靜態網站)
   - **Build command**: 填入 `:` 或留空
   - **Build output directory**: 填入 `./` 或留空
6. 點擊 **Deploy**

> ⚠️ **重要**：如果部署失敗，請檢查專案設置中的 **Build command**，確保設置為 `:` 或留空，而不是 `npx wrangler deploy`。

### 方法二：手動上傳

1. 進入 [Cloudflare Dashboard](https://dash.cloudflare.com/)
2. 進入 **Workers & Pages** → **Create** → **Pages**
3. 選擇 **Upload assets**
4. 將項目文件打包上傳
5. 完成部署

### 自定義域名

部署完成後，可以在 **Custom domains** 中添加自定義域名。

### 常見問題 / FAQ

**Q: 部署失敗，出現 `Missing entry-point to Worker script` 錯誤？**
A: 這是因為 Build command 設置不正確。請在 Cloudflare Pages 專案設置中：
1. 前往 **Settings** → **Build & deployments**
2. 將 **Build command** 改為 `:` 或留空
3. 重新觸發部署

**Q: 部署後頁面顯示 404？**
A: 請確保 **Build output directory** 設置為 `./` 或留空。

## 自定義 / Customization

- 修改 `index.html` 中的應用名稱和鏈接
- 替換 `logo.png` 為你的應用圖標
- 調整 CSS 樣式自定義顏色和效果

- Modify app name and links in `index.html`
- Replace `logo.png` with your app icon
- Adjust CSS styles to customize colors and effects

## 許可證 / License

[MIT License](LICENSE)

---

<p align="center">
  Made with ❤️ by <a href="https://github.com/pxbug">pxbug</a>
</p>
