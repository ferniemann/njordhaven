# Njordhaven Aufgabe

Setze das Design möglichst originalgetreu um. Eine Vorschau siehst du [hier](https://ferniemann.github.io/njordhaven).

## Assets

### Fonts
Die benutzten Schriftarten sind "Be Vietnam" (sans-serif) und "Abyssinica" (serif). Binde sie ein über folgende Link-Tags im `<head>`-Bereich deiner Seite:

```html
<link rel="preconnect" href="https://fonts.bunny.net" />
<link rel="preconnect" href="https://fonts.bunny.net" />
<link
  href="https://fonts.bunny.net/css?family=abyssinica-sil:400|be-vietnam-pro:200,400,900"
  rel="stylesheet" />
```

### CSS

Starte mit folgenden Grundlagen für das Stylesheet:

```css
*,
*::before,
*::after {
  box-sizing: border-box;
}

html {
  font-family: "Be Vietnam Pro";
}

body {
  height: 100%;
  max-width: 1920px;
  margin: 0 auto;
}
```

### Bilder
<img src="https://raw.githubusercontent.com/ferniemann/njordhaven/fc81aa92dafcc67d1a27160f8962691bc6dd350d/assets/logo.svg" alt="logo" width=40px>
Nutze für das Logo folgende Adresse: 

```
https://raw.githubusercontent.com/ferniemann/njordhaven/fc81aa92dafcc67d1a27160f8962691bc6dd350d/assets/logo.svg
```

<hr>

<img src="https://raw.githubusercontent.com/ferniemann/njordhaven/main/assets/couch.webp" alt="red couch" width=40px>
Nutze für die rote Couch folgende Adresse: 

```
https://raw.githubusercontent.com/ferniemann/njordhaven/main/assets/couch.webp
```

<hr>

<img src="https://raw.githubusercontent.com/ferniemann/njordhaven/main/assets/sessel-white.webp" alt="white chair" width=40px>
Nutze für den weißen Sessel folgende Adresse: 

```
https://raw.githubusercontent.com/ferniemann/njordhaven/main/assets/sessel-white.webp
```

<hr>

<img src="https://raw.githubusercontent.com/ferniemann/njordhaven/main/assets/sessel.webp" alt="white chair" width=40px>
Nutze für den gelben Sessel folgende Adresse: 

```
https://raw.githubusercontent.com/ferniemann/njordhaven/main/assets/sessel.webp
```

<hr>

<img src="https://raw.githubusercontent.com/ferniemann/njordhaven/main/assets/tische.webp" alt="white chair" width=40px>
Nutze für die Tische folgende Adresse: 

```
https://raw.githubusercontent.com/ferniemann/njordhaven/main/assets/tische.webp
```

<hr>

Für die zwei Pfeile nach unten ("Chevron") benutze folgendes SVG:

```svg
<svg xmlns="http://www.w3.org/2000/svg" fill="white" class="icon-chevron" viewBox="0 0 16 16">
  <path fill-rule="evenodd" d="M1.646 6.646a.5.5 0 0 1 .708 0L8 12.293l5.646-5.647a.5.5 0 0 1 .708.708l-6 6a.5.5 0 0 1-.708 0l-6-6a.5.5 0 0 1 0-.708"></path>
  <path fill-rule="evenodd" d="M1.646 2.646a.5.5 0 0 1 .708 0L8 8.293l5.646-5.647a.5.5 0 0 1 .708.708l-6 6a.5.5 0 0 1-.708 0l-6-6a.5.5 0 0 1 0-.708"></path>
</svg>
```
