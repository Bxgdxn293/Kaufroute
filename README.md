# Kaufroute

Einkaufslisten-Web-App, die deine Liste automatisch nach Abteilungen im Laden sortiert. Läuft im Browser auf Handy und PC und lässt sich auf den Homescreen legen.

**Live:** https://kaufroute.netlify.app/

## Funktionen

- Artikel frei eintippen, auch mehrere auf einmal mit Komma getrennt
- Ein Tipp sortiert die Liste nach Abteilungen (Obst & Gemüse, Milch, Drogerie …)
- Wird ein Artikel einer anderen Abteilung zugeordnet, merkt sich die App das
- Mehrere Listen, z. B. für Kaufland und Hornbach
- Abhaken beim Einkaufen mit Fortschrittsanzeige

## Aufbau

Die ganze App steckt in einer einzigen Datei: `index.html` (HTML, CSS und JavaScript). Es gibt keinen Build-Schritt und keine Abhängigkeiten.
Die Listen werden im Browser gespeichert (`localStorage`), also nur auf dem jeweiligen Gerät. Geteilte Listen brauchen später einen Server (z. B. Firebase oder Supabase).

## Lokal starten

`index.html` einfach im Browser öffnen.

## Veröffentlichen

Auf Netlify: Projekt mit diesem Repository verbinden (Build-Befehl leer lassen, Publish-Ordner `/`). Danach geht jede Änderung auf GitHub automatisch online.
