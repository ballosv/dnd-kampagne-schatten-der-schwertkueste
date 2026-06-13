# Die Schatten der Schwertküste – Verwaltungssystem

## Zweck dieses Systems

Dieses Repository dient der langfristigen Verwaltung einer D&D-Kampagne, die aus mehreren aufeinander aufbauenden und sich gegenseitig beeinflussenden Abenteuern besteht.

Das System stellt sicher, dass vergangene Ereignisse, NSCs, Orte, Gegenstände, Fraktionen, Geheimnisse und Konsequenzen konsistent dokumentiert und in zukünftigen Abenteuern berücksichtigt werden.

Die Verwaltung folgt einem Hybrid-Ansatz:

- strukturierte Status- und Referenzblöcke für schnelle Pflege und hohe Konsistenz
- ausführliche, stimmige und thematisch passende Beschreibungen für Atmosphäre, Spielleitung und kreative Weiterentwicklung

---

## Grundprinzipien

### 1. Kanon vor Entwurf

Was am Spieltisch tatsächlich passiert ist, hat immer Vorrang vor jeder Planung, Skizze oder ursprünglichen Abenteueridee.

### 2. Eine Information hat genau einen Hauptort

Jede relevante Information besitzt eine primäre Datei, in der sie verbindlich gepflegt wird. Andere Dateien dürfen diese Information nur verkürzt erwähnen oder auf sie verweisen.

### 3. Struktur und Atmosphäre zugleich

Jeder wichtige Eintrag soll sowohl klare Fakten als auch eine atmosphärische Beschreibung enthalten. Das System soll als Nachschlagewerk und als kreative Arbeitsgrundlage funktionieren.

### 4. Kampagnenweite Konsistenz

Entscheidungen, Folgen, Beziehungen, Verluste, Bündnisse und enthüllte Geheimnisse müssen in zukünftigen Abenteuern sichtbar bleiben.

### 5. Deutsch als Dokumentationssprache

Alle kampagnenbezogenen Dokumente werden auf Deutsch gepflegt.

### 6. D&D 5.1 als Regelgrundlage

Für regelmechanische Ausarbeitungen gilt `SRD_CC_v5.1_DE.pdf` als maßgebliche Systemreferenz für D&D 5.1 innerhalb dieses Projekts.

Das bedeutet insbesondere:

- regelmechanische Ausarbeitungen sollen sich an den dort beschriebenen Begriffen und Grundmechaniken orientieren
- Spielwerte, Zustände, Rettungswürfe, Schwierigkeitsgrade, Kampfeffekte und ähnliche Regeln sollen konsistent mit dieser Referenz formuliert werden
- erzählerische Dokumente sollen nicht unnötig mit Regeldetails überfrachtet werden, dürfen aber auf regelrelevante Inhalte verweisen

---

## Die Zuständigkeit der Hauptdateien

### `chronik.md`

Die Chronik dokumentiert ausschließlich bestätigte Ereignisse aus bereits gespielten Sitzungen oder abgeschlossenen Abenteuern.

Enthält:

- tatsächliche Ereignisse
- wichtige Entscheidungen der Heldengruppe
- unmittelbare Konsequenzen
- neue Tatsachen für den Kampagnenkanon

Enthält nicht:

- Planungen
- Vermutungen des Spielleiters
- geheime Hintergründe, die noch nicht als kanonisches Ereignis relevant geworden sind

Leitfrage:

Was ist wirklich passiert?

### `kampagnenbibel.md`

Die Kampagnenbibel enthält die übergeordnete Wahrheit der Kampagne.

Enthält:

- Leitidee und Metaplot
- Status quo der Kampagne
- Hauptantagonisten
- Fraktionen
- geheime Zusammenhänge
- zentrale Themen
- kampagnenweite Leitplanken
- langfristige Phasen und Zielrichtungen

Enthält nicht:

- vollständige Ereignisprotokolle jeder Sitzung
- kleinteilige Pflege aller einzelnen NSC- oder Ortsdetails, sofern diese bereits in den Spezialdateien gepflegt werden

Leitfrage:

Was ist im großen Ganzen wahr und kampagnenweit relevant?

### `nscs.md`

Dieses Dokument ist das zentrale Register aller wichtigen Nichtspielercharaktere.

Enthält:

- Identität und Rolle
- Fraktion oder Zugehörigkeit
- Motivation
- Beziehung zu den Helden
- aktueller Status
- letzter bekannter Stand
- relevante Geheimnisse
- Verweise auf Abenteuerauftritte

