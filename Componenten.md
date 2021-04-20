## Componenten UOI-code-stelsel

In dit hoofdstuk wordt een ontwerp beschrijving gegeven van een mogelijk
UOI-code-stelsel voor de gebouwde omgeving. We beginnen dit hoofdstuk met het
beschrijven van de componenten van een UOI-code-stelsel en werking op
hoofdlijnen. Doel van het UOI-code-stelsel is faciliteren van het
domein-overstijgend kunnen zoeken, vinden en semantisch interpreteren van
object-gegevens.

###  Object & haar verschijningsvormen

De werkelijkheid bestaat. En mensen zien er ‘dingen’ in, die al dan niet fysiek
aanwezig zijn. Deze dingen noemen we ook wel objecten. Een object is dus een
ding in de werkelijkheid. In de informatietechnologie representeren we deze
objecten met informatieobjecten. Het informatieobject is de informatie-eenheid
in de informatiekunde. De term object wordt vaak gebruikt op de plaats waar een
informatie-object wordt bedoeld. Strikt genomen is dat niet correct maar het
verschil is niet altijd van belang. Objecten kunnen worden geclassificeerd in
objecttypen of entiteiten. Een entiteit wordt benoemd met een begrip. Het begrip
omvat de term voor en definitie van de entiteit.

Objecten kunnen we classificeren in groepen of typen objecten. Voor het
UOI-code-stelsel is de volgende opdeling relevant:

**Fysiek object**

In de gebouwde omgeving komen fysieke (materiële, reële) objecten[^20] voor. We
hanteren de onderstaande definitie voor een fysiek object.

[^20]: Zie ook het [verschil tussen ding in de werkelijkheid en registratie
daarvan](https://bp4mc2.org/20181107/#drie-werkelijkheden)

*Een fysiek object is een object, dat bestaat of kan bestaan binnen de fysieke
4D ruimte-tijd. Een fysiek object vormt een manifestatie en een afbakening van
materie en/of energie, en is (in)direct waarneembaar door de zintuigen.*[^21]

[^21]: *Beperkt overgenomen uit NEN 2660-1*

*VOORBEELD Een viaduct, een lichtmast, een pomp, een auto, een muur, een vertrek
als fysieke ruimte.*

*OPMERKING 1 Een zelfde fysiek object kan zowel denkbeeldig bestaan
(conceptueel), bijvoorbeeld op een*

*tekening of in de vorm van een digitaal model, en in de werkelijke wereld
(geconstrueerd en in gebruik). Het betreft hier de verschillende levenscycli
waarin een object kan verkeren.*

*OPMERKING 2 Ook een (levend) organisme is een Fysiek Object, waarmee dus ook
een mens een Fysiek*

*Object is. Automatisch is een organisatie van mensen ook een Fysiek Object. UOI
bekijkt het Fysiek object vanuit het vastgoedperspectief en omvat dus geen
organismen.*

*Een fysiek object in de gebouwde omgeving is een object ‘duurzaam met de aarde
als planeet’ verbonden.*

*Een fysiek object kan zijn samengesteld uit meerdere fysieke objecten via
compositie en decompositie. (Meronomie)(deel-geheel-relaties)*[^22]*.*

[^22]: *In domein-overstijgende vragen is vaak behoefte aan gegevens die via
analyse van dergelijke structuur-relaties te achterhalen zijn. Denk aan in welke
ruimten bevinden zich welke installatie in een gebouw dat uit meerdere
verblijfsobjecten en ruimten bestaat.*

**Virtueel object**

Een virtueel (of immaterieel, niet-reëel)) object wordt gehanteerd om een ruimte
(gebied) bestuurlijk te duiden en te begrenzen. Denk aan een geurcirkel,
werkingsgebied van een juridische regel, of bijvoorbeeld voor registratie van
eigendom, vergunning enz. Deze worden administratief vastgelegd ook omdat deze
gebieden vaak in de werkelijkheid niet zichtbaar zijn.

*Virtuele object*[^23]*: Geo-object waarvan geen tastbaar, zichtbaar en begrensd
fenomeen in de werkelijkheid aanwezig is, maar die slechts in abstracte en/of
geregistreerde vorm bestaat.*

[^23]: *Aangepast overgenomen uit NEN 3610. NEN 3610 spreekt over een virtuele
ruimte. Voor dit document blijven we virtueel object als term aanhouden:*

*Opmerking: Virtuele ruimten zijn abstracte concepten die in registraties kunnen
bestaan, maar in de fysieke werkelijkheid niet uit zichzelf zichtbaar of
zichtbaar begrensd zijn*

*Een virtueel object in de gebouwde omgeving is een aan het fysieke object
gerelateerd object dat de mens gebruikt om de status van een gebeurtenis vanuit
wet- & regelgeving of relevant maatschappelijk verkeer vast te leggen*

**UOI-object**

In sommige alternatieve oplossingen voor het UOI-code-stelsel, zoals die in
hoofdstuk 3 worden beschreven, wordt gebruik gemaakt van een ‘UOI-object’ als
informatie-object. Daarom lichten we dat hier eerst toe.

Voor het UOI-stelsel wordt een denkbeeldig ‘UOI-object’ geïntroduceerd. Het
UOI-object is een informatie-object, bedoeld om als neutraal verbindingselement
tussen informatie-objecten uit verschillende domeinen binnen de gebouwde
omgeving te fungeren. Daarmee worden als het ware informatie-bruggen over de
domeinen gelegd. Neutraal omdat er geen domein-gebonden informatie bij wordt
vastgelegd anders dan de verbindingsgegevens. In de meeste, in hoofdstuk 3
uitgewerkte alternatieven, vertegenwoordigt het neutrale UOI-object daarmee een
informatie-object in een registratie, zonder de gegevens over te nemen.

*Een UOI-object is een domein-verbindend neutraal informatie-object dat
onderkend wordt op de knooppunten van entiteiten in overlappende domeinen*

In onderstaande figuur is een impressie gegeven van deze verbindende werking van
het UOI-object. Let wel het is vooralsnog de bedoeling deze alleen toe te wijzen
wanneer het gaat om entiteiten die relevant zijn voor de verbinding naar andere
domeinen. We noemen dit de knooppunt-entiteiten.

| [./media/image21.png](./media/image21.png)                        |
|-------------------------------------------------------------------|
| Figuur 7: Denklijn: Principe van een UOI-mechanisme als verbinder |

In de bouwwereld worden veel IFC-gebaseerde informatie-modellen gebruikt. In de
wereld van de geo-registraties veel IM-GEO gebaseerde informatiemodellen.

*Wanneer een IM-SOR vanuit het traject Samenhangende Object Registratie
(DIS-GEO) zou ontstaan, kan deze ook via een UOI-object worden verbonden met
andere domeinmodellen.*

###  Componenten van een UOI-code-stelsel

