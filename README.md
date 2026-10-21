# ✨ Frase del día

Una web sencilla que muestra **una frase motivadora distinta cada día**, con la fecha debajo. Sin servidor, sin base de datos: solo HTML, CSS y JavaScript.

🔗 **Ver la web:** https://adrianapereira-ops.github.io/MotivationalQuotes

---

## 💡 Cómo funciona

Hay una lista con **400 frases** en `script.js`. Cada día, el script calcula cuántos días han pasado desde una fecha de inicio y elige la frase que toca. Cuando se acaban las 400, vuelve a empezar.

Así la frase cambia sola, sin tocar nada.

## 🛠️ Tecnologías

- HTML
- CSS
- JavaScript

## 📁 Estructura

```
frase-del-dia/
├── index.html   → la página
├── style.css    → el diseño
└── script.js    → las frases y la lógica del día
```

## 🚀 Cómo probarla en local

1. Descarga o clona el repositorio.
2. Abre `index.html` en el navegador.

También puedes usar la extensión **Live Server** de VS Code para verla mientras editas.

## ✏️ Personalizar

- **Cambiar las frases:** edita la lista `frases` en `script.js`.
- **Cambiar la fecha de inicio:** edita la línea `const inicio = new Date(2026, 9, 21);` (el mes va de 0 a 11).
- **Cambiar colores y fondo:** edita `style.css`.

## 🌐 Publicación

Publicada con **GitHub Pages**.

---

Hecho con cariño 💙 para aprender y para empezar el día con buen pie.
