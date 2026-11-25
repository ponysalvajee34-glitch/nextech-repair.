# NEXTECH REPAIR

Aplicación Android para registrar reparaciones. Incluye clientes, teléfono, modelo, problema, precio en RD$, estado pendiente/listo, notas, búsqueda y exportación de copia JSON.

## Subir a GitHub desde Android
1. Descomprime este ZIP en el teléfono.
2. En el repositorio `nextech-repair`, pulsa **Add file → Upload files**.
3. Sube el contenido de esta carpeta (no la carpeta contenedora): `package.json`, `capacitor.config.json`, `www/`, `.github/` y `README.md`.
4. Pulsa **Commit changes**.

## Generar el APK
Después de subir los archivos, abre la pestaña **Actions** del repositorio.
El flujo **Build NEXTECH REPAIR APK** se ejecutará automáticamente. Cuando termine:
1. Entra al resultado de la ejecución.
2. Baja hasta **Artifacts**.
3. Descarga `NEXTECH-REPAIR-APK`.
4. Extrae el ZIP y encontrarás `app-debug.apk`.

La primera compilación puede tardar varios minutos. El APK debug sirve para instalar y probar; Android puede pedir permiso para instalar desde el navegador/archivos.

## Datos
Los trabajos se guardan localmente en el teléfono donde se registran. Usa “Exportar copia” para guardar un respaldo. No desinstales la app ni borres sus datos sin exportar primero.