Ons onderzoek heeft het karakter gehad van een iteratief ontwerpproces. Binnen
het UOI-onderzoeksteam zijn zoals gezegd meerdere alternatieven voor een
UOI-code-stelsel in ogenschouw genomen. We onderkennen nu een UOI-code stelsel
dat mogelijk bestaat uit de volgende componenten (los van de gekozen
organisatievorm en aantal aangesloten domeinen):

-   Registratie van

    -   UOI-codes \<UOI-code register\> voor UOI-objecten

    -   UOI-object-relaties

    -   UOI-object-verwantschappen (relaties op modelniveau)

    -   Domein informatie-modellen

    -   UOI-ontologieën

-   Regime voor

    -   Uitgeven van UOI-codes / UOI-object

    -   Registreren van UOI-object-relaties

    -   Registreren van UOI-object-verwantschappen

-   Governance UOI-stelstel

-   Interface met UOI-code stelsel (API Application Program Interface / Endpoint
    enz.)

| [./media/image22.png](./media/image22.png)               |
|----------------------------------------------------------|
| Figuur 8: Mogelijke componenten van het UOI-code stelsel |

Het vinden van gegevens over objecten uit de gebouwde omgeving veronderstelt
twee zaken:

1.  Uniek kunnen identificeren van een object in de gebouwde omgeving

2.  Met zekerheid kunnen vinden van aan het object gerelateerde gegevens

Dit inzicht heeft ons als onderzoekers er toe aangezet ook het gebruik van de
UOI-code in de praktijk op hoofdlijnen te onderzoeken en te beschrijven.

### Werking op hoofdlijnen – UOI-code-stelsel

We pakken de denklijn van de doelenboom weer op om de werking van een
UOI-code-stelsel toe te lichten. We doen dat aan de hand van de drie principes
identificeren, relateren en semantisch interpreteren. We pakken de
domein-overstijgende zoekvraag als vertrekpunt voor deze werking op hoofdlijnen.
Opgemerkt wordt dat de beschikbaarheid van het UOI-code-registraties hierbij
wordt verondersteld. Hoe deze tot stand zijn gekomen wordt niet hier maar elders
beschreven.

**Identificeren**

UOI-objecten zijn met behulp van de UOI-code uniek geïdentificeerd. Bij het
stellen van een domein-overstijgende vraag begint naar verwachting in het
bekende domein. Gezocht wordt naar een willekeurig domeinobject, dat onder het
UOI-uitgifte regime als UOI-object \<lees informatieobject\> werd gezien en wat
dus een UOI-code heeft toegewezen gekregen. In de domein registratie is deze
UOI-code opgenomen als attribuut bij het bewuste domeinobject. De gekozen
zoeksleutel in de domeinregistratie bepaalt welke domeinobjecten gevonden
worden. Via de gevonden UOI-code kunnen nu andere registraties in andere
domeinen bevraagd worden. De verzameling gevonden UOI-codes vormen de
verbindende identificatoren. We noemen deze verzameling de subset. Over deze
verzameling objecten zoeken we nu een domein-overstijgend antwoord.

**Relateren**

We gaan nu eerst op zoek naar de UOI-objecten uit de subset die in de
UOI-object-relatie-registratie zijn opgenomen. Aldaar vinden we de UOI-codes die
een relatie hebben op instantie niveau met de UOI-codes uit de subset. We noemen
de gevonden UOI-code met een relatie de doelset.

**Semantisch interpreteren**

We gaan aansluitend op zoek naar de domeinen van deze UOI-codes uit de doelset.
Die vinden we door in het UOI-code register de desbetreffende UOI-codes op te
zoeken en te aldaar de domeinentiteit en domeinnaam op te halen. In het UOI-code
register ligt vast bij de UOI-code welk UOI-object (domeinentiteit) uit welk
domein het betreft. Met deze kennis kunnen we voor de gevonden domeinen de
domein informatiemodellen en verwantschappen opvragen. Daarmee kunnen we de
gevonden gegevens ook semantisch interpreteren.

**Informatiebruggen gelegd**

De informatiebruggen zijn in meerdere stappen gelegd:

-   Identificeren UOI-objecten in de zoekvraag \<subset UOI-codes\>

-   Zoeken naar UOI-objecten in de UOI-object-relatieregistratie \<doelset
    UOI-codes met relaties\>

-   Bevragen UOI-code register met doelset UOI-codes om relevante
    domeinregistraties te leren kennen \<in het UOI-code register ligt vast bij
    de UOI-code welk UOI-object uit welk domein het betreft\>

-   Voor de relevante domeinen uit de doelset de domein-informatiemodellen
    opvragen

-   Voor de relevante domeinen uit de doelset de verwantschappen opvragen

**Manieren om te relateren**

Er zijn overigens meerdere manieren om te relateren op instantieniveau. Denk aan
de volgende manieren:

-   Met de hand leggen door experts (bij uitgifte, verandering, conversie)

-   Via ruimtelijke analyse

-   Door toepassen van set van relaterende mechanismes.

Het resultaat is dan een linkset, dan wel in de dataset vastgelegde relaties.

**Voorbeeld**

We geven een voorbeeld. Een CV-installatie wordt door een installatiebedrijf
voor een nieuw te realiseren bouwwerk X ontworpen. De ontwerper vraagt na het
ontwerp een UOI-code voor deze installatie (als geheel) aan. Aan dit
informatieobject (de CV-installatie) wordt een (gegenereerde/uitgegeven)
UOI-code gekoppeld. De ontwerper van bouwwerk X heeft direct na het 1e ontwerp
van het bouwwerk de moeite genomen om een UOI-code voor het ontwerp van bouwwerk
X aan te vragen en deze verkregen. De CV-installatie-ontwerper kon het bouwwerk
X ook vinden en heeft deze dus direct aan het hoogste abstractieniveau van het
bouwwerk X gekoppeld. Eerst bij plaatsen van de CV-installatie worden de
onderdelen in een dergelijke situatie aan de ruimtes gekoppeld waar zijn echt
zijn geplaatst. Dat veronderstelt een handeling door de installateur. D
registratie van de relaties ontstaat immers niet van zelf. Ofwel worden de
ruimtelijke ontwerpgegevens gebruikt om de koppeling aan ruimten/muren te
realiseren dan wel de installateur verzorgt deze detaillering van relaties.

### UOI-code en uitgifte regime

*We beginnen met de UOI-code, de uitgifte & regime van uitgifte.*

We beantwoorden vragen zoals:

-   Wat is een UOI-code?

-   Wat is de relatie met een lokale ID?

-   Wat lost een UOI-code op?

-   Hoe worden UOI-codes uitgegeven?

-   Wat is een UOI-code-uitgifte regime?

-   Waarom is een uitgifteregime nodig?

-   Hoe ziet een UOI-code eruit?

*Identificatie is een manier om een sleutel te verkrijgen waarmee objecten te
vinden zijn.*

