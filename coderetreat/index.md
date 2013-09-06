---
layout: page
title: Code retreat
---
Symfony Sverige arrangerar en rad olika träffar för våra medlemmar. Ett sådant är *Code retreaten*.

En Code retreat är ett tillfälle då du kan fokusera på att bli en bättre programmerare. Det handlar om s.k. deliberate practice, där du medvetet tränar din programmeringskunskap, oftast över en hel dag.

Testdriven utveckling och parprogrammering är viktiga delar i Code retreaten. Två och två sitter vi ned med ett relativt enkelt problem och försöker lösa det med en förbestämd approach. T.ex. kan du fokusera på att skriva minimalt små metoder, utesluta kommentarer helt genom att namnge allt väldigt uttrycksfullt eller verkligen skriva alla tester i förväg och låta dem guida din kod.

## Conway's Game of Life

Problemet som vi försöker lösa under en Code retreat är [Conway's Game of Life](http://en.wikipedia.org/wiki/Conway's_Game_of_Life). Det är en s.k. cellulär automat; en väldigt enkel virtuell värld med enkla regler som styr livet för invånarcellerna.

Världen är ett tvådimensionellt (oftast) rutnät där varje ruta antingen är levande eller döda. Uppgiften är sedan att beräkna nästa generations rutnät med följande regler:

- Levande celler med färre än två levande grannar dör.

- Levande celler med två eller tre levande grannar lever vidare.

- Levande celler med mer än tre levande grannar dör.

- Döda celler med exakt tre levande grannar börjar leva.

När reglerna är implementerade kan man välja vilka rutor som ska vara levande/döda och därefter kör man igång beräkningarna. Resultatet kan bli något sådant här:

![Gosper's Glider Gun](gospers_glider_gun.gif "Exempel på Conway's Game of Life, in action.")

## Utmaningar

Under Code retreaten kör vi flera sessioner á 45 minuter och inför varje ny session byter vi par.

Den första sessionen kommer säkert behövas för att bekanta sig med Game of Life och fundera över hur man bäst programmerar det. Inför de följande sessionerna är det bra om du funderar över vilka utmaningar du vill införa för att träna på specifika färdigheter.

Några exempel på utmaningar kan vara:

- Ping-pong-programmering.

- Utan mus eller touchpad.

- Använd endast papper och penna.

- Inga if-satser, nakna primitiver eller loopar.

- Max fyra rader kod per metod.

- Praktisera [Object Calisthenics](http://williamdurand.fr/2013/06/03/object-calisthenics/).

Du kan säkert komma på en mängd andra utmaningar att testa. Fundera bara på vad du vill bli bättre på och utmana dig själv att levla upp!

## Avslutning

Efter varje avslutad session kör vi en retrospektiv, där vi diskuterar vad som varit bra, vad som kan förbättras, samt vilka lärdomar vi tar med oss från övningen.

Vi raderar också all kod vi skrivit. Det är ett viktigt steg — Code retreat fokuserar på programmeringen och lärandet, inte på att producera kod.

Mer information finns på [coderetreat.org](http://coderetreat.org/).
