# Recuperacion_funcionalidad_contador_de_puntos_culebrita

ALGORITMO
CONTADOR DE PUNTOS 
-al comer mazanas el jugador recibira un puntaje

VARIABLES DONDE SE GUARDEN LOS PUNTOS 
Las veriables seran:
-puntos
-manzanas_comidas 

INICIALIZAR LAS VARIABLES 
 El valor de cada variable sera inicializado de esta manera:
-puntos = 0
-manzanas_comidas = 0

BIENVENIDA Y INSTRUCCIONES PARA EL JUGADOR 
Las instrucciones seran claras e intuitivas:
-Se le da la bienvenida y se le indica lo que queremos que haga 
-tambien le indicamos que debe presionar las flechas de teclado para moverse y que empiece a ganar puntos 

PROCESO
El proceso que se ejecuta
-se lee el dato de las manzanas comidas por el jugador
-se corrobora que el dato sea > 0 
-luego se toma una desicion 
-si la condicion se cumple se hara un calculo 
-si la condicion es falsa o no se cumple se le imprimira un mensaje que le diga que no gano puntos esta vez

PUNTAJE FINAL 
-al final si la condicion se cumple se le mostrara el puntaje que obtuvo



PSEUDOCODIGO

[UploAlgoritmo puntaje_culebrita
		DEFINIR puntos COMO ENTERO;
		DEFINIR manzanas_comidas COMO ENTERO;
		puntos = 0;
		manzanas_comidas = 0;
		ESCRIBIR "Bienvenido presiona enter para iniciar";
		ESCRIBIR "Debes mover las fleclas para comer manzanas y empezar a ganar puntos";
		LEER manzanas_comidas;
		SI manzanas_comidas > 0 ENTONCES
			puntos = puntos + manzanas_comidas * 5;
			ESCRIBIR"Tu puntaje es de: ",puntos;
		SINO 
			ESCRIBIR"Nos has ganado puntos esta vez";
		FinSi
FinAlgoritmo

ading puntaje_culebrita.psc…]()


![pseudocodigo 2025-03-28 094531](https://github.com/user-attachments/assets/b093a050-5eb7-49de-b756-56d3372ed28d)




DIAGRAMA DE FLUJO 


![DIAGRMA DE FLUJO  2025-03-28 120533](https://github.com/user-attachments/assets/89edc274-068b-45e3-b034-0d85c1a58165)

![DIAGRAMA  2025-03-28 120352](https://github.com/user-attachments/assets/6ac0b0d9-6f7a-40a4-9f66-aec1b31ec480)

