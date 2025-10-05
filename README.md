# Actividad 3: Arboles en Java
# Integrantes: 
## Victor Alfonso Aguiar Yotagrí 
## Juan Pablo Usma Alvarez.


# Árbol Binario de Búsqueda en Java
Descripción del Proyecto
Este proyecto implementa un Árbol Binario de Búsqueda en Java con una interfaz de menú en consola que permite insertar números, buscarlos y visualizar el árbol ordenado.

## ¿Qué es un Árbol Binario?
Un árbol binario es una estructura de datos que organiza información de manera jerárquica, similar a un árbol genealógico.

## Características principales:
Nodo raíz: Es el primer elemento del árbol (la base)
Nodos hijos: Cada nodo puede tener hasta 2 hijos (izquierdo y derecho)

## Regla de ordenamiento:
Los números menores van a la izquierda
Los números mayores van a la derecha

## ¿Cómo se implementó?
Estructura del código:

## Clase Node (Nodo):
Representa cada elemento del árbol
Contiene un número (key) y referencias a sus hijos izquierdo y derecho

## Clase Tree (Árbol):
Contiene el nodo raíz
Métodos principales:

insert(): Agrega un nuevo número al árbol
search(): Busca si un número existe en el árbol
inorder(): Muestra los números ordenados de menor a mayor

## Clase Main:
Contiene el menú interactivo
Permite al usuario interactuar con el árbol

## Funcionamiento de las operaciones:
Inserción: El número se compara con cada nodo, yendo a la izquierda si es menor o a la derecha si es mayor, hasta encontrar un espacio vacío.
Búsqueda: Se recorre el árbol comparando el número buscado con cada nodo hasta encontrarlo o llegar a un nodo vacío.
Recorrido Inorden: Visita primero el hijo izquierdo, luego el nodo actual, y finalmente el hijo derecho. Esto muestra los números ordenados.

## Ejemplo de Ejecución en Consola:
## Captura 1:
<img width="1322" height="713" alt="image" src="https://github.com/user-attachments/assets/ddd3987e-5583-4f4d-a509-2c848ceff735" />
## Captura 2: 
<img width="1280" height="633" alt="image" src="https://github.com/user-attachments/assets/8235ed31-db37-41a7-a517-550376458d40" />
## Captura 3:
<img width="1262" height="601" alt="image" src="https://github.com/user-attachments/assets/4683ee32-d8d3-4c03-8096-35aeafabf8c4" />
## Captura 4:
<img width="1219" height="563" alt="image" src="https://github.com/user-attachments/assets/81005b1b-7da1-47eb-9b5f-d06cd8f51ccb" />



