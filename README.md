# Proyecto ETL de Feriados Locales
Este proyecto ETL carga feriados locales desde un archivo de entrada a una base de datos. El proceso incluye validaciones de los datos y la generación de reportes. Utiliza Pentaho Data Integration (Kettle) para transformar y cargar los datos.

## Estructura del Proyecto

- `/kettle/`: Contiene todos los archivos relacionados con Pentaho Data Integration (Kettle), incluyendo transformaciones y trabajos.
  - `/transformations/`: Almacena las transformaciones (.ktr).
  - `/jobs/`: Almacena los trabajos (.kjb).

- `/input/`: Contiene el archivo de entrada que se procesará.

- `/output/`: Almacena los archivos de salida generados por el proceso.

- `/config/`: Almacena archivos de configuración necesarios para el proceso.

- `/sql/`: Contiene scripts SQL, como el DDL para la creación de la tabla en la base de datos.

## Requisitos

- **Pentaho Data Integration**: `pdi-ce-9.4.0.0-343.zip` debe estar instalado y configurado.
- **Java Runtime Environment (JRE)**: Instalado y configurado en el PATH del sistema.
- **Base de Datos**: Compatible con el DDL proporcionado en el directorio `/sql/`.

## Instalación y Configuración

1. **Instalación de Pentaho Data Integration**:
   - Descarga el archivo `pdi-ce-9.4.0.0-343.zip`.
   - Extrae el contenido en una ubicación de tu elección.
   - Configura las variables de entorno si es necesario.

2. **Configuración del Entorno**:
   - Asegúrate de que el JRE esté correctamente instalado y configurado.
   - Verifica que la base de datos esté operativa y accesible desde el entorno donde se ejecutará el proyecto.

## Uso

Para utilizar las transformaciones y ejemplos incluidos en este repositorio, sigue estos pasos:

1. **Clonar el Repositorio**:
    ```bash
    git clone https://github.com/Luciano-Gatti/Desafio-Tecnico-Evaluador-NBCH.git
    ```

2. **Abrir Transformaciones**:
    - Abre Spoon (o la herramienta ETL correspondiente) y carga las transformaciones desde el directorio clonado.

3. **Ejecutar Transformaciones**:
    - Configura las conexiones a bases de datos si es necesario.
    - Ejecuta las transformaciones y observa los resultados.

## Contribuir

Si deseas contribuir a este repositorio agregando tus propios ejercicios en Java o mejorando los existentes, ¡eres bienvenido! Aquí hay algunos pasos para contribuir:

1. Haz un fork del repositorio.
2. Crea una rama para tu función (`git checkout -b feature/AmazingFeature`).
3. Realiza tus cambios y haz commit de ellos (`git commit -m 'Add some AmazingFeature'`).
4. Haz push de la rama (`git push origin feature/AmazingFeature`).
5. Abre un pull request.

## Créditos

Este repositorio es mantenido por [Luciano Emmanuel Gatti Flekenstein]. ¡Gracias a todos los contribuyentes por sus valiosas contribuciones!

## Contacto

Si tienes preguntas, sugerencias o problemas con alguno de los ejercicios, no dudes en ponerte en contacto  abriendo un issue en el repositorio.
