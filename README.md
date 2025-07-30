🎯 Misión

 Desarrollar modelos predictivos capaces de prever qué clientes tienen mayor probabilidad de cancelar sus servicios.

La empresa quiere anticiparse al problema de la cancelación, y te corresponde a ti construir un pipeline robusto para esta etapa inicial de modelado.

🧠 Objetivos del Desafío

Preparar los datos para el modelado (tratamiento, codificación, normalización).

Realizar análisis de correlación y selección de variables.

Entrenar dos o más modelos de clasificación.

Evaluar el rendimiento de los modelos con métricas.

Interpretar los resultados, incluyendo la importancia de las variables.

Crear una conclusión estratégica señalando los principales factores que influyen en la cancelación.



# 📊 Análisis de Evasión de Clientes (Churn) – TelecomX

Este repositorio contiene el desarrollo completo de un análisis exploratorio de datos (EDA) enfocado en identificar patrones que explican la **evasión de clientes** en una empresa de telecomunicaciones. A través de visualizaciones y procesamiento de datos, se busca comprender las razones detrás del **churn** (abandono del servicio) y proponer acciones estratégicas para reducirlo.

---

## 📁 Contenido del proyecto

- `TelecomX_Data.json` – Archivo de datos con la información de clientes.
- Visualizaciones: gráficos generados con `matplotlib`, `seaborn` y `plotly`.
- Informe final estructurado al final del notebook.

---

## 🎯 Objetivo

Analizar el comportamiento de los clientes y determinar los factores que más influyen en su decisión de **permanecer o abandonar el servicio**. Este análisis permite:

- Comprender el perfil de los clientes que se van.
- Detectar servicios o condiciones asociadas al churn.
- Sugerir estrategias de retención basadas en datos.

---

## 🧹 Limpieza y tratamiento de datos

Se realizaron los siguientes pasos:

- Importación y revisión del dataset.
- Limpieza de valores inconsistentes y estandarización de variables.
- Ingeniería de características:
  - `cuentas_diarias`: cálculo del costo diario por cliente.
  - `cantidad_servicios`: conteo de servicios activos por cliente.
- Codificación binaria y mapeo de variables categóricas.

---

## 📊 Análisis exploratorio de datos

Se exploraron las siguientes relaciones:

- **Distribución de churn** general.
- Comparación por género, tipo de contrato y forma de pago.
- Relación entre cantidad de servicios contratados y churn.
- Distribución de cargos diarios.
- Matriz de correlación entre variables numéricas.

Visualizaciones destacadas:

- Gráficos de barras y pie charts.
- Violin plots y boxplots con Plotly.
- Matriz de correlación interactiva.

---

## 💡 Conclusiones

- Clientes con menos servicios contratados tienden a abandonar más.
- Contratos mensuales y cargos diarios altos se asocian a mayor churn.
- Clientes recientes tienen más probabilidad de irse.
- Los servicios de internet, soporte técnico y seguridad se relacionan con mayor retención.

---

## 🧭 Recomendaciones

1. Promover **contratos de mayor duración**.
2. Ofrecer **paquetes de servicios combinados**.
3. Identificar clientes en riesgo y aplicar **campañas de fidelización**.
4. Evaluar la estructura de **tarifas y cargos diarios**.
5. Monitorear activamente a **clientes nuevos** en los primeros meses.

---

## 🛠️ Tecnologías usadas

- Python 3
- Pandas
- Seaborn
- Matplotlib
- Plotly
- Google colab

---

## 📌 Cómo usar este repositorio

1. Clona este repositorio:
   ```bash
   git clone https:  https://github.com/Richie023/TelecomX_LATAM_challenge.git
# 📊 Análisis de Evasión de Clientes (Churn) – TelecomX

Este repositorio contiene el desarrollo completo de un análisis exploratorio de datos (EDA) enfocado en identificar patrones que explican la **evasión de clientes** en una empresa de telecomunicaciones. A través de visualizaciones y procesamiento de datos, se busca comprender las razones detrás del **churn** (abandono del servicio) y proponer acciones estratégicas para reducirlo.

---

## 📁 Contenido del proyecto

- `TelecomX_Data.json` – Archivo de datos con la información de clientes.
- `churn_analysis.ipynb` – Notebook de Jupyter con todo el análisis realizado.
- Visualizaciones: gráficos generados con `matplotlib`, `seaborn` y `plotly`.
- Informe final estructurado al final del notebook.

---

## 🎯 Objetivo

Analizar el comportamiento de los clientes y determinar los factores que más influyen en su decisión de **permanecer o abandonar el servicio**. Este análisis permite:

- Comprender el perfil de los clientes que se van.
- Detectar servicios o condiciones asociadas al churn.
- Sugerir estrategias de retención basadas en datos.

---

## 🧹 Limpieza y tratamiento de datos

Se realizaron los siguientes pasos:

- Importación y revisión del dataset.
- Limpieza de valores inconsistentes y estandarización de variables.
- Ingeniería de características:
  - `cuentas_diarias`: cálculo del costo diario por cliente.
  - `cantidad_servicios`: conteo de servicios activos por cliente.
- Codificación binaria y mapeo de variables categóricas.

---

## 📊 Análisis exploratorio de datos

Se exploraron las siguientes relaciones:

- **Distribución de churn** general.
- Comparación por género, tipo de contrato y forma de pago.
- Relación entre cantidad de servicios contratados y churn.
- Distribución de cargos diarios.
- Matriz de correlación entre variables numéricas.

Visualizaciones destacadas:

- Gráficos de barras y pie charts.
- Violin plots y boxplots con Plotly.
- Matriz de correlación interactiva.

---

## 💡 Conclusiones

- Clientes con menos servicios contratados tienden a abandonar más.
- Contratos mensuales y cargos diarios altos se asocian a mayor churn.
- Clientes recientes tienen más probabilidad de irse.
- Los servicios de internet, soporte técnico y seguridad se relacionan con mayor retención.

---

## 🧭 Recomendaciones

1. Promover **contratos de mayor duración**.
2. Ofrecer **paquetes de servicios combinados**.
3. Identificar clientes en riesgo y aplicar **campañas de fidelización**.
4. Evaluar la estructura de **tarifas y cargos diarios**.
5. Monitorear activamente a **clientes nuevos** en los primeros meses.

---

## 🛠️ Tecnologías usadas

- Python 3
- Pandas
- Seaborn
- Matplotlib
- Plotly
- Jupyter Notebook

---

## 📌 Cómo usar este repositorio

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu_usuario/nombre_del_repositorio.git

   👤 Autor [Ricardo Andres Ulloa Araya]


