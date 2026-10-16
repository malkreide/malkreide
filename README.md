🇩🇪 Deutsch | 🇬🇧 [English](README_EN.md)

# Hallo, ich bin Hayal 👋

**Leiter Marketing und Kommunikation, Mitglied der Geschäftsleitung | Schulamt der Stadt Zürich**  
**Mitglied der KI-Fachgruppe der Stadtverwaltung Zürich**

Ich baue Open-Source-Werkzeuge für eine KI, die dem öffentlichen Interesse dient – nicht umgekehrt. Meine Arbeit verbindet kritische Theorie, offene Daten und pragmatische Prozessoptimierung, damit Verwaltung und Bildung souverän digitalisieren können.

> *«Kein algorithmisches System ist neutral. Kein Verwaltungsprozess ist alternativlos. Und keine Datensouveränität entsteht von selbst.»*

---

## Woran ich glaube

KI in der öffentlichen Verwaltung scheitert nicht an der Technologie – sie scheitert an fehlender Reflexion, an blinden Prozessen und an der Illusion, dass Cloud-Abhängigkeit alternativlos sei.

Vier Prinzipien leiten meine Arbeit:

**Kritisch reflektieren, bevor implementieren.** Wer Bias und Machtstrukturen in KI-Systemen nicht versteht, automatisiert Ungleichheit. Kritische Theorie ist kein akademischer Luxus – sie ist Voraussetzung für verantwortungsvolle Technologieentscheide.

**Prozesse zuerst, Technologie danach.** Die grösste Gefahr ist ein kaputter Prozess mit neuer Software. Erst hinterfragen, dann löschen, dann – vielleicht – digitalisieren.

**Datensouveränität ist nicht verhandelbar.** Öffentliche Institutionen, die ihre Daten an proprietäre Plattformen abgeben, geben Handlungsfähigkeit ab. Lokale Verarbeitung, offene Schnittstellen und Open Source sind keine technischen Präferenzen – sie sind demokratische Notwendigkeiten.

**Belegen statt behaupten – und der Mensch entscheidet.** Jede Aussage eines KI-Systems muss auf eine überprüfbare Quelle zurückführbar sein; was sich nicht belegen lässt, wird markiert, nicht angezeigt. Tests und deterministische Regeln sind die Wahrheitsinstanz, nicht die Selbsteinschätzung eines Modells. Die letzte Freigabe liegt immer bei einem Menschen.

---

## Was ich baue

Über 60 eigene Repositories, fünf Themenfelder. Alles Open Source, fast alles unter MIT-Lizenz.

### 🏛️ Civic Tech: Verwaltung sichtbar und verständlich machen

