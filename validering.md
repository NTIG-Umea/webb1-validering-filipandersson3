# HTML
* Ändrade encodingen av HTML till UTF-8, som är standarden för webben. Annars så visas inte å, ä och ö.
* Lade till # framför länkarna på sidan så att det går att klicka på dem för att ta sig till id="1,2,3,4 och 5" på sidan. # behövs för att visa att du länkar till en id på sidan.
* Ändrat namnet på sidan till "Döda fallet". Det namn som visas för fliken.
* Fixat så att rubriken faktiskt är centrerad. Måste använda style="" eller CSS för att ändra hur texten ser ut.
* Fixat typo för h3.
* Fixat årtalet. För att skriva ett årtal i HTML måste man skriva det som "1796" inte "17960000".
* Fixat p element inuti p element.
* Gjort så att listan inte slutar innan den börjat och typo med stort I på li och så att länken slutar med ett ". Bara slarvfel eftersom andra element på sidan är skrivna rätt, så behöver inte förklaras.
* Kommentar måste avslutas, annars blir resten av texten en kommentar.
* Fixade länk som inte avslutades. Viktigt att komma ihåg att alltid avsluta element som inte är bilder i HTML.
* Lade till p element där det saknades.
* Fixat läsbarheten genom att strukturera upp koden så att p elementen inte fortsätter hur långt som helst åt höger. Fixade också indentationen.
* Fixat time datetime="" på samma sätt som innan. Antar att du bara vill ha time element på vissa datum så fixade bara till de som du hade lagt till sedan innan.
* Validateade HTML och fick 9 errors.
* Fixat character encoding till UTF-8. Behövde bara skriva till charset="UTF-8" inuti meta för att det ska visas att det är UTF-8.
* Lade in länkarna under ul in i li så att listan fungerar korrekt.
* Behövde flytta ner charset="UTF-8" till en ny meta.
* Alla bilder måste ha en alt ifall bilden inte visas.
* Width på bilder ska bara innehålla siffror utan enhet.
* Tog bort linebreak mitt i en länk (mitt fel).
* Fixade så att linjen under "Geologiska förutsättningar" inte går genom bilden. Gjorde detta i HTML så att jag inte måste göra en ny class i CSS för att det var en så liten förändring som bara behövdes för detta elementet.
* Ändrade längden på linjen till px för att det ska fungera för olika skärmar.
* Ändrat stor bokstav till liten. Länken fungerar annars inte på Pages.
# CSS
* Stängde parantes vid font-family. Samma anledning som för HTML.
* Gjorde länken till bakgrundsbilden relativ så att den laddar in rätt.
* Fixade typo för padding-top.
* Fixat så att > är åt rätt håll.
* Lade till enhet för margin-bottom.
* Tog bort .footer för att den användes inte.
* Förbättrade läsbarheten genom att göra bakgrunden mindre genomskinlig.
* Tog bort punkten framför h2 för att det inte är en class.
* Ändrade färgen och tjockleken på länkar så att det är lättare att läsa dem.
* Validateade och fick 1 error.
* Fixade enhet för font-size.
* Lade till en ny class "navbaritem" och tog bort punkterna framför alla items i listan. Gjorde också så att de hamnade bredvid varandra och ändrade typsnittet och ändrade färgen.
* Lade till padding till navbar.
# Övrigt
* Minskade bildstorleken till under 1 MB så att sidan laddar snabbare.
