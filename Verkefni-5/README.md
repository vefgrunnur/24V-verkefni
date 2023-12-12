> Verkefni 5 nýtt!

# Leturgerð, leiðakerfi og bakgrunnar


### Markmið:

Nemendur geta:

* unnið með mismunandi leturgerðir og náð í leturtýpur á [Google Fonts](https://fonts.google.com/). 
* skipulagt leiðakerfi fyrir vef (_innri og ytri tenglar_).
* fundið samræmi í leturgerð og litanotkun miðað við efni vefs 
* sett bakgrunnsliti í vefsíðu

---

### Listar  
 
Búðu til lista með eftirtöldum upplýsingum 

* Tenglar í haus og fæti vísa á vefsíður verkefnisins (_relative links_)
* Settu tengla sem vísa á aðra vefi á internetinu (_absolute links_) í _footer_ tagið

#### [Sjá sýnidæmi](https://vefgrunnur.github.io/synidaemi/verkefni-6/)

---

### Val á leturgerð  

* Passar leturgerðin sem þú velur, málefninu?  
* Hentar litaþemað sem þú hefur valið, málefninu?

Sækið leturgerðir á [Google font]() vefsíðuna sem hæfa efninu sem þú hefur valið.  Setjið mismunandi stíla á fyrirsögn, millifyrirsagnir og meginmálsletur, tengla, lista.  


### Bakgrunnsmynd í vefsíðu

```CSS

body {
    background-color: #6ff;
    background-image:url(flott-logo.svg);
    background-repeat: no-repeat;     /* repeat-x eða repeat-y */
    background-position: 200px 300px; /* föst staðsetning frá vinstra horni efst */
    background-position: center middle;
    /* X lárétt: left, center, right. Y lóðrétt: top, middle, bottom */
    background-attachment: fixed; /* scroll */	
}
/* allar bakgrunns-skipanir í einni */
body {			
	background: rgb(3,3,3) url(image.jpg) 0px -5px scroll no-repeat;
            /*  litur,   mynd,  staðsetning X-Y,  fixed,  repeat -x -y */

}

```