# Solar, Energiemonitoring & Home Assistant

Hier findest du meine Open-Source-Projekte rund um lokale Energieintegration, Batteriespeicher und Visualisierung in Home Assistant.

Die Projekte sind unabhängig voneinander nutzbar. Sie werden nicht von den jeweiligen Geräteherstellern unterstützt und beruhen teils auf lokalen Protokollen und praktischen Beobachtungen. Bitte lies vor Änderungen an Energieanlagen immer die Hinweise im jeweiligen Projekt.

## Projekte

| Projekt | Wofür ist es gedacht? | Geeignet für |
|---|---|---|
| [Envertech Local](https://github.com/SyntaxSorcerer7/envertech-local) | Lokale Home-Assistant-Integration für Envertech-µ-Wechselrichter – ohne Cloud. | Nutzer:innen von Envertech EVT-Mikrowechselrichtern und Home Assistant |
| [Solar Flow Card](https://github.com/SyntaxSorcerer7/home-assistant-solar-flow-card) | HACS-kompatible Dashboard-Karte für PV-, Batterie-, Haus- und Netzenergieflüsse. | Home-Assistant-Dashboards und Energievisualisierung |
| [MARSTEK B2500 MQTT tools](https://github.com/SyntaxSorcerer7/marstek-b2500-mqtt-tools) | Lokale MQTT-Werkzeuge und dokumentierte Erkenntnisse für B2500 V2 / HMJ-2. | Fortgeschrittene Nutzer:innen mit eigenem MQTT-Broker |

## Wo anfangen?

- Du möchtest deinen **Envertech-Wechselrichter lokal in Home Assistant einbinden**? Starte mit [Envertech Local](https://github.com/SyntaxSorcerer7/envertech-local).
- Du möchtest **PV, Speicher, Hausverbrauch und Netzfluss übersichtlich darstellen**? Nutze die [Solar Flow Card](https://github.com/SyntaxSorcerer7/home-assistant-solar-flow-card).
- Du verwendest einen **MARSTEK B2500 V2 / HMJ-2** und möchtest Status oder MQTT-Konfiguration lokal prüfen? Sieh dir die [B2500 MQTT tools](https://github.com/SyntaxSorcerer7/marstek-b2500-mqtt-tools) an.

## Grundsätze

- Lokal vor Cloud, wenn das Gerät dies unterstützt.
- Keine Zugangsdaten, privaten IP-Adressen, Seriennummern, MAC-Adressen oder vollständigen Aufzeichnungen in Issues oder Pull Requests veröffentlichen.
- Änderungen an Leistungsgrenzen, Speicher- oder Smart-Meter-Konfigurationen erst prüfen und anschließend am Gerät zurücklesen.

## Mitwirken

Fehlerberichte und Pull Requests sind willkommen. Bitte füge eine anonymisierte Beschreibung der Umgebung, die verwendete Software-/Firmware-Version und nachvollziehbare Schritte zum Reproduzieren bei.
