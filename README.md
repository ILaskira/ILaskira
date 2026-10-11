# 👋 Hi, I'm Zhen-Wei Wu (吳振瑋)

**Data Scientist | Statistics & Machine Learning Enthusiast**  
*M.S. in Statistics and Data Science, National Tsing Hua University*

我是一位具備紮實統計背景的資料科學研究者，擅長將統計方法與機器學習模型（Deep Learning、Ensemble Learning、Multi-Task Learning）結合，解決現實世界中的複雜問題。

擁有產學合作、金融資料建模與數據競賽實戰經驗，研究與實作領域涵蓋**時間序列預測、高維度特徵工程、自然語言處理（NLP）、深度學習及模型集成策略**。重視從資料前處理、特徵工程、模型設計到效能評估的完整建模流程，致力於將數據分析與人工智慧技術轉化為實際應用價值。

---

## 🚀 Key Highlights | 核心優勢

- 🏢 **產學合作**：與 **聯華電子（UMC）** 合作開發股價預測模型，次日漲跌方向預測準確率達 **80%**，預測區間覆蓋率達 98%。
- 🏆 **競賽實績**：永豐銀行 AI GO 飆股預測 **Top 3%**、AI CUP 桌球智慧球拍分類 **Top 5%**、ESG 承諾與證據分析競賽 **Top 19%（65/344）**。
- 🧠 **機器學習與深度學習**：具備 LSTM、GARCH、XGBoost、Stacking、Transformer 與 Multi-Task Learning 的模型開發經驗。
- 📊 **高維度資料分析**：能處理萬級特徵資料，結合特徵重要性分析、特徵選擇與集成學習提升建模效率。
- 🔍 **NLP 與文本理解**：使用 MacBERT 與 PyTorch 建構多任務文本分類模型，整合輔助式監督學習與規則式後處理。

---

## 🤝 Professional Experience | 專業經驗

### 🔍 聯華電子（UMC）產學合作專案 | Stock Price Prediction

*2024 | 團隊核心成員*

**Technologies: LSTM, GARCH, Time Series Analysis, Python**

- **深度學習時間序列建模（Deep Learning for Time Series）**：設計並實作 LSTM 股價預測模型，結合歷史價格、Log-return 與時間序列特性，分析股價走勢及報酬率變動。
- **波動度建模與風險區間估計（Volatility Modeling）**：整合 GARCH 模型估計市場波動度，建構 **95% 預測區間**，同時考量股價變動方向與預測不確定性。
- **模型預測成果（Predictive Performance）**：成功將次日股價漲跌預測準確率提升至 **80%**，預測區間覆蓋率達 **98%**。
- **技術成果展示（Technical Presentation）**：負責模型成果彙整與技術簡報，獨立向管理層及技術團隊報告模型設計、實驗結果與應用價值。

---

## 🎯 Competition Achievements | 數據競賽

### 🌟 永豐銀行 AI GO 飆股預測競賽 | Top 3%

**Role: Team Leader（團隊隊長）**

**Technologies: XGBoost, Stacking, Ensemble Learning, Feature Selection**

- **多樣性整合策略（Diversity-Driven Stacking）**：主導開發標準化模型訓練 SOP，透過異質化配置（Heterogeneous Configuration），從演算法種類、特徵子集到損失函數進行差異化設計，提高基礎模型的互補性，降低 Stacking 同質性過高與過擬合的風險。
- **高維度特徵選擇（High-Dimensional Feature Selection）**：結合 XGBoost Feature Importance 與 Permutation Importance，交叉篩選重要變數，將萬級維度精煉至 **23 個關鍵特徵**，降低模型複雜度並提升運算效率。
- **模型集成與策略優化（Ensemble Optimization）**：整合多種基礎學習器與特徵配置，透過模型差異性提高整體預測穩定度。
- **最終成果**：帶領團隊取得 **Top 3%** 佳績。

