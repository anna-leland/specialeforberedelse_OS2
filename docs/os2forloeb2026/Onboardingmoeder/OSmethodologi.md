# Open-source metodologi og praksis v. Jan og Anna-Lis (man kl.13.30-15)

Formål: at jeg får en indføring i methodologien bag open-source og leverance modeller 

Spørgsmål:
- Hvordan måler man modenheden af et produkt?
- Hvor vil du pege mig hen, når jeg skal læse op på open-source guru'er, cases etc?
- Hvad er en leverance model helt præcist?
    - Når I siger leverancemodel, hvilke dele af leverancen skelner I så mellem i OS2?
- Hvad er ideal tilstanden af et open source produkt og hvordan får man det til at passe ned i et kommunalt it-produkt?
- Oplever du diskrepanser imellem ideel open-source praksis og hvordan OS2's produkter håndteres i deres styre/koordinationsgrupper? I så fald hvordan?
- 


# Noter fra mødet

ejerskab vs. licens -

software ≠ en ting, software er = en process

# hvordan man bygger software generelt -> og hvor open source adskiller sig 
## WHAT ? DEV+DELIVERY -> en continuous improvement

<img width="4032" height="3024" alt="software_og_OS_software" src="https://github.com/user-attachments/assets/dbd44e5e-8561-4005-8a5e-713effb25ea2" />

**I OPENSOURCE UDSTILLER MAN DEN SKJULTE PROCESS**: 
- *Build test automate* -> forskellen i OS: man kan se hele processen og komme med forslag (alt under midterlinjen på billedet)
- starter hos nogen, som ikke ved noget om software, som bestiller noget der skal blive til software ud fra et **WHY** -> bliver til et ***issue*** 
- man hiver derefter ting ned i et branch, så man kan arbejde med det lokalt 
- derefter commit = en gemt ændring i Git-historikken
- rull request (RP) = en anmodning om at få en række commits flettet ind i en anden branch
- robotter/eller mennesker tjekker koden igennem udfra **kildekoden**
- **kildekoden** = regler
- ens RP skal matche ens grundlæggende dokument; lincens, user acceptance test, etc
- = bliver til et artefakt
- human in the loop tager en beslutning om at der skal laves et release (ud fra hvad ens strategi er, hvad har man lovet shareholdes) - rykkes over i et public release repo. Man burde helst bruge semantisk versionering
- **RELEASE**
- **OPERATIONS (OPS)**: et **MANIFEST** har komplekse automatiseringer, det kan fx være batch script der tager den færdigbyggede kode og eksekverer og kører den (i OS er man i tvivl om præcis hvem der kører det, i et kommcerielt firma er det bestemt hvem der må køre det)
- SQL database kan blive besluttet inden og deklareret i manifestet, men det kan også være op til en selv hvordan man vil køre det 
- UI elementet er SÅ småt, ift. hvad man tror er software, der er så meget bagved facaden
-  i den driftsmæssige integration, vil man lave lokale tilpasninger

## WHY ? ejerskab og værdi
- ur-magaer analogien; som blackbox og man selv åbner uret eller om urmageren slet ikke vil ha du ved hvordan man gør; vil ik løbe tør for arbejde 
- OS interesse fødes ofte ud af magtesløshed om et behov for ejerskab eller frihed til selv at vælge
- bliver ik så ofte som man tror født ud af en værdi om digital suverænitet fx (folk forskellige holdninger til hvad digi sov er; fx ordentlige licensaftaler m Microsoft - synes jeg jo ik tæller)
- Ift. at sørge for folk bygger ordentlig software:
      - closed source: gå den reaktive vej: gå ind efterfølgende med bøder og lade folk rette ind med straffe
      - open source / transparens: man bør bruge versionsstyring kode/docs -> giver stor transparens; hvem gjorde, hvad, hvorfor - tydeliggør ansvaret. Der er en konvention/skabelon for hvordan man skriver ordenlige commitbeskeder: tidspunkter.
- men vil man ha transparens? det skræmmer nemlig nogen, HVOR åbent ens arbejde (og fejl) bliver - opening the black box
- men hvis man ikke gider alt det her, fordi man ikke orker det - så er det hårdt arbejde at sidde med OS 
# De **fire friheder i open source/fri software** er:
1.  **Friheden til at bruge** softwaren til ethvert formål.
2. **Friheden til at undersøge og ændre** softwaren, så den passer til ens behov. Det kræver adgang til kildekoden.
3. **Friheden til at dele** kopier af softwaren med andre.
4. **Friheden til at dele ændrede versioner** af softwaren, så andre også kan få gavn af forbedringerne

