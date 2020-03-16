# Bakery

Con el proyecto se pretende aumentar el
volumen de ventas de una panadería averiguando patrones en el comportamiento de venta de los
consumidores que puedan ser aprovechables desde el punto de vista comercial.

Para lograr encontrar estos patrones se utilizará el algoritmo Apriori. Dicho algoritmo nos proporcionará
reglas a partir de las que averiguaremos cuál es el par de productos entre los que existe una cierta
asociación. El algoritmo procede identificando los ítems individuales frecuentes en el dataset y
extendiéndolos a conjuntos de mayor tamaño siempre y cuando esos conjuntos de datos aparezcan
suficientemente soportados en dicha base de datos. El objetivo será encontrar reglas de la forma if
{Producto A} then {producto B} que tengan un soporte alto para los datos de nuestro dataset