Leitfrage:

Wer ist diese Figur aktuell und welche Rolle spielt sie in der Kampagne?

### `orte.md`

Dieses Dokument ist das zentrale Register aller relevanten Orte.

Enthält:

- Beschreibung
- Bedeutung für die Kampagne
- aktueller Zustand
- Kontrolle oder Besitzverhältnisse
- bekannte Ereignisse
- relevante NSCs und Verbindungen

Leitfrage:

Was ist dieser Ort, warum ist er wichtig und wie ist sein aktueller Zustand?

### `offene_handlungsfaeden.md`

Dieses Dokument verwaltet alle offenen Konflikte, Geheimnisse, Gegnerpläne und zukünftigen Entwicklungen.

Enthält:

- offene Plot Hooks
- langfristige Gegnerpläne
- ungelöste Fragen
- mögliche Eskalationen
- Konsequenzen aus Spielerentscheidungen
- vorbereitete, aber noch nicht abgeschlossene Entwicklungen

Leitfrage:

Was ist noch offen, was droht und was kann sich als Nächstes entwickeln?

### `README.md`

Diese Datei dokumentiert die Regeln des Verwaltungssystems.

Sie definiert:

- Zweck und Arbeitsweise des Systems
- Zuständigkeiten der Dateien
- Pflegeprozess
- Statuslogik
- Konventionen für neue Einträge

---

## Trennung von Kanon, Planung und Detailausarbeitung

### Kanon

Kanon sind alle bestätigten Tatsachen der Kampagne.

Dazu zählen insbesondere:

- gespielte Ereignisse
- bestätigte Konsequenzen
- etablierte NSCs
- bekannte Orte
- enthüllte Geheimnisse
- gewonnene oder verlorene Gegenstände

### Planung

Planung umfasst Inhalte, die vorbereitet, aber noch nicht ausgespielt wurden.

Diese Inhalte gehören primär in Abenteuerentwürfe und in offene Handlungsfäden, jedoch nicht als bestätigte Tatsachen in die Chronik.

### Detailausarbeitung

Detailausarbeitungen für einzelne Abenteuer, Szenen, Gegner oder Begegnungen gehören in die jeweiligen Abenteuerordner.

---

## Verbindliche Hauptorte von Informationen

- Tatsächlich gespielte Ereignisse gehören in `chronik.md`
- Metaplot und kampagnenweite Wahrheiten gehören in `kampagnenbibel.md`
- Figurenstatus gehört in `nscs.md`
- Ortsstatus gehört in `orte.md`
- ungelöste Konflikte und zukünftige Entwicklungen gehören in `offene_handlungsfaeden.md`
- vorbereitete Szenen, Begegnungen und Abenteuerstrukturen gehören in die Abenteuerordner unter `abenteuer`

Wenn eine Information in mehreren Dateien relevant ist, wird sie nur an einem Ort vollständig gepflegt. Alle anderen Dateien enthalten nur Kurzverweise, Konsequenzen oder Zusammenfassungen.

---

## Standard für den Schreibstil

Alle Dokumente sollen:

- auf Deutsch verfasst werden
- klar und übersichtlich gegliedert sein
- inhaltlich konsistent mit dem bisherigen Kanon bleiben
- thematisch zur Kampagne passen
- detailliert und stimmungsvoll formuliert sein

Dabei gilt:

- Fakten sollen eindeutig sein
- Beschreibungen dürfen atmosphärisch und erzählerisch ausformuliert werden
- unnötige Wiederholungen zwischen Dateien sollen vermieden werden

---

## Standardisierte Statuswerte

### Für NSCs

Empfohlene Statuswerte:

- Aktiv
- Verbündet
- Neutral
- Feindlich
- Gefangen
- Verletzt
- Verschollen
- Tot
- Unbekannt

### Für Orte

Empfohlene Statuswerte:

- Sicher
- Bedroht
- Besetzt
- Umkämpft
- Verlassen
- Verborgen
- Zerstört

### Für Handlungsfäden

Empfohlene Statuswerte:

- Offen
- Aktiv
- Eskaliert
- Pausiert
- Gelöst
- Gescheitert

Diese Begriffe sollen möglichst konsistent verwendet werden, damit Entwicklungen über viele Abenteuer hinweg schnell erfassbar bleiben.

---

## Empfohlene Struktur neuer Einträge

### NSCs

Ein NSC-Eintrag sollte nach Möglichkeit folgende Aspekte enthalten:

- Name
- Rolle oder Funktion
- Zugehörigkeit oder Fraktion
- Status
- Aufenthaltsort oder letzter bekannter Aufenthaltsort
- Motivation
- Beziehung zu den Helden
- Geheimnisse oder verborgene Agenda
- letzter bekannter Stand
- relevante Abenteuerauftritte

### Orte

Ein Orte-Eintrag sollte nach Möglichkeit folgende Aspekte enthalten:

- Name des Ortes
- Typ oder Einordnung
- Region
- Kurzbeschreibung
- Bedeutung für die Kampagne
- aktueller Status
- Kontrolle oder Herrschaft
- relevante NSCs
- bekannte Ereignisse
- Verbindungen zu anderen Orten oder Handlungsfäden

### Offene Handlungsfäden

Ein Handlungsfaden sollte nach Möglichkeit folgende Aspekte enthalten:

- Titel
- Kategorie
- Status
- Ausgangslage
- beteiligte NSCs
- beteiligte Orte
- offene Fragen
- mögliche nächste Eskalation
- mögliche Folgen
- letzter Fortschritt

### Chronik-Einträge

Ein Chronik-Eintrag sollte nach Möglichkeit folgende Aspekte enthalten:

- Titel des Abenteuers oder der Sitzung
- zeitliche Einordnung
- beteiligte Figuren
- zentrale Ereignisse
- Entscheidungen der Helden
- direkte Konsequenzen
- neue offene Fäden

---

## Arbeitsprozess pro Spielsitzung oder Abenteuer

### Vor dem Spiel

Vorbereitete Inhalte werden in den Abenteuerunterlagen gepflegt.

Dazu gehören insbesondere:

- Szenen
- Begegnungen
- NSCs des Abenteuers
- Ortsdetails
- Hinweise, Enthüllungen und Konflikte
- regelmechanische Ausarbeitungen auf Basis von `SRD_CC_v5.1_DE.pdf`

### Nach dem Spiel

Nach einer Sitzung oder nach einem abgeschlossenen Abenteuer erfolgt die Pflege in dieser Reihenfolge:

#### 1. `chronik.md`

Eintragen, was tatsächlich passiert ist.

#### 2. `nscs.md`

Status, Beziehungen, Verluste, Bündnisse oder neue Erkenntnisse aktualisieren.

#### 3. `orte.md`

Ortsstatus, Kontrolle, Schäden oder neue Bedeutung aktualisieren.

#### 4. `offene_handlungsfaeden.md`

Neue Fäden eintragen, bestehende Fäden weiterschreiben, gelöste Fäden markieren.

#### 5. `kampagnenbibel.md`

Nur dann aktualisieren, wenn sich die übergeordnete Wahrheit, der Status quo oder der Metaplot der Kampagne verändert hat.

---

## Umgang mit Abenteuerordnern

Der Ordner `abenteuer` enthält die konkreten Unterlagen zu einzelnen Abenteuern.

Dort liegen insbesondere:

- Entwürfe
- Szenenstrukturen
- NSC-Detailausarbeitungen
- Ortsausarbeitungen
- Mechaniken und Begegnungen
- individuelle Abenteuerfolgen

Abenteuerdateien dürfen ausführlicher, experimenteller und planungsnäher sein als die kampagnenweiten Kerndokumente.

Sobald Inhalte im Spiel bestätigt wurden, sollen ihre kampagnenweiten Konsequenzen in die zuständigen Hauptdateien übertragen werden.

---

## Regeln zur Konsistenzprüfung

Bei jeder größeren Ergänzung sollten folgende Fragen geprüft werden:

- Widerspricht der neue Inhalt einem bereits gespielten Ereignis?
- Hat ein NSC, Ort oder Gegenstand bereits einen etablierten Status?
- Entsteht durch die Änderung ein neuer offener Handlungsfaden?
- Muss der Status quo der Kampagne angepasst werden?
- Muss die Chronik ergänzt werden?
- Ist die Regelmechanik mit `SRD_CC_v5.1_DE.pdf` vereinbar?

---

## Ziel des Systems

Dieses Verwaltungssystem soll ermöglichen, dass die Kampagne über viele Abenteuer hinweg:

- konsistent bleibt
- lebendig wirkt
- vergangene Entscheidungen ernst nimmt
- zukünftige Abenteuer sauber vorbereitet
- erzählerisch dicht und regelmechanisch nachvollziehbar geführt werden kann

Das System dient zugleich als Nachschlagewerk, Kanonarchiv, Planungsgrundlage und kreative Entwicklungsbasis für die gesamte Kampagne.
