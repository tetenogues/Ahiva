# Automatizacion del proceso de bining y data entry para la plataforma Ahiva del Correo Uruguayo.
Utilizando la libreria Pyoutogui y Selenium logre desarrollar la automatizacion de un proceso de conteo por categorias de un excel hasta el ingreso de los datos, ya procesados, en la plataforma web. Este webdriver tarda en total 1.5 minutos en realizar una tarea que de forma manual tardaria 20 minutos. 

Uno de los desafios a la hora de desallorar el codigo fue la velocidad del internet, es por esto que tuve que agregarle tiempos de descanso y una variable t que se puede ajustar dependiendo de si mejora o empeora la velocidad.

Otro parametro clave para poder tunear la posicion de los clicks que se programaron fue la funcion position() de la libreria Pyautogui para conocer las coordenadas del mouse adecuadas. 

Una de las limitaciones de este programa es que no se adapta frente a actualizaciones en el ui design de la plataforma donde opera. Ademas que tampoco se adapta a los diferentes tamaños de pantallas. Se genero en un tamaño (width=1366, height=768). 

Conclusion, es una solucion a la tarea rutinaria de data entry y se podria escalar a mas funciones. El desarrollo de este codigo fue de 2hs y me ahorro 7 horras al mes de tareas rutinarias y repetitivas.