- os2-brugeren: "jeg ville bare gøre x"  ... men det hele er skræddersyet, og det skræmmer dem, at de skal gøre en stor indsats - de vil helst bare tage en færdig løsning. Men der findes ikke én løsning; der er 35 afhængigt af ens behov. Og hvis man ikke forstår at man bare kan rulle tilbage, eller vælge om, så bliver de bange for at lave fejl.

- git ligger også i et database/repo, så får du også noget ejerskab , så kan du altid rykke det over i en anden operation eller pushe forskellige versioner ud til forskellige brugere fx lande med/uden GDPR-lovgivning

- **issue tracking**: en metode der hænger sammen med Forges (fx GitHub) et webinterface, der har en måde at tracke på en åben måde
- et problem kan tit være at en leverandør har noget af deres udvikling bag lukkede døre, så issue tracking er ikke transparent, - rammes af virkeligheden hvor kodet bliver personbundet og sårbar (orlov, barsel, sygdom, fyringer)
- godt eksempl **Blizzard:** åbnede op for deres WoW spil, så man kunne gå ind og brokke sig og selv teste løsninger, gjorde det til et af de bedste spil 
- trade-off: lev med at du udstiller dine fejl, og det passer ik så godt til et myndighedskoncept om at alt skal være perfekt
- **unicorn fallacy**: at man gatekeeper sin kode bag lukkede døre fordi den er "unik"; closed source - interlektuel property bruges som argument
- men myndigheder er ikke i konkurrence: alle laver det samme, og tosset at udvikle vær vores .. trods Henrik Brix tror han skal udvikle alt selv m Favrskov som afsender
- **EKSEMPEL** Vægværket fra Sveirige, samme produkt i NZ og blev brugt af noget tredje i England --> præcis hvad OS2 er bygget på 3+4=98 
- Open Source = "en moderne og kvalitetsbevidst måde at forbedre sig selv på"
- Old world og lukket tech = SaaS produkter, som er billigt og kan replikeres og sælges unikt og til overpris til alle kommunerne -> leverandørernes drøm
- transparens = giver en afledt kvalitetseffekt, som OS2 ikke kan fejre, fordi man samtidig ville gå ud og sige "gud hvor var produkterne i leverandører lavede dårlige før I gik open source" 
- kæmpe forskel på produkter udviklet ud fra dev experience vs. User experience

## Ejerskab
- den der **godkender** pull request er den der har ejerskabet - kan være i flere niveauer hvor de første 80% kan være automatiseret af robotter og de sidste 20% ofte af mennesker
- man bruger user acceptance testing inden merges for at understøtte UX. 
- **eksempel på et super agilt dev+deploy arbejdsplads**: Rul imellem 2 teams: et deploy-team og et developer-team: Demo-friday af nye features -- tænk over det i weekenden - deploy-team arbejder med rettelser man-tirs, kan rettes ons-tors og ny demo fredag. Og imens har dev-team tænkt på nye features, som deploy så kan arbejde på den næste uge. 
- beskyt din main branch: det er vores produkt. Skal have 4-eyes principles. Skal have tests. Jo mere automatisereringer kan man lave, jo nemmere.
- dårlig ide: Når man patcher nye versioner direkte ind i sit main branch -> bliver til et configuration-drifted
    - man mister historikken, det er ikke modulært, så man kan ikke trække de branches ud igen, 
- **sunken cost fallacy**: projektejer kan ikke klare at gå af med deres kildekode fordi de har brugt så mange timer på at skabe den
  - gør at de er hader for at man sletter noget og skriver helt nyt, hvilket giver en masse code rot med gammel og ubæredygtig kode som bliver gemt 'bare fordi'


## Templet - Mål-styrings model/ Ejerskabs tempel 

=<img width="4032" height="3024" alt="templet" src="https://github.com/user-attachments/assets/06cd1b17-6bde-4429-88cb-685df479a6af" />

