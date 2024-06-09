# Apuntes tercera clase
video en [YouTube](https://youtu.be/eV-N1ozcZrk?si=nTyxrnYWdiq7s-uL)

Comienza resumiendo los concetos de perceptrón y su funcionamiento.

### Teorema de Aproximación Universal

Esta función es suficientemente poderosa para cualquier problema [artículo Wikipedia](https://es.wikipedia.org/wiki/Teor%C3%ADa_de_la_aproximaci%C3%B3n)

> Sea F una función continua que va de [o,1]k -> [0.1]

> Para todo E>0 existen W, b, U tal que F(x) = sig(xW + b)U

> f(x) - F(x) | <E para todo xE[0,1]k

Otro [link](https://es.eitca.org/artificial-intelligence/eitc-ai-adl-advanced-deep-learning/neural-networks/neural-networks-foundations/examination-review-neural-networks-foundations/what-is-the-universal-approximation-theorem-and-what-implications-does-it-have-for-the-design-and-capabilities-of-neural-networks/)

Entonces una función que se ve tan simple puede ser tan poderoso para aproximar cualquier problema. Hay que ver en las funciones si puedo reemplazar amplitud con profundidad. Este teorema funciona con cualquier función que tiene limite por arriba y por abajo. Por ejemplo Relu(u) tiene problemas con una sola capa.

### Redes Feed-Forward
Luego hace un nuevo dibujo de redes neuronales en capas más que de perceptrones. Estos son los multi-layer perceptron (MLP) [link Datacamp](https://www.datacamp.com/tutorial/multilayer-perceptrons-in-machine-learning) 

Estas Redes se llaman Feed-Forward porque por los datos entran por la entrada y fluyen hasta el final. Por ejemplo las redes convolucionales también fluyen hasta el final. 