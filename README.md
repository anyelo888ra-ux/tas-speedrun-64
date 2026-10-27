# ⏱️ TAS & Speedrun 64 Studio

[![Status Active](https://img.shields.io/badge/Status-Active-brightgreen.svg)](https://tas-speedrun-64.vercel.app)
[![Platform WebAssembly](https://img.shields.io/badge/Platform-WebAssembly%20%7C%20WebGL-blue.svg)](https://tas-speedrun-64.vercel.app)
[![License MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

**TAS & Speedrun 64** es una suite de telemetría en tiempo real, análisis de física e interfaz para Tool-Assisted Speedruns (TAS) de Super Mario 64 que ejecuta directamente desde el navegador.

🚀 **Deploy Oficial:** [tas-speedrun-64.vercel.app](https://tas-speedrun-64.vercel.app)

---

## 🔥 Características Principales

- 🎮 **Reproductor WebGL SM64:** Ejecución nativa WebGL / Emscripten WASM directamente en el cliente.
- 🕹️ **Input Display On-Screen:** Gráfico en vivo del Joystick de N64 y estado de botones (A, B, Z, R, C-Buttons).
- 📊 **Telemetría de Física en Vivo:** Monitor frame-by-frame de Velocidad Horizontal (`hspeed`), Velocidad Vertical (`yspeed`), Coordenadas ($X, Y, Z$) y Ángulo de Yaw.
- 🤖 **Gestor de Scripts TAS:** Búfer para cargar y ejecutar secuencias precisas de input de control.
- ⏱️ **Timer de Splits de Precisión:** Cronómetro RTA (Real Time Attack) e IGT (In-Game Time) integrado con temporizador de sub-milisegundos.
- 💻 **Consola de Telemetría & CMD:** Registro en vivo de eventos del motor y bus de memoria.

---

## ⚡ Inicio Rápido

1. Visita la aplicación en [tas-speedrun-64.vercel.app](https://tas-speedrun-64.vercel.app).
2. Arrastra tu copia de la ROM legal de Super Mario 64 (`Super Mario 64 (USA).z64`).
3. Activa los paneles de telemetría y ejecuta tus secuencias TAS con precisión frame-perfect.

---

## ⚙️ Estructura del Repositorio

```text
tas-speedrun-64/
├── index.html        # Portal principal y cargador de ROMs
├── app.html          # Suite principal de TAS, Telemetría e Input Display
├── favicon.svg       # Icono SVG oficial
├── banner.svg        # OpenGraph Banner para embeds de Discord/Twitter
└── README.md         # Documentación oficial

```

---

## 📄 Licencia

Este proyecto está bajo la Licencia **MIT**. Desarrollado para la comunidad de speedrunning y romhacking de SM64.
---

¡Sube estos archivos a tu nuevo repo `tas-speedrun-64` y vincúlalo a Vercel para que empiece a compilar la suite de telemetría e input display en vivo! 🚀⏱️
