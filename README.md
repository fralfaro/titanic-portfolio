
# 🚢 Titanic - Data Science Portfolio

Este repositorio contiene un análisis completo del dataset del Titanic, utilizado como parte del portafolio para el curso **Fundamentos de Ciencia de Datos**.

El objetivo es predecir la supervivencia de los pasajeros utilizando técnicas de análisis exploratorio, limpieza de datos, visualización y modelos de machine learning. Este proyecto refleja habilidades clave en Python, visualización de datos, y comunicación de resultados.



## 📁 Estructura del Proyecto

```

titanic-data-science-portfolio/
│
├── data/
│   ├── train.csv
│   └── test.csv
│
├── notebooks/
│   └── main.ipynb
│
├── report/
│   └── report.md
|
├── .gitignore
├── LICENSE
├── README.md
└── requirements.txt

````



## 🔍 Contenido del Proyecto

### 📊 Análisis Exploratorio
- Distribución de variables
- Análisis de supervivencia según clase, edad y sexo
- Visualizaciones con `seaborn` y `matplotlib`

### 🧹 Limpieza y Preparación
- Imputación de valores nulos
- Ingeniería de características
- Codificación de variables categóricas

### 🤖 Modelado
- Modelos: Regresión Logística, Random Forest
- Evaluación con Accuracy, Confusion Matrix, ROC-AUC
- Selección del mejor modelo

### 📈 Resultados
- Precisión final: **83%**
- Variables más influyentes: `Sex`, `Pclass`, `Fare`, `Age`, `SibSp`



## 💡 Reflexión Personal

Este proyecto me ayudó a aplicar paso a paso el flujo de trabajo en ciencia de datos, desde entender el problema hasta comunicar los hallazgos. También reforzó mi habilidad para trabajar con datos reales y entregar resultados reproducibles.



## 🛠️ Tecnologías Utilizadas

- Python 3.10
- pandas, numpy, matplotlib, seaborn
- scikit-learn
- Jupyter / Google Colab



## 📚 Recursos de Referencia

- [Titanic - Kaggle Competition](https://www.kaggle.com/competitions/titanic)
- [Kaggle Tutorial: Data Science Solutions](https://www.kaggle.com/code/startupsci/titanic-data-science-solutions)
- [Documentación de scikit-learn](https://scikit-learn.org/stable/)



## 🚀 Cómo Ejecutar

1. Clona este repositorio:

    ```bash
    git clone https://github.com/tu_usuario/titanic-data-science-portfolio.git
    cd titanic-data-science-portfolio
    ````

2. Instala las dependencias:

     ```bash
     pip install -r requirements.txt
     ```

3. Abre los notebooks en Jupyter o Google Colab.


