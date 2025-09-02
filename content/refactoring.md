# Refaktorering

<p class="author">Emil Folino</p>


## Beskrivning

Nu börjar vi programmera på riktigt. Vi ska byta databas för backend och vi ska implementera ett frontend-ramverk. Vi tittar på tester för att enklare kunna refaktorera och avslutar med att driftsätta vår databas i MongoDB Atlas, backend i Azure molnet och frontend på studentservern.



## Läsa och titta

Använd resursen [Refactoring Guru](https://refactoring.guru/) för att skaffa er en överblick kring refaktorering.

I artikeln [Express](express) tar vi en kort titt på hur vi kan använda Express för att skapa ett API som svarar med JSON data.

I artikeln [MongoDB](mongodb) tar vi en titt på hur vi kan använda den dokument-orienterade databasen MongoDB tillsammans med Express API:t för att spara undan data.

I artikeln [Driftsättning](deploy) tittar vi på hur vi kan driftsätta frontend, backend och databasen på tre olika platser i molnet.

I artikeln [Test](test) tittar vi på hur vi kan säkerställa funktionalitet genom testning av backend och frontend. Och vi implementerar en CI-kedja med GitHub Actions.

Under kursmomentet bör ni arbete enligt GitHub-flow med `branches` och Pull Requests och merges mot den egna main-branchen. Vid inlämning skapar ni en ny branch `git checkout -b refactoring`, som används för inlämnings Pull Request, som en lärare merger vid rättning.



## Kravspecifikation

1. Byt ut från en SQLite databas till MongoDB för backend. Och gör om så API:t svarar med JSON-data istället för olika vyer.

1. Implementera frontenden med samma funktionalitet som i den befintliga appen fast i ett JavaScript ramverk. Frontend bör skapas som en fristående SPA i ett eget repo.

1. Implementera tester för att säkerställa funktionalitet under tiden ni gör refaktorering.

1. Skapa en CI-kedja med hjälp av GitHub Actions.

1. Driftsätta frontenden via GitHub Pages enligt [instruktionerna](deploy) och backenden samt databasen i "molnet" enligt [instruktionerna](deploy).

1. Lämna in länkar till de driftsatta applikationerna i README.md.



## Redovisning

Svara på nedanstående frågor individuellt i din akronym.md och lämna in genom en Pull Request på GitHub. Se till att länkarna till de driftsatta applikationerna finns som en del av README.md filen.

* Vad är din initiala upplevelse av dokument-orienterade databaser kontra relationsdatabaser?

* Vilka lärdomar har du gjort kring refaktorering och vilka strategier tycker du fungerar bra?

* Vilka fördelar och nackdelar ser du med JavaScript ramverken för frontend?

* Vilka fördelar och nackdelar ser du med arbetssättet GitHub Flow nu efter att ni jobbat lite mer på riktigt?