| Projekt | Was es tut |
|:--------|:-----------|
| **[Maschinerie Zürich](https://github.com/malkreide/maschinerie-zuerich)** | Interaktive, barrierefreie Visualisierung der Stadtverwaltung Zürich – Departemente, Dienstabteilungen, Budgets und Stellen aus offenen Daten, mit einer Lebenslagen-Suche («Hund anmelden» → zuständige Stelle). Fünf Sprachen inklusive Leichter Sprache. |
| **[Tessera](https://github.com/malkreide/tessera)** | Offene KI-Agenten, die Verwaltungsprozesse in kleine, maschinenlesbare Bausteine zerlegen. Jede Aussage bleibt an die Originalquelle gebunden, jede Änderung geht als Pull Request durch eine menschliche Freigabe. Speist die Maschinerie Zürich. |
| **[Zürich Schulferien ICS](https://github.com/malkreide/zuerich-schulferien-ics)** | Abonnierbarer Kalender-Feed für die Schulferien der Stadt Zürich, automatisch aus Open Data generiert. |

### 🎓 Bildung und Lernen

| Projekt | Was es tut |
|:--------|:-----------|
| **[Future Skills Evidence Graph](https://github.com/malkreide/future-skills-evidence-graph)** | Offener Evidenzkatalog für Zukunftskompetenzen in KI und Bildung, mit Abgleich zum Lehrplan 21. Keine Kompetenzempfehlung ohne Evidenzpfad. |
| **[Sokratische Methode](https://github.com/malkreide/socratic-method-skill)** | Claude als sokratischer Tutor – geleitete Wissensentdeckung durch systematisches Fragen statt direkter Instruktion. |
| **[Critical Pedagogy](https://github.com/malkreide/critical-pedagogy-skill)** | Lehrpläne, Schulkommunikation und Bildungstexte auf versteckte Machtdynamiken und Exklusionsmechanismen untersuchen. |
| **[Luanti Lernwelt](https://github.com/malkreide/luanti-lernwelt-template)** | Wiederverwendbares Framework für kindgerechte Lernwelten in Luanti (ehemals Minetest), mit Lehrplan-21-Tagging. |
| **[Papercraft KI](https://github.com/malkreide/papercraft-ki)** | Pädagogische Papercraft-Bastelbögen mit freien Werkzeugen und lokaler KI, dem Lehrplan 21 zugeordnet. |

### 🧰 Evidenzbasierte Werkzeuge für Entscheide

Gemeinsames Muster: KI extrahiert, Regeln rechnen deterministisch, der Mensch entscheidet.

| Projekt | Was es tut |
|:--------|:-----------|
| **[personakit](https://github.com/malkreide/personakit)** · [MCP](https://github.com/malkreide/personakit-mcp) | Evidenzbasierte, verhaltensorientierte Personas als versioniertes Markdown mit Jobs-to-be-Done, Lint-Regeln und Prompt-Export; per MCP-Server nur lesend für KI-Sessions verfügbar. |
| **[journeykit](https://github.com/malkreide/journeykit)** | Evidenzbasierte User Journeys für die öffentliche Verwaltung – Schema, Lints, Renderer und Claude-Skill. |
| **[sentimentkit](https://github.com/malkreide/sentimentkit)** | Sentiment-Toolkit mit austauschbaren Backends, Evidenz-Atomen, Eval-Harness und Policy-as-Code. |
| **[Methodos AI](https://github.com/malkreide/methodos-ai)** | Offener Katalog von Managementmethoden mit CLI, RAG, providerneutraler Architektur und MCP-Schnittstelle – standardmässig vollständig offline. |
| **[use-case-discovery](https://github.com/malkreide/use-case-discovery)** | Claude-Code-Skill für systematische Use-Case-Entdeckung aus Repos, Papers und Tools – mit Kreuzinspiration über frei konfigurierbare Kontexte. |
| **[dealkit](https://github.com/malkreide/dealkit)** | Immobilien-Deal-Screening mit deterministischem Bewertungskern, Evidenz-Schemas und Red-Flag-Checklisten. Sagt nie «kaufen». |

### 🔍 Claude Skills: Denk- und Arbeitsmethoden

Spezialisierte Anweisungssets, die Claude zu einem Experten für eine Aufgabe machen – kalibriert für Schweizer Verwaltung und Bildung.

| Skill | Was er tut |
|:------|:-----------|
| **[Critical AI Literacy](https://github.com/malkreide/critical-ai-literacy-skill)** | KI-Systeme auf Bias, Machtstrukturen und gesellschaftliche Auswirkungen analysieren – Frankfurter Schule trifft Technologiekritik. |
| **[Musk-Algorithmus](https://github.com/malkreide/musk-algorithm-skill)** | 5-Schritte-Prozessanalyse (Hinterfragen → Löschen → Vereinfachen → Beschleunigen → Automatisieren), adaptiert für die öffentliche Verwaltung. |
| **[Idea Cockpit](https://github.com/malkreide/idea-cockpit-skill)** · [Idea Synthesis](https://github.com/malkreide/idea-synthesis-skill) | Strukturiertes Ideenmanagement nach dem Idea-Flight-Deck-Framework und seed-basierte Ideensynthese über eine Notion-Wissensbasis, mit Provenienz. |
| **[UX Audit](https://github.com/malkreide/ux-audit-skill)** | Reproduzierbare UX-Audits (Nielsen, WCAG 2.2 AA, Core Web Vitals) mit hybrider Browser- und Code-Prüfung. |
| **[GitHub Repo](https://github.com/malkreide/github-repo-skill)** | Professionelle GitHub-Repositories erstellen und pflegen – zweisprachige READMEs, Standarddateien, Releases, Sicherheitscheck vor dem Push. |
| **[Raspberry Pi AI](https://github.com/malkreide/raspberry-pi-ai-skill)** | Raspberry-Pi-Entwicklung mit Edge AI (Hailo-NPU), Hardware-Integration und systematischem Debugging. |
| **[Notion AI Papers](https://github.com/malkreide/notion-ai-papers)** | Systematische Analyse von KI-Research-Papers mit automatisierter Notion-Integration. |

### 🔌 Swiss Public Data MCP: öffentliche Daten für KI-Agenten

Das [Model Context Protocol (MCP)](https://modelcontextprotocol.io/) ist der offene Standard, der KI-Modelle mit Datenquellen und Werkzeugen verbindet – ein genormter Stecker für die KI-Welt. Öffentliche Daten verdienen öffentliche Schnittstellen.

Das Portfolio **[swiss-public-data-mcp](https://github.com/malkreide/swiss-public-data-mcp)** umfasst **42 MCP-Server für 41 Schweizer Datenquellen in 13 Domänen** – von [Open Data der Stadt Zürich](https://github.com/malkreide/zurich-opendata-mcp) über [Bundesrecht (Fedlex)](https://github.com/malkreide/fedlex-mcp), [Bundesstatistik (BFS)](https://github.com/malkreide/swiss-statistics-mcp), [Geodaten (swisstopo)](https://github.com/malkreide/swisstopo-mcp), [öffentlichen Verkehr](https://github.com/malkreide/swiss-transport-mcp) und [Parlament](https://github.com/malkreide/parlament-mcp) bis zu Gesundheits-, Energie-, Bildungs- und Kulturdaten. Es wird als auditierbares Inventar geführt (`portfolio.json`, MCP-Registry-Einträge, Publishing-Runbook), nicht als lose Sammlung von Experimenten.

Zum Portfolio gehört eine eigene Qualitätskette:

| Projekt | Was es tut |
|:--------|:-----------|
| **[mcp-audit-skill](https://github.com/malkreide/mcp-audit-skill)** | 120 Checks in 12 Kategorien gegen einen kuratierten Best-Practice-Korpus – OAuth 2.1, OWASP, Lethal Trifecta, Schweizer Compliance (DSG/ISDS). |
| **[mcp-continuous-auditor](https://github.com/malkreide/mcp-continuous-auditor)** | Kontinuierlicher Multi-Agenten-Auditor für MCP-Server: promptfoo und CI als deterministische Wahrheitsinstanz, Probes für Versionsidentität und ausgelieferte Releases, der Mensch als Merge-Gate. |

Leitmotiv: **«Privacy by Architecture»** – Open Data offen zugänglich, sensible Daten lokal geschützt.

---

## Warum Open Source?

Öffentliche Verwaltung mit öffentlichem Geld sollte öffentliche Werkzeuge produzieren. Die Projekte hier sind frei verwendbar und frei adaptierbar.

Wenn eine Stadtverwaltung in Bern, Wien oder Berlin dieselben Herausforderungen hat wie wir in Zürich, soll sie nicht bei null anfangen müssen.

---

## Unabhängigkeit

Alle Repositories in diesem Account sind persönliche Projekte, in privater Zeit und mit privater Infrastruktur entwickelt. Sie sind keine Projekte des Schulamts, der Stadt Zürich oder der KI-Fachgruppe der Stadtverwaltung und implizieren weder Auftrag noch Freigabe noch produktiven Einsatz durch eine Institution. Verweise auf städtische oder eidgenössische Strategien sind Kontext, nicht Autorität.

---

## Theoretische Grundlagen

Meine Arbeit steht auf vier Pfeilern:

- **Kritische Theorie** (Horkheimer, Adorno, Habermas, Honneth) – Ideologiekritik und Machtanalyse als Grundlage für Technologieentscheide
- **Critical Pedagogy** (Freire, Giroux) – Bildung als Befreiungspraxis, nicht als Optimierungsproblem
- **Critical Data Studies** (Buolamwini, Noble, Couldry) – Algorithmische Gerechtigkeit und die politische Ökonomie von Daten
- **Lean / First Principles** (Goldratt, Toyota, Musk) – Radikal pragmatische Prozessoptimierung, die beim Hinterfragen beginnt

---

## Kontext

Das [Schulamt der Stadt Zürich](https://www.stadt-zuerich.ch/ssd/de/index/volksschule/schulamt.html) unterstützt die Schulen und die sieben Kreisschulbehörden bei der Steuerung und Entwicklung der städtischen Volksschule – mit rund 36'750 Schülerinnen und Schülern im Schuljahr 2026/27 ([Medienmitteilung](https://www.stadt-zuerich.ch/de/aktuell/medienmitteilungen/2026/08/neues-schuljahr-2026-27.html)).

Als Mitglied der **KI-Fachgruppe der Stadtverwaltung Zürich** arbeite ich am Erfahrungsaustausch, an Standards und an der Einschätzung von KI-Vorhaben für die gesamte Stadtverwaltung.

---

## Let's connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-hayaloezkan-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/hayaloezkan/)

---

<sub>Die meisten Projekte stehen unter MIT-Lizenz. Kalibriert für die Schweiz, adaptierbar für andere Kontexte.</sub>
