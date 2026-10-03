# Mein Kochbuch (PWA)

Dateien: `index.html` (die App), `manifest.webmanifest` (Installationsdaten), `sw.js` (Offline-Betrieb), drei Icons.
Alle Dateien müssen im selben Ordner liegen.

## Veröffentlichen mit GitHub Pages (kostenlos)

1. Auf github.com ein Konto anlegen oder anmelden.
2. Oben rechts auf „+" und „New repository". Name z. B. `kochbuch`, Sichtbarkeit „Public", Haken bei „Add a README" weglassen, dann „Create repository".
3. Im neuen Repository auf „uploading an existing file" klicken, alle Dateien aus diesem Ordner hineinziehen (nicht den Ordner selbst, sondern den Inhalt) und unten „Commit changes" wählen.
4. „Settings", dann „Pages". Bei „Branch" `main` und `/ (root)` wählen, „Save".
5. Nach ein bis zwei Minuten steht dort die Adresse, meist `https://DEINNAME.github.io/kochbuch/`.

Hinweis: Bei „Public" ist die Seite für jeden mit dem Link erreichbar. Deine Rezepte liegen aber nicht dort, sondern nur auf deinen Geräten.

## Auf dem Android-Gerät installieren

1. Adresse in Chrome öffnen (nicht in einer eingebetteten App-Ansicht).
2. Menü (drei Punkte), dann „App installieren" oder „Zum Startbildschirm hinzufügen".
3. Das Kochbuch startet dann als eigene App und funktioniert auch offline.

## Rezepte aus der bisherigen Testversion übernehmen

In der alten Version auf „Sichern" tippen, die Datei speichern. In der neuen App auf „Laden" tippen und die Datei wählen.

## Gut zu wissen

- Die Rezepte liegen im Browser des jeweiligen Geräts. Handy und Tablet sind nicht automatisch synchron. Mit „Sichern" und „Laden" überträgst du sie, und das ist auch dein Backup. Sichere regelmäßig, besonders vor dem Löschen von Browserdaten.
- Wenn du an der App etwas änderst, erhöhe in `sw.js` die Zahl bei `VERSION` (z. B. `kochbuch-v2`), sonst behalten Geräte die alte Fassung.
