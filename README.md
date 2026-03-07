🇩🇪 Deutsch | 🇬🇧 [English](README_EN.md)

# Hallo, ich bin Hayal 👋

**Leiter Kommunikation | Schulamt der Stadt Zürich**  
**Mitglied der Geschäftsleitung | KI-Fachgruppe der Stadtverwaltung Zürich**

Ich baue Open-Source-Werkzeuge für eine KI, die dem öffentlichen Interesse dient — nicht umgekehrt. Meine Arbeit verbindet kritische Theorie, Edge AI und pragmatische Prozessoptimierung, um Verwaltung und Bildung souverän zu digitalisieren.

> *«Kein algorithmisches System ist neutral. Kein Verwaltungsprozess ist alternativlos. Und keine Datensouveränität entsteht von selbst.»*

---

## Woran ich glaube

KI in der öffentlichen Verwaltung scheitert nicht an der Technologie — sie scheitert an fehlender Reflexion, an blinden Prozessen und an der Illusion, dass Cloud-Abhängigkeit alternativlos sei.

Drei Prinzipien leiten meine Arbeit:

**Kritisch reflektieren, bevor implementieren.** Wer Bias und Machtstrukturen in KI-Systemen nicht versteht, automatisiert Ungleichheit. Kritische Theorie ist kein akademischer Luxus — sie ist Voraussetzung für verantwortungsvolle Technologieentscheide.

**Prozesse zuerst, Technologie danach.** Die grösste Gefahr ist ein kaputter Prozess mit neuer Software. Erst hinterfragen, dann löschen, dann — vielleicht — digitalisieren.

**Datensouveränität ist nicht verhandelbar.** Öffentliche Institutionen, die ihre Daten an proprietäre Plattformen abgeben, geben Handlungsfähigkeit ab. Edge AI, lokale Verarbeitung und Open Source sind keine technischen Präferenzen — sie sind demokratische Notwendigkeiten.

---

## Was ich baue

### 🔍 Claude AI Skills

Spezialisierte Anweisungssets, die Claude zu einem Experten für spezifische Aufgaben machen — kalibriert für Schweizer Verwaltung und Bildung.

