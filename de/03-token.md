# Token

## Die einfache Analogie

Tokens sind wie **Puzzleteile**, die KI verwendet, um Text zu verarbeiten. Genau wie Sie ein komplexes Puzzle in handhabbare Teile zerbrechen könnten, zerlegt die KI Ihren Text in Chunks namens Tokens.

Denken Sie daran als die "Leseeinheiten" der KI - nicht immer ganze Wörter, aber bedeutungsvolle Chunks, die die KI verstehen und verarbeiten kann.

## Wie Wörter zu Tokens werden

### Einfache Beispiele

**Kurze/häufige Wörter** = 1 Token jeweils:
- "der" = 1 Token
- "und" = 1 Token  
- "Katze" = 1 Token

**Längere Wörter** könnten 1 Token sein:
- "Elefant" = 1 Token
- "wunderbar" = 1 Token

**Komplexe/ungewöhnliche Wörter** werden zerlegt:
- "Anthropomorphismus" = 2 Tokens: "Anthrop" + "omorphismus"
- "Telekommunikation" = 3 Tokens: "Tele" + "kommun" + "ikation"

**Zahlen und Satzzeichen**:
- "123" = 1 Token
- "1.234.567" = 4 Tokens: "1" + "." + "234" + "." + "567"
- "!!!" = 3 Tokens: "!" + "!" + "!"

### Aufschlüsselung eines echten Beispiels

**Text**: "Hallo! Wie geht es dir heute?"

**Tokens**: 
1. "Hallo"
2. "!"
3. "Wie"
4. "geht" 
5. "es"
6. "dir"
7. "heute"
8. "?"

**Gesamt**: 8 Tokens

## Warum Tokens für Ihre Arbeit wichtig sind

### 1. Kostenauswirkung 💰

KI-Services berechnen nach Tokens:
- **Input-Tokens**: Was Sie senden (Ihr Prompt)
- **Output-Tokens**: Was die KI zurücksendet (die Antwort)

**Beispiel-Kostenberechnung**:
```
Ihr Prompt: 100 Tokens
KI-Antwort: 300 Tokens
Gesamt: 400 Tokens berechnet

Wenn das Modell $0,002 pro 1.000 Tokens kostet:
Ihre Kosten = 400 × $0,002 ÷ 1.000 = $0,0008 (weniger als ein Cent)
```

### 2. Längenbeschränkungen 📏

Jedes Modell hat ein **Kontextfenster** - maximale Tokens, die es verarbeiten kann:

| Modell | Kontextfenster | Entsprechende Seiten |
|-------|----------------|------------------|
| GPT-3.5 | 4.000 Tokens | ~3 Seiten |
| GPT-4 | 8.000-32.000 Tokens | ~6-25 Seiten |
| Claude 3 | 200.000 Tokens | ~150 Seiten |

**Was passiert, wenn Sie das Limit überschreiten?**
- KI "vergisst" frühere Teile langer Gespräche
- Große Dokumente werden abgeschnitten
- Komplexe Aufgaben können nicht abgeschlossen werden

### 3. Leistungsauswirkung ⚡

Mehr Tokens = langsamere Antwortzeit und höhere Kosten
- Halten Sie Prompts prägnant aber klar
- Teilen Sie große Aufgaben in kleinere Chunks auf
- Verwenden Sie angemessene Modelle für die Dokumentgröße

## Praktische Bürostrategien

### Effiziente Prompts schreiben

**Ineffizient** (verschwendet Tokens):
```
"Ich würde es sehr schätzen, wenn Sie mir bitte beim Schreiben einer E-Mail an unseren Kunden bezüglich der Besprechung helfen könnten, die wir für nächsten Dienstag geplant hatten, und ich muss sie auf Donnerstag verschieben, und ich möchte sicherstellen, dass der Ton professionell und entschuldigend ist."
```
*Token-Anzahl: ~55*

**Effizient** (spart Tokens):
```
"Schreiben Sie eine professionelle, entschuldigende E-Mail, die die Dienstag-Kundenbesprechung auf Donnerstag verschiebt."
```
*Token-Anzahl: ~18*

### Lange Dokumente verwalten

**Problem**: 50-seitiger Bericht überschreitet Token-Limit

**Lösungen**:
1. **Aufteilen**: 10 Seiten auf einmal analysieren
2. **Erst zusammenfassen**: KI eine Zusammenfassung erstellen lassen, dann detaillierte Fragen stellen
3. **Schlüsselabschnitte extrahieren**: Fokus auf spezifische Kapitel/Abschnitte
4. **Hochkapazitätsmodelle verwenden**: Claude 3 für sehr lange Dokumente

### Token-Schätztipps

**Schnelle Schätzung**:
- **1 Token ≈ 4 Zeichen** (einschließlich Leerzeichen)
- **1 Token ≈ 0,75 Wörter** im Durchschnitt
- **100 Wörter ≈ 130-150 Tokens**

**Tools zur exakten Zählung**:
- OpenAIs Tokenizer-Tool
- Zeichen-/Wortzahl ÷ 4 (grobe Schätzung)

## Häufige Token-bezogene Probleme

### "Gespräch zu lang"-Fehler
**Problem**: Multi-Turn-Gespräch überschreitet Kontextfenster
**Lösung**: Neues Gespräch beginnen oder vorherige Diskussion zusammenfassen

### "Unvollständige Antwort" 
**Problem**: KI hört mitten im Satz auf
**Lösung**: KI bitten fortzufahren, oder Anfrage in kleinere Teile aufteilen

### Hohe unerwartete Kosten
**Problem**: Rechnungen sind höher als erwartet
**Lösung**: Token-Nutzung überwachen, einfachere Modelle für einfache Aufgaben verwenden

## Geld sparende Token-Tipps

1. **Seien Sie prägnant**: Unnötige Wörter aus Prompts entfernen
2. **Beispiele sparsam verwenden**: Jedes Beispiel fügt Tokens hinzu
3. **Richtiges Modell wählen**: GPT-4 nicht für einfache Aufgaben verwenden
4. **Kontext wiederverwenden**: Auf vorherigen Antworten aufbauen statt Kontext zu wiederholen
5. **Ähnliche Anfragen bündeln**: Mehrere ähnliche Aufgaben in einem Prompt bearbeiten

## Schlüsselerkenntnis

Tokens sind die **Währung** der KI-Interaktion:
- Sie bestimmen Ihre Kosten
- Sie begrenzen, wie viel Sie auf einmal verarbeiten können
- Sie beeinflussen die Antwortgeschwindigkeit

Denken Sie an Tokens wie **Textdatenverbrauch** - seien Sie achtsam, aber obsessieren Sie nicht über jeden einzelnen Token.

---

**Weiter**: Meistern Sie die Kunst des [Prompting](./04-prompt.md), um bessere KI-Antworten zu erhalten.