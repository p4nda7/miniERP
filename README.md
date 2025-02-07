# miniERP - Kundenmanagement und Statistiken

## 🏁 Einführung
Das **Pizza-Kassensystem** ist ein webbasiertes ERP-System, das speziell für Pizzerien entwickelt wurde. Es bietet Funktionen zur Verwaltung von Bestellungen, Kunden, Zahlungen und Statistiken.

---

## 💻 Systemanforderungen
- **Webbrowser**: Chrome, Firefox, Safari, Edge
- **JavaScript**: Aktiviert
- **Local Storage**: Aktiviert
- **Bildschirmauflösung**: Mindestens 1024x768

---

## ⚙️ Installation
1. **Repository klonen**:
   ```sh
   git clone <repository-url>
   ```
2. **In das Verzeichnis wechseln**:
   ```sh
   cd kassensystem
   ```
3. **Server starten** (z. B. mit einem einfachen HTTP-Server):
   ```sh
   python -m http.server 8000
   ```
4. **Im Browser öffnen**:
   [http://localhost:8000](http://localhost:8000)

---

## 🛠 Verwendung
### Anmeldung
- **Admin**: Benutzername `admin`, Passwort `admin123`
- **Mitarbeiter**: Benutzername `mitarbeiter`, Passwort `mitarbeiter123`

### Hauptfunktionen
- **Kundenauswahl**: Kundenname eingeben und Bestellung starten
- **Bestellungen**: Positionen hinzufügen, Preise festlegen, Bestellung abschließen
- **Zahlungen**: Beträge erfassen, Zahlungsstatus aktualisieren
- **Statistiken**: Umsatz, Gewinn, Produktanalysen
- **Produktpflege**: Produkte hinzufügen, bearbeiten, löschen

---

## 🏗 Architektur
- **Frontend**: HTML, CSS, JavaScript
- **Datenhaltung**: Local Storage für persistente Daten
- **Benutzeroberfläche**: Responsive Design mit Dark Mode

---

## 🔥 Funktionen
- **Dark Mode**: Umschaltbar über einen Button
- **Kundensuche**: Erweiterte Such- und Filterfunktionen
- **Statistiken**: Detaillierte Auswertungen und Analysen
- **Produktpflege**: Verwaltung von Produkten und Preisen

---

## 🛠 Technologien
- **HTML5**: Struktur der Anwendung
- **CSS3**: Styling und Layout
- **JavaScript**: Interaktive Funktionen und Logik
- **Local Storage**: Speicherung von Benutzerdaten und Einstellungen

---

## 🔐 Sicherheit
- **Benutzerauthentifizierung**: Rollenbasierte Zugriffsrechte
- **Session Management**: Speicherung von Login-Informationen in der Session
- **Datenvalidierung**: Eingabefelder mit Validierungsregeln

---

## 🏗 Entwicklung
### Lokale Entwicklung
1. **Entwicklungsumgebung einrichten**: Editor/IDE (z. B. VSCode), Browser Developer Tools
2. **Code-Änderungen vornehmen**: HTML, CSS, JavaScript Dateien bearbeiten
3. **Änderungen testen**: Browser aktualisieren und Funktionen testen

### Build & Deployment
- **Build-Tools**: Keine speziellen Build-Tools erforderlich
- **Deployment**: Einfaches Hochladen auf einen Webserver

---

## 🤝 Beitragen
1. **Fork das Repository**
2. **Erstelle einen Feature-Branch**:
   ```sh
   git checkout -b feature/NeuesFeature
   ```
3. **Commit deine Änderungen**:
   ```sh
   git commit -m 'Füge neues Feature hinzu'
   ```
4. **Push zum Branch**:
   ```sh
   git push origin feature/NeuesFeature
   ```
5. **Erstelle einen Pull Request**

---

## 📜 Lizenz
Dieses Projekt steht unter der **MIT-Lizenz**.
