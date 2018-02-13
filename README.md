# recetario
Un proyecto django donde implementamos un compendio de recetas de cocina

## Descripcion General

La idea es crear un simple sistema basado en django y usando django-admin como interfaz grafica para poder manejar un sistema de recetas de cocina. 

## Como funciona?

La idea es que los usuarios puedan entrar al sitio web a traves del administrador de python y tengan acceso a una aplicacion django donde pueden administrar sus recetas. Las recetas van a tener un nombre, una descripcion, una seccion de ingredientes y una seccion de pasos para realizar la misma. 

De la misma forma que hay una seccion para poder ver y agregar recetas, tambien va a haber una seccion para ver y agregar ingredientes que luego puedo seleccionar cuando armo una receta. Cada ingrediente va a tener un nombre, unidad de medida (Kg, L, Unidades) y el precio de la cantidad que definimos por unidad (ejemplo, si la unidad es Kg, ponemos el precio por Kg). 

Cuando ingreso los ingredientes de una receta, se deben poder seleccionar de una lista de ingredientes disponibles que ya fueron ingresados por el usuario en la seccion "ingredientes". Esto se hace de manera sencilla con django-admin (trae soluciones para implementar esto con campos ManyToMany). 

## Descripcion del trabajo

Ver la seccion  de [Issues](https://github.com/srodriki/recetario/issues).


