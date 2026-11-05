# Projekt: Mboa (Arbeitstitel)

App-Idee für die afrikanische Diaspora: eine Karte mit Flechterinnen, Essen und Catering, Gemeinden und Afro-Shops. Später kommt der Njangi-Manager als Bezahl-Funktion dazu (siehe `C:\Projekte\Njangi-Manager`), und vielleicht „Leute kennenlernen“. Status: Konzeptseite im Entwurf, noch keine Entscheidung zum Bauen (Stand 05.11.2026).

## Feste Regeln
- **Eigenes Projekt und eigenes Repository, nicht mit meet-us-there vermischen** (Jörg, 05.11.2026). Hosting über eine eigene kostenlose GitHub-Organisation (vorgeschlagen: `mboa-app`), Repository `<org>.github.io`, Seite mit `noindex`.
- Wir verwalten kein Geld. Die App vermittelt nur Kontakte, Zahlungen laufen direkt zwischen den Leuten.
- Texte auf Deutsch und Französisch (Englisch folgt), alle über Übersetzungen, nichts fest im Code.
- Vor jedem Veröffentlichen Jörg fragen.

## Entscheidungen 05.11.2026
- Eintragen bleibt kostenlos. Keine Gebühr als Spam-Schutz (Jörg: „keine Zahlungen“).
- Spam-Schutz: WhatsApp-Rückwärts-Nummernprüfung wie bei meet-us-there (Nutzer schickt der App-Nummer eine Nachricht, kostenlos, offizielle Cloud API), höchstens 3 Einträge pro Konto, neue Einträge „ungeprüft“ mit automatischer KI-Prüfung, nach 3 Meldungen ausgeblendet.
- Afro-Friseursalons und Afro-Shops gehören in die Vorab-Befüllung (OpenStreetMap). Inhaber können Einträge kostenlos übernehmen.
- Geld höchstens über freiwillige Extras für Firmen (Shops, Salons) und später den Njangi-Manager. Private Anbieter und Gemeinden zahlen nie.
