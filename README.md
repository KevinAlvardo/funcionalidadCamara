

Aplicación Móvil con Funcionalidad de Cámara y Compartición de Imágenes
Descripción
Esta es una aplicación móvil desarrollada en Kotlin que permite a los usuarios tomar fotos con la cámara del dispositivo, guardar las imágenes en la galería y compartirlas en otras aplicaciones. La aplicación utiliza CameraX para la captura de fotos y gestiona los permisos de cámara y almacenamiento en tiempo de ejecución.

Características
Captura de imágenes utilizando la cámara del dispositivo.
Vista previa de la imagen capturada.
Guardado de la imagen en la galería del dispositivo.
Compartición de la imagen en aplicaciones de terceros (por ejemplo, WhatsApp, correo electrónico, redes sociales, etc.).
Manejo de permisos en tiempo de ejecución para cámara y almacenamiento.
Interfaz sencilla y funcional con botones para tomar, guardar y compartir la imagen.
Requisitos
Android Studio 4.1 o superior.
Dispositivo con Android 6.0 (API 23) o superior.
Permisos de cámara y almacenamiento deben ser concedidos por el usuario para el correcto funcionamiento de la aplicación.
Instalación y Ejecución
Clonar el repositorio:

Copiar código
git clone https://github.com/usuario/repo-aplicacion-camara.git
Abrir el proyecto en Android Studio:

Abre Android Studio.
Selecciona File > Open y navega hasta la carpeta donde clonaste el repositorio.
Ejecutar la aplicación:

Conecta un dispositivo Android o utiliza un emulador.
Haz clic en el botón Run (o usa el atajo de teclado Shift + F10).
Asegúrate de haber concedido los permisos solicitados al abrir la aplicación por primera vez.
Permisos
Este proyecto requiere los siguientes permisos en tiempo de ejecución:

Cámara: Permite acceder a la cámara del dispositivo para capturar imágenes.
Almacenamiento: Permite guardar las imágenes en la galería del dispositivo.
Los permisos se solicitan cuando se ejecuta la aplicación y deben ser aceptados por el usuario para el correcto funcionamiento.

Uso
Tomar una foto:

Presiona el botón Tomar Foto para capturar una imagen utilizando la cámara del dispositivo.
Ver la imagen capturada:

La imagen capturada se mostrará automáticamente en la pantalla dentro de un ImageView.
Guardar la imagen:

Para guardar la imagen en la galería, utiliza el botón de Guardar Imagen.
Compartir la imagen:

Puedes compartir la imagen en aplicaciones de terceros (WhatsApp, correo, etc.) utilizando el botón de Compartir Imagen.
Estructura del Proyecto
MainActivity.kt: Lógica principal de la aplicación, gestión de la cámara y permisos.
activity_main.xml: Diseño de la interfaz de usuario, contiene botones y vistas para interactuar con la cámara y la imagen.
AndroidManifest.xml: Declaración de permisos y configuración del proyecto.
Tecnologías Utilizadas
Kotlin: Lenguaje de programación utilizado.
CameraX: Librería de Android para interactuar con la cámara.
Intents: Utilizado para compartir imágenes entre aplicaciones.
AndroidX: Librerías compatibles con las nuevas versiones de Android.
Capturas de Pantalla (Opcional)
Puedes agregar aquí capturas de pantalla que muestren el funcionamiento de la aplicación.

Contribuciones
Si deseas contribuir a este proyecto, siéntete libre de hacer un fork, clonar el repositorio y enviar pull requests con tus mejoras o nuevas funcionalidades.

Licencia
Este proyecto está bajo la licencia MIT. Puedes ver más detalles en el archivo LICENSE.
