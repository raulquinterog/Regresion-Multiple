#  Regresión Lineal Múltiple - Análisis de Datos de la NASA

## **Descargar archivos del proyecto**
 Puedes descargar los archivos desde este repositorio:

-  **[Regresion_lineal_multiple.ipynb](A1_3_Regresión_lineal_múltiple.ipynb)**
-  **[NASA.csv](A1.3_NASA.csv)**



Este proyecto realiza una **Regresión Lineal Múltiple** para predecir la variable `presion` (nivel de presión sonora) con base en otras cinco variables aerodinámicas extraídas de una base de datos de la **NASA**.

 **Objetivo:**  
Analizar los datos y construir un modelo de regresión para identificar qué variables tienen un impacto significativo en la predicción de `presion`.

---

## **Estructura del Proyecto**
El proyecto está organizado en un **Jupyter Notebook**, donde cada sección aborda un paso clave:

1. **Cargar y visualizar los datos**  
   - Se importa la base de datos `A1.3 NASA.csv`.  
   - Se revisan sus dimensiones y primeras filas.  

2. **Dividir los datos en entrenamiento y prueba**  
   - Se separan los datos en 70% para **entrenamiento** y 30% para **prueba**.  

3. **Ajustar el modelo de regresión lineal múltiple**  
   - Se usan `statsmodels` para entrenar el modelo.  
   - Se calculan los coeficientes de las variables predictoras.  

4. **Interpretación de resultados**  
   - Se identifican **las variables más importantes** según sus coeficientes y p-values.  

5. **Evaluación del modelo**  
   - Se calculan métricas de error: **RSE (Error Residual Estándar)** y **R² (Coeficiente de Determinación)**.  
   - Se comparan los resultados en entrenamiento y prueba.  

6. **Visualización del ajuste del modelo**  
   - Se genera una **gráfica de dispersión** que compara los valores reales vs. predichos.  
   - Se comenta sobre la calidad del modelo basado en la gráfica