| Skill | Was er tut |
|:------|:-----------|
| **[Critical AI Literacy](https://github.com/malkreide/critical-ai-literacy-skill)** | KI-Systeme auf Bias, Machtstrukturen und gesellschaftliche Auswirkungen analysieren — Frankfurter Schule trifft Technologiekritik |
| **[Critical Pedagogy](https://github.com/malkreide/critical-pedagogy-skill)** | Lehrpläne, Schulkommunikation und Bildungstexte auf versteckte Machtdynamiken und Exklusionsmechanismen untersuchen |
| **[Musk-Algorithmus](https://github.com/malkreide/musk-algorithm-skill)** | 5-Schritte-Prozessanalyse (Hinterfragen → Löschen → Vereinfachen → Beschleunigen → Automatisieren), adaptiert für die öffentliche Verwaltung |
| **[Sokratische Methode](https://github.com/malkreide/socratic-method-skill)** | Claude als sokratischer Tutor — geleitete Wissensentdeckung durch systematisches Fragen statt direkter Instruktion |

### 🤖 Edge AI & Raspberry Pi

Lokale KI-Verarbeitung auf Raspberry Pi — weil souveräne Institutionen ihre Daten nicht in fremde Clouds schicken.

| Projekt | Was es tut |
|:--------|:-----------|
| **[Raspberry Pi AI Skill](https://github.com/malkreide/raspberry-pi-ai-skill)** | Claude-Skill für Raspberry Pi Entwicklung mit Edge AI (Hailo-8L NPU), Hardware-Integration und systematisches Debugging |
| *Weitere Projekte in Entwicklung* | Edge-AI-Prototypen für Bildungs- und Verwaltungskontexte — Sprachverarbeitung, Bilderkennung und Sensordaten, lokal verarbeitet |

Mein Fokus: **KI, die auf einem 100-Franken-Gerät im Schulzimmer oder Büro läuft** — ohne Cloud-Abhängigkeit, ohne Datenabfluss, ohne Vendor Lock-in.

### 🔌 MCP Server — KI mit Daten verbinden

Das [Model Context Protocol (MCP)](https://modelcontextprotocol.io/) ist der offene Standard, der KI-Modelle sicher mit Datenquellen und Werkzeugen verbindet — wie ein genormter Stecker für die KI-Welt. Ich entwickle MCP-Server, die öffentliche Daten für KI-Agenten zugänglich machen, ohne Datensouveränität zu opfern.

| Projekt | Was es tut |
|---------|-----------|
| **[Zurich Open Data MCP](https://github.com/malkreide/zurich-opendata-mcp)** | MCP-Server für [Open Data der Stadt Zürich](https://data.stadt-zuerich.ch/) — 900+ Datensätze via CKAN, Geodaten (Schulanlagen, Quartiere), Parlamentsinformationen, Tourismusdaten, SPARQL Linked Data und Echtzeit-Parkplatzdaten über 6 APIs. 20 Tools, CC0-lizenziert. |
| **[Swiss Transport MCP](https://github.com/malkreide/swiss-transport-mcp)** | MCP-Server für den Schweizer öffentlichen Verkehr — OJP-Reiseplaner, Echtzeit-Abfahrten, Störungen, Auslastung, Ticketpreise, Zugkompositionen und Open Data von opentransportdata.swiss |
| **[Swiss Road Mobility MCP](https://github.com/malkreide/swiss-road-mobility-mcp)** | MCP-Server für Schweizer Strassenmobilität: Shared Vehicles, E-Ladestationen, DATEX-II-Verkehrsdaten, Strassenzähler, Park & Rail und multimodale Reiseplanung (Auto → Zug → Ziel). 12 Tools, Open Data first. |
| **[Fedlex MCP](https://github.com/malkreide/fedlex-mcp)** | MCP-Server für das Schweizer Bundesrecht (Fedlex) — systematische Rechtssammlung (SR) durchsuchen, Gesetzesänderungen verfolgen und BBl/Staatsverträge via SPARQL abfragen |
| **[Global Education MCP](https://github.com/malkreide/global-education-mcp)** | MCP-Server für internationale Bildungsdaten — UNESCO UIS (4'000+ Indikatoren) und OECD Education at a Glance via SDMX. Kein API-Schlüssel erforderlich. |
| **[ETH Library MCP](https://github.com/malkreide/eth-library-mcp)** | MCP-Server für die ETH-Bibliothek Zürich — Zugriff auf 30 Mio.+ Ressourcen (Bücher, Karten, Bilder, Archive) via Discovery & Persons API |
| **[MCP Server für Patentrecherche](https://github.com/malkreide/MCP-Server-for-patent-research-)** | MCP-Server für Patentrecherche — EPO OPS, Espacenet & IGE/Swissreg für europäische und schweizerische Schutzrechte |

Mein Fokus: Öffentliche Daten verdienen öffentliche Schnittstellen. Jeder MCP-Server, den ich baue, folgt dem Prinzip «Privacy by Architecture» — Open Data offen zugänglich, sensible Daten lokal geschützt.

### 🔧 Persönliche Workflows

Werkzeuge, die ich selbst täglich nutze und als Open Source teile.

| Projekt | Was es tut |
|:--------|:-----------|
| **[Notion AI Papers](https://github.com/malkreide/notion-ai-papers)** | Systematische Analyse von AI-Research-Papers mit automatisierter Notion-Integration — mein persönliches Wissensmanagementsystem für strategische Entscheide |

---

## Warum Open Source?

Öffentliche Verwaltung mit öffentlichem Geld sollte öffentliche Werkzeuge produzieren. Jeder Skill und jedes Projekt hier steht unter MIT-Lizenz — frei verwendbar, frei adaptierbar.

Wenn eine Stadtverwaltung in Bern, Wien oder Berlin dieselben Herausforderungen hat wie wir in Zürich, soll sie nicht bei Null anfangen müssen.

---

## Theoretische Grundlagen

Meine Arbeit steht auf vier Pfeilern:

- **Kritische Theorie** (Horkheimer, Adorno, Habermas, Honneth) — Ideologiekritik und Machtanalyse als Grundlage für Technologieentscheide
- **Critical Pedagogy** (Freire, Giroux) — Bildung als Befreiungspraxis, nicht als Optimierungsproblem
- **Critical Data Studies** (Buolamwini, Noble, Couldry) — Algorithmische Gerechtigkeit und die politische Ökonomie von Daten
- **Lean / First Principles** (Musk, Goldratt, Toyota) — Radikal pragmatische Prozessoptimierung, die beim Hinterfragen beginnt

---

## Kontext

Das [Schulamt der Stadt Zürich](https://www.stadt-zuerich.ch/ssd/de/index/volksschule/schulamt.html) unterstützt die Schulen und Kreisschulbehörden bei der Steuerung und Entwicklung der städtischen Volksschule — rund 32'000 Schülerinnen und Schüler, 4'500 Lehrpersonen, 125 Schulen.

Als Mitglied der **KI-Fachgruppe der Stadtverwaltung Zürich** arbeite ich an der strategischen KI-Implementation für die gesamte Stadtverwaltung.

---

## Let's connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-hayaloezkan-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/hayaloezkan/)

---

<sub>Alle Projekte stehen unter MIT-Lizenz. Kalibriert für die Schweiz, adaptierbar für andere Kontexte.</sub>
