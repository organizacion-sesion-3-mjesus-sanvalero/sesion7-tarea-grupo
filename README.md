# sesion7-tarea-grupo
EL PROBLEMA DE LA PRIMITIVA

 Crear un pequeña aplicación que gestione el juego de la primitiva incluyendo: la apuesta (que podrá ser generada de forma manual o automática), el sorteo y la determinación de premios.
 
 LA APUESTA:
 
 Una apuesta de la primitiva consiste en:
 
 • 6 números comprendidos entre el 1 y el 49, todos ellos diferentes
 
 • un reintegro generado por el sistema que es un número entre el 0 y el 9
 
 La generación de una combinación de la primitiva podrá ser generada de 2 formas:  
MANUAL (el usuario decide los números y el sistema genera un reintegro) y 
AUTOMÁTICA (el programa genera automáticamente los 6 números y el reintegro). 

EL SORTEO:

 Un sorteo consiste en:
 
 • 6 números comprendidos entre el 1 y el 49, todos ellos diferentes
 
 • un número complementario distinto de los 6 anteriores que tendrá su importancia en el caso del reparto de premios, al tener 5 números acertados
 
 • un reintegro generado automáticamente por el sistema que es un número entre el 0 y el 9
 
 Consiste en la generación automática de 6 números, un número complementario y un reintegro. icha generación se hará de forma automática por el sistema.
 
 Observaciones:  podemos utilizar parte del proceso anterior, puesto que ya hemos generado una combinación de forma automática, la única diferencia es que en este caso también deberemos enerar un número complementario.
 
 REPARTO DE PREMIOS. 
 
Esta fase consiste en establecer una serie de premios en función de los aciertos al comparar la apuesta con el sorteo y los reintegros. Los premios posibles en orden creciente, teniendo en cuenta que el reintegro se puede acumular a cualquiera de los demás premios, son:

 • Reintegro
 
 • 3 aciertos
 
 • 4 aciertos
 
 • 5 aciertos
 
 • 5 aciertos + el número complementario
 
 • 6 aciertos
