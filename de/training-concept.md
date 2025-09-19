# Training in der KI

## Die einfache Analogie

KI-Training ist wie **einen sehr intelligenten Schüler unterrichten**, indem man ihm Millionen von Beispielen zeigt, bis er lernt, Muster zu erkennen und Vorhersagen zu treffen.

Stellen Sie sich vor, jemandem beizubringen, E-Mail-Spam zu erkennen, indem Sie ihm 100.000 E-Mails zeigen, die als "Spam" oder "kein Spam" markiert sind, bis er neue E-Mails selbstständig genau identifizieren kann.

## Was ist KI-Training?

### Definition
Training ist der Prozess, einem KI-Modell beizubringen, Aufgaben auszuführen durch:
- **Füttern mit massiven Datenmengen** (Text, Bilder, Code, etc.)
- **Zeigen von Mustern und Beziehungen** in diesen Daten
- **Anpassung seiner internen Parameter** basierend auf dem Gelernten
- **Testen seiner Leistung** und Verbesserungen vornehmen

### Der Lernprozess
1. **Dateneingabe**: KI erhält Millionen von Beispielen
2. **Mustererkennung**: KI identifiziert statistische Beziehungen
3. **Parameteranpassung**: KIs "Gehirn" wird fein abgestimmt
4. **Validierung**: KIs Vorhersagen werden auf Genauigkeit getestet
5. **Iteration**: Prozess wiederholt sich bis Leistung zufriedenstellend ist

## Arten des KI-Trainings

### 1. Initial-/Vortraining 🧠
**Was es ist**: Der KI Grundlagenwissen beibringen

**Für Sprachmodelle**:
- KI liest Millionen von Büchern, Artikeln, Websites
- Lernt Grammatik, Vokabular, Fakten und Argumentationsmuster
- Entwickelt allgemeines Sprachverständnis
- Dauert Monate und massive Rechenleistung

**Beispiel**: GPT-4s Vortraining umfasste das Lesen des größten Teils des öffentlichen Internets

**Analogie**: Wie jemandem eine komplette Ausbildung vom Kindergarten bis zum Hochschulabschluss zu geben

### 2. Fine-Tuning 🎯
**Was es ist**: Die KI für spezifische Aufgaben oder Bereiche spezialisieren

**Prozess**:
- Mit vortrainiertem Modell beginnen
- Auf spezifischen, kuratierten Datensatz trainieren
- Für bestimmten Anwendungsfall oder Stil anpassen
- Viel schneller als Vortraining

**Beispiel**: Allgemeines GPT-4 nehmen und spezifisch auf Rechtsdokumenten trainieren, um einen Rechts-KI-Assistenten zu erstellen

**Analogie**: Wie einen Hochschulabsolventen zu spezialisierter Berufsausbildung zu schicken

### 3. Verstärkungslernen durch menschliches Feedback (RLHF) 👍
**Was es ist**: KI beibringen, sich an menschlichen Präferenzen zu orientieren

**Prozess**:
- KI generiert mehrere Antworten
- Menschen bewerten, welche Antworten besser sind
- KI lernt, von Menschen bevorzugte Antworten zu bevorzugen
- Resultiert in hilfreicherer, harmloserer, ehrlicherer KI

**Beispiel**: ChatGPT trainieren, hilfreiche Antworten zu geben statt nur Text zu vervollständigen

**Analogie**: Wie einen persönlichen Coach zu haben, der konstant Feedback zur Leistung gibt

## Trainingsdaten: Wovon KI lernt

### Text-Trainingsdaten 📚
**Quellen**:
- Bücher und Literatur
- Wikipedia und Enzyklopädien
- Nachrichtenartikel und Zeitschriften
- Webseiten und Foren
- Akademische Arbeiten
- Code-Repositories

**Was KI lernt**:
- Sprachmuster und Grammatik
- Faktisches Wissen (kann aber veraltet werden)
- Argumentations- und Logikmuster
- Schreibstile und Formate
- Kulturelle und soziale Konzepte

### Qualität vs. Quantität
**Hochwertige Daten** ✅:
- Genaue und faktengeprüfte Informationen
- Gut geschriebener und klarer Text
- Diverse Perspektiven und Quellen
- Aktuelle und relevante Inhalte

**Minderwertige Daten** ❌:
- Fehlinformationen und falsche Behauptungen
- Schlecht geschriebener oder verstümmelter Text
- Voreingenommene oder diskriminierende Inhalte
- Veraltete Informationen

**Auswirkung**: "Müll rein, Müll raus" - schlechte Trainingsdaten führen zu schlechter KI-Leistung

## Wie Training das KI-Verhalten beeinflusst

