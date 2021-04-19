# Oplossingsalternatieven op een rij

In dit hoofdstuk worden vijf oplossingsvarianten nader uitgewerkt. Het betreft
een uitwerking op hoofdlijnen ter afdekking van het spectrum van
oplossingsrichtingen.

1.  Vijf onderkende alternatieven

Tijdens het onderzoek zijn vijf alternatieven onderkend voor het realiseren van
een UOI-code-stelsel. In dit hoofdstuk zullen we die vijf alternatieven
beschrijven. We typeren deze maar geven als onderzoekers nog geen oordeel over
de oplossingen. Daartoe is een consultatie en een SWOT-analyse na de consultatie
voorzien. In de onderstaande figuur zijn 4 alternatieven weergegeven die
stapsgewijs de drie principes van identificeren, relateren en semantisch
interpreteren bevatten. We hebben daarnaast een vijfde alternatief onderkend dat
gebruik maakt van bestaande lokale identificatoren en dus voorbij gaat aan het
gaan gebruiken van een UOI-code-stelsel. Dat is een soort nul-alternatief.

| [./media/image29.png](./media/image29.png)                   |
|--------------------------------------------------------------|
| Figuur 15: Onderkende alternatieven met een UOI-code-stelsel |

Hierna worden deze alternatieven nader getypeerd en beschreven. In het denken
over deze alternatieven zijn mogelijke aspecten voor het kiezen van groeipaden
in overweging genomen. Denk aan het kunnen aansluiten van domeinen, meenemen van
meer en diepere verbindingen en de mate van regie die nodig is op het realiseren
van deze alternatieven. Deze worden later bij de SWOT-analyse (na de
consultatie) in ogenschouw genomen.

1.  UOI-code-stelsel (sober)

In deze paragraaf wordt een beschrijving gegeven van een UOI-code-stelsel dat
wordt opgebouwd uit een bouwsteen voor UOI-codes en UOI-informatieobjecten. Het
betreft een uitwerking als minimale variant voor een UOI-code-stelsel.

We beantwoorden de volgende vragen:

-   Welke componenten worden gebruikt?

-   Hoe werkt het dan?

-   Wat faciliteert het stelsel?

-   Wat moet je als gebruiker zelf blijven doen?

-   Wat karakteriseert deze oplossingsvariant?

In deze variant voor een mogelijk vorm te geven UOI-code stelsel wordt slechts
één principe door het UOI-code-stelsel actief ondersteund. Het principe van
*identificeren* wordt ondersteund door de uitgifte van UOI-codes aan objecten in
de gebouwde omgeving. Het vinden van de verwantschappen (het principe van
*semantisch interpreteren*) wordt aan de gebruiker overgelaten. Ook het
feitelijk vinden van de relaties tussen objecten (het principe van *relateren*)
wordt overgelaten aan de gebruiker die zelf linksets tot stand brengt.

**Welke componenten worden gebruikt?**

In dit alternatief wordt alleen de functionaliteit van het UOI-code-stelsel voor
identificatie (sleutel) gebruikt. Functionaliteit voor het beschrijven van
verwantschappen en het relateren op instantieniveau worden niet ontwikkeld. Dit
wordt aan de gebruiker overgelaten. Dat betekent dat de volgende componenten uit
het UOI-code-stelsel worden ingezet/ontwikkeld:

| **Registratie van**                                          | **Regime voor**                                |
|--------------------------------------------------------------|------------------------------------------------|
| UOI-codes \<UOI-code-register\> voor UOI-informatie-objecten | Uitgifte van UOI-codes / UOI-informatie-object |
| [./media/image30.PNG](./media/image30.PNG)                   |                                                |

**Hoe werkt het dan?**

Het UOI-code-uitgiftemechanisme bewaakt alleen de uitgifte van unieke codes.

Nagelaten wordt om te controleren of er al een UOI-informatie-object op dezelfde
locatie (binnen het zelfde ruimte) bestaat. Wanneer dat zo is lijkt het immers
aannemelijk dat sprake kan zijn van een relatie tussen de instanties. Het wordt
aan de uitgever van een nieuwe UOI-code overgelaten om te kijken of er wellicht
in een willekeurige andere registratie al een gerelateerd object is
geregistreerd.

**Wat faciliteert het stelsel?**

Het UOI-code-stelsel faciliteert dan het identificeren van alle relevante
(virtuele & fysieke) objecten in de gebouwde omgeving en het gebruik van deze
identificaties van dergelijke objecten in andere registraties.