- Toppen af templet: Mål (og hvorfor): ejerskab, evt. digi sov, frihed 
- Søjlerne: Metoder (hvordan): metodesæt - måden du arbejder på -> kan være:
      - **gode metoder:** eksempler på høj kvalitets softwarebyggeri på: fx Bent Flyvbjergs "plan slow, act fast" eller "prepare, plan, execute",
      - men kan også være **dårlige metoder:** fx. unicorn fallacy, sunken cost fallacy (se definition ovenfor) 
- Fundamentet: Værktøjer (på hvilken måde): git, pr-flows, forges 

Projektkoordinatorer er i virkeligheden projekt administratorer: de skal kontrollere 
i et **usundt** OS fællesskab: product owneren sidder typisk hos leverandøren og er den der godkender PR'er (kan hurtigt blive indspist) 
i et **sundt** OS fællesskab: product owneren sidder **EKSTERNT** og er den der godkender PR'er 

Squashed commits: 200 commits i én omgang - det er total malpractice - fordi man misser alle de forskellige commits, der er ikke gennemsigtighed og du kan ikke 
dump: de kopierer bare main branchen ned til OS2 - som ikke har mangler manifester, transperens 

## Leverandør roller: at man uddeler ansvaret ud på forskellige leverandører
- optil flere 1000 developers
- 1 lev der kører hosting i et datacenter
- 1 lev kører applikationslag
- 1 lev kører driftslag
- flere lev kører support
- 1 lev sidder og tjekker repo igennem
- 1 lev laver deployment
- 1 lev dev bygger applikationen
- 1 lev laver moniterering
- i stedet for bygge alt selv, så Udnytte at 3+4=98, så man deler udgifter 

ingen grund til at opfinde den dybe tallerken - det kræver så meget vedligehold etc og det er DYRT 
man skal lave én fælles kildekode, som alle kan tage i brug og bruge lokalt 
modul-byggeri: hvor man trækker på fx a, b, d, og h -> bruger i sin lokale kontekst /så man kun bruger til sit behov 

**hardcoding = VERTIKALT**: når leverandører koder det direkte ind i det samme sprog, som kun kan bruges én måde -> og du kan kun skalere veritkalt og køre det op i CPU ram, men når du rammer kapicitet kan du ikke skalere mere, så bare håb det ik bliver Black friday 

**Cloud native = HORIZONTAL**: at pakke ting en på en ensartet måde, så alle kan hente ting ned på en effektiv løstkoblet kode og bruge dem lokalt i deres forskellige programmeringssprog, 

# analogier for open source software og properiter software:

IKEA byg-selv møbler 
- al software er 'byg selv' moduler
- men delene er bygget ud fra standard skruer, umbraco, samlevejledning, du kan betale ekstra for montering, 
- -> i open source: du tager selv ansvaret når du tilpasser.
- -> properitær software: købe det samlet hos JYSK og så må du gå retur til leverandøren hvis limsamlingen går fra hinanden 

storebælt:
- forskellige regler, lovgivning, standarder, inspektører, bygge teams osv 
- forskelle: der er ikke lovning i software, man sætter regler op og prøver at bygge det fra start alt er reaktivt med GDRP/NIS2 frameworks 
- man kan holde sin kode lukket/ejerskab pga "intellektuel property", så du kan ikke blive audited og dermed ikke kontrolleret
  

det modsatte af reaktivt: security by design/by default 
- ikke en populær holdning, for der er mange penge i sikkerheds-audit 

## software leverandøren: hvem vil man være? 
- Zappa-metoden: klam ejerskabsmodel, binde og låse kildekoden væk (pengene der driver værket - har med magt at gøre) 
- WoW-metoden: vær den dygtigste, tør læg din kode ud åbent, indrøm fejl og ret dem og få folk til at hjælpe med rette fejlene (har alt med software at gøre, og det tjener man så penge på)

OS2 projektet understøtter at der ikke bør være konkurrence i det offentlige: istedet for at kæmpe om krummerne, så bager vi en stor kage, så der er slices til alle 


software kan være svært at overskue og forstå - det kan være i plain site og hidden anyway

den prøver OS at gøre op med - tag alt ud og eksponer det - 

Hvordan tjener man penge på Open source (fortsættes en anden dag) 
- ved at være den bedste til at udvikle, pudse og pleje
- copy-left: man kan indskrive i licensen at hvis du bruger den her kode, så skal du gøre XYZ fx give koden tilbage eller betale  
