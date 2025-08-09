# app-contactos
SISTEMA DE CONTACTOS EN PHP (PDO + MySQL)

Este es un proyecto básico de gestión de contactos con inicio de sesión, registro de usuarios y CRUD de contactos, desarrollado en PHP, PDO y MySQL.

CARACTERÍSTICAS

Registro de nuevos usuarios con contraseña encriptada usando password_hash.

Inicio de sesión seguro usando password_verify.

Listado de contactos por usuario.

Agregar, editar y eliminar contactos.

Validación para evitar contactos duplicados (por nombre, teléfono o correo).

Protección contra SQL Injection usando consultas preparadas (prepare + execute).

Manejo de sesiones para proteger páginas.

REQUISITOS

PHP versión 7.4 o superior.

MySQL o MariaDB.

Servidor local (XAMPP, WAMP, Laragon, etc.).

Navegador web.

ESTRUCTURA DEL PROYECTO
contactos-app/
│
├── index.php → Página principal con login y registro
├── funciones.php → CRUD de contactos
├── logout.php → Cerrar sesión
└── includes/
└── database.php → Conexión a la base de datos con PDO

BASE DE DATOS

acrivo de scrip para crear base de datos