In deze variant zijn de verwantschappen (en daarmee de knooppunt entiteiten) dus
onbekend. Uitgifte van UOI-codes vindt plaats voor alle objecten die waarvoor
dat door gebruikers (uit aangesloten domeinen) wordt aangevraagd.

De UOI-code-registratie kan naar keuze zowel centraal als federatief worden
vormgegeven. Er worden minimale gegevens vastgelegd zoals de UOI-code, gegevens
over de aanvrager, de uitgifte zelf & het soort object (domein-entiteit) waar de
UOI-code voor is uitgegeven. Dat is in de onderstaande figuur illustratief
weergegeven.

| [./media/image31.png](./media/image31.png) |
|--------------------------------------------|
| Figuur 16: UOI-code uitgifte               |

Er zijn meerdere variaties op het hierboven getoonde logische proces denkbaar.

**Wat moet je als gebruiker zelf blijven doen?**

Als je als gebruiker instanties van objecten in datasets wilt relateren, zul je
zelf naar die dataset moeten gaan kijken wat precies de afbakening en betekenis
is van die objecten die aangeduid zijn met UOI-codes. Ook is er geen eenduidige
manier om de gegevens van die andere registratie(s) op te halen. Wil de
gebruiker de gegevens koppelen, dan zal de gebruiker dus al het werk zelf moeten
doen.

**Wat karakteriseert deze oplossingsvariant?**

Dit alternatief kan gezien worden als een minimum oplossing voor een
UOI-code-stelsel. Er is alleen sprake van unieke code bij objecten. Deelnemende
partijen garanderen dat een unieke nummer aan slechts één object in hun
registratie wordt toegekend. Wat dat object inhoudt of waar het mee verbonden
is, moet de gebruiker zelf achterhalen. Deze variant is nog het best te
vergelijken met de ISBN-code voor boeken. Bij de ISBN-code is het object het
boek. Je weet dat ieder boek een unieke code heeft. Je weet wel zeker dat als
partijen het over dezelfde ISBN-code hebben, dat ze hetzelfde boek bedoelen! Er
is een zoekservice om te herleiden wel boek er achter welke ISBN-code zit.

*Voorbeeld* <https://www.zoekeenboek.nl/boeken-zoeken/isbn-zoeken/> *Primair
worden basale gegevens getoond. Dit veronderstelt een (federatieve of centrale
registratie) Tevens is zichtbaar dat deze service ook soortgelijke boeken over
het zelfde thema zoekt & vindt. Blijkbaar de in de ISBN-registratie of verbonden
registraties ook relaties op titel of thema gevonden. Niet bij ISBN
geregistreerde boeken worden niet gevonden.*

1.  UOI-code stelsel met geregistreerde relaties

In deze paragraaf wordt een beschrijving gegeven van een UOI-code stelsel dat
wordt opgebouwd uit een bouwsteen voor UOI-codes en UOI-relaties; Het betreft
een uitwerking op hoofdlijnen ter afdekking van het spectrum van
oplossingsrichtingen.

.

We beantwoorden de volgende vragen:

-   Welke componenten worden gebruikt?

-   Hoe werkt het dan?

-   Wat faciliteert het stelsel?

-   Wat moet je als gebruiker zelf blijven doen?

-   Wat karakteriseert deze oplossingsvariant?

| In deze variant voor een mogelijk vorm te geven UOI-code stelsel worden twee principes door het UOI-code stelsel actief ondersteund. Het principe van *identificeren* wordt ondersteund door de uitgifte van UOI-codes aan objecten in de gebouwde omgeving. Het feitelijk vinden van de relaties tussen objecten (het principe van *relateren*) wordt eveneens actief ondersteund. Er zijn dan dus linksets beschikbaar voor de knooppunt entiteiten. Het vinden van de verwantschappen (het principe van semantisch interpreteren) wordt aan de gebruiker overgelaten. |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|


In deze variant is er geen beheerde verwantschap-laag. De gebruiker moet deze
dus zelf realiseren om in staat te zijn relaties te leggen en deze op te nemen
in een linkset die daarna beschikbaar komt voor een ieder.

**Welke componenten worden gebruikt?**

In deze variant zijn de volgende componenten gebruikt.

