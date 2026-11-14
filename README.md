# People Search NL

Nederlandstalige donkere zoekhulp voor openbare nieuws-, overheids-, organisatie- en professionele bronnen.

## Webversie
Open `index.html` in een browser. Publiceren kan via GitHub Pages: **Settings → Pages → Deploy from a branch → main → /(root)**.

## Android APK
De Android-app laadt dezelfde HTML lokaal in een WebView. Na een push naar `main` bouwt GitHub Actions automatisch een debug-APK.
1. Open het tabblad **Actions** in deze repository.
2. Open de workflow **Build Android APK**.
3. Open de geslaagde run en download het artifact **People-Search-NL-debug**.
4. Pak het ZIP-bestand uit en installeer `app-debug.apk` op je Android-toestel.

## Privacy en beperkingen
- Minimaal twee van de vier velden (voornaam, achternaam, plaats, foto) moeten ingevuld zijn.
- De foto wordt alleen lokaal als voorbeeld getoond; de app uploadt of doorzoekt die niet en gebruikt geen gezichtsherkenning.
- Zoekopdrachten openen externe zoekmachines. De app scrapt geen sites en verzamelt of bewaart geen personenprofielen.
- Gebruik alleen rechtmatig openbare informatie voor professionele, journalistieke, organisatorische of andere legitieme publieke context.
- De app zoekt niet naar privé-adressen, telefoonnummers, privé-e-mailadressen, familiegegevens, afgeschermde profielen of privéfoto's.
- Naamgenoten kunnen voorkomen; controleer de context en bron zelf.

## Ontwikkeling
Android namespace/applicationId: `nl.peoplesearchengine`; minSdk 23; compileSdk 35; Java 17.
