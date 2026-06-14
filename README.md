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
- Verweise auf die zugehörige Datenblatt-Datei eines NSC oder Monsters

Leitfrage:

Wer ist diese Figur aktuell und welche Rolle spielt sie in der Kampagne?

### Datenblatt-Dateien für NSCs und Monster

Für jeden NSC und jedes Monster, das regelmechanisch relevant ist oder im Spiel als eigenständige Figur geführt wird, wird zusätzlich eine eigene Datei angelegt.

Diese Datei dient als standardisierte Quelle für:

- Spielwerte
- regelmechanische Merkmale
- Aktionen
- besondere Fähigkeiten
- Beute oder Belohnungen
- visuelle oder beschreibende Zusatzinformationen

Diese Dateien werden so aufgebaut, dass daraus später automatisiert oder halbautomatisiert ein Datenblatt generiert werden kann.

Die Datenblatt-Datei ist nicht der primäre Ort für den erzählerischen Kampagnenstatus. Dafür bleibt `nscs.md` zuständig.

Die Datenblatt-Datei ist der primäre Ort für die standardisierte regelmechanische Darstellung einer Figur oder Kreatur.

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
- Verweise auf die Vorlagen im Ordner `templates`

---

## Vorlagenordner

Der Ordner `templates` enthält die Standardvorlagen für die zentralen Kampagnendokumente.

Dort liegen insbesondere Vorlagen für:

- `chronik.md`
- `kampagnenbibel.md`
- `nscs.md`
- `orte.md`
- `offene_handlungsfaeden.md`

Diese Vorlagen dienen als Ausgangsbasis für neue Dokumente oder für eine spätere behutsame Angleichung bestehender Dateien an das Verwaltungssystem.

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
- standardisierte Spielwerte und Datenblattinformationen von NSCs und Monstern gehören in eigene Datenblatt-Dateien
- standardisierte Datenblattinformationen von besonderen oder kampagnenrelevanten Gegenständen gehören in eigene Datenblatt-Dateien
- Ortsstatus gehört in `orte.md`
- ungelöste Konflikte und zukünftige Entwicklungen gehören in `offene_handlungsfaeden.md`
- vorbereitete Szenen, Begegnungen und Abenteuerstrukturen gehören in die Abenteuerordner unter `abenteuer`

Wenn eine Information in mehreren Dateien relevant ist, wird sie nur an einem Ort vollständig gepflegt. Alle anderen Dateien enthalten nur Kurzverweise, Konsequenzen oder Zusammenfassungen.

### Verbindliche Synchronisationsregel

Immer wenn ein Inhalt in irgendeiner Datei hinzugefügt, verändert oder als neuer Kanon festgelegt wird, müssen automatisch auch die dadurch notwendigen Ergänzungen oder Änderungen in den betroffenen Hauptdateien vorgenommen werden.

Das ist keine optionale Nachpflege, sondern ein verbindlicher Bestandteil jeder inhaltlichen Änderung.

Beispiele:

- Wenn in `chronik.md` festgehalten wird, dass ein Ort durch eine Lawine verschüttet wurde, muss der Status dieses Ortes auch in `orte.md` angepasst werden.
- Wenn ein NSC in einem Abenteuer stirbt, verschwindet oder die Seiten wechselt, muss sein Status auch in `nscs.md` aktualisiert werden.
- Wenn ein neuer Gegenstand, ein neues Bündnis oder ein neuer kampagnenweiter Fakt bestätigt wird, müssen die entsprechenden Einträge auch in `kampagnenbibel.md`, `offene_handlungsfaeden.md` oder anderen betroffenen Hauptdateien ergänzt werden.

Für jede relevante Änderung gilt daher immer die Pflicht zur Prüfung von Folgewirkungen in mindestens diesen Hauptdateien:

- `chronik.md`
- `kampagnenbibel.md`
- `nscs.md`
- `orte.md`
- `offene_handlungsfaeden.md`

Ziel ist, dass keine kampagnenrelevante Änderung isoliert nur in einer einzelnen Datei stehen bleibt, wenn sie Auswirkungen auf den Gesamtzustand der Kampagne hat.

---

## Standard für Datenblatt-Dateien von NSCs, Monstern und Gegenständen

### Ziel

