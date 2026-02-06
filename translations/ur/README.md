[![GitHub license](https://img.shields.io/github/license/microsoft/ML-For-Beginners.svg)](https://github.com/microsoft/ML-For-Beginners/blob/master/LICENSE)
[![GitHub contributors](https://img.shields.io/github/contributors/microsoft/ML-For-Beginners.svg)](https://GitHub.com/microsoft/ML-For-Beginners/graphs/contributors/)
[![GitHub issues](https://img.shields.io/github/issues/microsoft/ML-For-Beginners.svg)](https://GitHub.com/microsoft/ML-For-Beginners/issues/)
[![GitHub pull-requests](https://img.shields.io/github/issues-pr/microsoft/ML-For-Beginners.svg)](https://GitHub.com/microsoft/ML-For-Beginners/pulls/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/ML-For-Beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/ML-For-Beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/ML-For-Beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/ML-For-Beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/ML-For-Beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/ML-For-Beginners/stargazers/)

### 🌐 کثیراللسانی مدد

#### GitHub Action کے ذریعہ معاونت یافتہ (خودکار اور ہمیشہ اپ ٹو ڈیٹ)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](./README.md) | [Vietnamese](../vi/README.md)

> **مقامی طور پر کلوون کرنا پسند کریں؟**

> اس ذخیرے میں 50+ زبانوں کے ترجمے شامل ہیں جو ڈاؤن لوڈ سائز میں نمایاں اضافہ کرتے ہیں۔ بغیر ترجموں کے کلون کرنے کے لیے sparse checkout استعمال کریں:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/microsoft/ML-For-Beginners.git
> cd ML-For-Beginners
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> یہ آپ کو کورس مکمل کرنے کے لئے ہر چیز فراہم کرتا ہے ایک بہت تیز ڈاؤن لوڈ کے ساتھ۔
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

#### ہماری کمیونٹی میں شامل ہوں

[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

ہمارے پاس AI کے ساتھ سیکھنے کی ایک سلسلہ جاری ہے، مزید جاننے اور شامل ہونے کے لئے [Learn with AI Series](https://aka.ms/learnwithai/discord) پر آئیں، تاریخ 18 - 30 ستمبر، 2025۔ آپ کو GitHub Copilot کے ذریعہ ڈیٹا سائنس کے استعمال کے ٹپس اور ٹرکس ملیں گے۔

![Learn with AI series](../../translated_images/ur/3.9b58fd8d6c373c20.webp)

# نو آموزوں کے لئے مشین لرننگ - ایک نصاب

> 🌍 دنیا کی ثقافتوں کے ذریعے مشین لرننگ کو دریافت کرتے ہوئے دنیا کے چکر لگائیں 🌍

Microsoft کے کلاؤڈ ایڈووکیٹس مشین لرننگ کے بارے میں 12 ہفتوں، 26 اسباق کا ایک نصاب پیش کرتے ہیں۔ اس نصاب میں آپ اس تکنیک کو سیکھیں گے جسے کبھی کبھار **کلاسیکی مشین لرننگ** کہا جاتا ہے، جو بنیادی طور پر Scikit-learn لائبریری کا استعمال کرتی ہے اور ڈیپ لرننگ سے گریز کرتی ہے، جس کا احاطہ ہمارے [AI for Beginners' نصاب](https://aka.ms/ai4beginners) میں کیا گیا ہے۔ ان اسباق کو ہمارے ['Data Science for Beginners' نصاب](https://aka.ms/ds4beginners) کے ساتھ جوڑا جا سکتا ہے۔

ہمارے ساتھ دنیا کے مختلف حصوں کے ڈیٹا پر یہ کلاسیکی تکنیکز نافذ کرنے کا سفر کریں۔ ہر سبق میں پہلے اور بعد میں کوئزز شامل ہیں، اسباق مکمل کرنے کے لئے تحریری ہدایات، حل، اسائنمنٹ اور بہت کچھ۔ ہمارا پروجیکٹ-بنیاد طریقہ آپ کو سیکھتے ہوئے بنانے کی اجازت دیتا ہے، جو نئی مہارتوں کو یاد رکھنے کا مؤثر طریقہ ہے۔

**✍️ ہماری مصنفین کا دلی شکریہ** جن لوپر، اسٹیفن ہاؤل، فرانسسکا لازیری، تومومی ایمورا، کیسی بریویو، دمتری سوشنکوف، کرس نورنگ، انربن مکھرجی، اورنیلا آلتیونین، روتھ یاکوبو اور ایمی بوئڈ

**🎨 شکریہ ہمارے مصورین کا** تومومی ایمورا، داسانی مادپالی، اور جن لوپر

**🙏 خاص شکریہ ہمارے Microsoft اسٹوڈنٹ ایمبیسیڈر مصنفین، جائزہ کار اور مواد فراہم کرنے والوں کو**، خصوصاً رشت دگلی، محمد ساکب خان اینان، روہان راج، الیگزنڈرو پیٹریسکو، ابھیشیک جیسوال، نویرن تبسم، یوان سامیولا، اور سگڈھا اگروال

**🤩 اضافی شکریہ Microsoft اسٹوڈنٹ ایمبیسیڈرز ایرک وانجاؤ، جزلین سندھی اور ویدوشی گپتا کو ہمارے R اسباق کے لئے!**

# شروع کریں

مندرجہ ذیل اقدامات کریں:
1. **ریزپوزٹری کو فورک کریں**: اس صفحہ کے اوپر دائیں جانب "Fork" بٹن پر کلک کریں۔
2. **ریزپوزٹری کو کلون کریں**: `git clone https://github.com/microsoft/ML-For-Beginners.git`

> [اس کورس کے تمام اضافی وسائل ہمارے Microsoft Learn کلیکشن میں تلاش کریں](https://learn.microsoft.com/en-us/collections/qrqzamz1nn2wx3?WT.mc_id=academic-77952-bethanycheum)

> 🔧 **مدد چاہیے؟** ہمارے [ٹربل شوٹنگ گائیڈ](TROUBLESHOOTING.md) کو چیک کریں جو انسٹالیشن، سیٹ اپ، اور اسباق چلانے کے عام مسائل کے حل فراہم کرتا ہے۔

**[طلباء](https://aka.ms/student-page)**، اس نصاب کو استعمال کرنے کے لئے، پورے رپوزٹری کو اپنے GitHub اکاؤنٹ پر فورک کریں اور مشقیں خود سے یا گروپ کے ساتھ مکمل کریں:

- پری لیکچر کوئز سے شروع کریں۔
- لیکچر پڑھیں اور سرگرمیاں مکمل کریں، ہر علمی چیک پر رک کر غور کریں۔
- پروجیکٹس بنانے کی کوشش کریں اسباق کو سمجھ کر بجائے حل کے کوڈ کو چلانے کے؛ البتہ یہ کوڈ ہر پروجیکٹ پر مبنی سبق میں `/solution` فولڈر میں دستیاب ہے۔
- پوسٹ لیکچر کوئز حل کریں۔
- چیلنج مکمل کریں۔
- اسائنمنٹ مکمل کریں۔
- ایک سبق کے گروپ مکمل کرنے کے بعد، [Discussion Board](https://github.com/microsoft/ML-For-Beginners/discussions) پر جائیں اور مناسب PAT روبریک بھر کر "آواز بلند کریں"۔ 'PAT' ایک Progress Assessment Tool ہے جو آپ کی سیکھنے میں مدد دیتا ہے۔ آپ دوسرے PATs پر ردعمل بھی دے سکتے ہیں تاکہ ہم سب مل کر سیکھ سکیں۔

> مزید مطالعات کے لئے، ہم آپ کو یہ [Microsoft Learn](https://docs.microsoft.com/en-us/users/jenlooper-2911/collections/k7o7tg1gp306q4?WT.mc_id=academic-77952-leestott) ماڈیولز اور سیکھنے کے راستے اپنانے کی سفارش کرتے ہیں۔

**اساتذہ**، ہم نے [کچھ تجاویز شامل کی ہیں](for-teachers.md) کہ اس نصاب کو کیسے استعمال کیا جائے۔

---

## ویڈیو واک تھروز

کچھ اسباق مختصر ویڈیو کے طور پر دستیاب ہیں۔ آپ انہیں سبھی اسباق میں لائن میں یا [Microsoft Developer YouTube چینل پر ML for Beginners کی پلے لسٹ](https://aka.ms/ml-beginners-videos) پر نیچے دی گئی تصویر پر کلک کرکے دیکھ سکتے ہیں۔

[![ML for beginners banner](../../translated_images/ur/ml-for-beginners-video-banner.63f694a100034bc6.webp)](https://aka.ms/ml-beginners-videos)

---

## ٹیم سے ملو

[![Promo video](../../images/ml.gif)](https://youtu.be/Tj1XWrDSYJU)

**گیف بذریعہ** [Mohit Jaisal](https://linkedin.com/in/mohitjaisal)

> 🎥 پروجیکٹ اور اس کے بانیوں کے بارے میں ویڈیو کے لئے اوپر تصویر پر کلک کریں!

---

## تدریسی طریقہ کار

ہم نے اس نصاب کی تعمیر میں دو تعلیمی اصول منتخب کیے ہیں: یہ یقینی بنانا کہ یہ ہاتھوں سے کام کرنے والا **پروجیکٹ-بنیاد** ہو اور اس میں **بار بار کوئزز** شامل ہوں۔ اس کے علاوہ، یہ نصاب ایک مشترکہ **موضوع** رکھتا ہے تاکہ اس میں ہم آہنگی پیدا ہو۔

اس بات کو یقینی بنا کر کہ مواد پروجیکٹس کے ساتھ ہم آہنگ ہے، طلباء کے لیے عمل زیادہ دلچسپ بنایا جاتا ہے اور تصورات کی یادداشت میں اضافہ ہوتا ہے۔ اس کے علاوہ، کلاس سے پہلے ہونے والا کم داؤ والا کوئز طالبعلم کے ارادے کو کسی موضوع کے سیکھنے کی طرف متوجہ کرتا ہے، جبکہ کلاس کے بعد دوسرا کوئز مزید یادداشت کو یقینی بناتا ہے۔ یہ نصاب لچکدار اور دلچسپ بنانے کے لئے ڈیزائن کیا گیا ہے اور اسے مکمل یا جزوی طور پر لیا جا سکتا ہے۔ پروجیکٹس چھوٹے شروع ہوتے ہیں اور 12 ہفتوں کے دورانیے کے آخر تک بڑھتے جاتے ہیں۔ اس نصاب میں ML کے حقیقی دنیا میں اطلاقات پر پوسٹ اسکرپٹ بھی شامل ہے، جسے اضافی کریڈٹ یا مباحثے کی بنیاد کے طور پر استعمال کیا جا سکتا ہے۔

> ہمارا [کوڈ آف کنڈکٹ](CODE_OF_CONDUCT.md)، [کنٹریبیوٹنگ](CONTRIBUTING.md)، [ترجمہ](TRANSLATIONS.md)، اور [ٹربل شوٹنگ](TROUBLESHOOTING.md) رہنما خطوط دیکھیں۔ ہم آپ کی تعمیری رائے کے خیرمقدم کرتے ہیں!

## ہر سبق میں شامل ہیں

- اختیاری سکیچ نوٹ
- اختیاری اضافی ویڈیو
- ویڈیو واک تھرو (صرف کچھ اسباق)
- [پری لیکچر وارم اپ کوئز](https://ff-quizzes.netlify.app/en/ml/)
- تحریری سبق
- پروجیکٹ پر مبنی اسباق کے لئے پروجیکٹ بنانے کے مرحلہ وار رہنما
- علمی چیک
- چیلنج
- اضافی مطالعہ
- اسائنمنٹ
- [پوسٹ لیکچر کوئز](https://ff-quizzes.netlify.app/en/ml/)

> **زبانوں کے بارے میں ایک نوٹ**: یہ اسباق بنیادی طور پر Python میں لکھے گئے ہیں، لیکن بہت سے R میں بھی دستیاب ہیں۔ R سبق مکمل کرنے کے لیے `/solution` فولڈر میں جائیں اور R اسباق تلاش کریں۔ ان میں .rmd توسیع شامل ہوتی ہے جو کہ **R Markdown** فائل کی نمائندگی کرتی ہے، جسے آسانی سے اس طرح بیان کیا جا سکتا ہے کہ یہ `code chunks` (R یا دیگر زبانوں کے) اور `YAML header` (جو آؤٹ پٹ جیسے PDF کی فارمیٹنگ کو ہدایت دیتا ہے) کو ایک `Markdown document` میں شامل کرتا ہے۔ اس طرح یہ ڈیٹا سائنس کے لیے ایک نمونہ مصنف فریم ورک کے طور پر کام کرتا ہے کیونکہ یہ آپ کو اپنے کوڈ، اس کا آؤٹ پٹ، اور اپنے خیالات کو Markdown میں لکھ کر یکجا کرنے کی اجازت دیتا ہے۔ مزید برآں، R Markdown دستاویزات PDF، HTML، یا Word جیسے آؤٹ پٹ فارمیٹس میں تبدیل کی جا سکتی ہیں۔
> **کوئز کے بارے میں ایک نوٹ**: تمام کوئز [کوئز ایپ فولڈر](../../quiz-app) میں شامل ہیں، جن کی تعداد 52 ہے ہر ایک میں تین سوالات ہیں۔ یہ اسباق کے اندر سے لنک کی گئی ہیں لیکن کوئز ایپ کو مقامی طور پر چلایا جا سکتا ہے؛ `quiz-app` فولڈر میں دی گئی ہدایات پر عمل کریں تاکہ مقامی طور پر ہوسٹ کریں یا Azure پر تعینات کریں۔

| سبق نمبر |                             موضوع                              |                   سبق کی جماعت                   | تعلیمی مقاصد                                                                                                             |                                                              لنک شدہ سبق                                                               |                        مصنف                        |
| :-------: | :------------------------------------------------------------: | :-----------------------------------------------: | ------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------: |
|    01     |                مشین لرننگ کا تعارف                             |      [تعارف](1-Introduction/README.md)             | مشین لرننگ کے بنیادی تصورات سیکھیں                                                                                         |                                             [سبق](1-Introduction/1-intro-to-ML/README.md)                                            |                       محمد                         |
|    02     |                مشین لرننگ کی تاریخ                             |      [تعارف](1-Introduction/README.md)             | اس میدان کی تاریخی معلومات حاصل کریں                                                                                       |                                            [سبق](1-Introduction/2-history-of-ML/README.md)                                             |                     جین اور ایمی                      |
|    03     |                 مشین لرننگ میں نزاکت اور عدل                  |      [تعارف](1-Introduction/README.md)             | اہم فلسفیانہ مسائل جو طلباء کو مشین لرننگ ماڈلز بنانے اور لاگو کرنے میں مدنظر رکھنے چاہئیں                                    |                                              [سبق](1-Introduction/3-fairness/README.md)                                                |                        ٹومومی                         |
|    04     |                مشین لرننگ کی تکنیکیں                           |      [تعارف](1-Introduction/README.md)             | مشین لرننگ محققین کن تکنیکوں کا استعمال کرتے ہیں؟                                                                            |                                          [سبق](1-Introduction/4-techniques-of-ML/README.md)                                           |                    کرس اور جین                       |
|    05     |                   ریگریشن کا تعارف                            |        [ریگریشن](2-Regression/README.md)           | ریگریشن ماڈلز کے لیے Python اور Scikit-learn کے ساتھ شروع کریں                                                                |         [Python](2-Regression/1-Tools/README.md) • [R](../../2-Regression/1-Tools/solution/R/lesson_1.html)         |      جین • ایرک وانجا                       |
|    06     |                شمالی امریکہ کے کدو کی قیمتیں 🎃                |        [ریگریشن](2-Regression/README.md)           | مشین لرننگ کی تیاری کے لیے ڈیٹا کو دیکھیں اور صاف کریں                                                                        |          [Python](2-Regression/2-Data/README.md) • [R](../../2-Regression/2-Data/solution/R/lesson_2.html)          |      جین • ایرک وانجا                       |
|    07     |                شمالی امریکہ کے کدو کی قیمتیں 🎃                |        [ریگریشن](2-Regression/README.md)           | خطی اور کثیر رکنی ریگریشن ماڈلز بنائیں                                                                                     |        [Python](2-Regression/3-Linear/README.md) • [R](../../2-Regression/3-Linear/solution/R/lesson_3.html)        |      جین اور دمتری • ایرک وانجا                 |
|    08     |                شمالی امریکہ کے کدو کی قیمتیں 🎃                |        [ریگریشن](2-Regression/README.md)           | لاجسٹک ریگریشن ماڈل بنائیں                                                                                                |     [Python](2-Regression/4-Logistic/README.md) • [R](../../2-Regression/4-Logistic/solution/R/lesson_4.html)      |      جین • ایرک وانجا                       |
|    09     |                          ویب ایپ 🔌                          |           [ویب ایپ](3-Web-App/README.md)            | تربیت یافتہ ماڈل کے استعمال کے لئے ویب ایپ بنائیں                                                                            |                                                 [Python](3-Web-App/1-Web-App/README.md)                                                  |                         جین                          |
|    10     |                 درجہ بندی کا تعارف                             |    [درجہ بندی](4-Classification/README.md)          | اپنا ڈیٹا صاف، تیار اور دیکھیں؛ درجہ بندی کا تعارف                                                                            | [Python](4-Classification/1-Introduction/README.md) • [R](../../4-Classification/1-Introduction/solution/R/lesson_10.html)  | جین اور کیسی • ایرک وانجا                  |
|    11     |             مزیدار ایشیائی اور ہندوستانی کھانے 🍜             |    [درجہ بندی](4-Classification/README.md)          | کلاسفائرز کا تعارف                                                                                                          | [Python](4-Classification/2-Classifiers-1/README.md) • [R](../../4-Classification/2-Classifiers-1/solution/R/lesson_11.html) | جین اور کیسی • ایرک وانجا                  |
|    12     |             مزیدار ایشیائی اور ہندوستانی کھانے 🍜             |    [درجہ بندی](4-Classification/README.md)          | مزید کلاسفائرز                                                                                                              | [Python](4-Classification/3-Classifiers-2/README.md) • [R](../../4-Classification/3-Classifiers-2/solution/R/lesson_12.html) | جین اور کیسی • ایرک وانجا                  |
|    13     |             مزیدار ایشیائی اور ہندوستانی کھانے 🍜             |    [درجہ بندی](4-Classification/README.md)          | اپنے ماڈل کی مدد سے ری کومینڈر ویب ایپ بنائیں                                                                                 |                                              [Python](4-Classification/4-Applied/README.md)                                              |                         جین                          |
|    14     |                   کلسٹرنگ کا تعارف                            |        [کلسٹرنگ](5-Clustering/README.md)             | اپنا ڈیٹا صاف، تیار اور دیکھیں؛ کلسٹرنگ کا تعارف                                                                             |         [Python](5-Clustering/1-Visualize/README.md) • [R](../../5-Clustering/1-Visualize/solution/R/lesson_14.html)         |      جین • ایرک وانجا                       |
|    15     |              نائیجیریائی موسیقی کے ذوق کی دریافت 🎧              |        [کلسٹرنگ](5-Clustering/README.md)             | K-Means کلسٹرنگ کا طریقہ دریافت کریں                                                                                        |           [Python](5-Clustering/2-K-Means/README.md) • [R](../../5-Clustering/2-K-Means/solution/R/lesson_15.html)           |      جین • ایرک وانجا                       |
|    16     |        قدرتی زبان کی پروسیسنگ کا تعارف ☕️                      |   [قدرتی زبان کی پروسیسنگ](6-NLP/README.md)          | سادہ بوٹ بنا کر NLP کے بنیادی اصول سیکھیں                                                                                    |                                             [Python](6-NLP/1-Introduction-to-NLP/README.md)                                              |                       اسٹیفن                        |
|    17     |                      عام NLP کے کام ☕️                        |   [قدرتی زبان کی پروسیسنگ](6-NLP/README.md)          | زبان کی ساختوں سے نمٹنے کے دوران ضرورت پڑنے والے عام کاموں کو سمجھ کر NLP کا علم بڑھائیں                                        |                                                    [Python](6-NLP/2-Tasks/README.md)                                                     |                       اسٹیفن                        |
|    18     |             ترجمہ اور جذباتی تجزیہ ♥️                          |   [قدرتی زبان کی پروسیسنگ](6-NLP/README.md)          | جین آستن کے ساتھ ترجمہ اور جذباتی تجزیہ                                                                                      |                                            [Python](6-NLP/3-Translation-Sentiment/README.md)                                             |                       اسٹیفن                        |
|    19     |                  یورپ کے رومانٹک ہوٹل ♥️                      |   [قدرتی زبان کی پروسیسنگ](6-NLP/README.md)          | ہوٹل کے جائزوں کے ساتھ جذباتی تجزیہ 1                                                                                        |                                               [Python](6-NLP/4-Hotel-Reviews-1/README.md)                                                |                       اسٹیفن                        |
|    20     |                  یورپ کے رومانٹک ہوٹل ♥️                      |   [قدرتی زبان کی پروسیسنگ](6-NLP/README.md)          | ہوٹل کے جائزوں کے ساتھ جذباتی تجزیہ 2                                                                                        |                                               [Python](6-NLP/5-Hotel-Reviews-2/README.md)                                                |                       اسٹیفن                        |
|    21     |            ٹائم سیریز پیش گوئی کا تعارف                         |        [ٹائم سیریز](7-TimeSeries/README.md)             | ٹائم سیریز پیش گوئی کا تعارف                                                                                                |                                             [Python](7-TimeSeries/1-Introduction/README.md)                                              |                      فرانسسکا                       |
|    22     | ⚡️ عالمی بجلی استعمال ⚡️ - ARIMA کے ساتھ ٹائم سیریز پیش گوئی |        [ٹائم سیریز](7-TimeSeries/README.md)             | ARIMA کے ساتھ ٹائم سیریز پیش گوئی                                                                                            |                                                 [Python](7-TimeSeries/2-ARIMA/README.md)                                                 |                      فرانسسکا                       |
|    23     |  ⚡️ عالمی بجلی استعمال ⚡️ - SVR کے ساتھ ٹائم سیریز پیش گوئی  |        [ٹائم سیریز](7-TimeSeries/README.md)             | سپورٹ ویکٹر ریگریسر کے ساتھ ٹائم سیریز پیش گوئی                                                                               |                                                  [Python](7-TimeSeries/3-SVR/README.md)                                                  |                       انربن                         |
|    24     |             ری انفورسمنٹ لرننگ کا تعارف                        | [ری انفورسمنٹ لرننگ](8-Reinforcement/README.md)       | Q-لرننگ کے ساتھ ری انفورسمنٹ لرننگ کا تعارف                                                                                   |                                             [Python](8-Reinforcement/1-QLearning/README.md)                                              |                        دمتری                         |
|    25     |                 پیٹر کو بھیڑیے سے بچائیں! 🐺                   | [ری انفورسمنٹ لرننگ](8-Reinforcement/README.md)       | ری انفورسمنٹ لرننگ جِم                                                                                                      |                                                [Python](8-Reinforcement/2-Gym/README.md)                                                 |                        دمتری                         |
|  اختتامیہ  |            حقیقی دنیا میں ML کی مثالیں اور اطلاقات           |      [حقیقی دنیا میں ML](9-Real-World/README.md)      | کلاسیکل مشین لرننگ کی دلچسپ اور معلوماتی حقیقی دنیا کی اطلاقات                                                                |                                             [سبق](9-Real-World/1-Applications/README.md)                                              |                         ٹیم                          |
|  اختتامیہ  |            RAI ڈیش بورڈ کے ذریعے ML میں ماڈل کی جانچ           |      [حقیقی دنیا میں ML](9-Real-World/README.md)      | ذمہ دار AI ڈیش بورڈ کمپونینٹس کا استعمال کرتے ہوئے مشین لرننگ میں ماڈل کی جانچ                                                 |                                             [سبق](9-Real-World/2-Debugging-ML-Models/README.md)                                              |                         روت یاکوبو                        |

> [اس کورس کے تمام اضافی وسائل ہماری Microsoft Learn کلیکشن میں تلاش کریں](https://learn.microsoft.com/en-us/collections/qrqzamz1nn2wx3?WT.mc_id=academic-77952-bethanycheum)

## آف لائن رسائی

آپ اس دستاویز کو آف لائن [Docsify](https://docsify.js.org/#/) استعمال کرکے چلا سکتے ہیں۔ اس ریپو کو فورک کریں، اپنے مقامی کمپیوٹر پر [Docsify انسٹال کریں](https://docsify.js.org/#/quickstart)، اور پھر اس ریپو کے روٹ فولڈر میں `docsify serve` لکھیں۔ ویب سائٹ آپ کے لوکل ہوسٹ پر پورٹ 3000 پر چلائے گی: `localhost:3000`.

## پی ڈی ایفز

نصاب کا پی ڈی ایف ورژن لنکس کے ساتھ یہاں حاصل کریں: [here](https://microsoft.github.io/ML-For-Beginners/pdf/readme.pdf).

## 🎒 دیگر کورسز

ہماری ٹیم دیگر کورسز بھی تیار کرتی ہے! دیکھیں:

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
 
### Generative AI Series
[![ابتدائی افراد کے لیے جنریٹو AI](https://img.shields.io/badge/Generative%20AI%20for%20Beginners-8B5CF6?style=for-the-badge&labelColor=E5E7EB&color=8B5CF6)](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![جنریٹو AI (.NET)](https://img.shields.io/badge/Generative%20AI%20(.NET)-9333EA?style=for-the-badge&labelColor=E5E7EB&color=9333EA)](https://github.com/microsoft/Generative-AI-for-beginners-dotnet?WT.mc_id=academic-105485-koreyst)
[![جنریٹو AI (جاوا)](https://img.shields.io/badge/Generative%20AI%20(Java)-C084FC?style=for-the-badge&labelColor=E5E7EB&color=C084FC)](https://github.com/microsoft/generative-ai-for-beginners-java?WT.mc_id=academic-105485-koreyst)
[![جنریٹو AI (جاوا اسکرپٹ)](https://img.shields.io/badge/Generative%20AI%20(JavaScript)-E879F9?style=for-the-badge&labelColor=E5E7EB&color=E879F9)](https://github.com/microsoft/generative-ai-with-javascript?WT.mc_id=academic-105485-koreyst)

---
 
### بنیادی تعلیم
[![ابتدائی افراد کے لیے ایم ایل](https://img.shields.io/badge/ML%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=22C55E)](https://aka.ms/ml-beginners?WT.mc_id=academic-105485-koreyst)
[![ابتدائی افراد کے لیے ڈیٹا سائنس](https://img.shields.io/badge/Data%20Science%20for%20Beginners-84CC16?style=for-the-badge&labelColor=E5E7EB&color=84CC16)](https://aka.ms/datascience-beginners?WT.mc_id=academic-105485-koreyst)
[![ابتدائی افراد کے لیے AI](https://img.shields.io/badge/AI%20for%20Beginners-A3E635?style=for-the-badge&labelColor=E5E7EB&color=A3E635)](https://aka.ms/ai-beginners?WT.mc_id=academic-105485-koreyst)
[![ابتدائی افراد کے لیے سائبرسیکورٹی](https://img.shields.io/badge/Cybersecurity%20for%20Beginners-F97316?style=for-the-badge&labelColor=E5E7EB&color=F97316)](https://github.com/microsoft/Security-101?WT.mc_id=academic-96948-sayoung)
[![ابتدائی افراد کے لیے ویب ڈیولپمنٹ](https://img.shields.io/badge/Web%20Dev%20for%20Beginners-EC4899?style=for-the-badge&labelColor=E5E7EB&color=EC4899)](https://aka.ms/webdev-beginners?WT.mc_id=academic-105485-koreyst)
[![ابتدائی افراد کے لیے IoT](https://img.shields.io/badge/IoT%20for%20Beginners-14B8A6?style=for-the-badge&labelColor=E5E7EB&color=14B8A6)](https://aka.ms/iot-beginners?WT.mc_id=academic-105485-koreyst)
[![ابتدائی افراد کے لیے XR ڈیولپمنٹ](https://img.shields.io/badge/XR%20Development%20for%20Beginners-38BDF8?style=for-the-badge&labelColor=E5E7EB&color=38BDF8)](https://github.com/microsoft/xr-development-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### کوپائلٹ سیریز
[![AI جوڑے پروگرامنگ کے لیے کوپائلٹ](https://img.shields.io/badge/Copilot%20for%20AI%20Paired%20Programming-FACC15?style=for-the-badge&labelColor=E5E7EB&color=FACC15)](https://aka.ms/GitHubCopilotAI?WT.mc_id=academic-105485-koreyst)
[![C#/.NET کے لیے کوپائلٹ](https://img.shields.io/badge/Copilot%20for%20C%23/.NET-FBBF24?style=for-the-badge&labelColor=E5E7EB&color=FBBF24)](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers?WT.mc_id=academic-105485-koreyst)
[![کوپائلٹ مہم](https://img.shields.io/badge/Copilot%20Adventure-FDE68A?style=for-the-badge&labelColor=E5E7EB&color=FDE68A)](https://github.com/microsoft/CopilotAdventures?WT.mc_id=academic-105485-koreyst)
<!-- CO-OP TRANSLATOR OTHER COURSES END -->

## مدد حاصل کرنا

اگر آپ پھنس گئے ہیں یا AI ایپس بنانے کے بارے میں کوئی سوالات ہیں۔ MCP کے بارے میں بات چیت میں شامل ہوں جہاں ساتھی سیکھنے والے اور تجربہ کار ڈویلپرز ہیں۔ یہ ایک مددگار کمیونٹی ہے جہاں سوالات کا خیرمقدم کیا جاتا ہے اور علم آزادانہ طور پر شیئر کیا جاتا ہے۔

[![مائیکروسافٹ فاؤنڈری ڈسکارڈ](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

اگر آپ کے پاس پروڈکٹ کا فیڈبیک ہے یا کوئی خرابی ہو رہی ہے تو براہ کرم ملاحظہ کریں:

[![مائیکروسافٹ فاؤنڈری ڈویلپر فورم](https://img.shields.io/badge/GitHub-Microsoft_Foundry_Developer_Forum-blue?style=for-the-badge&logo=github&color=000000&logoColor=fff)](https://aka.ms/foundry/forum)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**ڈسکلیمر**:  
اس دستاویز کا ترجمہ AI ترجمہ سروس [Co-op Translator](https://github.com/Azure/co-op-translator) کے ذریعے کیا گیا ہے۔ اگرچہ ہم درستگی کے لیے کوشاں ہیں، براہِ کرم ذہن میں رکھیں کہ خودکار ترجمے میں غلطیاں یا عدم درستیاں ہو سکتی ہیں۔ اصل دستاویز اپنی مادری زبان میں ایک معتبر ماخذ سمجھی جانی چاہیے۔ اہم معلومات کے لیے پیشہ ورانہ انسانی ترجمہ تجویز کیا جاتا ہے۔ اس ترجمے کے استعمال سے پیدا ہونے والی کسی بھی غلط فہمی یا غلط تعبیر کی ذمہ داری ہم پر نہیں ہوگی۔
<!-- CO-OP TRANSLATOR DISCLAIMER END -->