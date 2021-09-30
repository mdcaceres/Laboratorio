* Trabajo Práctico Integrador

* Objetivos:

Que el alumno sea capaz de:
• Integrar los conocimientos adquiridos en las materias Laboratorio de 
Computación I y II y Programación I y II.
• Aplicar dichos conocimientos a un caso práctico.
• Trabajar en grupo en forma ordenada y eficiente.

* Evaluación y Calificación:

Se evaluará la calidad, complejidad y presentación del trabajo como así 
también la oportunidad de entrega en fecha
Este práctico tiene carácter de obligatorio y deberá aprobarse con un 60% (al 
igual que los parciales) para regularizar la asignatura.
Especificaciones y requerimientos del trabajo a presentar
Realizar un sistema codificado en un lenguaje de programación, que sea 
capaz de mostrar cinco reportes diferentes. Estos reportes pueden ser propuestos 
por el docente del curso o por los integrantes de los diferentes grupos.
Se trabajará en grupos de cinco o 6 integrantes cada uno. No se aceptarán 
alumnos resolviendo el práctico en forma individual.

* Los temas propuestos para el diseño del sistema de base de datos son:
1. Sistema académico de las Tecnicaturas de la UTN FRC
2. La venta de entradas con butacas numeradas en un complejo de cines.
3. Sistema de ventas y control de stock de una automotriz.
4. Sistema de ventas de una farmacéutica
Otros temas propuestos por los alumnos como: sistema de gestión de 
recursos humanos, gestión de la producción, etc. éstos deberán estar bien 
explicados al momento de la presentación de la primera parte.

Los temas podrán ser bien designados por el docente del curso o bien 
elegidos libremente por cada grupo (esta decisión dependerá de cada docente).
La entrega se efectuará en tres partes:


* Primera Parte: 

Entrega del diagrama del modelo relacional de la base de 
datos utilizando el software que el grupo crea conveniente, en formato PDF, en el 
link de entrega que estará disponible en el aula de esta asignatura. 
El documento debe contar, además, con carátula donde deberá constar el 
legajo, apellido y nombre de cada integrante del grupo, curso, materia y fecha de 
entrega. Y si fuera necesario una hoja con la explicación o aclaración de parte o 
toda la base de datos en caso de ser necesario.

El archivo a entregar debe tener un nombre acorde, por ejemplo: 
1WX_GrupoX_Parte1, donde 1WX corresponde al curso (1W1, 1W3) y GrupoX al 
número de grupo correspondiente. En caso de presentarlo una segunda vez para 
corrección pueden agregarle la palabra “Correccion1” para diferenciarlo del original. 
No deberán entregarse las sentencias de definición ni de actualización de 
datos empleados para la creación y edición de las tablas de la base de datos
Fecha de entrega: antes del 7 de octubre de 2021 a las 23:59.

* 2da. Parte: 
enunciado de lo que se quiere mostrar en la consulta y código de 
la consulta que responda ese enunciado. Deberá entregarse junto con la primer 
parte en un único documento con un nombre apropiado, por ejemplo: 
1WX_GrupoX_Parte2. Para entregar esta segunda parte, la primera debe estar ya 
aprobada.

El nivel de complejidad de estas consultas debe estar de acuerdo con el 
grado de complicación de los ejercicios trabajados en clase, utilizando todos los 
conocimientos adquiridos en esta materia, donde existan composición de varias 
tablas, utilizando distintos tipos de test (distintas condiciones de búsquedas), 
consultas agrupadas, sumarias, subconsultas, vistas, procedimientos almacenados, 
funciones incorporadas y definidas por el usuario, triggers, tablas temporales y 
manejo de errores. 

Los resultados que se pretenden obtener de estas consultas pueden ser 
propuestos por el docente del curso o por los integrantes del curso. En este último 
caso, lo que se pretende mostrar, debe ser de utilidad para un supuesto usuario del 
Laboratorio de Computación II TPI Pág. 4
sistema (empleado, gerente, encargado o decisor de la entidad para la cual se 
diseña la propuesta). 

* Fecha de entrega: 
antes del 24 de octubre de 2021 a las 23:59.
3ra Parte: Presentación del ejecutable, el que será mostrado por todos los 
integrantes del grupo, en una computadora, al docente del curso; para ello las 
tablas de la base de datos deberá contener previamente datos cargados para tal 
fin, es decir todas las tablas de resultado deben mostrar filas. La muestra será 
realizada mediante Zoom y todos los integrantes deben poseer cámara o 
dispositivo similar.

Los test de comparación, correspondencia, pertenencia, rango etc., deben 
incluir el ingreso de datos por parte del usuario del sistema desde la respectiva 
pantalla de la aplicación.
La tabla resultante de la consulta debe ser visualizada en pantalla, el formato 
de presentación de dicha información queda a criterio del grupo que la presenta 
teniendo en cuenta que dentro de los criterios de evaluación cuenta la calidad de la 
presentación.

El docente podrá realizar preguntas, referidas al práctico, a cualquier 
integrante del grupo, de tal forma que todos puedan demostrar que participaron 
activamente en la realización de todo el práctico.
La presentación de esta tercera parte supone que las dos partes anteriores 
ya están aprobadas.

A modo de sugerencia, con respecto a la calidad de la presentación, el grupo 
puede suponer que debe vender la aplicación al docente el cual puede tomar el 
papel de usuario final del sistema.
No se requiere la programación de todo el sistema de base de datos; 
solamente la muestra de las consultas.

Fecha de presentación: 11 de noviembre de 2021 en el horario de clase.
Enunciados de los casos propuestos para el Práctico Integrador
La elección de uno de estos enunciados dependerá de la decisión del 
docente o bien de la puesta en común de todos los integrantes del grupo. Luego de 
realizado esto, deberán buscar información o asesoramiento del caso elegido con el 
objeto de realizar un correcto análisis del funcionamiento y de las necesidades de 
información típicas de ese tipo de sistema.

* Para todos los casos, tenga en cuenta de realizar filtros de tiempo (años, 
meses, o fechas ingresadas por el usuario o fijas) 

para evitar que el reporte traiga 
un listado de gran cantidad de registros históricos que no tengan sentido para el 
usuario y puedan entorpecer el tráfico de la comunicación entre cliente y servidor 
de la base de datos



* Sistema de Venta y Control de Stock de una Automotriz

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
A continuación, se presentan ejemplos de reportes posibles:
• Totales de facturación y promedio de facturación periódicos (por mes, 
trimestre, semestre, anuales, etc.)
• Automóviles más vendidos
• Automóviles que nunca se vendieron
• Porcentaje de compras por tipo de cliente
• Cantidad de vehículos entregados, promedio de montos, totales de 
ventas
• Cantidad de stock producido de autopartes por rango de fechas y/o por 
períodos


“If you absolutely can't tolerate critics, then don't do anything new or interesting“.
Jeff Bezos