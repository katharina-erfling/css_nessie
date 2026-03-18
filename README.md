# 🦕 Nessie

Responsiver Frontend-Prototype einer Service-Partner-Seite mit Tabelle, fixierter Navigation, Hero-Section und Scroll-to-top-Funktion. Gebaut mit purem HTML5 und CSS3.

---

## 📁 Projektstruktur

```
/
├── index.html
├── css/
│   └── stylesheet.css
└── images/
    ├── logoipsum-338.svg
    ├── search-alt-2-svgrepo-com.svg
    ├── sea-creature-svgrepo-com.svg
    ├── check-badge-svgrepo-com.svg
    ├── arrow-right-svgrepo-com.svg
    ├── arrow-right-up-358-svgrepo-com.svg
    ├── drop-energy-fuel-svgrepo-com.svg
    └── water-bg.jpeg
```

---

## 🧩 Seitenaufbau

**Navigation** – Fixierte Nav mit Logo, Links und Suchformular. Auf Mobile wird die Navigation durch einen Hamburger-Button ein- und ausgeklappt.

**Header / Hero** – Vollflächige Hero-Section mit Hintergrundbild, Argumentenliste mit SVG-Icons und CTA-Button.

**Main** – Zweispaltiger Textbereich mit typografischen CSS-Details (`::first-letter`, `::first-line`) sowie eine scrollbare Servicepartner-Tabelle mit Hover-Effekten und Status-Badges.

**Aside** – Fixierter Scroll-to-top-Button am rechten Rand mit SVG-Icon.

**Footer** – Dreispaltiger Footer mit Linklisten, Hintergrundbild und gestylten Link-Zuständen (`:link`, `:visited`, `:hover`, `:active`, `:focus`).

---

## 📱 Responsive Breakpoints

| Breakpoint | Zielgerät | Änderungen |
|---|---|---|
| `≤ 1024px` | Tablet | Padding reduziert |
| `≤ 768px` | Mobil | Hamburger-Menü, Textspalten untereinander, Footer einspaltiger, Aside ausgeblendet, `background-attachment: scroll` |
| `≤ 480px` | Kleines Mobil | Schriftgrößen weiter reduziert |

---

## 🛠️ Technologien

- **HTML5** – semantisches Markup
- **CSS3** – Flexbox, Media Queries, Pseudo-Elemente, CSS-Transitions, `::selection`, `:nth-child`
- **Kein Framework**, kein npm

---

## 📸 Bildquellen

Icons und SVGs von [SVG Repo](https://www.svgrepo.com) – frei verwendbar unter Public Domain / CC0.

---

## 📌 Hinweise

Dieser Prototype ist ein reines UI/UX-Demo ohne Backend-Anbindung. Tabelleninhalte und Texte sind Platzhalterdaten (Lorem Ipsum).
