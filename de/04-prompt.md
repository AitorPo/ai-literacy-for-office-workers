# Prompt

## Die einfache Analogie

Ein Prompt ist wie **einem neuen Mitarbeiter Anweisungen geben**. Die Qualität Ihrer Anweisungen bestimmt direkt die Qualität der Arbeit, die Sie zurückbekommen.

Denken Sie daran als **die einzige Art, wie Sie mit KI kommunizieren können** über das, was Sie wollen - also machen Sie es wirkungsvoll!

## Was einen guten Prompt ausmacht

### Das CLEAR-Framework

**C - Context (Kontext)**: Wie ist die Situation?
**L - Length (Länge)**: Wie lang sollte die Antwort sein?
**E - Examples (Beispiele)**: Zeigen Sie, wie gut aussieht
**A - Audience (Zielgruppe)**: Für wen ist das?
**R - Role (Rolle)**: Welche Rolle sollte die KI spielen?

## Prompt-Anatomie: Vorher und Nachher

### ❌ Schlechter Prompt
```
"Schreiben Sie eine E-Mail über die Besprechung."
```

**Probleme**: Vage, kein Kontext, unklare Zielgruppe, keine Spezifika

### ✅ Guter Prompt
```
**Rolle**: Sie sind ein professioneller Projektmanager.

**Kontext**: Unsere Q3-Planungsbesprechung für Dienstag 14 Uhr wurde wegen Verzögerungen bei der Budgetgenehmigung verschoben.

**Aufgabe**: Schreiben Sie eine E-Mail an das 8-köpfige Projektteam, die die Verschiebung erklärt.

**Zielgruppe**: Interne Teammitglieder (Mix aus technischen und geschäftlichen Rollen)

**Ton**: Professionell aber beruhigend

**Länge**: Unter 150 Wörtern halten

**Einschließen**: 
- Grund für die Verschiebung
- Neues Datum (wird diese Woche bestimmt)
- Was das Team in der Zwischenzeit tun soll
- Entschuldigung für die kurzfristige Mitteilung
```

## Die Prompt-Hierarchie: Von grundlegend bis fortgeschritten

### Level 1: Grundlegende Anfrage
```
"Fassen Sie diesen Artikel zusammen."
```

### Level 2: Spezifische Anfrage
```
"Fassen Sie diesen Artikel in 3 Aufzählungspunkten zusammen, die sich auf die hauptsächlichen Geschäftsauswirkungen konzentrieren."
```

### Level 3: Detaillierter Kontext
```
Rolle: Sie sind ein Geschäftsanalyst
Aufgabe: Fassen Sie diesen Artikel über KI in der Fertigung zusammen
Zielgruppe: C-Level-Führungskräfte, die schnelle Einblicke benötigen
Format: 3 Aufzählungspunkte
Fokus: Geschäftsauswirkungen und potenzieller ROI
Ton: Professionell und datengesteuert
```

### Level 4: Fortgeschritten mit Beispielen
```
Rolle: Sie sind ein Geschäftsanalyst
Aufgabe: Fassen Sie diesen Artikel über KI in der Fertigung zusammen
Zielgruppe: C-Level-Führungskräfte, die schnelle Einblicke benötigen

Format: Folgen Sie dieser Struktur:
• Geschäftsauswirkung: [wichtige Geschäftsauswirkungen]
• Finanzielle Auswirkungen: [Kosten, Einsparungen, ROI-Potenzial] 
• Strategische Empfehlungen: [was wir berücksichtigen sollten]

Ton: Professionell und datengesteuert
Länge: Jeder Aufzählungspunkt sollte maximal 1-2 Sätze haben

Beispiel für gute Ausgabe:
• Geschäftsauswirkung: KI-Implementierung könnte Produktionskosten um 15-20% reduzieren und gleichzeitig die Genauigkeit der Qualitätskontrolle verbessern.
```

## Prompt-Vorlagen für häufige Büroaufgaben

### E-Mail-Schreibung
```
Rolle: Professioneller [Ihre Berufsbezeichnung]
Aufgabe: Schreiben Sie eine [Typ] E-Mail
An: [Empfänger und Beziehung]
Über: [Hauptthema/Zweck]
Ton: [professionell/freundlich/dringend/entschuldigend]
Wichtige Punkte einschließen:
- [Punkt 1]
- [Punkt 2]
- [Punkt 3]
Länge: [Wort-/Absatzlimit]
```

### Dokumentenanalyse
```
Rolle: [relevante Expertenrolle]
Aufgabe: Analysieren Sie dieses [Dokumenttyp]
Fokus: [spezifische Aspekte zu analysieren]
Ausgabeformat: [Aufzählungen/Absätze/Tabelle]
Zielgruppe: [wer wird Ihre Analyse lesen]
Zu beantwortende Schlüsselfragen:
1. [Frage 1]
2. [Frage 2]
3. [Frage 3]
```

