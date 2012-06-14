Circle Menu
===========

Modificación del menú circular de Zikes http://zikes.github.com/circle-menu/

Funcionalidades agregadas:

- usar LI o DIVs (o cualquier etiqueta) con una class personalizable

en las opciones hay que definir

{
	...
	div: true // por defecto es false, entonces usa LI
}

Si 'div' es true entonces

busca todos los elementos con el class 'item', pero este class se puede cambiar con el parámetro 'item_class'

Los submenús tienen que tener el class 'submenu', también se puede definir con el parámetro 'submenu_class'


