# Functionaliteit, handleiding cq testplan

Bij LitterTagger wordt momenteel hard gewerkt aan nieuwe zaken. Zo hard, dat je al bijna zou vergeten wat er allemaal mogelijk is.

De documentatie die we tot nu toe geschreven hebben, is op 'hoog niveau' om juist niet steeds bij te hoeven werken als er een detail verandert. Daardoor bestaat echter de kans dat bepaalde details, die we nu aan het maken zijn, vergeten worden terwijl die juist met een reden gemaakt zijn.

Als er nieuwe zaken worden gemaakt, dan handelen we in principe een kaartje op ons Trello-board af en als die klaar is, dan sluiten we die.

Het is mijn bedoeling om in dit specifieke hoofdstuk de werking van die kaartjes op te gaan nemen zodat we een overzicht hebben van wat we al hebben gemaakt en ook meteen soort testplan hebben om per onderdeel te kijken of dat lekker werkt.

In principe zou je als gebruiker al deze stappen moeten kunnen doorlopen en dan zijn we uiteraard benieuwd naar je ervaringen.

O ja, het kan zijn dat er ook zaken worden beschreven die meer voor de 'adminitrators' zijn, die mag je negeren.

## Menu

Het menu heeft de volgende opties: Dashboard, My Photos, Upload, Docs, Dark/light-modus, Team-settings, User-settings

## User aanmaken

Op dit moment werken we nog met reeds aangemaakte testusers. Als bekend is hoe het (zelf) aanmaken van users werkt, wordt dat hier toegevoegd

## Profiel aanmaken/vullen

- het is mogelijk een profiel-foto toe te voegen, deze mag 20mb groot zijn
- het is mogelijk om de profiel-foto weer te verwijderen
- het is mogelijk om aan te geven of je afval wel of niet opraapt. (Per foto of item kan je dat ook nog wijzigen)
- het is mogelijk om aan te geven of je afval wel of niet recycled. (Per foto of item kan je dat ook nog wijzigen)
- 

## Foto's uploaden

- Het is mogelijk 1 foto te uploaden via het Upload-scherm. Dit kan door naar een folder te navigeren en een foto te selecteren, het kan ook door een foto te selecteren en naar het upload-scherm te slepen en daar los te laten.
- Het is ook mogelijk om in 1 keer meerdere foto's te uploaden.
- Het is ook mogelijk om nog meer foto's te 'droppen' terwijl de andere nog aan het uploaden zijn
- Door alvast naar 'My Photos' te gaan terwijl foto's nog aan het uploaden zijn, breekt het uploaden af!
- Tijdens het uploaden is de knop om naar My Photos te gaan, nog niet actief (maar zitten nog paar bugjes in, dus probeer dat niet totdat je klaar bent met uploaden)
- De geselecteerde foto's worden verkleind voordat ze worden geupload om ruimte te besparen. Ze blijven groot genoeg om beeldvullend te kunnen zijn
- Het is mogelijk om foto's van verschillende types te uploaden
- Er zit een bovengrens aan de foto's, als ze té groot zijn, dan worden ze niet geaccepteerd, dit zie je dan door een melding
- het is (uiteraard) mogelijk om foto's te uploaden met gps
- het is ook mogelijk om foto's te uploaden zónder gps

