# Radio Neon

Una aplicación web progresiva (PWA) minimalista y responsiva inspirada en los sistemas de cambio de estaciones de videojuegos clásicos, optimizada para un control fluido mediante gestos táctiles.

---

## Características Principales

* **Simulación de Radio en Vivo:** Calcula el tiempo de reproducción en base a la hora actual para simular transmisiones en tiempo real.
* **Control por Gestos:** Soporte nativo para eventos táctiles y de mouse (Deslizar ↔ para cambiar, ↑ para entrar a carpetas, ↓ para salir o apagar).
* **Estaciones Organizadas:** Estructura jerárquica compatible con carpetas y subestaciones.
* **Personalización Visual:** Panel de configuración dinámico para alterar el color del neón, habilitar rotación de carátulas o activar el modo de ritmo multicolor.
* **Optimización PWA:** Configuración lista para instalación en dispositivos móviles mediante `manifest.json`.

---

## Estructura del Proyecto

* `index.html` - Estructura semántica de la interfaz y elementos de audio.
* `style.css` - Estilos visuales basados en variables CSS, efectos de brillo neón y animaciones optimizadas.
* `radio.js` - Lógica de control de estados, cálculo de buffers temporales y procesamiento de gestos.

---

## Tecnologías Utilizadas

* HTML5 (Elementos de audio nativos)
* CSS3 (Variables, animaciones por fotogramas y filtros de brillo)
* JavaScript Vanilla (ES6+, manipulación del DOM y Pointer Events)
* Google Fonts (Fuente tipográfica *UnifrakturMaguntia*)

---

## Créditos

* **Desarrollador:** ING Jose
* **Plataforma de Código:** GitHub
* **Servicios Involucrados:** Dropbox, SoundJay y Google Fonts
