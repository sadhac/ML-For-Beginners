[![GitHub license](https://img.shields.io/github/license/microsoft/ML-For-Beginners.svg)](https://github.com/microsoft/ML-For-Beginners/blob/master/LICENSE)
[![GitHub contributors](https://img.shields.io/github/contributors/microsoft/ML-For-Beginners.svg)](https://GitHub.com/microsoft/ML-For-Beginners/graphs/contributors/)
[![GitHub issues](https://img.shields.io/github/issues/microsoft/ML-For-Beginners.svg)](https://GitHub.com/microsoft/ML-For-Beginners/issues/)
[![GitHub pull-requests](https://img.shields.io/github/issues-pr/microsoft/ML-For-Beginners.svg)](https://GitHub.com/microsoft/ML-For-Beginners/pulls/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/ML-For-Beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/ML-For-Beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/ML-For-Beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/ML-For-Beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/ML-For-Beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/ML-For-Beginners/stargazers/)

### 🌐 کثیر اللسانی سپورٹ

#### گیٹ ہب ایکشن کے ذریعے سپورٹ (خودکار اور ہمیشہ تازہ ترین)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](./README.md) | [Vietnamese](../vi/README.md)

> **مقامی طور پر کلون کرنا پسند کریں؟**

> اس ذخیرے میں 50+ زبانوں کے تراجم شامل ہیں جو ڈاؤن لوڈ کے سائز کو نمایاں طور پر بڑھاتے ہیں۔ بغیر تراجم کے کلون کرنے کے لیے، sparse checkout استعمال کریں:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/microsoft/ML-For-Beginners.git
> cd ML-For-Beginners
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> یہ آپ کو پورا کورس مکمل کرنے کے لیے ہر وہ چیز فراہم کرتا ہے جس کی آپ کو ضرورت ہے، بہت تیز ڈاؤن لوڈ کے ساتھ۔
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

#### ہماری کمیونٹی میں شامل ہوں

[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

ہمارے پاس ایک Discord "learn with AI" سیریز جاری ہے، مزید جانیں اور ہمارے ساتھ شامل ہوں [Learn with AI Series](https://aka.ms/learnwithai/discord) 18 - 30 ستمبر، 2025 سے۔ آپ کو GitHub Copilot کے استعمال کے لیے ٹپس اور ترکیبیں ملیں گی جو ڈیٹا سائنس کے لیے ہیں۔

![Learn with AI series](../../translated_images/ur/3.9b58fd8d6c373c20.webp)

# مشین لرننگ برائے مبتدی — ایک نصاب

> 🌍 دنیا کے ثقافتوں کے ذریعے مشین لرننگ کا سفر کریں 🌍

Microsoft کے Cloud Advocates خوش ہیں کہ آپ کو مشین لرننگ کے بارے میں 12 ہفتوں کا، 26 اسباق پر مشتمل نصاب پیش کریں۔ اس نصاب میں، آپ سیکھیں گے جسے کبھی کبھار "کلاسیک مشین لرننگ" کہا جاتا ہے، جہاں بنیادی طور پر Scikit-learn لائبریری استعمال کی جاتی ہے اور ڈیپ لرننگ سے گریز کیا جاتا ہے، جو ہمارے [AI برائے مبتدیوں کے نصاب](https://aka.ms/ai4beginners) میں شامل ہے۔ ان اسباق کو ہمارے ['ڈیٹا سائنس برائے مبتدیوں کے نصاب'](https://aka.ms/ds4beginners) کے ساتھ جوڑیں۔

ہمارے ساتھ دنیا بھر کا سفر کریں جب ہم دنیا کے مختلف علاقوں سے ڈیٹا پر یہ کلاسیک تکنیکس لاگو کرتے ہیں۔ ہر سبق میں پری-اور پوسٹ-سبق کوئزز، تحریری ہدایات، حل، اسائنمنٹ، اور مزید شامل ہیں۔ ہمارا پروجیکٹ-پر مبنی طریقہ سیکھنے کو بنانے کے ساتھ جوڑتا ہے، جو نئے مہارتیں سیکھنے کے لیے مؤثر طریقہ ہے۔

**✍️ ہمارے مصنفین کا دل کی گہرائیوں سے شکریہ** جن لوپر، اسٹیفن ہاؤل، فرانسسکا لازیری، ٹومومی اِمورا، کیسی بریویو، دمتری سوشنیکوف، کرس نورنگ، انربن مکھرجی، اورنیلا آلتیونیان، روتھ یاکوبو اور ایمی بوئڈ

**🎨 ہمارے ил 地رز کا بھی شکریہ** ٹومومی اِمورا، داسانی مادیپالی، اور جن لوپر

**🙏 خصوصی شکریہ 🙏 ہمارے Microsoft اسٹوڈنٹ ایمبیسڈرز مصنفین، جائزہ لینے والوں، اور مواد فراہم کنندگان، خصوصاً رشیت دگلی، محمد ساکب خان انان، روہان راج، الیگزینڈرو پیٹریسکو، ابھشیک جیسوال، نوورین تبسم، ایوان سیمویلا، اور سنگدھا اگر وال کو**

**🤩 Microsoft اسٹوڈنٹ ایمبیسڈرز ایرک وانجاو، جیسلین سونڈی، اور ودشی گپتا کو ہمارے R اسباق کے لیے خاص شکریہ!**

# آغاز

مندرجہ ذیل اقدامات پر عمل کریں:  
1. **ریپوزٹری کو فورک کریں**: اس صفحے کے اوپری دائیں کونے میں "Fork" بٹن پر کلک کریں۔  
2. **ریپوزٹری کو کلون کریں**:  `git clone https://github.com/microsoft/ML-For-Beginners.git`

> [اس کورس کے تمام اضافی وسائل ہمارے Microsoft Learn کلیکشن میں تلاش کریں](https://learn.microsoft.com/en-us/collections/qrqzamz1nn2wx3?WT.mc_id=academic-77952-bethanycheum)

> 🔧 **مدد چاہیے؟** ہمارے [Troubleshooting Guide](TROUBLESHOOTING.md) میں انسٹالیشن، سیٹ اپ، اور اسباق چلانے کے عام مسائل کے حل تلاش کریں۔

**[طلباء](https://aka.ms/student-page)**، اس نصاب کو استعمال کرنے کے لیے، پورے ریپوزٹری کو اپنے GitHub اکاؤنٹ میں فورک کریں اور مشقیں خود یا گروپ کے ساتھ مکمل کریں:

- پری لیکچر کوئز سے شروع کریں۔  
- لیکچر پڑھیں اور سرگرمیاں مکمل کریں، ہر نالج چیک پر توقف کر کے غور کریں۔  
- کوشش کریں کہ اسباق کو سمجھ کر پروجیکٹس بنائیں بجائے حل کے کوڈ کو چلانے کے؛ تاہم یہ کوڈ ہر پروجیکٹ پر مبنی سبق میں `/solution` فولڈر میں دستیاب ہے۔  
- پوسٹ لیکچر کوئز لیں۔  
- چیلنج مکمل کریں۔  
- اسائنمنٹ مکمل کریں۔  
- کسی سبق گروپ کو مکمل کرنے کے بعد، [Discussion Board](https://github.com/microsoft/ML-For-Beginners/discussions) پر جائیں اور مناسب PAT روبریک بھر کر "زور سے سیکھیں"۔ 'PAT' ایک پراگریس اسیسمنٹ ٹول ہے جسے آپ بھر کر اپنی سیکھ کو آگے بڑھاتے ہیں۔ آپ دوسرے PATs پر بھی ردعمل دے سکتے ہیں تاکہ ہم ایک ساتھ سیکھ سکیں۔

> اگلے مطالعے کے لیے، ہم ان [Microsoft Learn](https://docs.microsoft.com/en-us/users/jenlooper-2911/collections/k7o7tg1gp306q4?WT.mc_id=academic-77952-leestott) ماڈیولز اور لرننگ پاتھز کی پیروی کرنے کا مشورہ دیتے ہیں۔

**اساتذہ**، ہم نے [کچھ تجاویز](for-teachers.md) شامل کی ہیں کہ اس نصاب کو کیسے استعمال کیا جائے۔

---

## ویڈیو واک تھروز

کچھ اسباق مختصر ویڈیوز کی شکل میں دستیاب ہیں۔ آپ ان سب کو اسباق میں لائن کے اندر یا [Microsoft Developer YouTube چینل پر ML for Beginners پلیلسٹ](https://aka.ms/ml-beginners-videos) پر نیچے دی گئی تصویر پر کلک کر کے دیکھ سکتے ہیں۔

[![ML for beginners banner](../../translated_images/ur/ml-for-beginners-video-banner.63f694a100034bc6.webp)](https://aka.ms/ml-beginners-videos)

---

## ٹیم سے ملو

[![پرومو ویڈیو](../../images/ml.gif)](https://youtu.be/Tj1XWrDSYJU)

**گیف بذریعہ** [Mohit Jaisal](https://linkedin.com/in/mohitjaisal)

> 🎥 پروجیکٹ اور بنانے والوں کے بارے میں ویڈیو دیکھنے کے لیے اوپر دی گئی تصویر پر کلک کریں!

---

## تدریسی طریقہ کار

ہم نے اس نصاب کی تیاری کے دوران دو تدریسی اصول چنے ہیں: یہ کہ یہ عملی طور پر **پروجیکٹ پر مبنی** ہو اور اس میں **بار بار کوئزز** شامل ہوں۔ علاوہ ازیں، اس نصاب کو مربوط بنانے کے لیے ایک مشترکہ **موضوع** بھی ہے۔

پروجیکٹس کے ساتھ مواد کو ہم آہنگ کر کے، طلباء کے لیے عمل مزید دلچسپ بنایا جاتا ہے اور تصورات کا مضبوطی سے یاد رہنا ممکن ہوتا ہے۔ علاوہ ازیں، کلاس سے پہلے ایک کم دباو والا کوئز طالب علم کے سیکھنے کے ارادے کو قائم کرتا ہے، جب کہ کلاس کے بعد دوسرا کوئز زیادہ مضبوط یاددہانی یقینی بناتا ہے۔ یہ نصاب لچکدار اور خوشگوار انداز میں بنایا گیا ہے اور پورے یا جزوی طور پر لیا جا سکتا ہے۔ پروجیکٹس چھوٹے آغاز ہوتے ہیں اور 12 ہفتوں کے دورانیے کے آخر تک پیچیدہ ہو جاتے ہیں۔ اس نصاب میں مشین لرننگ کے حقیقی دنیا میں استعمالات پر بھی ایک اضافی تحریر شامل ہے، جسے آپ اضافی کریڈٹ کے طور پر یا بحث کے لیے بنیاد کے طور پر استعمال کر سکتے ہیں۔

> ہمارا [Code of Conduct](CODE_OF_CONDUCT.md)، [Contributing](CONTRIBUTING.md)، [Translation](TRANSLATIONS.md)، اور [Troubleshooting](TROUBLESHOOTING.md) گائیڈلائنز دیکھیں۔ ہم آپ کے تعمیری فیڈ بیک کا خیرمقدم کرتے ہیں!

## ہر سبق میں شامل ہیں

- اختیاری سکیچ نوٹ  
- اختیاری معاون ویڈیو  
- ویڈیو واک تھرو (کچھ اسباق کے لیے)  
- [پری لیکچر وارم اپ کوئز](https://ff-quizzes.netlify.app/en/ml/)  
- تحریری درس  
- پروجیکٹ-پر مبنی اسباق کے لیے، مرحلہ وار گائیڈز پروجیکٹ بنانے کے طریقے پر  
- نالج چیکس  
- ایک چیلنج  
- معاون مطالعہ  
- اسائنمنٹ  
- [پوسٹ لیکچر کوئز](https://ff-quizzes.netlify.app/en/ml/)

> **زبانوں کے بارے میں ایک نوٹ**: یہ اسباق بنیادی طور پر Python میں لکھے گئے ہیں، لیکن بہت سے R میں بھی دستیاب ہیں۔ R سبق مکمل کرنے کے لیے، `/solution` فولڈر میں جائیں اور R اسباق تلاش کریں۔ ان میں .rmd ایکسٹینشن ہوتی ہے جو کہ **R مارک ڈاؤن** فائل کی نمائندگی کرتی ہے، جسے سادہ الفاظ میں R یا دیگر زبانوں کے کوڈ چنکس اور ایک YAML ہیڈر کو مارک ڈاؤن ڈاکیومنٹ میں شامل کرنے کے لیے استعمال کیا جاتا ہے۔ اس طرح یہ ڈیٹا سائنس کے لیے ایک مثالی تحریری فریم ورک کے طور پر کام کرتا ہے کیونکہ یہ آپ کو اپنے کوڈ، اس کے نتائج، اور اپنے خیالات مارک ڈاؤن میں لکھنے کی اجازت دیتا ہے۔ مزید برآں، R مارک ڈاؤن ڈاکیومنٹس PDF، HTML، یا Word جیسے آؤٹ پٹ فارمیٹس میں رینڈر کیے جا سکتے ہیں۔
> **کویزز کے بارے میں ایک نوٹ**: تمام کویزز [Quiz App فولڈر](../../quiz-app) میں موجود ہیں، کل 52 کویزز ہر ایک میں تین سوالات شامل ہیں۔ یہ اسباق کے اندر سے لنک کیے گئے ہیں لیکن کوئز ایپ کو لوکل طور پر چلایا جا سکتا ہے؛ لوکل ہوسٹ کرنے یا Azure پر تعینات کرنے کے لیے `quiz-app` فولڈر میں دی گئی ہدایات پر عمل کریں۔

| سبق نمبر |                             موضوع                              |                   سبق کی ترتیب                   | سیکھنے کے مقاصد                                                                                                             |                                                              منسلک سبق                                                               |                        مصنف                        |
| :------: | :------------------------------------------------------------: | :----------------------------------------------: | ----------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------: |
|    01    |                مشین لرننگ کا تعارف                |      [تعارف](1-Introduction/README.md)       | مشین لرننگ کے بنیادی تصورات سیکھیں                                                                                |                                             [سبق](1-Introduction/1-intro-to-ML/README.md)                                             |                       محمد                       |
|    02    |                مشین لرننگ کی تاریخ                 |      [تعارف](1-Introduction/README.md)       | اس میدان کی تاریخی جانکاری حاصل کریں                                                                                         |                                            [سبق](1-Introduction/2-history-of-ML/README.md)                                            |                     جین اور ایمی                      |
|    03    |                 انصاف اور مشین لرننگ                 |      [تعارف](1-Introduction/README.md)       | انصاف کے اہم فلسفیانہ مسائل کیا ہیں جو طلباء کو مشین لرننگ ماڈلز بنانے اور لاگو کرتے وقت غور کرنا چاہیے؟ |                                              [سبق](1-Introduction/3-fairness/README.md)                                               |                        ٹومومی                        |
|    04    |                مشین لرننگ کی تکنیکیں                 |      [تعارف](1-Introduction/README.md)       | مشین لرننگ محققین کون سی تکنیکیں استعمال کرتے ہیں ماڈلز بنانے کے لیے؟                                                                       |                                          [سبق](1-Introduction/4-techniques-of-ML/README.md)                                           |                    کرس اور جین                     |
|    05    |                   رجریشن کا تعارف                   |        [رجریشن](2-Regression/README.md)         | رجریشن ماڈلز کے لیے Python اور Scikit-learn کے ساتھ شروعات کریں                                                                  |         [پائتھن](2-Regression/1-Tools/README.md) • [آر](../../2-Regression/1-Tools/solution/R/lesson_1.html)         |      جین • اریک وانجاؤ       |
|    06    |                شمالی امریکہ کے کدو کی قیمتیں 🎃                |        [رجریشن](2-Regression/README.md)         | مشین لرننگ کے لیے ڈیٹا کو ویژولائز اور صاف کریں                                                                                  |          [پائتھن](2-Regression/2-Data/README.md) • [آر](../../2-Regression/2-Data/solution/R/lesson_2.html)          |      جین • اریک وانجاؤ       |
|    07    |                شمالی امریکہ کے کدو کی قیمتیں 🎃                |        [رجریشن](2-Regression/README.md)         | خطی اور کثیر رکنی رجریشن ماڈل بنائیں                                                                                   |        [پائتھن](2-Regression/3-Linear/README.md) • [آر](../../2-Regression/3-Linear/solution/R/lesson_3.html)        |      جین اور دمتری • اریک وانجاؤ       |
|    08    |                شمالی امریکہ کے کدو کی قیمتیں 🎃                |        [رجریشن](2-Regression/README.md)         | لاجسٹک رجریشن ماڈل بنائیں                                                                                               |     [پائتھن](2-Regression/4-Logistic/README.md) • [آر](../../2-Regression/4-Logistic/solution/R/lesson_4.html)      |      جین • اریک وانجاؤ       |
|    09    |                          ایک ویب ایپ 🔌                          |           [ویب ایپ](3-Web-App/README.md)            | اپنے تربیت شدہ ماڈل کو استعمال کرنے کے لیے ویب ایپ بنائیں                                                                                       |                                                 [پائتھن](3-Web-App/1-Web-App/README.md)                                                  |                         جین                          |
|    10    |                 درجہ بندی کا تعارف                 |    [درجہ بندی](4-Classification/README.md)     | اپنے ڈیٹا کو صاف کریں، تیار کریں، اور ویژولائز کریں؛ درجہ بندی کا تعارف                                                            | [پائتھن](4-Classification/1-Introduction/README.md) • [آر](../../4-Classification/1-Introduction/solution/R/lesson_10.html)  | جین اور کیسی • اریک وانجاؤ |
|    11    |             لذیذ ایشیائی اور ہندی کھانے 🍜             |    [درجہ بندی](4-Classification/README.md)     | درجہ بندی کرنے والوں کا تعارف                                                                                                     | [پائتھن](4-Classification/2-Classifiers-1/README.md) • [آر](../../4-Classification/2-Classifiers-1/solution/R/lesson_11.html) | جین اور کیسی • اریک وانجاؤ |
|    12    |             لذیذ ایشیائی اور ہندی کھانے 🍜             |    [درجہ بندی](4-Classification/README.md)     | مزید درجہ بندی کرنے والے                                                                                                                | [پائتھن](4-Classification/3-Classifiers-2/README.md) • [آر](../../4-Classification/3-Classifiers-2/solution/R/lesson_12.html) | جین اور کیسی • اریک وانجاؤ |
|    13    |             لذیذ ایشیائی اور ہندی کھانے 🍜             |    [درجہ بندی](4-Classification/README.md)     | اپنے ماڈل کا استعمال کرتے ہوئے ری کومنڈر ویب ایپ بنائیں                                                                                    |                                              [پائتھن](4-Classification/4-Applied/README.md)                                              |                         جین                          |
|    14    |                   کلسٹرنگ کا تعارف                   |        [کلسٹرنگ](5-Clustering/README.md)         | اپنے ڈیٹا کو صاف کریں، تیار کریں، اور ویژولائز کریں؛ کلسٹرنگ کا تعارف                                                                |         [پائتھن](5-Clustering/1-Visualize/README.md) • [آر](../../5-Clustering/1-Visualize/solution/R/lesson_14.html)         |      جین • اریک وانجاؤ       |
|    15    |              نائجیرین موسیقی کے ذوق کا جائزہ 🎧              |        [کلسٹرنگ](5-Clustering/README.md)         | K-Means کلسٹرنگ طریقہ دریافت کریں                                                                                           |           [پائتھن](5-Clustering/2-K-Means/README.md) • [آر](../../5-Clustering/2-K-Means/solution/R/lesson_15.html)           |      جین • اریک وانجاؤ       |
|    16    |        زبان کی قدرتی پروسیسنگ کا تعارف ☕️         |   [قدرتی زبان کی پروسیسنگ](6-NLP/README.md)    | NLP کی بنیادی باتیں سیکھیں ایک سادہ بوٹ بنا کر                                                                             |                                             [پائتھن](6-NLP/1-Introduction-to-NLP/README.md)                                              |                       سٹیفن                        |
|    17    |                      عام NLP کے کام ☕️                      |   [قدرتی زبان کی پروسیسنگ](6-NLP/README.md)    | زبان کی ساخت کے ساتھ کام کرتے ہوئے مطلوبہ عام کاموں کو سمجھ کر اپنی NLP کی مہارت کو گہرا کریں                          |                                                    [پائتھن](6-NLP/2-Tasks/README.md)                                                     |                       سٹیفن                        |
|    18    |             ترجمہ اور جذباتی تجزیہ ♥️              |   [قدرتی زبان کی پروسیسنگ](6-NLP/README.md)    | جین آسٹن کے ساتھ ترجمہ اور جذباتی تجزیہ                                                                             |                                            [پائتھن](6-NLP/3-Translation-Sentiment/README.md)                                             |                       سٹیفن                        |
|    19    |                  یورپ کے رومانوی ہوٹل ♥️                  |   [قدرتی زبان کی پروسیسنگ](6-NLP/README.md)    | ہوٹل کا جائزہ 1 کے ساتھ جذباتی تجزیہ                                                                                         |                                               [پائتھن](6-NLP/4-Hotel-Reviews-1/README.md)                                                |                       سٹیفن                        |
|    20    |                  یورپ کے رومانوی ہوٹل ♥️                  |   [قدرتی زبان کی پروسیسنگ](6-NLP/README.md)    | ہوٹل کا جائزہ 2 کے ساتھ جذباتی تجزیہ                                                                                         |                                               [پائتھن](6-NLP/5-Hotel-Reviews-2/README.md)                                                |                       سٹیفن                        |
|    21    |            وقت کی سیریز کی پیش گوئی کا تعارف             |        [وقت کی سیریز](7-TimeSeries/README.md)        | وقت کی سیریز کی پیش گوئی کا تعارف                                                                                         |                                             [پائتھن](7-TimeSeries/1-Introduction/README.md)                                              |                      فرانسسکا                       |
|    22    | ⚡️ عالمی توانائی کا استعمال ⚡️ - ARIMA کے ساتھ وقت کی سیریز کی پیش گوئی |        [وقت کی سیریز](7-TimeSeries/README.md)        | ARIMA کے ساتھ وقت کی سیریز کی پیش گوئی                                                                                              |                                                 [پائتھن](7-TimeSeries/2-ARIMA/README.md)                                                 |                      فرانسسکا                       |
|    23    |  ⚡️ عالمی توانائی کا استعمال ⚡️ - SVR کے ساتھ وقت کی سیریز کی پیش گوئی  |        [وقت کی سیریز](7-TimeSeries/README.md)        | سپورٹ ویکٹر ریگریسر کے ساتھ وقت کی سیریز کی پیش گوئی                                                                           |                                                  [پائتھن](7-TimeSeries/3-SVR/README.md)                                                  |                       انربن                        |
|    24    |             ری انفورسمنٹ لرننگ کا تعارف             | [ری انفورسمنٹ لرننگ](8-Reinforcement/README.md) | Q-لرننگ کے ذریعے ری انفورسمنٹ لرننگ کا تعارف                                                                          |                                             [پائتھن](8-Reinforcement/1-QLearning/README.md)                                              |                        دمتری                        |
|    25    |                 پیٹر کو بھیڑیے سے بچائیں! 🐺                  | [ری انفورسمنٹ لرننگ](8-Reinforcement/README.md) | ری انفورسمنٹ لرننگ جم                                                                                                      |                                                [پائتھن](8-Reinforcement/2-Gym/README.md)                                                 |                        دمتری                        |
|  پس منظر   |            حقیقی دنیا میں ایم ایل کے منظرنامے اور اطلاقات            |      [جنگل میں ایم ایل](9-Real-World/README.md)       | کلاسیکی مشین لرننگ کی دلچسپ اور بامعنی حقیقی دنیا کی اطلاقات                                                               |                                             [سبق](9-Real-World/1-Applications/README.md)                                              |                         ٹیم                         |
|  پس منظر   |            RAI ڈیش بورڈ کے ساتھ ایم ایل میں ماڈل کی خرابیوں کی جانچ          |      [جنگل میں ایم ایل](9-Real-World/README.md)       | ذمہ دار AI ڈیش بورڈ اجزاء استعمال کرتے ہوئے مشین لرننگ میں ماڈل کی خرابیوں کی شناخت                                                              |                                             [سبق](9-Real-World/2-Debugging-ML-Models/README.md)                                              |                         روتھ یاکوبو                       |

> [اس کورس کے تمام اضافی وسائل ہماری Microsoft Learn کلیکشن میں تلاش کریں](https://learn.microsoft.com/en-us/collections/qrqzamz1nn2wx3?WT.mc_id=academic-77952-bethanycheum)

## آف لائن رسائی

آپ اس دستاویزات کو آف لائن [Docsify](https://docsify.js.org/#/) استعمال کرکے چلا سکتے ہیں۔ اس ریپوزٹری کو فورک کریں، [Docsify انسٹال کریں](https://docsify.js.org/#/quickstart) اپنے مقامی کمپیوٹر پر، اور پھر اس ریپوزٹری کے روٹ فولڈر میں یہ ٹائپ کریں `docsify serve`۔ ویب سائٹ آپ کے مقامی کمپیوٹر پر پورٹ 3000 پر دستیاب ہوگی: `localhost:3000`۔

## پی ڈی ایفز

نصاب کا ایک پی ڈی ایف ورژن لنکس کے ساتھ [یہاں](https://microsoft.github.io/ML-For-Beginners/pdf/readme.pdf) دستیاب ہے۔

## 🎒 دیگر کورسز

ہماری ٹیم دیگر کورسز بھی بناتی ہے! دیکھیں:

<!-- CO-OP TRANSLATOR OTHER COURSES START -->
### LangChain
[![نو آموزوں کے لیے LangChain4j](https://img.shields.io/badge/LangChain4j%20for%20Beginners-22C55E?style=for-the-badge&&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchain4j-for-beginners)
[![نو آموزوں کے لیے LangChain.js](https://img.shields.io/badge/LangChain.js%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchainjs-for-beginners?WT.mc_id=m365-94501-dwahlin)

---

### Azure / Edge / MCP / Agents
[![نو آموزوں کے لیے AZD](https://img.shields.io/badge/AZD%20for%20Beginners-0078D4?style=for-the-badge&labelColor=E5E7EB&color=0078D4)](https://github.com/microsoft/AZD-for-beginners?WT.mc_id=academic-105485-koreyst)
[![نو آموزوں کے لیے Edge AI](https://img.shields.io/badge/Edge%20AI%20for%20Beginners-00B8E4?style=for-the-badge&labelColor=E5E7EB&color=00B8E4)](https://github.com/microsoft/edgeai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![نو آموزوں کے لیے MCP](https://img.shields.io/badge/MCP%20for%20Beginners-009688?style=for-the-badge&labelColor=E5E7EB&color=009688)](https://github.com/microsoft/mcp-for-beginners?WT.mc_id=academic-105485-koreyst)
[![نو آموزوں کے لیے AI Agents](https://img.shields.io/badge/AI%20Agents%20for%20Beginners-00C49A?style=for-the-badge&labelColor=E5E7EB&color=00C49A)](https://github.com/microsoft/ai-agents-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### جنریٹیو AI سیریز
[![نو آموزوں کے لیے تخلیقی AI](https://img.shields.io/badge/Generative%20AI%20for%20Beginners-8B5CF6?style=for-the-badge&labelColor=E5E7EB&color=8B5CF6)](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![تخلیقی AI (.NET)](https://img.shields.io/badge/Generative%20AI%20(.NET)-9333EA?style=for-the-badge&labelColor=E5E7EB&color=9333EA)](https://github.com/microsoft/Generative-AI-for-beginners-dotnet?WT.mc_id=academic-105485-koreyst)
[![تخلیقی AI (جاوا)](https://img.shields.io/badge/Generative%20AI%20(Java)-C084FC?style=for-the-badge&labelColor=E5E7EB&color=C084FC)](https://github.com/microsoft/generative-ai-for-beginners-java?WT.mc_id=academic-105485-koreyst)
[![تخلیقی AI (جاوا اسکرپٹ)](https://img.shields.io/badge/Generative%20AI%20(JavaScript)-E879F9?style=for-the-badge&labelColor=E5E7EB&color=E879F9)](https://github.com/microsoft/generative-ai-with-javascript?WT.mc_id=academic-105485-koreyst)

---
 
### بنیادی تعلیم
[![نو آموزوں کے لیے مشین لرننگ](https://img.shields.io/badge/ML%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=22C55E)](https://aka.ms/ml-beginners?WT.mc_id=academic-105485-koreyst)
[![نو آموزوں کے لیے ڈیٹا سائنس](https://img.shields.io/badge/Data%20Science%20for%20Beginners-84CC16?style=for-the-badge&labelColor=E5E7EB&color=84CC16)](https://aka.ms/datascience-beginners?WT.mc_id=academic-105485-koreyst)
[![نو آموزوں کے لیے AI](https://img.shields.io/badge/AI%20for%20Beginners-A3E635?style=for-the-badge&labelColor=E5E7EB&color=A3E635)](https://aka.ms/ai-beginners?WT.mc_id=academic-105485-koreyst)
[![نو آموزوں کے لیے سائبر سیکیورٹی](https://img.shields.io/badge/Cybersecurity%20for%20Beginners-F97316?style=for-the-badge&labelColor=E5E7EB&color=F97316)](https://github.com/microsoft/Security-101?WT.mc_id=academic-96948-sayoung)
[![نو آموزوں کے لیے ویب ڈیولپمنٹ](https://img.shields.io/badge/Web%20Dev%20for%20Beginners-EC4899?style=for-the-badge&labelColor=E5E7EB&color=EC4899)](https://aka.ms/webdev-beginners?WT.mc_id=academic-105485-koreyst)
[![نو آموزوں کے لیے آئی او ٹی](https://img.shields.io/badge/IoT%20for%20Beginners-14B8A6?style=for-the-badge&labelColor=E5E7EB&color=14B8A6)](https://aka.ms/iot-beginners?WT.mc_id=academic-105485-koreyst)
[![نو آموزوں کے لیے ایکس آر ڈیولپمنٹ](https://img.shields.io/badge/XR%20Development%20for%20Beginners-38BDF8?style=for-the-badge&labelColor=E5E7EB&color=38BDF8)](https://github.com/microsoft/xr-development-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### کو پائلٹ سیریز
[![AI جوڑے پروگرامنگ کے لیے کو پائلٹ](https://img.shields.io/badge/Copilot%20for%20AI%20Paired%20Programming-FACC15?style=for-the-badge&labelColor=E5E7EB&color=FACC15)](https://aka.ms/GitHubCopilotAI?WT.mc_id=academic-105485-koreyst)
[![C#/.NET کے لیے کو پائلٹ](https://img.shields.io/badge/Copilot%20for%20C%23/.NET-FBBF24?style=for-the-badge&labelColor=E5E7EB&color=FBBF24)](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers?WT.mc_id=academic-105485-koreyst)
[![کو پائلٹ ایڈونچر](https://img.shields.io/badge/Copilot%20Adventure-FDE68A?style=for-the-badge&labelColor=E5E7EB&color=FDE68A)](https://github.com/microsoft/CopilotAdventures?WT.mc_id=academic-105485-koreyst)
<!-- CO-OP TRANSLATOR OTHER COURSES END -->

## مدد حاصل کرنا

اگر آپ پھنس جائیں یا AI ایپس بنانے کے بارے میں کوئی سوال ہو۔ MCP پر ساتھی سیکھنے والوں اور تجربہ کار ڈویلپرز کے ساتھ مباحثوں میں شامل ہوں۔ یہ ایک معاون کمیونٹی ہے جہاں سوالات خوش آمدید ہیں اور علم آزادانہ طور پر شیئر کیا جاتا ہے۔

[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

اگر آپ کے پاس پروڈکٹ فیڈبیک یا بنانے کے دوران کوئی غلطی ہو تو وزٹ کریں:

[![Microsoft Foundry Developer Forum](https://img.shields.io/badge/GitHub-Microsoft_Foundry_Developer_Forum-blue?style=for-the-badge&logo=github&color=000000&logoColor=fff)](https://aka.ms/foundry/forum)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**اس بات کا اعلان**:
اس دستاویز کا ترجمہ AI ترجمہ سروس [Co-op Translator](https://github.com/Azure/co-op-translator) کے ذریعے کیا گیا ہے۔ اگرچہ ہم درستگی کے لیے کوشاں ہیں، براہِ کرم یہ بات ذہن میں رکھیں کہ خودکار تراجم میں غلطیاں یا بے ضابطگیاں ہو سکتی ہیں۔ اصلی دستاویز اپنی مادری زبان میں مستند ماخذ سمجھی جانی چاہیے۔ اہم معلومات کے لیے پیشہ ور انسانی ترجمہ تجویز کیا جاتا ہے۔ اس ترجمے کے استعمال سے پیدا ہونے والی کسی بھی غلط فہمی یا غلط تشریح کے لیے ہم ذمہ دار نہیں ہیں۔
<!-- CO-OP TRANSLATOR DISCLAIMER END -->