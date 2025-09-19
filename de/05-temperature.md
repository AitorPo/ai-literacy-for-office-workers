# Temperatur (Kreativitätskontrolle)

## Die einfache Analogie

Temperatur ist wie der **"Kreativitätsregler"** oder **"Zufallskontrolle"** für KI-Antworten. Denken Sie daran wie die Anpassung der Persönlichkeit Ihres KI-Assistenten:

- **Niedrige Temperatur (0,1-0,3)**: Der methodische, vorhersagbare Kollege, der immer dieselbe Antwort gibt
- **Hohe Temperatur (0,7-1,0)**: Der kreative, spontane Kollege, der Sie mit neuen Ideen überrascht

## Die Skala verstehen

### Temperaturbereich: 0,0 bis 1,0

**0,0 - Roboter-Modus** 🤖
- Völlig vorhersagbar
- Gleiche Eingabe = gleiche Ausgabe jedes Mal
- Fokussiert auf statistisch wahrscheinlichste Antwort

**0,2 - Analyst-Modus** 📊
- Hochkonsistent und fokussiert
- Geringfügige Variationen in der Formulierung
- Gut für faktische, präzise Aufgaben

**0,5 - Ausgewogener Modus** ⚖️
- Mix aus Konsistenz und Kreativität
- Angemessene Vielfalt in Antworten
- Gute Allzweck-Einstellung

**0,8 - Kreativer Modus** 🎨
- Hohe Vielfalt und Kreativität
- Unerwartete aber relevante Antworten
- Gut für Brainstorming und Innovation

**1,0 - Joker-Modus** 🎲
- Maximale Zufälligkeit
- Kann unvorhersagbar oder seltsam sein
- Sparsam für maximale Kreativität verwenden

## Wann welche Temperatur verwenden

### Niedrige Temperatur (0,1-0,3) ❄️

**Am besten für**:
- Datenextraktion und -analyse
- Code-Generierung
- Rechtsdokumentenprüfung
- Finanzberechnungen
- Befolgen strenger Verfahren
- Faktische Frage-Antwort

**Beispielaufgaben**:
```
✅ "Extrahieren Sie alle E-Mail-Adressen aus dieser Kontaktliste"
✅ "Berechnen Sie den quartalsweisen ROI aus diesen Daten"
✅ "Schreiben Sie eine Standard-Datenschutzklausel"
✅ "Debuggen Sie diese Excel-Formel"
```

**Was Sie erhalten**: Konsistente, genaue, fokussierte Antworten

### Mittlere Temperatur (0,4-0,6) 🌡️

**Am besten für**:
- Allgemeines Geschäftsschreiben
- E-Mail-Komposition
- Berichtszusammenfassungen
- Prozessdokumentation
- Kundenservice-Antworten

**Beispielaufgaben**:
```
✅ "Schreiben Sie eine professionelle E-Mail, die diesen Anbietervorschlag ablehnt"
✅ "Fassen Sie die Schlüsselpunkte aus diesem Besprechungsprotokoll zusammen"
✅ "Erstellen Sie ein Standardverfahren für das Onboarding"
```

**Was Sie erhalten**: Professionell, zuverlässig, mit leichten Variationen

### Hohe Temperatur (0,7-1,0) 🔥

**Am besten für**:
- Brainstorming-Sitzungen
- Kreative Marketing-Inhalte
- Innovations-Workshops
- Problemlösungserkundung
- Story-Erstellung für Präsentationen

**Beispielaufgaben**:
```
✅ "Generieren Sie 20 kreative Namen für unsere neue Produktlinie"
✅ "Was sind einige unkonventionelle Lösungen zur Reduzierung der Bürokosten?"
✅ "Erstellen Sie eine fesselnde Geschichte, um unsere Unternehmenswerte zu erklären"
✅ "Brainstormen Sie einzigartige Teambuilding-Aktivitäten"
```

**Was Sie erhalten**: Abwechslungsreiche, kreative, überraschende Ideen

## Praxisbeispiele aus dem Büro

### Szenario: Kunden-Update-E-Mail schreiben

**Niedrige Temperatur (0,2) Antwort**:
> Sehr geehrte/r [Kunde],
> 
> Ich schreibe, um Ihnen ein Update zum Status Ihres Projekts zu geben. Die Entwicklungsphase wurde wie geplant abgeschlossen. Die Tests beginnen nächste Woche wie vorgesehen.
> 
> Bitte lassen Sie mich wissen, wenn Sie Fragen haben.

**Hohe Temperatur (0,8) Antwort**:
> Hallo [Kunde],
> 
> Aufregende Neuigkeiten von Ihrer Projektfront! Wir haben die Entwicklungsphase erfolgreich abgeschlossen und ich freue mich, Ihnen mitteilen zu können, dass alles über den Erwartungen läuft.
> 
> Unser Team bereitet sich bereits auf die Testphase nächste Woche vor, und wir sind zuversichtlich, dass Ihnen gefallen wird, was wir gebaut haben.