Jeder NSC, jedes Monster und jeder besondere oder wichtige Gegenstand mit eigener regelmechanischer oder kampagnenweiter Relevanz erhält eine eigene Datei, damit die Informationen eindeutig, einheitlich und maschinenlesbar genug für eine spätere Datenblatt-Generierung vorliegen.

### Grundregeln

- jede regelrelevante Figur, Kreatur oder jeder besondere Gegenstand erhält genau eine primäre Datenblatt-Datei
- der Anzeigename in der Datei muss eindeutig dem Namen in `nscs.md` zuordenbar sein
- die Datei muss standardisierte Feldbezeichnungen verwenden
- Spielwerte und Regelinformationen sollen aus `SRD_CC_v5.1_DE.pdf` ableitbar und mit D&D 5.1 vereinbar sein
- freie Fließtexte sind erlaubt, aber klar von strukturierten Datenblöcken zu trennen

Für Gegenstände gilt ergänzend:

- besondere Waffen, Artefakte, Schlüsselobjekte und kampagnenwichtige magische Gegenstände sollen in eigenen Datenblatt-Dateien erfasst werden
- Besitzverlauf, Zustand, bekannte Wirkungen und kampagnenweite Bedeutung sollen dort nachvollziehbar dokumentiert werden

### Zuordnung zwischen `nscs.md` und Datenblatt-Dateien

Jeder Eintrag in `nscs.md`, der eine eigene regelmechanische Darstellung benötigt, soll auf genau eine Datenblatt-Datei verweisen.

Die Zuordnung erfolgt über drei gemeinsame Kernelemente:

- Anzeigename
- eindeutige ID
- Dateipfad

### Verbindliche Mindestfelder jeder Datenblatt-Datei

Jede Datenblatt-Datei soll mindestens die folgenden Felder enthalten:

- `id`
- `name`
- `typ`
- `kategorie`
- `quelle`
- `regelbasis`
- `status`

Bedeutung:

- `id`: kampagnenweit eindeutiger technischer Schlüssel
- `name`: Anzeigename der Figur oder Kreatur
- `typ`: `nsc` oder `monster`
- `kategorie`: z. B. Humanoider, Drache, Monstrosität, Untoter
- `quelle`: z. B. Kampagnenoriginal, adaptiert, SRD-basiert
- `regelbasis`: in diesem Projekt standardmäßig `DND5.1-SRD-DE`
- `status`: optionaler Kurzstatus wie Aktiv, Tot, Verbündet, Feindlich

### Empfohlenes Namensschema für die ID

Die ID soll stabil, eindeutig und dateitauglich sein.

Empfohlenes Schema:

`typ-region-oder-fraktion-name`

Beispiele:

- `nsc-phandalin-harbin-wester`
- `nsc-schattengilde-elgor-der-eismagier`
- `monster-gnomengard-mimik-endboss`
- `monster-eisnadelfestung-kalthyros`

Regeln für IDs:

- nur Kleinbuchstaben
- Wörter mit Bindestrichen trennen
- keine Umlaute, stattdessen `ae`, `oe`, `ue`
- keine Sonderzeichen außer Bindestrich
- die ID soll sich nach Möglichkeit nie ändern

### Empfohlenes Dateinamensschema

Der Dateiname soll direkt aus der ID ableitbar sein.

Empfohlenes Schema:

`[id].md`

Beispiele:

- `nsc-phandalin-harbin-wester.md`
- `nsc-schattengilde-elgor-der-eismagier.md`
- `monster-gnomengard-mimik-endboss.md`

### Ablageorte

Die Dateien müssen an fest definierten Orten abgelegt werden, damit ihre Referenzen stabil und kampagnenweit einheitlich bleiben.

Verbindliche Ablage:

- kampagnenweite NSC-Datenblätter liegen im Ordner `datenblaetter/nscs`
- kampagnenweite Monster-Datenblätter liegen im Ordner `datenblaetter/monster`
- kampagnenweite Gegenstands-Datenblätter liegen im Ordner `datenblaetter/gegenstaende`
- abenteuerspezifische NSC- und Monster-Datenblätter liegen innerhalb des jeweiligen Abenteuerordners in dessen Unterordnern für NSCs oder Monster

Standardregel:

