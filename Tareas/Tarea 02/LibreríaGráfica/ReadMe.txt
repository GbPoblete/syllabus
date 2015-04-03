Caracter�sticas de la interfaz:

* Botones de navegaci�n: son 4, cada uno entrega un valor diferente al ser 
presionado:
	-Arriba: (0, 1)
	-Abajo: (0,-1)
	-Izquierda: (-1, 0)
	-Derecha: (1, 0)
* Barra de zoom: retorna un valor del 0 al 99, el valor actual se indica entre los
botones de navegaci�n.
* Mapa: grilla donde est�n los elementos actuales.
* Barra de consultas: puedes cambiar de consulta presionando las flechas.
Para aquellas consultas que requieran m�s de un elemento,
sep�relos con una "," y sin espacios. Se toma el supuesto de que las consultas toman los argumentos de la siguiente forma:
	-consulta1: (Ubicaci�n, regi�n)
	-consulta2: (Ubicaciones, regi�n) [Siendo ubicaciones una lista]
	-consulta3: (ubicacion1, ubicacion2)
	-consulta4: (ubicaci�n, cantidad de sub-grillas)
	-consulta5: (ubicaci�n, cantidad)
* Las dimensiones son fijas, no se pueden modificar.



C�mo usar:

* Para usar la interfaz se toma la clase "Interfaz" del m�dulo "interfaz". Esta clase
recibe como par�metros la funci�n de zoom, la funci�n de navegaci�n, el mapa inicial,
y una lista de funciones que corresponden a las consultas. Estas funciones deben ser entregadas
por el orden que est�n en el enunciado.