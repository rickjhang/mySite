志騰 (Chih-Teng) | 個人專屬一頁式專業形象與作品網站

從 1 到 100 推進產品成長。

專注於從市場、商業與公司策略的更高視角出發，在符合使用者需求的前提下，取得設計與技術開發的完美平衡。

📖 專案簡介 (Overview)

本專案為 志騰 (Chih-Teng) 的個人專業形象與作品網站原始碼。身為資深產品設計主任 (Senior Product Design Lead) 與產品線 Leader，此專案以現代化、高質感且輕量化的單一檔案（Single-file Web App）形式呈現，完整展示其在 產品策略規劃、UI/UX 設計、團隊領導與流程建構 以及 跨領域生活洞察 的核心競爭力。

同時，專案底層全面導入 現代 SEO / GEO / AEO 架構 與 Schema.org 語意化標籤，確保在搜尋引擎與大型語言模型（LLM）回答引擎中皆具備良好的可檢索性。

✨ 核心特色與內容模組 (Features & Modules)

Hero 形象視覺區塊

漸層動態標題與強烈個人定位標籤（Senior Product Design Lead）。

快速引導至專業領域與聯絡方式的平滑滾動 CTA。

關於我與核心管理職能 (About & Core Competencies)

Roadmap 制定：從定義目標到執行前期研究分析，擬定策略及解決方案，讓團隊以更明確的框架執行規劃。

團隊協作建立：建立內部工作流程與跨部門協作機制，讓設計團隊能有系統地維持高效運作。

專業領域與實踐 (Expertise)

商業與市場宏觀：跳脫純設計視角，從市場趨勢、商業模式推動產品成長歷程。

UI/UX 與開發平衡：理解程式開發邏輯，兼顧極致使用者體驗與工程落地可行性。

系統化流程建構：清晰的時程規劃與溝通框架，降低團隊摩擦成本。

生活與跨界探索 (Lifestyle & Insights)

關注環保、教育、科技與金融等趨勢議題，從日常發掘尚未被解決的真實問題。

結合衝浪、籃球等運動生活風格，保持敏銳思維與跳脫框架的活力。

現代化互動體驗

毛玻璃（Glassmorphism）動態導覽列與平滑錨點滾動（Smooth Scroll）。

跨行動裝置相容的手機側欄選單（Mobile Drawer Menu）。

輕量平滑的進場動畫效果（Fade-in Animations）。

🛠️ 技術架構 (Tech Stack)

核心技術：純原生 HTML5、CSS3、Vanilla JavaScript（零建置工具，開箱即用）。

樣式庫：Tailwind CSS (CDN) - 快速實現現代化原子化樣式與自訂色彩主題。

圖示庫：Lucide Icons - 輕量、現代且風格一致的向量 SVG 圖示。

字體配置：Google Fonts - Noto Sans TC - 清晰舒適的繁體中文字體呈現。

搜尋與 AI 檢索優化：

SEO：包含完整 title、meta description、keywords 與 Open Graph / Twitter Card 社群分享標籤。

AEO / GEO：內嵌符合標準的 application/ld+json (Schema.org Person 結構化資料)，精確定義專業領域與職稱。

無障礙 (a11y)：遵循 HTML5 語意化標籤（<header>, <main>, <section>, <footer>）與 ARIA 屬性支援。

🚀 快速上手 (Getting Started)

此專案為純前端靜態頁面，無需安裝任何 Node.js 環境或建置流程：

1. 本地預覽 (Local Preview)

# 複製專案
git clone https://github.com/your-username/your-repo-name.git

# 進入專案目錄
cd your-repo-name

# 使用預設瀏覽器直接打開 index.html
open index.html # macOS
# 或在 Windows 上直接按兩下 index.html


2. 本地開發伺服器（選用）

若習慣搭配本地伺服器即時重整，可使用 Python 或 Node 的靜態伺服器：

# 使用 Python 3
python -m http.server 8000

# 接著在瀏覽器打開 http://localhost:8000


⚙️ 客製化配置指南 (Customization)

在發布至正式環境（如 GitHub Pages、Vercel 或 Cloudflare Pages）前，建議替換以下內容：

個人基本資訊與社群連結：

將 index.html 中的 https://yourdomain.com/ 替換為您的真實個人網址。

更新頁尾（Footer）的 LinkedIn 網址與聯絡信箱（mailto:）。

社群預覽圖 (OG Image)：

準備一張 1200x630 的個人形象照或網頁截圖，放置於根目錄並命名為 og-image.jpg。

結構化資料 (JSON-LD)：

在 <head> 中的 <script type="application/ld+json"> 內，更新 worksFor、sameAs 等欄位至您的最新資訊。

📄 授權條款 (License)

本專案基於 MIT License 條款開放開源使用。
