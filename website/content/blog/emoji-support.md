---
title: "Importancia de un sitio web con hugo"
date: 2021-04-03T22:53:58+05:30
draft: false
github_link: "https://github.com/gurusabarish/hugo-profile"
author: "Roger Rojas"
tags:
  - Emoji support
bg_image: ""
description: ""
toc: 
---


Go Templates son archivos HTML con la adición de variables y funciones. Se puede acceder a las variables y funciones de Go Template dentro de los {{ }}.

Una variable predefinida podría ser una variable que ya existe en el ámbito actual (como el ejemplo de .Title en la sección Variables a continuación) o una variable personalizada (como el ejemplo de $address en esa misma sección).

Las [emojify](https://gohugo.io/functions/emojify/) La función se puede llamar directamente en plantillas o [Inline Shortcodes](https://gohugo.io/templates/shortcode-templates/#inline-shortcodes).

Para habilitar emoji globalmente, configure ```enableEmoji``` a ```true``` en la [configuration](https://gohugo.io/getting-started/configuration/) de tu sitio, y luego puede escribir códigos abreviados de emoji directamente en los archivos de contenido; p.ej

La [Emoji cheat sheet](http://www.emoji-cheat-sheet.com/) es una referencia útil para los códigos abreviados de emoji.

<hr>

**N.B.** Los pasos anteriores habilitan secuencias y caracteres emoji estándar Unicode en Hugo, sin embargo, la representación de estos glifos depende del navegador y la plataforma. Para diseñar el emoji, puede usar una fuente de emoji de terceros o una pila de fuentes; p.ej.

```
.emoji {
  font-family: Apple Color Emoji, Segoe UI Emoji, NotoColorEmoji, Segoe UI Symbol, Android Emoji, EmojiSymbols;
}
```

<br>

[Markdown format for emoji](https://gist.github.com/rxaviers/7360908)
