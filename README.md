# mis plantillas

este repositorio tiene la finalidad de almacenar las plantillas que he escrito para compilar programas con xbps-src.  
nota: puede que algunos de los programas listados aquí requieran de dependencias/configuraciones extra.

## ollama

para empaquetar ollama es necesario copiar el archivo shlibs (contenido en este repositorio) al directorio common de su repositorio clonado de void-packages.  
esto es necesario debido a que la herramienta xbps-src no reconoce ciertas librerías de nvidia necesarias para ejecutar ollama.
