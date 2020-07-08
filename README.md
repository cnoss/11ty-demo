# FD Static Page Genrator Demo based on eleventy-base-blog

Der Startercode basiert auf der [11ty Demo](git://github.com/11ty/eleventy-base-blog.git) von [Zach Leatherman](https://zachleat.com/"). Ergänzt wurden die bekannte File Struktur aus dem Modul Frontend Development, inkl. (hacky) BuildChain. Alles mit sehr heißer Nadel gestrickt :)

## Struktur

```
/_11ty           Eleventy Programmcode
/dist            die ausgespielte Site
/helper          Hilfsscripte für die BuildChain
/src
  /_includes     hier liegen die Templates
  /11ty-data     Metadaten für die Site
  /assets        Fonts und ähnlliches
  /content       Democontent von Zach
  /scripts       etwaige Javascripte für den Client
  /styles        SCSS Files

```

## Getting Started

### Abhängikeiten installieren

```
npm install
```

### Entwicklermodus

```
npm run watch
```

### Distribution

```
npm run build
```

