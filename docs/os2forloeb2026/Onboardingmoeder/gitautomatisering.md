# Automatiserede Git processer m. Jan (kl.14-15.30)

Formål: forstå Muligheder og krav til at funktioner kan automatiseres i Git. Så jeg kan vurdere hvor ting kan automatiseres i selv-evalueringen. 


**Spørgsmål:**

- Hvordan skelner vi mellem noget, GitHub kan dokumentere, og noget GitHub kun kan give en indikator på?

For eksempel:

README.md exists = true

betyder vel ikke nødvendigvis:

Produktet er veldokumenteret = true.

Git er cicd = continuous integration continuous deployment 

den kan tjekke en fil, en struktur, måle ting op mod hinanden

Automatisering:
- defineret i en jaml fil = deklarativt format med key values 
- fx: trigger: xxx, når xxx sker, kør xxx
- genialt til test, verificering, 


Github automatisering:
- ligger i mappen "git workflows" 

**Prisen og formål**
- det er meget dyrt at lave automatiseringer - dev-ops synes bare det er sjovt at programmere, for der er ingen tekniske begrænsninger 
- så man skal overveje hvad man gerne vil opnå?
- det koster tid$$ at vedligeholde


andre standarder man kunne måle på, som er FOSS godkendt i EU (ved ik om de er stavet korrekt) 
- open source initiativ
- oas
- chaos 

fx codeowners 


**i tilfælde af OS2 bliver udsat for auditted, er det en nemmere at **
- fx via cyber recilience act 

Jans bud på hvordan vi optimerer selv-eva med automatiseringer 
- start med at lave en afdækning af hvad der ikke fungerer i selv-eva
  - hvor forståeligt, brugbar er selv-eva?
  - hvor meget værdi giver selv-eva?
  - hvor kan man identificere nogle helt 
  - hvad kræver det af dem at vedligeholde koden der skal automatiseres, der i sidste ende kommer ind i rapporten? 
- udpeg automatiseringer der skal laves
- små og mellemstore virksomheder kan levere det code

POC - proof of concept 
- når du laver noget der skal skabe yderligere funding
- brug 250.000 på at finde ud af om vi skal bruge 5 millioner



- hvad beder vi dem om ?
- hvad er det for noget evidens vi skal indsamle?

EU kataloget - måler på genanvendelig og kvaliteten i software 


**Annas noter til sig selv**

har sekretariatet for høje standarder for os2 produkterne og skulle de hellere have arbejdet i en ren os-organisation ? er de ambitiøse på fællesskabets vejene?

har medlemmerne i OS2 en anden opfattelse end sektretariatet 

jan og Al er fra en enterprise kultur: hvis du er uenig, så gå et andet sted hen  - men i OS2 skal det pakkes ind og gives med ske  


**Danmark skal ikke bygge software selv**
- gøre op med Linux-skismet (om at han er den der skal trykke på knappen)
- danmark skal ikke opfinde noget; stikkontakter, vandværker
- genbrug nu det der findes
- historisk misforståelse: at danmark er førende på digitalisering
- "hvis det ikke er dansk-produceret, og det ik er på dansk, er det ikke godt nok"
- AI / tech har udviddet skalaen så meget - du kan ikke engang se DK på skalaen længere; dansk it-selskaber er så bagud de kommer aldrig til at følge trop
- microsoft: embrace, alter, reproduce
- netcompany = laver hardcoded
- --> hvorfor momsdifferiencering er så svært at lave 


**hvem vil OS2 være?**
- i sidste ende skal vi understøtte fællesskabet og det de gerne vil have
- der pt ik lige appetit for open source som løsning
- skal man bruge call to action sprog? - for at få folk med på Open source missionen (de har meget uncertaincy, doubt, fear)
- prøv at undgå projekt-økonomien, som ikke er bæredygtighed

**case for hvordan OS2 kunne være**
*styrelse for arbejdsmarked og rekrutering:*
- center for exellence
- har indført versionsstyring fra start
- nu det ikke en stor indkøbskontrakt 
- netcompany, systematic etc hyret ind for KUN at lave dev-opgaver
- styrelsen kontrollerede backloggen 
- blev færdig før tid, under budget

**skæv magt mellem OS2 og leverandør i leverandør-samarbejdet**
- alle projekter har forskellige aftaler
- man burde have standarder for hvordan man er dev-leverandør eller drift-leverandør

moms-karussel: hvor it-chefer udpeger AC'ere i hans budget som kan 

jan vil gerne indføre jobsamtaler for fx produktkoordinatore, 

**Prince 2** - 
- Anna-Lis' er oplært i denne - hendes way of thinking 
- en standard man burde kunne følge i OS2
- den oversætter udvikler sprog (Jan) til AC sprog 
- kommunernes projektmodel kører efter det

**modstand mod git/hub**
- folk i kommunerne bryder sammen over det ikke kan løses i word
- de forstår ikke/magter ikke bruge et nyt værktøj

Anna-Lis' forandringsstrategi: **dream and details**
- hav store drømme, og så fix det du faktisk kan her nu
- "hvordan får ændret organisations tankesæt" -> små skridt hen mod et mål
- Anna-Lis mission: at få produktkoordinatorerne til at shine, og forhåbentlig få gode produkter derigennem -> hjælpe dem med at sætte krav op,
- så kan vi løfte niveauet for når vi hiver leverandører ind