| **Registratie van**                                          | **Regime voor**                                                           |
|--------------------------------------------------------------|---------------------------------------------------------------------------|
| UOI-codes \<UOI-code-register\> voor UOI-informatie-objecten | Uitgifte van UOI-codes / UOI-informatie-object                            |
| [./media/image32.PNG](./media/image32.PNG)                   |                                                                           |
| UOI-object-relaties                                          | Geen regime. Relaties komen voort uit aanvragen voor opnemen van relaties |
| Er ontstaat een model van UOI-object-verwantschappen op M1   |                                                                           |
| Er ontstaan UOI-ontologieën (info-modellen domeinen)         |                                                                           |

We geven een korte toelichting:

-   UOI-code: Het format van de UOI-code is gedefinieerd in een aantal regels.
    In 2.5 en 3.2 staat op hoofdlijn hoe het proces om te komen tot deze regels
    er uitziet.

-   ID uitgifte & regime: UOI-codes worden uitgedeeld door een centrale
    UOI-uitgifte instantie of mechanisme. De instantie of het mechanisme zorgt
    voor een unieke registratie van uitgegeven UOI-codes. De UOI-code wordt
    toegekend aan nieuw gecreëerde informatie-objecten en ook uitgegeven aan al
    bestaande informatie-objecten. Bij de eerste ontstaat er voor nog niet in
    een registratie opgenomen domeinen een nieuwe registratie. Bij de tweede
    ontstaat er een nieuw UOI-informatieobject en de relatie daarmee wordt in
    een bestaande registratie vastgelegd.

-   Regie, regime relaties leggen: De relaties tussen informatie-objecten worden
    door de aangesloten domeinen zelf gelegd. Zo worden de linksets opgebouwd
    die daarna worden ontsloten. De verantwoordelijkheid voor het leggen van de
    relaties ligt daarvoor bij de aangesloten domeinen (of registraties). De
    relaties worden unilateraal gelegd vanuit een registratie naar een andere
    registratie zonder dat daar regie op is. Bij het leggen van de relatie hoeft
    het ‘doel-informatie-object’ het ‘bron-informatie-object’ niet te kennen
    maar als de relatie is gelegd kan het in beide richtingen worden bevraagd.
    De relatie hoeft ook niet altijd direct te liggen. Een informatieobject X
    heeft een relatie met een informatieobject Y en Y weer met Z. Z heeft
    daarmee ook een relatie met X. Er ontstaat hierdoor een ‘web van relaties’.
    De relaties worden geregistreerd bij een centraal toegankelijk register van
    UOI-codes en relaties. Het register van relaties is een groeiend register
    naar gelang er meer relaties worden gelegd. De relaties kunnen worden gelegd
    en geregistreerd door actief tussen informatie-objecten in bestaande
    registraties relaties te leggen en daarnaast op basis van uitvoering en
    realisatie van bijvoorbeeld bouw- en ontwikkelprojecten.

-   Linksets: Linksets worden opgebouwd zoals hierboven beschreven. De linksets
    worden centraal beheerd en kunnen daarnaast geïntegreerd zijn in de
    registraties.

**Hoe werkt het dan?**

Er is een centraal register van UOI-codes en van relaties tussen UOI-codes. Dit
register is bevraagbaar. Het bevragen van het register gebeurt altijd vanuit een
bestaande registratie. Stel jouw bevragingswereld is het bouwdomein en je wilt
van een bepaald informatieobject in de registratie, bijvoorbeeld een brug
(Julianabrug te Willemstad), weten welk ander domein informatie heeft over deze
brug. Via het centrale register vind je gekoppeld aan de UOI-code van deze brug
alle UOI-codes van informatieobjecten uit andere registraties die ook informatie
over deze brug hebben. Via bevraging van die registraties op die UOI-codes krijg
je de gekoppelde informatie.

| [./media/image33.png](./media/image33.png)                                  |
|-----------------------------------------------------------------------------|
| Figuur 17. Proces van analyseren en vastleggen relaties tussen UOI-objecten |

Het bevragingssysteem kan uitgebreid worden met een (API) koppeling naar de
aangesloten registraties zodat resultaat automatisch wordt terug geleverd Bij de
UOI-codes kan ook het aan de registraties gekoppelde begrippenkader of
informatiemodel worden gekoppeld. Het informatieobject brug (Julianabrug,
Willemstad) levert dan bijvoorbeeld als gekoppelde informatie op: UOI-object
type=‘monument’ (Julianabrug, Willemstand); UOI-object ‘type=vleermuishabitat’;
UOI-object ‘type=brugconstructie’; etc…. De bevrager kan op basis hiervan de
registraties bevragen op de informatiebehoefte die er is.

