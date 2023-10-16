# LaboReeks Git
## **Labo 5C: GitHub pages**

In dit labo gaan we aan de slag met GitHub pages.
We zullen ook in dit labo een lokale repository gaan clonen waar we vervolgens alle lokale wijzigingen gaan synchroniseren met deze remote git repository (GitHub). 

Je eindresultaat van het labo zal op deze manier automatisch in deze GitHub repository terecht komen. Met andere woorden, voor dit labo **upload je niks manueel** op GitHub! 
Alles wat gevraagd wordt dien je lokaal toe te voegen en vervolgens via de nodige commandos ook in de online repository te brengen.
Indien er GitHub-specifieke features gevraagd worden dan kan je deze uiteraard uitvoeren op de remote repository zelf. Dit zal aangeduid worden op de taken die van toepassing zijn op GitHub-specifieke features.

#### **Aanvullende toets op Leho**
Na het afwerken van dit labo heb je op Leho een aanvullende toets met betrekking tot het labo en de leerstof gekoppeld aan het labo.
Je kan/mag de aanvullende toets steeds afleggen gebruik makend van alle bronnen (cursusmateriaal, labo, online bronnen, ...)

### **Labo 5C:** *Takenlijst*
- [ ] Open de Git Bash Console op de locatie waar je dit labo wil gaan clonen. Dit kan via een rechtermuisklik op de locatie in kwestie en vervolgens de keuze **Git Bash Here** te selecteren.

- [ ] Zorg ervoor dat de startsituatie *(deze repository)* van het labo op jouw pc **gecloned** wordt. Maak hiervoor gebruik van het passende git commando. 

- [ ] Ga **na het clonen** via de Console naar de gecloonde repository. Dit kan/mag je uiteraard ook doen door de nieuwe aangemaakt folder aan te klikken en hier opnieuw een Git Bash console te openen via de **Git Bash Here** optie.
>**Tip!** Controleer voor je verder werkt of je al dan niet in de juiste git repository zit! Je kan dit snel visueel vaststellen in je console.

In de cursus kwam de manier van werken om een GitHub page draaiende te krijgen voor je eigen user aan bod.
In dit labo ga je aan de slag om een GitHub page te voorzien voor deze repository!
Het is de bedoeling dat je hier zelf wat extra opzoek- en/of uitzoekwerk doet om te achterhalen hoe dit precies werkt.

### Deel 1: voorbereiding
Voor we zomaar aan de slag gaan met het publiceren van de GitHub page van deze repository maken we eerst de nodige voorbereiding.

- [ ] Ga **via GitHub** naar de Labels op de repository van dit labo. Verwijder alle bestaande labels. Voeg nadien twee nieuwe labels toe, deze krijgen de naam *Must Have* en *Nice to Have*. Het kleurschema voor deze twee nieuwe labels is vrij te kiezen.

- [ ] **Via GitHub** maak je een nieuwe Milestone aan in de repository van dit labo. Geef deze Milestone de naam *First launch*. Plaats de **Due date** op de dag waarop je dit labo aan het uitwerken bent.

- **Via GitHub** maak je vervolgens onderstaande issues aan:

    - [ ] **Select page template**, wijs deze toe aan jezelf, wijs de Label *Must Have* en de Milestone *First Launch* toe aan deze issue.
    - [ ] **Customise page template**, wijs deze toe aan jezelf, wijs de Label *Nice to Have* en de Milestone *First Launch* toe aan deze issue.
    - [ ] **Configure GitHub Pages**, wijs deze toe aan jezelf, wijs de Label *Must Have* en de Milestone *First Launch* toe aan deze issue.

- [ ] Maak in je lokale repository een nieuwe branch **dev** die aftakt van **master** en synchroniseer deze met de remote.

### Deel 2: ons project stap voor stap afwerken

- [ ] Voorzie een branch in je lokale repository die je de naam **feature/template-selection** geeft (afgetakt van **dev**) en zorg ervoor dat je meteen ook op deze nieuwe branch werkt.

- [ ] Selecteer een van de drie basis webpagina's die je terug kan vinden in de zip file **op Leho** in de opgave voor dit labo (zie GitHub Pages Templates onderaan de opgave).

- [ ] Na het uitpakken/unzippen van de templates, kies je een van de drie beschikbare templates. En plaats je **de inhoud** van de gekozen folder (dus alle bestanden uit de gekozen map) in het **docs** mapje in je **lokale** repository. Dit kan simpelweg met een copy/paste gebeuren.

> **Tip!** Het is de bedoeling dat de homepage *index.html* van de gekozen template rechtstreeks onder *docs* komt te staan, dus **niet** in een subfolder. We zullen verder in het labo immers de nodige configuratie toevoegen zodat het *docs* mapje de root wordt van de GitHub page van deze repository.

- [ ] Maak gebruik van passende git commando's om de nieuw(e) bestand(en) te commiten naar git. Zorg ervoor dat je lokale wijzigingen vervolgens ook op je remote repository aanwezig zijn. **Zorg ervoor dat je in je commit message een referentie legt naar je issue en gebruik tevens een keyword dat ervoor zal zorgen dat na het mergen met de master branch je issue automatisch zal afgesloten worden.**

- [ ] Zorg door middel van een Pull Request **via GitHub** dat de wijzigingen die je aanbracht in de **feature/template-selection** branch ook op je **dev** branch gemerged worden. Wijs deze Pull Request toe aan jezelf, het Label *Must Have* en de Milestone die we eerder aanmaakten.

> **Tip!** Vergeet niet om je Pull Request volledig af te werken.

- [ ] Zoek het nodige op om vervolgens je GitHub Pages voor je repository te activeren (als **publiek** beschikbare website). Zorg ervoor dat de **docs** map op de **master** branch gebruikt wordt als root van je site.

> **Tip!** Aangezien we nog niks naar de **master** branch gemerged hebben, is het normaal dat de site daar nog niet op staat en je dus een HTTP 404 (not found) error krijgt wanneer je je site wil bekijken via de publieke url. Op het einde van het labo gaan we alles mergen naar **master** en kan je finaal controleren of je site goed getoond wordt.

- [ ] Maak een pull request om je **dev** branch in **master** te mergen. Werk deze pull request af. Wijs deze Pull Request toe aan jezelf, het Label *Must Have* en de Milestone die we eerder aanmaakten.

>**Tip!** Op dit moment zouden de bestanden voor je site op **master** moeten staan. Je zou nu dus ook de website te zien moeten krijgen via de url die je terugvindt op de pagina waar je je GitHub page hebt geconfigureerd. Er kan enige vertraging opduiken tot wanneer GitHub de pagina vernieuwt, dus heb even geduld als het niet meteen werkt. Eventueel kan je een refresh forceren door de GitHub Page settings even aan te passen naar een foute instelling, en dan terug juist te zetten.

- [ ] **Verifieer dat de site goed getoond wordt op deze url.** Indien je de site niet goed te zien krijgt, zoek dan uit wat er mis is met je GitHub page instellingen en/of files onder *docs*. Los eventuele problemen op.

- [ ] Het issue **Select page template** zou nu automatisch afgesloten moeten zijn. We gebruikten hiervoor immers een gepast keyword in de bijhorende commit, die nu tot op de **master** (= default) branch geraakt is. Verifieer dat het issue inderdaad op status *closed* staat.

> Het issue **Configure GitHub Pages** zou nog open moeten staan. Hiervoor maakten we immers geen commits, maar pasten we enkel de instellingen van de remote repo aan.

- [ ] Sluit het issue **Configure GitHub Pages** manueel af.
