<h1 align=center>📝 Proyecto BEM: Página de Noticias Falsas</h1>
<p>Este repositorio contiene la implementación de una interfaz web sencilla utilizando la metodología BEM (Bloque, Elemento, Modificador) para la organización de estilos CSS, como parte de un proyecto académico.</p>

## 🎯 Objetivos
Desarrollar una interfaz web responsive con:
- Estructura HTML semántica
- Organización CSS mediante BEM
- Componentes reutilizables
- Diseño adaptable a dispositivos móviles

## ✅ Requerimientos:
### Estructura de Archivos

```plaintext
proyecto-bem/
├── assets/
│   └── images/       # Todas las imágenes del proyecto
├── css/
│   └── styles.css    # Versión compilada
├── html/
├── index.html        # Página principal
└── README.md         # Este documento
```
### Estructura básica del HTML
```plaintext
<!-- Cabecera -->
<header class="header">
  <div class="header__logo">
    <img src="assets/images/logo.png" alt="Logo">
  </div>
  <nav class="header__menu">
    <ul class="nav">
      <li class="nav__item nav__item--activo">Inicio</li>
      <!-- Más items -->
    </ul>
  </nav>
</header>

<!-- Contenido Principal -->
<main class="main">
  <article class="article">
    <!-- Contenido de noticias -->
  </article>
  
  <section class="contact">
    <form class="form">
      <!-- Formulario -->
    </form>
  </section>
</main>

<!-- Pie de página -->
<footer class="footer">
  <!-- Redes sociales y contacto -->
</footer>
```

### Aplicación de la metodología BEM

|Componente|Ejemplo BEM|
|----------|-----------|
|**Bloque**| .header, .article|
|**Elemento**| .header__logo, .article__title|
|**Modificador**| .nav__item--activo, .form__button--submit|

### 🛠 Implementación Técnica:
1. **HTML:**
   - Estructura semántica
   - Clases BEM consistentes
   - Contenido organizado en secciones
2. **CSS:**
   - Definición de variables
   - Bloques y modificadores
   - Responsividad

### Responsable:
<p align=center>Carolina Hernández Barra</p>
