# 🎵 Analizador de Datos de Spotify

Este proyecto realiza un **análisis exploratorio** de un dataset de canciones de Spotify, transformando datos en **insights visuales** y métricas interesantes. El objetivo es practicar **Python, Pandas, Matplotlib y buenas prácticas de Git**, creando un portafolio profesional.

---

## 🗂️ Contenido del proyecto

- `notebooks/01_exploracion_spotify.ipynb`: Notebook principal donde se carga, explora y analiza el dataset de Spotify.
- `data/raw/`: Contiene los datos originales (CSV descargado de Kaggle).
- `data/processed/`: Carpeta destinada a guardar datos limpios o transformados.
- `src/`: Carpeta para scripts auxiliares si se requieren en el futuro.

---

## 📦 Dataset

- Fuente: Kaggle (en formato CSV).  
- Columnas principales:  
  - `artist`: Nombre del artista  
  - `song`: Nombre de la canción  
  - `duration_ms`: Duración en milisegundos  
  - `explicit`: Si la canción tiene contenido explícito  
  - `year`: Año de lanzamiento  
  - `popularity`: Popularidad de la canción  
  - `danceability`, `energy`, `valence`, `tempo`: Métricas de audio  
  - `genre`: Género de la canción

---

## 🎯 Objetivos del análisis

1. 🔍 **Exploración inicial:** revisar la estructura y dimensiones del dataset (`df.head()`, `df.shape`, `df.info()`).  
2. 🧹 **Limpieza y transformación de datos:** preparación para análisis más profundos.  
3. 📊 **Visualizaciones:** gráficas para entender tendencias de popularidad, baile, energía y valencia de las canciones.  
4. 🚀 **Extensiones futuras:**  
   - Guardar datos procesados en SQL  
   - Crear API simple con Flask o FastAPI para exponer métricas  
   - Dashboards interactivos con Power BI o Looker Studio

---

## 🛠️ Tecnologías y herramientas utilizadas

- Python 3.13  
- Pandas, Matplotlib, Numpy  
- Jupyter Notebook (VS Code)  
- Git y GitHub  
- Terminales UNIX

---

## ▶️ Cómo ejecutar

1. Clonar el repositorio:
```bash
git clone https://github.com/andresmatesanz/analizador-spotify-json.git
```

2. Crear y activar un entorno virtual (opcional pero recomendado):
```bash
conda create -n mienv python=3.13
conda activate mienv
```

3. Instalar dependencias:
```bash
pip install pandas matplotlib jupyter
```
4. Abrir el notebook y ejecutar celda por celda:
```bash
jupyter notebook notebooks/01_exploracion_spotify.ipynb
```

---

## 👤 Autor
**Autor:** Andrés Matesanz  
[LinkedIn](https://www.linkedin.com/in/andresmatesanz/) | [GitHub](https://github.com/andresmatesanz)
