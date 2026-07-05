# 📊 Análisis Exploratorio del Producto Bruto Interno (PBI) de América Latina (2000–2024)

<div align="center">

### Exploratory Data Analysis (EDA) • Data Analytics • Economía • Machine Learning

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-blue?style=for-the-badge&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green?style=for-the-badge)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?style=for-the-badge&logo=scikit-learn)

</div>

---

# 🌎 Descripción del proyecto

Este proyecto desarrolla un **Análisis Exploratorio de Datos (EDA)** sobre la evolución del **Producto Bruto Interno (PBI) nominal** de **17 países de América Latina** durante el período **2000–2024**.

El objetivo principal consiste en comprender cómo han evolucionado las economías latinoamericanas en los últimos veinticinco años mediante técnicas de estadística descriptiva, visualización de datos y análisis multivariado.

Además del estudio descriptivo, el proyecto busca identificar relaciones estructurales entre los países y sentar las bases para aplicar técnicas de **Machine Learning** como **PCA (Principal Component Analysis)** y **Clustering**.

---

# 🎯 Objetivo

Analizar la evolución del Producto Bruto Interno (PBI) de América Latina entre los años **2000 y 2024**, identificando patrones de crecimiento, diferencias estructurales, niveles de volatilidad y relaciones entre economías mediante técnicas de Ciencia de Datos.

---

# ❓ Preguntas de investigación

Este proyecto busca responder las siguientes preguntas:

- ¿Cómo ha evolucionado el PBI latinoamericano durante los últimos 25 años?
- ¿Qué países lideran el crecimiento económico regional?
- ¿Existen economías con comportamientos similares?
- ¿Cómo reaccionó América Latina frente a las principales crisis internacionales?
- ¿Es posible identificar bloques económicos mediante técnicas estadísticas?
- ¿Qué tan sincronizados se encuentran los ciclos económicos de la región?

---

# 📌 Principales hallazgos

Antes de profundizar en el análisis, estos son algunos de los resultados más relevantes obtenidos:

| Hallazgo | Resultado |
|----------|-----------|
| 🌎 Cobertura | 17 países latinoamericanos |
| 📅 Periodo analizado | 2000–2024 |
| 📈 Tendencia regional | Crecimiento sostenido con desaceleraciones temporales |
| 📉 Mayor volatilidad | Argentina |
| 🚀 Mayor crecimiento relativo | Perú y Panamá |
| 🔗 Correlación | Alta sincronización entre la mayoría de economías |
| 🧠 Machine Learning | La alta correlación justifica el uso de PCA y Clustering |

---

# 🗂️ Contenido del proyecto

- Introducción
- Dataset
- Tecnologías utilizadas
- Metodología
- Análisis Exploratorio de Datos (EDA)
- Estadística descriptiva
- Evolución temporal del PBI
- Análisis de volatilidad
- Crecimiento acumulado
- Matriz de correlación
- Interpretación económica
- Implicancias para PCA
- Implicancias para Clustering
- Conclusiones

---

# 🌎 Cobertura del estudio

| Característica | Descripción |
|----------------|-------------|
| Región | América Latina |
| Países | 17 |
| Cobertura temporal | 2000–2024 |
| Frecuencia | Anual |
| Variable analizada | Producto Bruto Interno Nominal |
| Unidad | Miles de millones de USD |

---

# 🌎 Países incluidos

| Sudamérica | Centroamérica |
|-------------|---------------|
| Argentina | Costa Rica |
| Bolivia | El Salvador |
| Brasil | Guatemala |
| Chile | Honduras |
| Colombia | Nicaragua |
| Ecuador | Panamá |
| Paraguay | República Dominicana |
| Perú | |
| Uruguay | |
| México* | |

> **Nota:** Aunque geográficamente México pertenece a Norteamérica, se incluye debido a su relevancia económica y su frecuente análisis conjunto con América Latina.

---

# 🛠️ Tecnologías utilizadas

| Herramienta | Propósito |
|--------------|-----------|
| Python | Desarrollo del proyecto |
| Pandas | Manipulación y limpieza de datos |
| NumPy | Cálculo numérico |
| Matplotlib | Visualización |
| Seaborn | Estadística gráfica |
| Scikit-Learn | PCA y Clustering |
| Jupyter Notebook | Desarrollo interactivo |

---

# 📂 Estructura del repositorio

