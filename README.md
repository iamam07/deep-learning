# Proyecto Final de la Materia Deep Learning

Este proyecto tiene como objetivo principal desarrollar, entrenar y evaluar modelos de aprendizaje profundo para la clasificación de imágenes utilizando el conjunto de datos **KMNIST**.

## Flujo de Trabajo

1. **Preparación de los datos**:
   - Transformaciones, normalización y división en conjuntos de entrenamiento, validación y prueba.

2. **Implementación de modelos**:
   - **Baseline MLP**: Un perceptrón multicapa básico para establecer un punto de comparación.
   - **CNN Personalizada**: Una red neuronal convolucional diseñada específicamente para este problema.
   - **ResNet18**: Un modelo preentrenado adaptado al conjunto de datos KMNIST.

3. **Entrenamiento y evaluación**:
   - Uso de técnicas como Early Stopping, Checkpointing y ajuste de hiperparámetros para optimizar el rendimiento.

4. **Visualización de resultados**:
   - Comparación de métricas como Accuracy y F1-Score, además de análisis de predicciones y matrices de confusión.

5. **Análisis interactivo**:
   - Gráficos dinámicos para explorar el rendimiento de los modelos a lo largo de las épocas.

## Modelos Implementados

### Baseline MLP
- Arquitectura básica con 100 neuronas en una única capa oculta.
- Optimización con SGD y técnicas de regularización.

### CNN Personalizada
- Tres capas convolucionales con Batch Normalization y MaxPooling.
- Capas densas con Dropout para reducir el sobreajuste.

### ResNet18
- Modelo preentrenado adaptado para imágenes en escala de grises.
- Modificaciones en la primera y última capa para ajustarse al conjunto de datos KMNIST.

## Resultados
- Métricas evaluadas: **Accuracy** y **F1-Score**.
- Comparación de los modelos en términos de rendimiento y generalización.

## Requisitos
- Python 3.11.9
- Librerías principales: PyTorch, PyTorch Lightning, torchvision, pandas, matplotlib, plotly.

## Ejecución
1. Instalar las dependencias:
   ```bash
   pip install -r requirements.txt

## Contribuciones
Si deseas contribuir a este proyecto, por favor sigue estos pasos:
1. Realiza un fork del repositorio.
2. Crea una rama para tu funcionalidad (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios y haz un commit (`git commit -m 'Añadir nueva funcionalidad'`).
4. Haz un push a la rama (`git push origin feature/nueva-funcionalidad`).
5. Abre un Pull Request.

## Licencia
Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.