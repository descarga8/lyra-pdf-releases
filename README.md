# Lyra PDF

Instaladores y actualizaciones firmadas de Lyra PDF para leer, organizar, reconocer, convertir, editar, rellenar, optimizar y firmar documentos.

## Descargar e instalar

Abre [Releases](https://github.com/descarga8/lyra-pdf-releases/releases) y descarga el instalador Windows x64 de la versión que quieras probar. Ejecuta el archivo `Lyra-PDF_VERSION_x64-setup.exe`; instala la aplicación para tu usuario. El motor Python, Tesseract y los idiomas español/inglés están incluidos. No necesitas instalar Python ni Tesseract. La aplicación requiere WebView2; el instalador comprueba este requisito.

Las versiones **beta / Pre-release** son para pruebas y descarga manual. La versión **Latest** es el canal estable. Si aún no hay una entrega estable publicada, usa una beta y revisa sus notas.

## Actualizaciones

La aplicación pública busca actualizaciones firmadas desde **Configuración → Actualizaciones**. Solo recibe versiones estables superiores a la instalada. Las betas y los borradores no activan ese canal. Antes de instalar, termina los trabajos y guarda/cierra tus documentos; Lyra prepara un respaldo local y reinicia.

Los archivos `.sig`, `latest.json` y `SHA256SUMS.txt` acompañan al instalador. La firma del actualizador verifica el paquete; las sumas permiten comprobar las descargas manuales. La firma de editor Windows (Authenticode) todavía no está configurada.

## Plataformas y edición madre

La entrega pública actual está preparada para **Windows x64**. Linux se valida en una rama y en paquetes privados; no se anuncia todavía soporte completo ni actualización estable Linux. No hay paquete macOS.

La **edición madre** es privada y separada: gestiona versiones y construcciones desde el código del propietario. Este repositorio público no contiene el módulo de distribución, las credenciales ni el código fuente privado.

## Privacidad y licencias

Las herramientas PDF y OCR trabajan en el equipo. La IA es opcional; si configuras un proveedor externo, el texto se envía a ese proveedor al solicitar una respuesta. La IA local necesita un servidor/modelo local instalado por el usuario.

El instalador incluye los avisos y licencias de Lyra y de los componentes distribuidos. El código propio mantiene Apache-2.0; los componentes externos conservan sus respectivas licencias.
