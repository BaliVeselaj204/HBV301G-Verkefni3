# Viðskiptamarkmið, framtíðarsýn og Minimum Viable Product 

<!-- Takið út hornklofa og fyllið inn í --> 

**Verkefni 3 — Vision and Scope**

**Heiti kerfis:** Sjálfvirkt bílastæðakerfi

**Teymi og höfundar:** Hópur 5: Bali Nói Veselaj, Kristinn Freyr Óskarsson

**Git repository:** https://github.com/BaliVeselaj204/HBV301G-Verkefni3.git

## Efnisyfirlit

1. [Viðskiptamarkmið](#1-viðskiptamarkmið)
2. [Framtíðarsýn](#2-framtíðarsýn)
3. [Prófíll mikilvægra notenda](#3-prófíll-mikilvægra-notenda)
4. [Forgangsröðun verkefnisins](#4-forgangsröðun-verkefnisins)
5. [Umfang fyrstu útgáfu (MVP)](#5-umfang-fyrstu-útgáfu-mvp)



## 1. Viðskiptamarkmið

<!-- Lýsið hvaða árangri viðskiptavinur eða stofnun vill ná með kerfinu og hvers vegna. Setjið fram mælanleg markmið þar sem því verður við komið: núverandi staða, æskileg breyting, mælikvarði og tímamörk. Greinið á milli viðskiptalegs árangurs og virkni kerfisins. Tengið markmiðin við þær þarfir sem komu fram í fyrri verkefnum. -->
<!-- Takið út hornklofa og fyllið inn í - Endurtakið eftir þörfum --> 

### BO-1: Minnka álag ökumanna

| Atriði | Lýsing |
|---|---|
| Mælikvarði (Scale) | Sjálfvirk skráning stæðis |
| Mæliaðferð (Meter) | Fjöldi skráninga sem eru skráð sjálfkrafa |
| Fyrri staða (Past) | Ekki þekkt enn. Upphafsstaða verður mæld á fyrirhuguðu innleiðingarsvæði með því að skrá hlutfall heimsókna sem fara fram án handvirkrar stæðisskráningar. Niðurstöður verða greindar eftir núverandi fyrirkomulagi, svo sem sjálfvirkri skráningu, áskrift eða handvirkri skráningu. |
| Markmið (Goal) | 100% skráninga |
| Metnaðarmarkmið (Stretch) | Á ekki við |

### BO-2: Minnka vinnuálag hjá umsjónaraðila

| Atriði | Lýsing |
|---|---|
| Mælikvarði (Scale) | Tími sem fer í lagfæringu á villum við skráningu, eftirlit og viðbrögð við óskráðum bílum, mælt miðað við seinustu 1000 heimsóknum |
| Mæliaðferð (Meter) | Umsjónaraðili mælir tímann sem fer í afskipti við skráningar. Heildarvinnustundum er því næst deilt með fjölda heimsókna sem áttu sér stað næst og margfaldað með 1000 |
| Fyrri staða (Past) | Ekki þekkt enn. Núverandi vinnuframlag verður mælt í vinnustundum á hverjar 1000 heimsóknir, þar með talið vinna sem fer í leiðréttingu á skráningarvillum og einnig eftirlit og viðbrögð við óskráðum bílum. |
| Markmið (Goal) | 30% færri vinnustundir fyrstu 6 mánuðina |
| Metnaðarmarkmið (Stretch) | 50% færri vinnustundir fyrstu 6 mánuðina |


## 2. Framtíðarsýn

Sjálfvirkt bílastæðakerfi er hugsað fyrir ökumenn og rekstraraðila gjaldskyldra bílastæða.
Ökumenn gleyma oft að greiða, borga fyrir rangan tíma eða fá sekt fyrir mistök, á meðan 
rekstraraðilar eyða tíma og fé í eftirlit og innheimtu. Kerfið skráir sjálfkrafa hvenær
bíll kemur og fer, reiknar gjaldið eftir gjaldskrá svæðisins og sendir kröfu í netbanka
ökumannsins. Ólíkt stöðumælum og forritum, þar sem ökumaður þarf að skrá sig inn
og út handvirkt, þarf ekki að muna eða óttast að fá sekt. Það fækkar sektum vegna gleymsku, gerir
stæðisupplifunina einfaldari og minnkar handvirkt eftirlit rekstraraðilans.

## 3. Prófíll lykilhagsmunaaðila eða mikilvægra notenda

<!-- Veljið þann hóp/a úr verkefni 2 sem skipta
mestu máli fyrir framtíðarsýnina og MVP. Rökstyðjið valið. Vísið í
verkefni 2 í stað þess að endurtaka alla hagsmunaaðilagreininguna. 
-->

**Val á notendahópi:** Daglegir ökumenn skipta mestu máli fyrir fyrstu útgáfuna því þeir nota kerfið oftast,
verða fyrir mestum áhrifum, og BREQ-1 og BREQ-2 snúa beinlínis að þeim.

| Atriði | Lýsing |
|---|---|
| Notendahópur og hlutverk | Allir sem leggja á gjaldsvæði, hvort sem það er daglega, stöku sinnum eða í fyrsta skipti. Þeir leggja bílnum og kerfið sér um restina |
| Helsta virði (Major value) | Þau þurfa ekki lengur að kaupa miða, muna eftir að greiða eða óttast sekt. Þau leggja bara og fara, og fá rukkun í netbankann eftir á |
| Viðhorf (Attitudes) | Flestum finnst gott að þurfa ekki að hugsa um greiðsluna, en vilja vera viss um að kerfið rukki rétt |
| Helstu áhugamál (Major interests) | Að vera rukkaður fyrir réttan tíma og rétta upphæð, að komur og brottför séu skráðar sjálfkrafa, og að fá greiðslubeiðnina fljótt |
| Takmarkanir (Constraints) | Það þarf að fylgja persónuverndarlögum, þar sem það skráir hvenær bílar koma og fara |

<!-- Ef þið veljið fleiri en einn hóp/aðila, gerið sérstakan prófíl
fyrir hvern þeirra. -->


## 4. Forgangsröðun verkefnisins

Flokkið hverja af fimm víddum verkefnisins sem **drifkraft (Driver)**,
**takmörkun (Constraint)** eða **frjálsleika/frígráðu (Degree of freedom)**.
Rökstyðjið flokkunina með vísun í viðskiptamarkmiðin, framtíðarsýnina
og þarfir og væntingar lykilhagsmunaaðila.

| Vídd | Flokkun | Rökstuðningur |
|---|---|---|
| Eiginleikar | Drifkraftur | BO-1 og BO-2 nást því aðeins að kerfið skrái komu og brottför sjálfkrafa og sendi greiðslubeiðni án inngrips. Þessir eiginleikar eru kjarni vörunnar — án þeirra skilar hún engu virði, svo þeir ráða umfangi frekar en að vera samningsatriði. |
| Gæði | Takmörkun | Nákvæmni skráningar þarf að ná ákveðnu lágmarki, annars er markmið BO-1 um 100% sjálfvirkar skráningar óraunhæft. Fari nákvæmnin undir það mark minnkar traust bæði ökumanna og rekstraraðila á kerfinu. |
| Tímasetningar | Frígráða | Engin ytri tímasetning, samningur eða viðburður krefst þess að kerfið sé tilbúið á nákvæmlega ákveðnum degi. Útgáfu má fresta ef þörf krefur án þess að það ógni viðskiptamarkmiðunum. |
| Kostnaður | Takmörkun | Verkefnið er unnið innan fasts fjárhagsramma án svigrúms fyrir viðbótarfjárfestingu í vélbúnaði umfram það sem þegar er til staðar á innleiðingarsvæðinu. |
| Mannafli | Takmörkun | Teymið sem vinnur verkefnið er fast að stærð og hefur takmarkaðan tíma, svo ekki er hægt að bæta við fólki til að auka umfang eða flýta fyrir. |


## 5. Umfang fyrstu útgáfu (MVP)

<!-- Lýsið minnstu nothæfu útgáfu kerfisins sem skilar virði fyrir mikilvæga
notendur og styður við viðskiptamarkmiðin í kafla 1. Hér er verið að afmarka
fyrstu útgáfu, ekki endurtaka kerfismörkin úr verkefni 1. -->

### 5.1 Umfang fyrstu útgáfu (MVP)

Í fyrstu útgáfu þarf kerfið að geta framið helstu aðgerðirnar sem nauðsynlegar eru
til þess að skrá inn réttar upplýsingar af sem mestri nákvæmni og mögulegt er.
Upplýsingarnar teljast nægilega nákvæmar ef kerfið nemur bíl þegar hann kemur inn á svæðið,
finnur réttan notanda út frá bílnúmeri, hefji talningu skömmu síðar, nemi þegar bíllinn
yfirgefur svæðið og lýkur talningu samtímis og í kjölfarið sendi greiðslubeiðni til notanda.
Notandinn á að geta komið inn á svæðið, lagt bílnum og að lokum yfirgefið svæðið án
þess að hafa áhyggjur af yfirvonandi sekt og getur búist við að fá sent til sín
greiðslubeiðni í heimabanka.
Því meiri nákvæmni því mun minna álag mun umsjónaraðili finna fyrir, því er óskandi
að hlutfall afskipta vegna villna frá kerfinu sé sem minnst og að umsjónaraðili fái að 
sjá meira um önnur mikilvægari skyldur.


| Hvað þarf að vera í MVP? | Hvers vegna? | Tengsl við fyrri verkefni, ef við á |
|---|---|---|
| Sjálfvirk greining bílnúmers og tenging við réttan notanda. | Gerir ökumanni kleift að leggja án miða eða handvirkrar skráningar og dregur þannig úr fyrirhöfn. | BREQ-2 úr V1 |
| Skráning komu- og brottfarartíma og útreikningur bílastæðagjalds. | Tryggir að gjaldið byggist á raunverulegum dvalartíma og dregur úr þörf á leiðréttingum. | F-1 og F-2 úr V1 |
| Sjálfvirk sending greiðslubeiðni í heimabanka. | Dregur úr fyrirhöfn ökumanns og handvirkri vinnu við innheimtu. | F-2 úr V1 |
| Nákvæm og áreiðanleg skráning bílnúmera og tímasetninga. | Dregur úr skráningarvillum og vinnu umsjónaraðila við leiðréttingar. | QA-1 úr V1 |

### 5.2 Rökstuðningur fyrir vali í fyrstu útgáfu

Þeir eiginleikar sem við lögðum fram skráðum við með háan forgang og þeir hagsmunaaðilar sem hafa 
sem mestan áhuga á kerfinu, ökumenn og umsjónar/rekstraraðilar, njóta sem mest góðs af gefnum eiginleikum
þar sem bæði álag á ökumenn og vinnutími umsjónaraðila minnkar til muna. 
Út frá forgangsröðun verkefnisins þar sem við flokkum eiginleikana sem drifkraft og gæði sem takmörkun
teljum við því við hæfi að leggja þessa eiginleika fram í fyrstu útgáfu.


### 5.3 Hvað bíður síðari útgáfu?

| Eiginleiki | Ástæða þess að hann getur beðið |
|---|---|
| Tilkynning til notanda þegar hann er skráður í stæði. | Sjálfvirk skráning og sending greiðslubeiðni virka án þessarar tilkynningar. Hún veitir ökumanni aukna staðfestingu en er ekki forsenda kjarnavirkni kerfisins. |
| Áskriftir eða afslættir fyrir reglulega notendur. | Ekki nauðsynlegt fyrir fyrstu útgáfu þar sem notendur þurfa aðeins eiginleika úr fyrstu útgáfu til þess að geta borgað, en úrræði fyrir notendur sem nýta sér þjónustuna oft getur verið góð viðbót í framtíðinni. |
| Saga notanda, yfirlit yfir fyrri skráningar. | Það getur gefið notendanum aukið gagnsæi að geta séð yfirlit yfir fyrri heimsóknum en þó er það ekki mikilvægt fyrir grunnvirkni kerfisins. | 
### 5.4 Takmarkanir og útilokanir

Það eru ekki margir eiginleikar sem notendur gætu búist við að kerfið bjóði upp á, sem það í raun gerir ekki,
en eitt dæmi um slíkt gæti verið fyrirfram bókun á stæði, ekki er fyrirhugað að bæta þeim eiginleika við.
