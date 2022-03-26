# Webtechnologie
Webtechnologie Praktikum beim Meister Stiehl


Grundkonzept:
-	Lern-Mini-Spiele
-	Forum
-	Bestenlisten
-	Schnelles Spiel
-	Anmeldung/Registrierung/Kontakt/FAQ/Impressum/Benutzerverwaltung

Funktionalität:
  -	Alle Datenbankoperationen werden öfters verwendet:
      o	Suchen: Bestenliste, Benutzerverwaltung, Forum, …
      o	Lesen: alles muss aus der DB gelesen werden, …
      o	Neuanlage: Nachrichten/Threads/… im Forum, neuer Nutzer, Bestenliste, …
      o	Aktualisierung: Nachricht im Forum bearbeiten, Passwort/Name ändern, Bestenliste, …
      o	Löschen: Benutzerverwaltung, Nachricht/Threads löschen, …
  -	Profilbilder deckt alle Funktionalitäten ab (zusätzlich Daten im Forum hochladen)
  -	Beispielsweise Bestenliste mit Benutzerliste
  -	Benutzerverwaltung vorhanden

Seiten:
  -	Startseite (Hauptmenü)
  -	Bestenliste
  -	Forum als Unteranwendung
      o	Forum
      o	Threads
      o	Post erstellen
      o	Community erstellen / Trending / Merkliste / User-Einstellungen / …
  - Spieleauswahl
      o	Mathespiele / Wörtersuche / Malen nach Zahlen / Spiele auf Zeit / Schwierigkeitsgrad / …
  -	Funktionalitäten je nach Nutzer 
      o	Gast -> Schnelles Spiel
      o	Angemeldet -> Gewertete Spiele 
  -	Benutzerverwaltung
  -	Anmeldung
  -	Registrierung
  -	Kontakt
  -	FAQ
  -	Impressum

Mögliche Datenbank-Tabellen:
  -	Benutzer / User / Angestellter
  -	Bestenliste
  -	Forum, Thread
  -	Kontaktformular
  -	Spiele, Lösungen, Aufgaben, Schwierigkeiten, …
