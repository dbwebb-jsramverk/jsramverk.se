# Specifikation

<p class="author">Emil Folino</p>



## Beskrivning

I denna delen av kursen börjar vi med att ta en titt på den befintliga koden och utvärderar frontend ramverk. Målet med denna delen är att ha en applikation som fungerar enligt specifikation och vi samtidigt tagit några beslut kring vägval inför kommande delar.

Börja därför med att skapa en fork av repot [dbwebb-jsramverk/ssr-editor](https://github.com/dbwebb-jsramverk/ssr-editor). Och sedan en branch kallat `specification` med kommandot `git checkout -b specification`.

I videorna nedan visar Emil hur man blir inbjudan till organisationen [dbwebb-jsramverk](https://github.com/dbwebb-jsramverk) på GitHub. Hur du Accepterar inbjudan och autentiserar ditt konto.

<div class='embed-container'><iframe src="https://www.youtube.com/embed/0BzEsBvBD8o?si=6_t4GQM46ikOMK6E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>

<div class='embed-container'><iframe src="https://www.youtube.com/embed/RuzoS0PXT08?si=mXiXuJUHyNHCwBTd" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>

Sedan skapar Emil en fork av repot och en branch för detta kurmoment.

<div class='embed-container'><iframe src="https://www.youtube.com/embed/_6U_LLJjYhU?si=4XSov0MCs-ZfSVyV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>



## Läsa och titta

Läs [dokumentationen](https://docs.npmjs.com/cli/v6/commands/npm-audit) för kommandot `npm audit` som utför en säkerhets genomgång av de installerade npm-moduler.

Läs introduktionen till [GitHub Flow](https://docs.github.com/en/get-started/quickstart/github-flow), som är en strategi för att samarbeta kring koden i ett repo.

Artikeln [Frontend](/frontend) introducerar frontend ramverk och går igenom olika kodexempel och jämför kodbaserna.



## Kravspecifikation

1. Skapa er en överblick över applikationen vi ska arbeta med under kursens gång. Se till att ni kan köra den med hjälp av kommandot `node app.mjs`.

1. Skapa ett gemensamt Git-repo med koden för repot. I inlämningen på Canvas länka till repot på GitHub.

1. Försök att under kursens gång jobba enligt GitHub Flow.

1. Se till att ha åtgärdat alla säkerhetshål enligt `npm audit`.

1. Skapa en `README.md` fil i repot. I denna filen kommer ni under hela kursen dokumentera olika val.

1. Beskriv i `README.md` vilka steg ni fick gå igenom för att få applikationen att fungera.

1. Implementera en `POST /update` route för att uppdatera innehåll istället för att skapa nya documents hela tiden.

1. Uppdatera vyerna så det är möjligt att uppdatera ett dokument och att skapa nya.

1. Gör ett val av frontend ramverk och dokumentera det i `README.md`. Ni behöver inte implementera något, men kan vara bra att börja titta på hur implementationen av ett frontend-ramverk kan gå till.

1. Skapa en Pull Request mot ditt egna repos `main`-branch. Se till att inte stänga denna Pull Request då vi som lärare gör det vid rättning.



## Redovisning

Svara på nedanstående frågor individuellt i en markdown fil i repot döpt till din akronym.md. Har du akronymen abcd24, blir alltså filen `abcd24.md`.

* Vilka lärdomar gjorde du dig kring ditt sätt att ta dig an kod som du inte själv skrivit?

* Var det enkelt att ta till dig information om de olika frontend-ramverken? Vilken är din uppfattning om ramverkens dokumentation?

* Vilka fördelar och nackdelar ser du med arbetssättet GitHub Flow?
