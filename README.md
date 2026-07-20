# Deflactor-de-montos-monetarios

El deflactor de esta guía se construye a partir del índice acumulado de precios implícitos que publica Inegi en el Banco de Información Económica (BIE, https://tinyurl.com/bdcwzvk6). La ruta para encontrar los datos necesarios es: Cuentas nacionales > Producto interno bruto trimestral, base 2018 > Índice acumulado de precios implícitos, 2018=100 > Producto Interno Bruto (Índice base 2018=100), Estados Unidos Mexicanos. Para los períodos posteriores no incluidos aún en esta base, se utiliza el deflactor del PIB publicado en los Criterios Generales de Política Económica, en la tabla Marco Macroeconómico.
Una vez que se descargan los datos para el período deseado, se seleccionan las observaciones correspondientes al cuatro trimestre de cada año y se realiza la siguiente operación aritmética:
Deflactor=Índice acumulado de precios implícitos para el año corrienteÍndice acumulado de precios implícitos del año base 100
Por ejemplo, para calcular el deflactor del año 2025 a precios de 2026, con base en los siguientes valores:
•	Índice acumulado de precios implícitos para 2025 =  143.137535116071 
•	Índice acumulado de precios implícitos para 2026 =  148.147348845133 
Entonces, el deflactor de precios de 2025 para el año base 2026 —es decir, si queremos pasar un valor de 2025 a precios de 2026— se calcula de la siguiente forma:
Deflactor2025,2026 = 100 = 143.137535116071 148.147348845133 x 100  =  96.618357488
Es decir, el deflactor para pasar un valor de 2025 a precios de 2026 es 96.618357488.

Cómo elegir el deflactor correcto
La tabla de deflactores cruza los años corrientes (identificado por el número del año) con los años base (identificados con el número de año, seguido de “= 100”). De esta forma, si queremos transformar un valor corriente del año 2025 a precios de 2026 (es decir, con 2026 como año base), entonces debemos buscar el cruce de la fila “2025” y la columna “2026 = 100”. 

