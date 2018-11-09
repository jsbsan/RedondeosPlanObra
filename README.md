# RedondeosPlanObra


Tipo de aplicacion: terminal o consola (sin entorno grafico)

Uso de comando:
$./RedondeosPlanObra.gambas nombrefichero

¿que hace el programa?
Ajusta las cantidades mensuales de PEM (variando los decimales), para que aplicando los redondeos de 2 decimales, en las operaciones intermedias (cálculo de gastos generales, beneficio industrial e iva), las sumas y los totales den correctamente.

Nota:
1) Si haces los cálculos teniendo en cuenta todos los decimales, el resultado va a cuadrar bien siempre, pero cuando aplicas redondeos a 2 decimales en las operaciones intermedias, al final repercute que los totales haya pequeñas diferencias, que no cuadran con el total calculado con todos los decimales.

2) Puede haber varias soluciones, el progama te da la primera que encuentre. En diferentes ejecuciones, puede dar diferentes soluciones.

3) Metodo de cálculo: aleatorio por fuerza bruta hasta encontrar una solucion.


Estructura del fichero de datos:

  'la primera linea contienne las candidades mensuales en PEM
  
  'la segunda linea la suma total que debe de dar en PEM
  
  'la tercera linea el % gg
  
  'la cuarta linea el % bi
  
  'la quinta linea el % iva


Para Gambas3, compilado para la version 3.11.4. Es posible recompilarlo para versiones inferiores de Gambas3.
