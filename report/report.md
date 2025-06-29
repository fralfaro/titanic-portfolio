# 🚢 Portafolio de Ciencia de Datos – Proyecto Titanic

* **Nombre:** Francisco Alfaro
* **Curso:** Fundamentos de Ciencia de Datos
* **Fecha:** Junio 2025
* **Repositorio GitHub:** [https://github.com/fralfaro/titanic-portfolio](https://github.com/fralfaro/titanic-portfolio)



## 📌 Resumen Ejecutivo

Este portafolio documenta el análisis completo del dataset del Titanic, uno de los conjuntos de datos más utilizados para introducir conceptos clave de ciencia de datos. El objetivo fue predecir la supervivencia de los pasajeros aplicando técnicas de limpieza de datos, visualización y aprendizaje automático. El proyecto muestra competencias en análisis exploratorio, manipulación de datos con Python, visualización con seaborn y modelado con scikit-learn.



## 📊 Proyecto: Predicción de Supervivencia en el Titanic

### 🔍 Descripción del problema

El objetivo es predecir si un pasajero sobrevivió al hundimiento del Titanic en base a información como clase, edad, sexo, número de familiares a bordo, entre otros.

* **Dataset fuente:** [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic)



### ⚙️ Metodología

1. **Exploración de datos**

   * Inspección de estructura (`df.info()`) y estadísticas (`df.describe()`).
   * Identificación de valores nulos y outliers.

2. **Limpieza y transformación**

   * Imputación de variables faltantes como `Age` y `Embarked`.
   * Eliminación de columnas irrelevantes como `Cabin` y `Ticket`.
   * Codificación de variables categóricas (`Sex`, `Embarked`).

3. **Visualización**

   * Análisis de supervivencia según variables claves con `seaborn` y `matplotlib`.

4. **Modelado predictivo**

   * División del dataset (entrenamiento y validación).
   * Entrenamiento con `LogisticRegression` y `RandomForestClassifier`.
   * Evaluación de modelos con métricas como accuracy, matriz de confusión y AUC.



### 📈 Resultados

* **Modelo más preciso:** Random Forest
* **Precisión obtenida:** 83%
* **Variables más relevantes:** `Sex`, `Pclass`, `Fare`, `Age`, `SibSp`

Ejemplo de código usado:

```python
from sklearn.ensemble import RandomForestClassifier
model = RandomForestClassifier(random_state=42)
model.fit(X_train, y_train)
print(model.score(X_test, y_test))  # Output: 0.83
```



### 🧠 Reflexión personal

Este proyecto me permitió aplicar todo el ciclo de trabajo en ciencia de datos, desde la limpieza hasta el modelado. Aprendí a seleccionar variables relevantes, probar diferentes algoritmos y comunicar resultados con claridad. Me interesa seguir profundizando en el uso de pipelines y validación cruzada.



## 🛠️ Habilidades Técnicas

* **Lenguajes:** Python, SQL
* **Librerías:** pandas, numpy, seaborn, matplotlib, scikit-learn, xgboost
* **Entornos:** Jupyter, Google Colab, GitHub



## 🔗 Recursos y enlaces

* [🔗 Repositorio en GitHub](https://github.com/fralfaro/titanic-data-science-portfolio)
* [📘 Tutorial de Kaggle](https://www.kaggle.com/code/startupsci/titanic-data-science-solutions)
* [🧪 Competencia original en Kaggle](https://www.kaggle.com/competitions/titanic)
* [📚 Documentación de scikit-learn](https://scikit-learn.org/stable/)

