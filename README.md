Ecocargo - Aplicación de Gestión de Envíos
Esta es una aplicación web para la gestión de envíos, diseñada con una arquitectura de múltiples páginas (MPA) y un estilo moderno.

Estructura del Proyecto
El proyecto consta de tres archivos HTML principales que definen el flujo del usuario:

index.html: Página de inicio de sesión. Autentica al usuario y lo redirige al panel de control.

dashboard.html: El panel de control principal. Muestra un historial de envíos, tarifas y permite iniciar la creación de un nuevo envío.

create-shipment.html: La página para crear un nuevo envío, que incluye un formulario de varios pasos y un mapa interactivo.

Guía de Despliegue Paso a Paso (GitHub + Vercel)
Sigue estos pasos para poner tu aplicación en línea de forma gratuita.

Paso 1: Crear un Repositorio en GitHub
Ve a GitHub: Inicia sesión en tu cuenta de GitHub.

Nuevo Repositorio: Haz clic en el botón "New" o ve a github.com/new.

Nombra tu Repositorio: Dale un nombre, por ejemplo, ecocargo-app.

Crea el Repositorio: Deja las demás opciones como están y haz clic en "Create repository".

Paso 2: Subir los Archivos del Proyecto
Descarga los Archivos: Asegúrate de tener los tres archivos (index.html, dashboard.html, create-shipment.html) en una carpeta en tu computadora.

Sube los Archivos a GitHub: En la página de tu nuevo repositorio, verás la opción "uploading an existing file". Haz clic ahí.

Arrastra y Suelta: Arrastra los tres archivos HTML a la ventana del navegador.

Confirma los Cambios: Escribe un mensaje corto (ej. "Versión inicial del proyecto") y haz clic en "Commit changes".

¡Tus archivos ahora están en GitHub!

Paso 3: Desplegar en Vercel
Vercel es una plataforma ideal para desplegar sitios web estáticos como este.

Regístrate en Vercel: Ve a vercel.com y regístrate usando tu cuenta de GitHub. Es la forma más fácil y rápida.

Importa tu Proyecto:

Una vez en tu panel de Vercel, haz clic en "Add New..." y selecciona "Project".

En la siguiente pantalla, Vercel mostrará tus repositorios de GitHub. Busca ecocargo-app (o el nombre que le hayas dado) y haz clic en el botón "Import".

Configura el Proyecto:

Vercel detectará automáticamente que es un proyecto estático sin un framework específico. No necesitas cambiar ninguna configuración.

Simplemente haz clic en el botón "Deploy".

¡Listo!: Vercel tomará unos segundos para construir y desplegar tu sitio. Al finalizar, te dará una URL pública (ej. ecocargo-app.vercel.app) donde podrás ver y usar tu aplicación en vivo.

Actualizaciones Futuras
Cada vez que hagas un cambio en los archivos y lo subas a GitHub (usando el mismo método de "upload files" o configurando Git en tu PC), Vercel detectará automáticamente el cambio y desplegará la nueva versión sin que tengas que hacer nada más.