```text
eda-correlacion-pbi-latinoamerica/
│
├── data/
│   └── pbi_latinoamerica.csv
│
├── notebooks/
│   └── eda_pbi_latinoamerica.ipynb
│
├── images/
│
├── README.md
│
└── requirements.txt
```

---

# 🔬 Metodología

El proyecto sigue un flujo de trabajo típico de Ciencia de Datos, integrando análisis exploratorio, estadística descriptiva y técnicas de aprendizaje no supervisado.

```text
Obtención de datos
        │
        ▼
Limpieza de datos
        │
        ▼
Análisis Exploratorio (EDA)
        │
        ▼
Visualización
        │
        ▼
Estadística descriptiva
        │
        ▼
Matriz de correlación
        │
        ▼
PCA
        │
        ▼
Clustering
        │
        ▼
Interpretación económica
```

---

# 📊 ¿Por qué analizar el PBI?

El Producto Bruto Interno (PBI) es uno de los indicadores macroeconómicos más utilizados para medir el tamaño y la evolución de una economía.

Analizar su comportamiento a lo largo del tiempo permite identificar:

- Tendencias de crecimiento.
- Cambios estructurales.
- Impacto de crisis económicas.
- Diferencias entre economías grandes y pequeñas.
- Similitudes entre países.

En este proyecto, el PBI constituye la variable central para explorar la dinámica económica de América Latina durante los últimos 25 años.

---

# 📈 Panorama general

Antes de estudiar cada economía de manera individual, es necesario comprender la evolución agregada del Producto Bruto Interno regional.

La siguiente visualización resume la evolución del PBI de los países latinoamericanos durante el período 2000–2024 y sirve como punto de partida para el análisis exploratorio presentado en las siguientes secciones.


---

# 📊 Análisis Exploratorio de Datos (EDA)

El **Análisis Exploratorio de Datos (EDA)** constituye la etapa inicial de cualquier proyecto de Ciencia de Datos. Su objetivo es comprender la estructura del conjunto de datos, identificar patrones, detectar anomalías y generar hipótesis antes de aplicar modelos estadísticos o de Machine Learning.

En este proyecto, el EDA permite analizar la evolución del Producto Bruto Interno (PBI) de América Latina durante el período **2000–2024**, identificando diferencias estructurales entre economías, tendencias de crecimiento y el impacto de eventos económicos internacionales.

---

# 📈 Evolución del PBI de América Latina (2000–2024)

<div align="center">

<img width="1000" src="https://github.com/user-attachments/assets/af494261-20ab-4e2b-b5ae-258cdf85d4ac"/>

</div>

## 🎯 ¿Qué muestra este gráfico?

La figura presenta la evolución anual del Producto Bruto Interno nominal de los 17 países analizados entre los años 2000 y 2024.

Cada línea representa la trayectoria económica de un país, permitiendo comparar simultáneamente el crecimiento, la estabilidad y la magnitud de sus economías.

---

## 📌 Principales observaciones

### Brasil y México dominan la economía regional

Desde el inicio del período analizado se observa que Brasil y México concentran la mayor parte del PBI latinoamericano.

Su tamaño económico genera una fuerte asimetría dentro de la región, influyendo significativamente sobre cualquier indicador agregado.

---

### Existe una elevada heterogeneidad económica

Mientras Brasil supera ampliamente el billón de dólares durante varios años, numerosas economías centroamericanas mantienen niveles considerablemente menores.

Esto evidencia que América Latina no constituye un bloque homogéneo desde el punto de vista económico.

---

### Crecimiento regional de largo plazo

A pesar de diversos episodios de crisis internacionales, la tendencia general muestra un crecimiento sostenido del Producto Bruto Interno regional.

Sin embargo, dicho crecimiento presenta diferentes velocidades dependiendo de la estructura productiva de cada país.

---

## 💡 Insight

> **El crecimiento latinoamericano está liderado por un reducido grupo de economías grandes, mientras la mayoría de países mantiene trayectorias significativamente menores.**

---

# 📊 Estadística descriptiva

Las medidas descriptivas permiten resumir el comportamiento general del conjunto de datos antes de realizar análisis más avanzados.

## Tendencia central

| Indicador | Año 2000 | Año 2024 |
|-----------|---------:|---------:|
| PBI promedio | USD 123 mil millones | USD 382 mil millones |

El incremento del promedio regional evidencia una expansión económica importante durante el período analizado.

No obstante, este crecimiento se encuentra influenciado principalmente por las economías de mayor tamaño.

---

## Dispersión

La desviación estándar aumenta progresivamente conforme avanza el período de estudio.

