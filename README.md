<div align="center">
  <img src="NGC1097.png" alt="NGC 1097" width="600"/>
  <p><em>Photograph I took during my time as an operator of the 2.15‑meter telescope at CASLEO.</em></p>
</div>

<div align="center">

# Welcome!

## Nicolás Ottero

## Data Scientist | Data Analyst | Data Engineer | Astronomy Research

</div>

- I studied Data Science at [Instituto Data Science Argentina](https://institutodatascience.org/) and Astronomy at [UNC](https://www.unc.edu.ar/)
- I work with **astronomical data**, pipelines, statistical analysis, and machine learning  
- I'm interested in collaborating on **data science** projects applied to astrophysics

---
### 🛠  Tech Stack and Tools

![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnubash&logoColor=white) ![AstroPy](https://img.shields.io/badge/AstroPy-ffcc00?style=for-the-badge&logo=astropy&logoColor=black) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) ![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=black) ![Matplotlib](https://img.shields.io/badge/Matplotlib-223A5E?style=for-the-badge&logo=matplotlib&logoColor=white) ![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=seaborn&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white) ![spaCy](https://img.shields.io/badge/spaCy-09A3D5?style=for-the-badge&logo=spacy&logoColor=white) ![NLTK](https://img.shields.io/badge/NLTK-4B8BBE?style=for-the-badge&logo=python&logoColor=white) ![Visual Studio](https://img.shields.io/badge/Visual%20Studio-5C2D91?style=for-the-badge&logo=visualstudio&logoColor=white) ![VSCode](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white) ![SSH](https://img.shields.io/badge/SSH-000000?style=for-the-badge&logo=openssh&logoColor=white)

**Machine Learning Models**: Random Forest · Gradient Boosting · LSTM · Spline Interpolation · Time Series Forecasting

**Tasks**: Text classification · Named Entity Recognition · Tokenization · Custom pipelines

---

### 📫 Contact Me

[![Gmail](https://img.shields.io/badge/Gmail-nicolas.ottero@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nicolas.ottero@gmail.com)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Nicolás%20Ottero-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nicolás-ottero-68b8182b8/)

[![Kaggle](https://img.shields.io/badge/Kaggle-nicolsottero-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/nicolsottero)

---

<div align="center">
  
# Investigación en curso

# Carbon Stars Lightcurve Modeling

</div>

Desarrollé un sistema completo para el análisis automatizado de estrellas de carbono a partir de datos fotométricos, integrando catálogos astronómicos, mediciones en banda Ks y modelos predictivos. El flujo de trabajo abarca desde la identificación precisa de las fuentes hasta la reconstrucción e interpolación de curvas de luz, incorporando técnicas de aprendizaje automático supervisado (Random Forest) y redes neuronales LSTM para predecir su evolución futura. El proyecto está documentado en cuatro notebooks en Kaggle, cada una dedicada a una etapa específica del proceso. Esta solución puede adaptarse a otros tipos de estrellas variables y contribuye a automatizar tareas que tradicionalmente se realizan de forma manual en astronomía.

Este trabajo fue publicado en la revista científica de la Asociación Argentina de Astronomía (AAA) en colaboración con el PhD. David Merlo. 

Acceso al código completo y a las explicaciones detalladas a través de notebooks en Kaggle:

1. [Catalog-Based Positional Matching of Carbon Stars](https://www.kaggle.com/code/nicolsottero/catalog-based-positional-matching-of-carbon-stars)
2. [Ks Band Photometric Extraction for Carbon Stars](https://www.kaggle.com/code/nicolsottero/ks-band-photometric-extraction-for-carbon-star)
3. [Modeling Carbon Star Light Curves with ML](https://www.kaggle.com/code/nicolsottero/modeling-carbon-star-light-curves-with-ml)
4. [Appendix: Modeling Carbon Star Variability](https://www.kaggle.com/code/nicolsottero/appendix-modeling-carbon-star-variability)

---

Acceso a la publicación revisada por pares de la Asociación Argentina de Astronomía (AAA):

* 📄 [Artículo publicado](https://drive.google.com/file/d/1wQlFtGvqs0r029vZ8lFyNmbOz6qsI1Gd/view)
* 📚 [Accede al volumen completo de la AAA para ver el artículo en su contexto. (p.109)](http://astronomiaargentina.org.ar/uploads/docs/baaa66.pdf)

---

La investigación avanza actualmente hacia una automatización completa mediante una interfaz basada en Streamlit y Docker, lo que permite su reproducibilidad y uso remoto. Se ha desarrollado una aplicación modular que procesa todo el flujo de trabajo, desde el procesamiento de catálogos hasta el modelado de curvas de luz, sin intervención manual. Actualmente estamos trabajando en mejorar el rendimiento predictivo reemplazando el modelo Random Forest por métodos de Gradient Boosting (como XGBoost y LightGBM), junto con una mejor ingeniería de características y validación sensible al tiempo. El Observatorio Astronómico de Córdoba (OAC) apoya el proyecto alojando el sistema, lo que facilita su acceso para pruebas continuas y uso científico.

---
