# Canvas LMS Bouwer (CLB)

Modules klaarzetten en exporteren naar Canvas, per opleiding in een eigen map.

- Startpagina: `index.html` (lijst uit `opleidingen.json`)
- Per opleiding: `<map>/` is het portaal voor studenten, `<map>/beheer/` is de CLB voor het ontwikkelteam
- Inloggen op de CLB: GitHub-gebruikersnaam en een fine-grained persoonlijke sleutel met **Contents: Read and write** op deze repository
- Publiceren in de CLB schrijft `<map>/content.json` in deze repository; GitHub Pages zet het binnen een paar minuten live
- Gedeelde sjablonen staan in `sjablonen/`

Hier staan geen gegevens van studenten: voortgang blijft in hun eigen browser.
