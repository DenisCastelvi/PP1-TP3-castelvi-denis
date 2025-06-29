# PP1-TP3-castelvi-denis
✅ 1. ¿Cómo cambiar el azul del encabezado (bg-primary)?
Bootstrap usa clases como bg-primary, bg-success, bg-danger, etc., con colores predeterminados. Para cambiar el color del encabezado a uno personalizado, tenés dos opciones:

🅰️ OPCIÓN 1: Cambiar con tu propio CSS (recomendado)
Quitá bg-primary de la etiqueta <header>.

En tu archivo estilo.css, agregá un estilo con tu color preferido. Por ejemplo:

css
Copiar
Editar
/* Estilo personalizado para encabezado */
header {
    background-color: #003366; /* azul oscuro personalizado */
    color: white;
}
Ahora el HTML quedaría así:

html
Copiar
Editar
<header class="text-white text-center py-4 shadow-sm mb-4">
    <!-- sin bg-primary -->
    <div class="container">
        <h1 class="display-5 fw-bold">Derecho a la Desconexión</h1>
        <p class="lead">Riesgos Psicosociales y la importancia de establecer límites en el teletrabajo</p>
    </div>
</header>
🔁 Podés cambiar el color #003366 por cualquier otro desde https://htmlcolorcodes.com/es/

✅ 2. README para tu proyecto
A continuación te dejo un archivo README.md con formato profesional. Copialo y guardalo como archivo de texto plano con extensión .md.

markdown
Copiar
Editar
# Riesgos Psicosociales y Derecho a la Desconexión 🧠💼

Este proyecto web presenta información sobre los riesgos psicosociales laborales, enfocándose en el **Derecho a la Desconexión**, especialmente en contextos de **teletrabajo**. Está desarrollado con **HTML5**, **CSS personalizado** y **Bootstrap 5**.

---

## 📁 Estructura del Proyecto

📁 proyecto-desconexion/
│
├── index.html → Página principal
├── CSS/
│ └── estilo.css → Estilos personalizados
└── README.md → Este archivo

yaml
Copiar
Editar

---

## 🚀 Tecnologías Utilizadas

- HTML5
- CSS3
- Bootstrap 5 (vía CDN)
- Diseño responsivo y moderno con clases populares de Bootstrap

---

## 🎯 Funcionalidades

- Encabezado destacado con color personalizado
- Contenido organizado en tarjetas (`.card`) con sombras (`.shadow`)
- Listas organizadas y responsivas
- Pie de página elegante
- Preparado para futuras mejoras: íconos, PDF, modo oscuro, etc.

---

## 🎨 Personalización

Para cambiar el color del encabezado:
1. Eliminar `bg-primary` en el `<header>`.
2. Agregar un color en `estilo.css` usando `background-color`.

Ejemplo:
```css
header {
    background-color: #003366;
    color: white;
}
📦 Cómo usar el proyecto
Clonar o descargar el proyecto.

Abrir el archivo index.html en cualquier navegador moderno.

Editar CSS/estilo.css para aplicar estilos personalizados.

🧑‍💻 Autor
Desarrollado por Denis Alexander Castelvi Garcia
Año: 2025

