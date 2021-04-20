## Samenvatting

### Regie op bouwgegevens

Het project “Regie op Bouwgegevens” beoogt de informatievoorziening binnen de
bouwsector (publiek & privaat) te verbeteren. De Unieke Objectidentificator
(UOI), richt zich daarbinnen specifiek op het ontwikkelen van een unieke
objectidentificatie. Deze UOI-code moet het mogelijk maken om gegevens op
verantwoorde en betrouwbare wijze te kunnen registreren, uitwisselen (delen) en
koppelen aan andere gegevens. Onderliggend wordt hiermee beoogd de gegevens over
objecten in de gebouwde omgeving domein-overstijgend te kunnen delen, waarbij de
UOI-code het identificeren verzorgt.

### Vervolgonderzoek

Dit document bevat de onderzoeksresultaten van een verdiepend onderzoek naar de
(on-) mogelijkheden van het gebruik van een UOI-code om objecten in de gebouwde
omgeving persistent uniek te kunnen identificeren. “In een eerdere fase (de
eerste onderzoeksfase) is een [eerste opzet
ontworpen](https://fibree.org/uoi-nl/) door een consortium van Fibree, Kadaster
en BZK. Bij de huidige (de tweede onderzoeksfase) heeft BZK Geonovum betrokken
om het ontwerp van de UOI beter af te stemmen op bestaande standaarden, zoals
NEN 3610, NEN 2660 & NTA 8035 en de manieren waarop deze omgaan met
identificatie (zoals o.a. toegepast bij een aantal basisregistraties) en ook op
de ideeën ten aanzien van identificatie vanuit DiS Geo (de samenhangende
objectenregistratie, SOR).

### Object versus informatie-object

De eerste vraag die het onderzoeksteam zich heeft gesteld, is waaraan een
UOI-code moet worden toegekend. Daarbij is van belang te bedenken dat elk domein
een eigen kijk op de werkelijkheid kan hebben en dus eigen informatie-objecten
kan hebben gedefinieerd. Allereerst is vastgesteld dat de UOI-code aan een
informatie-object moet worden toegekend. Dat informatieobject kan zowel gegevens
bevatten over een fysiek of een virtueel object in de gebouwde omgeving. De
UOI-code wordt dus gekoppeld aan de informatieobjecten over de fysieke dan wel
virtuele dingen (en dus niet aan die dingen zelf omdat de objectdefinities
daarvan per domein kunnen verschillen).

### Vorm van een UOI-code

Aanvankelijk leek de ontwerpopgave zich te concentreren op de vorm van de
UOI-code. Binnen een [recente
SOR-consultatie](https://www.geobasisregistraties.nl/documenten/publicatie/2021/03/11/reactiedocument-eerste-consultatie-conceptueel-model-sor)
is vastgesteld dat deze vooral uniek, persistent en machine-leesbaar moet zijn.
Daarmee kan de UOI-code bijvoorbeeld via een UUID[^1] of URI[^2]-strategie
worden vormgegeven. Ook is een UOI-code op basis van bestaande domein-ID’s
denkbaar.

[^1]: Als UUID bevat een UOI-code een unieke reeks karakters.

[^2]: Als URI zullen in een UOI-code waarschijnlijk een \<namespace\> en een
\<identifier\> te herkennen zijn.

### Gebouwde omgeving

De gebouwde omgeving is in dit kader gedefinieerd als de verzameling domeinen
waar gegevens in de vorm van informatieobjecten worden vastgelegd over:

-   Alle fysieke[^3] objecten die als onroerende zaken worden aangeduid (zoals
    gebouwd, geplaatst, geïnstalleerd, gelegd, aangelegd dan wel duurzaam
    aanwezig in de grond of het water maar ook niet-gebouwde fysieke objecten
    die wel van belang zijn voor de gebouwde omgeving zoals aanwezig in de
    topografische basisregistraties);

    [^3]: Fysiek (materieel of reëel)

-   Alle virtuele[^4] objecten die vanuit wet- en regelgeving en/of
    maatschappelijk verkeer gerelateerd zijn aan de fysieke objecten (zoals over
    gebruik, eigendom, heffing, subsidie, vergunning, adres, werkingsgebieden,
    beheergebieden, verzorgingsgebieden).

    [^4]: Virtueel (immaterieel of niet-reëel)

Niet meegenomen in de reikwijdte t.b.v. de UOI-code worden onderwerpen als:

-   Gebeurtenis-gebaseerde zaken (transacties) (zoals levering, overdracht,
    vergunning, enz.) betreffende de hierboven genoemde objecten;

-   De productie van bouwmaterialen & bouwproducten (hiervoor wordt de
    GS1-code[^5] veel gebruikt).

    [^5]: [GS1-code](https://www.gs1.nl/) is een productcode die veel gebruikt
    wordt in de productie-industrie

### Bouwproducten & -materialen & de UOI-code

Bouwproducten en -materialen krijgen mogelijk pas bij installatie of gebruik pas
een UOI-code. Namelijk wanneer er een verbinding kan worden gelegd tussen het
geserialiseerde[^6] bouwproduct en hun toepassing in een bouwobject.

[^6]: Bouwproducten kennen een type en een serienummer. Het achterhalen van
materiaaleigenschappen of gebruikte materialen kan per serie verschillen.

### Domein-onafhankelijke uitgifte van de UOI-code

Domeinen kennen elk hun eigen manier van indelen naar klassen (taxonomie) of
structuur (meronomie). Soms zijn structuur-relaties (deel/geheel)[^7] in een
domein vast gedefinieerd, soms variabel te benoemen zoals het IFC-model dat
mogelijk maakt. Ook zaken zoals de tijdvolgordelijkheid van informatieobjecten
(filiatie) worden veelal door de domeinen zelf bepaald. We beogen we de uitgifte
van de UOI-code te ontkoppelen van domeinspecifieke keuzes en semantiek Er is
dus een uitgifte-/generatieregime voor UOI-codes nodig dat onafhankelijk de
“eeuwigdurendheid” van het informatieobject op UOI-code-niveau garandeert

[^7]: Meronomie: relaties die deel geheel of compositie/aggregatie van objecten
definiëren (Gebouw bestaat uit verblijfsobjecten en verblijfsobjecten uit
ruimten enz.)

### Ruimere vraagstelling

Het onderzoeksteam van Geonovum en Kadaster heeft na de validatie van het eerste
onderzoekrapport geconcludeerd dat het succesvol delen en kunnen gebruiken van
gegevens over objecten uit de gebouwde omgeving meer vraagt dan alleen een
unieke objectidentificatie. De ontvanger moet gegevens ook kunnen relateren aan
eigen objecten en gegevens en ze semantisch kunnen interpreteren. Deze
aanvliegroute werd door het ingestelde UOI-expertteam beaamd. Dit inzicht heeft
in overleg met de opdrachtgever geleid tot een ruimere vraagstelling, waarin
naast de identificatie (UOI-code) ook de semantische interpretatie via een
verwantschapsontologie en een strategie voor het vinden van de relatie op
instantieniveau zijn meegenomen. Daarmee is de vraag over de UOI-code verruimd
tot een over een UOI-codestelsel.

### Domein-onafhankelijk kunnen verbinden

Domeinen hanteren eigen objectdefinities, spelregels voor vastleggen van de
geometrie, functie van het object, de opbouw van de deel/geheel relaties,
alsmede spelregels hoe met levensloop wordt omgegaan en of objecten wel of niet
worden opgenomen in de eigen registratie. Het kunnen verbinden van
domeingegevens vraagt om mogelijkheden semantisch te kunnen interpreteren zonder
te moeten harmoniseren. Dat wordt gezien als de opgave voor een werkend
UOI-code-stelsel.

### Paraplumechanisme om te verbinden

Een UOI-codestelsel is dus een overkoepeld stelsel dat als een paraplumechanisme
aangesloten domeinen weet te verbinden, waardoor gegevens in de
domeinregistraties gezocht, gevonden en semantisch geïnterpreteerd kunnen
worden. Het is uitdrukkelijk iets erbij en niet in plaats van. Domeinen worden
gezien als zelfstandige informatiestelsels met eigen besturen en spelregels. Een
UOI-codestelsel met de voorgestelde wegwijzer voor semantisch interpreteren
geeft beperkte regie op samenhang, is schaalbaar in omvang en kwaliteit en richt
zich op het verbinden van bestaande registraties. Het is daarmee een soort
paraplumechanisme voor de registraties die de gebouwde omgeving tot hun domein
rekenen.

Het doel van een UOI-codestelsel is het vereenvoudigen van het
domeinoverstijgend zoeken, vinden en semantisch interpreteren van gegevens over
objecten in de gebouwde omgeving.

### Samenhang met de SOR

De SOR in wording stuurt op volledigheid en maximale kwaliteit en is groeiende
in harmonisatie en aansluitbaarheid. De SOR is daarmee een soort
"kapstokdomein", waarbinnen het UOI-mechanisme ook moet kunnen worden toegepast.

### Alternatieven variëren qua functionaliteit

De beschreven alternatieven voor een UOI-codestelsel dekken deze principes van
identificeren, semantisch interpreteren en relateren in meer of minder mate af.
De geboden functionaliteit van de alternatieven hangt ook samen met de keuze om
relaties en semantische verwantschappen **vooraf** klaar te zetten in plaats van
**achteraf** te construeren. De alternatieven voor een UOI-codestelsel komen
voort uit het variëren op aspecten zoals federatieve tegenover centrale
voorzieningen, meer regie tegenover minder regie en meer impact tegenover minder
impact op bestaande registraties.

Het onderzoeksteam heeft vijf alternatieven voor een UOI-codestelsel onderkend.
Elk alternatief maakt wel of niet gebruik van mechanismes voor het
identificeren, semantisch interpreteren en relateren van informatieobjecten.
Onderstaande tabel typeert deze in het kort.

| Hfst | Oplossingsvariant                 | Bevat expliciet vooraf                | Dus zelf blijven doen                                          |
|------|-----------------------------------|---------------------------------------|----------------------------------------------------------------|
| 3.2  | Sober UOI-codestelsel             | Alleen UOI-codes                      | Verwantschap bepalen en relaties leggen                        |
| 3.3  | UOI-codestelsel + verwantschappen | UOI-code + verwantschappen            | Zelf relaties leggen                                           |
| 3.4  | UOI-codestelsel + relaties        | UOI-code + relaties                   | Zelf verwantschappen bepalen                                   |
| 3.5  | Formeel UOI-codestelsel           | UOI-code + verwantschappen + relaties | Zelf de zoekvraag formuleren en antwoorden interpreteren       |
| 3.6  | Geen UOI-codestelsel              | Gebruikt domein-ID’s Geen UOI-code    | Alles zelf doen, relateren en verwantschappen achteraf bepalen |

**In acht te nemen aspecten**

Domeinen en registraties moeten zich stapsgewijs kunnen aansluiten. Daarom
worden de uitgegeven/gegenereerde UOI-code, de vastgelegde relaties en de
uitgevoerde semantische interpretaties bij het ontstaan van nieuwe objecten in
de gebouwde omgeving. Ook moeten gegevens over bestaande objecten kunnen worden
aangemeld voor opname in het UOI-codestelsel.

**SWOT-analyse na consultatie**

Het onderzoeksteam heeft nu nog geen voorkeur voor alternatieven. Eerst zal een
eerste consultatie plaatsvinden. Daarna is een SWOT-analyse voorzien, waarna een
tweede consultatie zal volgen. Het onderzoeksteam volgt hier qua consultatie
dezelfde werkwijze als BZK voor de SOR.

**Vele vormen van relaties**

Informatiebruggen worden gebouwd via de relaties tussen de met UOI-codes
aangeduide informatieobjecten. De aard van deze relatie tussen
informatieobjecten kan variëren van semantische relaties (zoals “*komt exact
overeen*” en “*maakt deel uit van*”) tot “*heeft een ruimtelijke relatie*“ en
wordt via een verwantschapsontologie benoemd.

Dergelijke relaties kunnen langs twee wegen worden gelegd: op basis van locatie
(ruimtelijke analyse) of via identificerende codes. In de praktijk gaat het
toekennen van de unieke identificerende code vaak langs beide wegen. Soms geven
we het object een domeinidentificatie en relateren het daarna aan een locatie en
soms verloopt dat andersom. Een ontwerp voor een type woning behoeft geen
locatie te hebben en kan voor meerdere locaties hergebruikt worden. Zo krijgt
een prefab-bouwobject pas een locatie wanneer deze geplaatst wordt. Tegen de
achtergrond van duurzaam hergebruik kunnen bouwobjecten vaker hergebruikt gaan
worden en zal dan hun locatie gedurende hun levensloop kunnen veranderen.

De ontstane relaties tussen informatieobjecten (die over hetzelfde fysieke of
virtuele object gaan) kunnen naar keuze in de bestaande objectregistraties of in
een voor iedereen toegankelijke registratie worden vastgelegd. Deze registratie
van UOI-relaties kan een centraal of federatief[^8] karakter dragen.

[^8]: Decentrale opslag binnen federatief regime

**Organisch groeiend én meerwaarde**

Daarbij is het van belang aan te geven dat we aan een organisch groeiend
federatief stelsel denken dat zich behoefte-gestuurd kan ontwikkelen als er
meerwaarde is. Of die veronderstelde meerwaarde bestaat, zullen we na de
consultatie in een aansluitende SWOT-analyse proberen vast te stellen. Daarbij
komen ook aspecten als bijhouden, robuustheid, organisch kunnen groeien,
zelforganisatie, regie, impact op de bestaande registraties e.d. aan de orde.

Ongeacht waar de UOI-code wordt vastgelegd of welke vorm voor de UOI-code wordt
gekozen, moet de UOI-code “eeuwigdurend” kunnen worden gevonden. Onvindbaarheid
van de UOI-code, van de domeinregistratie waarin de gegevens van het
informatieobject zich behoren te bevinden of van het informatieobject in de
domeinregistratie schaadt de betrouwbaarheid en de werking van het
UOI-codestelsel.

**Knooppunt-entiteiten als verbinders**

Het onderzoeksteam verwacht dat alleen aan zogenoemde knooppuntentiteiten
UOI-codes hoeven te worden uitgegeven en wil dat in de casussen toetsen.
Knooppuntentiteiten zijn entiteiten (objecttypes) die een verbindende schakel
vormen in het relateren tussen domeinen. Binnen de domeinregistratie kan immers
via de UOI-code en de gevonden domein-ID verder worden gezocht. De
informatiebrug is dan gelegd. Dat zou kunnen betekenen dat niet aan alle
entiteiten in de aangesloten domeinen UOI-codes behoeven te worden gegeven.

**Kennisgraaf**

Verwantschappen tussen entiteiten uit meerdere domeinen kunnen worden vastgelegd
in een
[kennisgraaf](https://en.wikipedia.org/wiki/Knowledge_graph#:~:text=A%20knowledge%20graph%20is%20a,%E2%80%93%20with%20free%2Dform%20semantics.)[^9].
Verwantschapsoperatoren geven dan aan hoe instanties moeten worden behandeld,
bijvoorbeeld bij een exacte verwantschap, maar ook bij indicatieve
verwantschappen. Daarbij is het onvermijdelijk dat het gebruik van indicatieve
verwantschappen soms kan leiden tot onjuiste conclusies, zelfs als de gegevens
in de domeinregistraties foutloos zouden zijn.

[^9]: Dat is een model waarin de verwantschappen tussen entiteiten uit meerdere
domeinen beschreven worden. Zie ook bijlage 4.

**Praktijksituaties**

Hoofdstuk 4 van dit onderzoeksrapport zal aanvullende praktijksituaties gaan
beschrijven waarin elk van de onderkende alternatieve UOI-codestelsels haar
specifieke meerwaarde biedt. In hoeverre deze meerwaarde opweegt tegen de
inspanningen en impact van elk alternatief, zal later in de SWOT-analyse worden
onderzocht.

De gehanteerde casusbeschrijvingen zijn:

1.  Bouwwerkrenovatiepaspoort (i.s.m. Fibree c.s);

2.  Opleverdossier (Dossier bevoegd gezag) (i.s.m. Kadaster c.s.);

3.  Materiaalcertificaten (i.s.m. Fibree c.s.);

4.  Energienetwerkaansluitingen (i.s.m. Kadaster c.s.).
