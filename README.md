# Datenschutzerklärung & Impressum – „CashKompass“

Diese Seite gehört zur iPhone-App **CashKompass** von Elias Scherer.
Apple verlangt für die Veröffentlichung im App Store eine öffentlich
erreichbare Adresse mit der Datenschutzerklärung – dafür ist diese Seite da.

## Wenn sich etwas ändert

Der Text in `index.html` muss immer mit dem Text in der App übereinstimmen.
In der App steht er in `src/constants/legalText.ts`.

Ändere ich eine Funktion der App so, dass sie Daten überträgt, eine neue
Berechtigung nutzt oder einen fremden Dienst einbindet, muss **beides**
angepasst werden – und das Datum unter „Stand" mit.

## Wie ich den Text ändere

1. `index.html` bearbeiten
2. Änderung speichern und hochladen (`git add .`, `git commit`, `git push`)
3. Nach ein bis zwei Minuten ist die Seite im Netz aktualisiert

## Technischer Hinweis

Die Seite lädt bewusst nichts von fremden Servern nach – keine Schriftarten,
keine Symbole, keine Skripte. Dadurch verarbeitet sie selbst keine Daten der
Besucher und benötigt weder ein Cookie-Banner noch einen Abschnitt über
Server-Protokolle.
