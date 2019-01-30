# Impresión en caracol
***
### Elaborado por: 
* K. Alexander Diaz Pacheco
---
### Presentado para:
* Alejandro Daza (_Modelos de programación II_)
## Información del ejercicio: 
Dado un archivo `.txt` que contiene matriz cuadrada compuesta de letras, números, etc.. imprimir dicha matriz en forma de caracol .
> Aclaración:cada elemento debe estar separado por **espacios en blanco** como el siguiente ejemplo de una matriz cuadrada (3x3):  
> a b c  
> d e f  
> g h i

---
### Funciones usadas:

* cargar_archivo(lab): Esta funcion se encargar de leer como parametro (_lab_) el archivo `.txt` para su posterior manejo .

* road(elem): Funcion que guarda en una lista los elementos impresos previamente en forma de caracol.
* lon(lab): Funcion que determina la longitud de la lista devuelta por la funcion _cargar_archivo(lab)_
* der(lab,fil,col): Funcion encargada de recorrer la matriz hacia la derecha, imprimir los elementos y guardarlos en la lista de la funcion _road(elem)_
* down(lab,fil,col): Funcion encargada de recorrer la matriz hacia abajo, imprimir los elementos y guardarlos en la lista de la funcion _road(elem)_
* izq(lab,fil,col): Funcion encargada de recorrer la matriz hacia la izquierda, imprimir los elementos y guardarlos en la lista de la funcion _road(elem)_
* up(lab,fil,col): Funcion encargada de recorrer la matriz hacia arriba, imprimir los elementos y guardarlos en la lista de la funcion _road(elem)_
* caracol(carac): Funcion encargada de poner en funcionamiento el recorrido de la matriz 
### Parametros:
    * elem: refiere al elemento a guardar en la lista
    * lab: hace referencia al archivo .txt
    * fil: hace referencia a la posicion de la fila en la matriz
    * col: hace referencia a la posicion de la columna en la matriz 
    * carac: refiere al archivo `.txt` a leer
> El programa fue realizado en Python




