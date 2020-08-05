Description
Data Set Information

Los experimentos se llevaron a cabo con un grupo de 30 voluntarios dentro de un rango de edad de 19-48 años. Cada persona realizó seis actividades (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) usando un teléfono inteligente (Samsung Galaxy S II) en la cintura. Usando su acelerómetro y giroscopio integrados, capturamos la aceleración lineal 3-axial y la velocidad angular 3-axial a una velocidad constante de 50Hz. Los experimentos se grabaron en video para etiquetar los datos manualmente. El conjunto de datos obtenido se ha dividido aleatoriamente en dos conjuntos, donde se seleccionó el 70% de los voluntarios para generar los datos de entrenamiento y el 30% de los datos de la prueba.

Las señales del sensor (acelerómetro y giroscopio) se preprocesaron aplicando filtros de ruido y luego se tomaron muestras en ventanas corredizas de ancho fijo de 2.56 segundos y 50% de superposición (128 lecturas / ventana). La señal de aceleración del sensor, que tiene componentes gravitacionales y de movimiento corporal, se separó usando un filtro de paso bajo Butterworth en aceleración corporal y gravedad. Se supone que la fuerza gravitacional solo tiene componentes de baja frecuencia, por lo tanto, se utilizó un filtro con una frecuencia de corte de 0.3 Hz. De cada ventana, se obtuvo un vector de características calculando variables del dominio del tiempo y la frecuencia.


Para cada registro en el conjunto de datos se proporciona:

   -Aceleración triaxial del acelerómetro (aceleración total) y la aceleración corporal estimada.
    -Velocidad angular triaxial desde el giroscopio.
    -Un vector de características 561 con variables de dominio de tiempo y frecuencia.
    -Su etiqueta de actividad.
    -Un identificador del sujeto que realizó el experimento.
