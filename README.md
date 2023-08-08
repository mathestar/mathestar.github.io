# Mathstar Webseite

**Pull requests gehen an: https://github.com/david-star-git/mathestar.github.io**

## Beschreibung:
Mathstar ist eine Webseite, die sich der Erklärung von Mathematik auf verständliche Weise widmet. Unser Ziel ist es, komplexe mathematische Konzepte einfach und unterhaltsam zu erklären, damit jeder die Freude an der Mathematik entdecken kann.

## Status:
Die Webseite befindet sich derzeit in der Entwicklung. Wir arbeiten an der Gestaltung des Layouts, der Erstellung von Inhalten und der Implementierung interaktiver Funktionen, um ein optimales Lernerlebnis zu bieten.

## Pläne:
- [x] Implementierung von Mehrsprachigkeit, um ein breiteres Publikum anzusprechen
- [x] Fertigstellung einer klaren Grundstruktur der Webseite
- [x] Implementierung von einem System für mathematische Formeln und Ausdrücke
- [x] Integration einer umfassenden Formelsammlung unter Verwendung von MathJax, um mathematische Konzepte in ansprechender Weise darzustellen
- [ ] Übersetzung von Bildern wie `assets/img/posts/es/trig.png` in andere Sprachen
- [ ] Erstellung von Beiträgen zu verschiedenen mathematischen Themen


Wir freuen uns darauf, Mathstar zu einer inspirierenden und nützlichen Ressource für alle Mathematikbegeisterten zu machen! Wenn du Vorschläge, Fragen oder Feedback hast, zögere nicht, uns zu kontaktieren.

## Kontakt:
- Webseite: https://mathestar.github.io/
- Finde uns auf GitHub: https://github.com/mathestar

Wir danken dir für dein Interesse an Mathstar und wünschen dir viel Spaß beim Entdecken der faszinierenden Welt der Mathematik!

# Projekt Struktur
./<br>
├── [_data/]<br>
│   ├── [conf/] <-- Config dateien<br>
│   │   ├── [main.yml]<br>
│   │   ├── [others.yml]<br>
│   │   └── [posts.yml]<br>
│   ├── [content/]<br>
│   │   ├── [projects/] <-- Formelsammlung tab<br>
│   │   │   ├── [de.yml]<br>
│   │   │   ├── [en.yml]<br>
│   │   │   └── [es.yml]<br>
│   ├── [lang/] <-- Übersetzten Texte<br>
│   │   ├── [de.yml]<br>
│   │   ├── [en.yml]<br>
│   │   └── [es.yml]<br>
│   └── [owner/] <-- Information über den Besitzer<br>
│       ├── [de.yml]<br>
│       ├── [en.yml]<br>
│       └── [es.yml]<br>
├── [_posts/] <-- Spanishe Posts<br>
├── [assets/]<br>
│   └── [img/]<br>
│       ├── [about/]<br>
│       ├── [default/]<br>
│       ├── [drawio/]<br>
│       ├── [favicons/]<br>
│       ├── [home/]<br>
│       ├── [posts/] <-- Bilder ohne text<br>
│       │   ├── [de/] <-- Bilder mit Deutschen text für Deutsche posts<br>
│       │   ├── [en/] <-- Bilder mit Englishen text für Englishe posts<br>
│       │   └── [es/] <-- Bilder mit Spanischen text für Spanische posts<br>
│       └── [projects/]<br>
├── [de/]<br>
│   ├── [_posts/] <-- Deutsche Posts<br>
│   ├── [tabs/]<br>
│   │   ├── [about.md]<br>
│   │   ├── [archive.md]<br>
│   │   ├── [links.md]<br>
│   │   └── [projects.md] <-- Platzhalter für `./_data/content/projects/de.yml`<br>
│   ├── [404.md]<br>
│   ├── [index.md]<br>
│   └── [privacy-policy.md]<br>
├── [en/]<br>
│   ├── [_posts/] <-- Englishe Posts<br>
│   ├── [tabs/]<br>
│   │   ├── [about.md]<br>
│   │   ├── [archive.md]<br>
│   │   ├── [links.md]<br>
│   │   └── [projects.md] <-- Platzhalter  für`./_data/content/projects/en.yml`<br>
│   ├── [404.md]<br>
│   ├── [index.md]<br>
│   └── [privacy-policy.md]<br>
├── [tabs/] <-- Spanishe Tabs<br>
│   ├── [about.md]<br>
│   ├── [archive.md]<br>
│   ├── [links.md]<br>
│   └── [projects.md] <-- Platzhalter für `./_data/content/projects/es.yml`<br>
├── [_config.yml] <-- Haupt config Datei<br>
├── [404.md]<br>
├── [index.md]<br>
├── [privacy-policy.md]<br>
└── [README.md]<br>