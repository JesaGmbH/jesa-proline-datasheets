# ProLine PET-CF — Slicer-Profile

Erprobte Slicer-Profile für **ProLine PET-CF**, direkt aus der Fertigung der Jesa GmbH.  
Das sind die Einstellungen, mit denen wir selbst drucken — kein theoretisches Profil, sondern getestet im täglichen Einsatz.

---

## Verfügbare Profile

| Drucker | Düse | Material | Datei |
|---------|------|----------|-------|
| Bambu Lab X1 Carbon | 0.4 mm | PET-CF Schwarz | `JESA ProLine PET-CF Schwarz @Bambu Lab X1 Carbon 0.4 nozzle.json` |

Weitere Drucker- und Düsenkombinationen folgen. Profil für deinen Drucker fehlt? → siehe unten.

---

## Installation (Bambu Studio / OrcaSlicer)

1. Auf die `.json`-Datei oben klicken → rechts oben auf **Download raw file** (Download-Icon).
2. In Bambu Studio bzw. OrcaSlicer: **Filament-Einstellungen → Importieren** → die heruntergeladene Datei auswählen.
3. Vor dem Druck prüfen: Drucker, Düsendurchmesser und Düsenmaterial (gehärteter Stahl bei PET-CF Pflicht) müssen passen.

---

## Vor dem Druck — Filament trocknen

PET-CF zieht Feuchtigkeit aus der Luft. Feuchtes Filament = schlechte Schichthaftung, Blasen, sprödes Teil. Das Profil hilft dir nichts, wenn das Material nass ist.

- **Vortrocknen:** 90–100 °C, mindestens 12 h (Heißluftofen oder Filament-Trockner)
- **Nach dem Druck (optional):** Tempern bei 120 °C, 8 h — erhöht Festigkeit und Hitzebeständigkeit spürbar

Vollständige Druckparameter und mechanische Kennwerte stehen im Datenblatt.

---

## Hinweis zu den Profilen

Die Profile sind ein **erprobter Startpunkt** — kein Garant für perfekte Ergebnisse auf jedem Drucker. Düse, Bauplatte, Umgebungstemperatur und die Geometrie deines Teils beeinflussen das Ergebnis. Empfehlung: erst ein kleines Testteil drucken, dann das eigentliche Bauteil.

---

## Profil für deinen Drucker fehlt?

Schreib uns kurz, welchen Drucker und welche Düse du einsetzt — wir priorisieren danach, welche Profile als nächstes kommen.

**Kontakt:** https://shop.jesa-gmbh.de/pages/contact

---

## Mehr zu ProLine PET-CF

- 📄 **Datenblatt:** https://github.com/JesaGmbH/jesa-proline-datasheets/blob/main/PET-CF/ProLine%20PET-CF%20Filament.pdf.pdf
- 🛒 **Material kaufen:** https://shop.jesa-gmbh.de/products/proline-pet-cf-filament?variant=53457895555336
- 📂 **Profile für andere Materialien:** https://github.com/JesaGmbH/jesa-proline-datasheets/tree/main
