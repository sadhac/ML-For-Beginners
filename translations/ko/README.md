[![GitHub license](https://img.shields.io/github/license/microsoft/ML-For-Beginners.svg)](https://github.com/microsoft/ML-For-Beginners/blob/master/LICENSE)
[![GitHub contributors](https://img.shields.io/github/contributors/microsoft/ML-For-Beginners.svg)](https://GitHub.com/microsoft/ML-For-Beginners/graphs/contributors/)
[![GitHub issues](https://img.shields.io/github/issues/microsoft/ML-For-Beginners.svg)](https://GitHub.com/microsoft/ML-For-Beginners/issues/)
[![GitHub pull-requests](https://img.shields.io/github/issues-pr/microsoft/ML-For-Beginners.svg)](https://GitHub.com/microsoft/ML-For-Beginners/pulls/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/ML-For-Beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/ML-For-Beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/ML-For-Beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/ML-For-Beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/ML-For-Beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/ML-For-Beginners/stargazers/)

### 🌐 다국어 지원

#### GitHub Action을 통해 지원 (자동화 및 항상 최신 상태 유지)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](./README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **로컬에서 클론하는 것을 선호하시나요?**

> 이 저장소에는 50개 이상의 언어 번역본이 포함되어 있어 다운로드 크기가 크게 증가합니다. 번역 없이 클론하려면 스패어스 체크아웃을 사용하세요:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/microsoft/ML-For-Beginners.git
> cd ML-For-Beginners
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> 이렇게 하면 훨씬 빠른 다운로드로 코스 완료에 필요한 모든 것을 얻을 수 있습니다.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

#### 커뮤니티에 참여하세요

[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

우리는 Discord에서 AI와 함께 배우기 시리즈를 진행 중입니다. 2025년 9월 18일부터 30일까지 [Learn with AI Series](https://aka.ms/learnwithai/discord)에서 자세히 알아보고 참여하세요. GitHub Copilot을 데이터 과학에 활용하는 팁과 요령을 얻을 수 있습니다.

![Learn with AI series](../../translated_images/ko/3.9b58fd8d6c373c20.webp)

# 초보자를 위한 머신러닝 - 커리큘럼

> 🌍 세계 문화를 통해 머신러닝을 탐구하며 세계 여행을 떠나봅시다 🌍

마이크로소프트 클라우드 어드보케이트는 12주간 26개의 레슨으로 구성된 **머신러닝** 전체 커리큘럼을 제공하게 되어 기쁩니다. 이 커리큘럼에서는 주로 Scikit-learn 라이브러리를 사용하여 때때로 **고전 머신러닝**이라 불리는 것을 배우고, 딥러닝은 [AI for Beginners 커리큘럼](https://aka.ms/ai4beginners)에서 다룹니다. 이 수업들을 우리 ['Data Science for Beginners' 커리큘럼](https://aka.ms/ds4beginners)과 함께 활용하세요!

세계 여러 지역의 데이터를 사용하여 고전적인 기법을 적용하며 우리와 함께 세계 여행을 떠나보세요. 각 레슨에는 수업 전과 후 퀴즈, 수업 수행 지침, 해결책, 과제 등이 포함됩니다. 프로젝트 기반 수업법을 통해 학습하며 만드는 과정을 경험할 수 있어, 새 기술이 더 잘 익혀집니다.

**✍️ 진심으로 감사드립니다** 저자분들: Jen Looper, Stephen Howell, Francesca Lazzeri, Tomomi Imura, Cassie Breviu, Dmitry Soshnikov, Chris Noring, Anirban Mukherjee, Ornella Altunyan, Ruth Yakubu 그리고 Amy Boyd

**🎨 또 다른 감사를** 일러스트레이터분들: Tomomi Imura, Dasani Madipalli, Jen Looper

**🙏 특별한 감사 🙏 마이크로소프트 학생 대사 저자, 검토자, 컨텐츠 기여자 여러분께**, 특히 Rishit Dagli, Muhammad Sakib Khan Inan, Rohan Raj, Alexandru Petrescu, Abhishek Jaiswal, Nawrin Tabassum, Ioan Samuila, Snigdha Agarwal

**🤩 MS 학생 대사 Eric Wanjau, Jasleen Sondhi, Vidushi Gupta께도 R 수업 관련 특별한 감사 드립니다!**

# 시작하기

다음 단계를 따르세요:
1. **저장소 포크하기**: 이 페이지 우측 상단의 "Fork" 버튼을 클릭하세요.
2. **저장소 클론하기**:   `git clone https://github.com/microsoft/ML-For-Beginners.git`

> [이 과정과 관련된 모든 추가 자료는 Microsoft Learn 모음에서 찾을 수 있습니다](https://learn.microsoft.com/en-us/collections/qrqzamz1nn2wx3?WT.mc_id=academic-77952-bethanycheum)

> 🔧 **도움이 필요하신가요?** 설치, 설정 및 수업 실행에 관한 일반 문제 해결법은 [문제 해결 가이드](TROUBLESHOOTING.md)를 확인하세요.


**[학생 여러분](https://aka.ms/student-page)**, 이 커리큘럼을 사용하려면 저장소를 자신의 GitHub 계정으로 포크하고 혼자 또는 그룹과 함께 과제를 완료하세요:

- 강의 전 퀴즈부터 시작하세요.
- 강의를 읽고 각 지식 점검에서 멈추어 생각하며 활동을 완수하세요.
- 레슨을 이해하고 프로젝트를 직접 만들어 보세요. 하지만 `/solution` 폴더에 있는 솔루션 코드를 참고할 수 있습니다.
- 강의 후 퀴즈를 응시하세요.
- 챌린지를 완료하세요.
- 과제를 마치세요.
- 레슨 그룹을 완료한 후에는 [토론 게시판](https://github.com/microsoft/ML-For-Beginners/discussions)에서 '목소리 내어 학습'하며 적절한 PAT 루브릭을 작성해 주세요. 'PAT'는 학습 진행 평가 도구로, 여러분의 학습을 한층 심화시키기 위한 루브릭입니다. 다른 PAT에 리액션을 달아 함께 배울 수도 있습니다.

> 추가 학습을 위한 추천 [Microsoft Learn](https://docs.microsoft.com/en-us/users/jenlooper-2911/collections/k7o7tg1gp306q4?WT.mc_id=academic-77952-leestott) 모듈 및 학습 경로를 참고하세요.

**교사 여러분**, 이 커리큘럼 사용에 관한 [몇 가지 제안](for-teachers.md)을 제공하고 있습니다.

---

## 비디오 수업 안내

몇몇 레슨은 짧은 형태의 비디오로 제공됩니다. 수업 내에서 인라인으로 찾을 수 있거나, 아래 이미지를 클릭해 [Microsoft Developer 유튜브 채널의 ML for Beginners 재생목록](https://aka.ms/ml-beginners-videos)에서 보실 수 있습니다.

[![ML for beginners banner](../../translated_images/ko/ml-for-beginners-video-banner.63f694a100034bc6.webp)](https://aka.ms/ml-beginners-videos)

---

## 팀 소개

[![Promo video](../../images/ml.gif)](https://youtu.be/Tj1XWrDSYJU)

**GIF 제작자** [Mohit Jaisal](https://linkedin.com/in/mohitjaisal)

> 🎥 위 이미지를 클릭하여 프로젝트 및 제작자에 관한 비디오를 시청하세요!

---

## 교육 철학

이 커리큘럼을 구성하면서 두 가지 교육 원칙을 선택했습니다: 실습 중심의 **프로젝트 기반** 교육과 **자주 진행되는 퀴즈** 포함입니다. 더불어, 일관성을 위한 공통된 **주제**도 설정했습니다.

내용이 프로젝트와 연계되도록 하여 학생들이 더 몰입하고 개념 이해가 높아지게 했습니다. 학습 전의 낮은 강도의 퀴즈는 학생의 학습 목표를 설정하며, 수업 후 퀴즈는 개념의 장기 기억을 돕습니다. 이 커리큘럼은 유연하고 재미있게 설계되어 전체 또는 일부만 선택해 학습할 수 있습니다. 프로젝트는 작게 시작해 12주 과정이 끝날 때쯤 점점 복잡해집니다. 또한 머신러닝의 실제 적용에 관한 후기 내용도 포함되어 있어 추가 점수나 토론 주제로 활용할 수 있습니다.

> [행동 강령](CODE_OF_CONDUCT.md), [기여](CONTRIBUTING.md), [번역](TRANSLATIONS.md), [문제 해결](TROUBLESHOOTING.md) 가이드라인을 확인하세요. 여러분의 건설적인 피드백을 환영합니다!

## 각 레슨에 포함된 내용

- 선택적 스케치노트
- 선택적 보충 비디오
- 비디오 수업 안내 (일부 레슨)
- [강의 전 워밍업 퀴즈](https://ff-quizzes.netlify.app/en/ml/)
- 서면 강의
- 프로젝트 기반 수업은 단계별 프로젝트 구현 가이드 포함
- 지식 점검
- 도전 과제
- 보충 독서 자료
- 과제
- [강의 후 퀴즈](https://ff-quizzes.netlify.app/en/ml/)

> **언어에 관한 참고**: 이 레슨들은 주로 Python으로 작성되었으나, R 버전도 많이 제공됩니다. R 레슨을 완료하려면 `/solution` 폴더에서 R 레슨을 찾아보세요. 이들은 .rmd 확장자를 가진 **R 마크다운** 파일로, `코드 청크` (R 또는 다른 언어)와 `YAML 헤더`(PDF와 같은 출력 포맷 지정)를 `Markdown 문서`에 포함합니다. 따라서 코드, 출력물 및 생각을 Markdown에 기록할 수 있어 데이터 과학을 위한 훌륭한 저작 구성 도구입니다. 또한 R 마크다운 문서는 PDF, HTML, Word 같은 출력 포맷으로 렌더링할 수 있습니다.
> **퀴즈에 대한 안내**: 모든 퀴즈는 [Quiz App 폴더](../../quiz-app)에 포함되어 있으며, 각 퀴즈는 세 개의 질문으로 구성된 총 52개의 퀴즈입니다. 퀴즈는 수업 내에서 연결되어 있지만, 퀴즈 앱은 로컬에서 실행할 수 있습니다. 로컬 호스팅 또는 Azure에 배포하려면 `quiz-app` 폴더의 지침을 따르세요.

| 수업 번호 |                             주제                              |                   수업 그룹                   | 학습 목표                                                                                                                    |                                                              연결된 수업                                                               |                        저자                        |
| :-------: | :------------------------------------------------------------: | :------------------------------------------: | ----------------------------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------: |
|    01     |                머신러닝 소개                |      [소개](1-Introduction/README.md)       | 머신러닝의 기본 개념을 학습합니다                                                                                         |                                             [수업](1-Introduction/1-intro-to-ML/README.md)                                             |                       Muhammad                       |
|    02     |                머신러닝의 역사                 |      [소개](1-Introduction/README.md)       | 이 분야의 역사를 학습합니다                                                                                               |                                            [수업](1-Introduction/2-history-of-ML/README.md)                                            |                     Jen and Amy                      |
|    03     |                 공정성과 머신러닝                  |      [소개](1-Introduction/README.md)       | 공정성과 관련된 주요 철학적 문제들을 학생들이 ML 모델을 구축하고 적용할 때 고려해야 하는 점은 무엇인지 학습합니다. |                                              [수업](1-Introduction/3-fairness/README.md)                                               |                        Tomomi                        |
|    04     |                머신러닝 기법                 |      [소개](1-Introduction/README.md)       | ML 연구자가 ML 모델을 구축할 때 사용하는 기법을 학습합니다.                                                               |                                          [수업](1-Introduction/4-techniques-of-ML/README.md)                                           |                    Chris and Jen                     |
|    05     |                   회귀 소개                   |        [회귀](2-Regression/README.md)         | 회귀 모델을 위해 Python과 Scikit-learn 사용을 시작합니다                                                                  |         [Python](2-Regression/1-Tools/README.md) • [R](../../2-Regression/1-Tools/solution/R/lesson_1.html)         |      Jen • Eric Wanjau       |
|    06     |                북미 호박 가격 🎃                |        [회귀](2-Regression/README.md)         | 머신러닝 준비를 위해 데이터를 시각화하고 정리합니다                                                                          |          [Python](2-Regression/2-Data/README.md) • [R](../../2-Regression/2-Data/solution/R/lesson_2.html)          |      Jen • Eric Wanjau       |
|    07     |                북미 호박 가격 🎃                |        [회귀](2-Regression/README.md)         | 선형 및 다항 회귀 모델을 구축합니다                                                                                         |        [Python](2-Regression/3-Linear/README.md) • [R](../../2-Regression/3-Linear/solution/R/lesson_3.html)        |      Jen and Dmitry • Eric Wanjau       |
|    08     |                북미 호박 가격 🎃                |        [회귀](2-Regression/README.md)         | 로지스틱 회귀 모델을 구축합니다                                                                                            |     [Python](2-Regression/4-Logistic/README.md) • [R](../../2-Regression/4-Logistic/solution/R/lesson_4.html)      |      Jen • Eric Wanjau       |
|    09     |                          웹 앱 🔌                          |           [웹 앱](3-Web-App/README.md)            | 학습한 모델을 사용하는 웹 앱을 구축합니다                                                                                   |                                                 [Python](3-Web-App/1-Web-App/README.md)                                                  |                         Jen                          |
|    10     |                 분류 소개                 |    [분류](4-Classification/README.md)     | 데이터를 정리, 준비, 시각화하고 분류에 대한 소개를 받습니다                                                                 | [Python](4-Classification/1-Introduction/README.md) • [R](../../4-Classification/1-Introduction/solution/R/lesson_10.html)  | Jen and Cassie • Eric Wanjau |
|    11     |             맛있는 아시아 및 인도 요리 🍜             |    [분류](4-Classification/README.md)     | 분류기에 대한 소개                                                                                                         | [Python](4-Classification/2-Classifiers-1/README.md) • [R](../../4-Classification/2-Classifiers-1/solution/R/lesson_11.html) | Jen and Cassie • Eric Wanjau |
|    12     |             맛있는 아시아 및 인도 요리 🍜             |    [분류](4-Classification/README.md)     | 분류기 확장                                                                                                                | [Python](4-Classification/3-Classifiers-2/README.md) • [R](../../4-Classification/3-Classifiers-2/solution/R/lesson_12.html) | Jen and Cassie • Eric Wanjau |
|    13     |             맛있는 아시아 및 인도 요리 🍜             |    [분류](4-Classification/README.md)     | 모델을 사용하여 추천 웹 앱을 구축합니다                                                                                     |                                              [Python](4-Classification/4-Applied/README.md)                                              |                         Jen                          |
|    14     |                   클러스터링 소개                   |        [클러스터링](5-Clustering/README.md)         | 데이터를 정리, 준비, 시각화하고 클러스터링 소개를 받습니다                                                                   |         [Python](5-Clustering/1-Visualize/README.md) • [R](../../5-Clustering/1-Visualize/solution/R/lesson_14.html)         |      Jen • Eric Wanjau       |
|    15     |              나이지리아 음악 취향 탐험 🎧              |        [클러스터링](5-Clustering/README.md)         | K-평균 클러스터링 방법을 탐험합니다                                                                                         |           [Python](5-Clustering/2-K-Means/README.md) • [R](../../5-Clustering/2-K-Means/solution/R/lesson_15.html)           |      Jen • Eric Wanjau       |
|    16     |        자연어 처리 소개 ☕️         |   [자연어 처리](6-NLP/README.md)    | 간단한 봇을 만들어 NLP 기본을 배웁니다                                                                                     |                                             [Python](6-NLP/1-Introduction-to-NLP/README.md)                                              |                       Stephen                        |
|    17     |                      일반적인 NLP 작업 ☕️                      |   [자연어 처리](6-NLP/README.md)    | 언어 구조를 다룰 때 필요한 일반 과제를 이해하며 NLP 지식을 심화합니다                                                        |                                                    [Python](6-NLP/2-Tasks/README.md)                                                     |                       Stephen                        |
|    18     |             번역 및 감정 분석 ♥️              |   [자연어 처리](6-NLP/README.md)    | 제인 오스틴과 함께하는 번역 및 감정 분석                                                                                   |                                            [Python](6-NLP/3-Translation-Sentiment/README.md)                                             |                       Stephen                        |
|    19     |                  유럽의 로맨틱 호텔 ♥️                  |   [자연어 처리](6-NLP/README.md)    | 호텔 리뷰를 통한 감정 분석 1                                                                                                |                                               [Python](6-NLP/4-Hotel-Reviews-1/README.md)                                                |                       Stephen                        |
|    20     |                  유럽의 로맨틱 호텔 ♥️                  |   [자연어 처리](6-NLP/README.md)    | 호텔 리뷰를 통한 감정 분석 2                                                                                                |                                               [Python](6-NLP/5-Hotel-Reviews-2/README.md)                                                |                       Stephen                        |
|    21     |            시계열 예측 소개             |        [시계열](7-TimeSeries/README.md)        | 시계열 예측 소개                                                                                                           |                                             [Python](7-TimeSeries/1-Introduction/README.md)                                              |                      Francesca                       |
|    22     | ⚡️ 세계 전력 사용량 ⚡️ - ARIMA를 활용한 시계열 예측 |        [시계열](7-TimeSeries/README.md)        | ARIMA를 활용한 시계열 예측                                                                                                  |                                                 [Python](7-TimeSeries/2-ARIMA/README.md)                                                 |                      Francesca                       |
|    23     |  ⚡️ 세계 전력 사용량 ⚡️ - SVR을 활용한 시계열 예측  |        [시계열](7-TimeSeries/README.md)        | 서포트 벡터 회귀를 활용한 시계열 예측                                                                                       |                                                  [Python](7-TimeSeries/3-SVR/README.md)                                                  |                       Anirban                        |
|    24     |             강화학습 소개             | [강화학습](8-Reinforcement/README.md) | Q-러닝을 활용한 강화학습 소개                                                                                              |                                             [Python](8-Reinforcement/1-QLearning/README.md)                                              |                        Dmitry                        |
|    25     |                 피터가 늑대를 피하게 도우세요! 🐺                  | [강화학습](8-Reinforcement/README.md) | 강화학습 Gym                                                                                                               |                                                [Python](8-Reinforcement/2-Gym/README.md)                                                 |                        Dmitry                        |
|  후기글   |            실제 머신러닝 시나리오 및 응용            |      [현장 ML](9-Real-World/README.md)       | 고전적인 ML의 흥미롭고 드러나는 실제 응용 사례                                                                                |                                             [수업](9-Real-World/1-Applications/README.md)                                              |                         팀                         |
|  후기글   |            RAI 대시보드를 이용한 ML 모델 디버깅          |      [현장 ML](9-Real-World/README.md)       | 책임 있는 AI 대시보드 구성요소를 활용한 머신러닝 모델 디버깅                                                                  |                                             [수업](9-Real-World/2-Debugging-ML-Models/README.md)                                              |                         Ruth Yakubu                       |

> [본 과정의 추가 자료는 Microsoft Learn 모음에서 모두 확인하세요](https://learn.microsoft.com/en-us/collections/qrqzamz1nn2wx3?WT.mc_id=academic-77952-bethanycheum)

## 오프라인 접근

[Docsify](https://docsify.js.org/#/)를 사용하여 이 문서를 오프라인에서 실행할 수 있습니다. 이 저장소를 포크하고, 로컬 머신에 [Docsify 설치](https://docsify.js.org/#/quickstart) 후, 이 저장소의 루트 폴더에서 `docsify serve`를 실행하면 웹사이트가 로컬호스트의 포트 3000, 즉 `localhost:3000`에서 서비스됩니다.

## PDF

커리큘럼 PDF 파일은 [여기](https://microsoft.github.io/ML-For-Beginners/pdf/readme.pdf)에서 다운로드하세요.


## 🎒 기타 강좌

저희 팀은 다른 강좌들도 제공합니다! 다음을 확인하세요:

<!-- CO-OP TRANSLATOR OTHER COURSES START -->
### LangChain
[![초보자를 위한 LangChain4j](https://img.shields.io/badge/LangChain4j%20for%20Beginners-22C55E?style=for-the-badge&&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchain4j-for-beginners)
[![초보자를 위한 LangChain.js](https://img.shields.io/badge/LangChain.js%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchainjs-for-beginners?WT.mc_id=m365-94501-dwahlin)
[![초보자를 위한 LangChain](https://img.shields.io/badge/LangChain%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=0553D6)](https://github.com/microsoft/langchain-for-beginners?WT.mc_id=m365-94501-dwahlin)
---

### Azure / Edge / MCP / 에이전트
[![초보자를 위한 AZD](https://img.shields.io/badge/AZD%20for%20Beginners-0078D4?style=for-the-badge&labelColor=E5E7EB&color=0078D4)](https://github.com/microsoft/AZD-for-beginners?WT.mc_id=academic-105485-koreyst)
[![초보자를 위한 Edge AI](https://img.shields.io/badge/Edge%20AI%20for%20Beginners-00B8E4?style=for-the-badge&labelColor=E5E7EB&color=00B8E4)](https://github.com/microsoft/edgeai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![초보자를 위한 MCP](https://img.shields.io/badge/MCP%20for%20Beginners-009688?style=for-the-badge&labelColor=E5E7EB&color=009688)](https://github.com/microsoft/mcp-for-beginners?WT.mc_id=academic-105485-koreyst)
[![초보자를 위한 AI 에이전트](https://img.shields.io/badge/AI%20Agents%20for%20Beginners-00C49A?style=for-the-badge&labelColor=E5E7EB&color=00C49A)](https://github.com/microsoft/ai-agents-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### 생성 AI 시리즈
[![초보자를 위한 생성 AI](https://img.shields.io/badge/Generative%20AI%20for%20Beginners-8B5CF6?style=for-the-badge&labelColor=E5E7EB&color=8B5CF6)](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![생성 AI (.NET)](https://img.shields.io/badge/Generative%20AI%20(.NET)-9333EA?style=for-the-badge&labelColor=E5E7EB&color=9333EA)](https://github.com/microsoft/Generative-AI-for-beginners-dotnet?WT.mc_id=academic-105485-koreyst)
[![생성 AI (Java)](https://img.shields.io/badge/Generative%20AI%20(Java)-C084FC?style=for-the-badge&labelColor=E5E7EB&color=C084FC)](https://github.com/microsoft/generative-ai-for-beginners-java?WT.mc_id=academic-105485-koreyst)
[![생성 AI (JavaScript)](https://img.shields.io/badge/Generative%20AI%20(JavaScript)-E879F9?style=for-the-badge&labelColor=E5E7EB&color=E879F9)](https://github.com/microsoft/generative-ai-with-javascript?WT.mc_id=academic-105485-koreyst)

---

### 핵심 학습
[![초보자를 위한 ML](https://img.shields.io/badge/ML%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=22C55E)](https://aka.ms/ml-beginners?WT.mc_id=academic-105485-koreyst)
[![초보자를 위한 데이터 과학](https://img.shields.io/badge/Data%20Science%20for%20Beginners-84CC16?style=for-the-badge&labelColor=E5E7EB&color=84CC16)](https://aka.ms/datascience-beginners?WT.mc_id=academic-105485-koreyst)
[![초보자를 위한 AI](https://img.shields.io/badge/AI%20for%20Beginners-A3E635?style=for-the-badge&labelColor=E5E7EB&color=A3E635)](https://aka.ms/ai-beginners?WT.mc_id=academic-105485-koreyst)
[![초보자를 위한 사이버보안](https://img.shields.io/badge/Cybersecurity%20for%20Beginners-F97316?style=for-the-badge&labelColor=E5E7EB&color=F97316)](https://github.com/microsoft/Security-101?WT.mc_id=academic-96948-sayoung)
[![초보자를 위한 웹 개발](https://img.shields.io/badge/Web%20Dev%20for%20Beginners-EC4899?style=for-the-badge&labelColor=E5E7EB&color=EC4899)](https://aka.ms/webdev-beginners?WT.mc_id=academic-105485-koreyst)
[![초보자를 위한 IoT](https://img.shields.io/badge/IoT%20for%20Beginners-14B8A6?style=for-the-badge&labelColor=E5E7EB&color=14B8A6)](https://aka.ms/iot-beginners?WT.mc_id=academic-105485-koreyst)
[![초보자를 위한 XR 개발](https://img.shields.io/badge/XR%20Development%20for%20Beginners-38BDF8?style=for-the-badge&labelColor=E5E7EB&color=38BDF8)](https://github.com/microsoft/xr-development-for-beginners?WT.mc_id=academic-105485-koreyst)

---

### 코파일럿 시리즈
[![AI 페어 프로그래밍용 코파일럿](https://img.shields.io/badge/Copilot%20for%20AI%20Paired%20Programming-FACC15?style=for-the-badge&labelColor=E5E7EB&color=FACC15)](https://aka.ms/GitHubCopilotAI?WT.mc_id=academic-105485-koreyst)
[![C#/.NET용 코파일럿](https://img.shields.io/badge/Copilot%20for%20C%23/.NET-FBBF24?style=for-the-badge&labelColor=E5E7EB&color=FBBF24)](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers?WT.mc_id=academic-105485-koreyst)
[![코파일럿 어드벤처](https://img.shields.io/badge/Copilot%20Adventure-FDE68A?style=for-the-badge&labelColor=E5E7EB&color=FDE68A)](https://github.com/microsoft/CopilotAdventures?WT.mc_id=academic-105485-koreyst)
<!-- CO-OP TRANSLATOR OTHER COURSES END -->

## 도움 받기

AI 앱을 만드는 데 막히거나 질문이 있다면 MCP에 대해 함께 배우는 학습자와 숙련된 개발자들과 토론에 참여하세요. 질문이 환영받는 지원하는 커뮤니티이며 지식이 자유롭게 공유됩니다.

[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

제품 피드백이나 오류가 있을 경우 다음을 방문하세요:

[![Microsoft Foundry Developer Forum](https://img.shields.io/badge/GitHub-Microsoft_Foundry_Developer_Forum-blue?style=for-the-badge&logo=github&color=000000&logoColor=fff)](https://aka.ms/foundry/forum)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**면책 조항**:  
이 문서는 AI 번역 서비스 [Co-op Translator](https://github.com/Azure/co-op-translator)를 사용하여 번역되었습니다. 정확성을 위해 노력하고 있지만, 자동 번역에는 오류나 부정확한 부분이 있을 수 있음을 유의하시기 바랍니다. 원본 문서는 해당 언어로 작성된 문서가 권위 있는 출처로 간주되어야 합니다. 중요한 정보의 경우 전문적인 인간 번역을 권장합니다. 본 번역의 사용으로 발생하는 오해나 잘못된 해석에 대해서는 책임을 지지 않습니다.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->