
Inicio
    Define Lista de Calificaciones como una lista 
    Define suma en 0 
    Define numero de calificaciones en 0
    Define promedio en 0 

    Para cada calificacion en la lista hacer
        suma cada dato de lista de calificaciones 
        = suma total 

    Contar 
        Contamos la cantidad de calificaciones de la lista 
        = Numero de calificaiones 

    Promedio
        Suma total / Numero de calificaiones 
        = Promedio total 

    Si el promedio total >= 3.0 
        Imprimir "Felicidades Ana ganaste el curso" + promedio total 

    si el promedio total <  3.0
        imprimir "Lo siento pero reprobaste el curso" + promedio total

Fin




Inicio 
    Definimos variables
        Definir Velocidad como lista_V
        Definir Tiempo como lista_T
        Definir Distancia recorrida en 0 

        Multiplicamos las velocidades por los tiempos 
            (Lista_V * Lista_T) = Distancia_Total 

            Multiplicamos el dato 1 de Lista_V con el dato 1 de Lista_T

    Imprimir "La distancia total recorrida fue (Distancia_total)"

FIN


    



Inicio

    // Definimos variables (N=Nacimiento)
        Definir diaN, mesN, añoN 
        Definir diaAct, mesAct, añoAct 
        Definir años, meses, dias 

    Leer diaN, mesN, añoN
    Leer diaAct, mesAct, añoAct


    // Calcular años
        años <- añoAct - añoN
    

    // Calcular meses
        Si mesAct >= mesN entonces
            meses <- mesAct - mesN
        Sino
            meses <- (mesAct + 12) - mesN
        Fin Si
    
    // Calcular días
        Si diaAct >= diaN entonces
            dias <- diaAct - diaN
        Sino
            dias <- (diaAct + 30) - diaN // Asumimos 30 días para simplificar
            meses <- meses - 1
        Fin Si

    // Verificar si es su cumpleaños
        Si diaAct = diaN y mesAct = mesN entonces
            Imprimir "¡Hoy es tu cumpleaños!"
        Fin Si

        Imprimir "Tienes " + años + " años, " + meses + " meses, y " + dias + " días"
Fin
