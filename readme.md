![Visualizacion](banner.png)

# Trabajo Final de Visión por Computadora II - Especialización en Inteligencia Artificial (FIUBA)

**Autor:** Karen Raczkowski

En este repositorio se encuentra el trabajo final de la materia Visión por Computadora II de la Especialización en Inteligencia Artificial de la FIUBA.

### Descripción del proyecto:

- **Objetivo:** Identificar la raza de perros en imágenes.
- **Tipo de problema:** Clasificación multiclase.
- **Cantidad de clases:** 120 razas de perros, incluyendo 'Pekinese', 'Labrador', 'Bulldog', entre otras.
- **Dataset:** 20,580 imágenes, divididas en un 80% para entrenamiento y un 20% para test.
- **Arquitecturas de modelos utilizadas:** ResNet18, ResNet50, VGG19.
- **Transfer Learning:** Implementado utilizando el conjunto de datos IMAGENET.
- **Data Augmentation:** Técnicas como Horizontal Flip, Resized Crop y Normalize.

### Análisis y Resultados:

# Balance de clases: 

![Distribucion de razas en los datos](./Plots/distribucion.png)

![Razas](./Plots/razas.png)

# Resultados

### ResNet18

![ResNet18](./Plots/accuracy_resnet18.png)

![ResNet18](./Plots/precision_resnet18.png)

![ResNet18](./Plots/recall_resnet18.png)

### ResNet50

# Matrices de confusión

### ResNet18

![ResNet18](./Plots/confmatrix_resnet18.png)

### ResNet50




