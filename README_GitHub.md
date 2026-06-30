# 🧭 Reflexions-Navigator

Ein leichtgewichtiges Tool, das Teamleitungen nach einer Teamübung die passenden, fachlich sequenzierten **Reflexionsfragen** liefert – ohne Trainerausbildung durchführbar. Statt einer „100-Fragen-Wand" führt der Navigator durch wenige, gut gewählte Fragen je Phase.

Entstanden für pädagogische Teams (Kita / Schule / Sozialpädagogik). Marke: **GetCon** (Teambuilding, Erlebnispädagogik, Resilienz).

## Was es kann

- **13 Themen** (z. B. Vertrauen, Kommunikation, Konflikt, Kooperation, Resilienz, Teamstimmung) mit insgesamt **121 kuratierten Fragen**.
- **4-Phasen-Bogen** je Thema: Öffnen → Verstehen → Ressourcen → Transfer. Das Tool zeigt immer nur die Fragen der aktiven Phase.
- **Drei Nutzungsphasen:** Vorbereitung · Live-Beobachtung (mit privaten Notizen) · Reflexion.
- **Fragen einzeln auswählbar** mit Notiz je Frage; nur Gewähltes landet in der Team-Zusammenfassung.
- **Quellen-/Herkunft-Hinweis** je Frage: ehrliche Trennung von *Methodenherkunft* und (nur wo nötig) *wissenschaftlicher Quelle*.
- **Dark Mode**, Schritt-Navigation, Teilen-Funktion.

## Datenschutz

Alle Notizen bleiben **lokal auf dem Gerät** (Browser-Speicher), es findet **kein Datenaustausch** statt. Private Live-Beobachtungsnotizen der durchführenden Person werden **nie** geteilt.

## Nutzung

Es ist eine **einzelne HTML-Datei** – kein Server, keine Installation, keine externen Abhängigkeiten.

1. `reflexions-navigator.html` im Browser öffnen (Desktop oder mobil).
2. Thema wählen, durch die Phasen klicken, passende Fragen antippen.

## Status

🚧 **In Entwicklung.** Die Fragen sind kuratiert und quellen-geprüft, befinden sich aber noch im fachlichen Freigabe-Prozess. Die Universal-Einstiegs-/Transfer-Pools sind als Entwurf hinterlegt.

## Technik

Single-File HTML/CSS/JavaScript. Fragen liegen als strukturiertes Daten-Array (`THEMEN`) im Dokument – Konvertierung nach JSON/CSV ist dadurch leicht möglich.

---

*Fachliche Grundlagen u. a.: Kolb (Erfahrungslernen), Gibbs (Reflexionszyklus), lösungsfokussierte Kurzberatung, Gewaltfreie Kommunikation, Appreciative Inquiry. Persönlichkeitsmodelle werden ausschließlich als Beobachtungs-Linse genutzt, nie als Etikett.*
