## 🔍 Qualitätsziele

| **Aspekt**                              | **Zieldefinition**                                                                                                                                         |
| --------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Modularität**                         | Bauteile so modellieren, dass sie für ähnliche Bauarten wiederverwendet werden können (z.B. Achslager, Puffer, Kühlboxen, Türen als separate STL-Dateien). |
| **Einfacher Zusammenbau**               | Konstruktion ohne komplizierte Nachbearbeitung: Passungen mit ca. +0.1 mm Toleranz (Resin) und klare Klebestellen; minimale Schleifarbeiten erforderlich.  |
| **Funktionalität & Betriebssicherheit** | Vorrang vor absoluter Vorbildtreue. Stabile Rahmenkonstruktion, ausreichend Gewicht nach NEM, robust montierte Kupplungen.                                 |
| **Kompatibilität mit PEHO Kupplungen**  | Kupplungsaufnahme nach PEHO-Spezifikation; ggf. separater Adapterrahmen, falls nötig.                                                                      |
| **Druckqualität**                       | Keine sichtbaren Layerstrukturen auf Sichtflächen; Gravuren klar erkennbar; keine Supports auf strukturierten Flächen.                                     |
| **Wartung & Reparaturfreundlichkeit**   | Einzelteile (z.B. Puffer, Kupplungsschacht) leicht austauschbar bei Bruch oder Verschleiß.                                                                 |
| **Vorbildnähe**                         | Maßstäblich korrekter Eindruck und stimmige Proportionen; Detaillierung nach Priorität der Stabilität im Fahrbetrieb.                                      |

## ⚠️ Priorisierung für dieses Projekt

1. Fahrbetriebssicherheit auf Modultreffen (robust, entgleisungssicher, kompatibel).
1. Einfache Fertigung und Montage (geringe Nachbearbeitung, klare Montageanleitungen).
1. Modularer Aufbau zur Wiederverwendung von Baugruppen.
1. Optische Vorbildnähe ohne Beeinträchtigung der Funktion.

## 📝 Hinweise zur Umsetzung dieser Qualitätsziele

#### ✅ Modellierung

* Einzelteile (z.B. Puffer, Radsatzaufnahme, Kupplungsschacht, Wagenkasten) in separaten Bodies / Components modellieren.
* Normierte Schnittstellen (Kupplungsschächte, Radsatzlagerung) konsequent definieren.

#### ✅ Toleranzen

* Für Resin-Druck: Lochbohrungen +0.1 mm, Zapfen -0.1 mm als Startwert für Passungen.

#### ✅ Kupplungen

* PEHO Kupplungen: Normmaß TT prüfen (i.d.R. Schachtbreite 2.5 mm) und als direkter Slot oder Adaptermodell integrieren.

#### ✅ Stabilität

* Verstärkungen in Rahmen und Unterflurbauteilen, um Bruch bei Transport zu vermeiden.

#### ✅ Testdrucke

* Vor Serienproduktion einzelne Modul-Tests (z.B. Radsatzaufnahme, Kupplungshalter) durchführen und auf Funktion prüfen.
