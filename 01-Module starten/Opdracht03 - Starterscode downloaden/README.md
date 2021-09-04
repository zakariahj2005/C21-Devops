## Starterscode downloaden

## Uitleg

Bij de meeste programmeer modules in Canvas krijg je per opdracht starterscode aangeleverd. 

Dit kunnen lege bestanden zijn maar soms krijg je ook al bestaande code aangereikt die je dan vervolgens moet aanpassen. 

We gebruiken binnen de opleiding Git en Github om starterscode beschikbaar te maken. Dit zijn dezelfde systemen die je later in het werkveld als Software Developer zal tegenkomen.

> Weet je nog? **_Git_** is de software die je op je laptop hebt geinstalleerd om met versiebeheer te kunnen werken. **_Github_** is de dienst die ervoor zorgt dat je online kan samenwerken tijdens het ontwikkelen van software. 

Een verzameling van bestanden met programeer code die je beheert met versiebeheer software zoals Git noem je een **_repository_**. Elke programeer module in Canvas heeft een overeenkomende repository op Github met daarin de starterscode. 

In deze opdracht gaan we ervoor zorgen dat deze repository (met daarin de starterscode) die bij een module hoort wordt gedownload op je laptop zodat je er in VS Code mee kunt werken. 

> Later in deze module krijg je verder uitleg over Git, Github, repositories en hoe je je gemaakte werk kunt inleveren op Github, voor nu is het belangrijk dat je de starterscode lokaal op je laptop krijgt zodat je de volgende opdrachten kunt maken in VS Code.

## Leerdoelen

1. Ik kan een **fork** maken van een repository met starterscode vanuit de Amstelland Github account.
2. Ik kan een **clone** maken van een repository met starterscode vanuit mijn eigen Github account.

## Opdracht

1. Ga naar [de Devops repository](https://github.com/Amstelland-Software-Development/C21-Devops) op de Amstelland Github account.
2. Zorg dat je bent ingelogd met je eigen account.
3. Klik op de fork knop rechtsboven 
   > Er wordt nu een kopie gemaakt van de repository van de Amstelland Github account naar je eigen account. Dit gebeurt volledig online op Github.com.
4. Klik op je profiel icon rechtsboven en selecteer "Your Repositories" om naar de repository overzichtspagina te gaan van je eigen account.
5. Als het goed is zie dat er een C21-Devops repository in de lijst staat. Open deze door op de naam de klikken.
6. Klik op de groene Code knop en kopieer de link naar de repository
   > De link heeft als formaat: "https://github.com/_accountnaam_/C21-Devops.git"  
   > LETOP!: Dit is **_NIET_** de juiste link: https://github.com/Amsteland-Software-Development/C21-Devops.git. Als je deze link gebruikt dan download je wel het lesmateriaal naar je laptop maar kun je later geen eigen werk inleveren. Zorg er dus voor dat je je eigen Github gebruikersnaam terugziet in de link!
7. Open VS Code
8. Als het goed is heb je een map aangemaakt binnen OneDrive voor al je werk. Open deze in VS Code door uit het File menu te kiezen voor Open Folder en naar de juiste map te navigeren.
   > Als nog geen map hebt aangemaakt binnen OneDrive doe dit dan door rechtsonder in windows te klikken op het OneDrive ikoon en te kiezen voor "Open your Onedrive ... folder". Kies vervolgens voor de New Folder optie onder het File tabblad in Windows Explorer. Geef bij voorkeur een simpele naam aan de map zoals b.v. **Modules**.
9. Als het goed is heb je in VS Code de (eventueel net aangemaakte) map in je OneDrive geopend. Kies uit de menubalk bovenaan de optie Terminal > New Terminal. Binnen VS Code verschijnt er nu onderaan je scherm een optie om tekst in te voeren. Voer hier het onderstaande commando in en druk op enter.
    ```command
    git clone <link>
    ```
    > LETOP: in plaats van \<link> voer je hier de link in die je gekopieerd hebt op Github. Gebruik hiervoor de toets combinatie CTRL-V of klik met je rechtermuis knop in het terminal veld.
10. Als het goed is wordt je gevraagd om je Github account gegevens in te voeren. Doe dit. Als het goed gaat zie je in je terminal informatie over de voortgang van het downloaden.
    > Allemaal gelukt? Je ziet nu links in de Explorer van VS code de starterscode staan in een niuewe map genaamd C21-Devops. Als je dit niet ziet, klik dan op het bovenste ikoon in de vertikale actionbar aan de linkerkant van je scherm in VS Code. (of gebruik de sneltoets CTRL-SHIFT-E).
11. Je hebt nu de startercode die hoort bij deze module gedownload op je laptop.
    > Dat is wat git clone doet: de inhoud van een repository (in dit geval starterscode) downloaden van je eigen Github account naar je laptop.  
12. Een laatste toelichting: Je gaat met heel veel verschillende modules aan de slag en het is belangrijk dat je nauwkeurig werkt. Het komt soms voor dat studenten hun na een vakantie even niet meer weten in welke map ze nou aan het werk waren. Om dit te voorkomen: zorg ervoor dat je alle modules (tenzij anders vermeld) download (via het `git clone` commando) in de **Modules** map op je OneDrive.


## Eindresultaat

1. Een map in OneDrive genaamd Modules met daarin een map genaamd C21-Devops met de starterscode voor deze module.


## Bronnen
