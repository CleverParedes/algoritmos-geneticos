# Algoritmos Genéticos en Aprendizaje Automático

Este repositorio contiene implementaciones de **algoritmos genéticos** aplicados a diferentes problemas de aprendizaje automático, incluyendo:

- Selección de características
- Optimización de hiperparámetros
- Neuroevolución de redes neuronales

---

## Ejemplos Implementados

### Ejemplo A: Selección de Características con Algoritmo Genético
**Objetivo**: Encontrar el subconjunto óptimo de características para clasificación.

- **Dataset**: Breast Cancer (`scikit-learn`)
- **Algoritmo**: Random Forest con validación cruzada
- **Características**:
  - Representación binaria de características seleccionadas
  - Operadores genéticos:
    - Selección por torneo
    - Cruce de un punto
    - Mutación bit-flip
  - Visualización de:
    - Evolución del fitness
    - Características seleccionadas

---

### Ejemplo B: Optimización Multi-objetivo con GA
**Aplicaciones**:
- Selección de características (vector binario)
- Optimización de hiperparámetros para:
  - `RandomForest`
  - `SVM` (`C` y `gamma`)
- Neuroevolución para arquitecturas de `MLP`

**Dataset**: Breast Cancer (normalizado)  
**Métricas**: Precisión con validación cruzada  
**Visualización**: Evolución del fitness por método

---

### Ejemplo C: Neuroevolución para Redes Neuronales
**Objetivo**: Evolucionar arquitecturas de redes neuronales

- **Enfoque**: Optimización de capas ocultas y funciones de activación
- **Modelo**: Red neuronal con `TensorFlow`/`Keras`
- **Parámetros evolucionados**:
  - Número de neuronas en capas ocultas
  - Funciones de activación
- **Evaluación**: Precisión sobre el conjunto de prueba

---

## Requisitos

Instala las dependencias con:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn tensorflow

## Uso 

Cada ejemplo puede ejecutarse de forma independiente:
