# Descripción del Dataset Titanic (train.csv)

El archivo `titanic.csv` es el conjunto de datos de entrenamiento clásico del desafío de Kaggle "Titanic: Machine Learning from Disaster". Contiene información sobre **891 pasajeros** del Titanic, incluyendo si sobrevivieron o no, lo que lo hace ideal para entrenar modelos de aprendizaje automático.

## Objetivo del Dataset

Predecir qué pasajeros sobrevivieron al hundimiento del Titanic basándose en sus atributos personales y de viaje (como clase, sexo, edad, etc.).

## Diccionario de Variables

El dataset incluye las siguientes 12 columnas:

| Variable | Descripción |
|----------|-------------|
| **PassengerId** | Identificador único para cada pasajero (entero) |
| **Survived** | Supervivencia (0 = No, 1 = Sí). **Esta es la variable objetivo** |
| **Pclass** | Clase del boleto (1 = 1ª clase, 2 = 2ª clase, 3 = 3ª clase) |
| **Name** | Nombre completo del pasajero |
| **Sex** | Sexo del pasajero (male/female) |
| **Age** | Edad en años (dato faltante en algunos casos) |
| **SibSp** | Número de hermanos/cónyuges a bordo |
| **Parch** | Número de padres/hijos a bordo |
| **Ticket** | Número del boleto |
| **Fare** | Tarifa del pasaje (valor en libras esterlinas) |
| **Cabin** | Número de cabina (muchos datos faltantes) |
| **Embarked** | Puerto de embarque (C = Cherburgo, Q = Queenstown, S = Southampton) |

## Resumen Estadístico Rápido

Basado en las primeras filas de los datos:

- **Rango de edades**: Desde bebés (menos de 1 año) hasta pasajeros mayores (hasta 80 años)
- **Tarifas**: Desde £0 hasta más de £500
- **Familias a bordo**: Algunos pasajeros viajaban solos, otros con hasta 5 familiares (SibSp) o 5 padres/hijos (Parch)
- **Clase más común**: 3ª clase
- **Puerto más común**: Southampton (S)

## Características Particulares

1. **Datos Faltantes**: Las columnas `Age`, `Cabin` y `Embarked` tienen valores vacíos que necesitan ser procesados.
2. **Nombres**: La columna `Name` contiene títulos (Mr, Mrs, Miss, Master, etc.) que pueden extraerse como características útiles.
3. **Grupos Familiares**: Las columnas `SibSp` y `Parch` permiten crear nuevas variables como `FamilySize`.
4. **Sin Cabina**: Muchos registros no tienen número de cabina (especialmente en 3ª clase).

## Uso Típico

Este dataset es ampliamente utilizado para:
- **Clasificación binaria** (predecir "Sobrevivió" o "No sobrevivió")
- **Práctica de limpieza de datos** (manejar valores nulos)
- **Ingeniería de características** (crear nuevas variables a partir de nombres, boletos, etc.)
- **Comparar algoritmos** (Regresión Logística, Random Forest, XGBoost, etc.)

## Limitaciones

- Es solo el **conjunto de entrenamiento** (891 registros). El conjunto de prueba completo tiene 418 pasajeros adicionales.
- No incluye información de la tripulación (solo pasajeros).
- Algunos datos como `Cabin` son demasiado escasos para usar directamente en modelos simples.
