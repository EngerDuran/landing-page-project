# Proyecto Final del Curso de HTML y CSS 📘

## Objetivo 🏆

El objetivo de este proyecto es aplicar los conocimientos adquiridos en el curso de HTML y CSS para desarrollar una landing page para una empresa ficticia. Este proyecto tiene un nivel de dificultad intermedio y se espera que utilices HTML semántico, CSS avanzado, y un empaquetador para que los cambios se reflejen en tiempo real.

## Requisitos del Proyecto ✅

### Estructura del Proyecto 🏗️

1. **Landing Page**:
   - La página debe ser una landing page para una empresa ficticia.
   - Debe incluir al menos las siguientes secciones:
     - **Header**: Con el logo de la empresa y un menú de navegación.
     - **Hero Section**: Una sección de bienvenida con un llamado a la acción (Call to Action).
     - **Servicios/Productos**: Una sección donde se describan los servicios o productos ofrecidos.
     - **Testimonios**: Una sección con testimonios de clientes.
     - **Formulario de Registro**: Un formulario para que los usuarios se registren o se suscriban a una newsletter.
     - **Footer**: Información de contacto y enlaces a redes sociales.

### Requisitos Técnicos 🔧

1. **HTML Semántico**:

   - Utilizar etiquetas semánticas de HTML5 (`<header>`, `<nav>`, `<section>`, `<article>`, `<footer>`, etc.).
   - Estructurar el contenido de manera lógica y accesible.

2. **CSS**:

   - Aplicar estilos personalizados utilizando CSS.
   - Utilizar un archivo CSS externo para organizar los estilos.
   - Aplicar propiedades de CSS avanzadas como flexbox o grid.
   - Implementar un diseño responsivo que se adapte a diferentes dispositivos (mobile-first).

3. **Imágenes y Multimedia**:

   - Incluir imágenes relevantes y optimizadas para la web.
   - Utilizar etiquetas de imagen adecuadas (`<img>`) con atributos `alt` descriptivos.

4. **Links y Navegación**:

   - Incluir enlaces de navegación que funcionen correctamente.
   - Asegurarse de que los enlaces tengan un estado de hover visualmente distinguible.

5. **Formulario**:
   - Incluir un formulario de registro funcional.
   - Utilizar etiquetas y atributos de formulario correctamente (`<form>`, `<input>`, `<label>`, etc.).

### Empaquetador y Desarrollo en Tiempo Real 🚀

- Utilizar un empaquetador como **Parcel** o **Webpack** para el desarrollo del proyecto.
- Configurar el empaquetador para que los cambios en el código se reflejen en tiempo real en el navegador.

## Manejo de Git y GitHub 🗂️

1. **Repositorio en GitHub**:

   - Crear un repositorio en GitHub con el nombre `html-css-project-landing-page`.
   - Subir todo el código fuente al repositorio.

2. **Flujo de Trabajo con Git**:

   - Crear una rama (`branch`) por cada nueva funcionalidad o feature.
   - Desarrollar la funcionalidad en su rama correspondiente.
   - Una vez completada la funcionalidad, hacer merge de la rama feature con la rama `main` localmente:

     ```bash
     git checkout main
     git pull origin main
     git checkout <feature-branch>
     git merge main
     git checkout main
     git merge <feature-branch>
     ```

   - Resolver cualquier conflicto que pueda surgir durante el merge.
   - Hacer push de los cambios a la rama `main` en el repositorio remoto:

     ```bash
     git push origin main
     ```

   - Repetir este proceso para cada nueva funcionalidad.

## Pasos para Comenzar 🛠️

### Clonar el Proyecto Base 📂

1. Clona el repositorio del proyecto base en tu máquina local:

   ```bash
   git clone https://github.com/rcaterino/html-css-project-landing-page
   ```

2. Navega a la carpeta del proyecto:

   ```bash
   cd html-css-project-landing-page
   ```

3. Instala las dependencias del proyecto:

   ```bash
   npm install
   ```

4. Inicia el servidor de desarrollo:

   ```bash
   npm start
   ```

   Esto iniciará el servidor de desarrollo de Parcel y abrirá tu proyecto en el navegador, reflejando cualquier cambio que hagas en tiempo real.

### Trabajar en el Proyecto 👩‍💻

1. **Crear una nueva rama para cada funcionalidad**:

   ```bash
   git checkout -b feature/<nombre-de-la-funcionalidad>
   ```

2. **Desarrollar la funcionalidad** en la rama creada.

3. **Fusionar los cambios con la rama `main`**:

   - Asegúrate de que `main` esté actualizado:

     ```bash
     git checkout main
     git pull origin main
     ```

   - Vuelve a tu rama de funcionalidad y fusiona `main`:

     ```bash
     git checkout feature/<nombre-de-la-funcionalidad>
     git merge main
     ```

   - Resuelve cualquier conflicto que pueda surgir.

   - Fusiona tu rama de funcionalidad con `main`:

     ```bash
     git checkout main
     git merge feature/<nombre-de-la-funcionalidad>
     ```

   - Empuja los cambios a `main` en el repositorio remoto:

     ```bash
     git push origin main
     ```

4. **Repetir** el proceso para cada nueva funcionalidad.

## Entrega del Proyecto 📤

1. **Repositorio en GitHub**:

   - Crear un repositorio en GitHub con el nombre `landing-page-empresa`.
   - Subir todo el código fuente al repositorio.

2. **Documentación**:

   - Incluir un archivo `README.md` con una descripción del proyecto, instrucciones de instalación y uso, y capturas de pantalla de la página final.

3. **Presentación**:
   - Preparar una breve presentación (5-10 minutos) donde se muestre el proyecto final, se expliquen las decisiones de diseño y desarrollo, y se demuestre el funcionamiento de la landing page.

## Recursos Adicionales 📚

- [HTML5 Semantics](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5/HTML5_semantics)
- [CSS Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [Parcel Documentation](https://parceljs.org/getting_started.html)
- [Webpack Documentation](https://webpack.js.org/concepts/)
- [Git Branching](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging)
- [GitHub Flow](https://guides.github.com/introduction/flow/)
- [How to Write a Good README](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)
- [Landing Page Examples](https://www.awwwards.com/websites/landing-pages/)

¡Buena suerte y que disfrutes desarrollando tu proyecto final! 🚀
