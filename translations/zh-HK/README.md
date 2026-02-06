[![GitHub license](https://img.shields.io/github/license/microsoft/ML-For-Beginners.svg)](https://github.com/microsoft/ML-For-Beginners/blob/master/LICENSE)
[![GitHub contributors](https://img.shields.io/github/contributors/microsoft/ML-For-Beginners.svg)](https://GitHub.com/microsoft/ML-For-Beginners/graphs/contributors/)
[![GitHub issues](https://img.shields.io/github/issues/microsoft/ML-For-Beginners.svg)](https://GitHub.com/microsoft/ML-For-Beginners/issues/)
[![GitHub pull-requests](https://img.shields.io/github/issues-pr/microsoft/ML-For-Beginners.svg)](https://GitHub.com/microsoft/ML-For-Beginners/pulls/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/ML-For-Beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/ML-For-Beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/ML-For-Beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/ML-For-Beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/ML-For-Beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/ML-For-Beginners/stargazers/)

### 🌐 多語言支援

#### 透過 GitHub Action 支援（自動化且持續更新）

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[阿拉伯文](../ar/README.md) | [孟加拉文](../bn/README.md) | [保加利亞文](../bg/README.md) | [緬甸文 (Myanmar)](../my/README.md) | [中文 (簡體)](../zh-CN/README.md) | [中文 (繁體, 香港)](./README.md) | [中文 (繁體, 澳門)](../zh-MO/README.md) | [中文 (繁體, 台灣)](../zh-TW/README.md) | [克羅地亞文](../hr/README.md) | [捷克文](../cs/README.md) | [丹麥文](../da/README.md) | [荷蘭文](../nl/README.md) | [愛沙尼亞文](../et/README.md) | [芬蘭文](../fi/README.md) | [法文](../fr/README.md) | [德文](../de/README.md) | [希臘文](../el/README.md) | [希伯來文](../he/README.md) | [印地文](../hi/README.md) | [匈牙利文](../hu/README.md) | [印尼語](../id/README.md) | [義大利文](../it/README.md) | [日文](../ja/README.md) | [坎納達文](../kn/README.md) | [韓文](../ko/README.md) | [立陶宛文](../lt/README.md) | [馬來文](../ms/README.md) | [馬拉雅拉姆文](../ml/README.md) | [馬拉地文](../mr/README.md) | [尼泊爾文](../ne/README.md) | [奈及利亞皮欽語](../pcm/README.md) | [挪威文](../no/README.md) | [波斯文 (法爾西)](../fa/README.md) | [波蘭文](../pl/README.md) | [葡萄牙文 (巴西)](../pt-BR/README.md) | [葡萄牙文 (葡萄牙)](../pt-PT/README.md) | [旁遮普文 (古魯穆奇體)](../pa/README.md) | [羅馬尼亞文](../ro/README.md) | [俄文](../ru/README.md) | [塞爾維亞文 (西里爾字母)](../sr/README.md) | [斯洛伐克文](../sk/README.md) | [斯洛文尼亞文](../sl/README.md) | [西班牙文](../es/README.md) | [斯瓦希里文](../sw/README.md) | [瑞典文](../sv/README.md) | [塔加洛語 (菲律賓語)](../tl/README.md) | [泰米爾文](../ta/README.md) | [泰盧固文](../te/README.md) | [泰文](../th/README.md) | [土耳其文](../tr/README.md) | [烏克蘭文](../uk/README.md) | [烏爾都文](../ur/README.md) | [越南文](../vi/README.md)

> **想要本地端複製？**

> 此儲存庫包括 50 多種語言的翻譯，會大幅增加下載大小。若欲不含翻譯直接下載，可使用稀疏檢出：
> ```bash
> git clone --filter=blob:none --sparse https://github.com/microsoft/ML-For-Beginners.git
> cd ML-For-Beginners
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> 如此你能以更快的下載速度獲得完成課程所需的所有內容。
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

#### 加入我們的社群

[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

我們在 Discord 上持續舉辦 AI 系列學習活動，詳情與加入請見 [Learn with AI Series](https://aka.ms/learnwithai/discord)，時間為 2025 年 9 月 18 日至 30 日。你將學到如何使用 GitHub Copilot 進行資料科學的秘訣與技巧。

![Learn with AI 系列](../../translated_images/zh-HK/3.9b58fd8d6c373c20.webp)

# 初學者機器學習課程大綱

> 🌍 帶你環遊世界，以世界文化探索機器學習 🌍

微軟的 Cloud Advocates 高興地推出一個為期 12 週、包含 26 節課的**機器學習**課程。在本課程中，你將學習被稱為**經典機器學習**的方法，主要使用 Scikit-learn 函式庫，避免使用深度學習（深度學習已收錄於我們的 [AI for Beginners 課程](https://aka.ms/ai4beginners)）。你也可以搭配我們的['資料科學初學者課程'](https://aka.ms/ds4beginners)一起學習！

與我們一同環遊世界，將這些經典技術運用於來自世界各地的資料。每堂課包含課前與課後測驗、書面指引、解答、作業等內容。我們採用專案導向的教學法，讓你在建構中學習，這是經驗證的學習效果。

**✍️ 真誠感謝作者** Jen Looper、Stephen Howell、Francesca Lazzeri、Tomomi Imura、Cassie Breviu、Dmitry Soshnikov、Chris Noring、Anirban Mukherjee、Ornella Altunyan、Ruth Yakubu 及 Amy Boyd

**🎨 謝謝插畫團隊** Tomomi Imura、Dasani Madipalli 與 Jen Looper

**🙏 特別感謝 🙏 微軟學生大使作者、審閱人與內容貢獻者**，特別是 Rishit Dagli、Muhammad Sakib Khan Inan、Rohan Raj、Alexandru Petrescu、Abhishek Jaiswal、Nawrin Tabassum、Ioan Samuila 及 Snigdha Agarwal

**🤩 額外感謝微軟學生大使 Eric Wanjau、Jasleen Sondhi 和 Vidushi Gupta 為我們的 R 課程付出！**

# 開始使用

請依照下列步驟：
1. **分叉儲存庫**：點擊頁面右上角的「Fork」按鈕。
2. **克隆儲存庫**：  `git clone https://github.com/microsoft/ML-For-Beginners.git`

> [在我們的 Microsoft Learn 集合中找到本課程的所有額外資源](https://learn.microsoft.com/en-us/collections/qrqzamz1nn2wx3?WT.mc_id=academic-77952-bethanycheum)

> 🔧 **需要協助？** 請參考我們的 [疑難排解指引](TROUBLESHOOTING.md)，協助解決安裝、設置與執行課程的常見問題。

**[學生專區](https://aka.ms/student-page)**，使用此課程時，請將整個儲存庫分叉至自己的 GitHub 帳號，並自行或與組員一起完成練習：

- 從課前測驗開始。
- 閱讀課程內容，完成活動，於每個知識點處停下思考。
- 試著根據課程內容自行構建專案，而非直接執行解答程式碼；不過，每個以專案為導向的課程中，`/solution` 資料夾都有提供解答程式碼。
- 進行課後測驗。
- 完成挑戰題。
- 完成作業。
- 完成一組課程後，請訪問[討論板](https://github.com/microsoft/ML-For-Beginners/discussions)，透過填寫適當的 PAT 評量表來「大聲學習」。PAT 指「進度評估工具（Progress Assessment Tool）」，是一份你填寫以促進學習的評量表。你也可以對他人的 PAT 回應，一同交流學習。

> 若想進一步學習，我們推薦以下[Microsoft Learn](https://docs.microsoft.com/en-us/users/jenlooper-2911/collections/k7o7tg1gp306q4?WT.mc_id=academic-77952-leestott)模組與學習路徑。

**教師專區**，我們[提供一些使用本課程的建議](for-teachers.md)。

---

## 影片導覽

部分課程有短片教學。你可以在課程中嵌入觀看，或到 [Microsoft Developer YouTube 頻道上的 ML for Beginners 播放清單](https://aka.ms/ml-beginners-videos)觀看，點擊以下圖片即可。

[![ML for beginners banner](../../translated_images/zh-HK/ml-for-beginners-video-banner.63f694a100034bc6.webp)](https://aka.ms/ml-beginners-videos)

---

## 團隊介紹

[![Promo video](../../images/ml.gif)](https://youtu.be/Tj1XWrDSYJU)

**Gif 由** [Mohit Jaisal](https://linkedin.com/in/mohitjaisal) 製作

> 🎥 點擊上圖觀看專案與創建團隊成員的介紹影片！

---

## 教學法

我們在設計本課程時採用了兩大教學原則：確保課程是動手做的**專案導向**，並設計了**頻繁的測驗**。此外，本課程具有統一的**主題**以保持一致性。

確保內容配合專案，讓學習更有趣且提升概念記憶。課前的低壓力測驗能幫助學生建立學習主題的動機，課後測驗則加強記憶。本課程設計為靈活且有趣，可整體或部分進行。專案從簡單開始，隨著 12 週學習週期逐步變得更複雜。課程還包含機器學習現實應用的附錄，可作為額外學分或討論基礎。

> 請參閱我們的[行為準則](CODE_OF_CONDUCT.md)、[貢獻指南](CONTRIBUTING.md)、[翻譯指南](TRANSLATIONS.md)與[故障排除](TROUBLESHOOTING.md)方針。我們歡迎您的建設性意見！

## 每堂課包含

- 選擇性筆記圖示
- 選擇性補充影片
- 影片導覽（部分課程）
- [課前暖身測驗](https://ff-quizzes.netlify.app/en/ml/)
- 書面課程
- 專案課程中有逐步製作指引
- 知識檢核
- 挑戰題
- 補充閱讀
- 作業
- [課後測驗](https://ff-quizzes.netlify.app/en/ml/)

> **關於語言**：這些課程主要使用 Python 語言，但有許多課程同時提供 R 語言版本。要完成 R 課程，請前往 `/solution` 資料夾，尋找有 .rmd 副檔名的課程。此為 **R Markdown** 檔案，簡單來說是一種將 `code chunks`（R 或其他語言的程式碼塊）與 `YAML 標頭`（決定輸出格式如 PDF）嵌入於 `Markdown 文件` 的格式。因此，它是資料科學撰稿的極佳框架，允許你結合程式碼、輸出結果和文字說明一起撰寫。R Markdown 文件可輸出成 PDF、HTML 或 Word 等格式。
> **關於小測的說明**：所有小測均包含在 [Quiz App folder](../../quiz-app) 中，共計 52 個小測，每個小測包含三個問題。它們會從課程中連結，但測驗應用程式可在本地運行；請按照 `quiz-app` 資料夾中的指示進行本地託管或部署到 Azure。

| 課程編號 |                            主題                             |                   課程分組                    | 學習目標                                                                                                                    |                                                               相關課程                                                                |                       作者                       |
| :------: | :---------------------------------------------------------: | :------------------------------------------: | ---------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------: |
|    01    |                   機器學習入門                   |      [Introduction](1-Introduction/README.md)      | 學習機器學習背後的基本概念                                                                                                 |                                           [Lesson](1-Introduction/1-intro-to-ML/README.md)                                            |                    Muhammad                    |
|    02    |                  機器學習的歷史                  |      [Introduction](1-Introduction/README.md)      | 了解這個領域的歷史背景                                                                                                    |                                          [Lesson](1-Introduction/2-history-of-ML/README.md)                                           |                  Jen and Amy                   |
|    03    |                 公平性與機器學習                 |      [Introduction](1-Introduction/README.md)      | 建立及應用機器學習模型時，學生應考慮的重要哲學公平議題                                                                      |                                            [Lesson](1-Introduction/3-fairness/README.md)                                              |                     Tomomi                     |
|    04    |                  機器學習技術                   |      [Introduction](1-Introduction/README.md)      | 機器學習研究者使用的建模技術                                                                                              |                                          [Lesson](1-Introduction/4-techniques-of-ML/README.md)                                          |                  Chris and Jen                  |
|    05    |                   迴歸介紹                   |        [Regression](2-Regression/README.md)        | 開始使用 Python 和 Scikit-learn 進行迴歸模型                                                                                 |          [Python](2-Regression/1-Tools/README.md) • [R](../../2-Regression/1-Tools/solution/R/lesson_1.html)          |          Jen • Eric Wanjau          |
|    06    |                北美南瓜價格 🎃                |        [Regression](2-Regression/README.md)        | 為機器學習做視覺化及資料清理                                                                                                |           [Python](2-Regression/2-Data/README.md) • [R](../../2-Regression/2-Data/solution/R/lesson_2.html)          |          Jen • Eric Wanjau          |
|    07    |                北美南瓜價格 🎃                |        [Regression](2-Regression/README.md)        | 建立線性及多項式迴歸模型                                                                                                    |         [Python](2-Regression/3-Linear/README.md) • [R](../../2-Regression/3-Linear/solution/R/lesson_3.html)         |          Jen and Dmitry • Eric Wanjau          |
|    08    |                北美南瓜價格 🎃                |        [Regression](2-Regression/README.md)        | 建立邏輯迴歸模型                                                                                                            |      [Python](2-Regression/4-Logistic/README.md) • [R](../../2-Regression/4-Logistic/solution/R/lesson_4.html)       |          Jen • Eric Wanjau          |
|    09    |                          網頁應用 🔌                          |           [Web App](3-Web-App/README.md)            | 建立一個可使用你訓練模型的網頁應用                                                                                        |                                                    [Python](3-Web-App/1-Web-App/README.md)                                                   |                       Jen                       |
|    10    |                  分類介紹                  |    [Classification](4-Classification/README.md)    | 資料清理、準備與視覺化；分類入門                                                                                            | [Python](4-Classification/1-Introduction/README.md) • [R](../../4-Classification/1-Introduction/solution/R/lesson_10.html) | Jen and Cassie • Eric Wanjau |
|    11    |             美味的亞洲與印度料理 🍜             |    [Classification](4-Classification/README.md)    | 分類器介紹                                                                                                                 | [Python](4-Classification/2-Classifiers-1/README.md) • [R](../../4-Classification/2-Classifiers-1/solution/R/lesson_11.html) | Jen and Cassie • Eric Wanjau |
|    12    |             美味的亞洲與印度料理 🍜             |    [Classification](4-Classification/README.md)    | 更多分類器                                                                                                                | [Python](4-Classification/3-Classifiers-2/README.md) • [R](../../4-Classification/3-Classifiers-2/solution/R/lesson_12.html) | Jen and Cassie • Eric Wanjau |
|    13    |             美味的亞洲與印度料理 🍜             |    [Classification](4-Classification/README.md)    | 使用你的模型建立推薦系統網頁應用                                                                                          |                                               [Python](4-Classification/4-Applied/README.md)                                               |                       Jen                       |
|    14    |                  分群介紹                  |        [Clustering](5-Clustering/README.md)         | 資料清理、準備與視覺化；分群入門                                                                                            |          [Python](5-Clustering/1-Visualize/README.md) • [R](../../5-Clustering/1-Visualize/solution/R/lesson_14.html)          |          Jen • Eric Wanjau          |
|    15    |              探索奈及利亞音樂喜好 🎧              |        [Clustering](5-Clustering/README.md)         | 探索 K-Means 分群方法                                                                                                      |            [Python](5-Clustering/2-K-Means/README.md) • [R](../../5-Clustering/2-K-Means/solution/R/lesson_15.html)            |          Jen • Eric Wanjau          |
|    16    |        自然語言處理入門 ☕️        |   [Natural language processing](6-NLP/README.md)    | 透過建立簡單機器人學習 NLP 基礎                                                                                            |                                            [Python](6-NLP/1-Introduction-to-NLP/README.md)                                             |                     Stephen                     |
|    17    |                      常見 NLP 任務 ☕️                      |   [Natural language processing](6-NLP/README.md)    | 透過了解處理語言結構時常見任務，深化你的 NLP 知識                                                                           |                                                  [Python](6-NLP/2-Tasks/README.md)                                                  |                     Stephen                     |
|    18    |             翻譯與情感分析 ♥️             |   [Natural language processing](6-NLP/README.md)    | 與簡·奧斯汀一起做翻譯及情感分析                                                                                            |                                            [Python](6-NLP/3-Translation-Sentiment/README.md)                                             |                     Stephen                     |
|    19    |                  歐洲浪漫旅館 ♥️                  |   [Natural language processing](6-NLP/README.md)    | 使用旅館評論進行情感分析 1                                                                                                  |                                               [Python](6-NLP/4-Hotel-Reviews-1/README.md)                                               |                     Stephen                     |
|    20    |                  歐洲浪漫旅館 ♥️                  |   [Natural language processing](6-NLP/README.md)    | 使用旅館評論進行情感分析 2                                                                                                  |                                               [Python](6-NLP/5-Hotel-Reviews-2/README.md)                                               |                     Stephen                     |
|    21    |            時間序列預測入門            |        [Time series](7-TimeSeries/README.md)        | 時間序列預測介紹                                                                                                           |                                            [Python](7-TimeSeries/1-Introduction/README.md)                                             |                   Francesca                    |
|    22    | ⚡️ 全球電力使用 ⚡️ - 使用 ARIMA 進行時間序列預測 |        [Time series](7-TimeSeries/README.md)        | 使用 ARIMA 進行時間序列預測                                                                                                |                                                [Python](7-TimeSeries/2-ARIMA/README.md)                                                 |                   Francesca                    |
|    23    |  ⚡️ 全球電力使用 ⚡️ - 用 SVR 做時間序列預測  |        [Time series](7-TimeSeries/README.md)        | 使用支持向量回歸進行時間序列預測                                                                                           |                                                 [Python](7-TimeSeries/3-SVR/README.md)                                                 |                    Anirban                     |
|    24    |             強化學習入門             | [Reinforcement learning](8-Reinforcement/README.md) | 使用 Q-Learning 進行強化學習介紹                                                                                           |                                            [Python](8-Reinforcement/1-QLearning/README.md)                                            |                     Dmitry                     |
|    25    |                 幫彼得躲避狼！🐺                 | [Reinforcement learning](8-Reinforcement/README.md) | 強化學習 Gym                                                                                                              |                                                [Python](8-Reinforcement/2-Gym/README.md)                                                  |                     Dmitry                     |
|  後記   |           真實世界的機器學習情境與應用           |      [ML in the Wild](9-Real-World/README.md)       | 經典機器學習的有趣且具啟發性的真實世界應用                                                                                 |                                            [Lesson](9-Real-World/1-Applications/README.md)                                              |                      Team                      |
|  後記   |           使用 RAI 儀表板進行機器學習模型除錯           |      [ML in the Wild](9-Real-World/README.md)       | 使用負責任 AI 儀表板元件進行機器學習模型除錯                                                                               |                                            [Lesson](9-Real-World/2-Debugging-ML-Models/README.md)                                          |                    Ruth Yakubu                    |

> [在我們的 Microsoft Learn 集合中找到此課程的所有附加資源](https://learn.microsoft.com/en-us/collections/qrqzamz1nn2wx3?WT.mc_id=academic-77952-bethanycheum)

## 離線存取

你可以使用 [Docsify](https://docsify.js.org/#/) 離線執行此文件。叉出此存放庫，在你的本機安裝 [Docsify](https://docsify.js.org/#/quickstart)，然後在此存放庫根目錄中輸入 `docsify serve`。網站將在你的本地主機的 3000 端口服務：`localhost:3000`。

## PDF

可在此處找到帶有連結的課程 PDF：[pdf](https://microsoft.github.io/ML-For-Beginners/pdf/readme.pdf)。


## 🎒 其他課程 

我們的團隊還製作其他課程！查閱：

<!-- CO-OP TRANSLATOR OTHER COURSES START -->
### LangChain
[![LangChain4j for Beginners](https://img.shields.io/badge/LangChain4j%20for%20Beginners-22C55E?style=for-the-badge&&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchain4j-for-beginners)
[![LangChain.js for Beginners](https://img.shields.io/badge/LangChain.js%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchainjs-for-beginners?WT.mc_id=m365-94501-dwahlin)
[![LangChain for Beginners](https://img.shields.io/badge/LangChain%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=0553D6)](https://github.com/microsoft/langchain-for-beginners?WT.mc_id=m365-94501-dwahlin)
---

### Azure / Edge / MCP / Agents
[![AZD for Beginners](https://img.shields.io/badge/AZD%20for%20Beginners-0078D4?style=for-the-badge&labelColor=E5E7EB&color=0078D4)](https://github.com/microsoft/AZD-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Edge AI for Beginners](https://img.shields.io/badge/Edge%20AI%20for%20Beginners-00B8E4?style=for-the-badge&labelColor=E5E7EB&color=00B8E4)](https://github.com/microsoft/edgeai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![MCP for Beginners](https://img.shields.io/badge/MCP%20for%20Beginners-009688?style=for-the-badge&labelColor=E5E7EB&color=009688)](https://github.com/microsoft/mcp-for-beginners?WT.mc_id=academic-105485-koreyst)
[![AI Agents for Beginners](https://img.shields.io/badge/AI%20Agents%20for%20Beginners-00C49A?style=for-the-badge&labelColor=E5E7EB&color=00C49A)](https://github.com/microsoft/ai-agents-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### 生成式 AI 系列
[![Generative AI for Beginners](https://img.shields.io/badge/Generative%20AI%20for%20Beginners-8B5CF6?style=for-the-badge&labelColor=E5E7EB&color=8B5CF6)](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Generative AI (.NET)](https://img.shields.io/badge/Generative%20AI%20(.NET)-9333EA?style=for-the-badge&labelColor=E5E7EB&color=9333EA)](https://github.com/microsoft/Generative-AI-for-beginners-dotnet?WT.mc_id=academic-105485-koreyst)
[![Generative AI (Java)](https://img.shields.io/badge/Generative%20AI%20(Java)-C084FC?style=for-the-badge&labelColor=E5E7EB&color=C084FC)](https://github.com/microsoft/generative-ai-for-beginners-java?WT.mc_id=academic-105485-koreyst)
[![Generative AI (JavaScript)](https://img.shields.io/badge/Generative%20AI%20(JavaScript)-E879F9?style=for-the-badge&labelColor=E5E7EB&color=E879F9)](https://github.com/microsoft/generative-ai-with-javascript?WT.mc_id=academic-105485-koreyst)

---
 
### 核心學習
[![ML for Beginners](https://img.shields.io/badge/ML%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=22C55E)](https://aka.ms/ml-beginners?WT.mc_id=academic-105485-koreyst)
[![Data Science for Beginners](https://img.shields.io/badge/Data%20Science%20for%20Beginners-84CC16?style=for-the-badge&labelColor=E5E7EB&color=84CC16)](https://aka.ms/datascience-beginners?WT.mc_id=academic-105485-koreyst)
[![AI for Beginners](https://img.shields.io/badge/AI%20for%20Beginners-A3E635?style=for-the-badge&labelColor=E5E7EB&color=A3E635)](https://aka.ms/ai-beginners?WT.mc_id=academic-105485-koreyst)
[![Cybersecurity for Beginners](https://img.shields.io/badge/Cybersecurity%20for%20Beginners-F97316?style=for-the-badge&labelColor=E5E7EB&color=F97316)](https://github.com/microsoft/Security-101?WT.mc_id=academic-96948-sayoung)
[![Web Dev for Beginners](https://img.shields.io/badge/Web%20Dev%20for%20Beginners-EC4899?style=for-the-badge&labelColor=E5E7EB&color=EC4899)](https://aka.ms/webdev-beginners?WT.mc_id=academic-105485-koreyst)
[![IoT for Beginners](https://img.shields.io/badge/IoT%20for%20Beginners-14B8A6?style=for-the-badge&labelColor=E5E7EB&color=14B8A6)](https://aka.ms/iot-beginners?WT.mc_id=academic-105485-koreyst)
[![XR Development for Beginners](https://img.shields.io/badge/XR%20Development%20for%20Beginners-38BDF8?style=for-the-badge&labelColor=E5E7EB&color=38BDF8)](https://github.com/microsoft/xr-development-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Copilot 系列
[![Copilot for AI Paired Programming](https://img.shields.io/badge/Copilot%20for%20AI%20Paired%20Programming-FACC15?style=for-the-badge&labelColor=E5E7EB&color=FACC15)](https://aka.ms/GitHubCopilotAI?WT.mc_id=academic-105485-koreyst)
[![Copilot for C#/.NET](https://img.shields.io/badge/Copilot%20for%20C%23/.NET-FBBF24?style=for-the-badge&labelColor=E5E7EB&color=FBBF24)](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers?WT.mc_id=academic-105485-koreyst)
[![Copilot Adventure](https://img.shields.io/badge/Copilot%20Adventure-FDE68A?style=for-the-badge&labelColor=E5E7EB&color=FDE68A)](https://github.com/microsoft/CopilotAdventures?WT.mc_id=academic-105485-koreyst)
<!-- CO-OP TRANSLATOR OTHER COURSES END -->

## 尋求協助

如果您遇到困難或對建立 AI 應用程式有任何疑問，歡迎加入與其他學習者及經驗豐富的開發者一同討論 MCP。這是一個支持性的社群，歡迎提出問題並自由分享知識。

[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

如果您在開發過程中有產品回饋或發現錯誤，請造訪：

[![Microsoft Foundry Developer Forum](https://img.shields.io/badge/GitHub-Microsoft_Foundry_Developer_Forum-blue?style=for-the-badge&logo=github&color=000000&logoColor=fff)](https://aka.ms/foundry/forum)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**免責聲明**：
本文件經由 AI 翻譯服務 [Co-op Translator](https://github.com/Azure/co-op-translator) 進行翻譯。雖然我們致力追求準確性，但請注意自動翻譯可能包含錯誤或不準確之處。原文文件應被視為權威來源。如涉及重要資訊，建議尋求專業人工翻譯。我們對使用本翻譯所引起的任何誤解或曲解概不負責。
<!-- CO-OP TRANSLATOR DISCLAIMER END -->