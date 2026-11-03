# La Casa de los Números LEGO 🧱🏠

**Laboratorio Didáctico e Interactivo de Valor Posicional (Base 10) para Educación Primaria.**

🎮 **Jugar en vivo (GitHub Pages)**: [https://elchocazo.github.io/casa-de-los-numeros-lego/](https://elchocazo.github.io/casa-de-los-numeros-lego/)

Una aplicación web educativa interactiva desarrollada con HTML5, Tailwind CSS y Three.js, diseñada para ayudar a los estudiantes a comprender y experimentar el valor posicional de las cifras de forma visual, táctil y manipulativa.

---

## 🌟 Características Principales

- **Representación Visual Base-10 Auténtica**:
  - 🟥 **Unidades (U)**: Ladrillos LEGO en marcos de 10 (`2×5`) para fomentar la subitización inmediata.
  - 🟦 **Decenas (D)**: Barras verticales de 10 unidades.
  - 🟩 **Centenas (C)**: Placas planas de $10 \times 10$ ($100$ unidades).
  - 🟪 **Unidades de Mil (UM)**: Cubos de $1.000$ unidades.
  - 🟨 **Decenas de Mil (DM)**: Megatorres almenadas de $10.000$ unidades.
- **Canje Base-10 en Cascada**: Transformación automática cuando se alcanzan 10 piezas en un orden posicional ($9 + 1 = 10$, $99 + 1 = 100$, $999 + 1 = 1.000$), con animación visual de transporte entre habitaciones.
- **El Punto de Mil**: Separador visual e interactivo que refuerza la lectura en voz alta de la palabra *"mil"*.
- **3 Modos de Aprendizaje**:
  1. 🗺️ **Modo Aventura**: 8 misiones pedagógicas progresivas que desbloquean los 8 distritos de la **Isla Numbrópolis**.
  2. 🧩 **Modo Desafíos**: Acertijos con pistas desordenadas (ej. $4\text{ U} + 2\text{ C}$), dictados orales sin cifras visibles y descomposición aditiva, con sistema de rachas 🔥 y puntos 🏆.
  3. ✏️ **Taller Libre / Pizarra Docente**: Fijación libre de números, sumas y restas rápidas en vivo (`+1`, `+10`, `+100`) y selector de vista (*Bloques + Cifras*, *Solo Bloques* o *Solo Cifras*).
- **Entorno 3D con Three.js**:
  - Minifigura interactiva de **Leo el Constructor 3D** con parpadeo, movimiento gestual y sincronización labial.
  - Cuadrilla de obreros (Lucas y Sofía) que reaccionan a cada ladrillo añadido.
- **Lectura y Ortografía en Español**: Conversión exacta a palabras según la RAE y síntesis de voz (Web Speech API).
- **Diseño Táctil y Responsive**: Compatible con pantallas táctiles, tabletas, ordenadores de escritorio y pizarras digitales interactivas.

---

## 🚀 Cómo Ejecutar

No requiere instalación de dependencias ni servidores complejos:

1. Clona el repositorio o descarga el archivo `index.html`.
2. Abre `index.html` en cualquier navegador web moderno (Google Chrome, Microsoft Edge, Firefox, Safari).
3. ¡Comienza a construir!

---

## 🛠️ Tecnologías

- **HTML5 & CSS3**
- **Tailwind CSS** (vía CDN)
- **Three.js** (WebGL 3D)
- **Web Audio API & Web Speech API**
- **Canvas Confetti**
