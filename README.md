# Trabajo Práctico Integrador

## Objetivos:

Que el alumno sea capaz de:
• Integrar los conocimientos adquiridos en las materias Laboratorio de 
Computación I y II y Programación I y II.
• Aplicar dichos conocimientos a un caso práctico.
• Trabajar en grupo en forma ordenada y eficiente.

## Evaluación y Calificación:

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

## Los temas propuestos para el diseño del sistema de base de datos son:
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


# Primera Parte: 

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

# 2da. Parte: 
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

Fecha de entrega: antes del 24 de octubre de 2021 a las 23:59.
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

Para todos los casos, tenga en cuenta de realizar filtros de tiempo (años, 
meses, o fechas ingresadas por el usuario o fijas) para evitar que el reporte traiga 
un listado de gran cantidad de registros históricos que no tengan sentido para el 
usuario y puedan entorpecer el tráfico de la comunicación entre cliente y servidor 
de la base de datos

1.- Sistema Académico de las Tecnicaturas de la UTN FRC
Diseñar una base de datos que permita administrar información referente a 
los datos de los alumnos, las carreras en las que está inscripto, las notas de 
parciales y exámenes finales, docentes a cargo de las materias. Tomar como 
ejemplo el sistema académico de la Universidad Tecnológica Nacional Facultad 
Regional Córdoba.

Entre otras, la información que se necesita que el sistema brinde es el 
siguiente:

• Datos estadísticos sobre el estado académico de los alumnos a lo largo 
del tiempo: cantidad de alumnos regulares, libres, por materia, curso, 
carrera, año de cursado. Promedio de notas por alumno, materia, año, 
curso, etc.
• Cantidades de alumnos (promedio de notas, cantidad de materias 
regulares y aprobadas) por edades, estado civil, situación habitacional y 
laboral, etc.
• Alumnos que no han rendido (o no han aprobado) ninguna materia en los 
últimos años.
• Alumnos que no han cursado materias en el último año. 
2.- Venta de entradas con butacas numeradas en un complejo de 
cines

Un conocido complejo de salas de exhibición de films de la Ciudad de 
Córdoba desea contar con un sistema que registre la compra de tickets por parte de 
los clientes.


Para ello se debe diseñar una base de datos teniendo en cuenta la 
información relevada para tal fin: Esta empresa posee varias salas de proyección 
de distintos tipos (común, vip, 3D, etc.), todas ellas con butacas numeradas. 
En el momento en que una persona se acerca a comprar entradas (a una 
ventanilla o por Internet), se emite un comprobante donde figuran los datos de la 
compra realizada (película, tipo de sala, función, cantidad de entradas, monto y 
forma de pago) y además un ticket por cada entrada donde debe constar la sala, la 
película, día, horario (función) y el nro. de butaca. Una misma persona puede 
comprar, en un mismo momento varias entradas a distintas películas.
Hay que tener en cuenta, que existen días y horarios promocionales, es decir 
con descuentos.

Además, se pueden reservar entradas por internet la cual se confirma con el 
pago de estas. Esta reserva (si no se confirma) vence dos horas antes del inicio de 
función.

Pueden basarse para el desarrollo de esta base de datos y la posterior 
programación de los informes una sala conocida por el grupo.

## Los reportes posibles para este sistema de información son, por ejemplo:

• Ingresos totales mensuales por día de proyección, o por temporada 
(vacaciones de invierno, de verano, feriados) o por bloques horarios.

• Tipo de público que asiste en distintos horario o temporadas, tipos de 
películas vistas, etc.

• Tipo de público (menores, mayores, jubilados) que nunca asistió a una 
determinada película o tipo de película (terror, acción, animadas, etc.)

• Horarios o películas que no tuvieron ningún asistente

• Películas más vistas.

## 3.- Sistema de Venta y Control de Stock de una Automotriz

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

## 4.- Sistema de Venta de una Farmacéutica

Una cadena farmacéutica necesita llevar la información de su operatoria 
diaria de ventas al público y contar con reportes adecuados para un funcionamiento 
eficaz.

Laboratorio de Computación II TPI Pág. 8
La farmacéutica tiene distintas sucursales dispersas a lo largo del país, las 
cuales son abastecidas con suministros a través de empresas de logística y 
distribución ajenas al sistema. Cuando se entregan suministros en alguna sucursal 
por parte de la empresa de logística se registra la cantidad de cada uno de ellos 
identificados por su código de barras, además de quién realizó dicha entrega por 
parte de la empresa y el responsable (empleado de la farmacéutica) que recibió los 
suministros. 

La farmacéutica clasifica a los suministros en base a si son de venta libre o 
requieren una autorización o receta para poder ser entregados a los clientes. Los 
suministros pueden ser de diversos tipos como por ejemplo medicamentos, 
artículos de limpieza, higiene personal, estética, etc.
Cuando un cliente va a realizar compras en alguna sucursal, puede llevar 
algunos suministros que tengan cobertura por obra social (independientemente que 
sean de venta libre o no) por lo que deberá presentar la receta provista por el 
médico. Cada uno de esos productos puede o no tener algún descuento para dicha 
obra social en ese momento para la localidad donde se encuentra. Todos los 
meses las obras sociales envían la información de los descuentos que se deben 
ofrecer para cada tipo de producto para cada localidad del país.
Las obras sociales proveen un sistema externo de validación de afiliados, por 
lo que la farmacia debe ingresar los datos del cliente y el o los suministros que se 
encuentren en la receta además del nombre del médico y su matrícula. Una vez 
confirmados esos datos, estos sistemas externos devuelven un código de 
autorización a la farmacia que indica si la solicitud está aprobada o rechazada. A 
pesar de que este sistema no forma parte de la farmacéutica, se lleva un respaldo 
de la información ingresada en el portal de solicitud de coberturas por cuestiones 
de auditoría.

Todos estos descuentos realizados en suministros son facturados a la obra 
social que corresponda, por lo que se realiza un reporte con el listado de todos los 
tipos de suministros y las respectivas cantidades entregadas a los clientes para 
recibir el reembolso de la obra social. Una vez que este lote de suministros con 
descuentos ya fue reembolsado por la obra social se los marca para no ser vueltos 
a listar. Esto es así porque no necesariamente el listado para reembolso incluye 
suministros que hayan sido entregados en el mes que se está facturando.

Algunos posibles reportes que puede necesitar la farmacéutica son:

• Totales de facturación. Podría discriminarse por tipos de suministros, si 
fueron o no autorizados por obra social, etc.
• Reporte de reembolso para las obras sociales
• Clientes que realizaron compras el año actual sólo de suministros que 
requirieron autorización de obra social
• Cantidades de afiliados por obra social que realizaron compras, y total de 
descuentos aplicados
• Empresas de logística que más volumen de mercadería entregan


“If you absolutely can't tolerate critics, then don't do anything new or interesting“.
Jeff Bezos