### Besprechungsvorbereitung
```
Rolle: Besprechungsleiter
Aufgabe: Erstellen Sie eine Agenda für [Besprechungstyp]
Teilnehmer: [Liste oder Beschreibung]
Dauer: [Zeitlimit]
Hauptziel: [primäres Ziel]
Zu behandelnde Hauptthemen:
- [Thema 1 mit Zeitzuteilung]
- [Thema 2 mit Zeitzuteilung]
Format: Zeitfenster und erwartete Ergebnisse einschließen
```

## Fortgeschrittene Prompting-Techniken

### Gedankenkette
Bitten Sie die KI, ihre Überlegungen zu zeigen:
```
"Bevor Sie Ihre endgültige Antwort geben, führen Sie mich Schritt für Schritt durch Ihren Denkprozess."
```

### Rollenspiel
Lassen Sie die KI eine spezifische Perspektive einnehmen:
```
"Sie sind ein skeptischer CFO, der diesen Vorschlag überprüft. Welche Bedenken würden Sie äußern?"
```

### Einschränkungen setzen
Definieren Sie klare Grenzen:
```
"Begrenzen Sie Ihre Antwort auf genau 3 Empfehlungen, jede mit einer spezifischen Aktion und einem Zeitplan."
```

### Mehrstufiges Prompting
Unterteilen Sie komplexe Aufgaben in Schritte:
```
"Identifizieren Sie zuerst die Hauptprobleme in diesem Dokument. Dann schlagen Sie für jedes Problem 2 Lösungen vor. Ordnen Sie schließlich alle Lösungen nach Machbarkeit."
```

## Häufige Prompting-Fehler

### 1. Zu vage sein ❌
```
"Helfen Sie mir bei dieser Präsentation."
```
**Lösung**: Spezifizieren Sie, welche Art von Hilfe Sie benötigen

### 2. Kein Kontext ❌
```
"Schreiben Sie einen Vorschlag."
```
**Lösung**: Erklären Sie die Situation, Zielgruppe und den Zweck

### 3. Annehmen, dass KI Ihr Geschäft kennt ❌
```
"Wie sollten wir mit der Johnson-Situation umgehen?"
```
**Lösung**: Hintergrundinformationen bereitstellen

### 4. Keine Qualitätskriterien ❌
```
"Machen Sie das besser."
```
**Lösung**: Definieren Sie, was "besser" spezifisch bedeutet

### 5. Einzelnen Prompt überladen ❌
```
"Analysieren Sie diesen Bericht, schreiben Sie eine Zusammenfassung, erstellen Sie Aktionspunkte, entwerfen Sie eine E-Mail an Stakeholder und schlagen Sie eine Präsentationsgliederung vor."
```
**Lösung**: In separate, fokussierte Prompts unterteilen

## Iterative Prompting-Strategie

### Runde 1: Das Fundament schaffen
```
"Schreiben Sie einen Entwurf für die Implementierung eines KI-Chatbot-Kundenservice."
```

### Runde 2: Verfeinern und spezifizieren
```
"Überarbeiten Sie diesen Vorschlag, um sich mehr auf Kosteneinsparungen zu konzentrieren und spezifische Erfolgsmetriken einzuschließen."
```

### Runde 3: Polieren und perfektionieren
```
"Machen Sie den Ton führungskräftefreundlicher und fügen Sie einen Abschnitt zur Risikominderung hinzu."
```

## Ihre Prompts testen und verbessern

### A/B-Test Ihre Prompts
Probieren Sie verschiedene Versionen aus und vergleichen Sie die Ergebnisse:

**Version A**: "Erklären Sie dieses Konzept einfach."
**Version B**: "Erklären Sie dieses Konzept, als würden Sie es einem intelligenten Kollegen beibringen, der neu in dem Bereich ist."

### Eine Prompt-Bibliothek führen
Speichern Sie Ihre besten Prompts zur Wiederverwendung:
- E-Mail-Vorlagen
- Analyse-Frameworks
- Besprechungsagenda-Formate
- Berichtsstrukturen

## Schlüsselerkenntnis

**Großartige Prompts = Großartige Ergebnisse**

Denken Sie an Prompting wie an das **Briefing eines Beraters**:
- Geben Sie ihnen Kontext
- Seien Sie spezifisch über das, was Sie wollen
- Definieren Sie Erfolgskriterien
- Bieten Sie Beispiele, wenn hilfreich

Die 30 Sekunden, die Sie für die Erstellung eines guten Prompts aufwenden, sparen Ihnen 10 Minuten Hin-und-Her-Verfeinerung.

---

**Weiter**: Lernen Sie über [Temperatur](./05-temperature.md) und wie Sie KI-Kreativität kontrollieren.