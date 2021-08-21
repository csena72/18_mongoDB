# Desafío: SQLite3

### Consigna:  En base al enunciado para trabajar con un motor SQL, realizar las adaptaciones para trabajar sobre un servidor de base de datos MongoDB. Utilizar el cliente CLI Mongo shell.

1. Crear una base de datos llamada 'prueba'
2. Crear una tabla dentro de esa base con el nombre 'items' que contenga los siguientes campos:
    - 'nombre' del tipo varchar no nulo
    - 'categoria' del tipo varchar no nulo
    - 'stock' del tipo entero sin signo
    - 'id' clave primaria autoincremental no nula
3. Insertar estos 3 items en esa tabla
    - Fideos categoría:Harina stock:20 
    - Leche categoría:Lácteos stock:30
    - Crema categoría:Lácteos stock:15
4. Listar los items agregados

### >> Aspectos a incluir en el entregable:
Mostrar al finalizar las bases de datos presentes en el motor de base de datos, las colecciones de la base 'prueba' y los documentos dentro de ella.
Utilizar luego ROBO 3T para verificar la información presente en la base

## Notas
El campo id lo crea automáticamente el motor de base de datos MongoDB y se llama _id almacenando un ObjectID.
