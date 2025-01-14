# Logboek2024-2025SmartApps
# week 1
  hele week bezig geweest met een groep te zoeken
  
# week 2 (3 oktober)
  hele week bezig geweest met een groep te zoeken
  

# week 3 (10 oktober)
  groep gevonden en al begonnen aan Angular workshops

# week 4 (17 oktober)
  2 uur vewrder gewerkt aan de Angular workshops<br />
  3 uur bezig geweest met het maken van de layout van de webpaginas maar er is een probleem ondervonden.
  ik kon de paginas niet inladen op de browser

# week 5 (24 oktober)
  2 uur bezig geweest met ht probleem op te lossen uitendelijk ondervonden dat het probleem lag bij google chrome en het is opgelost met een incognito tabblad.
  dan waren er ook nog problemen met libraries en modulen zoals de ngmodule maar deze zijn opgelost geraakt<br />
  5 uur beziggeweest met de apicalls te bestuderen en om te vormen naar een template hier heb ik ook even vastgezeten. Nu zijn de apicalls in een service file aangemaakt
  verder ook nog de layout wat aangepast

# week 6 (1 november)
  begonnen aan Angularfire codelab<br />
  Nagedacht over gokmodel en onderzoek naar gedaan 2 uur

# week 7 (7 november)
  1 uur simpele gokmodel gemaakt waarbij je bij winst dubbel terugkrijgt en bij verlies het aantal punten kwijtraakt<br />
  2 uur gebruikers uit firestore gehaald en deze in localstorage zetten met een bepaald puntenbedrag.<br />
  Hier zijn een paar problemen aan bod gekomen maar ik geloof dat ik deze kan oplossen aan de hand van de codelab.
  
  # week 8 (14 november)
  30 minuten aan navigatie gewerkt om een hamburger menu te maken <br />
  30 minuten user naar de localstorage met de nodige data + gokpunten<br />
  30 minuten anpassingen gedaan aan de profile pagina door gebruik te maken van de juistre user data met toevoegingen zoals het aanpassen van profielfoto en naam.<br />
  4 uur bezig geweest met het nadenken over het gokmodel te verbeteren en ook effectief het gokmodel verbeterd. Door een bt interface te maken
  en gebruik te maken van hert oude punten systeem het is ook verbonden aan een gebruiker met zijn puntensaldo. Alleen moet er nog gewerkt worden aan het verbinden van het systeem met de matych dat eindigt.
  
# week 9 (28 november)
  2 uur bezig geweest met het oplossen van problemen omtrent cloud functions aan te maken in vsc en de benodigde packages daarvoor te downloaden.<br />
  3 uur bezig geweest met een cloudfunction dat controleert wanneer de status van een match veranderd naar finished en dan ook de bets berekend wanneer de status finished is en deze dan wegschrijft via een extra veld in de user authentication maar dit wil ik veranderen naar een user in firestore zelf.<br />
  1 uur bezig geweest met het oplossen van de permanente read problem dat kwam door de functie omdat hij bij elke kleine verandering een read deed. en dan opzoekeingen gedaan en ondervonden dat je niet op een specifieke veld een trigger kunt zetten.<br />

# week 10 (5 december)
  4 uur bezig geweest met het oplossen van problemen omtrent het bijwerken van de functie uiteindelijk besloten om op een ander manier te doen anders dan cloud function op cloud function.<br />
  half uur bezig geweest met het oplossen van de functie aan de hand van een cloud function die een functie aanroept.<br />
  1 uur bezig geweest met testen van de functie en het betten.<br />

# week 11 (12 december)
 3 uur bezig geweest met het toevoegen van foutcontroles op bets en je kan niet meer betten op begonnen matches en matches dat al bezig waren.
 1 uur gewerkt aan het laten inloggen en deze ingelogde gebruiker weg te schrijven naar de firestore met extra fields zoals de betsaldo en ook naar de localstorage
 30 min testen gedaan voor zowel bets als login.

# week 12 (19 december)
1 uur gewerkt aan het effectieve wegschrijven van de bets bedragen naar user accounts en bet prediction naar winner id gezet.
2 uur bezig geweest met het optimaliseren van de bet functie om zo min mogelijk calls te maken naar en van de firestore.
1 uur beziggeweest met het maken van de bethistory page waar je kan doorklikken op de match om is te kijken.
1 uur aan testing gedaan voor alles dat hier bescheven staat.

# week 13 (9 januari)
2 uur bezig geweest met merge conflicten
2 uur bezig geweest met effectief wegschrijven van punten naar accounts aan de hand van payouts een draw feature toegevoegd om draw error te voorkomen.
1 uur bezig geweest met het oplossen van betting op games met een speler en niet teams uiteindelijk besloten om betting voor deze games te dissabelen.
1 uur bezig geweest met het weergeven van een nieuw user als hij voor de eerste keer met google inlogged als hij al bestaat word hij weergegeven.

# week 14 (13 januarie voor de deadline)
30 minuten bezig geweest met het implementeren van share api.
1 uur bezig geweest met het oplossen van komende problemen dat zich hebeen veroorzaakt bij de profile page na de login daar naar om te zetten.
30 minuten bezig geweest met save van profile ook weg te schrijven naar firebase en bettingsaldo laten zien op profile page.
8 uur bezig geweest met het implementeren van de pushnotification api met firabse cloud messaging. hiervaan 3 uur informatie opgedaan. 1 uur de firabease token geimplementeerd om permissie te vragen voor push notifiactions en deze weg te schrijven bij de user en ook de implementatie om messages te krijgen. 2 uur testing gedaan om te zien of er effectief push notifications worden gestuurd dit heb ik gedaan aan de hand van verschillende manieren deze werkten niet tot ik de test van firebase zelf heb gevonden deze was redelijk vertopt omdat ze recent zijn overgegaan naar een nieuwe manier van cloud messaging. 1 uur samen met alex de functie geimplementeerd om notificaties aan te maken en dan te versturen specifiek als een bed van een match voo een user is afgesloten. 1 uur deze functie getest maar je moet labng wachten omdat je moet wachte op een pandascore api update op die match.
links: https://www.youtube.com/watch?v=TNxJxOZWmHs , https://www.linkedin.com/pulse/integrating-firebase-push-notifications-angular-dhiki-fauzan-xijic?utm_source=share&utm_medium=member_android&utm_campaign=share_via , https://stackoverflow.com/questions/77727305/in-standalone-mode-how-to-i-import-a-module-in-angular-17 , https://firebase.google.com/docs/cloud-messaging/js/first-message

