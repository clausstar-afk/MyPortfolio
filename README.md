# 🌟 My Portfolio | 互動網頁作品集

歡迎來到 **My Portfolio**！本專案是一個集結了 8 款現代化前端與全端互動式網頁應用、數據視覺化儀表板、生活生產力工具與地理地圖專案的個人作品集展示平台。

全站採用純原生 **HTML5、CSS3 (TailwindCSS) 與 JavaScript (ES6+)** 開發，具備完整的響應式設計（RWD）、深淺色主題切換、關鍵字模糊搜尋、分類標籤動態過濾以及內嵌即時預覽功能。

---

## 📱 首頁功能亮點 (`index.html`)

- **🎨 現代美學設計**：採用深色玻璃擬態（Glassmorphism）、微互動懸浮動畫（Hover Effects）與環境動態光暈（Ambient Mesh Glow）。
- **🌓 深淺色主題切換**：支援 Dark Mode 與 Light Mode 一鍵切換，並自動將使用者偏好儲存至 `localStorage`。
- **🔍 智慧即時搜尋**：支援作品標題、技術標籤（如 `Chart.js`, `Leaflet`, `ECharts` 等）、關鍵字與檔案名稱模糊搜尋。
- **🏷️ 分類動態篩選**：提供「全部作品」、「數據分析」、「實用工具」、「品牌與媒體」、「地理地圖」等多維度分類標籤切換。
- **👁️ 即時視窗預覽 (Live Preview Modal)**：除了直接於新分頁開啟網頁外，亦可在首頁直接呼叫彈出式視窗進行即時體驗與操作。
- **📐 100% RWD 響應式佈局**：完美適配手機、平板、筆電與超寬螢幕裝置。

---

## 📂 收錄作品一覽

| # | 作品名稱 | 檔案名稱 | 類型分類 | 核心技術與特色亮點 |
|:---:|---|---|:---:|---|
| **1** | **顧問銷售績效與營收分析系統** | `Analysis system app.html` | 數據分析 | ECharts 5、SheetJS (Excel 匯入解析)、銷售儀表板、KPI 績效指標與顧問排行榜 |
| **2** | **每日喝開水統計與記錄** | `Daily water intake tracker.html` | 實用工具 | 動態液面波浪視覺、Chart.js 飲水趨勢分析、目標達成慶祝彩帶 (Canvas Confetti) |
| **3** | **台北即時天氣 Dashboard** | `Taipei live weather app.html` | 實用工具 | 串接 Open-Meteo 即時氣象 API、24 小時氣溫折線圖、紫外線指數與多日天氣預報 |
| **4** | **台灣旅遊景點互動地圖** | `Taiwan travel map.html` | 地理地圖 | Leaflet.js 互動地圖、OpenStreetMap、全台熱門景點分類標記與縣市篩選導航 |
| **5** | **雲端同步個人待辦事項** | `Personal task manager.html` | 實用工具 | 暗黑質感介面、通行密碼 (Passcode) 跨裝置雲端同步、標籤分類與優先級管理 |
| **6** | **個人化雲端相簿** | `Personalized photo album.html` | 品牌與媒體 | 現代玻璃擬態、相片智慧標籤過濾、瀑布流排版、全螢幕燈箱檢視與幻燈片輪播 |
| **7** | **自由行需求調查回覆統計** | `My presentation analysis.html` | 數據分析 | PapaParse CSV 資料解析、Chart.js 多維統計圖表、5 款大地色系風格主題即時切換 |
| **8** | **個人履歷與專業亮點展示** | `About me.html` | 品牌與媒體 | 溫潤大地色系美學、核心技能雷達、職涯里程碑與專案成功案例展示 |

---

## 🛠️ 技術棧 (Tech Stack)

- **核心技術**：HTML5, CSS3, JavaScript (ES6+)
- **樣式與圖標**：[Tailwind CSS](https://tailwindcss.com/), [FontAwesome 6.5](https://fontawesome.com/), Google Fonts (Plus Jakarta Sans, Noto Sans TC, JetBrains Mono)
- **數據視覺化**：[Chart.js](https://www.chartjs.org/), [Apache ECharts 5](https://echarts.apache.org/)
- **地理地圖**：[Leaflet.js](https://leafletjs.com/), [OpenStreetMap](https://www.openstreetmap.org/)
- **資料處理**：[PapaParse](https://www.papaparse.com/) (CSV), [SheetJS](https://sheetjs.com/) (XLSX)
- **外部 API**：[Open-Meteo API](https://open-meteo.com/) (即時全球天氣)
- **特效庫**：[Canvas Confetti](https://www.kirilv.com/canvas-confetti/)

---

## 🚀 如何在本機運行

本專案無需任何繁瑣的建置步驟（無需 Node.js 編譯或安裝額外依賴）：

1. **直接開啟**：
   - 雙擊開啟根目錄下的 `index.html` 即可在任一現代瀏覽器中運行。
2. **使用 VS Code Live Server（推薦）**：
   - 在 VS Code 安裝 `Live Server` 擴充套件。
   - 在 `index.html` 上按右鍵並選擇 **"Open with Live Server"** 即可獲得最佳開發與預覽體驗。

---

## 📦 版本控制 (Git) 指令參考

若要在本機初始化版本庫或進行版控提交：

```bash
# 初始化 Git 儲存庫
git init

# 加入所有檔案至暫存區
git add .

# 建立 Commit 存檔
git commit -m "Initial commit: Add MyPortfolio index page and 8 web applications"
```

---

© 2026 My Portfolio. All rights reserved.
