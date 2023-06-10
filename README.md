# Proyecto Individual de Redes Neuronales

---
Maestría en Ciencias de Datos

Universidad de Sonora
<br> <br>
---

Curso propedéutico: Álgebra lineal y optimización

Profesor: Dr. Jesus Francisco Espinoza Fierro

Autor: Estephania Pivac Alcaraz

---

En este proyecto de redes neuronales, se investigaron los fundamentos teóricos y se desarrolló un esquema matemático detallado para una red neuronal de alimentación directa (feedforward). El objetivo principal fue mejorar la eficiencia y precisión del proceso de admisión en programas de posgrado.

Se utilizaron diversas variables relevantes para realizar las predicciones de probabilidad de aceptación en el programa de posgrado. Estas variables incluyeron los puntajes de los exámenes estandarizados GRE y TOEFL, la calificación de la universidad de origen, la fortaleza de la declaración de propósito (SOP), las cartas de recomendación (LOR), el GPA de pregrado (CGPA) y la experiencia en investigación.

La red neuronal propuesta consta de varias capas: una capa de entrada, dos capas densas ocultas y una capa de salida. La capa de entrada está compuesta por 7 neuronas que representan variables numéricas relevantes para la predicción de la probabilidad de admisión. Estas variables incluyen puntajes de exámenes estandarizados, calificaciones universitarias y otras métricas significativas. Cabe destacar que no se incluye su implementación.

Las capas densas ocultas son completamente conectadas, lo que significa que cada neurona en una capa está conectada a todas las neuronas en la capa siguiente. Estas capas utilizan la función de activación relu (Rectified Linear Unit) para introducir no linealidad en la red y capturar relaciones complejas entre las variables de entrada.

La capa de salida consta de una sola neurona que representa la probabilidad de ser aceptado en el programa de posgrado. Para obtener esta probabilidad, se utiliza la función de activación sigmoidal, que transforma el valor de salida en un rango entre 0 y 1, representando una probabilidad.

En resumen, el proyecto se enfocó en desarrollar una red neuronal feedforward con capas de entrada, capas densas ocultas y una capa de salida. Las funciones de activación relu y sigmoidal se utilizaron para mejorar la eficiencia y precisión en el proceso de admisión en programas de posgrado. El objetivo final fue utilizar datos relevantes de los solicitantes para realizar predicciones más precisas de la probabilidad de admisión.
