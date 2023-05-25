# Inicialización de la Base de Datos

## Título
Base de Datos de la Aplicación "Recop"

## Descripción de la Entidad y los Requisitos
La base de datos "Recop" es utilizada por la aplicación "Recop" para gestionar información relacionada con empresas, socios, documentos, sucursales, empleados, entre otros. La base de datos está diseñada para almacenar y organizar datos relevantes para el funcionamiento de la aplicación.

## Diagrama Propuesto de la Base de Datos
Aquí se presenta el diagrama de la base de datos propuesta:

[Insertar imagen del diagrama de la base de datos aquí]

## Requisitos Técnicos
Para levantar localmente la base de datos y utilizarla en el entorno de desarrollo, se requieren los siguientes componentes:

- Sistema operativo compatible (por ejemplo, Windows, macOS o Linux)
- Docker instalado y configurado en el sistema
- Conexión a Internet para descargar las imágenes de Docker necesarias

## Cómo Levantar Localmente la Base de Datos

1. Clonar el repositorio de GitHub: 
git clone https://github.com/SamuelEscobar761/adb.git

2. Acceder a la carpeta del proyecto:
cd adb

3. Ejecutar el comando de Docker Compose para levantar la base de datos:
docker-compose up -d

4. Esperar a que Docker descargue las imágenes y configure los contenedores.

5. Una vez que los contenedores estén en funcionamiento, la base de datos estará lista para su uso localmente.

6. Puedes conectarte a la base de datos utilizando las credenciales y los parámetros de conexión apropiados en tu aplicación o mediante una herramienta de administración de bases de datos (por ejemplo, MySQL Workbench).

Recuerda que la base de datos ya ha sido creada a partir del script proporcionado, por lo que contendrá datos de ejemplo para realizar pruebas.

¡Ahora puedes comenzar a utilizar la base de datos "Recop" en tu entorno local!

**Nota:** Asegúrate de tener instalado Docker y Docker Compose en tu sistema antes de ejecutar los comandos mencionados anteriormente. Si no los tienes instalados, consulta la documentación oficial de Docker para obtener instrucciones sobre cómo instalarlos en tu sistema operativo específico.