UOI-codes zijn identificaties van objecten binnen het UOI-code-stelsel die
eenduidig een UOI-object identificeren (een UOI-code wordt slechts één keer
uitgegeven). Hoe deze code eruitziet hangt af van het gekozen stelsel, maar
meestal gaat het om een reeks tekens zoals bijvoorbeeld een UUID of een URI.

Het UOI-code-stelsel beoogt objecten uit domein-registraties te verbinden.
Registraties waarin de objecten al bestaan en waarin het object binnen die
domein-registraties al een unieke identificatie heeft. Deze lokale identificatie
hoeft echter niet uniek te zijn binnen de gehele gebouwde omgeving. Afhankelijk
van hoe de UOI-codes worden uitgegeven, is het mogelijk om een lokale
identificatie op te nemen in de UOI-code. Daarmee bevat de UOI-code van een
BAG-object dus de BAG-ID en de UOI-code van een BT-object de BGT-ID enz.

Het voordeel van een UOI-code boven een lokale identificatie is dat een UOI-code
gegarandeerd uniek is binnen het hele UOI-code stelsel terwijl een lokale code
(domein-specifiek) dat niet altijd is.

Er zijn mengvormen denkbaar bij de feitelijke uitgifte/generatie van UOI-code.
Zo is het denkbaar dat deze centraal gegeneerd worden (je vraagt en krijgt een
UOI-code) maar het is ook denkbaar dat een federatief stelsel ontstaat waarin
meerdere actoren binnen het regime zelf een UOI-code kunnen genereren en
uitgeven. Het regime waarborgt in dat geval de uniekheid van de UOI-code. Een
tussenvorm daarbij is dat centraal reeksen worden gegenereerd, die daarna door
partijen binnen de federatie stuk voor stuk aan één informatie-object worden
uitgegeven.

| [./media/image23.png](./media/image23.png)                |
|-----------------------------------------------------------|
| Figuur 9. Middelen UOI-code en UOI-code-uitgifte & regime |

**Hoe ziet een UOI-code eruit?**

