# 📊 Análisis de Viajes Compartidos y su Relación con el Clima en Chicago

## 📌 Descripción del Proyecto

Este proyecto analiza datos de viajes compartidos en la ciudad de **Chicago** para identificar patrones en el comportamiento de los pasajeros y evaluar el impacto de factores externos —como el clima— en la frecuencia de los viajes.

El análisis se realiza para **Zuber**, una nueva empresa de ride-sharing que busca comprender el mercado y el comportamiento de los usuarios a partir de datos de competidores.

El proyecto combina **consultas SQL, análisis exploratorio de datos y pruebas estadísticas** para evaluar cómo las condiciones climáticas pueden influir en la duración y frecuencia de los viajes.

---

## 🎯 Objetivos del Análisis

* Analizar datos de viajes de compañías de transporte en Chicago.
* Identificar las empresas con mayor número de viajes.
* Analizar los destinos más frecuentes de los pasajeros.
* Obtener datos climáticos de Chicago mediante **web scraping**.
* Evaluar si las condiciones climáticas influyen en la duración de los viajes.
* Validar los resultados mediante **pruebas estadísticas de hipótesis**.

---

## 📂 Dataset

El proyecto utiliza múltiples fuentes de datos relacionadas con viajes y condiciones climáticas.

### Datos de Viajes

Incluyen información sobre:

* compañías de transporte
* número de viajes
* puntos de recogida y destino
* duración de los viajes

### Datos Climáticos

Datos extraídos mediante **web scraping** desde:

https://practicum-content.s3.us-west-1.amazonaws.com/data-analyst-eng/moved_chicago_weather_2017.html

Estos datos incluyen información del clima en **Chicago durante noviembre de 2017**.

### Variables principales

* `company_name` — compañía de transporte
* `trips_amount` — número de viajes
* `pickup_location` — punto de recogida
* `dropoff_location` — destino
* `trip_duration` — duración del viaje
* `weather_condition` — condición climática

---

## 🔎 Metodología

### 1️⃣ Obtención de datos

* Consultas SQL para analizar datos de viajes
* Web scraping para extraer información climática

### 2️⃣ Preparación de datos

* Limpieza de datos
* Conversión de tipos de datos
* Verificación de valores faltantes
* Creación de variables relevantes

### 3️⃣ Análisis Exploratorio (EDA)

Se analizaron:

* compañías con mayor número de viajes
* destinos más populares
* distribución de duración de viajes
* comportamiento de los viajes según condiciones climáticas

Se utilizaron visualizaciones para entender las distribuciones y patrones.

### 4️⃣ Prueba de hipótesis

Se evaluó la siguiente hipótesis:

**Hipótesis nula (H₀):**
La duración promedio de los viajes en días lluviosos es igual a la duración en días sin lluvia.

**Hipótesis alternativa (H₁):**
La duración promedio de los viajes en días lluviosos es diferente.

Se utilizó una **prueba t para muestras independientes** con un nivel de significancia **α = 0.05**.

---

## 📈 Resultados Clave

* Se identificaron las compañías de transporte con mayor número de viajes en Chicago.
* Se detectaron los destinos más populares dentro de la ciudad.
* El análisis estadístico permitió evaluar el impacto de la lluvia en la duración de los viajes.
* La prueba de hipótesis permitió determinar si las diferencias observadas eran estadísticamente significativas.

---

## 🛠 Tecnologías Utilizadas

* **SQL**
* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **SciPy**
* **BeautifulSoup (Web Scraping)**
* **Jupyter Notebook**

---

## ▶️ Cómo ejecutar el proyecto

```bash
git clone https://github.com/tu_usuario/nombre_proyecto.git
cd nombre_proyecto
pip install -r requirements.txt
```

Abrir el archivo `.ipynb` en **Jupyter Notebook** para reproducir el análisis.

---

## 📁 Estructura del Repositorio

```
data/
notebooks/
sql_queries/
README.md
requirements.txt
```

---

## 📌 Conclusión

Este análisis permitió comprender mejor los patrones de movilidad dentro de Chicago y evaluar el impacto de las condiciones climáticas en los viajes.

Los resultados pueden ayudar a empresas de ride-sharing a:

* anticipar la demanda en condiciones climáticas adversas
* optimizar la asignación de conductores
* mejorar la planificación operativa.

---

## 👤 Autor

**Eduardo Aranda**
Data Analyst
LinkedIn: https://www.linkedin.com/in/juan-eah/
GitHub: (agregar enlace)
