# 小林攝影工作室｜作品集網站

單頁式攝影師作品集，使用原生 HTML、內嵌 CSS 與 JavaScript，適合 GitHub Pages 或 Vercel 靜態部署。

## 專案結構

```text
lin-photo-portfolio/
├── index.html
├── images/
│   └── README.md
└── README.md
```

## 上線前請先完成

1. 將 `images/README.md` 中列出的圖片放進 `images/` 資料夾，檔名需完全相同。
2. 將 `hello@linphotography.example` 與 `@lin.photography.example` 換成真實聯絡方式。
3. 調整方案價格、照片張數、交件時間與加選規則。
4. 如果要直接在網站接收表單資料，請串接 Formspree 等表單服務；目前表單會用 `mailto:` 開啟訪客的電子郵件程式，不會將資料存進伺服器。
5. 若正式部署，建議補上實際網域的 Open Graph 圖片、favicon 與 sitemap。

## GitHub 與 Vercel 部署

- GitHub：建立 repository，將 `index.html`、`images/`、README 一起上傳。
- Vercel：匯入該 GitHub repository，Framework Preset 選 `Other`，Build Command 留空，Output Directory 使用 `.`，部署即可。
- 不需要 Node.js、npm 或 build step。

## 圖片

請使用自行拍攝或具備適當授權的免費圖庫圖片，下載後依 `images/README.md` 的檔名放置。請保留圖片來源與授權紀錄，尤其是人物肖像用途。
