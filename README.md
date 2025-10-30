# Ev2IN

# Trabajo N.º 2 — Caso de investigación N.º 2
## Título: Uso de regresión, clasificación y agrupamiento para responder hipótesis de BI en Fuga de Clientes

**Autor:** Jorge Garrido
**Fecha:** 30 de octubre
**Curso:** Business Intelligence (BI)

---

## Resumen del Proyecto

Este trabajo aborda el problema de la fuga de clientes (Churn) en el sector de las telecomunicaciones, utilizando el dataset "Telco Customer Churn" de Kaggle. El objetivo es validar la hipótesis de BI de que la antigüedad (`tenure`) y el tipo de contrato (`Contract`) son determinantes clave del valor económico (`TotalCharges`) y el riesgo de fuga (`Churn`) del cliente. Para ello, se implementan y evalúan tres técnicas de Machine Learning: (1) Regresión Lineal Múltiple, (2) Random Forest Classifier y (3) K-Means Clustering, proporcionando conclusiones accionables para el negocio.

## Instrucciones de Ejecución

Para replicar este análisis, sigue los siguientes pasos:

1.  **Clonar o descargar el repositorio:**
    Obtén los archivos en tu máquina local.

2.  **Crear un entorno virtual:**
    Se recomienda usar `venv` para aislar las dependencias del proyecto.
    ```bash
    python -m venv venv
    ```

3.  **Activar el entorno virtual:**
    * En Windows (CMD/PowerShell):
        ```bash
        .\venv\Scripts\activate
        ```
    * En macOS/Linux:
        ```bash
        source venv/bin/activate
        ```

4.  **Instalar las dependencias:**
    Instala las librerías necesarias. (Puedes crear un `requirements.txt` con la lista de abajo o instalarlas manualmente).
    ```bash
    pip install pandas numpy scikit-learn matplotlib seaborn jupyter
    ```

5.  **Iniciar Jupyter:**
    Abre la interfaz de Jupyter.
    ```bash
    jupyter notebook
    ```
    O (recomendado):
    ```bash
    jupyter lab
    ```

6.  **Ejecutar el Notebook:**
    Abre el archivo `BI_T2_JorgeGarrido.ipynb` (o `Jorgegarrido.ipynb`) y ejecuta las celdas en orden secuencial.

## Dependencias

El proyecto fue desarrollado utilizando **Python 3.9**. Las librerías principales son:

* `pandas`
* `numpy`
* `scikit-learn`
* `matplotlib`
* `seaborn`
* `jupyter`

## Dataset

* **Nombre:** Telco Customer Churn
* **Fuente:** Kaggle
* **Licencia:** CC0: Public Domain
* **Enlace:** [https://www.kaggle.com/datasets/blastchar/telco-customer-churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
