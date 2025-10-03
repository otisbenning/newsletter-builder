# Start with a Friend Newsletter Builder

Ein visueller Drag & Drop Newsletter-Editor für Start with a Friend e.V. mit CleverReach Integration.

## 🚀 Features

- **Drag & Drop Editor** - Intuitive Bedienung ohne Code-Kenntnisse
- **Event-Import** - Automatischer Import von Events vom SwaF-Portal
- **CleverReach Integration** - Direkt kompatibles HTML
- **Responsive Design** - Optimiert für Desktop, Tablet und Mobile
- **Template-Verwaltung** - Speichern und Laden von Vorlagen
- **Highlight-Funktion** - Events visuell hervorheben

## 📋 Module

### Pflicht-Module
- **Preheader** - Unsichtbarer Vorschau-Text
- **Header** - Logo + "Im Browser ansehen" Link
- **Footer/Impressum** - Kontaktdaten & Social Media Links

### Inhalts-Module
- **Hero Bild** - Großes Titelbild
- **Begrüßung** - Personalisierte Anrede
- **Bild & Text** - Kombiniertes Modul
- **Nur Text** - Einfacher Textblock
- **Events** - Event-Liste mit Import-Funktion
- **Zwei/Drei Spalten** - Mehrspaltige Layouts mit Buttons
- **Drei Buttons** - Button-Reihe
- **Zitat** - Formatiertes Zitat
- **Call-to-Action** - Hervorgehobener CTA-Bereich
- **Button (zentriert)** - Einzelner zentrierter Button
- **Social Media** - Social Media Icons
- **Ansprechpartner** - Kontaktperson mit Bild
- **Partner News** - Partner-Informationen
- **Trennlinie** - Visuelle Trennung

## 🛠️ Installation

1. Laden Sie die `swaf-newsletter-builder.html` herunter
2. Öffnen Sie die Datei in einem modernen Browser (Chrome, Firefox, Safari)
3. Fertig! Keine Installation notwendig

## 📖 Nutzung

### Newsletter erstellen

1. **Module hinzufügen**: Ziehen Sie Module aus der Sidebar in die Vorschau
2. **Bearbeiten**: Klicken Sie auf "✎ Bearbeiten" um Inhalte anzupassen
3. **Reihenfolge ändern**: Nutzen Sie die ↑↓ Buttons oder Drag & Drop
4. **HTML exportieren**: Klicken Sie auf "📋 HTML kopieren"

### Events importieren

1. Klicken Sie im Events-Modul auf "📥 Events importieren"
2. Ziehen Sie das Bookmarklet in Ihre Lesezeichen-Leiste
3. Öffnen Sie [portal.startwithafriend.de/events](https://portal.startwithafriend.de/events)
4. Klicken Sie auf das Bookmarklet → Events werden kopiert
5. Fügen Sie im Editor die Events ein (Strg+V / Cmd+V)

### In CleverReach einfügen

1. Klicken Sie auf "📋 HTML kopieren"
2. Öffnen Sie CleverReach → Neuer Newsletter
3. Wählen Sie "HTML-Editor"
4. Fügen Sie den Code ein (Strg+V / Cmd+V)
5. Speichern & Versenden

### Templates verwalten

- **Speichern**: Button "Speichern" → Name eingeben
- **Laden**: Button "Laden" → Template auswählen
- **Export**: "Export JSON" → Datei wird heruntergeladen
- **Import**: "Import JSON" → JSON-Datei auswählen

## 🎨 Design-System

### Farben (lt. Style Guide)
- **Primär**: `#009a93` (Türkis) / `#c5003d` (Rot)
- **Sekundär**: `#00989a` (Türkis), `#213293` (Dunkelblau)
- **Schrift**: GT Walsheim (Fallback: Arial)

### Personalisierung
Nutzen Sie CleverReach-Platzhalter:
- `{FIRSTNAME[std:Hi]}` - Vorname (Fallback: "Hi")
- `{EMAIL}` - E-Mail-Adresse
- `[MAILING_ID]`, `[HASH]` - CleverReach-IDs

## 🔧 Browser-Kompatibilität

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+

## 📄 Lizenz

Entwickelt für Start with a Friend e.V.

## 🤝 Support

Bei Fragen oder Problemen:
- Klicken Sie auf "❓ Hilfe" im Editor
- Kontakt: [Ihre Email/GitHub]

## 📝 Changelog

### Version 1.0 (2025-01-03)
- Initial Release
- Drag & Drop Editor
- Event-Import via Bookmarklet
- Template-Verwaltung
- Responsive Design
- CleverReach Integration
