# Lyra PDF

Suite de escritorio para leer, organizar, reconocer, convertir, optimizar y firmar documentos. El procesamiento se realiza en tu equipo.

## Descargar e instalar

Las versiones aprobadas se publican en [Releases](https://github.com/descarga8/lyra-pdf-releases/releases). Este repositorio distribuye instaladores, firmas de actualización y notas de cambios. La primera entrega está en preparación y no debe considerarse estable hasta completar sus pruebas de instalación y actualización.

En Windows, descarga el instalador `Lyra PDF_VERSION_x64-setup.exe` de la versión estable más reciente. El paquete incluye el motor y OCR. No necesitas instalar Python. Si ya utilizas una carpeta portable anterior, guarda tus trabajos, sal de Lyra desde la bandeja e instala esta versión una vez.

## Actualizaciones

Desde la versión 0.2.0, abre **Configuración → Actualizaciones** para buscar y descargar nuevas versiones. Puedes activar la búsqueda diaria. Lyra verifica la firma de la descarga y permite reiniciar cuando hayas terminado los trabajos y cerrado los documentos. Antes de instalar crea un respaldo local; las versiones beta no se distribuyen por el canal estable.

Los archivos `SHA256SUMS.txt` permiten comprobar descargas manuales. Las firmas `.sig` se utilizan por el actualizador. Nunca se solicita una contraseña de GitHub desde Lyra.

## Linux

El empaquetado AppImage y DEB está preparado para validación futura. El soporte Linux aún no se anuncia como disponible. La primera base de OCR requiere Tesseract y los idiomas español/inglés instalados en el sistema.

## Problemas

Describe el problema en [Issues](https://github.com/descarga8/lyra-pdf-releases/issues). No adjuntes certificados, contraseñas ni documentos con información privada.
