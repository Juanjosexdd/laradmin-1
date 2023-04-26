# Base Ecommerce

**Base Ecommerce** es mi “personal Base Ecommerce" desarrollado haciendo uso de **Laravel 10.9** y una plantilla **Personalizada**,  para ser usada como base inicial en proyectos tipo Ecommerce.

---

## Requerimientos

- [Composer](https://getcomposer.org/)
- [Requerimientos de Laravel 10](https://laravel.com/docs/10/installation#installation)
- [Node.js y NPM](https://nodejs.org/es/) (Opcional)

---

> Aviso **crear un virtual host** para este proyecto, **es necesario que el directorio public (como se aconseja) del framework funcione como la raíz**, o no funcionara la correcta lectura de las fuentes por parte de font awesome y otras librerias empleadas en este desarrollo.

## Instalación

```
git clone https://github.com/Juanjosexdd/ecommerce.git
cd ecommerce
composer install
```

Modificar el archivo **.env** con los datos correspondientes al proyecto, credenciales a la base de datos y envió de correo electrónico (recuperación de contraseña).

## Crea la base de datos

```
/* Accede a MySQL */
mysql -h localhost -u root -p

/* Crear la base de datos */
mysql> create database ecommerce;

```

Migrar a la base de datos los roles y permisos iniciales, así como el **usuario administrador por defecto**.

```
cd ecommerce
php artisan migrate --seed
```
Los datos del **usuario por defecto** podrán ser vistos (y modificados antes de migrar), en los archivos **seeds** del proyecto en **database/seeds**.

Enjoy!! :)

---

## Paquetes y dependencias

A continuación el listado de tecnologías y plugins utilizados en este desarrollo.

### Back-end
- [Laravel 10.9](https://laravel.com/)
- Entre otros más.

### Front-end

- [Tailwind CSS](https://tailwindcss.com/docs/)
- [LiveWire](https://laravel-livewire.com/)
- [Alpine JS](https://alpinejs.dev/start-here)

---


---

#### Créditos

Backend web developer  
JuanJosexD@gmail.com | [@JuanJose_xDD](https://twitter.com/JuanJose_xDD)
