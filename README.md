# Medrano-Themes

Es un tema heredado de Luma que contiene toda la estructura del tema Luma, para la instalación del tema es necesario crear en el directorio raiz de Magento la siguiente carpeta:
# /var/www/html/magento/app/design/frontend/medrano/luma_child
posteriormente copiamos el repositorio en esta carpeta y ejecutamos los siguientes comandos:

Para instalar el tema:

1.- php bin/magento setup:upgrade
2.- php bin/magento setup:static-content:deploy -f
3.- php bin/magento cache:clean
4.- php bin/magento cache:flush

Una vez ejecutado el comando procedemos a activar el tema Medrano, para ello vamos al Admin

Para aplicar el Tema:

1.- En Admin, vamos a CONTENT > Design > Configuration. En la página Design Configuration contiene un grid con los ámbitos de configuración disponibles.
2.- En el tercer registro donde se tiene el Default Store View damos click en Edit.
3.- En la pestaña Default Theme, en el menú desplegable Applied Theme, seleccione su tema recién creado.
4.- Damos click en Save Configuration.
5.- Si el cache esta habilitado limpiamos el cache.
Para ver los cambios aplicados, vuelva a cargar la página de inicio.

Si se le realiza cambios al tema para que sean aplicadas debe ejecutar los comandos de instalación del Tema a partir del 2.
