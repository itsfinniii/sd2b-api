# SD2B Discord API

### Servers

| Adres          | Naam          | Extra informatie                             |
| -------------- | ------------- | -------------------------------------------- |
| itsfinniii.com | Eigen website | Hoort 24/7 aan te staan, kan wat traag zijn. |



### Cache

De API gebruikt een cache, zodat extreme overbelasting met de Discord API niet mogelijk is. De Discord Bot haalt alle informatie die in de API hoort op, en zet dit in JSON bestanden.

De cache wordt elke 30 seconde herladen, dus het is altijd vers. Ook heeft elk endpoint een "cached" integer. Dit integer staat voor het unix epoch timestamp, ook wel bekend als het unix timestamp. Dit is de hoeveelheid seconde na 1 januari 1970 00:00 in de UTC tijdzone. Als je meer wilt weten, zie de links hieronder:

https://en.wikipedia.org/wiki/Unix_time
https://www.unixtimestamp.com/



### Hoe kom ik bij een API?

In elke taal is het anders. Ik heb een ander document gemaakt waarin voorbeelden staan over hoe je in populaire talen een request maakt.



### Responsecodes

De API maakt ook gebruik van response codes. Je kan deze codes in meerder talen bekijken, maar dit gaat in elke taal net wat anders.



### JSON Endpoints

#### /api/sd2b/endpoints.json

Keert alle endpoints van de API terug.



#### /api/sd2b/members.json

Keert alle gebruikers in de guild terug.



#### /api/sd2b/member/{discordid}.json

Keert een gebruiker terug, met dezelfde informatie als */api/sd2b/members.json*.



#### /api/sd2b/emotes.json

Keert de links van alle emotes in de server terug, inclusief de naam.



#### /api/sd2b/guild.json

Keert alle informatie over de guild terug.