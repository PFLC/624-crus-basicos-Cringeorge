# Aplicación CRUD de PHP

Este repositorio contiene una aplicación PHP CRUD (Create, Read, Update, Delete) simple. Es una demostración básica de cómo integrar PHP con una base de datos MySQL para gestionar datos de usuarios. La aplicación permite a los usuarios agregar, ver, editar y eliminar información de usuario.

## Tecnologías Utilizadas

PHP: Lenguaje de script del lado del servidor utilizado para el desarrollo web. PHP es una elección popular para la creación de aplicaciones web dinámicas debido a su facilidad de uso y amplia compatibilidad con diferentes sistemas operativos y servidores web.
MySQL: Sistema de gestión de base de datos relacional ampliamente utilizado para almacenar y gestionar datos estructurados. MySQL proporciona una plataforma robusta y escalable para la gestión eficiente de datos.
HTML & CSS: Estas tecnologías se utilizan para estructurar y dar estilo a las páginas web generadas dinámicamente por PHP. HTML se encarga de definir la estructura y el contenido de las páginas, mientras que CSS se utiliza para aplicar estilos y diseños visuales a la interfaz de usuario.
Tailwind CSS: Un framework de CSS utilitario que facilita el desarrollo rápido y la personalización de interfaces de usuario. Tailwind CSS ofrece una amplia gama de clases predefinidas que permiten diseñar interfaces atractivas y responsivas con un mínimo esfuerzo.
![0_yQiGbHGeV0tko6EW](https://github.com/PFLC/624-crus-basicos-Cringeorge/assets/113739759/d3d0a59b-71c0-40f8-a018-164b5fb0da3c)

# Páginas y Funcionalidades

### 1. Página de Inicio (`display.php`)

![Página de Inicio](images/display.png)
Funcionalidad: La página de inicio muestra todos los usuarios almacenados en la base de datos en un formato de tabla fácil de leer. Proporciona una vista general de todos los registros de usuario disponibles.
Características:
Los usuarios pueden examinar rápidamente la lista completa de usuarios.
Se incluyen enlaces de navegación que permiten a los usuarios acceder fácilmente a las funciones de agregar, editar o eliminar información de usuario.

### 2. Agregar Usuario (`user.php`)

![Agregar Usuario](images/add.png)

Funcionalidad: La página de agregar usuario permite a los usuarios ingresar los detalles de un nuevo usuario y agregarlos a la base de datos.
Características:
Un formulario interactivo guía a los usuarios a través del proceso de ingreso de información del usuario, incluidos el nombre, correo electrónico, teléfono móvil y contraseña.
Se implementa una validación de datos en el lado del servidor para garantizar que se ingresen datos válidos antes de enviar la información a la base de datos.

### 3. Editar Usuario (`edit.php`)

![Editar Usuario](images/edit.png)

Funcionalidad: La página de edición de usuario permite a los usuarios modificar los detalles de un usuario existente en la base de datos.
Características:
Un formulario prellenado muestra la información actual del usuario seleccionado, lo que facilita la identificación y modificación de los detalles necesarios.
Los cambios realizados se actualizan inmediatamente en la base de datos, asegurando que la información del usuario esté siempre actualizada.

### 4. Eliminar Usuario (`delete.php`)

Funcionalidad: La página de eliminación de usuario permite a los usuarios eliminar un usuario específico de la base de datos.
Características:
Se proporciona una confirmación antes de eliminar permanentemente un usuario, lo que ayuda a prevenir eliminaciones accidentales.
La eliminación se realiza de manera segura, eliminando únicamente el registro del usuario seleccionado en la base de datos sin afectar a otros datos.

## Cómo Ejecutar

Clona el repositorio en tu máquina local para obtener una copia del código fuente.
Configura un entorno de desarrollo local que incluya un servidor PHP y MySQL, como XAMPP o WAMP.
Utiliza phpMyAdmin u otra herramienta de gestión de bases de datos para crear la base de datos necesaria para la aplicación.
Inicia el servidor local y ejecuta la aplicación desde tu navegador web para empezar a utilizarla.

## Nota de Seguridad

Esta aplicación es una demostración básica y no implementa medidas avanzadas de seguridad. Es recomendable utilizar declaraciones preparadas (prepared statements) u ORM para las interacciones con la base de datos para prevenir ataques de inyección SQL.

---

Siéntete libre de contribuir a este proyecto o sugerir mejoras. Para cualquier consulta o problema, por favor abre un issue en este repositorio.


