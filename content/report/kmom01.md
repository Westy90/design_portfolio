---
Title: Kmom01
Description: Part 1
---

Kursmoment 1
===

I detta kursmoment så introducerades det ganska många grejer som jag inte var bekant med sedan innan. Dels att använda en CMS, vilket känns som det ger fördelen att man får en ganska snygg sida att börja med. Men å andra sidan så är det väldigt mycket kod och det är svårt att se hur flödet ser ut på sidan. Jag tänker tillbaka i htmlphp där det fanns ett flöde med multisidorna och det var redan då lite knepigt att förstå flödet även om man skrev det själv. Och då är det ganska mycket kod som man inte har sett sedan innan och det är svårt att sätta sig in i exakt vad den gör. Men dock så var videon ändå bra där niklas gick igenom sidan steg för steg då det gav bättre förståelse för hur det hela hängde ihop. Något annat som var nytt är detta med markdown vilket kan jag förstå säkert är väldigt lätt och nybörjarvänligt men nu när man ändå har lärt sig lite html och php så känns det som en omväg till att skriva koden...
Något jag funderade på när jag gjorde detta kursmoment är flashbilden. Det gick bra att byta ut den. Men jag blev fundersam om det verkligen är vettigt att denna ligger hårdkodad i twig-koden? Det känns som det kanske vore vettigare att behandla den som man gör med logotypen, det vill säga att filhänvisningen ligger under meta-mappen och sedan så hämtar twig-koden från metamappen, precis som körs med contentmapparna. Jag tänker mig att så lite som möjligt bör vara hårdkodat i twig-vyn? Jag gjorde dock inte någon förändring utan lät det ligga kvar hårdkodat som det var.

Däremot så ändrade jag footern som var hårdkodad i twig-filen till att istället lägga in den i _meta.md och sedan refererade jag den i index.md till den. Det känns som en bättre lösning tycker jag då, om det ska finnas flera themes så är det bara på ett ställe jag behöver ändra för att uppdatera footern för alla mallar i theme.

Gällande förutfattade meningar med webbdesign så vet jag inte. Jag tänker mig väl att webbdesignen ska stödja användaren så att den kan navigera och hitta den informationen den behöver så snabbt som möjligt. Men jag kan tänka mig att i stora bolag inom exempelvis social media så som youtube och instagram så kanske är designen gjord så att användaren ska vara kvar i applikationen så mycket så möjligt så att företaget kan dra in maximalt med reklamintäkter etc, det är alltså inte gjorda primärt gjorda för användarupplevelsen.

Jag tycker det gick bra att styla min egen layout. Dock är jag osäker om jag gjorde tillräckligt mycket. Det jag gjorde var att jag ändrade lite färger, ändrade ordningen så att github-ikonen blev till höger sidan istället för vänster och footer-texten blir till höger. Sedan ändrade jag fontstorleken på h2 då jag tyckte h1 och h2 var allt för lika. Så gjorde jag lite liknande sådana småsaker. Jag la även till ett nytt menyval för spelsamling och la till några spel där i olika listor.

Den stora utmaningen för mig i detta kursmoment var att kunna hantera github, vilket jag har haft stora problem i i andra kurser (MVC). Dock så fick jag hjälp på labbstugan och nu så fungerar den. Det är väl den stora "äntligen" känslan då jag har haft problem med github gällande nycklar men också för att förstå konceptet (som jag iofs inte förstått riktigt än heller, men är på god väg.)