- wenn ein NSC kampagnenübergreifend relevant ist, liegt seine Datei in `datenblaetter/nscs`
- wenn ein Monster kampagnenübergreifend relevant ist, liegt seine Datei in `datenblaetter/monster`
- wenn ein Gegenstand kampagnenübergreifend relevant ist, liegt seine Datei in `datenblaetter/gegenstaende`
- wenn ein NSC oder Monster ausschließlich für ein einzelnes Abenteuer relevant ist, darf seine Datei im jeweiligen Abenteuerordner liegen

Empfohlene Beispiele:

- `datenblaetter/nscs/nsc-phandalin-harbin-wester.md`
- `datenblaetter/nscs/nsc-schattengilde-elgor-der-eismagier.md`
- `datenblaetter/monster/monster-gnomengard-mimik-endboss.md`
- `datenblaetter/gegenstaende/gegenstand-gnomengard-frostbrecher-zorn-des-ruhktar.md`
- `abenteuer/A06/nsc/nsc-schattengilde-frostgardist.md`

Wichtig ist, dass der Pfad in `nscs.md` immer exakt auf die tatsächlich verwendete Datei verweist.

### Verbindliche inhaltliche Struktur

Jede Datenblatt-Datei soll in zwei Ebenen aufgebaut sein:

- strukturierter Datenblock
- erzählerischer Zusatzblock

Der strukturierte Datenblock soll später in ein Datenblatt überführt werden können.

### Strukturierter Datenblock

Dieser Block soll nach Möglichkeit die folgenden Bereiche in klarer Reihenfolge enthalten:

- Identität
- Einordnung
- Grundwerte
- Verteidigung und Überleben
- Bewegungsraten
- Attributswerte
- Rettungswürfe
- Fertigkeiten
- Resistenzen, Immunitäten, Verwundbarkeiten
- Sinne
- Sprachen
- Herausforderungsgrad oder vergleichbare Einordnung
- Eigenschaften und Merkmale
- Aktionen
- Bonusaktionen
- Reaktionen
- Legendäre Aktionen oder Spezialmechaniken
- Beute, Belohnungen oder verwertbare Komponenten

### Erzählerischer Zusatzblock

Zusätzlich können enthalten sein:

- Kurzbeschreibung des Auftretens
- Rolle im Abenteuer
- Kampfverhalten
- Taktik
- äußere Erscheinung
- Bildreferenz

### Verknüpfung in `nscs.md`

Wenn ein NSC oder Monster eine eigene Datenblatt-Datei besitzt, soll der Eintrag in `nscs.md` künftig mindestens um folgende Angaben ergänzt werden:

- `ID`
- `Typ`
- `Datenblatt`

Beispiel:

- `ID: nsc-phandalin-harbin-wester`
- `Typ: NSC`
- `Datenblatt: pfad/zur/datei/nsc-phandalin-harbin-wester.md`

Dadurch bleibt ein Eintrag sowohl für das Lesen als auch für spätere automatische Verarbeitung eindeutig zuordenbar.

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
- ID
- Typ
- Rolle oder Funktion
- Zugehörigkeit oder Fraktion
- Status
- Aufenthaltsort oder letzter bekannter Aufenthaltsort
- Motivation
- Beziehung zu den Helden
- Geheimnisse oder verborgene Agenda
- letzter bekannter Stand
- relevante Abenteuerauftritte
- Datenblatt-Datei

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

### Grundsatz zur Ablage

- bereits abgeschlossene oder ältere Abenteuer dürfen weiterhin als einzelne Markdown-Datei direkt in `abenteuer/` liegen
- neue Abenteuer sollen grundsätzlich als eigener Ordner unter `abenteuer/[Abenteuer-ID]/` angelegt werden
- die Ordnerstruktur dient der Planung, Vorbereitung, Durchführung und Nachbereitung eines einzelnen Abenteuers

### Verbindliche Grundstruktur für neue Abenteuerordner

Jeder neue Abenteuerordner soll mindestens die folgenden Dateien enthalten:

- `README.md`
- `abenteuer-entwurf.md`
- `abenteuer-ausarbeitung.md`
- `abenteuer-sitzungsnotizen.md`
- `abenteuer-zusatzinformationen.md`

Zusätzlich sollen bei Bedarf die folgenden Unterordner verwendet werden:

- `szenen/`
- `begegnungen/`
- `orte/`
- `handouts/`
- `tabellen/`
- `nsc/`
- `monster/`
- `gegenstaende/`
- `assets/`

