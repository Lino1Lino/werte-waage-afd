# Die digitale Werte-Waage

Eine eigenständige, datensparsame Web-Anwendung zur Sach- und Werturteilsbildung in der gymnasialen Oberstufe, Beispiel: „Soll gegen die AfD ein Parteienverbotsverfahren eingeleitet werden?“

## Nutzung

- `index.html` im Browser öffnen. Internet ist für die Arbeit mit der Anwendung nicht erforderlich (externe Rechtsquellen benötigen Internet).
- Nach der Pro-Kontra-Debatte eigene Kriterien eintragen, Argumente abwägen, vier Rückfragen beantworten, Urteil formulieren.
- Unter **Ergebnis** → **Als PDF speichern / drucken** den Browserdialog öffnen und **Als PDF speichern** wählen. Dies ist ein Browser-PDF-Export, keine externe PDF-Bibliothek.
- Alternativ Ergebnis als `.txt` sichern.

## Berechnung der Waage

Für jedes der acht Kriterien wird seine Wichtigkeit (1–5) mit dem **Durchschnitt** der Tragfähigkeit (1–5) der eingegebenen Pro-Argumente multipliziert. Analog für die Kontra-Argumente. Damit bewirkt das bloße Wiederholen vieler gleichartiger Argumente innerhalb eines Kriteriums keine automatische Erhöhung des Gesamtgewichts. Unklare und leere Argumente werden nicht gezählt. Alle Werte sind subjektive Schülerangaben und kein juristisches Urteil oder Wahrscheinlichkeitswert. Die Schüler*innen formulieren das Gesamturteil eigenständig und müssen der Waagenanzeige nicht folgen.

## Datenschutz / technische Voraussetzungen

- Keine Anmeldung, keine Analytics, keine Cookies, keine serverseitige Speicherung, keine externen Abhängigkeiten.
- Eingaben werden nur im geöffneten Browser-Tab im Arbeitsspeicher gehalten, nicht dauerhaft gespeichert. Beim Schließen/Neu-Laden gehen sie verloren. Ergebnisse vorher exportieren.
- Keine echte Sprach-KI: Die Rückfragen werden auf Basis der strukturierten Eingaben regelbasiert ausgewählt. Freitexte werden nicht automatisiert faktisch bewertet.

## GitHub Pages

1. Neuen öffentlichen Repository-Ordner anlegen und alle Dateien dieses Pakets ins Repository-Stammverzeichnis (`root`) hochladen.
2. Unter **Settings → Pages** die Option **Deploy from a branch** auswählen, Branch `main` und Ordner `/(root)` auswählen, speichern.
3. GitHub Pages veröffentlicht anschließend die `index.html` unter der angezeigten Pages-Adresse. Der `.nojekyll`-Marker verhindert unnötige Jekyll-Verarbeitung.
4. Link oder QR-Code an die Klasse verteilen. Die Anwendung ist lokal ebenso nutzbar.

## Lehrkraft-Hinweis

Die Anwendung ersetzt weder Recherche noch juristische Prüfung. Rechtliche Grundlagen vor Verwendung mit der aktuellen Lage abgleichen. Die acht Kriterien werden im Unterricht gemeinsam erarbeitet und sind absichtlich nicht vorbefüllt.
