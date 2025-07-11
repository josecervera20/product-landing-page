# 🐾 Cat Haven: Landing Page de Producto

---

## 📝 Descripción del Proyecto

Este proyecto es una **Landing Page de Producto** para "Cat Haven", un **refugio felino ficticio** donde los amantes de los gatos pueden explorar y considerar la adopción de adorables felinos. Desarrollada como un requisito clave para la certificación en **Responsive Web Design de freeCodeCamp**, esta página no solo presenta información de manera atractiva, sino que también demuestra la implementación de técnicas de diseño web modernas como **Flexbox, CSS Grid y Media Queries** para asegurar una experiencia de usuario **fluida y responsiva** en cualquier dispositivo.

---

## ✨ Características Principales

- **Navegación Fija y Fluida**: Una barra de navegación superior (`#header`) que permanece **visible en todo momento** (sticky) y permite a los usuarios saltar a secciones específicas de la **Landing Page** con un solo clic.
- **Galería Responsiva de Gatos**: Presenta una colección de adorables gatos en tarjetas (`.cat-card`) organizadas con **CSS Grid**, adaptándose dinámicamente a la pantalla para mostrar más o menos columnas según el espacio disponible.
- **Video Incrustado**: Incluye un video relevante sobre la importancia de la adopción, mejorando la experiencia del usuario.
- **Formulario de Suscripción Interactivo**: Un formulario de contacto (`#form`) con validación de email (`type="email"`, `required`) y un botón de envío, diseñado con **Flexbox** para una disposición ordenada.
- **Diseño Adaptable (Responsive)**: Utiliza **media queries** estratégicas para asegurar que la **Landing Page** se vea y funcione perfectamente en dispositivos móviles, tabletas y escritorios.
- **Estilo Moderno y Coherente**: Definición de variables CSS (`:root`) para colores, sombras, y transiciones, lo que permite un diseño visual armonioso y fácil de mantener.
- **Accesibilidad y Usabilidad**: Enlaces de navegación claros, marcadores de posición en el formulario y un diseño intuitivo que mejora la experiencia del usuario.

---

## 💻 Tecnologías Utilizadas

Este proyecto fue desarrollado utilizando las tecnologías fundamentales de la web, enfocándose en la creación de una interfaz de usuario atractiva y funcional para una **Landing Page**:

- **HTML5**: Para estructurar el contenido de la **Landing Page**, incluyendo el encabezado, la navegación, la galería, la sección de video, el formulario y el pie de página.
- **CSS3**: Para aplicar los estilos visuales, implementar el diseño responsivo (utilizando **Flexbox, CSS Grid y Media Queries**), y definir variables para un desarrollo de estilos eficiente.

---

## 📦 Instalación y Ejecución Local

Para ver y explorar esta **Landing Page de Producto** en tu entorno, sigue estos sencillos pasos:

1.  **Clona el repositorio:** Abre tu terminal o línea de comandos y ejecuta el siguiente comando:
    ```bash
    git clone https://github.com/josecervera20/product-landing-page.git
    ```
2.  **Navega al directorio del proyecto:**
    ```bash
    cd product-landing-page
    ```
3.  **Abre la página en tu navegador:** Simplemente abre el archivo `index.html` directamente desde tu explorador de archivos. No se requiere un servidor web local. Opcionalmente, puedes usar comandos de terminal:
    ```bash
    open index.html   # Para usuarios de macOS
    start index.html  # Para usuarios de Windows
    xdg-open index.html # Para usuarios de Linux
    ```

---

## 🚀 Cómo Navegar y Usar la Página

Una vez que la **Landing Page** esté abierta en tu navegador:

1.  **Explora las Secciones**: Utiliza la barra de navegación superior para saltar a las secciones clave:
    - **"Cats"**: Para ver la galería de gatos disponibles.
    - **"Why Adopt"**: Para ver el video explicativo.
    - **"Subscribe"**: Para suscribirte al boletín.
2.  **Interactúa con el Formulario**: Ingresa tu dirección de correo electrónico en el campo de suscripción y haz clic en "Subscribe" para simular el envío.
3.  **Observa la Adaptabilidad**: Cambia el tamaño de la ventana de tu navegador o visualiza la **Landing Page** en diferentes dispositivos para ver cómo el diseño se adapta de forma fluida.

---

## 📂 Estructura del Proyecto

El proyecto está organizado de manera clara y concisa:

```
product-landing-page/
├── index.html       # El archivo principal que contiene la estructura de la Landing Page.
├── styles.css       # La hoja de estilos que define la apariencia y la responsividad de la página.
└── README.md        # Este documento de información del proyecto.
```

---

## 🤝 Contribuciones

¡Las contribuciones son siempre bienvenidas\! Si tienes ideas para mejorar esta **Landing Page**, encuentras algún error o quieres añadir nuevas funcionalidades que se alineen con los requisitos de freeCodeCamp, ¡no dudes en participar\!

1.  **Haz un Fork** del repositorio a tu cuenta de GitHub.
2.  **Crea una Rama**: Clona tu fork localmente y crea una nueva rama para tus cambios:
    ```bash
    git checkout -b feature/tu-mejora-o-nombre-de-la-funcionalidad
    ```
    (o `bugfix/descripcion-del-bug` si es una corrección).
3.  **Realiza tus Cambios**: Implementa tus mejoras o correcciones. Asegúrate de probar bien tus cambios para que cumplan con los requisitos de freeCodeCamp.
4.  **Haz Commit**: Guarda tus cambios con un mensaje de commit claro y descriptivo (siguiendo la convención `feat:` para nuevas características o `fix:` para correcciones de errores):
    ```bash
    git commit -m 'feat: Añadir X funcionalidad'
    # o 'fix: Corregir el diseño responsivo en Y sección'
    ```
5.  **Sube tus Cambios**: Empuja tu rama a tu repositorio bifurcado en GitHub:
    ```bash
    git push origin feature/tu-mejora-o-nombre-de-la-funcionalidad
    ```
6.  **Abre un Pull Request (PR)**: Finalmente, ve a GitHub y crea un Pull Request hacia el repositorio original. Describe detalladamente los cambios que realizaste y por qué son beneficiosos.

---

## 📄 Licencia

Este proyecto es de código abierto y se publica bajo la [Licencia MIT](LICENSE). Siéntete libre de usar, modificar y distribuir este código para tus propios proyectos.