### 1. Wissens-Stichtage 📅
**Was es bedeutet**: KI kennt nur Informationen bis zu dem Zeitpunkt, als sie trainiert wurde

**Beispiel**: Wenn KI Anfang 2024 trainiert wurde, kennt sie keine Ereignisse von Ende 2024

**Büroauswirkung**: KI kennt möglicherweise nicht:
- Jüngste Software-Updates
- Aktuelle Marktbedingungen
- Neue Vorschriften oder Richtlinien
- Jüngste Unternehmensänderungen

### 2. Verzerrungen und Einschränkungen 🎭
**Woher sie kommen**:
- In Trainingsdaten vorhandene Verzerrungen
- Überrepräsentation bestimmter Perspektiven
- Historische Verzerrungen in geschriebenem Inhalt
- Geografische oder kulturelle Beschränkungen

**Beispiele**:
- KI könnte Geschlechterstereotype aus Trainingsdaten widerspiegeln
- Könnte besser in Englisch als in anderen Sprachen sein
- Könnte veraltete Ansichten über Technologie oder Gesellschaft haben

### 3. Stärken und Schwächen 💪
**KI glänzt typischerweise bei**:
- Themen, die in Trainingsdaten gut repräsentiert sind
- Häufigen Mustern und oft diskutierten Themen
- Allgemeinwissen und weit akzeptierten Fakten

**KI hat typischerweise Schwierigkeiten mit**:
- Hochspezialisierten oder Nischenthemen
- Jüngsten Entwicklungen oder aktuellen Nachrichten
- Persönlichen oder privaten Informationen
- Aufgaben, die reale Erfahrung erfordern

## Trainingsprozess-Zeitplan

### Large Language Models (wie GPT-4)
```
Vortraining: 6-12 Monate
├── Datensammlung und -bereinigung: 2-3 Monate
├── Modellarchitektur-Design: 1-2 Monate  
├── Training-Berechnung: 3-6 Monate
└── Erste Tests und Validierung: 1-2 Monate

Fine-Tuning: 1-4 Wochen
├── Spezialisierte Datensatzvorbereitung: 3-7 Tage
├── Training auf spezifischem Bereich: 5-14 Tage
└── Tests und Optimierung: 3-7 Tage

RLHF-Training: 2-8 Wochen
├── Menschliches Feedback-Sammlung: 1-4 Wochen
├── Präferenzlernen: 3-14 Tage
└── Finales Alignment-Training: 3-14 Tage
```

### Kosten und Ressourcen 💰
**Vortraining eines großen Modells**:
- Kosten: $10-100+ Millionen
- Berechnung: Tausende spezialisierte Chips
- Energie: Entspricht der Stromversorgung einer kleinen Stadt
- Zeit: Monate kontinuierlicher Berechnung

**Fine-Tuning**:
- Kosten: $1.000-100.000
- Berechnung: Dutzende bis Hunderte von Chips
- Zeit: Tage bis Wochen

## Training für Ihre Organisation

### Wann Ihr Unternehmen KI trainieren könnte

**1. Benutzerdefiniertes Fine-Tuning**
- Sie haben große Mengen unternehmensspezifischer Daten
- Brauchen KI, die Ihren Branchenjargon versteht
- Wollen KI, die Ihrem Unternehmensstil und -verfahren folgt
- Benötigen spezialisiertes Wissen, das nicht in allgemeinen Modellen ist

**2. Bereichsspezifische Anwendungen**
- Anwaltskanzleien trainieren auf Fallrecht und Verträgen
- Medizinische Organisationen trainieren auf klinischen Daten
- Finanzunternehmen trainieren auf Marktanalyse
- Fertigungsunternehmen trainieren auf technischen Spezifikationen

### Trainingsdaten-Vorbereitung

**Schritte für Unternehmens-Training**:
1. **Datensammlung**
   - Relevante Unternehmensdokumente sammeln
   - E-Mails, Berichte, Verfahren einschließen
   - Kundeninteraktionen sammeln
   - Nach Thema und Qualität organisieren

2. **Datenbereinigung**
   - Sensible oder vertrauliche Informationen entfernen
   - Formatierungsprobleme und Fehler beheben
   - Duplikate und irrelevante Inhalte entfernen
   - Datenqualität und -genauigkeit sicherstellen

3. **Datenmarkierung** (falls benötigt)
   - Beispiele als gut/schlecht markieren
   - Nach Typ oder Thema kategorisieren
   - Qualität oder Nützlichkeit bewerten
   - Richtige Antworten für Training bereitstellen

