##### inicio: costoFijaciondePrecioBase

##### &#x20;    

##### &#x20;             definir: costoBase, como entero

##### &#x20;             definir: gananciaEsperada, como entero

##### &#x20;             definir: valorGanancia, como entero

##### &#x20;             definir: subtotal, como entero

##### &#x20;             definir: impuestoMonto,  como decimal

##### &#x20;             definir: precioFinal, como decimal

##### &#x20;             

##### &#x20;              IMPUESTO_IVA= 0.19

##### 

##### &#x20;     entrada: escribir: "ingresar costo base"

##### &#x20;              leer: costoBase

##### &#x20;              escribir: "ingrese ganancia esperada"

##### &#x20;              leer: gananciaEsperada

##### 

##### &#x20;     proceso: valorGanancia <- costoBase \* ganaciaEsperada

##### &#x20;              subtotal      <- costoBase + valorGanancia

##### &#x20;              impuestoMonto <- IMPUESTO_IVA= 0.19 \* subtotal

##### &#x20;              preciofinal   <- impuestoMonto + subtotal

##### 

##### &#x20;     salida: imprimir "el valor de la ganancia es", valorGanacia

##### &#x20;              imprimir "subtotal es", subtotal 

##### &#x20;              imprimir "el impuesto IVA aplicado sobre el subtotal es", impuestoMonto 

##### &#x20;              imprimir "el precio final al publico es", precioFinal 

##### 

##### final
