# Produktdagbok
## Gruppmedlemmar
- Berat Ukiqi
- Lisa Ryd-Carlsson
- Malek Mahfoudh

## Projektegenskaper
- En sprint är 2 veckor.
- Vi har 3 utvecklare.
- En arbetsdag är 3 Poäng - (3 utv x 1 Poäng).
- En arbetsvecka är 15 Poäng.
 
## Sprint Goal
Målet är att skapa ett robust och skalbart system som ska ha ett unikt gränssnitt där vi hanterar produkter, lånekort, sökfunktioner och integrerar bibliotekets scannrar.

## Definition of Done
Databasen är klar när vi har skapat egna databaser (produktdatabas, användardatabas) som bygger på bibliotekens tidigare databaser. Biblioteken ska ha tillgång till databaserna och kunna justera innehållet genom att lägga till, ändra och ta bort produkter samt användare. 

Sökfunktionerna är klara när användare & biblioteken kan genera sökresultat på alla egenskaperna från produktdatabasen samt att biblioteken ska kunna generera sökresultat på alla egenskaper från användardatabasen, oberoende av Versaler/Gemener.  

Scannrarna är klara när de kan läsa av lånekort samt produkter och returnera värdet till vårat system. 

Gränssnitten är klara när vi har två unika gränssnitt, ett för biblioteken samt ett för användarna. Alla administrativa funktioner ( lägga till, ändra och ta bort ) ska presenteras för användaren / biblioteken. 

Lånekort är klara när vi kan registrera en användare till kortnumret som blir kopplat till en profil. Kortet ska returnera profilens id när det scannas för att kunna hantera profilens uppgifter samt produkter.


## Händelser 

- Vi blev väldigt förvirrade över User Stories som nästan "gör samma sak" men för olika "användare". Bör man slå ihop dom, till risk att det blir epics, eller ska man bryta ner dom men då bli väldigt små User Stories. Vi märker att flera User Stories löser ut varandras inre tasks. Vi kom fram till att om två User Stories är väldigt lika, men från olika användare så slår vi ihop dom, annars formulerar vi dom bättre för att beskriva funktionen.

- Vi valde att lägga till ett custom-field på våra User stories för att kategorisera dom efter vilken "feature" de tillhör. Eftersom det var så många behövde vi bättre överblick. Nu blev det lättare för oss att prioritera ordningen då vi ser vad som tillhör vad.

- Vi gjorde en prioriteringsrangordning på Product Backloggen. Här avgjorde vi vilka moment som var tvungna att vara klara i vilken ordning. Vi kunde se hur detta steg gör nästa steg i processen enklare genom tydlig struktur i vilken ände vi ska arbeta från. Vi utgick mycket från MVP där vi tänkte vad är minimumkravet och hur förhåller sig det till nästa User Story.

- Vi gjorde första Sprint Backloggen. De flesta av våra User Stories kom med i första sprinten. Vi estimerade tiden på varje story till högst 2 arbetsdagar / poäng. När vi räknade ihop alla arbetsdagar (2 veckor) så var nästan alla User Stories klara. Det är svårt att estimera exakt hur lång tid varje moment kommer ta, men vi har gjort ett estimat för att ändå gå igenom varje del i Scrum ramverket. I detta skede kände vi att hela projektet nog troligtvis inte kommer kunna skapas inom 2-3 veckors arbete. Vi tänker nu om och lite djupare inför varje User story och ser ifall de är större än vi tänkt oss och om de kan brytas ner ytterligare.

- Vi började skriva en Definition of Done på vår ursprungliga Sprint backlog. Vi insåg att det blev väldigt mycket krav eftersom nästan alla User Stories ingick i första sprinten. Efter detta kom vi fram till att vi förmodligen har en del epic User stories och beslutade att försöka bryta ner dessa ytterligare. Får vi detta klart så innebär det att Definition of Done kan bli mer konkret och rimlig. Inkrementen blir tydligare och vi kan med nästkommande sprintar erbjuda fler. 


- När vi hade sorterat och estimerat allt i Sprint Backloggen så behövde vi omprioritera. Vi la till en egenskap som heter "Priority" där man kan välja mellan, "Must" "Should" och "Could". Här prioriterar vi nu utefter vad som verkligen krävs för vårat "MVP" eller Inkrement. Det som har MUST kommer först, därefter SHOULD, sen COULD. 
Nu blev vår lista ojämn och vi fick flytta runt User Stories återigen för att de skulle hamna i rätt prio-ordning. 

- Definition of Done var klurigt. Vi undersökte hur noggrannt vi behövde specifiera kraven. Vi gick inte för djupt in på tekniska specifikationer, men såg ändå till att det som verkligen behövs var specifierat. Varje "feature" presenterade vi i en lista där vi skrev kraven för just den. Möts inte allt i "feature"-kravet så presenterar vi inte denna vid Sprint Reviewen och den hamnar i Product Backlog.