4. **Datenschutz und Sicherheit**
   - Persönliche Informationen entfernen
   - Compliance mit Vorschriften sicherstellen
   - Zugriffskontrollen implementieren
   - Datenspeicherung und -löschung planen

## Trainingsbeschränkungen verstehen

### 1. Statisches Wissen ⏰
**Problem**: KI-Wissen friert zum Trainingszeitpunkt ein
**Auswirkung**: Kennt keine jüngsten Ereignisse oder Änderungen
**Lösung**: Regelmäßiges Retraining oder Tools verwenden, die auf aktuelle Informationen zugreifen

### 2. Trainingsverzerrungen 🎯
**Problem**: KI erbt Verzerrungen aus Trainingsdaten
**Auswirkung**: Könnte verzerrte oder unfaire Antworten geben
**Lösung**: Diverse Trainingsdaten und Verzerrungstests

### 3. Halluzinationstendenz 🌟
**Problem**: KI generiert plausibel klingende aber falsche Informationen
**Auswirkung**: Könnte selbstbewusst falsche Fakten behaupten
**Lösung**: Wichtige Informationen immer überprüfen

### 4. Kontextbeschränkungen 📏
**Problem**: KI kann nur begrenzte Informationsmengen auf einmal berücksichtigen
**Auswirkung**: Könnte frühere Teile langer Gespräche "vergessen"
**Lösung**: Schlüsselpunkte in langen Interaktionen zusammenfassen

## Praktische Auswirkungen für Büroangestellte

### 1. KI-Fähigkeiten verstehen
- KI glänzt bei Aufgaben ähnlich ihren Trainingsdaten
- Leistung variiert nach Thema und Bereich
- Jüngste Informationen könnten fehlen oder veraltet sein

### 2. Mit KI-Beschränkungen arbeiten
- Kontext bereitstellen, der der KI fehlen könnte
- Fakten und aktuelle Informationen überprüfen
- Sich möglicher Verzerrungen in Antworten bewusst sein

### 3. Das richtige KI-Tool wählen
- Allgemeine Modelle für breite Aufgaben
- Spezialisierte Modelle für bereichsspezifische Arbeit
- Trainingsdatum für zeitkritische Informationen berücksichtigen

### 4. Ihre Fähigkeiten zukunftssicher machen
- Verstehen, dass KI-Fähigkeiten sich mit besserem Training verbessern werden
- Lernen, KI-Ausgaben kritisch zu bewerten
- Über neue Modellveröffentlichungen und -fähigkeiten informiert bleiben

## Schlüsselfragen zum KI-Training

### "Woher weiß ich, womit eine KI trainiert wurde?"
- Dokumentation des KI-Anbieters überprüfen
- Nach Informationen über Trainingsdatenquellen suchen
- Sich bewusst sein, dass vollständige Datensätze oft nicht offengelegt werden

### "Warum gibt KI manchmal falsche Antworten?"
- Trainingsdaten enthielten falsche Informationen
- KI macht statistische Vermutungen, schlägt nicht Fakten nach
- Einige Themen waren in Training unterrepräsentiert

### "Kann KI aus unserem Gespräch lernen?"
- Die meisten kommerziellen KIs lernen nicht aus individuellen Gesprächen
- Jedes Gespräch beginnt "frisch" ohne Erinnerung an frühere Benutzer
- Einige Systeme könnten Gespräche nutzen, um zukünftige Versionen zu verbessern

### "Wie oft wird KI neu trainiert?"
- Große Modelle werden alle 1-2 Jahre neu trainiert
- Fine-Tuned Modelle könnten häufiger aktualisiert werden
- Einige Systeme haben kontinuierliche Lernfähigkeiten

## Schlüsselerkenntnis

**Training ist das, was KI ihre Fähigkeiten und Beschränkungen gibt.**

Training verstehen hilft Ihnen:
- **Realistische Erwartungen setzen** für das, was KI kann und nicht kann
- **Erkennen, warum KI sich verhält** wie sie es tut
- **Angemessene KI-Tools wählen** für Ihre Bedürfnisse
- **Effektiv mit KI arbeiten** durch Verstehen ihres Hintergrunds

Denken Sie an KI-Training wie **jemanden mit einem spezifischen Bildungshintergrund einzustellen** - sie werden in Bereichen glänzen, die sie studiert haben, aber könnten Hilfe bei Themen außerhalb ihres Trainings brauchen.

**Denken Sie daran**: KI ist nur so gut wie das, womit sie trainiert wurde, also berücksichtigen Sie immer die Quelle und Aktualität ihres Wissens.

---

**Verwandte Konzepte**: [Large Language Model](./01-large-language-model.md) | [Fine-Tuning](./08-fine-tuning.md) | [Halluzination](./07-hallucination.md)