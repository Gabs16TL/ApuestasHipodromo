# Apuestas Hipodromo
- Se le solicita realizar un diseño de base de datos para el manejo de apuestas y control de carreras realizadas en un Hipódromo.
- En cada carrera participan 10 caballos
- Por los cuales las personas pueden apostar una cierta cantidad de dinero
- Cuando una persona realiza una apuesta, elige un caballo ganador y un monto, además debe apuntar el posible orden de llegada de los 9 caballos restantes. 
- Dichas apuestas sólo pueden ser realizadas con un lapso de tiempo de 2 horas antes de que se lleve a cabo la carrera esto por temas de seguridad y transparencia de los resultados. 
- Dado que al momento exacto en el que inicie la carrera las apuestas se cierran y al finalizar se deben de mostrar los resultados, el procesamiento de las apuestas debe de ser el más óptimo posible ya que esto transcurre en pocos segundos mejorando la optimización en la entrega de los resultados en tiempo real. 
- Para poder aceptar una apuesta se debe verificar que cuenten con el orden de llegada de los 10 caballos (todos los participantes), corroborando que ninguno de estos se repita, por ende si no cumplen dicha condición se descarta la apuesta. 
- Al finalizar la verificación de todas las apuestas disponibles se deberá guardar los detalles de las apuestas que no fueron aprobadas (rechazadas). 
- Cuando termine la carrera se debe de procesar las apuestas para poder calcular los resultados, esto inmediatamente después de ingresar el resultado de la carrera, el cálculo se realizará en base a los siguientes criterios, 
si la persona atino la primera posición 10 puntos, segunda posición 9 puntos y así sucesivamente. 
- Dichos resultados se deben de mostrar de acuerdo a la configuración de orden la cual puede ser en orden alfabético de acuerdo a los nombres de los apostadores o en orden del puntaje obtenido (por defecto).
