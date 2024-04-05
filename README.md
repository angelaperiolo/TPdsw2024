# TPdsw2024
UTN FRRo - Desarrollo de software

## Grupo
### Integrantes
* 49330 - Dignani, Clara Josefina
* 49702 - Periolo, Ángela Sol
* 48814 - Tomas, Maria Belen
* 49256 - Muller, Dafne

### Repositorios
- front
- back

## Tema
### Descripción
Esta plataforma de comercio electrónico se especializa en la venta de prendas de ropa. Los usuarios pueden explorar y seleccionar productos de un catálogo publicado por el vendedor. Ofrecemos la opción de iniciar sesión para mantener un registro de datos personales y compras realizadas. Nuestro sistema facilita todas las etapas de la transacción, desde agregar productos al carrito hasta completar el pago. Además, mantenemos un registro actualizado del stock disponible y los pedidos realizados para una experiencia de compra sin complicaciones.

## Alcance Funcional 

### Alcance Mínimo

|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Pedido<br>2. CRUD Categoría<br>3. CRUD Producto<br>4. CRUD Cliente|
|CRUD simple|1. CRUD Categoría<br> 2. CRUD Cliente|
|CRUD dependiente|1. CRUD Pedido {depende de} CRUD Producto<br>2. CRUD Producto {depende de} CRUD Categoría|
|Listado<br>+<br>detalle| 1. Listado de productos filtrados por categoría.<br> 2. Listado de usuarios filtrados por nombre y apellido|
|CUU/Epic|CUU01. Cargar producto<br>CUU02. Registro de usuarios<br>CUU03. Búsqueda de productos<br>CUU04. Carrito de compras|
