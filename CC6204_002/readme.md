# Segunda clase
[link](https://youtu.be/mDCxK2Pu0mA?si=KchBbtRnZSx0Xqli)
Primer concepto: perceptrón. Unidad muy básica inspirada en como funcionan las neuronas humanas.

### Perceptrón
El modelo es una unidad que recibe entradas, cada uno va a tener distintos pesos y va a tener una salida ¿Cómo se va a computar es salida? 

También tenemos un parámetro de sesgo que no tiene entrada ni peso.
Vamos a tener una variable (u) que es una ponderación de las entradas, es una suma de las multiplicaciones de las entradas y los pesos, más el sesgo. Por ejemplo:

> u = X1xW1 + X2xW2 + ... + XnxWn + b


> y = f(u)

#### Funciones de activación
Las funciones de activación las veremos en esta clase. La unidad más básica es es la función escalón. Esta tiene valores entre cero y uno. Uno es para cualquier valor positivo. Si el perceptrón es negativo la neurona no se activa, en caso distinto si se activa. 
Esta es una función que no se usa en general, aunque para tñerminos históricos es bueno saberlo.

La función que se utiliza regularmente es Sigmoid function (Función sigmoide) es una especie de aproximación a la función escalón, pero que es continua y suave. Cumple un rol parecido, pero cuando lo acumulado en el perceptrón es negativo no se activa, pero funciona distinto cuando está cerca del cero. Acá un [link de Wikipedia](https://es.wikipedia.org/wiki/Funci%C3%B3n_sigmoide) ahí la fórmula.

Otra función de activación muy común