Beheer en regie op actualiteit van het register is nodig. De relaties krijgen
daarom een tijdstempel voor de begin en eindtijd van de geldigheid. Dit beheer
kan alleen gestuurd worden door het beheer van de aangesloten registraties. Als
bijvoorbeeld een informatieobject wordt beëindigd worden de relaties ook als
beëindigd geregistreerd. De informatie blijft wel aanwezig zodat ook historische
bevragingen mogelijk zijn.

**Wat faciliteert het stelsel?**

De centrale voorziening zorgt voor een gecoördineerde uitgifte van UOI-codes en
bouwt hiermee een domein-overstijgende registratie op van UOI-codes. De
UOI-codes bevatten meta-informatie o.a. met betrekking tot objecttype, herkomst
en temporele eigenschappen. De meta-eigenschappen kunnen worden uitgebreid.

De UOI-codes bevatten de informatie over de registratie waar het
informatieobject is geregistreerd. De centrale voorziening kan de koppeling naar
het informatieobject in de registratie ontsluiten o.a. door API koppelingen.

De centrale voorziening bevat de relaties tussen UOI-codes. De relaties kunnen
worden opgevraagd. Afhankelijk van beschikbaarheid van informatiemodellen van
aangesloten domeinen is bevraging over domeinen heen mogelijk op basis van
koppelentiteiten

**Wat moet je als gebruiker zelf blijven doen?**

De aangesloten registraties moeten zelf:

i.r.t. beheer en onderhoud:

-   een mechanisme hebben om het beheer van hun eigen registratie te
    synchroniseren met de centrale voorziening;

-   aangevraagde UOI-codes opnemen in hun registratie;

-   de registratie bevraagbaar maken op basis van UOI codes;

-   zelf nadenken over het registreren van relaties in de centrale voorziening.

i.r.t. gebruik van de voorziening:

-   Bij het bevragen van de voorziening moeten op basis van bekendheid met
    informatiemodellen van aangesloten domeinen de relaties worden
    geïnterpreteerd. Bevraging over modellen heen die verder gaat dan de
    koppelentiteit kan alleen op basis van bekendheid met informatiemodellen.

*Het kan voorkomen dat sommige objecten met toegekende UOI-code niet verder
worden gebruikt. Bijvoorbeeld bij een afgewezen vergunning, een ontwerp dat niet
wordt doorgezet. Alleen objecten die echt gerealiseerd worden (gebruikt worden)
kennen een langere linkhistorie. Er kan in de ogen van een beheerder
“vervuiling” in de registratie ontstaan omdat er objecten in voorkomen die niet
verder leven in de ‘gebruikelijke’ levenshistorie van een object. Als er geen
afmelding plaatsvindt, blijven deze objecten en hun relatie bestaan. Dat zijn
dan wel objecten die niet verder kwamen in hun levenscyclus dan bijvoorbeeld het
ontwerpstadium. Dat is natuurlijk de consequenties van deze manier van
vastleggen en niet mogen/kunnen verwijderen.*

**Wat karakteriseert deze oplossingsvariant?**

Deze variant heeft de volgende karakteristieken:

-   UOI-code wordt onder regie, uitgegeven;

-   UOI-code bestaat naast eventuele registratie-eigen code;

-   UOI-code is een informatieobject met alleen basisinformatie; de inhoudelijke
    informatie blijft in registraties;

-   relaties tussen UOI-codes wordt centraal geregistreerd op basis van aanvraag
    uit aangesloten registraties;

-   registratie van relaties is een groeimodel;

-   registratie van relaties heeft geen effect op domeinmodellen;

-   relaties lopen van bron-UOI-informatieobject naar doel-UOI-informatieobject.
    Ze zijn naar beide kanten op bevraagbaar;

-   er is geen verwantschap-laag of regie daarop. Verwantschappen worden door de
    registraties zelf gelegd;

-   een verwantschap-laag ontstaat vanzelf door het semantisch registreren van
    relaties.

    1.  UOI-code stelsel met geregistreerde verwantschappen

In deze paragraaf wordt een beschrijving gegeven van een UOI-code-stelsel dat
wordt opgebouwd uit een bouwsteen voor UOI-codes en UOI-verwantschappen. Het
betreft een uitwerking op hoofdlijnen ter afdekking van het spectrum van
oplossingsrichtingen.

We beantwoorden de volgende vragen:

-   Welke componenten worden gebruikt?

-   Hoe werkt het dan?

-   Wat faciliteert het stelsel?

-   Wat moet je als gebruiker zelf blijven doen?

