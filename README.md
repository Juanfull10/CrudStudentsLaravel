Proyecto de ejemplo en Laravel que permite realizar un CRUD de estudiantes.
Permite crear, leer, actualizar y eliminar registros de estudiantes desde una interfaz web.

Tecnologías usadas

PHP 8.x

Laravel 10

MySQL (o la base de datos que uses)

Bootstrap / Tailwind CSS (según tu diseño)

Composer para dependencias

Instalación

Clonar el repositorio:

git clone https://github.com/Juanfull10/CrudStudentsLaravel.git


Entrar al proyecto:

cd CrudStudentsLaravel


Instalar dependencias de PHP:

composer install


Copiar archivo de configuración de entorno:

cp .env.example .env


Configurar la base de datos en .env:

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=prueba1
DB_USERNAME=usuario
DB_PASSWORD=


Ejecutar migraciones:

php artisan migrate


Iniciar servidor local:

php artisan serve

Uso

Acceder al proyecto en el navegador en http://127.0.0.1:8000/students

Crear, editar, eliminar estudiantes desde la interfaz.

Listado de estudiantes con sus datos: nombre, edad, etc.
