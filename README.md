
# RailMarket

Una tienda online de compra venta de productos.
Escrita en Ruby con el framework RubyonRails.


## APRENDE RUBY

Para empezar el proyecto de ruby on rails con base de datos en postgres,
seguiremos los seguientes comandos.


## INSTALACION

Crea un proyecto con rails

```bash
  rails new myProject --database=postgresql
  cd myProject
```
Ahora para poder encender el servidor de rails usaremos esto:
```bash
  rails s
```
Para crear un nuevo modelo de tabla en la base de datos usaremos esto:
```bash
  rails g model Product title:string description:text price:integer
```
Para migrar lo que hemos generado anteriormente usaremos el siguiente comando:
```bash
  rails db:migrate
```
Para poder insertar nuevos datos en nuestra tabla deberemos usar el comando para ejecutar la terminal de ruby:
```bash
  rails console
```