# 🔧 FL-StVZO - Straßenverkehrs-Zulassungs-Ordnung Editor

**Fahrlehrer-Ausbildung FL-BE_07/25**  
Verkehrsinstitut Schielein Nürnberg

---

## 📚 Über dieses Repository

Dieses Repository enthält die Daten für den **StVZO Editor** - ein professionelles Werkzeug zur systematischen Aufbereitung der Straßenverkehrs-Zulassungs-Ordnung (StVZO) für die Fahrlehrer-Ausbildung.

Der Editor ermöglicht die strukturierte Erfassung von Gesetzestexten, technischen Vorschriften, Praxisbeispielen und deren Synchronisation über GitHub.

---

## 📂 Repository-Struktur

```
FL-StVZO/
├── README.md       (diese Datei - Projektbeschreibung)
└── data.json       (StVZO-Daten, automatisch synchronisiert vom Editor)
```

---

## 🔄 Daten-Synchronisation

Die Datei `data.json` wird **automatisch** vom StVZO Editor synchronisiert:

- ✅ Jedes Speichern im Editor aktualisiert diese Datei
- ✅ Änderungen werden mit Zeitstempel versioniert
- ✅ Team-Kollaboration möglich (mehrere Nutzer, ein Repository)

**⚠️ WICHTIG:** Die `data.json` sollte **nicht manuell bearbeitet** werden!  
Alle Änderungen bitte nur über den StVZO Editor vornehmen.

---

## 🛠️ Verwendung

### 1. Repository-Setup (einmalig)
- Repository erstellt: ✅ `710Deckel/FL-StVZO`
- README.md hochgeladen: ✅

### 2. Editor-Verwendung
- HTML-Datei lokal öffnen (`stvzo-editor.html`)
- GitHub Token eingeben (einmalig, gleicher Token wie andere Tools!)
- Paragraphen hinzufügen und speichern
- Automatische Synchronisation erfolgt

### 3. Token-Anforderungen
Der verwendete Token benötigt folgende Berechtigungen:
- ✅ `repo` (Full control of private repositories)

**Hinweis:** Du kannst denselben Token für alle Fahrlehrer-Tools verwenden!

---

## 📋 Datenstruktur

Die `data.json` enthält alle StVZO-Paragraphen im folgenden Format:

```json
{
  "paragraphen": [
    {
      "id": "timestamp",
      "gesetz": "StVZO",
      "nummer": "§ 29",
      "titel": "Bremsen",
      "gesetzestext": "...",
      "quelle": "https://...",
      "praxisbeispiele": [
        {
          "titel": "Beispiel",
          "klasse": "ALLE",
          "beschreibung": "...",
          "wichtigkeit": "CRITICAL"
        }
      ]
    }
  ]
}
```

---

## 🎯 Features des Editors

- **2-Spalten-Layout:** Gesetzestext | Praxisbeispiele
- **GitHub Auto-Sync:** Automatische Synchronisation
- **Template-System:** Vordefinierte Beispiele für technische Vorschriften
- **Badge-System:** CRITICAL (rot) | HIGH (orange) | BANAL (grün)
- **PDF-Export:** Professionelle Druckausgabe
- **Import/Export:** JSON-Backup-System
- **Keyboard Shortcuts:** Strg+S zum Speichern
- **Grünes Theme:** Speziell für technische Vorschriften

---

## 🔧 Wichtige StVZO-Bereiche

Der Editor deckt alle wichtigen technischen Vorschriften ab:

- **§ 29 - Bremsen:** Bremsanlagen, Prüfung, Mängel
- **§ 30 - Beleuchtung:** Scheinwerfer, Rücklichter, Blinker
- **§ 38 - Reifen:** Profiltiefe, Zustand, Winterreifen
- **§ 41 - Geschwindigkeitsmesser:** Tachometer-Pflicht
- **§ 49 - Auspuff:** Lärm- und Abgasvorschriften
- **§ 57 - HU/AU:** Hauptuntersuchung, Abgasuntersuchung

---

## 🔗 Weitere Fahrlehrer-Tools

Dieses Repository ist Teil einer systematischen Tool-Suite für die Fahrlehrer-Ausbildung:

- [📘 FL-StVO](https://github.com/710Deckel/stvo-teleprompter) - StVO Teleprompter mit Erläuterungen
- [🚛 FL-FPersV-EG-VO](https://github.com/710Deckel/FL-FPersV-EG-VO) - Fahrpersonalverordnung & EU-Verordnung
- [⚖️ FL-StVG](https://github.com/710Deckel/FL-StVG) - Straßenverkehrsgesetz
- [🔧 FL-StVZO](https://github.com/710Deckel/FL-StVZO) - Straßenverkehrs-Zulassungs-Ordnung (dieses Repository)
- [📋 FL-FeV](https://github.com/710Deckel/FL-FeV) - Fahrerlaubnis-Verordnung
- [🚗 FL-FZV](https://github.com/710Deckel/FL-FZV) - Fahrzeug-Zulassungsverordnung

---

## 📝 Lizenz & Verwendung

**Projekt:** Fahrlehrer-Ausbildung FL-BE_07/25  
**Ersteller:** Justin Lee Probis  
**Institut:** Verkehrsinstitut Schielein Nürnberg  
**Zweck:** Ausbildung und Podcast "Fahrlehrer Inside"

Dieses Tool und die Daten sind für **Ausbildungszwecke** erstellt.

---

## 📞 Kontakt & Feedback

Bei Fragen, Problemen oder Verbesserungsvorschlägen:
- GitHub Issues in diesem Repository
- Feedback über das Tool (Thumbs Down Button)

---

**Erstellt mit ❤️ für die Fahrlehrer-Ausbildung**

*Letzte Aktualisierung: Dezember 2024*
