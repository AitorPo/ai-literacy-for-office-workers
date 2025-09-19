# KI-Schnellreferenz-Spickzettel

*Drucken Sie diese Seite für einfache Referenz an Ihrem Schreibtisch*

## 🧠 Kern-KI-Konzepte

| Konzept | Ein-Satz-Beschreibung | Wann verwenden |
|---------|-------------------------|-------------|
| **LLM** | Autocomplete-Engine, die Sprachmuster aus dem Internet lernte | KI-Fähigkeiten/-Grenzen verstehen |
| **Modell** | Spezifische KI-"Engine", die für verschiedene Aufgaben optimiert ist | Das richtige Tool wählen |
| **Token** | Text-Chunks, die KI verarbeitet (beeinflusst Kosten & Grenzen) | Kosten & Länge verwalten |
| **Prompt** | Ihr Anleitungshandbuch für KI | Bessere Ergebnisse erhalten |
| **Temperatur** | Kreativitätsregler (niedrig=vorhersagbar, hoch=kreativ) | Aufgabe an Ausgabestil anpassen |
| **Agent** | KI, die Aktionen ausführen kann, nicht nur beraten | Mehrstufige Aufgaben automatisieren |
| **Halluzination** | Wenn KI selbstbewusst falsche Informationen behauptet | KI-Ausgabe faktenprüfen |
| **Fine-tuning** | KI auf den spezifischen Daten Ihres Unternehmens trainieren | Spezialisierte KI erstellen |

---

## 🎯 Temperatur-Schnellguide

| Aufgabentyp | Temperatur | Beispiel |
|-----------|-------------|---------|
| **Daten/Fakten** | 0,1-0,3 ❄️ | Zahlen extrahieren, Berechnungen |
| **Geschäftsschreiben** | 0,4-0,6 🌡️ | E-Mails, Berichte, Verfahren |
| **Kreative Aufgaben** | 0,7-1,0 🔥 | Brainstorming, Marketing-Ideen |

---

## ✍️ Prompt-Formel

**Das CLEAR-Framework:**
```
Context (Kontext): Wie ist die Situation?
Length (Länge): Wie lang sollte die Antwort sein?
Examples (Beispiele): Zeigen Sie, wie gut aussieht
Audience (Zielgruppe): Für wen ist das?
Role (Rolle): Welche Rolle sollte die KI spielen?
```

**Schnelle Vorlage:**
```
Rolle: Sie sind ein [Berufsbezeichnung]
Aufgabe: [Was Sie getan haben möchten]
Kontext: [Relevanter Hintergrund]
Zielgruppe: [Wer wird das sehen]
Format: [Wie Ausgabe strukturieren]
Ton: [Professionell/locker/etc.]
```

---

## 🚨 Halluzinations-Warnzeichen

**Immer überprüfen**, wenn KI bereitstellt:
- ❌ Spezifische Statistiken oder Prozentsätze
- ❌ Zitate, Studien oder Quellen
- ❌ Aktuelle Ereignisse oder jüngste Daten
- ❌ Unternehmensspezifische Informationen
- ❌ Technische Konfigurationsschritte
- ❌ Rechts- oder Compliance-Beratung

**Warnzeichen:**
- Übermäßig spezifische Details (genau 1.247 Teilnehmer)
- Perfekte runde Zahlen (genau 25% Steigerung)
- Zu-günstige Quellen
- Selbstbewusste Gewissheit über unsichere Themen

---

## 💰 Token-Kostenmanagement

**Schnelle Schätzung:**
- 1 Token ≈ 4 Zeichen
- 1 Token ≈ 0,75 Wörter
- 100 Wörter ≈ 130-150 Tokens

**Geld sparende Tipps:**
- ✅ Einfachere Modelle für einfache Aufgaben verwenden
- ✅ Prägnant aber klar in Prompts sein
- ✅ Nicht unnötig neu generieren
- ✅ Richtiges Modell für den Job wählen

---

