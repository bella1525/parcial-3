# Proyecto Validador y Visualizador de Movimientos de Ajedrez (SAN)

## Integrantes
- samuel serna 
- isabella bejarano 

## Lenguaje utilizado
- Python 3

## Versión del compilador o IDE
- Python 3.10 (o superior)
- IDE recomendado: Visual Studio Code / PyCharm / cualquier editor que soporte Python

## Instrucciones para ejecutar
1. Asegúrate de tener Python 3 
2. Instala la librería `graphviz`
   
## funcion del programa 
- Movimiento: Representa un movimiento individual en la partida (aunque en el código actual sólo almacena el texto del movimiento).

- Analizador: Contiene patrones regulares que validan si un movimiento está bien escrito según notación algebraica estándar (SAN). Revisa línea por línea y movimiento por movimiento, reportando errores.

- NodoArbol: Nodo básico para construir un árbol, que contiene un movimiento y enlaces a nodos hijos (izquierda y derecha).

- ArbolPartida: Construye un árbol que representa los turnos de una partida, donde cada turno contiene movimientos de las piezas blancas y negras.

 - VisualizadorArbol: Usa la librería Graphviz para crear un gráfico visual del árbol de la partida.

- Función imprimir_arbol: Imprime en consola la estructura del árbol para revisión rápida

## explicacion

https://youtu.be/uQielL_GMPE?feature=shared