We hebben in het onderzoek een reeks mogelijkheden onderkend waarmee de UOI-code
kan worden vormgegeven. We hebben daar 1:1 de eisen zoals geformuleerd in de NEN
3610 en ook in de SOR overgenomen. Deze zijn in [bijlage
3](#_Identificatie_van_objecten) (bron Programma van Eisen SOR) nader
beschreven.

Een UOI-code kan bijvoorbeeld de vorm van een UUID, GUID of een URI aannemen. Ze
is betekenisloos, uniek en persistent. 68% van de respondenten op de
SOR-consultatie van eind 2020 geeft aan met een dergelijke identificator in te
kunnen stemmen, mits in de domeinregistratie aanvullende mensleesbare kenmerken
zijn vastgelegd. Of te wel als het maar een unieke identificeerde code is. Een
voorloopcode NL- lijkt handig omdat daarmee nadere duiding wordt ingebakken die
handig is bij het achterhalen van wegen tot vinden van nadere informatie.

**Uitgifte van UOI-codes**

Het woord uitgifte van UOI-codes suggereert voor menigeen een loket waar je een
UOI-code kan verkrijgen. Toch is ook een federatief stelsel denk baar waarbij
domeinen zelf de UOI-code verstrekken, dan wel dat de UOI-code door de manier
van opbouw \<namespace\>\<ID\> intrinsiek altijd uniek is. Waar het omgaat is
dat de uniciteit en persistentie van de UOI-code geborgd is en gegarandeerd kan
blijven worden.

Het is van belang dat de bekend is waar gegevens over het object, dat wordt
geïdentificeerd met de UOI-code, gevonden kan worden. Dat wordt ofwel in een
UOI-code-register vastgelegd, dan wel is via een \<namespace\> constructie en
een \<namespace\>register afgedekt.

Omdat zaken zoals tijdvolgordelijkheid van informatie-objecten (zoals bekend uit
filiatie) door de domeinen worden bepaald, is het zaak een
uitgifte/generatie-regime voor UOI-codes te hanteren dat de “eeuwigdurendheid”
van het informatie-object op UOI-stelselniveau garandeert.

**Knooppunt-entiteiten**

In dit onderzoek gaan we uit van het toekennen van een UOI-code minimaal en
mogelijk ook maximaal aan de zogeheten knooppunt-entiteiten in de aangesloten
domeinregistraties. Alleen in variant 1 (zie hoofdstuk 3.2) wordt deze logica
los gelaten, omdat in die variant de knooppunt-entiteiten (als onderdeel van de
verwantschaps-ontologie) nog onbekend zijn.

*Een knooppunt-entiteit is voor ons een entiteit die een relatie heeft op
modelniveau met een andere knooppunt-entiteit van een ander
domein-informatiemodel. Er kunnen in een domein-informatiemodel meerdere
knooppunt-entiteiten voorkomen.*

*(Vooralsnog streven we ernaar alleen UOI-codes uit te geven voor objecten die
op de zogeheten knooppunten qua verwantschappen liggen)*

In de onderstaande figuur zijn mogelijke knooppunt-entiteiten voor een achttal
domeinen symbolisch met een gestippelde ellips gemarkeerd. De lijnen
symboliseren de verwantschappen tussen de knooppunt-entiteiten. Let wel. Deze
verwantschappen kunnen exact maar ook indicatief van aard zijn.

| [./media/image24.png](./media/image24.png)                      |
|-----------------------------------------------------------------|
| Figuur 10. Logica van de knooppunt entiteiten & verwantschappen |

Het model in bovenstaande is uitdrukkelijk indicatief en illustratief en niet
gevalideerd of compleet gemaakt. In de casus-onderzoeken die parallel
plaatsvinden gaan we het gebruik van deze verwantschapsmodellen toetsen. Lees
meer daarover in hoofdstuk 4.

**Bouwsteen: Regime uitgifte UOI-code**

Door via een regime van uitgifte van UOI-codes bij het ontstaan van een
informatieobject een UOI-code aan dat informatie-object toe te kennen, blijft de
unieke identificatie bestaan en kan de UOI-code als zoeksleutel werken. Het
object is nu uniek persistent digitaal identificeerbaar, zelfs als het logische
in Nederland gehanteerde adres in een adresregistratie zoals de BAG zou
veranderen. Het object kan uit meerdere sub-objecten bestaan, of deel uit maken
van een super-object.

**Bouwsteen: UOI-code-register**

Er is mogelijk een UOI-code-register nodig waarin de uitgegeven UOI-codes, met
gegevens over de uitgifte en identificatie, duurzaam beschikbaar zijn en
blijven. Dit is dus afhankelijk van de gekozen oplossing voor de UOI-code.


### Relaties & regime UOI-objecten

We vervolgen met UOI-Object-relaties & het regime om deze relaties tussen
UOI-objecten onderling vast te leggen dan wel achterhaald kunnen worden.

We beantwoorden vragen zoals:

-   Wat zijn objectrelaties

-   Hoe kan je objectrelaties leggen (bijv linksets)

-   Wie kunnen objectrelaties leggen

-   Wat is de kwaliteit van objectrelaties

-   Wat als objectrelaties veranderen?

-   Wat als een object verandert? (Bij de bron) (temporele aspecten)

Er is sprake van een objectrelatie als de identificatiecode van een
informatieobject expliciet in verband is gebracht met de identificatiecode van
een ander object, al dan niet via een UOI-code. Het mag gaan om objecten in
dezelfde registratie, maar ook om objecten in andere registraties. Voor het
vastleggen van zo'n objectrelatie registreert het verwijzende object de
identificatiecode van het andere object bij de eigen objectgegevens. Alternatief
kan er sprake zijn van een koppeltabel (of linkset) met relaties tussen
identificatiecodes van objecten. Het bijhouden van zo'n koppeltabel staat los
van die van de objecten.

Als de objectrelatie deel uitmaakt van de gegevens van het verwijzende object,
maakt het bijhouden van de relatie deel uit van het reguliere bijhouden van het
object en daarmee ook van de historie en het kwaliteitsregime. De bronhouder van
het verwijzende object bepaalt aan de hand van regels welke objecten een relatie
hebben met het object en houdt deze relaties bij door nieuwe toe te voegen,
gewijzigde en foutieve te corrigeren en achterhaalde op te ruimen**.** Soms zijn
zulke verwijzingen echter niet gewenst, bijvoorbeeld als een registratie geen
verantwoordelijkheid kan dragen voor verwijzingen naar objecten buiten de eigen
registratie.

het bijhouden van een koppeltabel staat los van die van de gerelateerde
objecten. De maker van zo'n koppeltabel hoeft dus niets met het bijhouden van de
objecten van doen te hebben**.** Dit kan een bronhouder van objecten zijn, een
gebruiker of een willekeurige andere partij. Iedereen kan dus een koppeltabel
beschikbaar stellen, ook voor UOI-codes. Dit houdt ook in dat de maker van een
koppeltabel zelf beslist over het leggen van relaties, over het actualiseren van
die relaties en over het bijhouden van historie. Een nieuwe versie komt er
misschien naar aanleiding van een objectwijziging, periodiek, incidenteel of
nooit. En als er historie beschikbaar is, kan dat bestaan uit eerdere, separate
versies van de koppeltabel of uit bijvoorbeeld het integreren van gedetailleerde
levenscycli inclusief filiatie.

Als het bijhouden van een koppeltabel niet is verweven met het bijhouden van
objecten, beschikt de maker van de koppeltabel niet over dezelfde
inwininformatie als de bronhouder van een gekoppeld object. Die informatie
alsnog inwinnen is kostbaar en dat zou ervoor pleiten om de objectrelatie alsnog
bij te houden bij het verwijzende object. Koppeltabellen bestaan dus vooral
wanneer het (nog) niet loont of om andere redenen niet gewenst is om relaties
individueel in te winnen en bij te houden. Het maken van een koppeltabel komt
dus neer op het interpreteren van modellen en gegevens van objecten, al dan niet
geautomatiseerd. Ook dit gebeurt aan de hand van regels.

Een koppeltabel kan vaak een juiste uitkomst opleveren, maar niet altijd bieden
gegevens die voor een ander doel zijn vastgelegd, genoeg inzicht in de
werkelijkheid om een juiste koppeling te garanderen. Ook kan er van alles
veranderen in de werkelijkheid zonder dat dat zichtbaar wordt in de gegevens van
objecten, zoals het doorbreken van een muur tussen twee panden zonder
verblijfsobjecten. Of misschien hebben de objecten die worden gekoppeld, niet
allemaal dezelfde peildatum. De kwaliteit van een koppeltabel is zo vaak lager
dan wanneer de objecten zelf naar gerelateerde objecten verwijzen. Regels missen
sommige relaties die in de werkelijkheid wel of leggen relaties die in de
werkelijkheid niet bestaan. En hoe bruikbaar is een koppeltabel die minder vaak
wordt bijgehouden dan de objecten waarnaar deze verwijst? Gebruikers van een
koppeltabel moeten daarom toetsen of deze gebruikt kan en mag worden voor het
beoogde doel.

Voor een goed werkende UOI-code is het essentieel dat deze gevrijwaard blijft
van bovengenoemde haken en ogen. Er is daarom een regime nodig dat zorgt voor
het leggen en bijhouden van relaties tussen objecten en zo de kwaliteit
waarborgt.

| [./media/image25.png](./media/image25.png)      |
|-------------------------------------------------|
| Figuur 11. Middelen UOI-code relaties en regime |

**Bouwsteen: Registratie UOI-object-relaties**

Om de feitelijke objectrelaties op instantieniveau te kennen, moeten deze
objectrelaties worden achterhaald of vastgelegd. Deze objectrelaties ontstaan of
veranderen bij het ontstaan of veranderen van het object, maar ook wanneer de
verwantschappen ontstaan of veranderen. Het vastleggen of achterhalen van de
UOI-relaties wordt gedaan voor de, op de knooppunten (lees entiteiten) van
overlappende ontologieën.

**Bouwsteen: Regime UOI-relaties**

Een regime van registratie van UOI-relaties draagt zorg voor het vastleggen van
de UOI-relaties bij het ontstaan of veranderen van een object of nieuw
gerelateerd object. Dit dient op instantieniveau te gebeuren.

### Verwantschappen & regime UOI-object

We vervolgen met de wijze waarop UOI-object verwantschappen worden vastgelegd en
welk regime daartoe wordt voorgesteld.

**Bouwsteen: Registratie verwantschappen UOI-object**

*Om de semantische samenhang te kennen dienen de verwantschap van begrippen en
definities tussen de entiteiten in de domein-informatiemodellen eveneens
bereikbaar te zijn. Die worden vastgelegd in zogeheten verwantschapsrelaties op
modelniveau. Dit gebeurt bijvoorbeeld in een kennisgraaf.*

**Bouwsteen: Regime Verwantschappen UOI-object**

*Een regime van registratie van UOI-verwantschappen draagt zorg voor het
vastleggen van de UOI-verwantschappen bij het ontstaan of veranderen van een
entiteit in een domeininformatiemodel dat de rol van knooppunt qua
UOI-verwantschap vervult. Dit dient op modelniveau te gebeuren.*

Verwantschappen zijn relaties tussen entiteiten uit verschillende modellen. Het
zijn relaties op modelniveau waarbij nog niet is bepaald of ze ook op
instantieniveau geregistreerd zullen worden. Om geen verwarring te krijgen met
relaties binnen modellen en op instantieniveau spreken we van
verwantschappen[^24]

[^24]: (affiliates)

We beantwoorden achtereenvolgens de volgende vragen:

-   Wat zijn verwantschappen?

-   Hoe gaan we om met verwantschappen in en over domeinen?

-   Hoe past het domein informatiemodel in verwantschappen?

-   Hoe passen objecttypebibliotheken in verwantschappen? (deeldefinitie van een
    informatiemodel: een ontologie)

-   Wat doen we met deze kennis over verwantschappen?

-   Welke winst biedt gedeelde toegang tot verwantschappen?

| [./media/image26.png](./media/image26.png)             |
|--------------------------------------------------------|
| Figuur 12. Middelen UOI-code verwantschappen en regime |

*De Verwantschap-laag is een domein-onafhankelijke ontologie.*

In de doel-middel hiërarchie bevindt zich een verwantschaps-ontologie. In deze
laag zijn de relaties tussen de entiteiten opgenomen tussen de verschillende
domeinmodellen die allemaal relevant zijn voor het koppelen van gegevens ten
behoeve van de gebouwde omgeving. Deze relaties zijn in de regel niet binnen de
domein-modellen beschreven. De verwantschappen in de verwantschaps-ontologie
vormen de semantische koppelvlakken tussen domeinmodellen.

*Een verwantschaps-ontologie is een domein overstijgende ontologie.*

**Leggen van verwantschappen**

Verwantschappen (relaties tussen entiteiten in modellen) kunnen worden
vastgelegd door deze “relaties” met behulp van verwantschapsoperatoren te
definiëren. Denk aan Bouwobject ”komt-overeen-met” BAG-object. De gangbare set
van verwantschapsoperatoren is opgenomen in bijlage 7. Hoe dit precies moet is
nu nog niet bepaald. Tegelijk is er een manier ontwikkeld om dergelijke
verwantschappen te definiëren

Deze verwantschappen zijn op meerdere manieren met hulpmiddelen te achterhalen:

-   via ontology matching (<http://www.ontologymatching.org/>)

-   via typering als topologische relaties

-   via typering als nieuwe domein overstijgende inhoudelijke relatie

-   via typering als de(compositie) relatie (deel/geheel)

-   handmatig m.b.v. domeinexperts.

Bij al deze “relaties” kan aangegeven worden hoe sterk of zwak de relatie is.
Dergelijke verwantschappen worden vaak in een kennisgraaf vastgelegd. Daarbij
worden verwantschap-operatoren gebruikt. Zie bijlage 7.

| *Wat is een kennisgraaf?*  *De kennisgraaf vertegenwoordigt een verzameling onderling verbonden beschrijvingen van entiteiten - objecten, gebeurtenissen of concepten. Een kennisgraaf bevat een model (ontologie) en de instanties, het creëert een netwerk (graaf) aan verbonden data, die gevisualiseerd kan worden, doorzoekbaar is, en daarmee ook ideaal is voor data analyse.* [Zie ook deze link](https://www.ontotext.com/knowledgehub/fundamentals/what-is-a-knowledge-graph/#:~:text=The%20knowledge%20graph%20represents%20a,%2C%20unification%2C%20analytics%20and%20sharing.) *Lees meer in bijlage 4* |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|


In ons denken worden deze verwantschapsrelaties worden formeel
geregistreerd/gepubliceerd in een ontologie: ‘verwantschappen gebouwde
omgeving’. Deze ontologie van verwantschappen is als een domein-overstijgende
ontologie te beschouwen van de gebouwde omgeving.

Met deze ontologie zijn een aantal doelen te ondersteunen:

-   Visualisatie van de relaties tussen domeinmodellen;

-   Definitie van relaties tussen koppelentiteiten van domeinmodellen;

-   Registratie van koppelentiteiten

-   Creatie van een geregistreerde kennisgraaf ‘gebouwde omgeving’:

-   Realisatie van de relaties daadwerkelijk op instantieniveau.

    -   Dit kan ‘handmatig’ maar ook door het automatische genereren van
        linksets d.m.v. redeneren op basis van combinatie van ruimtelijke en
        semantische verwantschapsregels.

    -   De relaties kunnen ook gebruikt worden voor de creatie van ‘on the fly’
        relaties door d.m.v. redeneren gebaseerd op ruimtelijke en semantische
        verwantschapsregels.

-   Registratie van deze gevonden relaties

De totstandkoming van de verwantschap-laag is een samenwerkingsproces waarbij
domeindeskundigheid en informatiekunde bij elkaar komen. Van belang is dat de
domeinmodellen (ontologieën) en vocabulaires (begrippen) beschikbaar zijn. De
OTL-ontologie (object type bibliotheek) valt ook hieronder.

### Formaliseren van UOI-object verwantschappen & relaties

We beantwoorden achtereenvolgens de volgende vragen:

-   Waarom een formeel UOI-code-stelsel?

-   Hoe werken de drie middelen/principes onderling samen?

-   Wat is de meerwaarde van een formeel UOI-code-stelsel?

-   Wat is de winst van gedeelde toegang tot formele UOI-code-stelsel-data?

**Waarom een formeel UOI-code-stelsel?**

In de voorgaande paragrafen zijn de principes identificeren, relateren en
verwantschappen ten behoeve van semantisch interpreteren, als componenten voor
het domein-overstijgend kunnen beantwoorden van vragen over objecten in de
gebouwde omgeving behandeld. Genoemde principes kunnen in een UOI-code-stelsel
in meer of mindere mate expliciet deel uit maken van dat UOI-code-stelsel.

Wanneer een UOI-code-stelsel alleen het principe van identificeren omvat moet
met andere middelen het relateren en semantisch interpreteren worden bereikt om
domein-overstijgende vragen te beantwoorden. Wanneer gebruik gemaakt wordt van
methoden en technieken zoals linked data en resolvers (mapping van domeinen via
ID’s) zijn er ook wegen te vinden om domein-overstijgende vragen te
beantwoorden. Ook zonder een UOI-code kan dat, zij het dat wanneer het aantal
domeinen dat meegenomen moet worden in de het beantwoorden van
domein-overstijgende vragen groeit, deze wegen complexer worden, mede doordat de
reikwijdte qua objecten varieert.

Dit geeft voeding aan een idee om de UOI-objectrelaties en verwantschappen te
formaliseren zodat er een zeer hoge garantie bestaat op het kunnen beantwoorden
van domein-overstijgende vragen.

| [./media/image27.png](./media/image27.png)            |
|-------------------------------------------------------|
| Figuur 13. Middelen UOI-code formeel UOI-code-stelsel |

**Hoe werken de drie middelen/principes onderling samen?**

In de bovenstaande figuur zijn daartoe in de doelenboom twee paarse blokken
toegevoegd die de extra benodigde componenten in een dergelijk formeel
UOI-code-stelsel duiden. Het regime verwantschap leggen, moet borgen dat zodra
een domein wordt aangesloten ook het aantal knooppunten qua entiteiten wordt
uitgebreid en dat tevens alle verbindingen met al aangesloten domeinen in kaart
gebracht worden en verwantschappen formeel worden gepubliceerd. Ook wordt de
toegang tot de ontologieën uit dat nieuw aangesloten domein toegevoegd. Voor te
onderkennen UOI-objecten worden daarna UOI-codes uitgegeven. Ook wordt een
regime voor UOI-object relaties in werking gezet. Dat beoogt te garanderen dat
de relaties van UOI-objecten vastgelegd worden ten behoeve van het
domein-overstijgend zoeken en vinden.

**Wat is de meerwaarde van een formeel UOI-code-stelsel?**

De beoogde meerwaarde van een formeel UOI-code-stelsel is dat een zeer hoge
garantie op het beantwoorden van domein-overstijgende vragen wordt bereikt. Alle
zoekwegen liggen klaar voor domein-overstijgende vragen. Nader onderzoek moet
uitwijzen welke spelregels deze regimes dienen te bevatten en of het direct
vastleggen meerwaarde heeft ten opzichte van het achteraf of “on-the-fly”
reconstrueren van deze relaties.

**Wat is de winst van gedeelde toegang tot de data in een formeel
UOI-code-stelsel?**

Het feit dat beide regimes (verwantschappen en relaties) een uniforme werking
hebben voor alle domeinen zal de kans op verschillende uitkomsten op
domein-overstijgende vragen door verschillende algoritmes naar verwachting
aanzienlijk verkleinen. Ook wordt de totale som van investeringen tot
faciliteren van beantwoorden van domein-overstijgende vragen in de maatschappij
door samenwerking in één infrastructuur naar verwachting sterk ingeperkt. Een
mKBA zal hiertoe een onderbouwing moeten kunnen bieden.

### Faciliteren leggen van UOI-object verwantschappen & relaties

Deze paragraaf beschrijft het proces voor de realisatie van de
verwantschap-laag. De volgende twee punten uit de doel-middel hiërarchie zijn
van belang:

**Bouwsteen: Registratie Domein-informatiemodellen**

Om de semantische definitie van begrippen en hun samenhang in het domein te
kennen dienen de domein-informatiemodellen bereikbaar te zijn.

**Bouwsteen: Registratie ontologie domein-overstijgend**

Er bestaan vaak vele objecten die vanuit een bepaald gezichtspunt gegevens
vastleggen over het object of over onderdelen in het object. Het object kan ook
op één of meerdere sub-objecten of een super-object betrekking hebben. Het is
dus nodig de relaties tussen het object (sub/super) en het object (sub/super) te
kennen om gegevens éénduidig te kunnen vinden. Veel van deze relaties zijn vaak
geheel of gedeeltelijk in een domeinregistraties vastgelegd. Welke van belang
zijn wordt vaak in een ontologie vastgelegd. Daarom dienen voor het gegarandeerd
vinden van domein-overstijgende gegevens deze domein-overstijgende ontologie
bereikbaar te zijn. Het toepassen van de FAIR-principes daarbij lijkt ook
noodzakelijk.

**Delen van semantiek.**

De verwantschap laag brengt de gedeelde semantiek van de verschillende domeinen
in beeld en formaliseert deze. In feite gaat het nog los van modellen over het
delen van begrippen en leggen van verwantschapsrelaties. De verwantschappen
worden gelegd tussen de eerdergenoemde koppel-entiteiten. Er kunnen meerdere
typen verwantschapsrelaties zijn.

| *Informatiemodel en ontologie worden in deze notitie gelijk geschakeld. Strikt genomen kan het verschil worden gemaakt, maar dat is niet van belang voor deze notitie.* |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|


Het kan gaan over semantische relaties die aangeven dat een begrip synoniem is,
of equivalent, of ‘inhoudelijk gerelateerd is aan’. Maar het kan ook gaan over
ruimtelijke relaties: ‘*bevindt zich in’*; of het gaat over meronomische
relaties: ‘*is een deel van’*. Daarnaast kunnen er nog andere
verwantschapsrelaties een rol spelen die nu nog niet zijn benoemd. Het is van
belang om het vocabulaire van de typen verwantschapsrelaties te ontwikkelen. Dit
heeft het karakter van een collectief proces gestuurd door domeinexpertise en de
behoefte tot beantwoorden van domein overstijgende vragen.

**Domeinen en domeinexpertise.**

Om de begrippen en modellen van de domeinen met elkaar te verbinden is toegang
nodig tot de begrippenkaders, ontologieën, informatiemodellen en domeinmodellen.
Voor deze notitie maken we geen onderscheid tussen een (informatie)model en een
ontologie. Waar het om gaat is dat de aanwezige semantiek beschikbaar is op
basis waarvan de verwantschap laag kan worden ontwikkeld. In de ‘linked data
omgeving’ van het Kadaster en het [linked dataonderzoeks platform
PLDN](https://www.pldn.nl/wiki/Platform_Linked_Data_Nederland) is hier ervaring
mee.

Het vakgebied van **ontology-matching** kan hieraan bijdragen. In samenwerking
met de stakeholders en deskundigheid van de domeinen kan een verwantschap laag
worden ontwikkeld en geformaliseerd. De verwantschap laag zelf is weer een eigen
ontologie. Deze verwantschapsontologie beschrijft de relaties op entiteitniveau
en alleen voor de koppel-entiteiten. De instantiering daarvan in daadwerkelijke
relaties tussen informatie-objecten is een optioneel volgende stap.

**Beheer en ontwikkeling.**

De verwantschapsontologie dient bij voorkeur te worden geformaliseerd om ze te
kunnen gebruiken voor het ontsluiten en bevragen van aan elkaar gerelateerde
objecten. De verwantschapsontologie is niet statisch en zal bij voorkeur (er is
immers regie nodig) in beheer genomen moeten worden om te kunnen beantwoorden
aan veranderende domeinmodellen en begrippen en ook nieuwe eisen voor
verwantschapsrelaties.

### Digitale toegang tot de UOI-object-registraties

We beantwoorden achtereenvolgens de volgende vragen:

-   Hoe kan je als gebruiker digitale toegang verkrijgen tot UOI-registraties?

-   Welk karakter hebben deze UOI-registraties?

Het gaat om de functionele toegang (overeenkomstig de principes van Tim Berners
Lee) tot de onderstaande vijf bij het UOI-code stelsel mogelijk betrokken
registraties:

-   Registraties van

    -   UOI-codes \<UOI-code-register\> voor UOI-objecten

    -   UOI-object-relaties

    -   UOI-object-verwantschappen

    -   Domein informatie-modellen

    -   UOI-ontologieën (domeinoverstijgend)

Een UOI-code is een identificator voor een ding. De ontwerpprincipes voor hoe om
te gaan met identificator voor een ding, om zo maximaal mogelijk
herbruikbaarheid te garanderen en de kracht van het World Wide Web optimaal te
benutten zijn door sir Tim Berners-Lee vastgesteld. [Dat is na te lezen op deze
link](https://www.w3.org/DesignIssues/LinkedData.html). Hij propageert het
gebruik van een URI: Unique Resource Indentifier.

1.  *Gebruik URI’s bij de naamgeving van dingen*

2.  *Gebruik HTTP URI’s zodat mensen deze namen kunnen raadplegen.*

3.  *Wanneer iemand een URI raadpleegt, verstrek dan bruikbare informatie door
    standaarden te benutten*

4.  *Neem verwijzingen naar andere URI’s op, zodat de raadplegers meer
    informatie & zaken kunnen ontdekken.*

De basis eisen voor een URI zijn dat het uniek moet zijn op het web en naar een
weblocatie moet leiden (‘*resolved on the web’*) en dat deze bron voor mens &
machine bruikbare informatie moet opleveren. Dat betekent dat er naast een
machine leesbare inhoud, ook een HTML-representatie moet zijn. Voor de
implementatie betekent dat ‘content-negotiation’ (een onderhandelingsmechanisme
tussen de browser en de met de URI aangeduide bron) gewenst is.

De vindbaarheid van objecten kent verschillende aspecten:

**Vindbaarheid op object-niveau**

Wanneer binnen het stelsel van UOI-codes objecten naar elkaar gaan verwijzen is
een service die, gegeven een UOI-code, de vindplaats van dit UOI-object
retourneert wenselijk. Hiervoor zijn verschillende oplossingsrichtingen
mogelijk:

-   Een centrale service (mogelijk ook federatief geïmplementeerd) die gegeven
    een UOI-code de vindplaats van informatie over het OBJECT retourneert. Dit
    kan bijvoorbeeld doordat een ‘oogst-service’ de bij deze service aangemelde
    bronnen frequent bevraagt en veranderingen oogst op het Internet
    (harvesting) of op basis van de UOI-code een service kan ‘zien’ wat de
    vindplaats van het object is.

-   In linked-data toepassingen is de identificator ook meteen de plek waar het
    object gevonden kan worden (URL) en is zo’n service overbodig.

-   In een minimaal UOI stelsel wordt alleen de uniciteit van een UOI-code
    gewaarborgd en is het aan de gebruiker van de gegevens om de registratie te
    vinden waarin het UOI-object zich bevindt.

Wanneer de registratie waarin het object zich bevindt eenmaal gevonden is, moet
de informatie over het object ook nog uit de registratie gehaald worden. Hierin
zijn weer verschillende gradaties van ondersteuning te onderkennen variërend
van:

1.  totaal geen ondersteuning waar de gebruiker van de gegevens zelf maar moet
    uitzoeken hoe de gegevens opgehaald worden tot

2.  een volledige linked-data oplossing waar deze het protocol waarmee de
    gegevens opgehaald kunnen worden volledig vastligt.

**Vindbaarheid op modelniveau**

Niet alleen de UOI-informatie-objecten moeten vindbaar zijn; ook de betekenis
van die objecten, uitgedrukt in het model waaraan de gegevens voldoen moet
vindbaar zijn. Deze modelinformatie kan ook gebruikt worden voor het beschrijven
van de verwantschaps-ontologie tussen klasses van objecten. Ook hier zijn weer
verschillende gradaties van ondersteuning te onderscheiden; beginnend bij (1)
het aanbieden van de modelomschrijvingen van datasets op mens-leesbare manier
tot (2) een linked-data oplossing waarbij het model (of ontologie) waaraan een
object voldoet volgens een voorgeschreven (machine leesbare) standaard
beschreven is. In dit laatste geval zijn de modellen ook data geworden en is een
model een bevraagbare bron geworden.

**Vindbaarheid op dataset niveau**

Het kan zijn dat het UOI-code-stelsel gaat bestaan uit een collectie datasets
die voldoen aan de specificaties van de UOI-code. Om deze datasets vindbaar te
maken kan binnen het UOI-code-stelsel een register ingericht worden waarin
aanbieders van gegevens binnen het UOI-code-stelsel hun dataset kunnen
aanmelden. Door het toekennen van vindbaarheidsmetadata worden datasets
vindbaar. Voorbeelden hiervan zijn bijvoorbeeld het nationaal georegister voor
geodata

( <https://www.nationaalgeoregister.nl/geonetwork/srv/dut/catalog.search#/home>
) of het dataregister van de Nederlandse overheid ( <https://data.overheid.nl/>
).

**Eeuwigdurende vindbaarheid**

De registraties die in een UOI-code-stelsel worden aangelegd dienen eeuwigdurend
toegankelijk en bereikbaar te zijn. Alleen zo kan worden voorkomen dat een
domein-overstijgende zoekvraag door ‘verdwijnen’ van gegevensinformatie-objecten
of registraties niet beantwoord kunnen worden. Blockchaintechnologie biedt een
manier om een dergelijke robuustheid te bieden. Daarbij is het nader te bepalen
welke gegevens wel en niet “eeuwigdurend” zouden moeten/kunnen worden vastgelegd
en hoe “eeuwigdurendheid” in dit kader om praktische redenen mogelijk wordt
begrensd.

**UOI-code als URI**

Wanneer een UOI-code geïmplementeerd wordt als een URI, dan is er al veel
beschreven over de constructie. Er zijn meerdere URI-strategieën, waaronder die
van PLDN (<https://www.geonovum.nl/themas/uri-strategie>), en ook in NEN3610
komt dit onderwerp terug
(<https://geonovum.github.io/NEN3610-Linkeddata/#nen3610id>).

De “eeuwigdurendheid” van een URI op het internet is niet gegarandeerd. Er kan
linkrot optreden wanneer de bronhouder de met de URI aangeduide registratie of
het record aangeduid door de UOI-code verwijderd. Er is om die reden een
aanvullende afspraak over “eeuwigdurendheid” nodig om het UOI-code stelsel
robuustheid te geven.

**UOI-code als UUID-code**

Wanneer een UOI-code als een UUID-code wordt geïmplementeerd moet het
UOI-register en de UOI-code zelf tevens persistent bereikbaar en
machine-leesbaar zijn.

**Toegangsdiensten**

Op bronnen met URI’s bestaan verschillende toegangsdiensten:

-   HTML

-   REST API

-   GRAPHQL

-   SPARQL

-   ELASTICSEARCH

-   (LINKED DATA FRAGMENTS), etc.

Met ElasticSearch maak je het bijvoorbeeld mogelijk om op de naam van een gebouw
te zoeken en de desbetreffende UOI-code te vinden. Met SPARQL kan je federatief
data over een UOI-code bevragen.

Op bronnen met blockchaincodes bestaan verschillende toegangsdiensten die
eveneens eerst naar een URI verwijzen en dan specifieke blockchain toegang
benutten.

**Soorten URI’s**

Voor de omgang met URI’s zijn er drie subtypen URI’s relevant: Registratie,
Model, Instantie.

| Registratie | UOI Registratie voorbeeld: <https://bgt.basisregistraties.overheid.nl/bgt>  In feite is dit een metadatarecord van een dataset. Zou ook gepubliceerd moeten worden via [Google Datasetsearch](https://datasetsearch.research.google.com/), [Data.overheid.nl](https://data.overheid.nl/) en andere (zoek) registers van datasets. Om dat mogelijk te maken moet de inhoud die via de URI’s wordt geindentificeerd ook voldoen aan het gebruik van metadata standaarden, zoals het gebruik van [schema.org](https://schema.org/). Bij URIs die naar geo-objecten verwijzen is een kaart visualisatie van de verkregen inhoud ook gewenst. |
|-------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Model       | UOI-model (ontologie) voorbeeld: BGT Pand: <https://bgt.basisregistraties.overheid.nl/bgt/def/Pand>  Bij een model URI is vaak een grafische model visualisatie prettig, om snel een overzicht te krijgen van het model. Dit biedt ook het noodzakelijke overzicht om succesvol zoekbevragingen (queries) op instantie niveau te kunnen opstellen.                                                                                                                                                                                                                                                                                       |
| Instantie   | Voorbeelden van een instantie URI: BGT Pand object: <https://bgt.basisregistraties.overheid.nl/bgt/id/registratie/NL.IMGeo.G0301.a4b70c600f474e3a98b3bbe04c56d2a0.2016-03-21T15-32-29.000Z> Of BAG Pand object: <http://bag.basisregistraties.overheid.nl/bag/id/verblijfsobject/0301010000013709>                                                                                                                                                                                                                                                                                                                                       |

Onderstaande figuur (screenshot van een instantie URI) laat de verschillende
facetten zien: met de links kan je er doorheen browsen, ook kan je naar het
model of naar de registratie. Ook kan je naar SPARQL toe om in de URIs te
doorzoeken c.q. te bevragen (‘query-en’), en ook kun je met de knop formats aan
‘*content negotiation*’ doen.

| [./media/image28.png](./media/image28.png)                                                    |
|-----------------------------------------------------------------------------------------------|
| Figuur 14. Voorbeeld RWS-pedia \<*illustratief in kader van ontwerpactiviteiten ontwikkeld*\> |

**Bouwsteen: Interface met UOI-stelsel**

Om de vindbaarheid van gerelateerde objecten over de aangesloten
domeinenregistraties te kunnen realiseren is een soort UOI-API (services) &
model-endpoint nodig die de verschillende zoek/vind transacties op instantie en
modelniveau kan faciliteren.

### Organisatorische borging werking UOI-code stelsel

We beantwoorden achtereenvolgens op hoofdlijnen de volgende vragen:

-   Wat is er nodig om samen het UOI-code-stelsel te realiseren?

-   Wat is er nodig om samen het UOI-code stelsel in stand te kunnen houden?

-   Wat is er nodig om samen het UOI-code-stelsel te beheren?

-   Wat is er nodig om samen het UOI-code-stelsel te besturen?

Deze vragen gaan over wat vaak als governance wordt betiteld. Het is belangrijk
het onderwerp van deze governance daarbij te duiden. Eerder in dit rapport
spraken we al over regime. Dat kan gezien worden als de afspraken over de
uitgifte, vastlegging van de UOI-code, UOI-objecten, UOI-object-relaties en
UOI-object-verwantschappen. Daarnaast zal er in een dergelijk UOI-code-stelsel
ook in een regime voor toegankelijkheid en borging van digitale duurzaamheid van
de gegevens, binnen de reikwijdte van het UOI-code stelsel, moeten worden
voorzien.

**Bouwsteen: Governance**

Om het geheel van deze UOI-faciliteiten, regime-afspraken enz. in stand te
kunnen houden & beheren is een UOI-governance noodzakelijk. Daarmee kan sturing
gegeven aan de blijvende werking van het UOI-code-stelsel

**Wat is er nodig om samen het UOI-code-stelsel te realiseren?**

Om een UOI-code-stelsel van deze omvang met zoveel belanghebbenden te kunnen
realiseren vergt een vehikel dat namens en met de belanghebbenden het stelsel
langs programmamatige weg kan doen realiseren. Tevens is er een flexibele
instap- en ontwikkelstrategie nodig waarlangs het stelsel kan worden opgebouwd.
Deze flexibele instap- en ontwikkelstrategie dient te worden uitgewerkt naar een
stappenplan, een communicatieplan. Ook zal een raming van kosten en baten te
worden opgesteld om coalitievorming en besluitvorming over de realisatieplannen
te kunnen initiëren. Deze stappen zijn later in het traject voorzien. Nu gaat
het vooral om een beeld te krijgen van wat een UOI-code-stelsel kan zijn en
welke meerwaarde dat kan hebben. Uiteraard is aanvullend op wat hierboven is
genoemd ook commitment van belanghebbenden voor realisatieprogramma
noodzakelijk. Daartoe zal een consultatieproces worden ingericht. Wanneer dat
positief wordt uitpakt komt financiering en organisatie van een programmatische
realisatie in zicht.

**Wat is er nodig om het UOI-code stelsel in stand te kunnen houden?**

Om een dergelijk stelsel in stand te kunnen houden is structurele financiering
noodzakelijk om de kosten van de beheerorganisatie en wijzigingsbudgetten te
kunnen dekken. Daarbij lijkt een dergelijk stelsel een infrastructuur die door
alle belanghebbenden zou moeten worden gefinancierd. Via een mKBA
(Maatschappelijke Kosten Baten analyse) kan de omvang van kosten en baten
alsmede waar die kosten en baten vallen in kaart gebracht worden. Dat zicht zal
de beeld-, oordeels en besluitvorming over deelname vanuit belanghebbenden
stimuleren.

**Wat is er nodig om samen het UOI-code-stelsel te beheren?**

Om een infrastructurele voorziening als deze te kunnen beheren is een
beheerorganisatie nodig die de ongestoorde werking van alle componenten van het
borgt. Deze beheerorganisatie acteert in de regel op operationeel en tactisch
niveau. Zij herstelt incidentele fouten in de werking respectievelijk voorziet
in een gremium waar op tactisch niveau beperkte wijzigingen aan componenten en
de werking van het stelsel kunnen worden ingebracht, besproken. Over grote
wijzigingen, die projectmatig gerealiseerd moeten worden, wordt in de
governance-structuur besloten. Het lijkt daarbij handig de
[BOMOS-standaard](https://www.forumstandaardisatie.nl/sites/bfs/files/proceedings/FS22-10-04%204b%20BOMOS.pdf)
als uitgangspunt te hanteren.

**Wat is er nodig om samen het UOI-code-stelsel te besturen?**

Er is een governance-structuur nodig waarin vanuit het gezichtspunt van de
belanghebbenden beslissingen kunnen worden genomen over alle structurele zaken
van het UOI-code stelsel. Dat zijn zaken die een beroep doen op de
gemeenschappelijke fondsen dan wel verschuivingen in de toegevoegde waarde voor
belanghebbenden veroorzaken.