## 🔧 Modell-Auswahlguide

**Schneller Entscheidungsbaum:**
- **Brauchen Sie es schnell & günstig?** → GPT-3.5, Claude Instant
- **Ist Qualität kritisch?** → GPT-4, Claude 3 Opus
- **Lange Dokumente?** → Claude 3 (großer Kontext)
- **Aktuelle Web-Info?** → Bing Chat, Bard
- **Programmieraufgaben?** → GitHub Copilot, GPT-4

---

## ✅ Sichere KI-Praktiken

### **Grünes Licht** (Allgemein sicher) 🟢
- Brainstorming und Ideenfindung
- Schreibhilfe und Bearbeitung
- Vorlagen und Frameworks erstellen
- Konzepte erklären
- Entwurfserstellung

### **Gelbes Licht** (Schlüsselfakten überprüfen) 🟡
- Geschäftsberichte und Präsentationen
- Prozessdokumentation
- Kundenkommunikation
- Datenanalyse-Zusammenfassungen

### **Rotes Licht** (Hohes Risiko - Alles überprüfen) 🔴
- Finanzentscheidungen und Berechnungen
- Rechtliche Compliance-Informationen
- Technische Implementierungsschritte
- Medizinische oder Sicherheitsberatung
- Aktuelle Ereignisse und jüngste Daten

---

## 🎭 Rollenbasierte KI-Nutzung

### **Buchhalter/Finanzen**
- Standard: Niedrige Temperatur
- Am besten für: Datenextraktion, Berechnungen, Finanzmodellierung
- Überprüfen: Alle Zahlen, Formeln, Compliance-Info

### **Marketing/Kreativ**
- Standard: Hohe Temperatur
- Am besten für: Inhaltserstellung, Brainstorming, Kampagnen-Ideen
- Überprüfen: Statistiken, Konkurrenten-Behauptungen, Marktdaten

### **Betrieb/Prozess**
- Standard: Niedrige Temperatur
- Am besten für: Dokumentation, Verfahren, Workflow-Optimierung
- Überprüfen: Technische Schritte, Compliance-Anforderungen

### **Verkauf**
- Standard: Mittlere Temperatur
- Am besten für: E-Mail-Vorlagen, Vorschlagsschreibung, Einwandbehandlung
- Überprüfen: Produktspezifikationen, Preise, Konkurrenten-Info

### **HR**
- Standard: Mittlere Temperatur
- Am besten für: Richtlinienerklärungen, Kommunikationsvorlagen
- Überprüfen: Rechtliche Anforderungen, Unternehmensrichtlinien

---

## 🆘 Notfall-Fehlerbehebung

**"KI gab mir falsche Informationen"**
→ Prüfen Sie, ob es halluzinations-anfällige Inhalte waren → Mit Originalquellen überprüfen

**"Antwort ist zu generisch"**
→ Mehr Kontext zum Prompt hinzufügen → Rolle und Zielgruppe spezifizieren

**"KI folgt meinen Anweisungen nicht"**
→ Komplexe Anfragen in Schritte unterteilen → Beispiele im Prompt verwenden

**"Antwort ist zu lang/kurz"**
→ Exakte Längenanforderungen spezifizieren → Aufzählungspunkte für Struktur verwenden

**"Gespräch wurde zu lang und KI vergaß früheren Kontext"**
→ Neues Gespräch beginnen → Schlüsselpunkte in neuem Prompt zusammenfassen

---

## 📞 Hilfe bekommen

1. **Diesen Spickzettel zuerst überprüfen**
2. **Unternehmens-Wissensdatenbank durchsuchen**
3. **IT-Team für technische Probleme fragen**
4. **Mit Kollegen konsultieren, die KI regelmäßig verwenden**
5. **Vollständige Konzeptguides für tieferes Verständnis überprüfen**

---

*Behalten Sie diese Referenz griffbereit - meistern Sie diese Konzepte und Sie werden ein KI-Power-User!*