Esto significa que la diferencia entre las economías grandes y pequeñas continúa ampliándose.

En consecuencia, los datos sugieren un proceso de **divergencia económica**, más que de convergencia regional.

---

## Distribución

La distribución del PBI presenta una marcada **asimetría positiva**.

Esto ocurre porque:

- Brasil y México desplazan el promedio hacia valores elevados.
- La mayoría de economías se concentra en niveles mucho menores.
- Existen pocos valores extremadamente altos.

Desde una perspectiva estadística, esta distribución corresponde a una **Long Tail Distribution**.

---

# 🌎 Clasificación estructural de las economías

A partir del tamaño del Producto Bruto Interno es posible distinguir tres grandes grupos económicos.

| Grupo | Países | Características |
|--------|---------|----------------|
| Grandes | Brasil, México | Alta participación regional y mayor volatilidad |
| Medianas | Argentina, Chile, Colombia, Perú | Crecimiento sostenido con diferencias estructurales |
| Pequeñas | Centroamérica, Bolivia, Paraguay y Uruguay | Mayor estabilidad, menor tamaño económico |

---

# 🌍 Grandes ciclos económicos

## Crisis regional (2000–2002)

<div align="center">

<img width="900" src="https://github.com/user-attachments/assets/90387c62-c517-4f00-9062-f02c8f3d50ca"/>

</div>

Durante los primeros años del siglo XXI la región experimentó importantes dificultades económicas.

Argentina sufrió una de las crisis financieras más severas de su historia reciente, mientras Uruguay también registró una fuerte desaceleración.

Brasil y México lograron amortiguar parcialmente los efectos gracias al tamaño de sus mercados internos.

---

## Boom de materias primas (2003–2011)

El incremento sostenido del precio internacional de los commodities impulsó una etapa de crecimiento generalizado.

Las economías más beneficiadas fueron:

- 🇧🇷 Brasil
- 🇨🇱 Chile
- 🇵🇪 Perú
- 🇨🇴 Colombia

Este período coincide con una expansión significativa del comercio internacional y de la demanda asiática, particularmente de China.

---

## Desaceleración (2012–2019)

Luego del auge de los commodities, la región experimentó una etapa de crecimiento moderado.

Entre las principales causas destacan:

- Menor crecimiento mundial.
- Reducción del precio de materias primas.
- Limitaciones estructurales internas.
- Menor inversión extranjera.

---

## Pandemia COVID-19 (2020)

La pandemia produjo una contracción prácticamente simultánea en todas las economías latinoamericanas.

Este comportamiento constituye una primera evidencia visual de una elevada sincronización regional.

---

## Recuperación (2021–2024)

La recuperación posterior a la pandemia no fue uniforme.

Mientras Brasil y México recuperaron rápidamente gran parte de su actividad económica, otros países enfrentaron procesos de recuperación más lentos y heterogéneos.

---

# 📊 Análisis de volatilidad

<div align="center">

<img width="900" src="https://github.com/user-attachments/assets/29ed539e-344e-48dc-88ff-2f4da266deb3"/>

</div>

La volatilidad permite medir la intensidad de las fluctuaciones económicas registradas por cada país durante el período analizado.

## Países con mayor volatilidad

🥇 Argentina

🥈 Brasil

🥉 Chile

Estas economías muestran una mayor sensibilidad frente a cambios en el contexto internacional y a factores internos de política económica.

---

## Países con mayor estabilidad

- Guatemala
- Honduras
- Nicaragua
- Panamá

Aunque presentan economías de menor tamaño, sus trayectorias muestran variaciones considerablemente más moderadas.

---

# 🚀 Crecimiento acumulado

<div align="center">

<img width="900" src="https://github.com/user-attachments/assets/4f588f2b-867c-4895-ba2a-af3a14c7a6a2"/>

</div>

El crecimiento acumulado permite comparar el desempeño económico de los países durante todo el período de estudio.

## Economías con mayor crecimiento relativo

| Posición | País |
|-----------|------|
| 🥇 | Perú |
| 🥈 | Panamá |
| 🥉 | República Dominicana |
| 4️⃣ | Colombia |

Estas economías lograron expandir significativamente su tamaño económico gracias a una combinación de estabilidad macroeconómica, apertura comercial e inversión.

---

## 📌 Principales conclusiones del EDA

✔ La economía latinoamericana creció de forma sostenida durante las últimas dos décadas.

✔ Brasil y México continúan concentrando una parte importante del PBI regional.

