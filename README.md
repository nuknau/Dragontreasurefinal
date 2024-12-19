# Dragontreasurefinal
Översikt
Dragon treaure √§r ett ävventyrsspel implementerat på neatbeans (Java). Syftet med denna uppgift är att utveckla ett spel där en spelare kan navigera i en dungeon. 

Klasser
Vi har skapat fem klasser; Door, Dragontreasure, Dungeon, Player och Room. Spelet är på engelska.

Antaganden
-dörrarna är direkt kopplade mellan rummen (därför finns det bara en dörr mellan varje rum)
-om man råkar gå ut från the dungeon genom rummet som har en exit symbol förlorar man 
-för att vinna räcker det att komma in i rum 6 och välja att slåss mot draken
-spelaren talar sanning om den har hittat/ej hittat nyckeln i rum 3
-spelaren har rätt att få se en karta över the dungeon i början av spelet
-metoden setupgame får ha andra returtyper än void
-Klassen Door behövs inte eftersom vi löst det på andra sätt i den här delen av uppgiften
-isLocked behövs inte eftersom vi löst det på andra sätt i den här delen av uppgiften
-Metoden storyLine() används för att välkomna spelaren

Spelstruktur
-spelaren börjar i rummet med ljusstakar
-spelaren navigerar genom dörrarna i varje rum
-målet är att hitta skattkistan