-   Wat karakteriseert deze oplossingsvariant?

In deze variant voor een mogelijk vorm te geven UOI-code stelsel worden twee
principes door het UOI-code stelsel actief ondersteund. Het principe van
identificeren wordt ondersteund door de uitgifte van UOI-codes aan objecten in
de gebouwde omgeving. Het principe van semantisch interpreteren wordt
ondersteund door het opbouwen van een verwantschaps-ontologie voor
knooppunt-entiteiten. Het feitelijk vinden van de relaties tussen objecten (het
principe van relateren) wordt overgelaten aan de gebruiker die zelf linksets tot
stand brengt.

**Welke componenten worden gebruikt?**

In dit alternatief worden de functionaliteit van het UOI-code stelsel voor
identificatie (sleutel) en verwantschapsherkenning (wegwijzer) gebruikt. De
functionaliteit voor relateren op instantieniveau wordt niet ontwikkeld. Het
relateren wordt aan de gebruiker overgelaten.

Dat betekent dat de volgende componenten uit het UOI-stelsel worden
ingezet/ontwikkeld:

| Registratie van                                              | Regime voor                                    |
|--------------------------------------------------------------|------------------------------------------------|
| UOI-codes \<UOI-code register\> voor UOI-informatie-objecten | Uitgifte van UOI-codes / UOI-informatie-object |
| [./media/image34.PNG](./media/image34.PNG)                   |                                                |
| UOI-object-verwantschappen                                   |                                                |
| Domein informatie-modellen                                   | Registratie van UOI-object-verwantschappen     |
| UOI-ontologieën (info-modellen domeinen)                     |                                                |

**Hoe werkt het dan?**

Het UOI-code-uitgiftemechanisme controleert in de verwantschap-laag of een
UOI-code wordt aangevraagd voor een knooppunt-entiteit. Wanneer dat zo is, wordt
een UOI-code uitgegeven en geregistreerd. De aanvrager registreert verplicht de
UOI-code ook in de domeinregistratie bij de desbetreffende object-instantie.

Nagelaten wordt om op basis van de bekende verwantschappen of er in verwante
registraties al een registratie van een UOI-object op dezelfde locatie (binnen
hetzelfde ruimte/locatie) bestaat. Wanneer dat zo is lijkt het immers
aannemelijk dat sprake kan zijn van een relatie tussen de instanties. Bij
twijfel kunnen aanvullende manieren van relateren worden ingezet door de
gebruiker. Zie 2.3 en 3.3.

**Wat faciliteert het stelsel?**

Het UOI-code-stelsel faciliteert dan het identificeren van knooppunt entiteiten
die op de verwantschap-laag tussen de domeinen herkend zijn. (identificeren) Het
UOI-code-stelsel faciliteert het beschikbaar hebben van een verwantschap-laag
van entiteiten in domeinen op knooppunt niveau. (semantisch interpreteren)

Het proces van analyseren van deze verwantschap is hieronder gevisualiseerd.

| [./media/image35.png](./media/image35.png)            |
|-------------------------------------------------------|
| Figuur 18. Proces van realisatie van een verwantschap |

**Wat moet je als gebruiker zelf blijven doen?**

Als gebruiker zul je in dit alternatief zelf de relaties op instantieniveau
moeten achterhalen die relevant zijn voor de door jou als gebruiker gestelde
domein-overstijgende vraag. Als gebruiker moet je zelf de linkset daartoe zien
samen te stellen.

**Wat karakteriseert deze oplossingsvariant?**

Dit alternatief kan gezien worden als een sleutel en wegwijzer voor het
beantwoorden van domein-overstijgende vragen. We karakteriseren dit als een
eerste groeistap voor een UOI-code-stelsel.

1.  Formeel UOI-code stelsel

In deze paragraaf wordt een beschrijving gegeven van een Formeel UOI-code
stelsel. Het betreft een uitwerking op hoofdlijnen ter afdekking van het
spectrum van oplossingsrichtingen

We beantwoorden de volgende vragen:

-   Welke componenten worden gebruikt?

-   Hoe werkt het dan?

-   Wat faciliteert het stelsel?

-   Wat moet je als gebruiker zelf blijven doen?

-   Wat karakteriseert deze oplossingsvariant?