### Zweck der Kern-Dateien eines Abenteuerordners

- `README.md`: Navigations- und Übersichtsdatei des Abenteuers mit Status, Kurzbeschreibung, Dateiverweisen und offenen Baustellen
- `abenteuer-entwurf.md`: früher Ideenraum für Plot, Varianten, offene Fragen und noch nicht spielfertige Gedanken
- `abenteuer-ausarbeitung.md`: operative Hauptdatei für die Spielvorbereitung mit Szenen, Begegnungen, Proben, Konsequenzen und Leitfäden
- `abenteuer-sitzungsnotizen.md`: Dokumentation dessen, was am Spieltisch tatsächlich passiert ist
- `abenteuer-zusatzinformationen.md`: Reserve-Material, Lore, Alternativen, Handout-Texte, Varianten und sonstige Zusatzinformationen

### Regeln für lokale und kampagnenweite NSC-, Monster- und Gegenstandsdateien

- kampagnenweit relevante NSCs liegen primär in `datenblaetter/nscs`
- kampagnenweit relevante Monster liegen primär in `datenblaetter/monster`
- kampagnenweit relevante Gegenstände liegen primär in `datenblaetter/gegenstaende`
- ausschließlich abenteuerspezifische NSCs dürfen im jeweiligen Abenteuerordner unter `nsc/` liegen
- ausschließlich abenteuerspezifische Monster dürfen im jeweiligen Abenteuerordner unter `monster/` liegen
- ausschließlich abenteuerspezifische Gegenstände dürfen im jeweiligen Abenteuerordner unter `gegenstaende/` liegen

Wenn eine zunächst lokale Figur, Kreatur oder ein Gegenstand später kampagnenweit relevant wird, soll eine primäre Datei in den passenden Ordner unter `datenblaetter/` überführt oder dort neu angelegt werden.

### Regeln für Bilder, Karten und sonstige Assets

Für visuelles Material wird zwischen kampagnenweiten und abenteuerspezifischen Assets unterschieden.

Kampagnenweit wiederverwendbare Assets liegen zentral in `assets/`, insbesondere unter:

- `assets/nscs/`
- `assets/monster/`
- `assets/gegenstaende/`
- `assets/orte/`
- `assets/karten/`
- `assets/handouts/`

Abenteuerspezifische Assets liegen im jeweiligen Abenteuerordner unter `assets/`, insbesondere unter:

- `abenteuer/[Abenteuer-ID]/assets/karten/`
- `abenteuer/[Abenteuer-ID]/assets/nscs/`
- `abenteuer/[Abenteuer-ID]/assets/monster/`
- `abenteuer/[Abenteuer-ID]/assets/gegenstaende/`
- `abenteuer/[Abenteuer-ID]/assets/handouts/`

Entscheidungsregel:

- Material mit kampagnenweiter oder mehrfacher Nutzung liegt im zentralen Ordner `assets/`
- Material, das nur für ein einzelnes Abenteuer benötigt wird, liegt im `assets/`-Ordner des jeweiligen Abenteuerordners

### Empfohlene Benennung von Asset-Dateien

- Bild- und Asset-Dateien sollen nach Möglichkeit aus der ID oder dem Abenteuerkontext ableitbar sein
- kampagnenweite Porträts, Karten oder Illustrationen sollen die zugehörige ID im Dateinamen tragen
- abenteuerspezifische Assets sollen zusätzlich die Abenteuer-ID im Dateinamen tragen

Beispiele:

- `assets/nscs/nsc-schattengilde-elgor-der-eismagier-portrait.png`
- `assets/gegenstaende/gegenstand-gnomengard-frostbrecher-zorn-des-ruhktar.png`
- `abenteuer/A06/assets/karten/a06-eisnadelfestung-uebersicht.jpg`
- `abenteuer/A06/assets/handouts/a06-runenfragment-01.png`

### Arbeitsablauf für Abenteuerordner

Vor dem Spiel werden Entwurf, Ausarbeitung, Szenen, Begegnungen, lokale Datenblätter, Handouts und Karten im Abenteuerordner gepflegt.

Während und nach dem Spiel werden die tatsächlichen Ereignisse in `abenteuer-sitzungsnotizen.md` festgehalten.

Danach werden bestätigte Folgen wie gewohnt in die kampagnenweiten Hauptdateien synchronisiert.

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
