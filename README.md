
# Proyecto de Gestión de Estudiantes

Este es un proyecto personal creado durante mi tiempo en la universidad. El propósito de este proyecto es desarrollar una aplicación de escritorio en Java, conectada a una base de datos, que permita a los profesores gestionar la información de sus estudiantes.

## Funcionalidades

### Registro y Autenticación de Usuarios
- Los usuarios pueden crear una cuenta con un nombre de usuario y contraseña.
  ![REGISTRO DE USUARIO]

- Los usuarios pueden recuperar su contraseña en caso de olvido.
  ![RECUPERACION DE CONTRASEÑA]

- Los usuarios pueden iniciar sesión en la aplicación.
  ![INICIO DE SESION]

### Gestión de Estudiantes
- Una vez autenticados, los usuarios acceden al menú principal donde pueden realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) sobre los registros de estudiantes.
- Los usuarios pueden generar un PDF con la lista de estudiantes registrados en su materia.
  ![MENU PRINCIPAL]

## Tecnologías Utilizadas
- **Java**: Lenguaje de programación principal para la lógica de la aplicación.
- **Base de Datos**: Sistema de gestión de bases de datos para almacenar la información de los usuarios y estudiantes.
- **JasperReports**: Biblioteca para generar informes PDF.

## Instrucciones de Instalación

1. Clonar el repositorio:
   ```sh
   git clone https://github.com/tuusuario/tu-repositorio.git
   ```
2. Importar el proyecto en tu IDE favorito (por ejemplo, Eclipse, IntelliJ IDEA).
3. Configurar la conexión a la base de datos en el archivo `database.properties`.
4. Ejecutar el proyecto.
