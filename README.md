# 👋 Hi, I'm Zhen-Wei Wu (吳振瑋)

**Data Scientist | Statistics & Machine Learning Enthusiast** *M.S. in Statistics and Data Science, National Tsing Hua University*

我是一位具備紮實統計背景的資料科學研究生，擅長將統計邏輯與機器學習模型（Deep Learning, Ensemble Learning）結合，解決現實世界中的複雜問題。我擁有豐富的產學合作與數據競賽實戰經驗，特別是在**時間序列預測**與**高維度特徵工程**領域有深入的研究。

---

## 🚀 *Key Highlights | 核心優勢*

- 🏢 **產學合作**：與 **聯華電子 (UMC)** 合作開發預測模型，準確率達 80%。
- 🏆 **競賽實績**：永豐銀行 AI GO 飆股預測 **Top 3%**、AI CUP 桌球智慧球拍分類 **Top 5%**。
- 📊 **專業背景**：清大統計所畢業，兼具深厚統計理論與大型數據集（萬級變數）處理能力。

---

## 🤝 *Professional Experience | 專業經驗*

### 🔍 *聯華電子 (UMC) 產學合作專案 | Stock Price Prediction*
*2024 - 團隊核心成員*
- **技術架構**：LSTM / GARCH Model / Time Series Analysis
- **貢獻描述**：
  - 設計並實作 **LSTM 預測模型**，結合 Log-return 與 GARCH 波動度估計，建構 **95% 預測信賴區間**。
  - 成功將次日股價漲跌預測準確率提升至 **80%**，覆蓋率達 98%。
  - 負責技術成果彙整，獨立向管理層與技術團隊進行簡報，獲得高度肯定。

---

## 🎯 *Competition Achievements | 數據競賽*

### 🌟 *永豐銀行 AI GO 飆股預測競賽 | Top 3%*
**Role: Team Leader (團隊隊長)**
- **多樣性整合策略 (Diversity-Driven Stacking)**：主導開發一套標準化 SOP，透過**異質化配置（Heterogeneous Configuration）**——從演算法種類、特徵子集、到損失函數的差異化設計，確保基礎模型間具備強互補性，有效解決 Stacking 常見的同質性過高與過擬合風險。
- **高維特徵萃取**：結合多種特徵重要性指標（XGB, Permutation Importance）取其交集，成功將萬級維度精煉至 23 個關鍵特徵，極大化運算效率。
- **最終成果**：帶領團隊達成前 3% 佳績。

### ✨ *AI CUP 桌球智慧球拍分類 | Top 5%*
**Role: Team Leader (團隊隊長)**
- **目標函數優化 Voting (Metric-Oriented Voting)**：針對競賽特定的評分機制開發**客製化加權投票規則**，透過數學邏輯將模型預測結果與積分算法最佳化對接，使最終成效優於傳統準確率模型。
- **跨領域溝通與協作**：帶領包含非統計背景成員的跨領域團隊，將複雜的訊號處理（FFT, 小波變換）與統計分析結果轉譯為團隊共識。
- **最終成果**：穩定分類高頻感測數據，排名公開組前 5%。


---

# 🤖 AI-Powered News Orchestrator
> **基於 n8n 與 Gemini 的自動化技術情報分析系統**

本專案透過 n8n 低代碼平台編排自動化管線，實現從 RSS 新聞抓取、LLM 語義摘要到即時訊息推播的完整鏈路。

## 🌟 技術特點
- **數據預處理優化**：利用 JavaScript `.map()` 函數將複雜的 XML 物件轉換為純文字列表，有效解決 LLM 無法直接解析 `[object Object]` 的問題。
- **Agentic Workflow**：整合 Gemini 1.5 系列模型，透過動態 Prompt 實現高品質的內容精選與摘要。
- **高可用性設計**：針對 API 頻率限制 (Quota) 導入自動重試機制，確保系統在不穩定網路環境下的魯棒性。

## 🛠️ 工作流架構
1. **Manual/Schedule Trigger**：啟動自動化任務。
2. **HTTP Request**：從 Google News RSS 獲取最新 AI 技術新聞。
3. **XML Parser**：將原始 XML 轉換為結構化 JSON。
4. **Gemini AI Agent**：進行語義分析、精選 Top 2 重要新聞。
5. **LINE Messaging API**：將處理後的結果即時推送至行動裝置。

---

## 🛠 *Skills & Tools | 技術棧*

| Category | Skills |
| :--- | :--- |
| **Languages** | Python (Pandas, Scikit-learn), **SQL (Basic Syntax & Joins)**, R |
| **AI & Automation** | **LLM Application (Gemini)**, **n8n Workflow**, **LINE API** |
| **ML / DL** | LSTM, XGBoost, Random Forest, Stacking, Ensemble Learning |
| **Statistics** | Time Series Analysis, Multivariate Analysis, Financial Mathematics |
| **Data Viz & Tools** | **Power BI**, Git |

---

## 📂 *Selected Projects | 精選專案回顧*

| Project | Key Technologies | Link |
| :--- | :--- | :--- |
| **Stock Price Forecasting** | LSTM, GARCH, Confidence Interval | [🔗 GitHub](https://github.com/ILaskira/Stock-Price-Prediction) |
| **SinoPac Soaring Stock** | High-dim Feature Selection, Stacking | [🔗 GitHub](https://github.com/ILaskira/Soaring-Stock-Prediction-Challenge) |
| **Table Tennis Classification** | FFT, Wavelet, XGBoost Ensemble | [🔗 GitHub](https://github.com/ILaskira/Table-Tennis-Smart-Racket-Classification) |
| **League of Legends Win Prediction** | Feature Engineering, Classification | [🔗 GitHub](https://github.com/ILaskira/LOL-How-to-Win-.github.io) |

---


## 📬 *Contact | 聯絡資訊*

- **Email**: [a10155105105@gmail.com](mailto:a10155105105@gmail.com)
- **GitHub**: [@ILaskira](https://github.com/ILaskira)
- **Resume**: [📄 下載完整中文履歷 (PDF)](./吳振瑋數據履歷_1.pdf)
