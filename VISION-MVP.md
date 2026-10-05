# Viðskiptamarkmið, framtíðarsýn og Minimum Viable Product 

<!-- Takið út hornklofa og fyllið inn í --> 

**Verkefni 3 — Vision and Scope**

**Heiti kerfis:** Vaktin

**Teymi og höfundar:** Edil Inga Kristjánsdóttir og Gabríel Orri Karlsson

**Git repository:** https://github.com/edilinga/HBV301G-Verkefni-3.git

## Efnisyfirlit

1. [Viðskiptamarkmið](#1-viðskiptamarkmið)
2. [Framtíðarsýn](#2-framtíðarsýn)
3. [Prófíll mikilvægra notenda](#3-prófíll-lykilhagsmunaaðila-eða-mikilvægra-notenda)
4. [Forgangsröðun verkefnisins](#4-forgangsröðun-verkefnisins)
5. [Umfang fyrstu útgáfu (MVP)](#5-umfang-fyrstu-útgáfu-mvp)



## 1. Viðskiptamarkmið

Vaktaskipti á vinnustöðum geta verið tímafrek og óskipulögð þegar samskipti fara fram í gegnum hópspjöll, skilaboð eða aðrar óformlegar leiðir. Starfsmenn geta átt erfitt með að finna hæfan samstarfsmann til að taka vakt og vaktstjórar þurfa oft að verja tíma í að samræma og samþykkja breytingar. Tækifæri er því til að einfalda vaktaskipti, stytta tímann sem fer í að finna staðgengil og draga úr handvirkri umsýslu vaktstjóra.

### BO-1: Stytta meðaltíma sem tekur að finna staðgengil fyrir vakt um 50% innan sex mánaða frá innleiðingu kerfisins

| Atriði | Lýsing |
|---|---|
| Mælikvarði (Scale) | Meðaltími frá því að beiðni um vaktaskipti er skráð þar til hæfur staðgengill hefur fundist. |
| Mæliaðferð (Meter) | Tímastimplar í kerfinu mæla tímann frá skráningu beiðni þar til staðgengill hefur tekið vaktina. |
| Fyrri staða (Past) | Ekki þekkt enn. Upphafsstaða verður metin með upplýsingum frá starfsfólki um núverandi ferli áður en kerfið er tekið í notkun. |
| Markmið (Goal) | 50% styttri meðaltími innan sex mánaða frá innleiðingu kerfisins. |
| Metnaðarmarkmið (Stretch) | 70% styttri meðaltími innan sex mánaða frá innleiðingu kerfisins. |

### BO-2: Draga úr tíma sem vaktstjórar verja í umsýslu vaktaskipta um 40% innan sex mánaða frá innleiðingu kerfisins

| Atriði | Lýsing |
|---|---|
| Mælikvarði (Scale) | Meðaltími sem vaktstjórar verja í að samræma og afgreiða vaktaskipti. |
| Mæliaðferð (Meter) | Ekki þekkt enn. Upphafsstaða verður metin með því að mæla þann tíma sem fer í umsýslu vaktaskipta samkvæmt núverandi verklagi áður en kerfið er tekið í notkun. |
| Fyrri staða (Past) | Ekki þekkt enn. Upphafsstaða verður mæld með upplýsingum frá vaktstjórum áður en kerfið er tekið í notkun. |
| Markmið (Goal) | 40% minni tími fari í umsýslu vaktaskipta innan sex mánaða frá innleiðingu. |
| Metnaðarmarkmið (Stretch) | 60% minni tími fari í umsýslu vaktaskipta innan sex mánaða frá innleiðingu. |

### BO-3: Ná að minnsta kosti 90% hlutfalli vaktaskiptabeiðna sem leystar eru með hæfum staðgengli innan sex mánaða frá innleiðingu kerfisins

| Atriði | Lýsing |
|---|---|
| Mælikvarði (Scale) | Hlutfall vaktaskiptabeiðna þar sem hæfur staðgengill finnst og vaktaskiptin eru samþykkt. |
| Mæliaðferð (Meter) | Kerfið skráir fjölda vaktaskiptabeiðna og hversu margar þeirra enda með samþykktum vaktaskiptum við hæfan staðgengil. |
| Fyrri staða (Past) | Ekki þekkt enn. Upphafsstaða verður metin út frá upplýsingum um vaktaskipti áður en kerfið er tekið í notkun. |
| Markmið (Goal) | Að minnsta kosti 90% vaktaskiptabeiðna verði leyst með hæfum staðgengli innan sex mánaða frá innleiðingu. |
| Metnaðarmarkmið (Stretch) | Að minnsta kosti 95% vaktaskiptabeiðna verði leyst með hæfum staðgengli innan sex mánaða frá innleiðingu. |


## 2. Framtíðarsýn

Vaktin er snjallsímalausn og stjórnendaviðmót ætlað starfsfólki og vaktstjórum í vaktavinnu sem þurfa að framkvæma og samþykkja vaktaskipti og afleysingar á einfaldan og skilvirkan hátt.
Kerfið býður upp á rauntíma yfirsýn yfir lausar vaktir, sjálfvirkt eftirlit með hæfniskröfum og skýrt ferli fyrir samþykki vaktaskipta. Ólíkt óformlegum samskiptaleiðum eins og Facebook-hópum eða skilaboðaöppum heldur Vaktin utan um vaktaskipti á einum miðlægum stað, dregur úr handvirkri umsýslu stjórnenda og tryggir að aðeins starfsmenn sem uppfylla hæfniskröfur viðkomandi vaktar geti tekið við henni.

## 3. Prófíll lykilhagsmunaaðila eða mikilvægra notenda

**Val á notendahópi:** Starfsmenn og vaktstjórar voru valdir sem mikilvægustu notendahóparnir fyrir fyrstu útgáfu (MVP). Starfsmenn nota kerfið til að óska eftir afleysingu og taka að sér lausar vaktir, en vaktstjórar bera ábyrgð á að yfirfara og samþykkja breytingar. Báðir hóparnir eru því nauðsynlegir til að vaktaskiptaferlið virki og til að styðja við viðskiptamarkmið BO-1, BO-2 og BO-3.

### Prófíll 1: Starfsmenn

| Atriði | Lýsing |
|---|---|
| Notendahópur og hlutverk | Starfsmenn í vakta- eða hlutastarfi. Nota kerfið til að skoða eigin vaktir, óska eftir afleysingu og óska eftir að taka lausar vaktir. |
| Helsta virði (Major value) | Hraðari og einfaldari leið til að leysa úr vaktaskiptum og minni þörf á samskiptum í óformlegum hópspjöllum. Styður sérstaklega BO-1 og BO-3. |
| Viðhorf (Attitudes) | Búast við einföldu og skýru kerfi þar sem auðvelt er að sjá lausar vaktir og stöðu beiðna. |
| Helstu áhugamál (Major interests) | Einfalt viðmót, skýr staða beiðna, uppfært vaktaplan og tímanlegar tilkynningar. |
| Takmarkanir (Constraints) | Kerfið þarf að taka tillit til hæfniskrafna einstakra vakta og þess að vaktaskipti taka ekki gildi fyrr en stjórnandi hefur samþykkt þau. |

### Prófíll 2: Vaktstjórar / stjórnendur

| Atriði | Lýsing |
|---|---|
| Notendahópur og hlutverk | Vaktstjórar eða aðrir ábyrgir stjórnendur. Hafa yfirsýn yfir vaktaskipti og afleysingar og samþykkja eða hafna beiðnum. |
| Helsta virði (Major value) | Minni handvirk umsýsla, skýrari yfirsýn og auðveldara að tryggja að hæfur starfsmaður taki við vakt. Styður sérstaklega BO-2 og BO-3. |
| Viðhorf (Attitudes) | Búast við að kerfið einfaldi umsýslu án þess að þeir missi stjórn á samþykkt vaktaskipta. |
| Helstu áhugamál (Major interests) | Skýr yfirsýn yfir beiðnir, upplýsingar um starfsmenn og vaktir, hæfniskröfur og einfalt samþykktarferli. |
| Takmarkanir (Constraints) | Vaktaskipti mega ekki taka gildi án samþykkis stjórnanda og starfsmaður sem tekur við vakt þarf að uppfylla hæfniskröfur hennar. |

## 4. Forgangsröðun verkefnisins

Við forgangsröðun verkefnisins er stuðst við fimm víddir Wiegers og Beatty til að skilgreina hvaða þættir verkefnisins eru fastar kröfur og hvar svigrúm er til að aðlaga umfang og útfærslu. Markmiðið er að tryggja að hægt sé að afhenda nothæft MVP innan tilsettra tímamarka sem styður við viðskiptamarkmiðin og þarfir helstu notenda.

| Vídd | Flokkun | Rökstuðningur |
|---|---|---|
| **Eiginleikar (Features)** | **Degree of freedom (Frjálsleiki)** | Svigrúm er til að aðlaga umfang eiginleika svo lengi sem kjarnavirkni MVP styður BO-1, BO-2 og BO-3. Forgangur er á vaktaskiptum, afleysingum, hæfniskröfum, samþykki stjórnanda og uppfærðu vaktaplani. Aðrir eiginleikar geta beðið síðari útgáfu. |
| **Gæði (Quality)** | **Constraint (Takmörkun)** | Kerfið þarf að vera áreiðanlegt og auðvelt í notkun. Upplýsingar um vaktir og stöðu beiðna þurfa að vera réttar og uppfærðar og kerfið þarf að framfylgja skilgreindum hæfniskröfum og samþykktarferli. |
| **Tímasetningar (Schedule)** | **Driver (Drifkraftur)** | Tímasetningar stýra umfangi fyrstu útgáfu. Markmiðið er að afhenda nothæft MVP innan tilsettra tímamarka og því geta eiginleikar sem eru ekki nauðsynlegir fyrir kjarnavirkni beðið síðari útgáfu. |
| **Kostnaður (Cost)** | **Degree of freedom (Frjálsleiki)** | Enginn sérstakur fjárhagsrammi hefur verið skilgreindur fyrir verkefnið. Kostnaður er því ekki helsti þátturinn sem stýrir umfangi fyrstu útgáfu. |
| **Mannafli (Staffing)** | **Constraint (Takmörkun)** | Verkefnið er unnið af tveimur hópmeðlimum og mannafli er því fastur. Umfang og forgangsröðun verkefnisins þurfa að taka mið af þeim tíma og mannafla sem er til staðar. |

## 5. Umfang fyrstu útgáfu (MVP)

### 5.1 Umfang fyrstu útgáfu (MVP)

Fyrsta útgáfa kerfisins þarf að styðja við allt grunnferli vaktaskipta og afleysinga, frá því að starfsmaður óskar eftir afleysingu þar til stjórnandi hefur afgreitt beiðnina og vaktaplanið hefur verið uppfært.

| Hvað þarf að vera í MVP? | Hvers vegna? | Tengsl við fyrri verkefni, ef við á |
|---|---|---|
| Starfsmaður getur sett eigin vakt í afleysingu | Er upphafspunktur vaktaskiptaferlisins og gerir starfsmanni kleift að óska eftir staðgengli. Styður BO-1 og BO-3. | UR-1, FR-1–FR-3 |
| Starfsmenn geta skoðað lausar vaktir og óskað eftir að taka þær | Gerir mögulegum staðgenglum kleift að finna lausar vaktir á einum stað og styður hraðari afleysingar. Styður BO-1 og BO-3. | UR-2, FR-4–FR-5 |
| Kerfið kannar hvort starfsmaður uppfylli hæfniskröfur vaktar | Dregur úr hættu á að óhæfur starfsmaður taki að sér vakt og styður BO-3. | BRG-2, FR-6 |
| Stjórnandi getur skoðað, samþykkt eða hafnað beiðnum | Tryggir að stjórnandi haldi yfirsýn og stjórn á vaktaskiptum á sama tíma og umsýslan fer fram á einum stað. Styður BO-2 og BO-3. | BRG-1, UR-3–UR-4, FR-7–FR-11 |
| Vaktaplan uppfærist eftir samþykkt vaktaskipti | Tryggir að réttur starfsmaður sé skráður á vakt og að upplýsingar séu uppfærðar. | UR-5, FR-12–FR-15 |
| Notendur fá tilkynningar um stöðu beiðna og breytingar sem varða þá | Minnkar óvissu og þörf fyrir handvirk samskipti milli starfsmanna og stjórnenda. Styður BO-1 og BO-2. | UR-6, FR-16–FR-18 |


### 5.2 Rökstuðningur fyrir vali í fyrstu útgáfu

Atriðin í MVP voru valin vegna þess að saman mynda þau lágmarksferli sem þarf til að vaktaskipti og afleysingar geti farið fram í kerfinu frá upphafi til enda. Starfsmaður þarf að geta óskað eftir afleysingu, annar hæfur starfsmaður þarf að geta óskað eftir að taka vaktina og stjórnandi þarf að geta samþykkt eða hafnað breytingunni. Að lokum þarf vaktaplanið að endurspegla samþykkta breytingu og viðeigandi notendur að fá upplýsingar um niðurstöðuna.

Þessi virkni styður beint við BO-1 með því að auðvelda og flýta leit að staðgengli, BO-2 með því að halda umsýslu og samþykkt vaktaskipta á einum stað og BO-3 með því að kanna hæfniskröfur og halda utan um samþykktar beiðnir. Val á umfangi tekur einnig mið af forgangsröðun verkefnisins þar sem tímasetningar og mannafli takmarka hversu mikla virkni er raunhæft að hafa í fyrstu útgáfu.

### 5.3 Hvað bíður síðari útgáfu?

Fyrsta útgáfa leggur áherslu á grunnferli vaktaskipta og afleysinga. Frekari eiginleikar sem geta aukið þægindi og yfirsýn notenda geta komið í síðari útgáfum án þess að grunnvirði MVP tapist.

| Eiginleiki | Ástæða þess að hann getur beðið |
|---|---|
| Ítarlegri síun og leit að lausum vöktum | Grunnlisti yfir lausar vaktir nægir til að framkvæma kjarnaverkefni MVP. Ítarlegri leit og síun getur bætt notendaupplifun síðar. |
| Ítarlegri yfirlit og samantektir fyrir stjórnendur | Stjórnendur geta þegar skoðað og afgreitt beiðnir í MVP. Frekari yfirlit og samantektir eru gagnlegar en ekki nauðsynlegar fyrir grunnferlið. |
| Fleiri stillingar fyrir tilkynningar | MVP þarf að senda nauðsynlegar tilkynningar um beiðnir og breytingar. Sérsniðnar tilkynningastillingar geta beðið síðari útgáfu. |

### 5.4 Takmarkanir og útilokanir

Kerfinu er ætlað að halda utan um vaktaskipti, afleysingar og tengda uppfærslu vaktaplans. Það er ekki ætlað að vera heildstætt mannauðs-, launa- eða bókhaldskerfi. Launaútreikningar, launagreiðslur og önnur almenn mannauðsstjórnun eru því utan fyrirhugaðs umfangs kerfisins.
