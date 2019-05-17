He empleado la red neuronal para clasificar un dataset formado por más de 5000 piezas de lego. Utilizando varias capas convolutivas
y funciones de max pooling he llegado a una precisión del 97% al clasificar las piezas en una de las 16 categorías que hay. Al 
principio la red tenía underfitting, para solucionarlo he añadido 3 capas convolutivas más y he aumentado el tamaño del batch además
de poner a 400 los pasos por época. Se adjuntan en el github los resultados de varias pruebas hechas con cambios en los hiperparámetros.
