[![GitHub-lisenssi](https://img.shields.io/github/license/microsoft/ML-For-Beginners.svg)](https://github.com/microsoft/ML-For-Beginners/blob/master/LICENSE)
[![GitHub-yhteistyökumppanit](https://img.shields.io/github/contributors/microsoft/ML-For-Beginners.svg)](https://GitHub.com/microsoft/ML-For-Beginners/graphs/contributors/)
[![GitHub ongelmat](https://img.shields.io/github/issues/microsoft/ML-For-Beginners.svg)](https://GitHub.com/microsoft/ML-For-Beginners/issues/)
[![GitHub vetopyynnöt](https://img.shields.io/github/issues-pr/microsoft/ML-For-Beginners.svg)](https://GitHub.com/microsoft/ML-For-Beginners/pulls/)
[![Vetopyynnöt tervetulleita](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

[![GitHub seuraajat](https://img.shields.io/github/watchers/microsoft/ML-For-Beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/ML-For-Beginners/watchers/)
[![GitHub haarukat](https://img.shields.io/github/forks/microsoft/ML-For-Beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/ML-For-Beginners/network/)
[![GitHub tähdet](https://img.shields.io/github/stars/microsoft/ML-For-Beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/ML-For-Beginners/stargazers/)

### 🌐 Monikielituki

#### Tuettu GitHub Actionin avulla (automaattinen ja aina ajan tasalla)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabia](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgaria](../bg/README.md) | [Burma (Myanmar)](../my/README.md) | [Kiina (yksinkertaistettu)](../zh-CN/README.md) | [Kiina (perinteinen, Hongkong)](../zh-HK/README.md) | [Kiina (perinteinen, Macao)](../zh-MO/README.md) | [Kiina (perinteinen, Taiwan)](../zh-TW/README.md) | [Kroatia](../hr/README.md) | [Tsekki](../cs/README.md) | [Tanska](../da/README.md) | [Hollanti](../nl/README.md) | [Viro](../et/README.md) | [Suomi](./README.md) | [Ranska](../fr/README.md) | [Saksa](../de/README.md) | [Kreikka](../el/README.md) | [Heprea](../he/README.md) | [Hindi](../hi/README.md) | [Unkari](../hu/README.md) | [Indonesia](../id/README.md) | [Italia](../it/README.md) | [Japani](../ja/README.md) | [Kannada](../kn/README.md) | [Korea](../ko/README.md) | [Liettua](../lt/README.md) | [Malaiji](../ms/README.md) | [Malajalami](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norja](../no/README.md) | [Persia (Farsi)](../fa/README.md) | [Puola](../pl/README.md) | [Portugali (Brasilia)](../pt-BR/README.md) | [Portugali (Portugali)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romania](../ro/README.md) | [Venäjä](../ru/README.md) | [Serbia (kyrillinen)](../sr/README.md) | [Slovakki](../sk/README.md) | [Sloveeni](../sl/README.md) | [Espanja](../es/README.md) | [Swahili](../sw/README.md) | [Ruotsi](../sv/README.md) | [Tagalog (filipino)](../tl/README.md) | [Tamili](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkki](../tr/README.md) | [Ukraina](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnam](../vi/README.md)

> **Haluatko kloonata paikallisesti?**

> Tämä repositorio sisältää yli 50 kielikäännöstä, mikä lisää merkittävästi latauskokoa. Jos haluat kloonata ilman käännöksiä, käytä sparse checkoutia:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/microsoft/ML-For-Beginners.git
> cd ML-For-Beginners
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Tämä antaa sinulle kaiken tarvittavan kurssin suorittamiseen paljon nopeammalla latauksella.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

#### Liity yhteisöömme

[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

Meillä on meneillään Discordissa tekoälyn oppimissarja, lue lisää ja liity mukaan osoitteessa [Learn with AI Series](https://aka.ms/learnwithai/discord) ajalla 18.–30. syyskuuta 2025. Saat vinkkejä ja niksejä GitHub Copilotin käyttämiseen Data Scientistin työn tukena.

![Learn with AI series](../../translated_images/fi/3.9b58fd8d6c373c20.webp)

# Koneoppiminen aloittelijoille - Opetussuunnitelma

> 🌍 Matkusta ympäri maailmaa tutustuessamme koneoppimiseen maailman kulttuurien kautta 🌍

Microsoftin Cloud Advocates -tiimi tarjoaa 12 viikon, 26 oppitunnin opetussuunnitelman, joka käsittelee **koneoppimista**. Tässä opetussuunnitelmassa opit ns. **klassista koneoppimista**, pääasiassa Scikit-learn-kirjaston avulla, välttäen syväoppimista, joka sisältyy [tekoälyn aloittelijoiden opetussuunnitelmaamme](https://aka.ms/ai4beginners). Yhdistä nämä oppitunnit myös ['Data Science aloittelijat' -opetusohjelmaamme](https://aka.ms/ds4beginners)!

Matkusta kanssamme ympäri maailmaa soveltamalla klassisia tekniikoita eri puolilta kerättyyn dataan. Jokainen oppitunti sisältää ennakko- ja jälkikyselyt, kirjalliset ohjeet oppitunnin suorittamiseen, ratkaisun, tehtävän ja paljon muuta. Projektipohjainen pedagogiikkamme mahdollistaa oppimisen samalla kun rakennat, mikä on osoittautunut tehokkaaksi tavaksi saada uudet taidot 'jämähtämään'.

**✍️ Lämpimät kiitokset kirjoittajille:** Jen Looper, Stephen Howell, Francesca Lazzeri, Tomomi Imura, Cassie Breviu, Dmitry Soshnikov, Chris Noring, Anirban Mukherjee, Ornella Altunyan, Ruth Yakubu ja Amy Boyd

**🎨 Kiitokset myös kuvittajille:** Tomomi Imura, Dasani Madipalli ja Jen Looper

**🙏 Erityiskiitokset 🙏 Microsoftin opiskelija-ambassadoreille, kirjoittajille, arvioijille ja sisällöntuottajille:** erityisesti Rishit Dagli, Muhammad Sakib Khan Inan, Rohan Raj, Alexandru Petrescu, Abhishek Jaiswal, Nawrin Tabassum, Ioan Samuila ja Snigdha Agarwal

**🤩 Ekstra kiitokset Microsoftin opiskelija-ambassadoreille Eric Wanjau, Jasleen Sondhi ja Vidushi Gupta R-kielten oppitunneistamme!**

# Aloittaminen

Noudata näitä ohjeita:
1. **Forkkaa repositorio**: Klikkaa oikeassa yläkulmassa olevaa "Fork" -painiketta.
2. **Kloonaa repositorio**: `git clone https://github.com/microsoft/ML-For-Beginners.git`

> [löydät kaikki lisäresurssit tälle kurssille Microsoft Learn kokoelmastamme](https://learn.microsoft.com/en-us/collections/qrqzamz1nn2wx3?WT.mc_id=academic-77952-bethanycheum)

> 🔧 **Tarvitsetko apua?** Katso [Vianmääritysohjeemme](TROUBLESHOOTING.md) yleisimpiin ongelmiin asennuksessa, käytössä ja oppituntien suorittamisessa.

**[Opiskelijat](https://aka.ms/student-page)**, käyttäkää tätä opetussuunnitelmaa forkkaamalla koko repo omalle GitHub-tilillenne ja suorittamalla harjoitukset yksin tai ryhmässä:

- Aloita ennakkokyselyllä.
- Lue oppitunti ja suorita tehtävät, pysähtyen ja pohdiskellen jokaisessa tietotarkistuksessa.
- Yritä luoda projektit ymmärtämällä oppituntien sisältö koodiratkaisun ajamisen sijaan; koodit löytyvät kuitenkin kunkin projektipohjaisen oppitunnin /solution-kansiosta.
- Tee jälkikysely.
- Suorita haaste.
- Suorita tehtävä.
- Oppituntiryhmän suorittamisen jälkeen käy [keskustelupalstalla](https://github.com/microsoft/ML-For-Beginners/discussions) ja "oppi ääneen" täyttämällä PAT-arviointilomake. PAT on Progress Assessment Tool, arviointimatriisi, jonka täytät oppimisesi edistämiseksi. Voit myös reagoida muiden PAT-arviointeihin, jotta voimme oppia yhdessä.

> Jatko-opiskelua varten suosittelemme seuraamaan näitä [Microsoft Learn](https://docs.microsoft.com/en-us/users/jenlooper-2911/collections/k7o7tg1gp306q4?WT.mc_id=academic-77952-leestott) moduuleja ja oppimispolkuja.

**Opettajat**, olemme lisänneet joitakin [ehdotuksia](for-teachers.md) tämän opetussuunnitelman hyödyntämiseen.

---

## Videon läpikäynnit

Jotkin oppitunnit ovat saatavilla lyhyinä videoina. Löydät ne kaikki oppituntien yhteydestä tai [ML for Beginners -soittolistalta Microsoft Developer YouTube -kanavalla](https://aka.ms/ml-beginners-videos) klikkaamalla alla olevaa kuvaa.

[![ML aloittelijoille banneri](../../translated_images/fi/ml-for-beginners-video-banner.63f694a100034bc6.webp)](https://aka.ms/ml-beginners-videos)

---

## Tapaa tiimi

[![Promo-video](../../images/ml.gif)](https://youtu.be/Tj1XWrDSYJU)

**Gif:** [Mohit Jaisal](https://linkedin.com/in/mohitjaisal)

> 🎥 Klikkaa yllä olevaa kuvaa nähdäksesi videon projektista ja sen tekijöistä!

---

## Pedagogiikka

Olemme valinneet kaksi pedagogista periaatetta tämän opetussuunnitelman rakentamisessa: varmistaa, että se on käytännönläheinen **projektipohjainen** sekä että siinä on **usein toistuvia kyselyjä**. Lisäksi opetussuunnitelmalla on yhteinen **teema**, joka antaa sille yhtenäisyyden.

Sisällön yhdistäminen projekteihin tekee opiskelusta kiinnostavampaa ja lisää käsitteiden muistamista. Lisäksi luennoille ennen aloitusta tehtävä pieni tietokilpailu ohjaa opiskelijan asenteen oppimiseen, ja luennon jälkeinen toinen tietokilpailu varmistaa opitun pysyvyyden. Tämä opetussuunnitelma on suunniteltu joustavaksi ja hauskaksi, ja sitä voi suorittaa kokonaan tai osittain. Projektit alkavat pienestä ja monimutkaistuvat 12 viikon aikana. Sisältää myös jälkisanat koneoppimisen todellisista sovelluksista, joita voi käyttää ylimääräisinä pisteinä tai keskustelun pohjana.

> Löydät [käyttäytymissäännöt](CODE_OF_CONDUCT.md), [osallistumisohjeet](CONTRIBUTING.md), [käännösohjeet](TRANSLATIONS.md) ja [vianmääritysohjeet](TROUBLESHOOTING.md). Otamme mielellämme vastaan rakentavaa palautetta!

## Jokainen oppitunti sisältää

- vapaaehtoisen muistiinpanokuvauksen (sketchnote)
- vapaaehtoisen lisävideon
- videon läpikäynnin (vain joissain oppitunneissa)
- [ennakko-oppitentin](https://ff-quizzes.netlify.app/en/ml/)
- kirjallisen oppitunnin
- projektipohjaisissa oppitunneissa askel askeleelta ohjeet projektin rakentamiseen
- tietotarkistuksia
- haasteen
- lisälukemista
- tehtävän
- [lopputentin](https://ff-quizzes.netlify.app/en/ml/)

> **Huomio kielistä:** Nämä oppitunnit on pääasiassa kirjoitettu Pythonilla, mutta monet ovat myös saatavilla R-kielellä. Suorittaaksesi R-oppitunnin, siirry /solution-kansioon ja etsi R-kielisiä oppitunteja. Ne sisältävät .rmd-päätteen, joka edustaa **R Markdown** -tiedostoa, joka voidaan määritellä upotuksena `koodin palstoista` (R:llä tai muilla kielillä) ja `YAML-otsikosta` (joka ohjaa esimerkiksi PDF-muotoilua) Markdown-dokumentissa. Tämä toimii erinomaisena kirjoituskehyksenä data-analyysiin, sillä voit yhdistää koodisi, sen tulokset ja ajatuksesi kirjoittamalla ne Markdownilla. Lisäksi R Markdown -tiedostot voidaan renderöidä PDF-, HTML- tai Word-muotoon.
> **Huomautus harjoituksista**: Kaikki harjoitukset löytyvät [Quiz App -kansiosta](../../quiz-app), yhteensä 52 harjoitusta, joissa jokaisessa on kolme kysymystä. Ne on linkitetty oppituntien yhteyteen, mutta kysymyskoneen voi ajaa myös paikallisesti; noudata `quiz-app`-kansion ohjeita isännöidäksesi tai ottaaksesi sen käyttöön Azuren palvelussa paikallisesti.

| Oppitunnin numero |                             Aihe                              |                   Oppitunnin ryhmittely                   | Oppimistavoitteet                                                                                                             |                                                              Linkitetty oppitunti                                                               |                        Tekijä                        |
| :---------------: | :----------------------------------------------------------: | :-------------------------------------------------------: | ----------------------------------------------------------------------------------------------------------------------------- | :-----------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------: |
|        01         |                Johdatus koneoppimiseen                      |      [Johdanto](1-Introduction/README.md)                 | Opi koneoppimisen peruskäsitteet                                                                                              |                                             [Oppitunti](1-Introduction/1-intro-to-ML/README.md)                                            |                       Muhammad                       |
|        02         |                Koneoppimisen historia                        |      [Johdanto](1-Introduction/README.md)                 | Opi tämän alan historia                                                                                                       |                                             [Oppitunti](1-Introduction/2-history-of-ML/README.md)                                            |                     Jen ja Amy                        |
|        03         |                 Oikeudenmukaisuus ja koneoppiminen          |      [Johdanto](1-Introduction/README.md)                 | Mitkä ovat tärkeät filosofiset kysymykset oikeudenmukaisuudesta, joita opiskelijoiden tulee miettiä koneoppimismallien rakentamisessa ja soveltamisessa? |                                              [Oppitunti](1-Introduction/3-fairness/README.md)                                              |                        Tomomi                        |
|        04         |                Koneoppimisen tekniikat                       |      [Johdanto](1-Introduction/README.md)                 | Mitä tekniikoita koneoppimis­tutkijat käyttävät mallien rakentamiseen?                                                        |                                           [Oppitunti](1-Introduction/4-techniques-of-ML/README.md)                                            |                    Chris ja Jen                      |
|        05         |                   Johdatus regressioon                       |        [Regressio](2-Regression/README.md)                 | Ota Python ja Scikit-learn käyttöön regressiomallien tekemiseen                                                              |         [Python](2-Regression/1-Tools/README.md) • [R](../../2-Regression/1-Tools/solution/R/lesson_1.html)         |      Jen • Eric Wanjau       |
|        06         |                Pohjois-Amerikan kurpitsahinnat 🎃            |        [Regressio](2-Regression/README.md)                 | Visualisoi ja siivoa data koneoppimisen valmisteluksi                                                                         |          [Python](2-Regression/2-Data/README.md) • [R](../../2-Regression/2-Data/solution/R/lesson_2.html)          |      Jen • Eric Wanjau       |
|        07         |                Pohjois-Amerikan kurpitsahinnat 🎃            |        [Regressio](2-Regression/README.md)                 | Rakenna lineaarisia ja polynomisia regressiomalleja                                                                           |        [Python](2-Regression/3-Linear/README.md) • [R](../../2-Regression/3-Linear/solution/R/lesson_3.html)        |      Jen ja Dmitry • Eric Wanjau       |
|        08         |                Pohjois-Amerikan kurpitsahinnat 🎃            |        [Regressio](2-Regression/README.md)                 | Rakenna logistinen regressiomalli                                                                                             |     [Python](2-Regression/4-Logistic/README.md) • [R](../../2-Regression/4-Logistic/solution/R/lesson_4.html)      |      Jen • Eric Wanjau       |
|        09         |                          Web sovellus 🔌                      |           [Web App](3-Web-App/README.md)                    | Rakenna web-sovellus käyttämään koulutettua malliasi                                                                          |                                                 [Python](3-Web-App/1-Web-App/README.md)                                                 |                         Jen                          |
|        10         |                 Johdatus luokitteluun                         |    [Luokittelu](4-Classification/README.md)                | Siivoa, valmistele ja visualisoi datasi; johdatus luokitteluun                                                                | [Python](4-Classification/1-Introduction/README.md) • [R](../../4-Classification/1-Introduction/solution/R/lesson_10.html)  | Jen ja Cassie • Eric Wanjau |
|        11         |             Herkulliset aasialaiset ja intialaiset keittiöt 🍜 |    [Luokittelu](4-Classification/README.md)                | Johdatus luokittelijoihin                                                                                                     | [Python](4-Classification/2-Classifiers-1/README.md) • [R](../../4-Classification/2-Classifiers-1/solution/R/lesson_11.html) | Jen ja Cassie • Eric Wanjau |
|        12         |             Herkulliset aasialaiset ja intialaiset keittiöt 🍜 |    [Luokittelu](4-Classification/README.md)                | Lisää luokittelijoita                                                                                                         | [Python](4-Classification/3-Classifiers-2/README.md) • [R](../../4-Classification/3-Classifiers-2/solution/R/lesson_12.html) | Jen ja Cassie • Eric Wanjau |
|        13         |             Herkulliset aasialaiset ja intialaiset keittiöt 🍜 |    [Luokittelu](4-Classification/README.md)                | Rakenna malliasi hyödyntävä suositusweb-sovellus                                                                              |                                              [Python](4-Classification/4-Applied/README.md)                                             |                         Jen                          |
|        14         |                   Johdatus klusterointiin                     |        [Klusterointi](5-Clustering/README.md)               | Siivoa, valmistele ja visualisoi datasi; johdatus klusterointiin                                                              |         [Python](5-Clustering/1-Visualize/README.md) • [R](../../5-Clustering/1-Visualize/solution/R/lesson_14.html)         |      Jen • Eric Wanjau       |
|        15         |              Tutustu nigerialaisiin musiikki­mieltymyksiin 🎧  |        [Klusterointi](5-Clustering/README.md)               | Tutustu K-Means -klusterointimenetelmään                                                                                      |           [Python](5-Clustering/2-K-Means/README.md) • [R](../../5-Clustering/2-K-Means/solution/R/lesson_15.html)           |      Jen • Eric Wanjau       |
|        16         |        Johdatus luonnollisen kielen käsittelyyn ☕️           |   [Luonnollisen kielen käsittely](6-NLP/README.md)           | Opi NLP:n perusteet rakentamalla yksinkertainen botti                                                                         |                                             [Python](6-NLP/1-Introduction-to-NLP/README.md)                                             |                       Stephen                        |
|        17         |                      Yleisiä NLP-tehtäviä ☕️                  |   [Luonnollisen kielen käsittely](6-NLP/README.md)           | Syvennä NLP-tietoasi ymmärtämällä yleisiä kielirakenteiden kanssa tarvittavia tehtäviä                                         |                                                    [Python](6-NLP/2-Tasks/README.md)                                                      |                       Stephen                        |
|        18         |             Käännös ja mielipideanalyysi ♥️                   |   [Luonnollisen kielen käsittely](6-NLP/README.md)           | Käännös ja mielipideanalyysi Jane Austenin avulla                                                                             |                                            [Python](6-NLP/3-Translation-Sentiment/README.md)                                             |                       Stephen                        |
|        19         |                  Euroopan romanttiset hotellit ♥️             |   [Luonnollisen kielen käsittely](6-NLP/README.md)           | Mielipideanalyysi hotelliarvosteluilla 1                                                                                      |                                               [Python](6-NLP/4-Hotel-Reviews-1/README.md)                                               |                       Stephen                        |
|        20         |                  Euroopan romanttiset hotellit ♥️             |   [Luonnollisen kielen käsittely](6-NLP/README.md)           | Mielipideanalyysi hotelliarvosteluilla 2                                                                                      |                                               [Python](6-NLP/5-Hotel-Reviews-2/README.md)                                               |                       Stephen                        |
|        21         |            Johdatus aikasarjaennusteisiin                     |        [Aikasarjat](7-TimeSeries/README.md)                  | Johdatus aikasarjaennustamiseen                                                                                                |                                             [Python](7-TimeSeries/1-Introduction/README.md)                                             |                      Francesca                       |
|        22         | ⚡️ Maailman energiankäyttö ⚡️ - aikasarjaennuste ARIMAlla     |        [Aikasarjat](7-TimeSeries/README.md)                  | Aikasarjaennuste ARIMA-mallin avulla                                                                                          |                                                 [Python](7-TimeSeries/2-ARIMA/README.md)                                                 |                      Francesca                       |
|        23         |  ⚡️ Maailman energiankäyttö ⚡️ - aikasarjaennuste SVR:llä    |        [Aikasarjat](7-TimeSeries/README.md)                  | Aikasarjaennuste tukivektoriregressorin avulla                                                                                |                                                  [Python](7-TimeSeries/3-SVR/README.md)                                                   |                       Anirban                        |
|        24         |             Johdatus vahvistusoppimiseen                      | [Vahvistusoppiminen](8-Reinforcement/README.md)             | Johdatus vahvistusoppimiseen Q-Learningin avulla                                                                              |                                             [Python](8-Reinforcement/1-QLearning/README.md)                                             |                        Dmitry                        |
|        25         |                 Auta Peteriä välttämään susi! 🐺              | [Vahvistusoppiminen](8-Reinforcement/README.md)             | Vahvistusoppiminen Gym-ympäristössä                                                                                           |                                                [Python](8-Reinforcement/2-Gym/README.md)                                                  |                        Dmitry                        |
|  Jälkikirjoitus  |            Käytännön ML-tilanteita ja sovelluksia             |      [ML luonnossa](9-Real-World/README.md)                   | Mielenkiintoisia ja paljastavia klassisen ML:n sovelluksia tosielämässä                                                      |                                             [Oppitunti](9-Real-World/1-Applications/README.md)                                             |                         Tiimi                         |
|  Jälkikirjoitus  |            Mallien virheiden selvitys ML:ssä RAI-hallintapaneelin avulla            |      [ML luonnossa](9-Real-World/README.md)                   | Mallien virheiden selvitys koneoppimisessa Responsible AI -hallintapaneelin komponenteilla                                     |                                             [Oppitunti](9-Real-World/2-Debugging-ML-Models/README.md)                                             |                         Ruth Yakubu                       |

> [Löydä kaikki tämän kurssin lisäresurssit Microsoft Learn -kokoelmastamme](https://learn.microsoft.com/en-us/collections/qrqzamz1nn2wx3?WT.mc_id=academic-77952-bethanycheum)

## Offline-käyttö

Voit käyttää tätä dokumentaatiota offline-tilassa Docsifyn avulla [Docsify](https://docsify.js.org/#/). Tee fork tälle repositoriolle, [asenna Docsify](https://docsify.js.org/#/quickstart) paikalliselle koneellesi ja kirjoita sitten tämän repoversion juurikansiossa `docsify serve`. Sivusto aukeaa portissa 3000 paikallisessa koneessasi: `localhost:3000`.

## PDF-tiedostot

Löydä pdf-opas sisältöineen linkkeineen [täältä](https://microsoft.github.io/ML-For-Beginners/pdf/readme.pdf).


## 🎒 Muut kurssit

Tiimimme tuottaa myös muita kursseja! Tutustu:

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
 
### Generatiivisen tekoälyn sarja
[![Generatiivinen tekoäly aloittelijoille](https://img.shields.io/badge/Generative%20AI%20for%20Beginners-8B5CF6?style=for-the-badge&labelColor=E5E7EB&color=8B5CF6)](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Generatiivinen tekoäly (.NET)](https://img.shields.io/badge/Generative%20AI%20(.NET)-9333EA?style=for-the-badge&labelColor=E5E7EB&color=9333EA)](https://github.com/microsoft/Generative-AI-for-beginners-dotnet?WT.mc_id=academic-105485-koreyst)
[![Generatiivinen tekoäly (Java)](https://img.shields.io/badge/Generative%20AI%20(Java)-C084FC?style=for-the-badge&labelColor=E5E7EB&color=C084FC)](https://github.com/microsoft/generative-ai-for-beginners-java?WT.mc_id=academic-105485-koreyst)
[![Generatiivinen tekoäly (JavaScript)](https://img.shields.io/badge/Generative%20AI%20(JavaScript)-E879F9?style=for-the-badge&labelColor=E5E7EB&color=E879F9)](https://github.com/microsoft/generative-ai-with-javascript?WT.mc_id=academic-105485-koreyst)

---
 
### Keskeinen oppiminen
[![ML aloittelijoille](https://img.shields.io/badge/ML%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=22C55E)](https://aka.ms/ml-beginners?WT.mc_id=academic-105485-koreyst)
[![Data-analytiikka aloittelijoille](https://img.shields.io/badge/Data%20Science%20for%20Beginners-84CC16?style=for-the-badge&labelColor=E5E7EB&color=84CC16)](https://aka.ms/datascience-beginners?WT.mc_id=academic-105485-koreyst)
[![Tekoäly aloittelijoille](https://img.shields.io/badge/AI%20for%20Beginners-A3E635?style=for-the-badge&labelColor=E5E7EB&color=A3E635)](https://aka.ms/ai-beginners?WT.mc_id=academic-105485-koreyst)
[![Kyberturvallisuus aloittelijoille](https://img.shields.io/badge/Cybersecurity%20for%20Beginners-F97316?style=for-the-badge&labelColor=E5E7EB&color=F97316)](https://github.com/microsoft/Security-101?WT.mc_id=academic-96948-sayoung)
[![Web-kehitys aloittelijoille](https://img.shields.io/badge/Web%20Dev%20for%20Beginners-EC4899?style=for-the-badge&labelColor=E5E7EB&color=EC4899)](https://aka.ms/webdev-beginners?WT.mc_id=academic-105485-koreyst)
[![IoT aloittelijoille](https://img.shields.io/badge/IoT%20for%20Beginners-14B8A6?style=for-the-badge&labelColor=E5E7EB&color=14B8A6)](https://aka.ms/iot-beginners?WT.mc_id=academic-105485-koreyst)
[![XR-kehitys aloittelijoille](https://img.shields.io/badge/XR%20Development%20for%20Beginners-38BDF8?style=for-the-badge&labelColor=E5E7EB&color=38BDF8)](https://github.com/microsoft/xr-development-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Copilot-sarja
[![Copilot tekoälyn pariohjelmointiin](https://img.shields.io/badge/Copilot%20for%20AI%20Paired%20Programming-FACC15?style=for-the-badge&labelColor=E5E7EB&color=FACC15)](https://aka.ms/GitHubCopilotAI?WT.mc_id=academic-105485-koreyst)
[![Copilot C#/.NET](https://img.shields.io/badge/Copilot%20for%20C%23/.NET-FBBF24?style=for-the-badge&labelColor=E5E7EB&color=FBBF24)](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers?WT.mc_id=academic-105485-koreyst)
[![Copilot-seikkailu](https://img.shields.io/badge/Copilot%20Adventure-FDE68A?style=for-the-badge&labelColor=E5E7EB&color=FDE68A)](https://github.com/microsoft/CopilotAdventures?WT.mc_id=academic-105485-koreyst)
<!-- CO-OP TRANSLATOR OTHER COURSES END -->

## Apua saatavilla

Jos juutut tai sinulla on kysymyksiä tekoälysovellusten rakentamisesta. Liity muiden oppijoiden ja kokeneiden kehittäjien keskusteluihin MCP:stä. Se on tukevainen yhteisö, jossa kysymykset ovat tervetulleita ja tietoa jaetaan vapaasti.

[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

Jos sinulla on tuotepalautetta tai kohtaat virheitä rakentaessasi, käy osoitteessa:

[![Microsoft Foundry Developer Forum](https://img.shields.io/badge/GitHub-Microsoft_Foundry_Developer_Forum-blue?style=for-the-badge&logo=github&color=000000&logoColor=fff)](https://aka.ms/foundry/forum)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Vastuuvapauslauseke**:
Tämä asiakirja on käännetty käyttämällä tekoälypohjaista käännöspalvelua [Co-op Translator](https://github.com/Azure/co-op-translator). Vaikka pyrimme tarkkuuteen, huomaathan, että automaattiset käännökset saattavat sisältää virheitä tai epätarkkuuksia. Alkuperäistä asiakirjaa sen omalla kielellä tulee pitää auktoritatiivisena lähteenä. Tärkeissä tiedoissa suositellaan ammattimaista ihmiskäännöstä. Emme ole vastuussa tämän käännöksen käytöstä aiheutuvista väärinymmärryksistä tai virhetulkintojen seurauksista.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->