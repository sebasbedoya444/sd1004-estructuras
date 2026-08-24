## ¿Que estructura me costó mas?
Los diagramas estaban relativamente fácil, según la explicación de el video que vi fue fácil imaginármelos y diagramarlos, el que me costo un poco mas entender fue el linkend list ya que va por nodos, pero después lo repase bien y lo logre hacer y entender mas.

## Reto Mental
#### 1. Spotify
Yo creo que utiliza la estructura de datos de Queue (una cola), porque la fila de canciones funciona estrictamente bajo la lógica FIFO (First In, First Out). La primera canción que agregas a la cola es la primera que debe sonar al terminar la actual. Un arreglo o una pila no funcionarían bien aquí porque una pila reproduciría primero lo último que agregaste, y la cola garantiza un orden de llegada.

#### 2. WhatsApp (Estados)
Yo creo que usa una Lista Enlazada ya que cuando ves los estados de tus contactos, avanzas del estado de una persona al de la siguiente mediante una secuencia. Si alguien elimina su estado o pasa el tiempo de expiración (24 horas), una lista enlazada permite eliminar ese nodo o reconectarlo en memoria al instante sin tener que reorganizar todo el grupo de estados, algo que en un arreglo fijo sería muy ineficiente.

#### 3. YouTube (Buscador y autocompletado de videos)
Yo creo que utiliza una Tabla Hash (Hash Table) ya que YouTube maneja miles de millones de videos. Para encontrar un video o canal al escribir una palabra clave en el buscador, necesita una estructura con tiempo de búsqueda casi instantáneo. La Tabla Hash toma el texto ingresado como una clave (key) y apunta directamente a la dirección en memoria del video o lista de resultados (value), evitando tener que recorrer el sitio video por video desde el inicio.
