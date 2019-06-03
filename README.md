# Neuralnetwork-Actividad-1
Implementación de una red neuronal feedforward-Backpropagation para regresión.

Utilizando los conceptos y el material visto en clase realice lo siguiente:

  1. Implemente un red neuronal de alimentación hacia delante con algoritmo de retro-propagación del error (feedforward-Backpropagation Neuralnetwork).
  1. Por cada una de las function de la Tabla 1 realice:
     * Grafíque el comportamiento de la función dentro de los límites dados.
     * Genere aleatoriamente un conjunto de entrenamiento y un cojunto de prueba.
     * Entrene la red neuronal para ajustar a los datos de la función.
     * Grafíque el comportamiento real vs el ajuste de la red neuronal.
     * Grafíque el comportamiento de la red neuronal para descartar el sobre-entrenamiento (entrenamiento vs prueba).
     * Genere un nuevo conjunto y asegure que los datos son 100% nuevos, es decir, que no existan en los conjuntos de entrenamiento y prueba. Muestre el comportamiento de la red con el nuevo conjunto y muestre su error.

### Tabla 1. Funciones de prueba.

| Función   | límites |
| -----------| -------|
| ![equation](http://www.sciweavers.org/tex2img.php?eq=f_1%20%3D%20x%5E5%20%2B%20x%5E4%20%2B%20x%5E3%20%2B%20x%5E2%20%2B%20x&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0) | ![equation](http://www.sciweavers.org/tex2img.php?eq=x%20%5Cin%20%5B-1%2C%201%5D&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0)  |
| ![equation](http://www.sciweavers.org/tex2img.php?eq=f_2%20%3D%20%5Csin%7Bx%7D%20%2B%20%5Csin%7B%28x%20%2B%20x%5E%7B2%7D%29%20%7D&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0)| ![equation](http://www.sciweavers.org/tex2img.php?eq=x%20%5Cin%20%5B-1%2C%201%5D&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0)|
| ![equation](http://www.sciweavers.org/tex2img.php?eq=f_3%20%3D%202.0%20-%20%282.1%20%28%5Ccos%7B%289.8%20%2A%20x_1%29%7D%20%2A%20%5Csin%7B%281.3%20%2A%20x_2%29%7D&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0) | ![equation](http://www.sciweavers.org/tex2img.php?eq=x%20%5Cin%20%5B-50%2C%2050%5D&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0) |
| ![](f4.jpg) | ![equation](http://www.sciweavers.org/tex2img.php?eq=f_4%20%3D%20%5Cfrac%7B10%7D%7B5%20%2B%20%5Csum_%7Bi%3D1%7D%5E%7B5%7D%20%28x_i%20-%203%29%5E%7B2%7D%7D&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0) | 
