<h1>Sistema de ventas y de stock automotriz</h1>

Una fábrica automotriz necesita un sistema para el control del stock y de lo 
que vende, como así también de sus clientes, que pueden ser consumidor final, una 
empresa, un concesionario, o una vendedora de autopartes.
Los productos que la misma fabrica y vende son vehículos terminados o 
autopartes. De las autopartes se cuenta con un stock y se conoce el mínimo de 
Laboratorio de Computación II TPI Pág. 7
stock que debe haber en inventario, en cambio para vehículos no se cuenta con 
stock previo.
Cuando un cliente quiere comprar vehículos, o autopartes que no se 
encuentran en stock se genera una orden de pedido, y se le informa al cliente la 
fecha de entrega. Para el caso de autopartes en donde la cantidad que haya en 
inventario cubra la cantidad pedida por el cliente, solo se genera una orden de 
pedido en el caso de que la nueva cantidad de inventario sea menor al stock 
mínimo.
Al momento de realizar la factura se asocia la orden de pedido en caso de 
que haya alguna.
Los clientes que son consumidores finales tienen la posibilidad de entrar en 
un autoplan, lo cual implica que al precio del producto se le aplicará una tasa de 
interés dependiendo de la cantidad de cuotas del plan.
Por otro lado, las vendedoras de autopartes reciben descuentos en los 
productos por compras realizadas al por mayor.
La empresa además necesita conocer el historial de precios de sus 
productos

<h3> Descripcion: </h3>
        Sistema codificado en C# .net framework,
        capaz de mostrar cinco reportes diferentes. 

<h3> Primera Parte: </h3>

* 1er diagrama del modelo relacional de la base de datos.
![Alt text](..\proyecto2\diagrams\firstdiagram.png)
<img src="..\proyecto2\diagrams\firstdiagram.svg">

<h3> 2da. Parte: </h3>

* Enunciados: 
    <ul>
    <li>Totales de facturación y promedio de facturación periódicos (por mes,trimestre, semestre,anuales, etc.)</li>
    <li>Automóviles que nunca se vendieron</li>
    <li>Porcentaje de compras por tipo de cliente</li>
    <li>sCantidad de vehículos entregados, promedio de montos, totales de ventas</li>
    <li>Cantidad de stock producido de autopartes por rango de fechas y/o por períodos</li>
    </ul>

## Goals: ## 
<ul>
<li>composición de varias tablas</li>
<li>utilizar distintos tipos de test (distintas condiciones de búsquedas)</li>
<li>consultas agrupadas</li>
<li>sumarias</li>
<li>subconsultas</li>
<li>vistas</li>
<li>procedimientos almacenados</li>
<li>funciones incorporadas definidas por el usuario</li>
<li>triggers</li>
<li>tablas temporales</li>
<li>manejo de errores</li> 
</ul>

<h3>3ra Parte:</h3> 
Presentación del ejecutable; para ello las 
tablas de la base de datos deberá contener previamente datos cargados para tal 
fin, es decir todas las tablas de resultado deben mostrar filas.

Los test de comparación, correspondencia, pertenencia, rango etc., deben 
incluir el ingreso de datos por parte del usuario del sistema desde la respectiva 
pantalla de la aplicación.

“If you absolutely can't tolerate critics, then don't do anything new or interesting“.
Jeff Bezos