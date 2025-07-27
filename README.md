# To-do List 📝✅

Aplicación web ligera y moderna para gestionar tus notas, tareas y colaboradores, con almacenamiento local en archivos JSON.

## 📂 Estructura del Proyecto

```
To-do-List/
├── data/                   # Carpeta donde se almacenan los datos JSON por usuario
│   └── usuarios/
│       └── [usuario]/
│           ├── notas.json           # Notas personales
│           ├── tareas.json          # Tareas con fechas y alertas
│           └── colaboradores.json   # Usuarios colaboradores y permisos
├── index.php               # Página de inicio y login
├── panel.php               # Panel principal de usuario
├── notas.php               # Gestión de notas
├── tareas.php              # Gestión de tareas
├── colaboradores.php       # Gestión de colaboradores
├── configuracion.php       # Configuración del usuario
└── README.md               # Documentación del proyecto
````

## 🚀 Despliegue

1. **Sube los archivos al servidor web con PHP (7.4+)**.
2. Asegúrate que la carpeta `/data/usuarios/` tenga permisos de escritura para que la app pueda guardar los datos.
3. Abre la URL en el navegador, crea tu usuario y empieza a gestionar tus notas y tareas.

*No requiere base de datos ni instalación local.*

## ✨ Funcionalidades principales

* 🗒️ Notas personales con títulos y contenido.
* ✅ Tareas con fechas límite y alertas programadas.
* 👥 Gestión de colaboradores con permisos para ver y editar.
* 🗃️ Datos almacenados en JSON, fáciles de mantener y respaldar.
* 📱 Interfaz responsive y moderna, adaptada a móviles y escritorio.
* 🔒 Control de acceso mediante sesiones PHP seguras.

## 🔧 Requisitos

* Servidor web con soporte PHP 7.4 o superior.
* Permisos de escritura en la carpeta `data/usuarios/`.
* Navegador actualizado con soporte para JavaScript.


## 🤝 Contribuciones

Si deseas contribuir, puedes:

* Reportar errores o sugerencias mediante issues.
* Enviar pull requests con mejoras o nuevas funcionalidades.

## 📄 Licencia

Licenciado bajo MIT. Consulta el archivo `LICENSE` para detalles.

## 📬 Contacto

Para dudas o soporte, abre un issue en el repositorio o contacta directamente.

**To-do List** — Organiza tu día a día con estilo y sencillez desde cualquier navegador.

```
