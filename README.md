**Model Card: Proyecto Final Clasificador de Imágenes**   


**Resumen del Modelo**  
Este modelo es una red neuronal básica que se utiliza para clasificar dígitos escritos a mano en la base de datos MNIST. La red neuronal consta de una capa de entrada de 784 nodos (representan los píxeles en cada imagen de entrada de 28x28). El modelo utiliza la función de activación sigmoid en las capas ocultas y la función de activación softmax en la capa de salida.


**Propósito y Justificación**
La creación de un modelo de redes neuronales para MNIST tiene implicaciones educativas importantes. La creación de modelos básicos de redes neuronales es una forma efectiva de aprender los conceptos fundamentales detrás de la construcción y entrenamiento de redes neuronales, lo que puede ser útil para aquellos que se están iniciando en el campo del aprendizaje automático o que buscan una comprensión más profunda de los conceptos.


**Detalles del Modelo**  
Base de datos: MNIST  
Tamaño de entrada: 784 nodos (28x28 píxeles)  
Capa oculta: 512 nodos  
Capa de salida: 10 nodos  
Algoritmo de optimización: Adam  
Precisión (accuracy) en el conjunto de prueba: 97.32%


**Rendimiento del Modelo**  
El modelo se experimento con un total de 4 versiones diferentes. Fueron evaluados utilizando la precision como métrica de rendimiento. Después del entrenamiento, el modelo mas optimo logró una 97.32% en el conjunto de prueba. Este tenia 512 capas ocultas, 10 nodos de salida. 


**Sesgos Potenciales**  
Es importante tener en cuenta que este modelo puede ser susceptible a sesgos si la base de datos de entrenamiento no es representativa de la población general. Además,


**Limitaciones**  
Este modelo es limitado en su capacidad para reconocer dígitos escritos a mano en situaciones en las que la calidad de la imagen es pobre o la escritura es ilegible.
