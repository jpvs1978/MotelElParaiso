# MotelElParaiso
Odoo 9 para el Motel El Paraiso - Administración de alquiler de habitaciones y venta de productos mediante el POS 

-

1.- Instalar Odoo 9 con el Script de Yenthe e instalar todos los módulos base.
Configurar Postgress, Workers, procesadores, memoria, etc.
http://pgtune.leopard.in.ua/
PC estandar con 8 GB de ram
en /etc/odoo.conf:

[options]
limit_memory_hard = 1677721600
limit_memory_soft = 629145600
limit_request = 8192
limit_time_cpu = 600
limit_time_real = 1200
max_cron_threads = 1
workers = 8


2.- Actualizar el código nativo del módulo "pos_restaurant"

3.- Instalar el módulo "custom_pos_restaurant" Modificado por Bruno
Configurar las Mesas del PTV con sus productos por defecto.

4.- Instalar el módulo "pos_change_table" Modificado por Bruno

5.- Instalar el módulo pos_product_availab de Yelizariev 

6.- Instalar el módulo "mass_editing" para editar varios productos a la vez

7.- Tener disponible el repositorio web-9.0 de OCA (dependencias de "Brand Kit"
Agregar al path de odoo /odoo/custom/addons/web-9.0

8.- Tener disponible el repositorio "misc-addons-9.0" de it projects llc para instalar "brand kit"
