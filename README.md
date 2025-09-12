# 🚀 Proyecto Final de Machine Learning

![Banner](./banner.png)

Bienvenido a nuestro **proyecto final** de Machine Learning.  
Este repositorio contiene tanto el código fuente como la documentación en forma de **Jupyter Book**, desplegada en GitHub Pages:  

👉 **Acceso directo al libro**  
[![Ver Jupyter Book](https://img.shields.io/badge/📖%20Ver%20Jupyter%20Book-blueviolet)](https://nicoplayz58.github.io/ml-project/)

---

## 🌟 Descripción
En este proyecto abordamos **dos problemas principales de Machine Learning**, aplicando técnicas de análisis exploratorio, preprocesamiento, selección de características, modelado y evaluación de resultados.  

Los casos de estudio son:  

1. **Home Credit Default Risk (Kaggle)**  
2. **Análisis de Series de Tiempo con Bitcoin**  

---

## 🎯 Problemas que resolvemos

### 1. 🏦 Home Credit Default Risk
El acceso al crédito es esencial para el desarrollo financiero, pero evaluar la solvencia de los solicitantes es un gran desafío.  
La competencia **Home Credit Default Risk** de Kaggle provee un dataset con información de clientes de Home Credit, una entidad financiera que ofrece préstamos a personas con historial crediticio limitado.  

**Objetivo del análisis**:  
- Comprender la estructura de los datos (variables, valores faltantes, outliers).  
- Explorar la distribución de características como edad, ingresos y estado laboral.  
- Analizar la relación de la variable objetivo **TARGET** (cumple / incumple pagos) con otras variables.  
- Estudiar correlaciones y patrones que expliquen el riesgo de incumplimiento.  
- Visualizar tendencias mediante gráficos y estadísticas descriptivas.  

Este problema se aborda como un **problema de clasificación supervisada** para identificar a los clientes con mayor probabilidad de incumplir sus obligaciones crediticias.  

---

### 2. ₿ Análisis de Series de Tiempo de Bitcoin
Bitcoin es una criptomoneda descentralizada con alta volatilidad, cuyo precio varía de forma constante por factores de oferta/demanda, noticias económicas, regulación y dinámicas del mercado.  

El dataset usado contiene información histórica del **mercado de Bitcoin** en distintos niveles de granularidad (15 min, 1h, 4h, 1d), incluyendo:  
- Precio de apertura (Open), cierre (Close), máximo (High) y mínimo (Low).  
- Volumen total de transacciones.  
- Número de trades.  
- Retornos porcentuales y volatilidad.  

**Objetivo del análisis**:  
- Detectar patrones temporales (tendencia, ciclos, estacionalidad).  
- Identificar anomalías y cambios bruscos en el precio.  
- Evaluar la volatilidad y su impacto en el mercado.  
- Preparar los datos para modelos predictivos de series de tiempo.  

Este problema se aborda desde un **enfoque de análisis exploratorio y pronóstico temporal**, clave para inversionistas y analistas financieros.  

---

## 📂 Estructura del Repositorio
- `notebooks/` → Jupyter Notebooks con el código y experimentos.  
- `data/` → Datos utilizados (si son públicos o de prueba).  
- `scripts/` → Código modular en Python para el pipeline de análisis.  
- `docs/` → Jupyter Book compilado.  
- `_config.yml` y `_toc.yml` → Configuración del libro.  
- `README.md` → Este archivo de presentación.  

---

## 🚀 Cómo visualizar el Jupyter Book
El libro completo está desplegado en GitHub Pages. Puedes acceder aquí:  

👉 **[https://nicoplayz58.github.io/ml-project/](https://nicoplayz58.github.io/ml-project/)**  

Para verlo localmente:  

```bash
# Clona el repositorio
git clone https://github.com/nicoplayz58/ml-project.git
cd ml-project

# Construye el Jupyter Book
jupyter-book build .

# Visualiza el resultado en docs/
open _build/html/index.html
