# Melanoma Detection
* **Curso:** INF658-COMPUTACIÓN GRÁFICA
* **Alumno:** José Guillermo Balbuena Galván

El repositorio contiene el proyecto realizado como parte del curso INF658-Computación Gráfica ciclo 2021-1. Elproyectoconsiste en la detección de Melanoma en imagenes mediante la utilización de Redes Convolucionales (CNN). En el repositorio se encontrara distintos modelos utilizados para la tarea asignada, la métrica utilizada para la evaluación final el el ROC-AUC. Se entrenaron tres (03) modelos:

* VGG16
* InceptionV3
* miniXception

Luego se pondero las probabilidades de los tres (03) modelos, dos mejores resultados para el AUC-ROC:

1. La primera ponderación, con la que se obtuvo 0.84071 en la metrica AUC-ROC

> Prob<sub>total</sub> = (2.4 x Prob<sub>VGG16</sub> + 0.4 x Prob<sub>miniXception</sub> + 0.2 x Prob<sub>InceptionV3</sub>)/3

2. La segunda ponderación, con la que se obtuvo 0.84136 en la metrica AUC-ROC

> Prob<sub>total</sub> = (2.4 x Prob<sub>VGG16</sub> + 0.4 x Prob<sub>miniXception</sub> + 0.2 x Prob<sub>InceptionV3</sub>)/3
