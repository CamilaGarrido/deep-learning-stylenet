# StyleNet: Clasificador Inteligente de Moda 

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)

## Descripción del Proyecto
StyleNet es un prototipo de visión computacional diseñado para automatizar la categorización de inventario en una plataforma de e-commerce. Utilizando el dataset **Fashion-MNIST**, este proyecto implementa y compara Redes Neuronales Densas (MLP) y Redes Neuronales Convolucionales (CNN) para identificar 10 categorías de prendas de vestir.

El objetivo principal es transitar de un etiquetado manual a un sistema de **categorización automatizada**, optimizando la eficiencia operativa y reduciendo el error humano.

## Arquitectura y Metodología
El desarrollo se dividió en etapas evolutivas de aprendizaje profundo:

1. **Clasificación Binaria:** Validación inicial del flujo de datos con un modelo simple (Camisetas vs. Pantalones).
2. **Red Densa (ANN):** Implementación de una arquitectura MLP con capas de regularización para establecer una línea base.
3. **Red Convolucional (CNN):** Diseño de un modelo avanzado con capas `Conv2D` y `MaxPooling2D` para capturar jerarquías espaciales y texturas.

## Resultados Destacados
* **Precisión Final (CNN):** 90.3% en el conjunto de prueba.
* **Regularización:** Se utilizó **Dropout (0.5)** para mitigar el overfitting, logrando una excelente capacidad de generalización entre entrenamiento y validación.
* **Optimización:** Uso de **Adam** y **Sparse Categorical Crossentropy** para una convergencia rápida y estable.

### Matriz de Confusión
La evaluación mediante la matriz de confusión permitió identificar que el modelo es altamente preciso en calzado (*Sneakers*, *Boots*), mientras que presenta áreas de mejora en prendas con siluetas similares como *Shirts* y *Coats*.



## Tecnologías Utilizadas
* **Lenguaje:** Python 3.x
* **Frameworks:** TensorFlow / Keras
* **Análisis de Datos:** Pandas, NumPy
* **Visualización:** Matplotlib, Seaborn
* **Métricas:** Scikit-learn (Confusion Matrix, Classification Report)

##  Instalación y Uso
1. Clonar el repositorio:
   ```bash
   git clone [https://github.com/CamilaGarrido/deep-learning-stylenet.git](https://github.com/CamilaGarrido/deep-learning-stylenet.git)
