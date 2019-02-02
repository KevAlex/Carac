# Impresión en caracol
***
### Elaborado por: 
* K. Alexander Diaz Pacheco
---
### Presentado para:
* Alejandro Daza (_Modelos de programación II_)
## Información del ejercicio: 
Dado un archivo `.txt` que contiene matriz cuadrada compuesta de letras, números _(un solo digito)_, etc.. imprimir dicha matriz en forma de caracol .
> Aclaración:cada elemento debe estar separado por **espacios en blanco** como el siguiente ejemplo de una matriz cuadrada (3x3):  
> a b c  
> d e a  
> g h i

---
### Funciones usadas:

* cargar_archivo(lab): Esta funcion se encargar de leer el archivo `.txt` para su posterior manejo .
* lon(lab): Funcion que determina la longitud de la lista devuelta por la funcion _cargar_archivo(lab)_
* der(lab,fil,col): Funcion encargada de recorrer la matriz hacia la derecha e imprimir los elementos 
* down(lab,fil,col): Funcion encargada de recorrer la matriz hacia abajo e imprimir los _elementos_
* izq(lab,fil,col): Funcion encargada de recorrer la matriz hacia la izquierda e imprimir los elementos 
* up(lab,fil,col): Funcion encargada de recorrer la matriz hacia arriba e imprimir los elementos 
* caracol(carac): Funcion encargada de poner en funcionamiento el recorrido de la matriz 
### Parametros:
    * cz: indica el tamaño de las columnas de la matriz
    * fz: indica el tamaño de las filas de la matriz
    * n: permite realizar una verificacion para compararlo con la posicion de la  fila
    * a: permite realizar una verificacion para compararlo con la posicion de la columna
    * lab: hace referencia al archivo .txt
    * fil: hace referencia a la posicion de la fila en la matriz
    * col: hace referencia a la posicion de la columna en la matriz 
    * carac: refiere al archivo .txt a leer  
    * h: contador que permite imprimir el ultimo elemento de la matriz
    
> El programa fue realizado en Python




