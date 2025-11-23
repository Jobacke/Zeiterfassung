# Zeiterfassung Pro V4.0

## 🎉 Neue Features in Version 4.0

### 1. Smart Sync Banner
- Automatische Erkennung wenn Synchronisation nötig ist
- Erscheint nach 3 Sekunden wenn >5 Einträge vorhanden
- Mini-Tutorial per Klick
- Dauerhaft schließbar

### 2. Export-Funktionen
- **Zeitraum wählen**: Heute / Diese Woche / Dieser Monat / Benutzerdefiniert
- **Format wählen**: XLSX / PDF / CSV
- Professional formatierte Exports mit Zusammenfassung
- Backup-System für Synchronisation zwischen Geräten

### 3. Dashboard
- 4 Statistik-Karten (Woche, Heute, Projekte, Homeoffice%)
- Wochen-Balkendiagramm (Mo-So)
- Projekt-Donut-Chart mit Farben
- Automatische Aktualisierung

## 📁 Dateien in diesem Paket

- **index.html** - Hauptdatei mit kompletter App
- **manifest.json** - PWA Manifest für iPhone Installation
- **service-worker.js** - Service Worker für Offline-Funktionalität
- **README.md** - Diese Anleitung

## 🚀 Installation auf GitHub Pages

### Schritt 1: Zu GitHub hochladen

1. Gehe zu deinem GitHub Repository
2. Klicke auf "Add file" → "Upload files"
3. Lade alle 3 Dateien hoch:
   - index.html
   - manifest.json
   - service-worker.js
4. Commit mit: "Update V4.0 - Dashboard, Export, Smart Sync"

### Schritt 2: GitHub Pages aktivieren

1. Gehe zu "Settings" in deinem Repository
2. Scrolle zu "Pages"
3. Wähle Branch: main
4. Wähle Folder: / (root)
5. Klicke "Save"

### Schritt 3: App öffnen

Nach 2-3 Minuten ist die App verfügbar unter:
`https://DEIN-USERNAME.github.io/DEIN-REPO-NAME/`

### Schritt 4: Auf iPhone installieren

1. Öffne die URL in Safari
2. Tippe auf "Teilen" Button (Quadrat mit Pfeil)
3. Scrolle runter und wähle "Zum Home-Bildschirm"
4. Tippe auf "Hinzufügen"
5. Die App erscheint als Icon auf deinem Home-Bildschirm

## ✅ Funktions-Checkliste

- ✅ Timer mit Start/Stop
- ✅ Manuelle Zeiterfassung
- ✅ Projekt-Verwaltung mit Farben
- ✅ Homeoffice/Office Tracking
- ✅ Zeitkonflikt-Erkennung
- ✅ Dashboard mit Charts
- ✅ Export: XLSX, PDF, CSV
- ✅ Backup/Import für Sync
- ✅ Smart Sync Banner
- ✅ PWA-Unterstützung
- ✅ Offline-Funktionalität
- ✅ Responsive Design

## 🔄 Synchronisation zwischen Geräten

### iPhone → Mac

1. **Auf iPhone:**
   - Gehe zu Export (📤)
   - Klicke "Backup erstellen"
   - Speichere in iCloud Drive

2. **Auf Mac:**
   - Öffne die App im Browser
   - Gehe zu Export (📤)
   - Klicke "Daten importieren"
   - Wähle das Backup aus iCloud Drive

### Mac → iPhone

Gleicher Prozess in umgekehrter Reihenfolge!

## 🎨 Features im Detail

### Dashboard
- **Statistik-Karten**: Zeigen wichtigste KPIs auf einen Blick
- **Wochen-Chart**: Balkendiagramm Mo-So mit Stunden
- **Projekt-Chart**: Donut-Diagramm mit Zeitverteilung

### Export
- **Heute**: Alle Einträge von heute
- **Diese Woche**: Montag bis heute
- **Dieser Monat**: 1. des Monats bis heute
- **Benutzerdefiniert**: Freie Wahl von/bis Datum

### Smart Sync
- Erkennt automatisch wenn Sync nötig
- Tutorial per Klick verfügbar
- Tracking der letzten Synchronisation

## 💾 Datenstruktur

Die App speichert alles in **localStorage**:
- Projekte mit ID, Name, Farbe
- Einträge mit Datum, Zeit, Projekt, Ort
- Einstellungen (letzte Sync, Banner-Status)

## 🔧 Technische Details

- **Frontend**: Vanilla JavaScript (kein Framework)
- **Styling**: Pure CSS mit Gradients
- **Charts**: Chart.js 3.9.1
- **Excel**: SheetJS (xlsx) 0.18.5
- **PDF**: jsPDF 2.5.1
- **PWA**: Service Worker + Manifest

## 📱 Browser-Kompatibilität

- ✅ Safari (iOS & macOS)
- ✅ Chrome (Desktop & Mobile)
- ✅ Firefox (Desktop & Mobile)
- ✅ Edge (Desktop)

## 🆘 Problembehebung

### "Charts werden nicht angezeigt"
→ Prüfe Internet-Verbindung (Chart.js muss geladen werden)

### "Export funktioniert nicht"
→ Stelle sicher, dass Downloads im Browser erlaubt sind

### "PWA lässt sich nicht installieren"
→ Verwende HTTPS (GitHub Pages = automatisch HTTPS)

### "Daten sind weg nach Neuinstallation"
→ Erstelle vorher ein Backup! localStorage wird bei App-Löschung gelöscht

## 📞 Support

Bei Fragen oder Problemen erstelle ein Issue im GitHub Repository.

## 📄 Lizenz

Für persönliche und kommerzielle Nutzung frei verfügbar.

---

**Version**: 4.0  
**Datum**: November 2024  
**Autor**: Johannes
