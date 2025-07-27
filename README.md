# ✅ To-do List · Gestión inteligente de tus tareas y notas

**To-do List** es una aplicación web ligera, moderna y segura para ayudarte a gestionar tus tareas, notas y colaboradores de forma simple y eficiente. Todo se almacena en archivos JSON por usuario, sin necesidad de base de datos.

## 📁 Estructura del Proyecto
```
To-do-List/
├── data/
│   └── usuarios/
│       └── \[usuario]/
│           ├── notas.json           # Notas personales
│           ├── tareas.json          # Tareas con fechas y alertas
│           └── colaboradores.json   # Lista de colaboradores y permisos
├── index.php               # Página de inicio y login/registro
├── panel.php               # Panel principal del usuario
├── notas.php               # Editor de notas
├── tareas.php              # Gestión de tareas y alertas
├── colaboradores.php       # Gestión de colaboradores y permisos
├── configuracion.php       # Ajustes del usuario
└── README.md               # Documentación del proyecto
```
## 🚀 ¿Cómo usarlo?

1. Abre la web desde tu navegador favorito.
2. Regístrate o inicia sesión.
3. Comienza a crear tareas, tomar notas y gestionar tus proyectos fácilmente.

## ✨ Funcionalidades principales

- 🗒️ **Notas**: Guarda ideas, apuntes o recordatorios con título y contenido.
- ✅ **Tareas**: Crea tareas con fechas límite y alertas visuales.
- 👥 **Colaboradores**: Agrega usuarios con permisos personalizados para ver o editar tus notas y tareas.
- 📂 **Datos en JSON**: Cada usuario tiene su propio almacenamiento en archivos JSON (sin bases de datos).
- 📱 **Diseño responsive**: Optimizado para escritorio, tablets y móviles.
- 🔒 **Seguridad**: Control de sesiones y validación en cada acción importante.

## ⚙️ Requisitos del sistema

- Servidor web (como Apache o Nginx) con PHP 7.4 o superior.
- Permisos de escritura en la carpeta `data/usuarios/`.
- Navegador moderno con soporte para HTML5, CSS3 y JavaScript.

## 🛠️ Desarrollo

Puedes contribuir al desarrollo del proyecto:

- Informando de bugs o ideas mediante [issues](https://github.com/To-do-List/issues)
- Enviando Pull Requests con nuevas características o mejoras
- Sugerencias sobre el diseño, UX o nuevas vistas

## 📄 Licencia

Este proyecto está licenciado bajo la licencia **MIT**. Consulta el archivo `LICENSE` para más detalles.

## 📬 Contacto

¿Tienes dudas o necesitas soporte?  
Crea un issue o contáctanos directamente.

> **To-do List** – Organiza tu vida con estilo, simplicidad y control total desde cualquier dispositivo.
