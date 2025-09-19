# Modell

## Die einfache Analogie

Wenn ein LLM das allgemeine Konzept eines "Automotors" ist, dann ist ein **Modell** eine spezifische Motor-Implementation, wie:

- **Economy-Modell**: Erledigt die Arbeit effizient (schnell, günstig)
- **Luxus-Modell**: Hochwertige Ausgabe mit Premium-Funktionen
- **Sport-Modell**: Spezialisiert auf spezifische Hochleistungsaufgaben
- **Hybrid-Modell**: Ausgewogener Ansatz für allgemeine Nutzung

Jedes Modell hat verschiedene Stärken, Kosten und ideale Anwendungsfälle.

## Was Modelle unterscheidet

### Trainingsdaten und Größe
- **Größere Modelle**: Mehr Trainingsdaten, besser bei komplexen Aufgaben, teurer
- **Kleinere Modelle**: Schneller, günstiger, gut für einfache Aufgaben
- **Spezialisierte Modelle**: Trainiert auf spezifischen Bereichen (Recht, Medizin, Programmierung)

### Leistungsmerkmale
- **Geschwindigkeit**: Wie schnell sie antworten
- **Kosten**: Wie viel sie pro Nutzung berechnen
- **Genauigkeit**: Wie zuverlässig ihre Ausgaben sind
- **Fähigkeiten**: Bei welchen Aufgabentypen sie glänzen

## Beliebte Modelle für Büroarbeit

### Allzweck-Modelle

**GPT-4 (OpenAI)**
- **Am besten für**: Komplexes Schreiben, Analyse, Problemlösung
- **Denken Sie**: Der Premium-Berater - teuer aber sehr fähig
- **Verwenden wenn**: Qualität wichtiger ist als Geschwindigkeit/Kosten

**GPT-3.5 (OpenAI)**
- **Am besten für**: Alltägliche Schreibaufgaben, schnelle Antworten
- **Denken Sie**: Der zuverlässige Generalist - gute Balance aus Qualität und Kosten
- **Verwenden wenn**: Sie schnelle, ausreichend gute Ergebnisse brauchen

**Claude 3 (Anthropic)**
- **Am besten für**: Lange Dokumente, sorgfältige Analyse, präzises Befolgen von Anweisungen
- **Denken Sie**: Der gewissenhafte Forscher - große Aufmerksamkeit für Details
- **Verwenden wenn**: Arbeit mit langen Texten oder sehr genaues Befolgen komplexer Anweisungen nötig

**Gemini (Google)**
- **Am besten für**: Integration mit Google Workspace, Websuche
- **Denken Sie**: Der Google-Ökosystem-Spezialist
- **Verwenden wenn**: Sie in Gmail, Google Docs und Google Sheets leben

### Spezialisierte Modelle

**Codex/GitHub Copilot**
- **Am besten für**: Code-Generierung und Programmieraufgaben
- **Verwenden wenn**: Code schreiben oder debuggen

**DALL-E, Midjourney**
- **Am besten für**: Bildgenerierung
- **Verwenden wenn**: Visuelle Inhaltserstellung benötigt

## Wie Ihr Unternehmen Modelle verwenden könnte

### Standard-Modelle
Ihr Unternehmen verwendet bestehende Modelle (wie ChatGPT) wie sie sind:
```
Mitarbeiter → ChatGPT → Allgemeine Antworten
```

### Fine-Tuned Modelle
Ihr Unternehmen trainiert ein Modell auf Ihren spezifischen Daten:
```
Mitarbeiter → IhrUnternehmen-GPT → Antworten im Stil/Wissen Ihres Unternehmens
```

**Beispiel**: Eine Anwaltskanzlei könnte ein Modell auf ihre vergangenen Falldateien fine-tunen, um beim Erstellen von Verträgen zu helfen, die dem Stil und Präzedenzfällen der Kanzlei entsprechen.

## Das richtige Modell für Ihre Aufgabe wählen

### Schneller Entscheidungsbaum

**Brauchen Sie es schnell und günstig?**
→ Kleinere/einfachere Modelle verwenden (GPT-3.5, Claude Instant)

**Ist Qualität kritisch?**
→ Premium-Modelle verwenden (GPT-4, Claude 3 Opus)

**Arbeiten mit langen Dokumenten?**
→ Modelle mit großen Kontextfenstern verwenden (Claude 3)

**Aktuelle Web-Informationen benötigt?**
→ Modelle mit Web-Zugang verwenden (Bing Chat, Bard)

**Hochspezielle/technische Aufgabe?**
→ Domain-spezifische Modelle verwenden (Codex für Programmierung)

## Praktische Bürobeispiele

### E-Mail-Schreibung
- **Einfache Antwort**: GPT-3.5 (schnell, günstig)
- **Wichtige Kundenkommunikation**: GPT-4 (höhere Qualität)
- **Rechtliche Korrespondenz**: Fine-tuned Rechtsmodell

### Dokumentenanalyse
- **Schnelle Zusammenfassung**: Claude Instant
- **Detaillierte Analyse**: Claude 3 Opus
- **Finanzdokument**: Finanz-spezialisiertes Modell

### Kreative Aufgaben
- **Brainstorming**: Jedes allgemeine Modell
- **Marketing-Copy**: GPT-4 (kreativer)
- **Technisches Schreiben**: Claude (präziser)

## Kostenüberlegungen

**Typische Kostenstruktur**:
- **Input-Tokens**: Was Sie an das Modell senden
- **Output-Tokens**: Was das Modell zurücksendet
- **Modell-Stufe**: Premium-Modelle kosten 10-20x mehr als Basis-Modelle

**Geld sparende Tipps**:
1. Einfachere Modelle für einfache Aufgaben verwenden
2. Prägnant in Ihren Prompts sein
3. Antworten nicht unnötig neu generieren
4. Das richtige Modell für den Job verwenden

## Schlüsselerkenntnis

Denken Sie an Modelle wie **verschiedene Spezialisten in Ihrem Büro**:
- Der schnelle Praktikant für einfache Aufgaben
- Der erfahrene Analyst für komplexe Arbeit
- Der Domain-Experte für spezialisierte Bedürfnisse

Wählen Sie basierend auf Ihren spezifischen Bedürfnissen: Geschwindigkeit, Qualität, Kosten und Spezialisierung.

---

**Weiter**: Lernen Sie über [Tokens](./03-token.md) und wie KI Text verarbeitet und berechnet.