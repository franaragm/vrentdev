# VRENT SYMFONY APLICATION LIKE AIRBNB -- Aplicacion Symfony estilo Airbnb

## Video Demostración

[Ver video Demo][14]

## Instrucciones

### Comandos de instalación

* Instalar dependencias:

 `$ composer install`

* Crear base de datos y configurar parametros en parameters.yml
* Crear estructura de tablas

`$ php app/console doctrine:schema:create`

* Importar datos sql de prueba de app/Resources

### Datos de acceso a un usuario

email: fran@aragon.com

password: fran

### Comandos útiles

* Limpiar cache y logs

`$ php app/console cache:clear --env=prod --no-debug`

[14]: https://www.youtube.com

*Fran Aragon*