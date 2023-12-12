# Sveigjanleg hönnun vefs  (_Responsive Web Design_)
 
### Markmið:

Nemendur öðlast skilning á:

* hönnun svegjanlegs viðmóts (_Respnsive Web_) vefsíðu
* hvernig hægt er að vinna með CSS _@media_ skipunina til að breyta skipulagi vefsíðu miðað við skjástærð 

Skipulag vefsíðu með mörgum dálkum gengur ekki upp í litlum farsímaskjáum. Til að hafa áhrif á skipulag HTML síðu setjum við inn viðmið (_breakpoints_) í CSS stílsíðuna.  Við notum **_@media screen_** skipunina til að birta mismunandi skipulag eftir skjástærðum.  

## 4.1 Sveigjanlegt dálkaskipulag, 1, 2, 4

Afritaðu verkefni 3.1 yfir í verkefni 4.1 og gerum vefsíðna sveigjanlega.  Notaðu **_@media screen_** skipunina til að birta mismunandi skipulag eftir skjástærðum.

* Viðmið: 0 – 599px, allir dálkar með 100% breidd (1fr)
* Viðmið: 600px – 767px, 2 og 4 dálkar með 50% breidd (1fr 1fr)
* Viðmið: 768px – 959px, 2 dálkar 50% breidd (1fr 1fr), 3 dálkar 33.33% breidd (1fr 1fr 1fr) og 4 dálkar 25% breidd (1fr 1fr 1fr 1fr)

#### [Dæmi 4.1](Namsefni-4/README.md)

## 4.2 Sveigjanlegur vefur

Nú er komið að gera vefinn þinn sveigjanlegan. HTML tög eiga að hafa skiljanlega merkingu í uppsetningunni,  helstu tögin eru ` <header> <nav> <main> <section> <article> <aside> og <footer>`, [sjá öll tögin hér](https://www.w3schools.com/html/html5_semantic_elements.asp).  

Notaðu CSS Grid til að hanna eigið dálkaskipulag. Vefsíður þurfa að birtast í öllum helstu skjástærðum, búðu til viðmið (_breakpoint @media …_) til að stjórna skipulagi vefsíðunnar. 

#### [Sýnidæmi](https://vefgrunnur.github.io/synidaemi/verkefni-4/index.html)

### Námsmat 20% 

* **2% 4.1 Dálkaskipulag.** Vefsíða með 2, 3 eða 4 dálkum  
    * 0 – 599px (Allir dálkar skiptast í 1fr)
    * 600px – 767px (2, 4 dálkar skiptast í 1fr 1fr)
    * 768px – + (Allir dálkar skiptast rétt, 2, 3 og 4 dálkar)
* **8% 4.2.1 Vefsíða með viðmiðum**
    * Mobile: 0 – 599px  _eins dálks hönnun_  
    * Tablet: 600px – 767px _tveggja dálka hönnun_
    * Desktop: 768px – 959px _3 eða 4 + dálka hönnun_
    * 960px + Efni vefsíðunnar er miðjusett (_max-width_) í vafranum
*  **3% 4.2.2 Valmynd sveigjanleg og bakgrunnslitir**
    * Valmynd (nav) skal vera svegjanleg (_display:flex_)
    * Tengla (_links_) í valmynd skal stíla (ekki hafa sjálfgefnar stillingar)
    * Mismunandi bakgrunnslitir í `nav, main og footer`
*  **3% 4.2.3 Rétt notkun taga og framsetning á HTML og CSS**
    * HTML5 ritháttur, hreiðruð tög inndreginn
      * `nav, header, main, aside, article og footer`
    * Uppsetning á CSS
      * ```css
        .daemi {
            skipun:gildi;
        }
        ```
*  **4% Texti notaður sem þú hefur samið og skipulagt** 
    * Vefur með forsíðu og einni undirsíðu (_lágmark_) eða fleiri
    * Allir tenglar á milli síðna virkir með huldu klösum (_pseudo classes, link, visited, hover og active_)  

### Verkefnaskil:  

Öllum gögnum er skilað í **Innu/VEFÞ1/Verkefni 4**.

> **Athugið** að sýnindæmi eru ekki metin til einkunnar.

#### Einkunn verður birt í Innu

_Gangi þér vel_
