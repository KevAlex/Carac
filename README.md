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
a b c   
s f g
r t u

---
### Funciones usadas:

* cargar_archivo(lab): Esta funcion se encargar de leer como parametro (_lab_) el archivo `.txt` para su posterior manejo .

* road(elem): Funcion que guarda en una lista los elementos impresos previamente en forma de caracol. 
* lon(lab): Funcion que determina la longitud de la lista devuelta por la funcion _cargar_archivo(lab)_
* der(lab,fil,col): FUncion encargada de recorrer la matriz hacia la derecha, imprimir los elementos y guardarlos en la lista de la funcion _road(elem)_
* down(lab,fil,col): FUncion encargada de recorrer la matriz hacia abajo, imprimir los elementos y guardarlos en la lista de la funcion _road(elem)_
* izq(lab,fil,col): FUncion encargada de recorrer la matriz hacia la izquierda, imprimir los elementos y guardarlos en la lista de la funcion _road(elem)_
* up(lab,fil,col): FUncion encargada de recorrer la matriz hacia arriba, imprimir los elementos y guardarlos en la lista de la funcion _road(elem)_
* caracol(carac): FUncion encargada de poner en funcionamiento el recorrido de la matriz

> El programa fue realizado en Python


