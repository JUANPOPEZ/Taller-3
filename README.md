# Taller-3

Traductor ASCII 🎨

Un aplicativo interactivo diseñado para transformar cadenas de texto convencional en composiciones visuales de arte ASCII en tiempo real. Este proyecto fue desarrollado como parte de un taller práctico de programación, enfocándose en el diseño de interfaces de usuario (UI), validación de datos y manipulación de cadenas.

🚀 Características Principales

Conversión en Tiempo Real: Transforma texto a arte ASCII instantáneamente.

Múltiples Estilos Tipográficos:

Estándar (Clásico / #, *, :)

Bloques sólidos (█)

Matriz / Binario (1, 0)

Interfaz Moderna y Responsiva: Diseño oscuro tipo terminal que resalta el resultado generado manteniendo la alineación monoespaciada.

Portabilidad: Incluye versión empaquetada para Android y un script de ejecución directa para entornos de escritorio Windows.

Gestión del Portapapeles: Copia rápida del arte generado respetando los saltos de línea para exportación a .txt, .csv o .svc.

Validación de Entradas: Manejo de errores para campos vacíos que garantiza la estabilidad del sistema.

📁 Estructura del Proyecto

app.py: Motor principal y lógica de servidor en Python que gestiona la traducción de caracteres.

android_build/assets/index.html: Cliente visual (Frontend) que contiene la estructura, estilos e interacción del usuario.

TraductorASCII.apk: Aplicación compilada y lista para ser instalada en dispositivos Android.

run_desktop.bat: Script de automatización para levantar el proyecto directamente en Windows.

build_apk.ps1: Script de PowerShell para la compilación y empaquetado del aplicativo móvil.

DOCUMENTO_TECNICO.md y GUION_VIDEO_5_MINUTOS.md: Soportes documentales del proyecto.

⚙️ Instrucciones de Ejecución

Opción 1: Entorno de Escritorio (Windows)

La forma más rápida de ejecutar el proyecto en un computador Windows es mediante el script por lotes integrado.

Clona o descarga este repositorio.

Haz doble clic sobre el archivo run_desktop.bat.

El script inicializará el entorno y abrirá la interfaz de la aplicación automáticamente.

(Nota: Requiere tener Python instalado en el sistema).

Opción 2: Dispositivo Móvil (Android)

Transfiere el archivo TraductorASCII.apk a tu dispositivo Android.

Habilita la instalación desde "Orígenes desconocidos" en la configuración de seguridad de tu teléfono.

Instala el APK y ejecuta la aplicación "Traductor ASCII".

Opción 3: Ejecución Manual (Desarrolladores)

Si prefieres levantar el servidor manualmente desde la terminal:

# Navega al directorio del proyecto
cd ruta/al/proyecto

# Ejecuta la aplicación principal
python app.py


🛠️ Tecnologías Utilizadas

Backend: Python 3

Frontend: HTML5, CSS3, JavaScript (Vanilla)

Empaquetado Móvil: Herramientas de build nativas de Android

📝 Autores

Desarrollado para el Taller de Programación - Ingeniería de Software.