✔ Las economías pequeñas muestran mayor estabilidad, aunque con menor capacidad de crecimiento.

✔ Las crisis internacionales afectan simultáneamente a la mayoría de países.

✔ La recuperación posterior depende principalmente de factores estructurales internos.

---

> ---

# 🔥 Matriz de Correlación

La matriz de correlación permite evaluar el grado de relación lineal entre las economías latinoamericanas durante el período **2000–2024**.

En este proyecto se utilizó el **coeficiente de correlación de Pearson**, una de las métricas más empleadas en estadística para cuantificar la intensidad y dirección de la relación entre dos variables.

Su interpretación es la siguiente:

| Valor | Interpretación |
|---------|----------------|
| **1.00** | Correlación positiva perfecta |
| **0.80 – 0.99** | Muy fuerte |
| **0.60 – 0.79** | Fuerte |
| **0.40 – 0.59** | Moderada |
| **0.20 – 0.39** | Débil |
| **0.00** | Sin relación lineal |

> **Importante:** Una correlación alta indica que dos economías presentan trayectorias similares, pero **no implica causalidad**.

---

<div align="center">

<img width="900" src="https://github.com/user-attachments/assets/79b9f585-aa1c-477c-bf7e-747846c0402b"/>

</div>

---

# 📊 Interpretación general

La matriz revela que la mayoría de las economías latinoamericanas presentan **correlaciones positivas elevadas**, lo que indica que sus ciclos económicos han evolucionado de manera similar durante los últimos veinticinco años.

Este comportamiento sugiere que los países de la región responden de forma relativamente sincronizada a eventos externos como:

- Crisis financieras internacionales.
- Variaciones en los precios de los commodities.
- Cambios en las tasas de interés internacionales.
- Fluctuaciones del comercio mundial.
- Cambios en la demanda de Estados Unidos y China.

En términos económicos, esto significa que América Latina comparte un ciclo económico regional, aunque cada país conserve características estructurales propias.

---

# 📌 Hallazgos principales

## 🌎 1. Existe una elevada sincronización regional

La mayor parte de los coeficientes supera **0.85**, indicando que las economías latinoamericanas atraviesan fases de crecimiento y desaceleración de forma similar.

Este resultado refleja la fuerte influencia de factores macroeconómicos globales sobre la región.

---

## 🇧🇷 2. Brasil presenta el comportamiento más independiente

Brasil registra correlaciones menores respecto a varios países de la región.

Esto puede explicarse por:

- Gran mercado interno.
- Mayor diversificación productiva.
- Importante sector industrial.
- Menor dependencia relativa del comercio regional.

Aunque continúa formando parte del ciclo latinoamericano, su evolución depende en mayor medida de factores internos.

---

## 🇲🇽 3. México mantiene una dinámica particular

México presenta una posición intermedia dentro de la matriz.

Su estrecha integración con Estados Unidos hace que su crecimiento responda tanto al contexto latinoamericano como al ciclo económico norteamericano.

Actualmente destacan factores como:

- Nearshoring.
- Manufactura.
- Exportaciones industriales.
- Cadenas globales de suministro.

---

## ⛰️ 4. Las economías andinas muestran trayectorias similares

Perú, Chile, Colombia y Ecuador presentan correlaciones elevadas entre sí.

Las similitudes pueden asociarse a:

- Dependencia de exportaciones mineras.
- Influencia del mercado chino.
- Estructuras productivas comparables.
- Políticas macroeconómicas relativamente similares.

---

## 🌴 5. Centroamérica conforma uno de los bloques más homogéneos

Guatemala, Honduras, El Salvador, Nicaragua, Costa Rica y Panamá muestran algunas de las correlaciones más altas del estudio.

Esto sugiere una fuerte integración económica y una elevada sensibilidad a factores comunes como:

- Turismo.
- Remesas.
- Comercio intrarregional.
- Economía estadounidense.

---

## 🇦🇷 6. Argentina destaca por su volatilidad

Aunque mantiene correlaciones positivas con el resto de la región, Argentina presenta una mayor amplitud en sus fluctuaciones económicas.

Las causas incluyen:

- Inflación persistente.
- Crisis cambiarias.
- Cambios frecuentes de política económica.
- Restricciones fiscales.

Esto explica por qué comparte el ciclo regional, pero con una intensidad considerablemente mayor.

---

# 📈 Implicancias económicas

La elevada correlación observada indica que las economías latinoamericanas no evolucionan de manera aislada.

