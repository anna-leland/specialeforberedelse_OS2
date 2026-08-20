# Konceptuel intro til Git m. Anna-Lis og Jan (kl.9-11.30)

Formål: general indføring i Git og git-processer

Hvad er de bærende elementer?
Hvad er arbejdsflowet for at køre en gitorganisation?

OS2 - har lagt alle æg i GitHubs kurv
- vi har ikke købt 'github' som et produkt; det kan man ikke - det er bare en samarbejdsplatform 
- ejer ikke en 'version' af github, som vi kan kontrollere 
- vi har ingen backups
- hvis github går ned i morgen, så har vi måske en gammel version liggende 


TEMPEL

<img width="4032" height="3024" alt="git_templet_konceptuel intro" src="https://github.com/user-attachments/assets/27b4742d-4418-47b4-9bfb-822b575520cc" />


mål:
- fremme samarbejde, deling, digital udvikling
- udbrede kendskab og brug af FOSS (free open source software) 

metoder:
- standardisering
- governance 
- versionsstyring, industry best practice fra software industrien, trods ingen kommuner kender det (timestamps, hvem lavede hvad, hvornår, hvorfor, nej-tak, godkendelser, peer-review)
- transparens 

fundament:
- git:

værdier:
- "ting bliver her"
- "...historik"
- "frihed, tryghed" -> man tør lave fejl og ting er ikke endegyldige, man kan undgå at merge, det kan bare rulles tilbage 


**git**
- pronix unix standard
- kommandolinjeværktøj
- .git files, skjulte og reserverede til systemet -> bliver til et database agtigt versionstræ med repo-struktur
- diff-værktøjet: kan hvad er forskellen på de her 
- push fra lokal computer til en server, dele på tværs af tidszoner
- pull 
- commit
- merge

# forges (nogen der 'smedjer' GIT i en samarbejdsplatforme) 

**commercielle samarbejdsplatforme, venture capitalist backed, har enterprise modeller**
- **github** - microsoft owned og de laver funktioner som nu kun fungerer i GitHub 
- gitlab - open core; bedre end Github og mere open source, men ikke perfekt (elephant factor på 1) - de er lidt lukkede om sig selv
  - *"Elephant factor measures the minimum number of companies whose employees contribute a specified percentage of the total commits in a software repository"*

**reelle FOSS** - alternativer til commercielle samarbejdsplatforme 
- gitea (der sad én godkender og det blev folk trætte af) 
- *afledt* af gitea og videreudviklet: **forgejo** - -> her Europa peger henimod. Er *implementeret* i:
  - codeberg: de laver en federeret activity pub (et system for trusted partnere, uden at man skal have en konto) 
  - .NL (Jan kan ik huske navnet)
  - med flere! 

motivation for at tage dårlige beslutninger i software: 
- fear uncertainty and doubt 

alle produkter har forskellige github 'organisationer' repos 
- ingen strukturer sat op for deres repos
- modenheds-vurdering: Jan har fået oprettet niveauet under niv-1 i Sandboxen, hvor produkter kan testes inden de får en 'organisation' 
- hvornår må man sætte titlen 'os2' på ? det kan blive open washing - for at få financiering 

vi skal **ikke opfinde/innovere** nye standarder fra OS2 
- vi skal bruge standarder der allerede findes/er skabt af FOSS organisationer som virker - så dem bør vi henvise til
- det er virkelig uproduktivt at prøve at opfinde det selv

Danmark skifter handler kun om at det ik må være amerikansk
- men hvis man har ordenlige kontroller, så er det vel fint ? (siger Jan og AL)
- virkelig mange produkter der har
- vi skal bruge det som er forankret i anderkendte, internationale og selvstyrende foundations 

når nogen siger at Danmark er førende inden for open source -> næh nej, se Liam Maxwell - government digital services, rock star for at bruge OS for 15 år siden 


# eftermiddagsmødet
data-versionsstyring vs.  betjeningsværktøjer. 
