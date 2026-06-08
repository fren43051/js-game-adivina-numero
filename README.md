# 🎯 Adivina el Número

> Un juego web interactivo donde debes adivinar un número secreto entre **1 y 10**.  
> Proyecto del curso de **JavaScript** de [Alura](https://www.alura.com.br).

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Status](https://img.shields.io/badge/Estado-En%20desarrollo-blue?style=for-the-badge)

---

## 🎮 ¿Cómo se juega?

1. La aplicación elige un **número secreto** al azar (del 1 al 10).
2. Escribe tu intento en el campo de entrada.
3. Pulsa **Intentar** y recibirás una pista:
   - 📉 *"El número secreto es menor"* — prueba un número más bajo.
   - 📈 *"El número secreto es mayor"* — prueba un número más alto.
   - 🎉 *"¡Acertaste el número!"* — ¡ganaste!
4. Cuando aciertes, pulsa **Nuevo juego** para jugar otra ronda.

---

## ✨ Características

- Interfaz moderna con gradientes y tipografías **Chakra Petch** e **Inter**
- Diseño responsive centrado en la pantalla
- Feedback visual en tiempo real según cada intento
- Lógica del juego implementada con **JavaScript puro** (sin frameworks)
- Botón de reinicio para empezar una partida nueva

---

## 🛠️ Tecnologías

| Tecnología   | Uso                          |
| ------------ | ---------------------------- |
| HTML5        | Estructura y semántica       |
| CSS3         | Estilos, layout y diseño     |
| JavaScript   | Lógica del juego e interacción |

---

## 📁 Estructura del proyecto

```
js-game-adivina-numero/
├── index.html      # Página principal del juego
├── style.css       # Estilos y diseño visual
├── app.js          # Lógica del juego (JavaScript)
├── img/
│   ├── ia.png      # Ilustración del personaje
│   ├── code.png    # Fondo decorativo
│   ├── Ruido.png   # Textura del contenedor
│   └── bg.png      # Imagen de fondo
└── README.md
```

---

## 🚀 Cómo ejecutarlo localmente

No necesitas instalar dependencias. Solo un navegador web.

**Opción 1 — Abrir directamente**

Haz doble clic en `index.html` o arrástralo a tu navegador.

**Opción 2 — Con Live Server (recomendado)**

Si usas VS Code o Cursor, instala la extensión **Live Server** y haz clic en *Go Live*.

**Opción 3 — Con un servidor local**

```bash
# Con Python 3
python -m http.server 8000

# Con Node.js (npx)
npx serve .
```

Luego abre `http://localhost:8000` en tu navegador.

---

## 🎨 Vista previa

El juego presenta un panel central con fondo azul oscuro, un campo numérico, botones de acción y una ilustración de personaje a la derecha. El diseño evoca una interfaz futurista de programación.

---

## 📚 Aprendizaje

Este proyecto forma parte del curso de JavaScript de Alura y cubre conceptos como:

- Manipulación del DOM
- Eventos de usuario (`click`, `input`)
- Variables y condicionales
- Números aleatorios con `Math.random()`
- Validación de entradas del usuario

---

## 👤 Autor

**Fabian** — [@fren43051](https://github.com/fren43051)

---

## 📄 Licencia

Proyecto educativo. Libre para uso personal y de aprendizaje.
