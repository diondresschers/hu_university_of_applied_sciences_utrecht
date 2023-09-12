<p>INNO Scrum</p>

* Naam: INNO Scrum 
* Datum: 2023-09-12
* Original: [2020 De Scrum Gids](https://scrumguides.org/docs/scrumguide/v2020/2020-Scrum-Guide-Dutch.pdf)
* By: Ken Schwaber en Jeff Sutherland
* Derrivative by: [HU University of Applied Sciences](https://www.hu.nl/) by [Dion Dresschers](https://www.linkedin.com/in/diondresschers/) 
* Download: [hu_university_of_applied_sciences_utrecht/de_scrum_gids at main · diondresschers/hu_university_of_applied_sciences_utrecht](https://github.com/diondresschers/hu_university_of_applied_sciences_utrecht/tree/main/de_scrum_gids)
* Status: Concept
* Versie: 2023-09-12 12:18:26

# Inhoud

- [Inhoud](#inhoud)
- [1. Doel van de Scrum Gids](#1-doel-van-de-scrum-gids)
- [2. Scrum Definitie](#2-scrum-definitie)
- [3. Scrum Theorie](#3-scrum-theorie)
  - [3.1. Transparantie](#31-transparantie)
  - [3.2. Inspectie](#32-inspectie)
  - [3.3. Aanpassing](#33-aanpassing)
- [4. Scrum Waarden](#4-scrum-waarden)
- [5. Scrum Team](#5-scrum-team)
  - [5.1. Developers](#51-developers)
  - [5.2. Product Owner](#52-product-owner)
  - [5.3. Scrum Master](#53-scrum-master)
- [6. Scrum Gebeurtenissen](#6-scrum-gebeurtenissen)
  - [6.1. De Sprint](#61-de-sprint)
  - [6.2. Sprint Planning](#62-sprint-planning)
  - [6.3. Daily Scrum](#63-daily-scrum)
  - [6.4. Sprint Review](#64-sprint-review)
  - [6.5. Sprint Retrospective](#65-sprint-retrospective)
- [7. Scrum Artefacten](#7-scrum-artefacten)
  - [7.1. Product Backlog](#71-product-backlog)
    - [7.1.1. Commitment: Product Doel](#711-commitment-product-doel)
  - [7.2. Sprint Backlog](#72-sprint-backlog)
    - [7.2.1. Commitment: Sprint Doel](#721-commitment-sprint-doel)
  - [7.3. Increment](#73-increment)
    - [7.3.1. Commitment: Definition of Done](#731-commitment-definition-of-done)
- [8. Eindnoot](#8-eindnoot)
  - [8.1. Erkenning](#81-erkenning)
    - [8.1.1. Mensen](#811-mensen)
    - [8.1.2. Scrum Gids Geschiedenis](#812-scrum-gids-geschiedenis)
    - [8.1.3. Vertaling](#813-vertaling)
    - [8.1.4. Wijzigingen ten opzichte van de 2017 Scrum Gids](#814-wijzigingen-ten-opzichte-van-de-2017-scrum-gids)

# 1. Doel van de Scrum Gids

We hebben Scrum in het begin van de 90’er jaren ontwikkeld. We schreven de eerste versie van de Scrum Gids in 2010 om mensen wereldwijd te helpen Scrum te begrijpen. Sindsdien hebben we de Gids middels kleine, functionele aanpassingen geëvolueerd. We staan hier samen achter.

De Scrum Gids bevat de definitie van Scrum. Elk element in het Scrum raamwerk dient een specifiek doel dat essentieel is voor de algehele waarde en resultaten gerealiseerd met Scrum. Het basisontwerp of ideeën van Scrum aanpassen, het weglaten van elementen of de regels van Scrum niet volgen, verbergt problemen en beperkt de voordelen van Scrum en maakt het potentieel zelfs nutteloos.

We volgen het toenemende gebruik van Scrum in een steeds complexere wereld. We zijn vereerd dat Scrum wordt toegepast in vele domeinen waar belangrijk complex werk ligt, voorbij het domein van software productontwikkeling waar de wortels van Scrum liggen. Naarmate het gebruik van Scrum zich verspreidt, doen ontwikkelaars, onderzoekers, analisten, wetenschappers en andere specialisten het werk. We gebruiken het woord ‘Developer’ in Scrum niet om buiten te sluiten, maar om het eenvoudiger te maken. Als je waarde haalt uit Scrum, beschouw jezelf dan inbegrepen.

Tijdens het gebruik van Scrum worden patronen, processen en inzichten gevonden, toegepast en bedacht die passen bij het gebruik van Scrum zoals beschreven in dit document. De beschrijvingen van deze patronen, processen en inzichten passen niet bij het doel van de Scrum Gids, want ze zijn contextafhankelijk en verschillen sterk, afhankelijk van waar Scrum wordt toegepast. Deze tactieken in het gebruik van Scrum lopen sterk uiteen en worden elders beschreven.

Ken Schwaber en Jeff Sutherland, November 2020

© 2020 Ken Schwaber and Jeff Sutherland

This publication is offered for license under the Attribution Share‐Alike license of Creative Commons, accessible at http://creativecommons.org/licenses/by‐sa/4.0/legalcode and also described in summary form at http://creativecommons.org/licenses/by‐sa/4.0/. By utilizing this Scrum Guide, you acknowledge and agree that you have read and agree to be bound by the terms of the Attribution Share‐Alike license of Creative Commons.

# 2. Scrum Definitie

Scrum is een lichtgewicht raamwerk dat mensen, teams en organisaties helpt om waarde te creёren door middel van adaptieve oplossingen voor complexe problemen. In het kort heeft Scrum een Scrum Master nodig om een omgeving te bevorderen waar:

1. Een Product Owner het werk voor een complex probleem ordent in een Product Backlog.
2. Een Scrum Team een selectie van dit werk verandert in een waardevol Increment tijdens een
Sprint.
3. Een Scrum Team en zijn belanghebbenden de resultaten inspecteren en zich aanpassen voor de
volgende Sprint.
4. Herhaal.

Scrum is eenvoudig. Probeer het uit zoals het is en bepaal of de filosofie, theorie en structuur helpen om doelen te behalen en waarde te creëren. Het Scrum raamwerk is doelbewust incompleet en definieert alleen de delen die nodig zijn om Scrum theorie te implementeren. Scrum is gebouwd op de gezamenlijke kennis van de mensen die het gebruiken. Scrum geeft geen gedetailleerde instructies maar begeleidt mensen in hun relaties en interacties.

Binnen het Scrum raamwerk kunnen diverse processen, technieken en methoden worden toegepast. Scrum wikkelt zich om bestaande gebruiken of maakt ze overbodig. Scrum maakt de relatieve doeltreffendheid van huidig management, van de omgeving en van werktechnieken zichtbaar, zodat verbeteringen gedaan kunnen worden.

# 3. Scrum Theorie

Scrum is gebaseerd op empirisme en Lean denken. Empirisme beweert dat kennis ontstaat uit ervaring en dat men beslissingen neemt op basis van wat bekend is. Lean denken vermindert verspilling en richt zich op de meest belangrijke dingen.

Scrum past een iteratieve, incrementele aanpak toe om voorspelbaarheid te optimaliseren en risico’s te beheersen. Scrum verbindt groepen mensen die samen alle benodigde vaardigheden en expertise hebben, om het werk te kunnen doen. Als het nodig is delen ze deze vaardigheden met elkaar of verkrijgen ze deze vaardigheden.

Scrum combineert vier formele gebeurtenissen ten behoeve van inspectie en aanpassing binnen een overkoepelende gebeurtenis, de Sprint. Deze gebeurtenissen zijn effectief omdat zij de empirische Scrum pijlers transparantie, inspectie en aanpassing in praktijk brengen.

## 3.1. Transparantie

Het proces en werk dat ontstaat, moet zichtbaar zijn voor diegenen die het werk doen en diegenen die het werk ontvangen. Met Scrum worden belangrijke keuzes gebaseerd op de waargenomen staat van de drie formele artefacten.

Transparantie maakt inspectie mogelijk. Inspectie zonder transparantie is misleidend en verspillend.

## 3.2. Inspectie

De Scrum artefacten en de voortgang richting overeengekomen doelen moeten regelmatig en grondig worden geïnspecteerd, om mogelijk ongewenste varianties of problemen te detecteren. Om inspectie te ondersteunen, biedt Scrum cadans in de vorm van vijf gebeurtenissen.

Inspectie maakt aanpassing mogelijk. Inspectie zonder aanpassing is zinloos. Scrum gebeurtenissen zijn ontworpen om verandering uit te lokken.

## 3.3. Aanpassing

Als één of meer aspecten van een proces buiten de acceptabele grenzen vallen of als het resulterende product onacceptabel is, zal het proces dat wordt toegepast of het onderhanden werk aangepast moeten worden. Een aanpassing moet zo snel mogelijk uitgevoerd worden om verdere afwijkingen te beperken.

Aanpassing wordt lastiger wanneer de betrokkenen niet bevoegd of zelfsturend zijn. Er wordt van een Scrum Team verwacht zich aan te passen op het moment dat het Scrum Team iets nieuws leert door inspectie.

# 4. Scrum Waarden

Succesvol gebruik van Scrum hangt af van het bekwaam worden in het naleven van de volgende vijf waarden:

> Commitment, Focus, Openheid, Respect en Moed

De Scrum Teamleden committeren zich aan het halen van hun doelen en aan het ondersteunen van elkaar. Hun primaire focus is op het werk van de Sprint, zodat de best mogelijke voortgang richting hun doelen gemaakt kan worden. Het Scrum Team en zijn belanghebbenden zijn open over het werk en de uitdagingen. Scrum Teamleden respecteren elkaar om de capabele, onafhankelijke mensen die ze zijn. Ze worden als zodanig ook gerespecteerd door de mensen waar ze mee werken. De Scrum Teamleden hebben de moed om het juiste te doen; om aan de lastige problemen te werken.

De Scrum waarden geven richting aan het Scrum Team voor hun werk, acties en gedrag. De besluiten die worden genomen, de stappen die worden gemaakt en de manier waarop Scrum wordt toegepast, zouden deze waarden moeten versterken, niet verminderen of ondermijnen. De Scrum Teamleden leren en ontdekken deze waarden tijdens het werken met de Scrum gebeurtenissen en artefacten. Wanneer deze waarden worden uitgedragen door het Scrum Team en de mensen waar ze mee werken, zullen de empirische Scrum pijlers (transparantie, inspectie en aanpassing) tot leven komen en vertrouwen opbouwen.

# 5. Scrum Team

De fundamentele eenheid van Scrum is een klein team van mensen; een Scrum Team. Het Scrum Team bestaat uit één Scrum Master, één Product Owner en Developers. Binnen een Scrum Team bestaan er geen sub‐teams of hiërarchieën. Het Scrum Team is een samenhangende eenheid van professionals gericht op steeds één doel; het Product Doel.

Scrum Teams zijn multidisciplinair, wat inhoudt dat de teamleden alle benodigde vaardigheden hebben om elke Sprint waarde te creëren. Daarnaast is het Scrum Team zelfsturend, wat betekent dat de teamleden onderling bepalen wie wat doet, wanneer en hoe.

Het Scrum Team is klein genoeg om wendbaar te blijven en groot genoeg om werk van betekenis te voltooien binnen een Sprint. Een typisch Scrum Team bestaat uit 10 of minder personen. Over het algemeen communiceren kleine teams beter en zijn ze productiever. Als Scrum Teams te groot worden, kunnen ze overwegen om zich te reorganiseren naar meerdere samenhangende Scrum Teams, elk gericht op hetzelfde product. Om deze reden zouden deze Scrum Teams zowel het Product Doel, de Product Backlog en de Product Owner moeten delen.

Het Scrum Team is verantwoordelijk voor alle productgerelateerde activiteiten, zoals samenwerking met belanghebbenden, verificatie, onderhoud, operatie, experimenteren, onderzoek en ontwikkeling en al het andere dat nodig is. Scrum Teams zijn opgezet en bevoegd door de organisatie, zodat zij hun eigen werk kunnen managen. Het werken in sprints op een duurzaam tempo verbetert de focus en de consistentie van het Scrum Team.

Het gehele Scrum Team is elke Sprint verantwoordelijk voor het creëren van een waardevol en bruikbaar Increment. Scrum definieert drie specifieke verantwoordelijkheden binnen het Scrum Team: de Developers, de Product Owner en de Scrum Master.

## 5.1. Developers

Developers zijn de mensen in het Scrum Team die iedere Sprint gecommitteerd zijn aan het maken van elk aspect van een bruikbaar Increment.

De specifieke vaardigheden die nodig zijn voor de Developers, zijn vaak breed en variëren met het domein van het werk. Developers zijn altijd verantwoordelijk voor:

* Het creëren van een plan voor de Sprint; de Sprint Backlog;
* Het garanderen van kwaliteit door vast te houden aan een Definition of Done;
* Het dagelijks aanpassen van hun plan richting het Sprint Doel;
* Het elkaar verantwoordelijk houden als professionals.

## 5.2. Product Owner

De Product Owner is verantwoordelijk voor het maximaliseren van de waarde van het product, dat het resultaat is van het werk van het Scrum Team. Hoe dit wordt gedaan, kan sterk uiteenlopen tussen organisaties, Scrum Teams en individuen.

De Product Owner is ook verantwoordelijk voor effectief Product Backlog management, wat het volgende omvat:

* Het ontwikkelen en duidelijk overbrengen van het Product Doel;
* Het creëren en helder overbrengen van Product Backlog items;
* Het ordenen van Product Backlog items;
* Het ervoor zorgen dat de Product Backlog transparant en zichtbaar is en begrepen wordt.

De Product Owner kan bovenstaand werk zelf doen of de verantwoordelijkheid delegeren aan anderen. De Product Owner blijft hier echter eindverantwoordelijk voor.

Om Product Owners succesvol te kunnen laten zijn, moet de gehele organisatie hun beslissingen respecteren. Deze beslissingen zijn zichtbaar in de inhoud en ordening van de Product Backlog en in het inspecteerbare Increment tijdens de Sprint Review.

De Product Owner is één persoon, geen comité. De Product Owner kan de behoeften van vele belanghebbenden vertegenwoordigen in de Product Backlog. Zij die de Product Backlog willen veranderen, kunnen dat doen door de Product Owner proberen te overtuigen.

## 5.3. Scrum Master

De Scrum Master is verantwoordelijk voor het opzetten van Scrum, zoals staat beschreven in de Scrum Gids. Scrum Masters doen dit door iedereen te helpen om Scrum theorie en praktijk te begrijpen, zowel binnen het Scrum Team als binnen de organisatie.

De Scrum Master is verantwoordelijk voor de effectiviteit van het Scrum Team. Scrum Masters doen dit door het Scrum Team in staat te stellen zijn werkwijzen te verbeteren binnen het Scrum raamwerk.

Scrum Masters zijn echte leiders die het Scrum Team en de grotere organisatie dienen.

De Scrum Master dient het Scrum Team op een aantal manieren, waaronder:

* Het coachen van teamleden in zelfsturing en multidisciplinair werken;
* Het Scrum Team helpen focussen op het creëren van Increments met hoge waarde, die voldoen aan de Definition of Done;
* Het zorgdragen voor de verwijdering van belemmeringen (‘impediments’) in de voortgang van het Scrum Team;
* Het zorgen dat alle Scrum gebeurtenissen plaatsvinden en dat deze positief, productief en binnen de timebox zijn.

De Scrum Master dient de Product Owner op een aantal manieren, waaronder:

* Het helpen bij het vinden van technieken voor effectieve Product Doel definitie en Product Backlog management;
* Het Scrum Team helpen de noodzaak in te zien van duidelijke en beknopte Product Backlog
items;
* Het helpen tot stand brengen van empirische productplanning voor een complexe omgeving;
* Het faciliteren van samenwerking met belanghebbenden wanneer gevraagd of nodig.

De Scrum Master dient de organisatie op een aantal manieren, waaronder:

* Het leiden, trainen en coachen van de organisatie in haar Scrum adoptie;
* Het plannen en adviseren van Scrum implementaties in de organisatie;
* Het helpen van medewerkers en belanghebbenden bij het begrijpen en volgen van een empirische benadering voor complex werk;
* Het verwijderen van hindernissen tussen belanghebbenden en Scrum Teams.

# 6. Scrum Gebeurtenissen

De Sprint is een overkoepelende gebeurtenis voor alle andere gebeurtenissen. Elke gebeurtenis in Scrum is een formele gelegenheid om de Scrum artefacten te inspecteren en aan te passen. Deze gebeurtenissen zijn specifiek ontworpen om de benodigde transparantie mogelijk te maken. Wanneer het niet lukt om één van deze gebeurtenissen te laten werken zoals beschreven, dan raakt een kans op inspecteren en aanpassen verloren. Gebeurtenissen in Scrum worden gebruikt om regelmaat te creëren en om de behoefte te minimaliseren tot vergaderingen die niet in Scrum zijn gedefinieerd. Het meest gunstig is om de gebeurtenissen op dezelfde plek en op dezelfde tijd te houden om complexiteit te verminderen.

## 6.1. De Sprint

Sprints zijn de hartslag van Scrum, waar ideeën worden omgezet in waarde.

Sprints hebben een vaste lengte van één maand of korter. De vaste lengte zorgt voor consistentie. Een
nieuwe Sprint start direct nadat de vorige Sprint is afgelopen.

Al het noodzakelijke werk wat nodig is om het Product Doel te bereiken, inclusief Sprint Planning, Daily Scrums, Sprint Review en Sprint Retrospective, vindt plaats binnen Sprints.

Tijdens de Sprint:

* Worden geen veranderingen aangebracht die het Sprint Doel in gevaar kunnen brengen;
* Neemt de kwaliteit niet af;
* Wordt de Product Backlog naar behoefte verder uitgewerkt;
* Mag de scope worden verduidelijkt en heronderhandeld met de Product Owner naarmate meer
wordt geleerd.

Sprints maken voorspelbaarheid mogelijk, doordat zij verzekeren dat er tenminste éénmaal per kalendermaand inspectie en aanpassing plaatsvindt ten aanzien van voortgang richting het Product Doel. Wanneer een Sprint te lang duurt, kan het Sprint Doel ongeldig worden, kan complexiteit toenemen en kan het risico groter worden. Kortere Sprints kunnen ingezet worden om meer leercycli te genereren en beperken het risico op onnodige kosten en inzet tot een kortere tijdsspanne. Elke Sprint kan gezien worden als een kort project.

Er zijn verschillende manieren om voortgang te voorspellen, zoals burn‐downs, burn‐ups of cumulative flows. Alhoewel deze manieren hun nut hebben bewezen, vervangen zij niet het belang van empirisme. In complexe omgevingen is het onbekend wat er zal gebeuren. Alleen wat er al is gebeurd, mag worden gebruikt voor toekomstgerichte besluitvorming.

Een Sprint kan afgebroken worden als het Sprint Doel overbodig wordt. Alleen de Product Owner heeft de autoriteit om de Sprint af te breken.

## 6.2. Sprint Planning

Sprint Planning start de Sprint door het uit te voeren werk voor de Sprint uit te stippelen. Het resulterende plan wordt gemaakt door het gezamenlijke werk van het gehele Scrum Team.

De Product Owner verzekert zich ervan dat de aanwezigen voorbereid zijn om de meest belangrijke Product Backlog items en hoe deze zich verhouden tot het Product Doel te bespreken. Het Scrum Team mag ook anderen uitnodigen om de Sprint Planning bij te wonen als adviseur.

Sprint Planning behandelt de volgende onderwerpen:

Onderwerp Een: Waarom is deze Sprint waardevol?

De Product Owner doet een voorstel hoe het product in waarde en bruikbaarheid zou kunnen toenemen deze Sprint. Het hele Scrum Team werkt vervolgens samen om een Sprint Doel te definiëren dat aangeeft waarom deze Sprint waardevol is voor de belanghebbenden. Het Sprint Doel moet vastgelegd zijn voor het einde van de Sprint Planning.

Onderwerp Twee: Wat kan deze Sprint worden afgerond?

In overleg met de Product Owner selecteren de Developers items van de Product Backlog om op te nemen in de huidige sprint. Het Scrum Team kan deze items tijdens dit proces verder uitwerken, zodat begrip en vertrouwen toenemen.

Het kan uitdagend zijn om te selecteren hoeveel werk gedaan kan worden binnen een Sprint. Echter, hoe meer de Developers weten over hun vorige prestaties, hun aankomende capaciteit en hun Definition of Done, hoe meer vertrouwen zij zullen hebben in hun Sprint prognoses.

Onderwerp Drie: Hoe zal het gekozen werk gedaan worden?

Voor elk geselecteerd Product Backlog item plannen de Developers het werk dat nodig is om een Increment te maken dat aan de Definition of Done voldoet. Dit gebeurt vaak door Product Backlog items op te breken in kleinere werk items die gedaan kunnen worden binnen een dag of minder. Hoe dit gebeurt, is volledig aan de Developers. Niemand anders mag ze vertellen hoe ze de Product Backlog items moeten omzetten in waardevolle Increments.

Het Sprint Doel, de Product Backlog items die geselecteerd zijn voor de Sprint, plus het plan hoe ze worden opgeleverd, worden gezamenlijk de Sprint Backlog genoemd.

Sprint Planning is getimeboxt tot een maximum van acht uur voor een Sprint van een maand. Voor kortere Sprints duurt deze gebeurtenis meestal korter.

## 6.3. Daily Scrum

Het doel van de Daily Scrum is om voortgang richting het Sprint doel te inspecteren en de Sprint Backlog als nodig aan te passen, waarbij het aankomend gepland werk wordt bijgesteld.

De Daily Scrum is een gebeurtenis van 15 minuten voor de Developers van het Scrum Team. Om complexiteit te verminderen, wordt het elke werkdag van de Sprint op dezelfde tijd en op dezelfde plaats gehouden. Als de Product Owner of Scrum Master actief werken aan items in de Sprint Backlog nemen ze deel als Developers.

De Developers kiezen zelf de structuur en techniek die ze willen, zolang hun Daily Scrum focust op voortgang richting het Sprint Doel en het een uitvoerbaar plan genereert voor het werk van de komende dag. Dit creëert focus en verbetert de zelfsturing.

Daily Scrums verbeteren communicatie, identificeren belemmeringen, helpen in het snel nemen van beslissingen en nemen daarmee de noodzaak voor andere vergaderingen weg.

De Daily Scrum is niet het enige moment waarop de Developers hun plan mogen aanpassen. Gedurende de dag komen ze vaak samen voor meer gedetailleerde discussies over het aanpassen of het herplannen van de rest van het werk van de Sprint.

## 6.4. Sprint Review

Het doel van de Sprint Review is om de uitkomst van de Sprint te inspecteren en toekomstige aanpassingen te bepalen. Het Scrum Team presenteert de resultaten van hun werk aan de belangrijkste belanghebbenden en de voortgang richting het Product Doel wordt besproken.

Tijdens de Sprint Review beoordelen het Scrum Team en belanghebbenden wat werd bereikt in de Sprint en wat er is veranderd in hun omgeving. Op basis van deze informatie werken de aanwezigen samen om te bepalen wat als volgende te doen. De Product Backlog kan ook aangepast worden om nieuwe kansen te grijpen. De Sprint Review is een werksessie en het Scrum Team zou moeten vermijden dat het bij een presentatie blijft.

De Sprint Review is de voorlaatste gebeurtenis van de Sprint en is getimeboxt tot een maximum van vier uur voor een Sprint van een maand. Voor kortere Sprints duurt deze gebeurtenis meestal korter.

## 6.5. Sprint Retrospective

Het doel van de Sprint Retrospective is om manieren te bedenken om kwaliteit en effectiviteit te verhogen en in te plannen.

Het Scrum Team inspecteert hoe de afgelopen Sprint is gegaan met betrekking tot individuen, interacties, processen, tools en hun Definition of Done. Geïnspecteerde elementen verschillen vaak per domein van het werk. Aannames die niet juist bleken, worden geïdentificeerd en hun oorsprong onderzocht. Het Scrum Team bespreekt wat goed ging tijdens de Sprint, welke problemen het is tegengekomen en hoe deze problemen werden (of niet werden) opgelost.

Het Scrum Team identificeert de meest nuttige veranderingen om zijn effectiviteit te verhogen. De meest impactvolle verbeteringen worden zo snel mogelijk aangepakt. Ze kunnen zelfs worden toegevoegd aan de Sprint Backlog voor de volgende Sprint.

De Sprint Retrospective sluit de Sprint. Het is getimeboxt tot een maximum van drie uur voor een Sprint van een maand. Voor kortere sprints duurt deze gebeurtenis meestal korter.

# 7. Scrum Artefacten

De artefacten van Scrum vertegenwoordigen werk of waarde. Ze zijn ontworpen voor maximale transparantie van de belangrijkste informatie. Dankzij deze transparantie heeft iedereen, die deze artefacten inspecteert, dezelfde basis voor aanpassing.

Elk artefact bevat een commitment om ervoor te zorgen dat het informatie geeft die de transparantie en de focus verhoogt, waaraan de vooruitgang kan worden gemeten:

* Voor de Product Backlog is dit het Product Doel.
* Voor de Sprint Backlog is dit het Sprint Doel.
* Voor het Increment is dit de Definition of Done.

Deze commitments bestaan om empirisme en de Scrum waarden te versterken voor het Scrum team en zijn belanghebbenden.

## 7.1. Product Backlog

De Product Backlog is een levende, geordende lijst van wat nodig is om het product te verbeteren. Het is de enige bron van het werk dat door het Scrum Team gedaan wordt.

Product Backlog items die binnen een Sprint ‘Done’ gemaakt kunnen worden door het Scrum Team, worden beschouwd als klaar voor selectie in een Sprint Planning. De items halen dit niveau van transparantie gebruikelijk na verder uitgewerkt te zijn. Het uitwerken van de Product Backlog(‘refinement’) is het verkleinen en verder definiëren van Product Backlog items in kleinere, meer nauwkeurige items. Dit is een doorlopende activiteit om details zoals een beschrijving, volgorde en grootte toe te voegen. De attributen verschillen vaak per domein van het werk.

De Developers die het werk doen zijn verantwoordelijk voor het inschatten van de grootte. De Product Owner mag de Developers beïnvloeden door ze te helpen bij het begrijpen en selecteren van afwegingen.

### 7.1.1. Commitment: Product Doel

Het Product Doel beschrijft een toekomstige staat van het product, dat kan dienen als een doelwit voor het Scrum Team om tegen te plannen. Het Product Doel is onderdeel van de Product Backlog. De rest van de Product Backlog wordt voortdurend aangevuld met items die definiëren “wat” invulling zal geven aan het Product Doel.

> Een product is een middel om waarde te leveren. Het heeft een duidelijk kader, bekende belanghebbenden en goed‐gedefinieerde gebruikers of klanten. Een product kan een dienst, een fysiek product of iets meer abstracts zijn.

Het Product Doel is de langetermijndoelstelling van het Scrum Team. Ze moeten het ene doel bereiken (of opgeven) voordat ze het volgende doel aanpakken.

## 7.2. Sprint Backlog

De Sprint Backlog is samengesteld uit het Sprint Doel (waarom), de set van Product Backlog items geselecteerd voor de Sprint (wat) en een uitvoerbaar plan voor het opleveren van het Increment (hoe).

De Sprint Backlog is een plan voor en door de Developers. De Sprint Backlog is een zeer zichtbaar, realtime beeld van het werk dat de Developers van plan zijn te doen gedurende de Sprint om het Sprint Doel te bereiken. Daarom wordt de Sprint Backlog geüpdatet tijdens de Sprint, naarmate er meer wordt geleerd. De Sprint Backlog zou voldoende detail moeten hebben, zodat de Developers hun voortgang kunnen inspecteren tijdens de Daily Scrum.

### 7.2.1. Commitment: Sprint Doel

Het Sprint Doel is de enige doelstelling voor de Sprint. Het Sprint Doel is een commitment door de Developers. Het geeft flexibiliteit in de vorm van het exacte werk dat nodig is om het doel te behalen. Het Sprint Doel geeft ook samenhang en focus, zodat het Scrum Team wordt aangemoedigd om samen te werken in plaats van aan verschillende initiatieven.

Het Sprint Doel wordt opgesteld tijdens de Sprint Planning en daarna toegevoegd aan de Sprint Backlog. Tijdens het werken in de Sprint houden de Developers het Sprint Doel voor ogen. Indien het werk anders blijkt te zijn dan de Developers hadden verwacht, werken zij binnen de Sprint samen met de Product Owner om over de scope van de Sprint Backlog te onderhandelen, zonder daarbij het Sprint Doel aan te tasten.

## 7.3. Increment

Een Increment is een concrete stap in de richting van het Product Doel. Elk Increment is een toevoeging aan alle voorgaande Increments en grondig getoetst om ervoor te zorgen dat alle Increments samenwerken. Om waarde te creëren, moet het Increment bruikbaar zijn.

Er kunnen meerdere Increments gemaakt worden binnen een Sprint. De som van de Increments wordt gepresenteerd tijdens de Sprint Review en ondersteunt zo het empirisme. Een Increment mag echter aan belanghebbenden geleverd worden voor het eind van de Sprint. De Sprint Review mag nooit worden beschouwd als een poort naar het vrijgeven van waarde.

Werk kan niet worden beschouwd als onderdeel van een Increment, tenzij het voldoet aan de Definition of Done.

### 7.3.1. Commitment: Definition of Done

De Definition of Done is een formele beschrijving van de staat van het Increment wanneer deze voldoet aan de kwaliteitseisen die voor het product benodigd zijn.

Op het moment dat een Product Backlog item voldoet aan de Definition of Done, ontstaat een Increment.

De Definition of Done zorgt voor transparantie, doordat iedereen een gedeeld begrip heeft van wat voor werk is afgerond als onderdeel van het Increment. Als een Product Backlog item niet voldoet aan de Definition of Done, dan kan het niet gereleased worden en zelfs niet in de Sprint Review gepresenteerd worden. In plaats daarvan gaat het item terug naar de Product Backlog, voor toekomstige overweging.

Als de Definition of Done voor een Increment onderdeel is van de standaarden van de organisatie, dan moeten alle Scrum Teams deze ten minste volgen. Als de Definition of Done geen standaard van de organisatie is, moet het Scrum Team een Definition of Done opstellen die geschikt is voor het product.

De Developers zijn verplicht zich te houden aan de Definition of Done. Als er meerdere Scrum Teams aan hetzelfde product samenwerken, moeten zij gezamenlijk dezelfde Definition of Done definiëren en eraan voldoen.

# 8. Eindnoot

Scrum is gratis en wordt aangeboden in deze Gids. Het Scrum raamwerk, zoals in deze Gids uiteen is gezet, is onveranderlijk. Hoewel het implementeren van delen van Scrum mogelijk is, is het daaruit volgend resultaat geen Scrum. Scrum bestaat slechts als geheel en functioneert goed als container voor andere technieken, methodologieën en gebruiken.

## 8.1. Erkenning

### 8.1.1. Mensen

Van de duizenden mensen die hebben bijgedragen aan Scrum, moeten we toch een paar mensen benoemen die sleutelrollen hebben vervuld bij het begin: Jeff Sutherland werkte samen met Jeff McKenna en John Scumniotales, Ken Schwaber werkte samen met Mike Smith en Chris Martin; ze hebben ook allemaal samengewerkt. In de jaren daaropvolgend hebben nog vele anderen een bijdrage geleverd en zonder hun hulp zou Scrum niet zo verfijnd zijn zoals nu het geval is.

### 8.1.2. Scrum Gids Geschiedenis

Ken Schwaber en Jeff Sutherland presenteerden samen Scrum voor het eerst tijdens de OOPSLA‐ conferentie in 1995. Deze presentatie documenteerde in wezen datgene wat Ken en Jeff geleerd hadden gedurende de afgelopen jaren en dit was de eerste publieke formele definitie van Scrum.

De Scrum Gids documenteert Scrum zoals ruim dertig jaar ontwikkeld, geëvolueerd, en in stand gehouden door Jeff Sutherland en Ken Schwaber. Andere bronnen voorzien in patronen, processen en inzichten die het Scrum raamwerk aanvullen. Deze kunnen de productiviteit, waarde, creativiteit en tevredenheid met de resultaten verhogen.

De volledige geschiedenis van Scrum wordt elders beschreven. Ter ere van de eerste plekken waar het werd geprobeerd en bewezen, noemen we hier Individual Inc., Newspage, Fidelity Investments en IDX
(nu GE Medical).

### 8.1.3. Vertaling

Deze Gids is vertaald vanuit de originele Engelse versie, beschikbaar gesteld door de ontwikkelaars van Scrum, die hierboven genoemd worden. Deze vertaling is gemaakt door Ruud Rietveld (scrumruud@gmail.com), Jaap Verweij en Maarten Wagenaar. Hun dank gaat uit naar Stefan Warringa, Eelco Gravendeel, Marco Heerebout, Peter Janssens en Arjen Wassink voor de eerdere versies van de Nederlandse vertaling.

### 8.1.4. Wijzigingen ten opzichte van de 2017 Scrum Gids

Nog Minder Voorschrijvend

Over de jaren heen begon de Scrumgids iets meer voorschrijvend te worden. De 2020 versie is bedoeld om Scrum terug te brengen naar een minimaal voldoende raamwerk door het verwijderen of afzwakken van voorschrijvende taal. Voorbeelden zijn: het verwijderen van de Daily Scrum vragen, het afzwakken van taal rondom Product Backlog Item attributen, het afzwakken van taal rondom Retrospective items op de Sprint Backlog, het verkorten van de tekst over het afbreken van de Sprint en meer.

Eén Team, Gefocust op Eén Product

Het doel was om het concept van een apart team binnen een team te elimineren. Dat concept heeft geleid tot “proxy” of “wij” en “zij” gedrag tussen Product Owner en het Development Team. Er is nu alleen één Scrum Team, gefocust op hetzelfde doel, met drie verschillende sets aan verantwoordelijkheden: Product Owner, Scrum Master en Developers.

Introductie van het Product Doel

De 2020 versie van de Scrum Gids introduceert het concept van een Product Doel om focus te geven voor het Scrum Team richting een grotere, waardevolle doelstelling. Elke Sprint moet het product dichter bij het Product Doel brengen.

Een Thuis voor Sprint Doel, Definition of Done en Product Doel

Vorige Scrum Gidsen hebben het Sprint Doel en de Definition of Done beschreven zonder ze een identiteit te geven. Ze waren geen artefacten maar waren enigszins gekoppeld aan artefacten. Met de toevoeging van het Product Doel geeft de 2020 versie hier meer duidelijkheid over. Elk van de drie artefacten heeft nu ‘commitments’ in zich. Voor de Product Backlog is dit het Product Doel, voor de Sprint Backlog is dit het Sprint Doel en het Increment heeft de Definition of Done (nu zonder aanhalingstekens). Ze bestaan om transparantie en focus te brengen richting de voortgang van elk artefact.

Zelfsturend over Zelforganiserend

Vorige Scrum Gidsen hebben Development Teams zelforganiserend genoemd: zelf kiezen wie het werk doen en hoe. Met een grotere focus op het Scrum Team benadrukt de 2020 versie een zelfsturend Scrum Team: zelf kiezen waaraan te werken, wie het werk doet en hoe.

Drie Sprint Planning Onderwerpen

Als toevoeging op de Sprint Planning onderwerpen “Wat” en “Hoe” benadrukt de 2020 versie van de Scrum Gids een derde onderwerp: “Waarom”, verwijzend naar het Sprint Doel.

Algemene Vereenvoudiging van Taalgebruik voor een Breder Publiek

De 2020 versie van de Scrum Gids heeft de nadruk gelegd op het verwijderen van overtollige en complexe uitspraken en het verwijderen van elke resterende verwijzing aan IT werk (zoals testen, systeem, ontwerp, requirement et cetera). De Scrum Gids is nu minder dan 14 pagina’s.