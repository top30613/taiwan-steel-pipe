# 台灣精工鋼管｜Taiwan Precision Steel Pipe

SEO 優化靜態網站（繁中 + 國際關鍵字）  
核心賣點：**從材料到製程的穩定與客製化服務**

**GitHub Repo**: https://github.com/top30613/taiwan-steel-pipe

---

## 一鍵 Git 部署流程（推薦）

本專案已準備好給三大平台直接從 Git 部署，無需手動上傳檔案。

### 1. Vercel（最快）
1. 前往 https://vercel.com/new
2. Import Git Repository → 選擇 `top30613/taiwan-steel-pipe`
3. Framework Preset 選 **Other**（或留空）
4. 直接 Deploy
5. 完成後網址類似：`https://taiwan-steel-pipe.vercel.app`

已包含 `vercel.json`（安全標頭 + cleanUrls）。

### 2. Netlify
1. 前往 https://app.netlify.com/start
2. Import from Git → 選擇此倉庫
3. Build command 留空，Publish directory 填 `.`
4. Deploy site
5. 網址會是：`https://taiwan-steel-pipe.netlify.app`

已包含 `netlify.toml`。

### 3. Cloudflare Pages
1. 前往 Cloudflare Dashboard → Workers & Pages → Create → Pages
2. Connect to Git → 授權 GitHub → 選擇 `taiwan-steel-pipe`
3. Build settings：Framework preset = None，Build command 留空，Output directory = `/`
4. Save and Deploy
5. 網址會是：`https://taiwan-steel-pipe.pages.dev`

之後只要 `git push` 到 main，三個平台都會自動更新。

---

## 專案結構

```
.
├── index.html          # 首頁（SEO 主頁）
├── about.html          # 關於我們
├── products.html       # 產品規格
├── contact.html        # 聯絡詢價
├── css/style.css       # 樣式
├── robots.txt
├── sitemap.xml
├── vercel.json         # Vercel 設定
├── netlify.toml        # Netlify 設定
└── README.md
```

## SEO 重點已完成
- LocalBusiness Schema（地緣搜尋）
- 繁中 + 英文關鍵字
- Geo meta（新北市新莊區）
- Canonical / Open Graph
- NAP 一致性
- 行動版友善

## 後續建議
1. 在 Google Search Console 提交網站
2. 建立 Google 商家檔案（同一地址電話）
3. 之後可綁定自訂網域（.com 或 .com.tw）
4. 表單可改接 Formspree / Netlify Forms / Cloudflare Forms

---
© 2026 台灣精工鋼管有限公司
