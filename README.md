# Deep Learning Forecasting S&P500

Forecasting para el indice S&amp;P500 utilizando RNN y CNN 

Se utilizó los datos diarios de 10 años de este indice y se construyó 3 modelos
  
  * Red neuronal recurrente univariada
  * Red neuronal convolucional univariada
  * Red neuronal convolucional multivariada
  
Para la construcción de cada modelo se tunearon la cantidad de retardos, capas y neuronas para cada uno y luego grid search para cada uno de los hyperparámetros de los de modelos, adicional se hace un stacking de modelos, utilizando 2 métodos, uno es un promedio y otro es un combinador lineal de estos modelos 






