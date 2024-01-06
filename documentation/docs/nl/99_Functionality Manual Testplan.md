# Functionaliteit, handleiding cq testplan

Bij LitterTagger wordt momenteel hard gewerkt aan nieuwe zaken. Zo hard, dat je al bijna zou vergeten wat er allemaal mogelijk is.

De documentatie die we tot nu toe geschreven hebben, is op 'hoog niveau' om juist niet steeds bij te hoeven werken als er een detail verandert. Daardoor bestaat echter de kans dat bepaalde details, die we nu aan het maken zijn, vergeten worden terwijl die juist met een reden gemaakt zijn.

Als er nieuwe zaken worden gemaakt, dan handelen we in principe een kaartje op ons Trello-board af en als die klaar is, dan sluiten we die.

Het is mijn bedoeling om in dit specifieke document de werking van die kaartjes op te gaan nemen zodat we een overzicht hebben van wat we al hebben gemaakt en ook meteen soort testplan hebben om per onderdeel te kijken of dat lekker werkt.

In principe zou je als gebruiker al deze stappen moeten kunnen doorlopen en dan zijn we uiteraard benieuwd naar je ervaringen.

O ja, het kan zijn dat er ook zaken worden beschreven die meer voor de 'adminitrators' zijn, die mag je negeren.

## Menu

Het menu heeft de volgende opties: Dashboard, My Photos, Upload, Docs, Dark/light-modus, Team-settings, User-settings

## User aanmaken

Op dit moment werken we nog met reeds aangemaakte testusers. Als bekend is hoe het (zelf) aanmaken van users werkt, wordt dat hier toegevoegd

## Profiel aanmaken/vullen

- het is mogelijk een profiel-foto toe te voegen, op dit moment mag hij echter niet groter zijn dan 1024kb
- het is mogelijk om de profiel-foto weer te verwijderen
- het is mogelijk om aan te geven of je afval wel of niet opraapt. (Per foto of item kan je dat ook nog wijzigen)
- 

## Foto's uploaden

- Het is mogelijk 1 foto te uploaden via het Upload-scherm. Dit kan door naar een folder te navigeren en een foto te selecteren, het kan ook door een foto te selecteren en naar het upload-scherm te slepen en daar los te laten.
- Het is ook mogelijk om in 1 keer meerdere foto's te uploaden.
- Het is ook mogelijk om nog meer foto's te 'droppen' terwijl de andere nog aan het uploaden zijn
- Door alvast naar 'My Photos' te gaan terwijl foto's nog aan het uploaden zijn, breekt het uploaden af!
- De geselecteerde foto's worden verkleind voordat ze worden geupload om ruimte te besparen. Ze blijven groot genoeg om beeldvullend te kunnen zijn
- Het is mogelijk om foto's van verschillende types te uploaden
- Er zit een bovengrens aan de foto's, als ze té groot zijn, dan worden ze niet geaccepteerd, dit zie je dan door een melding
- het is (uiteraard) mogelijk om foto's te uploaden met gps
- het is ook mogelijk om foto's te uploaden zónder gps
- het is nog niet mogelijk om foto's ook weer te verwijderen, als je een foto verwijderd wilt hebben, zal dat nog via de admins moeten

## My Photos
- het is mogelijk om nog geen enkele foto te hebben
- het is mogelijk om 1 foto te hebben, die wordt dan getoond
- het is mogelijk om er meerdere te hebben, die nog steeds op 1 pagina kunnen worden getoond
- het is mogelijk om meer foto's te hebben dan er op 1 pagina passen (momenteel ingesteld op 16?), dan verschijnen knoppen om over de pagina's heen te navigeren
- bij het navigeren kan je niet verder vooruit dan de laatste pagina en niet verder terug dan de eerste pagina
- je kan naar een specifieke pagina gaan (is dat zo?)
- je kan naar vorige/volgende of naar 1e/laatste (is dat zo?)
- als je een of meerdere foto's van kenmerken hebt voorzien, dan staat er een label-icoontje op die foto

## Donker of licht scherm
- het is mogelijk om te switchen naar Dark-mode
- het is mogelijk om te switchen naar Light-mode
- het is mogelijk om te switchen naar de system-setting, die je zelf ingesteld hebt staan

## Kenmerken toevoegen aan een foto, 'taggen'
- een foto die net geupload is, heeft nog geen kenmerken
- de lijst van objecten waaruit je kan kiezen staat op alf. volgorde, de eerste wordt standaard getoond
- het is mogelijk om een waarde te kiezen door de lijst door te scrollen en een keuze te maken
- het is mogelijk om een waarde te kiezen door de beginletters ervan te tikken en te selecteren met muis, of Enter
- het is mogelijk om meer dan 1 item te kiezen voor 1 foto (1 foto met meerdere verschillende soorten items)
- het is mogelijk om hetzelfde item meerdere keren te kiezen (1 foto met meerdere soortgelijke items)
- alle Nederlandse merken zijn aanwezig
- Voor elk afzonderlijk item op de foto kan je aangeven of het opgeraapt is of niet, hij neemt de defaultwaarde over die bij Profiel is aangegeven
- Elk kenmerk dat gegeven is aan een item kan worden verwijderd door daar weer op te klikken
- Elk item waarvan aangegeven is dat het voorkomt op de foto kan worden verwijderd door op de prullenbak te klikken
- Er kunnen meerdere materialen, merken en evenementen worden gekozen voor 1 item
- Op elk moment kan gekozen worden voor de copieerknop in het item-scherm, alles wat tot dan toe aangegeven is voor dat ene item op de foto, wordt gedupliceerd
- Als er nog nieuwere foto's zijn zonder items of tags, dan staat onder de foto een 'previous'-knop die je naar die foto brengt,
- Als er nog oudere foto's zijn zonder items of tags, dan staat onder de foto een 'next'-knop die je naar die foto brengt,
- Voor elk te kiezen 'ding' (item, materiaal, merk, evenement) is er een keuze 'OTHER' voor het geval de juiste waarde er niet is
- 

## Admin-opties
- de admin kan alle foto's zien
- de admin kan alle mogelijke items, tags en users zien
- de admin kan de foto's per user zien en kan daar bulk-acties op uitvoeren
- de admin kan sorteren op alle kolommen, standaard staat hij op alf. volgorde
- de admin kan teams toevoegen
