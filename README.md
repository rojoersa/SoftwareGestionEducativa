#Descripcion 

Este proyecto es una aplicación web para gestionar estudiantes, docentes, asignaturas y matrículas. 
Está desarrollado en Laravel 12 y utiliza una arquitectura basada en controladores y modelos.

#Tecnologias utilizadas: 
- PHP 8.x
- Laravel 12
- Sqlite 
- Inertia.js + React
- TailwindCSS 

#Para configurar el proyecto se requiere lo siguiente lo siguiente: 

# Requisitos
- PHP >= 8.x
- Composer
- Node.js y npm
- MySQL
- XAMPP 

# Pasos

1. Clonar el repositorio:

  - git clone https://github.com/tuusuario/proyecto.git
  - cd proyecto

2. Se realiza la instalacion de las dependencias: 

- composer install
- npm install

3. Ejecutar comando para generar archivo para las variables de entorno 

- cp .env.example .env
- php artisan key:generate

4. Configurar la base de datos en .env y luego ejecutar:

- php artisan migrate --seed

5. Iniciar servidor de Laravel 12 con el comando: 

- php artisan serve

6. Verificar o configurar archivo cors para conectar con el frontend en la ruta: 

- config/cors 
- apuntando a: http://localhost:3000


7. Una vez iniciado el servidor, puedes acceder desde:

- http://localhost:3000/usuarios/crear
- http://localhost:3000/usuarios/estudiante
- http://localhost:3000/usuarios/docente
- http://localhost:3000/asignaturas
- http://localhost:3000/matriculas


Autor: 
Robin Ramirez 
Estudiante de Ingeniería de Sistemas
Proyecto de Programación Avanzada II - 2025



