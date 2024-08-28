# Gestor de ejercicios de Gym y Calistenia

Este es una aplicación desarrollada en Flutter eficaz para utilizarla cuando vamos a entrenar, sea en el gimnasio o en nuestra casa.

## I) HISTORIAS DE USUARIOS

#### 1. Gestionar los ejercicios
* Descripcion: Como usuario necesito poder añadir, eliminar y modificar los ejercicios y elegir sus propiedades.
* Estado: En desarrollo.

#### 2. Gestionar los registros historicos de la ejecución de ejercicios.
* Descripcion: Como usuario necesito ejecutar los ejercicios. 
Esto se hace seleccionando el ejercicio, creando el peso a usar, creando un dia de ejecución 
y añadiendo las repeticiones realizadas en ese mismo día para que asi se guarde en la base de datos histórica de repeticiones.
* Estado: Completo.

#### 3. Gestionar las rutinas
* Descripcion: Como usuario tengo la libertad de añadir, eliminar y modificar las rutinas y sus ejercicios
* Estado: En desarrollo.

#### 4. Ejecución de las rutinas
* Descripcion: Como usuario necesito ejecutar las rutinas añadiendo las repeticiones por ejercicio, estas repeticiones tienen que guardarse en la base de datos histórica de repeticiones.
* Estado: En desarrollo.


## II) CRITERIOS DE ACEPTACIÓN

#### 1. Gestionar los ejercicios

##### AC 1.1 Creación de un ejercicio
* Descripcion: **Dado** un usuario <br> 
**cuando** registra un nuevo ejercicio<br> 
**entonces** se la añade a la lista de ejercicios de manera automática<br> 
**y** se puede modificar su información.
* Estado: Pendiente

##### AC 1.2 Creación de ejercicio unilateral
* Descripcion: **Dado** un usuario <br> 
**cuando** registra un nuevo ejercicio<br> 
**y** selecciona que es unilateral<br> 
**entonces** cada repeticion se ejecutará solo con el brazo izquierdo o derecho.
* Estado: Pendiente

#### 2. Gestionar los registros historicos de la ejecución de ejercicios.

##### AC 2.1 Añadir pesos
* Descripcion: **Dado** un ejercicio seleccionado<br>
**cuando** se registra un nuevo peso<br> 
**entonces** se la añade a la lista de pesos del ejercicio de manera automática.<br> 
* Estado: Pendiente

##### AC 2.2 Añadir nuevo día de ejecución
* Descripcion: **Dado** un peso seleccionado<br> 
**cuando** añadimos un nuevo día<br>
**entonces** se la añade a la lista de dias de manera automática con 0 repeticiones totales<br>
**y** la fecha actual. <br>
* Estado: Pendiente

##### AC 2.3 Añadir nueva serie
* Descripcion: **Dado** un día seleccionado<br> 
**cuando** registra una nueva serie con un numero de repeticiones <br>
**entonces** se la añade a la lista de series ejecutadas en el día <br> 
**y** se actualiza el número de repeticiones totales de manera automática. <br> 
* Estado: Pendiente


#### 3. Gestionar las rutinas

##### AC 3.1 Creación de una rutina
* Descripcion: **Dado** un usuario <br> 
**cuando** registra una rutina con los datos validos<br> 
**entonces** se actualiza la lista de rutinas.
* Estado: Pendiente

##### AC 3.2 Seleccion de los ejercicios de la rutina
* Descripcion: **Dado** una rutina creada <br> 
**cuando** seleccionamos los ejercicios de la rutina<br> 
**entonces** se actualiza la lista de ejercicios de la rutina de manera automática
* Estado: Pendiente

##### AC 3.3 Eliminación de una rutina
* Descripcion: **Dado** las repeticiones y dias ejecutadas de la rutina <br> 
**y** el registro automatico en la base historica <br>
**cuando** intento eliminar una rutina,<br> 
**entonces** se debe cambiar el id del dia de la rutina a las repeticiones y sus dias de la base historica <br> 
**y** se deben eliminar todos los registros y datos de esta rutina.
* Estado: Pendiente


#### 4. Ejecución de las rutinas

##### AC 4.1 Adición de un nuevo día
* Descripcion: **Dada** una rutina ya creada <br> 
**cuando** seleccionamos la opcion "Add a new day"<br> 
**entonces** se actualiza la lista de días registrados.
* Estado: Pendiente

##### AC 4.2 Ejecución de los ejercicios de la rutina
* Descripcion: **Dado** un dia registrado en la rutina <br> 
**y** los ejercicios ya establecidos <br> 
**cuando** modificamos las series y repeticiones en cada ejercicio de la rutina<br> 
**entonces** se actualizan el conteo de repeticiones y series de los ejercicios de la rutina de manera automática
**y** tambien se actualiza los registros historicos del conteo de repeticiones y series de los ejercicios.<br> 
* Estado: Pendiente