## My Photos
- het is mogelijk om nog geen enkele foto te hebben
- het is mogelijk om 1 foto te hebben, die wordt dan getoond
- het is mogelijk om er meerdere te hebben, die nog steeds op 1 pagina kunnen worden getoond
- het is mogelijk om meer foto's te hebben dan er op 1 pagina passen (momenteel ingesteld op 12), dan verschijnen knoppen om over de pagina's heen te navigeren
- bij het navigeren kan je niet verder vooruit dan de laatste pagina en niet verder terug dan de eerste pagina
- je kan naar een specifieke pagina gaan (mits die getoond wordt als nummer onder de foto's)
- je kan naar vorige/volgende of naar 1e/laatste (is dat zo? Nog niet te zien omdat we nog niet zoveel pagina's hebben)
- als je een of meerdere foto's van kenmerken hebt voorzien, dan staat er een label-icoontje op die foto
- elke foto in 'my photos' is voorzien van een prullenbak, daarmee kan je de foto verwijderen

## Donker of licht scherm
- het is mogelijk om te switchen naar Dark-mode
- het is mogelijk om te switchen naar Light-mode
- het is mogelijk om te switchen naar de system-setting, die je zelf ingesteld hebt staan

## Kenmerken toevoegen aan een foto, 'taggen'
- een foto die net geupload is, heeft nog geen kenmerken
- de lijst van objecten waaruit je kan kiezen staat op alf. volgorde, de eerste wordt standaard getoond
- het is mogelijk om een waarde te kiezen door de lijst door te scrollen en een keuze te maken
- het is mogelijk om een waarde te kiezen door letters te tikken, de waarden die daaraan voldoen, worden getoond. Dit kan zowel voor het item, het materiaal, het merk en/of het evenement
- het is mogelijk om meer dan 1 item te kiezen voor 1 foto (1 foto met meerdere verschillende soorten items)
- het is mogelijk om hetzelfde item meerdere keren te kiezen (1 foto met meerdere soortgelijke items)
- Voor elk afzonderlijk item op de foto kan je aangeven uit wat voor materiaal (of meerdere) het bestaat
- Voor elk afzonderlijk item op de foto kan je aangeven uit wat voor merk (of meerdere) het bestaat
- Voor elk afzonderlijk item op de foto kan je aangeven voor welk evenement (of meerdere) deze geraakt is
- Voor elk afzonderlijk item op de foto kan je aangeven hoeveel er op staan met de tags die je gegeven hebt. Je kan dit met de pijltjestoetsen doen, of door het getal in te voeren. Nadat hij het aantal heeft overgenomen, wordt dat ook getoond voor de naam van het item. Je hebt de optie tussen 1 tm 999 (het getal toont nu nog niet lekker, wordt later verbeterd).
- Voor elk afzonderlijk item op de foto kan je aangeven of het opgeraapt is of niet, hij neemt de defaultwaarde over die bij Profiel is aangegeven
- Voor elk afzonderlijk item op de foto kan je aangeven of je het (laat) recyclen of niet, hij neemt de defaultwaarde over die bij Profiel is aangegeven
- Er kunnen meerdere materialen, merken en evenementen worden gekozen voor 1 item
- Elk kenmerk dat gegeven is aan een item kan worden verwijderd door daar weer op te klikken
- het hele item kan worden verwijderd door op de prullenbak te klikken die bij het item staat
- Elk item waarvan aangegeven is dat het voorkomt op de foto kan worden verwijderd door op de prullenbak te klikken
- Op elk moment kan gekozen worden voor de copieerknop in het item-scherm, alles wat tot dan toe aangegeven is voor dat ene item op de foto, wordt gedupliceerd
- Als er nog nieuwere foto's zijn zonder items of tags, dan staat onder de foto een 'previous'-knop die je naar die foto brengt,
- Als er nog oudere foto's zijn zonder items of tags, dan staat onder de foto een 'next'-knop die je naar die foto brengt,
- Het navigeren naar vorige/volgende, kan ook met de sneltoets CTRL + Pijltjestoets (links/rechts)
- Voor elk te kiezen 'ding' (item, materiaal, merk, evenement) is er een keuze 'OTHER' voor het geval de juiste waarde er niet is
- Als je naar een andere foto bent gegaan en je komt terug bij de eerdere foto, dan staan de laatst gegeven kenmerken er nog

## Evenementen
Er zullen meerdere evenementen zijn per jaar, en als we deze willen faciliteren, dan zullen we deze toe moeten voegen. Dit doen we in principe met 2 kenmerken: 1 voor de algemene (die elk jaar gebruikt wordt) en 1 voor dezelfde naam, inclusief een jaartal (die alleen in dat jaar gebruikt wordt). Op die manier kan data gezocht worden van een specifiek jaar (of enkele specifieke jaren), maar ook gezocht worden over alle jaren heen.

De volgende evenementen zullen aanwezig zijn, met de volgende reden:
- Canuary: Voor de actie van Paul Waye die in januari blikjes verzameld
- Cleanup4Sarah: Voor de actie die elk jaar gehouden wordt ter nagedachtenis aan Sarah, een zwerfafvalraapster
- CornishSpliced: Voor de twitteraar die elke maand een groeps-speurtocht organiseert
- PeukMeuk: Voor de actie waarbij in NL op 1 dag zoveel mogelijk peuken worden geraapt
- RedBullLitter: Voor de twitteraar die elke dag 1 blikje Red Bull tweet
- WorldCleanupDay: Voor de actie waarop in de hele wereld op 1 dag zoveel mogelijk afval wordt geraapt
- ZaandeWandel: Voor de actie waarbij wandelaars geld inzamelen tegen kanker en waarbij de route na afloop wordt opgeruimd

De volgende evenementen zijn niet echt evenementen in die zin van het woord, maar kunnen wel worden gebruikt om speciale zaken eruit te laten springen:
- BeforeAndAfter: Om een vervuilde plaats te laten zien (dit kenmerk, plus 'before') en de opgeruimde plaats (dit kenmerk, plus 'after')
- ShowYourImpact: Om het eindresultaat van een cleanup te laten zien, bijv een berg met volle vuilniszakken

## Admin-opties
- de admin kan alle mogelijke **items** zien en beheren (toevoegen/wijzigen/verwijderen),
- de admin kan alle **foto's** zien:
  Hij kan kiezen tussen 'alle fotos/alle foto's met tag/alle foto's zonder tags'
  Hij kan sorteren op id of user
  Hij kan zoeken (op users alleen?)
  Hij kan filteren op users
  Hij kan kiezen om alleen foto met gps te laten zien of alle foto's, (alleen foto's zónder gps komt later)
  Hij kan een aantal extra velden laten zien (default niet in beeld, ook handig voor video's)
  Hij kan bulk-acties uitvoeren op 1 of meerdere geselecteerde foto's (delete voor nu)
- de admin kan alle mogelijke tags zien en beheren (toevoegen/wijzigen/verwijderen),
  Hij kan zien hoeveel er zijn van elke soort en daarop filteren
  Hij kan sorteren op alle kolommen, standaard staat hij op alf. volgorde
  Hij kan zoeken naar specifieke tags
  Hij kan extra kolommen laten zien
- de admin kan alle users zien en beheren (toevoegen/wijzigen/verwijderen),
  Hij kan sorteren op alle kolommen
  Hij kan zoeken op een user
  hij kan filters toepassen (voor nu alleen op team)
  Hij kan extra kolommen laten zien
  Hij kan bulk-acties uitvoeren

## Pull Requests
Het is mogelijk om bij te dragen aan het project. Daarvoor is wel enige specifieke kennis nodig, maar er zijn genoeg leden die bereid zijn om dat uit te leggen.

Als je een github-account hebt, dan heb je waarschijnlijk al voldoende kennis om bijvoorbeeld zelf een extra merk toe te voegen. (Als github je niets zegt, is dat niet erg, maar dan heb je vermoedelijk onvoldoende kennis om dat zelf te doen, in dat geval kan je vragen of dat extra merk door een admin toegevoegd kan worden zodat je direct verder kan (en wordt dat merk ook door iemand toegevoegd in de zogenaamde 'feeder').
Als een Pull Request wordt gemaakt, worden ook automatisch tests afgetrapt. Mocht er iets niet goed zijn in de PR, dan zie je dat dus binnen een minuut.
