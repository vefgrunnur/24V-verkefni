# Vefhönnun

### Markmið

Nemendur geta hannað einfaldan upplýsingavef sem hægt er að birta á internetinu

### Kröfulisti

Upplýsingavefurinn þarf að uppfylla eftrifarandi skilyrði

* Forsíða (landing page)
* Undirsíður
    * 3 vefsíður
* Efnisyfirlit (navigation)
    * Allar vefsíður með sama efnisyfirlit 
    * Allir tenglar í vefnum virkir  
* Innihald (main)
    * Umfjöllun um efni sem nemandi hefur valið (_Þema: kvikmyndir_) 
    * Myndir sem styðja innihald textans 
    * Video mynd frá Youtube &lt;video>
    * .mp3 hljóðskrá í &lt;audio>
    * Staðsetning á korti <iframe>
* Sveigjanleg hönnun
    * Vefsíðurnar aðlagast mismunandi skjástærðum
    * Viðmið: { 0 - 37.5em }, { 37.5 - 48em }, { 48em - 60em }, { 60em - 80em } og { 80em + }
* Leturgerð og litaval á að hæfa efnisinnihaldi vefsíðunnar. 
* Allur kóði á að vera skipulega uppsettur og myndir eiga að vera í sér möppu. Html tög sem eru hreiðruð í önnur tög eiga að vera inndregin. Í stílsíðu eiga eigindi að vera inndregin og stílar að vera skipulega settir í stílsíðuna.

### Námsmat 20%

* 2% Forsíða (Landing page)
* 2% Efnisyfirlit og tenglar 
* 6% Innihald vefs
    * 3 undirsíður
* 2% Myndanotkun (_.jpg, .png_)
* 2% API íhlutir (_kort, video og audio_)
* 2% Sveigjanleg hönnun
* 2% Leturgerð og litaval
* 2% Uppsetning kóða og frágangur


### Verkefnaskil

* Vefnum er skilað í **Innu/VEFÞ1VG/Verkefni 7**
  
#### Einkunn verður birt í Innu
		
_Gangi þér vel_

<!-- 
#### Uppsetning vefsíðu á (notandi).github.io

### Markmið:

nemendur geta:

Sett töflu með lagalista inn á vefsíðu
* Sett fyrirspurnarform inn á vefsíðu (_aðeins útlitshönnun_) 
* Birt eigin vef á eigin vefsvæði á https://(notandi).Github.io

## Uppsetning vefsíðu á (notandi).github.io  

Github býður viðskiptavinum sínum að búa til vef sem tengist reikningi þeirra. Eina sem þarf að gera er að virkja veftenginguna í Github notendastillingum (Settings). 

dæmi:  
1.	Gitub reikningur: **Notandi** 
1.	heiti geymslu: **notandi.github.io**
1.	Í notandi.github.io geymslunni -> valslá -> **Settings** -> **Pages**, þar velur þú "Branch": **Main**. 
1.	Github býr til tengingu á milli geymslunnar og vefhýsingarinnar á github.io 
1.	Nú getur þú birt verkefnin á eigin vefsíðu.
1.	Skilaðu tengli (_link_) í Innu sem vísar á vefsíðuna þína

* Tengli (link) á vefinn þinn á https://notandi.github.io er skilað í **athugasemdir** til kennara  


* Öll sýnidæmi áfangans eru á github.io: https://vefgrunnur.github.io/synidaemi/

---
-->

<!-- færist yfir á 2 önn
### Verkefni 7.1 Tafla – &lt;Table> 

Tabular Data &lt;td> er eina tagið sem er hannað til að sækja gögn af miðlara í hvert sinn sem vefsíða er opnuð, jafnvel þegar flett er á milli síðna. Það er mjög gagnlegt þegar um er að ræða upplýsingar sem uppfærast daglega eða oftar.

Töflur henta ekki í útlithönnun ss til að birta texta og myndir sem breytast ekki. Vafrinn getur geymt slíkar upplýsingar í vinnsluminni sínu og þarf ekki að sækja þessi gögn í sífellu. 

"Table" tagið er erfitt að eiga við þegar kemur að sveigjanleika vefsíðu og best að nota það ekki nema þegar um gagnvirkar færslur er að ræða.        

#### Hér er dæmi um [sveigjanlega töflu](https://allthingssmitty.com/2016/10/03/responsive-table-layout/).

---

### Verkefni 7.2 - Skráningarform - &lt;Form> 
Setjið skráningarform inn á vefinn ykkar, hafið samræmi í útliti formsins og töflunnar og í rökréttu samhengi við heildarútlit vefsins.  Formið á að vera sýnilegt í öllum helstu skjástærðum.

Formið er með fieldset utan um innsláttarsvæðin og hnappinn **_submit_**. Label tög
fylgja með valtökkunum **_radio_** og **_checkbox_**. Input tögin eiga að vera með viðeigandi type gildum a.m.k.**_text_**, **_email_** og **_tel_**. 

#### FORM VALIDATION – HTML5

```HTML

<input type=“x“ name=“x“ value=“X“ required placeholder=“fyllið út þennan reit“>

```
Þegar smellt er á hnappinn (_type submit_) í skráningarforminu þá á vafrinn að athuga (_validate_) hvort einver texti hafi verið settur í **_required_** innsláttarreitina. Ef reitirnir uppfylla ekki þau skilyrði þá á ekki að vera hægt að senda upplýsingar frá vefsíðunni, ef allt er í lagi þá sendum við innsláttinn út í bláinn. 

* Ekki er hægt að skilja nafnareit auðan 		
* Símanúmer verður að vera tölur (tel)
* Tölvupóstfang verður að vera með @	      	
* Notið „input date“
* Notið „select option, checkbox og radio“. 	
* Notið aðra leturgerð og stærð í „textarea“

#### [Sjá sýnidæmi](https://vefgrunnur.github.io/synidaemi/verkefni-7/umokkur.html)

--->
<!--
#### Tafla

* 3% 	Notaðu thead, tbody og tfooter tögin í töflukóðanum. Í stílsíðu er hægt að nota gerviklasa (Pseudo class - nth-child) til að fá litskiptingu í bakgrunn töflunnar.  
Taflan inniheldur upplýsingar sem eru skiljanlegar og skilmerkilega settar upp.
* 3% 	Taflan er svegjanleg (responsive) og skiptist þannig að hún er öll sýnileg
á litlum skjáum.

#### Form

* 3%	input -text, -email, -radio, -checkbox, select og textarea er í pöntunarformi 
* 3%	Ekki á að vera hægt að senda (submit) form fyrr en skilyrðum (request)  eru uppfyllt í „text“, „email“, „date“ og „telephone“.
-->
