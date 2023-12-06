[Listi með öllum sýnidæmum.](https://vefgrunnur.github.io/synidaemi/)
<!--
# Nýskráning Github reiknings

- Nemendur verða að vera með Github reikning (_Github user account_)
- Til að stofna Github reikning verður þú að vera með tölvupóstfang (_E-mail account_). Þú getur notað skólapóstfang sem þér er úthlutað við innskráningu í Tækniskólann. [Hér eru leiðbeiningar á vef Tækniskólans um hvernig nemendur fá skólapóstfang](https://tskoli.is/nethjalp/um-skolanetfang/). Með því að nota skólapóstfangið getur þú fengið [Github Student Developer Pack](Namsefni-1/GithubStudentDeveloperPack.md) sem getur nýst þér vel í námi á tölvubraut.

1. Við skráningu Github reiknings verður að koma **skýrt fram hver er eigandinn**. Námsaðstoð fer í gegnum Github verkefnageymslu (_repository_) og þá er mikilvægt að kennari geti séð hver er eigandi reiknings. Kennari getur hafnað reikningi ef það er ekki gert.
    * Í **Stillingar (_Settings_)** er skráð fullt nafn.
1. Eftir nýskráningu færðu tölvupóst frá Github þar sem beðið er um staðfestingu (_confirm your email account_) á að þú sért að stofna reikninginn. 
1. Bættu við tölvupóstfanginu í **Profile -> Settings -> Emails** í Github reikningi þínum 

1. Til að Git geti tengst við Github þá verður að skrá Github notandanafnið þitt og tölvupóstfang í GIT BASH (_terminal_) [$ git config --global](https://vefgrunnur.github.io/verkefnaskil/git_innsetning.html) 
```
git config --global user.name "þittnotendanafn"
git config --global user.email þitt@email.is
```
1. Þú stofnar verkefnageymslu (_Repository_) á Github reikningnum þínum. Geymslan á að vera lokuð **_"Privat"_**. Engin nema þú og kennarinn eiga að hafa aðgang að geymslunni
1. Til að kennari geti haft aðgang að verkefnageymslunni þarf að opna aðgang fyrir hann
   * Farðu í _Settings_ og þar velur þú _Collaborators and teams_ 
   * Veldu _Add peoble_ og skráðu notandanafn kennara (t.d. GJG) og síðan veluru _"Add this member to this repository"_
1. Það er hægt að vinna verkefni beint í Github geymslunni en það er ekki skynsamlegt.  Best er að afrita verkefnageymsluna yfir á þína tölvu, vinna verkefnin og skila síðan jafnóðum.  [Náðu í geymsluna yfir í þína tölvu](https://vefgrunnur.github.io/verkefnaskil/git_verklag.html)

```

Github.com/notendanafnið þitt
   |___ README.md
   |___ vef1vg (verkefnageymsla - repository)

       
Staðvært umhverfi (local environment) = tölvan þín.
   |___	vef1vg (verkefnageymsla - repository clone)
-->
```


