# 30-clean-architecture-bulletpoints

## Clean Architecture är ett arkitekturmönster som delar upp en applikation i olika lager för att göra koden enklare att underhålla, testa och vidareutveckla.



## 1 Domain-lagret innehåller systemets kärna, såsom affärsregler, entiteter och logik, helt oberoende av externa tekniker.

## 2 Application-lagret hanterar applikationens användningsfall och styr hur affärslogiken ska användas.

## 3 Infrastructure-lagret ansvarar för externa tjänster som databaser, filhantering och kommunikation med andra API:er.

## 4 Presentation-lagret hanterar användargränssnittet, exempelvis genom ASP.NET Core MVC, Blazor eller Web API.

Dependency Rule är den viktigaste principen och innebär att beroenden alltid ska peka inåt mot systemets kärna, aldrig utåt.



Den största fördelen med Clean Architecture är att vi kan byta exempelvis databas eller användargränssnitt utan att behöva ändra systemets centrala affärslogik.