In deze variant voor een mogelijk vorm te geven UOI-code stelsel worden drie
principes door het UOI-code stelsel actief ondersteund. Het principe van
*identificeren* wordt ondersteund door de uitgifte van UOI-codes aan objecten in
de gebouwde omgeving. Het principe van *semantisch interpreteren* wordt eveneens
ondersteund door het opbouwen van een verwantschap-laag voor
knooppunt-entiteiten. Het feitelijk vinden van de relaties tussen objecten (het
principe van *relateren*) wordt eveneens actief ondersteund. Er zijn dan dus
linksets beschikbaar voor de knooppunt entiteiten.

**Welke componenten worden gebruikt?**

In dit alternatief worden de functionaliteit van het UOI-code-stelsel voor
identificatie (sleutel) en verwantschapsherkenning (wegwijzer) én relateren
(gelegde wegen (wegenstructuur)) gebruikt. De functionaliteit voor relateren op
instantieniveau wordt ook ontwikkeld. Dat betekent dat de volgende componenten
uit het UOI-code-stelsel worden ingezet/ontwikkeld:

| Registratie van                                              | Regime voor                                    |
|--------------------------------------------------------------|------------------------------------------------|
| UOI-codes \<UOI-code register\> voor UOI-informatie-objecten | Uitgifte van UOI-codes / UOI-informatie-object |
| [./media/image36.PNG](./media/image36.PNG)                   |                                                |
| UOI-object-relaties                                          | Registratie van UOI-object-relaties            |
| UOI-object-verwantschappen                                   | Registratie van UOI-object-verwantschappen     |
| Domein informatie-modellen                                   |                                                |
| UOI-ontologieën (info-modellen domeinen)                     |                                                |

**Hoe werkt het dan?**

Het UOI-code-uitgiftemechanisme controleert in de verwantschap-laag of een
UOI-code wordt aangevraagd voor een knooppunt-entiteit. Wanneer dat zo is én er
geen verbindend informatie-object met een UOI-code reeds bestaat voor deze
instantie, wordt een UOI-code uitgegeven en geregistreerd. De aanvrager
registreert verplicht de UOI-code ook in de domeinregistratie bij de
desbetreffende object-instantie. Zie ook 3.2.

Tevens wordt op basis van de bekende verwantschappen nagegaan of er in verwante
registraties al een registratie van een UOI-object op dezelfde locatie (binnen
dezelfde ruimte) bestaat. Wanneer dat zo is lijkt het immers aannemelijk dat
sprake kan zijn van een relatie tussen de instanties. Bij twijfel worden
aanvullende manieren van relateren ingezet door de gebruiker. Zie 2.3.

Tevens worden de relaties tussen de instanties van de UOI-objecten bepaald en
geregistreerd. Dit gaat als volgt. De bestaande UOI-code register wordt bevraagd
om de entiteit van het UOI-object waarvoor de relaties gezocht worden ten
behoeve van registratie te kennen. Daarna wordt de verwantschappen van deze
entiteit opgezocht in de verwantschap-laag (ontologie). Daarmee weten we dat
alle eerder geregistreerde UOI-objecten die op dezelfde locatie/ruimte binnen de
‘minimum bounding box(es)’ van de geometrie van deze UOI-objecten vallen een
ruimtelijke relatie met elkaar hebben. Deze relaties leggen we als koppelparen
vast om het daarna bevragen direct te kunnen beantwoorden. Er worden direct
wegen naar de gerelateerde objecten gelegd. We doen dit alleen voor de
knooppunt-entiteiten. Wil een gebruiker verder zoeken binnen een
domeinregistratie waarmee voor het opgevraagde UOI-object een relatie bestaat,
dan moet deze zelf deze registratie via de UOI-codes uit de koppelparen
bevragen.

**Wat faciliteert het stelsel?**

Het UOI-code-stelsel faciliteert dan het identificeren van knooppunt entiteiten,
die op de verwantschap-laag tussen de domeinen herkend zijn. (identificeren) Het
UOI-code-stelsel faciliteert het beschikbaar hebben van een verwantschap-laag
van entiteiten in domeinen op knooppunt niveau. (semantisch interpreteren). Het
UOI-code-stelsel faciliteert dan het relateren op instantieniveau van de
aangemelde UOI-informatie-objecten (alleen die als knooppunt entiteit herkend
worden).

**Wat moet je als gebruiker zelf blijven doen?**

Als gebruiker zul je in dit alternatief zelf de relaties op instantieniveau
moeten valideren die relevant zijn voor de door jou als gebruiker gestelde
domein-overstijgende vraag. Als gebruiker moet je zelf de linkset daartoe zien
te valideren en zonodig zien te verbeteren.

**Wat karakteriseert deze oplossingsvariant?**