**🔗 [View Project on GitHub](https://github.com/ILaskira/Soaring-Stock-Prediction-Challenge)**

### ✨ AI CUP 桌球智慧球拍分類 | Top 5%

**Role: Team Leader（團隊隊長）**

**Technologies: FFT, Wavelet Transform, XGBoost, Ensemble Learning**

- **感測訊號特徵工程（Sensor Signal Feature Engineering）**：利用快速傅立葉轉換（FFT）與小波轉換（Wavelet Transform），從高頻感測器訊號中萃取時域與頻域特徵，建立機器學習分類模型。
- **目標函數優化投票（Metric-Oriented Voting）**：針對競賽特定評分機制，設計客製化加權投票策略，透過數學邏輯將模型預測結果與官方計分方式對接，使最終成效優於傳統準確率導向的集成方式。
- **跨領域溝通與協作（Cross-Disciplinary Collaboration）**：帶領包含非統計背景成員的團隊，將訊號處理、機器學習與統計分析結果轉換為可理解的技術共識。
- **最終成果**：於公開組取得 **Top 5%** 佳績。

**🔗 [View Project on GitHub](https://github.com/ILaskira/Table-Tennis-Smart-Racket-Classification)**

### 🌱 ESG Commitment & Evidence Analysis | Top 19%

**Rank: 65 / 344 Teams**

**Technologies: PyTorch, MacBERT, Transformer, Multi-Task Learning, NLP, Data Augmentation**

- **多任務深度學習架構（Multi-Task MacBERT）**：基於預訓練中文語言模型 `hfl/chinese-macbert-base`，設計 Shared Transformer Encoder 與四個獨立 Classification Heads，同時完成 ESG 承諾識別（Commitment Classification）、支持證據判斷（Evidence Identification）、證據清晰度分類（Clarity Classification）及驗證時間推論（Timeline Classification）。
- **輔助式監督學習（Auxiliary Supervision）**：除四個主要分類任務外，額外設計 Promise/Evidence Span Detection 與 Token-Level Keyword Classification，將承諾與證據標註語句轉換為 Token-Level 監督訊號，協助模型學習文本中的關鍵語意區域。
- **資料增強與類別不平衡處理（Data Augmentation & Class Imbalance）**：透過句子重排、輕量語句刪除、ESG 同義詞替換與標點變化等策略，將 **800 筆原始訓練樣本擴增至 1,210 筆**，並整合 Class-Weighted Cross-Entropy Loss，降低少數類別對模型訓練的影響。
- **時間語意特徵工程（Temporal Feature Engineering）**：從 ESG 報告文本中萃取年份、短中長期規劃、完成狀態與數值特徵等訊號，輔助模型判斷承諾的預期驗證時間。
- **規則式後處理（Rule-Based Post-Processing）**：依據承諾、證據、清晰度與驗證時間之間的邏輯相依性，設計預測一致性修正機制，並以官方加權 Macro-F1 比較原始預測與不同後處理策略。
- **模型評估（Model Evaluation）**：依據官方四項任務權重（20%、30%、35%、15%）計算 Weighted Macro-F1，Notebook 已記錄的最高驗證分數為 **0.61856**。
- **最終成果**：於 **344 支參賽隊伍中排名第 65 名（Top 19%）**，展現中文 NLP、多任務學習、深度學習模型設計及非結構化文本分析能力。

---

## 🤖 AI-Powered News Orchestrator | AI 新聞自動化系統

> **基於 n8n 與 Gemini 的自動化技術情報分析系統**

本專案使用 n8n 低代碼自動化平台建立 AI 新聞處理工作流，整合 RSS 新聞擷取、資料結構化、LLM 語意摘要與 LINE 即時訊息推播，實現端到端的技術新聞自動化分析。

### 🌟 技術特點

- **自動化資料管線（Automated Data Pipeline）**：整合 Google News RSS、HTTP Request 與 XML Parser，自動取得並處理最新 AI 技術新聞。
- **資料前處理優化（Data Preprocessing）**：使用 JavaScript `.map()` 將複雜 XML/JSON 物件轉換為模型可處理的純文字資料，避免 LLM 接收到 `[object Object]` 等非預期內容。
- **LLM 工作流整合（LLM Workflow Integration）**：串接 Gemini 1.5 系列模型，透過動態 Prompt 執行語意分析、新聞重要性篩選與重點摘要。
- **高可用性設計（Reliability Engineering）**：針對 API Quota 與請求失敗情況導入自動重試機制，提高自動化流程的穩定性。
- **訊息推播整合（Messaging Integration）**：透過 LINE Messaging API 即時推送篩選後的新聞摘要。

### 🛠️ 工作流架構

1. **Manual / Schedule Trigger**：啟動自動化任務。
2. **HTTP Request**：從 Google News RSS 取得新聞資料。
3. **XML Parser**：將 XML 轉換為結構化 JSON。
4. **Data Transformation**：清理新聞文字及格式。
5. **Gemini AI Agent**：進行語意分析並精選 Top 2 重要新聞。
6. **LINE Messaging API**：將結果推送至行動裝置。

---

## 🛠 Skills & Tools | 技術棧

| Category | Skills |
| :--- | :--- |
| **Programming Languages** | Python, SQL, R, JavaScript |
| **Data Processing** | Pandas, NumPy, Scikit-learn, Data Cleaning, Feature Engineering |
| **Machine Learning** | XGBoost, Random Forest, Stacking, Ensemble Learning, Feature Selection |
| **Deep Learning** | PyTorch, LSTM, Transformer, BERT, MacBERT, Multi-Task Learning |
| **Natural Language Processing** | Text Classification, Tokenization, Span Detection, Data Augmentation |
| **Statistics & Mathematics** | Time Series Analysis, GARCH, Multivariate Analysis, Financial Mathematics |
| **Model Evaluation & Optimization** | Cross-Validation, Macro-F1, Class-Weighted Loss, Model Selection |
| **AI & Automation** | LLM Applications, Gemini API, n8n Workflow, LINE Messaging API |
| **Data Visualization & Tools** | Power BI, Git, Jupyter Notebook, Google Colab |

---

## 📂 Selected Projects | 精選專案回顧

| Project | Key Technologies | Link |
| :--- | :--- | :--- |
| **Stock Price Forecasting (UMC)** | LSTM, GARCH, Prediction Interval | [🔗 GitHub](https://github.com/ILaskira/Stock-Price-Prediction) |
| **SinoPac Soaring Stock Prediction** | High-Dimensional Feature Selection, Stacking | [🔗 GitHub](https://github.com/ILaskira/Soaring-Stock-Prediction-Challenge) |
| **AI CUP Table Tennis Classification** | FFT, Wavelet, XGBoost Ensemble | [🔗 GitHub](https://github.com/ILaskira/Table-Tennis-Smart-Racket-Classification) |
| **ESG Commitment & Evidence Analysis** | MacBERT, PyTorch, Multi-Task NLP | Top 19% |
| **League of Legends Win Prediction** | Feature Engineering, Classification | [🔗 GitHub](https://github.com/ILaskira/LOL-How-to-Win-.github.io) |

---

## 📬 Contact | 聯絡資訊

- **Email**: [a10155105105@gmail.com](mailto:a10155105105@gmail.com)
- **GitHub**: [@ILaskira](https://github.com/ILaskira)
- **Resume**: [📄 下載完整中文履歷 (PDF)](./吳振瑋數據履歷_1.pdf)
