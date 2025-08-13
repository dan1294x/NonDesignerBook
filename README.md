# Astro + Non-Designer’s Design Book Projects

Este proyecto es un sitio web desarrollado con [Astro](https://astro.build/) para documentar y poner en práctica lo aprendido en el libro **The Non-Designer’s Design Book** de Robin Williams.  
Cada página es un pequeño experimento que aplica conceptos de diseño (contraste, repetición, alineación y proximidad) junto con habilidades técnicas adquiridas en Astro.

## 🎯 Objetivo
Crear un repositorio de mini-proyectos que sirvan como:
- Práctica de los principios de diseño gráfico del libro.
- Ejercicios para mejorar en Astro y desarrollo web.
- Portafolio visual y funcional de aprendizaje progresivo.

## 📂 Estructura del Proyecto
- **`/src/layout/BaseLaoyout.astro`** → Layout base para mantener consistencia visual en todas las páginas.
- **`/src/components/ProjectCont.astro`** → Contenedor que muestra el proyecto anterior y el nuevo para comparar evolución.
- **`/src/components/OldProject.astro`** → Versión inicial del diseño (antes de aplicar principios del libro).
- **`/src/components/NewProject.astro`** → Versión mejorada aplicando lo aprendido.
- **`/src/pages/index.astro`** → Página principal con listado de proyectos.
- **`/public/images/`** → Recursos visuales, como imágenes de fondo.

## 🎨 Principios de Diseño Aplicados
En cada proyecto se trabaja uno o más principios del libro:
1. **Contraste**: Uso de tipografía, color y tamaños para jerarquizar información.
2. **Repetición**: Reforzar identidad visual con estilos y elementos recurrentes.
3. **Alineación**: Organización clara y lógica de contenido.
4. **Proximidad**: Agrupación visual coherente para mejorar la comprensión.

## 🚀 Cómo ejecutar el proyecto
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/usuario/astro-non-designers.git
   cd astro-non-designers
   ```
2. Instalar dependencias:
   ```bash
   npm install
   ```
3. Iniciar servidor de desarrollo:
   ```bash
   npm run dev
   ```
4. Abrir en el navegador:
   ```
   http://localhost:4321
   ```

## 📌 Ejemplo de Proyecto Actual
**The Shakespeare Papers**  
Ejercicio de rediseño basado en un folleto impreso, aplicando:
- Jerarquía tipográfica con familias contrastantes (`Kaushan Script` y `K2D`).
- Uso de color para secciones y llamadas a la acción.
- Distribución en grid para equilibrio visual.
- Imagen de fondo con opacidad controlada usando `::before`.

## 📜 Licencia
Este proyecto es de uso personal y educativo. Libre para referencia y aprendizaje.
