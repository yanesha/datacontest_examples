# Reto de programación - Datathon URP

## Problema
Se debe entregar encomiendas en varias ubicaciones del mundo, teniendo para ello un mapa con un punto por ubicación exacta, y las respectivas distancias entre cada punto.

Los puntos de inicio y fin deben ser distintos pero debe visitar cada ubicación exactamente una vez. ¿Cuál es la distancia más corta que puede recorrer para lograr esto? Por ejemplo, dadas las siguientes distancias:

London to Dublin = 464

London to Belfast = 518

Dublin to Belfast = 141

Las posibles rutas son:

Dublin -> London -> Belfast = 982

London -> Dublin -> Belfast = 605

London -> Belfast -> Dublin = 659

Dublin -> Belfast -> London = 659

Belfast -> Dublin -> London = 605

Belfast -> London -> Dublin = 982

Siendo el más corto London -> Dublin -> Belfast = 605

A continuación tiene el archivo rutas.txt con las distancias a considerar, se calificará el método de lectura del archivo, la estrategia de resolución y el resultado mismo.

## Nota
Puedes practicar sin ver el archivo 'reto.py', el archivo a resolver es 'rutas.txt' y hay un archivo de ejemplo 'ejemplo.txt'.
