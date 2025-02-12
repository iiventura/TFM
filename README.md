# 🎓 Trabajo de Fin de Máster

## 🔍 Exploración de patrones en series temporales de datos inerciales usando técnicas de segmentación no supervisada

### 🏫 Universidad Nacional de Educación a Distancia (UNED)

Este repositorio contiene notebooks 📂 dedicados al análisis, preprocesamiento y experimentación con datos, aplicando modelos de aprendizaje no supervisado. Se centra en dos conjuntos de datos principales: **Bokken** ⚔️ y **Shikko** 🥋, y explora métodos de clustering como K-Means y K-Medoids.

## 📌 Contexto

Este trabajo está asociado al **Trabajo de Fin de Máster (TFM) "Exploración de patrones en series temporales de datos inerciales usando técnicas de segmentación no supervisada"**, realizado en la Universidad Nacional de Educación a Distancia (UNED). El objetivo principal del estudio es analizar habilidades motoras en Aikido 🥋 utilizando técnicas de segmentación no supervisada en datos inerciales obtenidos de sensores.

El estudio se basa en investigaciones previas que emplearon métodos supervisados y busca validar estos resultados desde un enfoque exploratorio. Se analiza si la segmentación no supervisada puede identificar patrones y estructuras significativas en series temporales sin necesidad de etiquetas predefinidas.

Los datos provienen de dos conjuntos: **Bokken** ⚔️ (golpes con espada) y **Shikko** 🥋 (desplazamientos de rodillas). Se realiza una extracción de características tanto de los participantes como de las series temporales utilizando descriptores estadísticos, temporales y espectrales. Posteriormente, se aplican modelos de clustering para analizar la organización de los datos.

## 📂 Contenido

### 1. 📊 Análisis Datasets.ipynb

Este notebook está enfocado en:

- **Carga y preprocesamiento de datos:**
  - 📥 Importación de librerías esenciales como `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn` y `tsfel`.
  - 🔍 Análisis exploratorio de los datasets `shikko_dataset.csv` y `bokken_dataset.csv`.
  - ⚙️ Manejo de valores nulos y transformaciones de las features.
  - 📈 Extracción de características de series temporales con `TSFEL`.
  - 📝 Preparación de los datos y generación de archivos CSV (`bokken_data_selected_features.csv` y `shikko_data_selected_features.csv`) para su uso en los modelos del siguiente notebook.

### 2. 🤖 `ModelosNoSupervisados.ipynb`

Este notebook se centra en:

- **Carga de datasets preprocesados** (`bokken_data_selected_features.csv` y `shikko_data_selected_features.csv`).
- **Aplicación de modelos de clustering**:
  - 🏷️ Implementación de **K-Means** y **K-Medoids** para segmentar los datos.
  - 📊 Evaluación y comparación de los resultados obtenidos.
  - 📌 Gráficos para visualización de los clusters formados.

## 🛠️ Requisitos

Este proyecto utiliza **Python 3.10** 🐍 y proporciona un archivo `requirements.txt` 📜 con las librerías instaladas en el entorno. Para ejecutar los notebooks, instala las dependencias con:

```bash
pip install -r requirements.txt
```

## 🚀 Uso

1. 🖥️ Clona el repositorio:
   ```bash
   git clone <URL_DEL_REPOSITORIO>
   cd <NOMBRE_DEL_REPOSITORIO>
   ```
2. ⚡ Asegúrate de tener un entorno virtual activo (opcional pero recomendado):
   ```bash
   python -m venv venv
   source venv/bin/activate  # En Linux/macOS
   venv\Scripts\activate     # En Windows
   ```
3. 📦 Instala las dependencias y abre los notebooks en Jupyter:
   ```bash
   pip install -r requirements.txt
   jupyter notebook
   ```

## 📬 Contacto

Si tienes preguntas o sugerencias, por favor abre un issue en el repositorio. 😊
```

Este contenido está formateado en Markdown y listo para ser utilizado en GitHub o cualquier otro repositorio compatible. 🚀