Los principales eventos internacionales afectan simultáneamente a la mayoría de países, generando ciclos económicos sincronizados.

No obstante, la velocidad de recuperación depende de factores internos como:

- Productividad.
- Instituciones.
- Diversificación económica.
- Estabilidad macroeconómica.
- Calidad de las políticas públicas.

---

# 🧠 Implicancias para Machine Learning

Uno de los objetivos del proyecto consiste en evaluar si las técnicas de aprendizaje automático pueden aportar una mejor comprensión de las relaciones económicas entre países.

Los resultados del análisis exploratorio muestran que sí.

## 📌 Redundancia de información

Las altas correlaciones indican que muchas variables contienen información muy similar.

Desde una perspectiva estadística esto se conoce como **multicolinealidad**.

Como consecuencia:

- Existe redundancia en el conjunto de datos.
- Varias variables aportan información repetida.
- El espacio de características puede simplificarse.

---

## 📊 ¿Por qué aplicar PCA?

El **Análisis de Componentes Principales (PCA)** permite reducir la dimensionalidad del problema sin perder gran parte de la información contenida en los datos.

En este proyecto, PCA permitirá:

- Reducir variables altamente correlacionadas.
- Eliminar redundancia.
- Identificar factores comunes de crecimiento.
- Facilitar la visualización del conjunto de datos.

---

## 🤖 ¿Por qué aplicar Clustering?

Si varios países presentan trayectorias similares, es razonable esperar que puedan agruparse automáticamente mediante algoritmos de aprendizaje no supervisado.

El análisis de Clustering permitirá identificar bloques económicos sin necesidad de definir categorías previamente.

Esto facilitará descubrir grupos de economías con patrones de crecimiento comparables.

---

# 💡 Principales insights

| Insight | Interpretación |
|----------|----------------|
| 🌎 Alta correlación regional | Las economías responden de forma similar a choques externos. |
| 🇧🇷 Brasil | Presenta mayor independencia económica relativa. |
| 🇲🇽 México | Actúa como puente entre América Latina y Estados Unidos. |
| ⛰️ Países andinos | Comparten patrones de crecimiento similares. |
| 🌴 Centroamérica | Constituye el bloque económico más homogéneo. |
| 🧠 PCA | La alta correlación justifica la reducción de dimensionalidad. |
| 🤖 Clustering | Es posible identificar grupos naturales de economías. |

---

# ⚠️ Limitaciones del proyecto

Este análisis presenta algunas limitaciones que deben considerarse:

- Se utiliza únicamente el PBI nominal.
- No se incorporan variables demográficas o institucionales.
- No se consideran indicadores de inflación ni productividad.
- No se analizan relaciones causales.

Estas limitaciones representan oportunidades para ampliar el proyecto en futuras investigaciones.

---

# 🚀 Trabajo futuro

Como continuación de este estudio se propone incorporar:

- 📊 Dashboard interactivo en Power BI o Tableau.
- 🌍 Visualizaciones geográficas.
- 📈 Modelos de series temporales (ARIMA, Prophet y LSTM).
- 🤖 Modelos predictivos con Machine Learning.
- 📦 Análisis de exportaciones y comercio internacional.
- 💰 Indicadores de inversión extranjera directa.
- 🏛️ Variables institucionales y de gobernanza.

---

# 🎯 Conclusiones

Este proyecto demuestra cómo las técnicas de **Análisis Exploratorio de Datos (EDA)** permiten comprender la evolución económica de América Latina mediante el estudio del Producto Bruto Interno.

Los resultados evidencian un crecimiento sostenido de la región durante el período 2000–2024, acompañado de diferencias significativas entre economías grandes, medianas y pequeñas.

La matriz de correlación muestra una elevada sincronización entre los países, lo que sugiere la existencia de factores comunes que influyen sobre el desempeño económico regional.

Asimismo, la presencia de variables altamente correlacionadas justifica la aplicación de técnicas como **PCA** y **Clustering**, las cuales permiten simplificar el análisis e identificar patrones ocultos dentro de los datos.

En conjunto, este proyecto integra herramientas de estadística, visualización y aprendizaje automático para transformar datos económicos en información útil para el análisis y la toma de decisiones.

---

# 📚 Herramientas utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# 👨‍💻 Autor

## Andrés Mena

**Ingeniería • Data Analytics • Machine Learning • Comercio Internacional • Agroindustria**

📌 Si este proyecto te resultó útil o interesante, considera darle una ⭐ al repositorio y compartir tus comentarios o sugerencias.

---