Dit alternatief kan gezien worden als een sleutel, wegwijzer en wegenstructuur
voor het beantwoorden van domein-overstijgende vragen. We karakteriseren dit als
een mogelijke tweede groeistap voor een UOI-code-stelsel.

1.  Geen UOI-code-stelsel

In deze paragraaf wordt een beschrijving gegeven van de situatie waarin er geen
UOI-code-stelsel ontstaat. Dit is namelijk een verbonden ID-code-stelsel dat
geen aparte UOI-code nodig heeft. Het betreft een uitwerking op hoofdlijnen ter
afdekking van het spectrum van oplossingsrichtingen.

In deze variant wordt geen UOI-code-stelsel tot stand gebracht. Met behulp van
andere mechanismes worden de drie principes *identificeren*, *relateren* en
*semantisch interpreteren* ondersteund.

| Registratie van                            | Regime voor |
|--------------------------------------------|-------------|
| Geen registratie                           | Geen regime |
| [./media/image37.PNG](./media/image37.PNG) |             |

Er worden twee varianten binnen dit nul-alternatief onderscheiden:

1.  Gebruik van bestaande identificatiecodes

2.  Gebruik van bestaande ruimtelijke relaties

We beantwoorden voor de genoemde twee varianten de volgende vragen:

-   Welke componenten worden dan als alternatief gebruikt?

-   Hoe werkt het dan?

-   Van welke “stelsel”- werking is dan nog sprake?

-   Wat moet je als gebruiker dan zelf blijven doen?

-   Wat karakteriseert deze oplossingsvariant?

**A. Oplossingsvariant gebruik van bestaande identificatiecodes**

In de variant op basis van bestaande identificatiecodes wordt geen
UOI-codestelsel tot stand gebracht. Met behulp van andere mechanismes worden de
drie principes identificeren, relateren en semantisch interpreteren ondersteund.

**Welke componenten worden dan als alternatief gebruikt?**

Objecten hebben in beginsel een unieke identificatiecode binnen de eigen
domeinregistratie. Die identificatiecode in combinatie met die van de unieke
identificatie van de registratie is daarom altijd herleidbaar tot de gegevens
over een object. Hiermee zijn alle oplossingsrichtingen denkbaar die ook
mogelijk zijn met een UOI-code, maar dan op basis van de bestaande
identificatiecodes en een unieke aanduiding van de betreffende registratie. Voor
dat laatste is een uitgifte- en registratieregime nodig.

**Hoe werkt het dan?**

In plaats van UOI-codes krijgen de bestaande identificatiecodes met behulp van
de registratiecode een soort eigen identificerende ‘namespace’. Deze garandeert
dat de samenstelling van identificatiecode en registratiecode uniek is. Een
register van registratiecodes waarborgt dat de betreffende registratie (en
daarmee een object in deze registratie) vindbaar is. Voor het overige is de
werking gelijk aan oplossingsvarianten op basis van een UOI-code.

**Van welke "stelsel"-werking is dan nog sprake?**

Dit is een verbonden ID-code-stelsel dat geen aparte UOI-code nodig heeft. Er
moet wel zekerheid zijn dat de ID-codes in de domeinregistraties onveranderlijk
blijven bestaan. Verlies van identificatie door wegvallen van de identificerende
code dan wel het object dat met de UOI-code wordt geïdentificeerd, mag niet
voorkomen. Technisch herstel moet natuurlijk wel gefaciliteerd worden.

**Wat moet je als gebruiker dan zelf blijven doen?**

De gebruiker moet zelf zorgdragen voor semantische interpretatie en het leggen
van relaties. Zoals ook beschreven in alternatief ‘Sober UOI-code-stelsel’. zie
3.2.

**Wat karakteriseert deze oplossingsvariant?**

In dit alternatief wordt getracht minimale impact op bestaande registraties te
bereiken. Daardoor kunnen de beoogde voordelen van een UOI-code mogelijk niet
allemaal gerealiseerd worden. In dit alternatief is er geen gecoördineerde regie
op de kwaliteit van de relaties en verwantschappen. In de bestaande
domeinregistratie worden geen verwijzingen naar een UOI-code opgenomen. De
belangrijkste verandering is dat een expliciete verwijzing naar een registratie
wordt toegevoegd aan reeds bestaande relaties. Dus: Koppelpaar \<namespace X\> +
\<Id-code A\> relateert aan \<namespace Y\> + \<Id-code B\>

De ‘logische’ UOI-code wordt hier dus een \<namespace\> + \<Id-code\>.

