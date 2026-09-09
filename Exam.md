Del 1 Analysera en teknisk lösning



1.Hållbarhet

\-Tjänst: Spotify



**-Hur används resurser:**

Databaser-Användarnamn, spellistor bibliotek, likes, följare, historik, abonnemang, skapa.

API-Mobilen/webbapp som skickar requests tex get post search.
Server/Cloud-Kör själva backend logiken och hanterar miljontals användare samtidigt.
CDN/cache-Placerar innehåll närmare användaren så att allt flyter på bättre, musik, videos, poddar, ljudböcker, bilder laddas upp snabbt.

Objekt lagring-Musik video filerna, bilder ligger i stora lagrings system inte som vanliga databasrader.

Autentisering-Login, tokens, lösenord, behörigheter och sessions hantering.

Söktjänster-För att snabbt hitta det du vill hitta eller höra.

Rekommendation system-Analys system som hittar din typ av musik genom att jämföra changerar, skapar rekommendationer.

Event/JAM/Köer-Enorma mängder av händelser, tex din vän lyssnade nyss på det här! Kolla in!

Lyssna tillsammans över nätet så ni hör samma låt samtidigt. Eller spela upp från fler enheter i samma rum tex.

Loggning/monitorering-Backend behöver hitta problem eller ta hand om problem, hitta fel eller  lösning om det skulle gå långsamt.

Socialt- tex meddelanden och se vad vänner lyssnar på eller lyssnat.

AI tjänst-Som jag upptäckte nu i måndags ska kolla mer in på den senare.



**-Utveckla hållbarhet:**

Ingenting jag själv direkt stör mig på vid användning.

Tycker det flyter på bra trots att det är otroligt många som använder tjänsten samtidigt.

Ev bara att skydda information bättre så att hackare inte kan ta sig in eller på nåt sätt stjäla information men det är ju bara förebyggande isf.

Annars så inget rakt på som jag tänker det här borde dom göra bättre.

Isf kanske något helt nytt i en ny riktlinje men som sagt är otroligt nöjd med som den är.







**2.Säkerhet**

\-Vilken typ av data använder tjänsten:

Hanterar musik data, användardata, historik, sök data, rekommendationer, betal data,

tekniska loggar.



**-Vilka säkerhets åtgärder tror jag det finns:**

Säkerhet vid inlogg, säkerhet kring privat information, säkerhet kring betal medels information, säkerhet om tjänsten skulle stöta  på tekniska problem så den inte står stilla, teknisk säkerhet kring inlogg privat info och betal så allt är smidigt snabbt och lätt för användaren.



**-Finns det risker:**

Finns väl alltid risker för kraschar, att info kan läcka, brand i serverhall, data intrång, kapning, attacker, API nycklar kommer på vift, buggar,

finns en hel del man kan tänka på som kan gå fel. Därför dom har folk som jobbar med detta dygnet runt, runt om i världen.

Det är nog mycket större risker med betal och betal information än vad man tror, det är väl det som kunderna är mest rädda över att bli av med.





**Del 2 - Pseudokod**



\-G nivå-Split the nota



Start

Läs in summa
Läs in antalVänner

Läs in dricks



totalSumma = summa + (Summa \* dricks)

perPerson = totalSumman / antalVänner



skriv ut perPerson

Stop





**-VG nivå-Bibliotekssystem**



Start



Fråga "Vill du låna en bok eller flera"



Om "Ja"

sökSkriv "Bokens Namn"

kontrollera om den finns

&#x09;om ja

&#x09;om nej ny sökning

kontrollera antalet "lånade böcker"

&#x09;om 1 sök igen

&#x09;eller välja avsluta program

kontrollera om man antal mindre än "2"

&#x09;



isf markera som utlånad



annars

&#x09;kontrollera om mer än 2 böcker lånade svara "Du har lånat 2"

&#x09;Skriv ut "maxgräns nåd"



Slut om

annars

&#x09;Skriv"Boken finns inte"



Slut om

ananrs

&#x09;Skriv "Programmet avslutas"

Stop





**Del 3 - Reflektion**



**-Efter två veckor på utbildningen:**

Rollen som utvecklare är jätte intressant lite av ett intresse som jag aldrig kollade in mer på för länge sen känns lite som det blir lättare för att det verkar vara lite roligt med sådär halvt eller hur jag ska förklara.
Jag är ju en sån som ska lösa alla problem oavsett hur lång tid det tar jag kanske gräver ner mig lite men ger aldrig upp så på så sätt är det väl bara bra. Känner också att jag har många idéer om vad man kan förbättra på olika ställen, kanske är det mina idéer som driver mig framåt det eller att jag vill lösa grejer.

Sen när jag börjat komma in i kodningen på riktigt så vet jag att inget kommer stoppa mig oavsett vad man gör så blir man bra på det allt man behöver är sin tid.

Samma med allt man gör så tänker jag iaf.

Är allmänt glatt överraskad på hur nice backend verkar vara.

Känns som intresset bara växer.



**-Hur tror du AI kommer påverka yrkesrollen de kommande fem åren?**

Med tank på hur fort det går så är det jätte svårt att säga men jag tror att vi har börjat närma oss en fas där ai kanske saktar ner lite, det är redan mycket som är inlärt och ja den lär sig än men all information har redan gått in ska väl bara vara om det dyker upp helt nya områden eller saker som inte lästs in innan.
Jag tror med att det kommer mer program som hjälper vanliga människor att göra saker lättare för dom okunniga. Känner mig inte rädd för det heller vi som vi kommer ju ändå att behövas för vi blir fler människor och det kommer komma nya system som ska sättas upp eller liknande. Kommer alltid finns problem som ska lösas och alla kan inte göra allt med ai tror jag. Men ai är ett starkt hjälpmedel det kortar ju ner all tid gör oss effektivare.

&#x20;