**Verschiedene Zwecke, verschiedene Temperaturen!**

### Szenario: Verkaufsdatenanalyse

**Niedrige Temperatur**: Perfekt für das Extrahieren spezifischer Zahlen und Trends
**Hohe Temperatur**: Schlecht - könnte Datenpunkte "halluzinieren"

### Szenario: Marketing-Kampagnen-Ideen

**Niedrige Temperatur**: Generische, sichere Ideen
**Hohe Temperatur**: Einzigartige, mutige Konzepte, die hervorstechen

## Wie man Temperatur kontrolliert

### In ChatGPT Plus/API
- Verfügbar in API und einigen erweiterten Schnittstellen
- Vor Gesprächsbeginn einstellen

### In anderen Tools
Viele Tools haben ähnliche Kontrollen mit anderen Namen:
- **"Kreativ" vs "Präzise"** (Bing Chat)
- **"Kreativer" vs "Ausgewogener" vs "Präziser"** (Claude)
- **Kreativitätsregler** (Verschiedene KI-Schreibtools)

### Durch Prompting
Auch ohne direkte Temperaturkontrolle können Sie Kreativität beeinflussen:

**Für niedrigen Temperatur-Effekt**:
```
"Geben Sie mir die genaueste, faktischste Antwort. Seien Sie präzise und konsistent."
```

**Für hohen Temperatur-Effekt**:
```
"Seien Sie kreativ und geben Sie mir mehrere einzigartige Perspektiven. Denken Sie über den Tellerrand hinaus."
```

## Temperatur-Strategie für verschiedene Rollen

### Für Buchhalter/Finanzen
- **Standard**: Niedrige Temperatur (0,2)
- **Ausnahme**: Hohe Temperatur für Kostensparideen

### Für Marketing/Kreativ
- **Standard**: Hohe Temperatur (0,7-0,8)
- **Ausnahme**: Niedrige Temperatur für Datenanalyse und Berichterstattung

### Für Betrieb/Prozess
- **Standard**: Niedrige Temperatur (0,2-0,3)
- **Ausnahme**: Mittlere Temperatur für Prozessverbesserungsideen

### Für Strategie/Planung
- **Standard**: Mittlere Temperatur (0,5)
- **Ausnahme**: Hohe Temperatur für Innovationssitzungen

## Häufige Temperatur-Fehler

### Fehler 1: Hohe Temperatur für Fakten verwenden ❌
```
Temperatur: 0,9
Prompt: "Wie hoch war der Umsatz unseres Unternehmens letztes Jahr?"
Ergebnis: KI könnte Zahlen erfinden
```

### Fehler 2: Niedrige Temperatur für Kreativität verwenden ❌
```
Temperatur: 0,1
Prompt: "Geben Sie mir kreative Marketing-Ideen"
Ergebnis: Generische, vorhersagbare Vorschläge
```

### Fehler 3: Vergessen anzupassen ❌
Dieselbe Temperatur für alle Aufgaben verwenden, unabhängig vom Bedarf

## Schnelle Entscheidungshilfe

**Fragen Sie sich**: "Möchte ich, dass die KI mehr wie... ist"

🤖 **Ein präziser Rechner?** → Niedrige Temperatur
⚖️ **Ein zuverlässiger Kollege?** → Mittlere Temperatur  
🎨 **Ein kreativer Brainstorming-Partner?** → Hohe Temperatur

## Profi-Tipps

1. **Beginnen Sie mittig, dann anpassen**: Mit 0,5 beginnen und basierend auf Ergebnissen modifizieren
2. **Aufgabe anpassen**: Kreativität für kreative Aufgaben, Präzision für präzise Aufgaben
3. **Experimentieren**: Denselben Prompt bei verschiedenen Temperaturen versuchen
4. **Zielgruppe berücksichtigen**: Konservative Zielgruppen bevorzugen Niedrig-Temperatur-Ausgaben
5. **Einstellungen speichern**: Merken Sie sich, was für wiederkehrende Aufgaben funktioniert

## Schlüsselerkenntnis

Temperatur handelt von der **Anpassung der KI-Persönlichkeit an Ihre Aufgabe**:

- **Brauchen Sie Zuverlässigkeit und Genauigkeit?** Kreativität herunterdrehen
- **Brauchen Sie Innovation und Vielfalt?** Kreativität hochdrehen
- **Nicht sicher?** In der Mitte beginnen und anpassen

Denken Sie daran wie verschiedene Arten von Beratern für verschiedene Arten von Arbeit zu engagieren.

---

**Weiter**: Entdecken Sie [Agenten](./06-agent.md) und wie KI Aktionen ausführen kann, nicht nur Ratschläge geben.