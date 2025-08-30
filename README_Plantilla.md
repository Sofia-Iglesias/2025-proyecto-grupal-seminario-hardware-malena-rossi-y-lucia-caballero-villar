# **`Nombre del Proyecto`**

`Tecnología de los Sistemas de Información - Seminario Avanzado`  
`Ciclo Lectivo 2025`
Documento de google: https://docs.google.com/document/d/1u7MkA4-LgH85kjfDXtkuWASeIknJe-Sx_1jN9wlRQZ0/edit?usp=sharing
## **`Integrante/s`**

- Lucia Caballero Villar 
- Malena Rossi

## **`Objetivo`**

Nuestro proyecto consiste de un semaforo inteligente, distinto y evolucionado de los que utilizamos hoy en dia. Actualmente, los peatones deben esperar en la vereda a pesar de que no este circulando ningun auto, lo que lo convierte en un sistema de regulacion inacertado e inservible. Por ello, este semaforo nos brinda la oportunidad de priorizar tanto peatones como vehiculos por la interaccion que sucede entre ellos y los componentes.

## **`Descripción del Proyecto`**

`Este proyecto es un semaforo inteligente con la intencion de cambiar como funciona la relacion peaton-vehiculo en las calles. Para esto, utilizamos una serie de componentes mencionados en el siguiente punto los cuales permiten que la corriente sea fluída. Lo explicaremos con situaciones hipoteticas para que se comprenda lo mayor posible de nuestro proyecto:
    Caso 1: Un peaton esta esperando en la vereda y tiene su semaforo en rojo, por lo cual no pasa. Por otro lado, no hay ningun auto circulando, por lo que el sensor que detecta la presencia de peatones lo detecta y los que detectan la presencia de autos no detectan ningun vehículo, por lo tanto, el semaforo para peatones se pondra en blanco y para autos en rojo.
    Caso 2: Un peaton esta esperando en la vereda y hay autos circulando en las calles a mas de 30 km/h. Por lo tanto, al presenciar autos y peatones no pondra el semaforo de autos en rojo. En esa situacion, el peaton tiene la posibilidad de apretar un boton en el poste donde tambien se encuentra el sensor de presencia y se activara el conteo de 30 segundos para autos, dandoles tiempo para pasar. Pasados esos segundos, el peaton tendra su semaforo en blanco, significado de que puede circular
    Caso 3: Hay un peaton esperando y un auto yendo a 20 km/h en la calle, por lo tanto, el auto al estar yendo a una velocidad menor a la de 30 km/h, se pondra el semaforo en rojo para los autos y se concedera el paso del peaton/peatones.
    Caso 4: El semaforo para autos esta en rojo, pero en la vereda no hay ningun peaton esperando para circular en las calles. Por lo tanto, al no detectar la presencia de peatones pero si de autos se cambia el estado del semaforo de autos a verde y la de peatones a rojo.

## **`Componentes`**

- 2 botones input.
- 6 sensores de presencia input.
- 2 leds blancas output.
- 3 leds rojas output.
- 1 led amarilla output.
- 1 led verde output.
- 7 resistencias. (una para cada led)
- Display 2 digitos 7 segmentos output.



## **`Requisitos`**

- `Software necesario`  
- `Librerías`  
- `Hardware adicional`

`Completar una vez definido el proyecto.`

## **`Etapas del proyecto`**
### Etapa 1: conectar los 3 semáforos y el display.
- Conectar todas las leds con sus respectivas resistencias y llevar a cabo el circuito para comprobar que funcionan correctamente junto con el display y que lleve a cabo el conteo correctamente.

### Etapa 2: conectar los sensores de presencia del auto.
- Conectar los 4 sensores de presencia del auto y programarlos para que cuando detecte el auto en los primeros dos sensores comience un tiempo y al llegar al segundo par de sensores se termine de calcular la velocidad del auto y así determinar si el semáforo se pone en rojo para el auto o no.

### Etapa 3: conectar los sensores de presencia del peatón y los botones.
- Conectar los 4 sensores de presencia del peatón y programarlos para que cuando haya peatón se comience a calcular la velocidad de los autos para ver si el semáforo se puede poner en rojo para los autos y que el peatón pase o no. 
- Conectar los dos botones (uno de cada lado de la calle) para que el peatón toque en caso de querer cruzar pero no poder ya que los autos están yendo a más de 30 km/h, encendiendo de esta forma el timer del display.

### Etapa 4: programar situaciones de lo que puede pasar.
- Sin peatón ni auto detectado, semáforo para autos en verde.
- Sin peatón con auto detectado, semáforo para autos en verde.
- Hay peatón sin auto detectado, semáforo para peatón en verde.
- Hay peatón y auto a menos de 30 km/h, semáforo para peatón en verde.
- Hay peatón y auto a más de 30 km/h, semáforo para auto en verde.
- El peatón presiona el botón, se muestra en el display 30 segundos restantes para que pasen los autos y que luego haya semáforo verde para el peatón.

### Etapa 5: conectar todo lo programado.
- Tras todas las programaciones individuales, es necesario unificarlas todas para comprobar el funcionamiento correcto.

### Etapa 6: pasarlo al prototipo.
- Comenzar a construir el prototipo en el que llevaremos a cabo todo lo anteriormente hecho, utilizando las LEDs, botones, resistencias, sensores y display. 

## **`Extras`**

- `Extra 1`  
- `Extra 2`  
- `Extra 3`
