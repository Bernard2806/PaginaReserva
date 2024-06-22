# Página de Reserva de Audio Visuales / Audio Visual Reservation Page

## Español

### Descripción

Este repositorio contiene el código de una página web para la reserva del salón de audiovisuales, comedor o salón de actos en la Escuela Técnica Industrial Nº1 "Mariano Moreno", ubicada en Chivilcoy. El sistema permite:

- **Inicio de sesión con cuentas normales y de administrador.**
  - **Cuentas normales**: Los usuarios pueden realizar reservas.
  - **Cuentas de administrador**: Los administradores pueden modificar reservas y gestionar los datos de otros usuarios.
- **Reservar espacios para proyecciones:** Los salones se pueden reservar para ver contenido en un proyector o televisor (en el caso del comedor y audiovisuales).
- **Solicitar el proyector:** Los usuarios pueden pedir el proyector y especificar cualquier salón de la escuela para su uso.

### Configuración

Para que el proyecto funcione correctamente, se debe crear un archivo llamado `config.php` en la raíz del proyecto con el siguiente código:

```php
<?php
return [
    'db' => [
        'usuario' => 'tu_usuario',
        'clave' => 'tu_clave',
        'servidor' => 'tu_servidor',
        'basededatos' => 'tu_basededatos',
    ],
];
?>
```

### Instrucciones de uso

1. Clona el repositorio a tu máquina local.
2. Crea el archivo `config.php` en la raíz del proyecto con las credenciales de tu base de datos.
3. Sube el proyecto a tu servidor web y asegúrate de que los permisos sean correctos.
4. Accede a la página web y utiliza las funcionalidades según el tipo de cuenta (normal o administrador).

---

## English

### Description

This repository contains the code for a web page designed to reserve the audiovisual room, dining hall, or auditorium at Escuela Técnica Industrial Nº1 "Mariano Moreno" located in Chivilcoy. The system includes:

- **Login functionality with normal and admin accounts.**
  - **Normal accounts**: Users can make reservations.
  - **Admin accounts**: Administrators can modify reservations and manage other users' data.
- **Reserve spaces for viewing content:** Rooms can be reserved to watch content using a projector or TV (in the case of the dining hall and audiovisual room).
- **Request the projector:** Users can request the projector and specify any room in the school for its use.

### Configuration

To ensure the project functions correctly, create a file named `config.php` at the root of the project with the following code:

```php
<?php
return [
    'db' => [
        'usuario' => 'your_user',
        'clave' => 'your_password',
        'servidor' => 'your_server',
        'basededatos' => 'your_database',
    ],
];
?>
```

### Usage Instructions

1. Clone the repository to your local machine.
2. Create the `config.php` file at the root of the project with your database credentials.
3. Upload the project to your web server and ensure the permissions are correct.
4. Access the web page and use the functionalities according to the account type (normal or admin).