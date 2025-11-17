# Uvod v Git

Git je orodje, ki omogoča **sledenje spremembam** v datotekah in učinkovito **sodelovanje v skupinah**.  
Nastal je leta 2005, ko ga je Linus Torvalds razvil za upravljanje izvorne kode Linux jedra.  
Od takrat se je Git razširil in postal **standard** v svetu razvoja programske opreme.

Git omogoča, da vsak razvijalec dela **lokalno** na svojem repozitoriju, nato pa spremembe deli z drugimi preko **oddaljenega repozitorija** (npr. GitHub, GitLab ali Bitbucket).  
S tem se zmanjša možnost konfliktov in izgube podatkov.


## Glavne značilnosti

- **Zgodovina sprememb**: vsak commit predstavlja točko v zgodovini projekta.  
- **Veje**: omogočajo razvoj različnih funkcionalnosti vzporedno.  
- **Skladnost (merge)**: Git zna združiti spremembe različnih razvijalcev.  
- **Razpršenost**: vsak razvijalec ima popolno kopijo repozitorija.  
- **Zanesljivost**: Git zagotavlja integriteto podatkov s preverjanjem hash vrednosti (SHA-1).


## Pogosti ukazi

| Ukaz | Namen |
|------|--------|
| `git init` | Ustvari nov lokalni repozitorij |
| `git clone <url>` | Klonira obstoječi repozitorij |
| `git status` | Prikaže stanje sprememb |
| `git add <datoteka>` | Doda datoteko v pripravo za commit |
| `git commit -m "Opis spremembe"` | Zabeleži spremembe |
| `git push` | Pošlje spremembe v oddaljeni repozitorij |
| `git pull` | Povleče nove spremembe z oddaljenega repozitorija |
| `git branch` | Prikaže ali ustvari nove veje |
| `git merge <veja>` | Združi določeno vejo z trenutno |
| `git log` | Prikaže zgodovino commitov |



