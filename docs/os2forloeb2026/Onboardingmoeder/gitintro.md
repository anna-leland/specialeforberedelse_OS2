# Konceptuel intro til Git m. Anna-Lis og Jan (kl.9-11.30)

Formål: general indføring i Git og git-processer

Hvad er de bærende elementer?
Hvad er arbejdsflowet for at køre en gitorganisation?


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