Als deze toevoeging eerst pas bij de gegevensuitwisseling plaatsvindt, behoeft
de inhoud van bestaande domein-registraties zelf niet te wijzigen. In situaties
met domeingebonden filiatie moet er een aanvullende oplossing voor eeuwigdurende
bereikbaarheid worden gerealiseerd.

**B. Oplossingsvariant ruimtelijke relaties**

In de variant op basis van ruimtelijke relaties worden de relaties niet vooraf
vastgelegd maar bij een domein-overstijgende vraag via ruimtelijke analyse
bijeengezocht. Met behulp van hierna te noemen mechanismes worden de drie
principes identificeren, relateren en semantisch interpreteren ondersteund.

**Welke componenten worden dan als alternatief gebruikt?**

Deze variant gebruikt de component ‘objectrelaties’ voor het registreren van de
uitkomsten van controles. Daar horen ook de componenten regime en daarmee ook
‘governance’ en ‘interfaces’ bij.

**Hoe werkt het dan?**

Geo-objecten hebben een locatie. Net als bij [‘spatial R-tree
indexing’](https://en.wikipedia.org/wiki/R-tree) kun je voor zo'n geometrie een
‘[minimum bounding
box’](https://en.wikipedia.org/wiki/Minimum_bounding_box)[^25] vormen waar de
geometrie van het object precies in past. Vervolgens zoek je alle objecten
waarvan de doorsnede van hun ‘minimum bounding boxes’, al dan niet voorzien van
een buffer, niet leeg is. Geometrisch komt dit neer op het vergelijken van de
kleinste X, grootste X, kleinste Y, grootste Y en kleinste Z, grootste Z van de
geometrieën van objecten. Op deze manier kun je op basis van de geometrie
eenvoudig en snel objecten vinden die mogelijk een fysieke en/of virtuele
ruimtelijke relatie hebben.

[^25]: Zie ook paragraaf ruimtelijke analyse 1.6

Om zeker te weten of deze fysieke en/of virtuele ruimtelijke relatie voldoende
is voor het beantwoorden van de gestelde domein-overstijgende vraag, is
aanvullend onderzoek nodig. Je kunt immers ook objecten vinden, die voor het
beantwoorden van jouw domein-overstijgende vraag niet van belang zijn. Daarnaast
is uit de gevonden ruimtelijke relaties niet op te maken of er ook
administratieve relaties zijn vastgelegd. Dat zul je, als je dat wilt weten,
zelf moet uitzoeken. Je kunt vanuit dit alternatief doorgroeien door de gevonden
relaties vast te leggen en deze verkregen kennis voor hergebruik ter beschikking
te stellen.

**Van welke "stelsel"-werking is dan nog sprake?**

Er is sprake van een zeer losse koppeling tussen registraties, waarbij iedereen
een eigen koers kan blijven varen, maar men elkaar wel helpt door de resultaten
van eigen onderzoek naar relaties te delen. 

**Wat moet je als gebruiker dan zelf blijven doen?**

Gebruikers moeten steeds zelf de ‘minimum bounding boxes’ van geometrieën
vergelijken en de uitkomsten van eerdere controles door anderen verwerken. Dit
levert uitkomsten op die voor sommige toepassingen voldoende betrouwbaar kunnen
zijn. Om zeker te weten of een relatie ook nu nog klopt, moet de gebruiker die
zelf controleren. Zij kunnen anderen weer helpen door de uitkomst van zo'n
controles te registreren.

**Wat karakteriseert deze oplossingsvariant?**

Er wordt alleen geïnvesteerd in de identificatie \<namespace\> + \<Id-code\>.
Dit betekent dat er niet vooraf relaties en verwantschappen worden uitgezocht en
geregistreerd, maar achteraf wordt uitgezocht als er vraag naar is. Een analyse
van ‘minimum bounding boxes’ kan heel snel, maar om zeker te weten, zijn
controles nodig en die kosten tijd en samenwerking. Daar staat tegenover dat er
geen kosten worden gemaakt voor het bijhouden van UOI-gegevens.

Deze methode werkt alleen voor informatie-objecten waarvan de locatie bekend is.
Objecten uit de bouwwereld worden dan pas vindbaar zodra deze geo-gerefereerd
zijn. Wanneer de objecten in bijvoorbeeld een bouwobject in de IFC-structuur
bekend zijn, volstaat het om het bouwobject een locatie te geven om vervolgens
de gerelateerde / samenstellende delen ook te kunnen vinden.