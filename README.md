# Google Drive Folder Info

## Descripción
Google Drive Folder Info es un script de Google Apps Script que analiza una carpeta de Google Drive para proporcionar información detallada sobre su contenido:

- Tamaño total de la carpeta (incluyendo subcarpetas).
- Cantidad total de archivos.
- Clasificación de archivos por tipo: Imágenes, Videos y PDFs.

## Características
- Procesamiento recursivo de subcarpetas.
- Clasificación de archivos basada en el tipo MIME.
- Fácil de ejecutar y configurar en Google Apps Script.

## Requisitos
- Una cuenta de Google con acceso a Google Apps Script.
- Permisos de acceso a la carpeta de Google Drive que deseas analizar.

## Instalación
1. Abre Google Drive y ve a `Extensiones > Apps Script`.
2. Crea un nuevo proyecto y copia el código proporcionado en este repositorio.
3. Guarda el proyecto con un nombre descriptivo.

## Uso
1. Obtén el ID de la carpeta que deseas analizar desde su URL en Google Drive.
2. Reemplaza `folderId` en la función principal `getFolderInfo(folderId)` con el ID de la carpeta.
3. Ejecuta la función desde el editor de Apps Script.
4. Consulta los resultados en el registro (`Ver > Registro`).

## Ejemplo de Resultados
```plaintext
El tamaño total de la carpeta es: 1.2 GB
Total de archivos: 150
Cantidad de imágenes: 80
Cantidad de videos: 50
Cantidad de PDFs: 20
```

## Personalización
Puedes modificar el script para:
* Incluir otros tipos de archivos.
* Generar un informe más detallado.
* Exportar los resultados a un archivo en Google Drive.

## Límites
* Apps Script tiene un límite de ejecución de 6 minutos por sesión. Si la carpeta es muy grande, considera dividir el procesamiento.

## Contribuciones
Las contribuciones son bienvenidas. Si tienes sugerencias o mejoras, abre un issue o envía un pull request.

## Licencia
Este proyecto está licenciado bajo la Licencia MIT.
