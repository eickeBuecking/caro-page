# Carolin Genreith - Filmemacherin

Modern portfolio website für Carolin Genreith, built with vanilla HTML & CSS.

## 🎯 Projekt-Überblick

Diese Website ist eine moderne Neugestaltung von [carolin-genreith.de](http://www.carolin-genreith.de/). Alle Inhalte und Bilder der Original-Seite wurden übernommen und in einem zeitgemäßen, responsiven Design präsentiert.

## ✨ Features

- **Modern & Clean**: Minimalistisches Design mit klarer Typografie
- **Fully Responsive**: Optimiert für Desktop, Tablet und Mobile
- **Vanilla Code**: Keine Frameworks - nur HTML, CSS und minimales JavaScript
- **Performance**: Schnelle Ladezeiten ohne WordPress-Overhead
- **Smooth Scrolling**: Sanfte Navigation zwischen Sektionen
- **Mobile Menu**: Intuitive Navigation auf kleinen Bildschirmen

## 📁 Struktur

```
caro-page/
├── index.html          # Haupt-HTML-Datei
├── style.css           # Alle Styles
├── img/                # Bilder
│   ├── start.jpg
│   ├── filme.jpg
│   ├── tvundco.jpg
│   ├── auszeichnungen.jpg
│   └── backup.jpg
├── CLAUDE.md          # Dokumentation für Claude Code
└── README.md          # Diese Datei
```

## 🚀 Verwendung

### Lokal öffnen
Einfach die `index.html` im Browser öffnen.

### Mit lokalem Server
Für bessere Entwicklererfahrung mit Live-Reload:

```bash
# Mit Python 3
python -m http.server 8000

# Mit Node.js
npx serve

# Mit Live Server (VS Code Extension)
# Rechtsklick auf index.html → "Open with Live Server"
```

Dann öffne `http://localhost:8000` im Browser.

## 🎨 Design-Entscheidungen

### Was wurde übernommen?
- ✅ Alle Texte (1:1 von der Original-Seite)
- ✅ Alle Bilder (heruntergeladen)
- ✅ Komplette Struktur (Vita, Filme, TV & Co, Auszeichnungen, Impressum)
- ✅ Alle Informationen und Inhalte

### Was wurde verbessert?
- ✨ Modernes, minimalistisches Design
- ✨ Bessere Typografie und Spacing
- ✨ Voll responsive auf allen Geräten
- ✨ CSS Grid & Flexbox Layout
- ✨ Smooth Scrolling & Animationen
- ✨ Fixed Navigation mit Scroll-Effekt
- ✨ Mobile-optimiertes Menü

## 🛠️ Technologien

- **HTML5**: Semantisches Markup
- **CSS3**: Custom Properties, Grid, Flexbox
- **JavaScript**: Vanilla JS für interaktive Elemente
- **Responsive Design**: Mobile-First Ansatz

## 📱 Responsive Breakpoints

- **Desktop**: 1200px+
- **Tablet**: 768px - 1199px
- **Mobile**: 480px - 767px
- **Small Mobile**: < 480px

## 🎯 Browser-Support

- Chrome/Edge (neueste Versionen)
- Firefox (neueste Versionen)
- Safari (neueste Versionen)
- Mobile Browser (iOS Safari, Chrome Mobile)

## 📝 Inhalte bearbeiten

### Text ändern
Alle Texte befinden sich in der `index.html` in semantischen HTML-Elementen. Einfach die gewünschten Stellen bearbeiten.

### Styles anpassen
Alle Styles sind in `style.css`. Die Design-Tokens (Farben, Schriften, Abstände) sind als CSS Custom Properties definiert:

```css
:root {
    --primary-color: #1ad5a0;
    --text-color: #333;
    --spacing-md: 3rem;
    /* etc. */
}
```

### Bilder austauschen
Neue Bilder im `img/` Ordner speichern und die Referenzen in `index.html` aktualisieren.

## 📄 Lizenz

Alle Inhalte © 2021 Carolin Genreith

## 👤 Kontakt

**Carolin Genreith**
c/o Hush Hush GbR
Lerchenstraße 89c
22767 Hamburg

E-Mail: info@carolin-genreith.de
