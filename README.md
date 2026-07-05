# 📊 Análisis Exploratorio del Producto Bruto Interno (PBI) de América Latina (2000–2024)

<div align="center">

## Exploratory Data Analysis (EDA) | Estadística | Visualización | Economía | Ciencia de Datos

---

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-blue?style=for-the-badge&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green?style=for-the-badge)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?style=for-the-badge&logo=scikit-learn)
![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)

</div>

---

# 📖 Descripción del proyecto

Este proyecto desarrolla un **Análisis Exploratorio de Datos (EDA)** sobre la evolución del **Producto Bruto Interno (PBI) nominal** de **17 países de América Latina** durante el período **2000–2024**.

El estudio tiene como propósito identificar patrones de crecimiento, ciclos económicos, niveles de volatilidad y similitudes estructurales entre las economías latinoamericanas utilizando herramientas estadísticas y técnicas de análisis multivariado.

Más allá de describir el comportamiento histórico del PBI, el proyecto busca responder una pregunta de gran relevancia económica:

> **¿Las economías latinoamericanas crecen de manera independiente o siguen un mismo ciclo económico?**

Para responder esta interrogante se emplean diferentes técnicas de Ciencia de Datos que permiten transformar datos económicos en información útil para comprender la dinámica regional.

---

# 🎯 Objetivos

## Objetivo general

Analizar la evolución del Producto Bruto Interno (PBI) de América Latina entre los años 2000 y 2024 mediante técnicas de análisis exploratorio de datos (EDA), estadística descriptiva, correlación, reducción de dimensionalidad y aprendizaje no supervisado.

---

## Objetivos específicos

- Explorar la evolución temporal del PBI de cada país.

- Identificar tendencias de crecimiento económico regional.

- Detectar diferencias estructurales entre economías grandes, medianas y pequeñas.

- Analizar la volatilidad económica de cada país.

- Evaluar el grado de sincronización entre las economías latinoamericanas.

- Determinar si existen grupos de países con trayectorias económicas similares.

- Validar el uso de técnicas como PCA y Clustering para reducir la complejidad del conjunto de datos.

---

# ❓ Preguntas de investigación

Este proyecto intenta responder las siguientes preguntas:

- ¿Cómo ha evolucionado el PBI latinoamericano durante los últimos 25 años?

- ¿Existen economías que lideran el crecimiento regional?

- ¿Qué países presentan mayor estabilidad económica?

- ¿Las economías latinoamericanas reaccionan de manera similar frente a las crisis internacionales?

- ¿Es posible identificar bloques económicos mediante técnicas de Ciencia de Datos?

- ¿Qué tan correlacionados están los ciclos económicos de la región?

---

# 🌎 Cobertura del estudio

| Variable | Descripción |
|-----------|-------------|
| Región | América Latina |
| Número de países | 17 |
| Cobertura temporal | 2000 – 2024 |
| Frecuencia | Anual |
| Variable principal | Producto Bruto Interno Nominal |
| Unidad | Miles de millones de dólares estadounidenses (USD) |

---

# 📂 Países analizados

- Argentina
- Bolivia
- Brasil
- Chile
- Colombia
- Costa Rica
- Ecuador
- El Salvador
- Guatemala
- Honduras
- México
- Nicaragua
- Panamá
- Paraguay
- Perú
- República Dominicana
- Uruguay

---

# 📚 Tecnologías utilizadas

El proyecto fue desarrollado completamente en Python utilizando herramientas ampliamente empleadas en Ciencia de Datos.

| Herramienta | Uso |
|------------|------|
| Python | Lenguaje principal |
| Pandas | Manipulación de datos |
| NumPy | Operaciones matemáticas |
| Matplotlib | Visualización |
| Seaborn | Gráficos estadísticos |
| Scikit-Learn | PCA y Clustering |
| Jupyter Notebook | Desarrollo del proyecto |

---

# 📁 Estructura del proyecto

```
eda-correlacion-pbi-latinoamerica/

├── data/
│      pbi_latinoamerica.csv
├── notebooks/
│      EDA_PBI.ipynb
├── images/
├── README.md
└── requirements.txt
---

# 🔬 Metodología

El proyecto sigue una metodología clásica de Ciencia de Datos aplicada al análisis económico.

## 1️⃣ Recolección de datos

Se recopiló la información histórica del Producto Bruto Interno de cada país latinoamericano para el período comprendido entre 2000 y 2024.

Posteriormente se realizó la consolidación de todas las series temporales en un único conjunto de datos estructurado.

---

## 2️⃣ Limpieza y preparación de datos

Durante esta etapa se realizaron las siguientes actividades:

- revisión de valores faltantes

- estandarización de nombres

- transformación de variables

- validación de consistencia

- organización del dataset para análisis temporal

---

## 3️⃣ Análisis Exploratorio de Datos (EDA)

Se aplicaron técnicas de estadística descriptiva para comprender el comportamiento general del conjunto de datos.

Entre ellas destacan:

- medidas de tendencia central

- dispersión

- distribución

- evolución temporal

- comparación entre países

- detección de patrones

---

## 4️⃣ Correlación

Se construyó una matriz de correlación para evaluar el grado de asociación lineal entre las trayectorias del PBI de los distintos países.

Esta etapa permite determinar qué economías evolucionan de manera similar y constituye la base para aplicar técnicas posteriores de reducción de dimensionalidad.

---

## 5️⃣ Reducción de dimensionalidad (PCA)

El Análisis de Componentes Principales (PCA) permite sintetizar la información contenida en múltiples variables altamente correlacionadas, reduciendo la complejidad del conjunto de datos sin perder una proporción significativa de la variabilidad.

---

## 6️⃣ Clustering

Finalmente se aplican técnicas de aprendizaje no supervisado para identificar grupos de países con patrones de crecimiento económico similares.

El objetivo es reconocer estructuras regionales que no son evidentes mediante un análisis descriptivo convencional.

---

# 📈 Flujo metodológico

```text
Obtención de datos
        │
        ▼
Limpieza y preparación
        │
        ▼
Análisis Exploratorio (EDA)
        │
        ▼
Estadística descriptiva
        │
        ▼
Visualización
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

# 📊 Panorama general del conjunto de datos

Antes de analizar cada país individualmente, resulta importante comprender la estructura general del conjunto de datos.

Las economías latinoamericanas presentan diferencias sustanciales en tamaño, ritmo de crecimiento y volatilidad. Mientras Brasil y México concentran una parte importante del PBI regional, el resto de países exhibe economías considerablemente menores, generando una distribución altamente asimétrica.

Esta heterogeneidad hace indispensable el uso de herramientas estadísticas que permitan diferenciar patrones estructurales de simples diferencias de escala.

La siguiente figura resume visualmente la evolución agregada del Producto Bruto Interno latinoamericano durante el período analizado.

```



<img width="1178" height="722" alt="image" src="https://github.com/user-attachments/assets/af494261-20ab-4e2b-b5ae-258cdf85d4ac" />

# 📊 Análisis Exploratorio de Datos (EDA)

El Análisis Exploratorio de Datos (Exploratory Data Analysis - EDA) constituye la primera etapa analítica del proyecto y tiene como propósito comprender el comportamiento histórico del Producto Bruto Interno (PBI) de las economías latinoamericanas antes de aplicar técnicas de modelado estadístico.

A través de estadísticas descriptivas y visualizaciones es posible identificar tendencias, patrones de crecimiento, cambios estructurales, niveles de volatilidad y diferencias entre países.

Este enfoque permite transformar grandes volúmenes de datos en conocimiento económico útil para interpretar la evolución regional durante los últimos veinticinco años.

---

# 🌎 Evolución del PBI latinoamericano (2000–2024)

<img width="1178" height="722" alt="image" src="https://github.com/user-attachments/assets/af494261-20ab-4e2b-b5ae-258cdf85d4ac"/>

## Principales características del conjunto de datos

| Característica | Valor |
|----------------|-------|
| Período analizado | 2000–2024 |
| Número de observaciones | 25 años |
| Países analizados | 17 |
| Variable principal | PBI Nominal |
| Unidad | Miles de millones de dólares (USD) |

---

## Interpretación

La evolución histórica del Producto Bruto Interno muestra un crecimiento prácticamente continuo de la economía latinoamericana durante las últimas dos décadas, aunque dicho crecimiento no ha sido uniforme entre los países.

A simple vista puede observarse una marcada diferencia entre un pequeño grupo de economías de gran tamaño —principalmente Brasil y México— y el resto de países de la región.

Esta diferencia genera una distribución altamente asimétrica, donde unas pocas economías concentran la mayor parte de la producción regional.

En consecuencia, el comportamiento agregado de América Latina suele estar fuertemente influenciado por estas dos economías.

---

## Hallazgos principales

- El PBI regional aumenta de manera sostenida entre 2000 y 2024.

- Brasil y México concentran una proporción significativa de la producción regional.

- Las economías pequeñas presentan trayectorias mucho más estables.

- La región mantiene una elevada heterogeneidad económica.

---

# 📈 Estadística descriptiva

El análisis descriptivo constituye la base del EDA, ya que resume el comportamiento general del conjunto de datos mediante indicadores estadísticos.

Las medidas de tendencia central muestran un incremento importante del tamaño promedio de las economías latinoamericanas durante el período analizado.

## Tendencia central

| Año | PBI promedio aproximado |
|-----|-------------------------|
| 2000 | USD 123 mil millones |
| 2024 | USD 382 mil millones |

El incremento del promedio regional refleja un crecimiento económico agregado considerable.

No obstante, este crecimiento no implica que todas las economías hayan experimentado una expansión similar.

Las economías de mayor tamaño ejercen una influencia desproporcionada sobre el promedio regional.

---

## Dispersión económica

Uno de los resultados más relevantes del análisis descriptivo es el incremento progresivo de la desviación estándar.

Este comportamiento indica que la distancia entre las economías grandes y pequeñas continúa aumentando.

En otras palabras, el crecimiento económico regional ha estado acompañado por una mayor desigualdad en tamaño económico.

### Interpretación económica

En lugar de observar un proceso de convergencia económica, donde las economías pequeñas alcancen gradualmente a las grandes, los datos muestran un fenómeno de divergencia.

Brasil y México continúan ampliando la brecha respecto al resto de países.

---

## Asimetría de la distribución

La distribución del PBI presenta una marcada asimetría positiva.

Esto se evidencia porque:

- La media supera ampliamente a la mediana.
- Existen pocos valores extremadamente grandes.
- La mayoría de economías poseen un tamaño relativamente reducido.

Desde una perspectiva estadística, esta distribución corresponde a una **cola larga (long tail distribution)**.

---

# 🏛 Clasificación estructural de las economías

A partir de la magnitud del Producto Bruto Interno es posible distinguir tres grandes grupos dentro de América Latina.

## Economías grandes

- 🇧🇷 Brasil
- 🇲🇽 México

Estas economías representan la mayor parte del PBI regional.

Características principales:

- Mayor influencia sobre el promedio regional.
- Alta exposición a los mercados financieros internacionales.
- Elevada sensibilidad al precio de los commodities.
- Mayor volatilidad durante crisis globales.

Brasil presenta el ciclo económico más pronunciado del conjunto de datos.

Su trayectoria puede dividirse en cuatro etapas claramente diferenciadas:

- Boom económico (2003–2011)
- Estancamiento (2014–2019)
- Crisis COVID-19 (2020)
- Recuperación parcial (2021–2024)

---

## Economías medianas

- 🇦🇷 Argentina
- 🇨🇴 Colombia
- 🇨🇱 Chile
- 🇵🇪 Perú

Estas economías muestran un comportamiento mucho más heterogéneo.

Mientras Perú y Colombia mantienen trayectorias relativamente estables, Argentina presenta episodios recurrentes de elevada volatilidad.

Chile exhibe una evolución intermedia, influenciada por los ciclos internacionales del cobre.

---

## Economías pequeñas

Incluyen principalmente a los países centroamericanos y algunas economías sudamericanas.

Entre ellas destacan:

- Guatemala
- Honduras
- Nicaragua
- El Salvador
- Paraguay
- Bolivia
- Uruguay
- Panamá
- República Dominicana

En conjunto presentan:

- Crecimiento sostenido.
- Menor amplitud de los ciclos económicos.
- Mayor estabilidad relativa.
- Menor exposición a grandes fluctuaciones internacionales.

---

# 📉 Grandes ciclos económicos

## Crisis inicial (2000–2002)

<img width="1028" height="632" alt="image" src="https://github.com/user-attachments/assets/90387c62-c517-4f00-9062-f02c8f3d50ca"/>

La primera etapa del análisis está marcada por importantes dificultades macroeconómicas.

Argentina atraviesa una profunda crisis financiera entre 2001 y 2002, generando efectos sobre Uruguay y otras economías vecinas.

Brasil y México muestran una mayor capacidad de resistencia debido a la dimensión de sus mercados internos.

---

## Boom de commodities (2003–2011)

Este período representa la fase de mayor expansión económica observada en el conjunto de datos.

El incremento sostenido de los precios internacionales de materias primas impulsó el crecimiento de prácticamente toda la región.

Los principales beneficiados fueron:

- Brasil
- Chile
- Perú
- Colombia

Este ciclo permitió:

- Incremento del ingreso nacional.
- Expansión de las exportaciones.
- Reducción de pobreza en diversos países.
- Crecimiento acelerado de la inversión.

Desde una perspectiva histórica, constituye el período macroeconómico más favorable para América Latina durante el siglo XXI.

---

## Estancamiento (2012–2019)

Luego del fin del súper ciclo de commodities comienza una desaceleración regional.

Las principales causas incluyen:

- Menor crecimiento mundial.
- Caída del precio de materias primas.
- Problemas estructurales internos.
- Menor inversión.

La región experimenta una etapa caracterizada por bajo crecimiento y limitada capacidad de expansión.

---

## Crisis COVID-19 (2020)

La pandemia genera una caída prácticamente sincronizada en todas las economías latinoamericanas.

Los efectos se observan con especial intensidad en:

- Brasil
- México
- Argentina
- Chile

Las economías más pequeñas muestran una recuperación relativamente más rápida debido a su menor tamaño y a la reactivación gradual del turismo y las remesas.

---

## Recuperación (2021–2024)

El comportamiento posterior a la pandemia evidencia una recuperación desigual.

Brasil y México recuperan rápidamente parte de la actividad económica.

Perú y Colombia muestran una recuperación sólida.

Argentina continúa presentando elevada volatilidad.

Las economías centroamericanas mantienen trayectorias relativamente estables.

---

# 📊 Análisis de volatilidad

<img width="1111" height="627" alt="image" src="https://github.com/user-attachments/assets/29ed539e-344e-48dc-88ff-2f4da266deb3"/>

La volatilidad mide la magnitud de las fluctuaciones económicas experimentadas por cada país a lo largo del período analizado.

## Países más volátiles

- Argentina
- Brasil
- Chile

Estas economías presentan mayores variaciones debido a:

- Dependencia de commodities.
- Cambios de política económica.
- Crisis financieras.
- Choques internacionales.

## Países más estables

- Guatemala
- Honduras
- Nicaragua
- Panamá

Su crecimiento resulta menos pronunciado, aunque considerablemente más estable.

---

# 🚀 Crecimiento acumulado (2000–2024)

<img width="1093" height="628" alt="image" src="https://github.com/user-attachments/assets/4f588f2b-867c-4895-ba2a-af3a14c7a6a2"/>

El crecimiento acumulado permite comparar la capacidad de expansión de las economías durante los últimos veinticinco años.

## Economías con mayor crecimiento relativo

🥇 Perú

🥈 Panamá

🥉 República Dominicana

🏅 Colombia

Estas economías lograron incrementar significativamente su tamaño económico mediante una combinación de estabilidad macroeconómica, apertura comercial e inversión.

## Economías con menor crecimiento

- Argentina
- Uruguay

En el caso argentino, los episodios recurrentes de inestabilidad macroeconómica limitaron el crecimiento de largo plazo.

---

# 📌 Principales hallazgos del EDA

Del análisis exploratorio pueden extraerse las siguientes conclusiones preliminares:

- El crecimiento regional no ha sido homogéneo.

- La brecha entre economías grandes y pequeñas continúa ampliándose.

- Las crisis internacionales afectan simultáneamente a casi toda la región.

- Las recuperaciones económicas muestran trayectorias mucho más heterogéneas.

- Perú, Panamá y República Dominicana destacan por su elevado crecimiento relativo.

- Argentina constituye el caso más representativo de alta volatilidad macroeconómica.

---

En la siguiente sección se analiza la **matriz de correlación**, uno de los resultados más importantes del proyecto, ya que permite identificar el grado de sincronización entre las economías latinoamericanas y justifica posteriormente la aplicación de técnicas como **PCA (Análisis de Componentes Principales)** y **Clustering**.



<img width="1028" height="632" alt="image" src="https://github.com/user-attachments/assets/90387c62-c517-4f00-9062-f02c8f3d50ca" />

---

# 🔥 Análisis de la Matriz de Correlación

La matriz de correlación representa una de las herramientas más importantes dentro del Análisis Exploratorio de Datos (EDA), ya que permite medir el grado de asociación lineal entre las trayectorias del Producto Bruto Interno (PBI) de los países latinoamericanos durante el período 2000–2024.

A diferencia del análisis descriptivo, que estudia cada economía de manera individual, la matriz de correlación revela **cómo evolucionan conjuntamente las economías de la región** y permite identificar patrones compartidos de crecimiento, sincronización económica y posibles bloques regionales.

En este proyecto se empleó el coeficiente de correlación de **Pearson**, cuyos valores oscilan entre **-1 y 1**:

| Coeficiente | Interpretación |
|-------------|----------------|
| 1.00 | Correlación positiva perfecta |
| 0.80 – 0.99 | Correlación muy fuerte |
| 0.60 – 0.79 | Correlación fuerte |
| 0.40 – 0.59 | Correlación moderada |
| 0.20 – 0.39 | Correlación débil |
| 0.00 | Sin correlación |
| Valores negativos | Relación inversa |

En términos económicos, una correlación elevada indica que dos países experimentan variaciones similares en su PBI a lo largo del tiempo, aunque ello **no implica causalidad** ni que ambos tengan el mismo tamaño económico.

---

# 📊 Matriz de Correlación

<img width="997" height="919" alt="image" src="https://github.com/user-attachments/assets/79b9f585-aa1c-477c-bf7e-747846c0402b"/>

---

# 📌 Hallazgos principales

## 1. Alta sincronización regional

El primer resultado que destaca es la presencia de coeficientes de correlación superiores a **0.85** entre la mayoría de las economías analizadas.

Esto evidencia que los países latinoamericanos tienden a experimentar fases de expansión y contracción económica de manera relativamente sincronizada.

En otras palabras, aunque existen importantes diferencias en tamaño económico, las trayectorias del crecimiento siguen patrones similares.

Esta sincronización refleja la influencia predominante de factores externos compartidos.

Entre ellos destacan:

- Ciclo económico mundial.
- Precios internacionales de los commodities.
- Tasas de interés internacionales.
- Flujos de inversión extranjera.
- Demanda proveniente de Estados Unidos y China.

Uno de los hallazgos más relevantes del estudio es que **América Latina presenta una elevada sincronización cíclica, pero no una convergencia económica**.

Es decir, las economías crecen y se desaceleran al mismo tiempo, aunque las diferencias estructurales entre ellas continúan ampliándose.

---

## 2. Bloque altamente integrado de economías medianas y pequeñas

La matriz evidencia un subconjunto de países con correlaciones extremadamente elevadas (0.97–0.99).

Entre ellos destacan:

- 🇵🇪 Perú
- 🇪🇨 Ecuador
- 🇵🇦 Panamá
- 🇨🇷 Costa Rica
- 🇩🇴 República Dominicana
- 🇬🇹 Guatemala
- 🇳🇮 Nicaragua
- 🇭🇳 Honduras
- 🇸🇻 El Salvador

Este comportamiento sugiere la existencia de un bloque económico con dinámicas muy similares.

Las posibles explicaciones incluyen:

- Economías relativamente abiertas.
- Dependencia de exportaciones primarias.
- Elevada importancia del turismo.
- Remesas como fuente significativa de ingreso.
- Alta sensibilidad a cambios del contexto internacional.

Desde la perspectiva del análisis de datos, estas economías presentan un comportamiento suficientemente parecido como para ser agrupadas mediante algoritmos de aprendizaje no supervisado.

---

## 3. Brasil: la economía más independiente

Brasil presenta los coeficientes de correlación más bajos dentro del conjunto.

En particular:

- Brasil – México ≈ 0.68
- Brasil – Perú ≈ 0.64
- Brasil – Centroamérica ≈ 0.55–0.60

Aunque estos valores siguen siendo positivos, resultan considerablemente inferiores al promedio regional.

Esto sugiere que Brasil posee un ciclo económico parcialmente independiente.

Las principales razones son:

- Mercado interno de gran tamaño.
- Diversificación productiva.
- Sector industrial relativamente desarrollado.
- Mayor autonomía macroeconómica.
- Menor dependencia de remesas y turismo.

Brasil continúa participando del ciclo latinoamericano, aunque su evolución responde en mayor medida a factores domésticos.

---

## 4. México: puente entre América Latina y Estados Unidos

México ocupa una posición intermedia dentro de la matriz de correlación.

Mantiene relaciones elevadas con la mayoría de países latinoamericanos, aunque inferiores a las observadas entre las economías centroamericanas.

Su comportamiento puede explicarse por su estrecha integración con la economía estadounidense.

Actualmente gran parte de su crecimiento depende de:

- Manufactura.
- Nearshoring.
- Cadenas globales de suministro.
- Comercio exterior con Estados Unidos.

Por ello, México actúa como un puente entre la dinámica económica latinoamericana y el ciclo industrial norteamericano.

---

## 5. Países andinos

Perú, Chile, Colombia y Ecuador presentan correlaciones muy elevadas.

Este comportamiento responde principalmente a características estructurales comunes.

Entre ellas destacan:

- Producción minera.
- Exportación de recursos naturales.
- Dependencia del mercado chino.
- Políticas macroeconómicas relativamente similares.

Este grupo constituye uno de los candidatos naturales para formar un mismo clúster durante el análisis de aprendizaje no supervisado.

---

## 6. Centroamérica

Guatemala, Honduras, El Salvador y Nicaragua presentan algunas de las correlaciones más altas de toda la matriz.

Esto sugiere una fuerte integración económica regional.

Las posibles explicaciones incluyen:

- Remesas.
- Integración comercial.
- Similitud productiva.
- Mercados relativamente pequeños.

Desde una perspectiva estadística, estas economías evolucionan prácticamente como un único bloque económico.

---

## 7. Argentina

Argentina presenta correlaciones relativamente altas con el resto de la región.

Sin embargo, también exhibe una volatilidad considerablemente superior.

Esto significa que comparte el ciclo regional, pero amplifica sus fluctuaciones debido a factores internos.

Entre ellos:

- Inflación persistente.
- Cambios frecuentes de política económica.
- Crisis cambiarias.
- Inestabilidad fiscal.

---

# 📈 Interpretación Económica

La matriz de correlación permite llegar a una conclusión importante.

América Latina no constituye un conjunto de economías independientes.

Por el contrario, la región responde de manera relativamente homogénea frente a eventos externos.

Las principales crisis internacionales afectan simultáneamente a casi todos los países.

Sin embargo, la velocidad de recuperación depende de factores internos como:

- Productividad.
- Instituciones.
- Diversificación económica.
- Política fiscal.
- Política monetaria.

Por ello, la región comparte el ciclo económico, pero no necesariamente comparte el crecimiento de largo plazo.

---

# 📊 Implicancias Estadísticas

Desde el punto de vista estadístico, la matriz evidencia un fenómeno conocido como **multicolinealidad**.

Cuando muchas variables presentan correlaciones muy elevadas, existe una importante redundancia de información.

Esto implica que varias variables contienen prácticamente el mismo patrón de comportamiento.

Como consecuencia:

- Los modelos de regresión pueden volverse inestables.
- Los coeficientes pueden resultar difíciles de interpretar.
- Aumenta la redundancia del conjunto de datos.

Este hallazgo justifica plenamente la aplicación de técnicas de reducción de dimensionalidad.

---

# 🔬 Justificación del PCA

El Análisis de Componentes Principales (Principal Component Analysis - PCA) permite sintetizar múltiples variables altamente correlacionadas en un pequeño número de componentes.

En este proyecto, el PCA permite:

- Reducir la dimensionalidad del problema.
- Eliminar redundancia estadística.
- Identificar factores comunes de crecimiento.
- Facilitar la visualización del conjunto de datos.

En otras palabras, el PCA transforma múltiples variables económicas en componentes capaces de resumir la mayor parte de la información disponible.

---

# 🤖 Justificación del Clustering

La elevada correlación entre varios países sugiere la existencia de grupos naturales dentro del conjunto de datos.

Por ello, resulta apropiado aplicar algoritmos de clustering para identificar economías con comportamientos similares.

El objetivo consiste en descubrir estructuras ocultas sin utilizar información previa sobre categorías económicas.

Los resultados del clustering permiten identificar bloques regionales con trayectorias comparables, facilitando la interpretación económica.

---

# 💡 Principales Insights

📌 El crecimiento económico latinoamericano presenta una fuerte dependencia del contexto internacional.

📌 Brasil constituye la economía con mayor autonomía relativa.

📌 México mantiene un comportamiento híbrido debido a su integración con Estados Unidos.

📌 Las economías andinas presentan patrones de crecimiento altamente similares.

📌 Centroamérica conforma uno de los bloques económicos más homogéneos de la región.

📌 Las crisis internacionales generan efectos sincronizados, mientras que las recuperaciones muestran trayectorias diferenciadas.

📌 Las elevadas correlaciones justifican el uso de técnicas de reducción de dimensionalidad y aprendizaje no supervisado.

---

# ⚠️ Limitaciones del estudio

Aunque el análisis proporciona resultados relevantes, existen algunas limitaciones.

- El estudio considera únicamente el PBI nominal.
- No incorpora variables institucionales ni sociales.
- No se incluyen indicadores de inflación.
- No se analiza productividad laboral.
- No se consideran indicadores de desigualdad.

La incorporación de estas variables permitiría desarrollar modelos económicos más completos.

---

# 🚀 Trabajo futuro

Este proyecto puede ampliarse mediante la incorporación de nuevas técnicas de Ciencia de Datos.

Entre las posibles extensiones destacan:

- Modelos predictivos de crecimiento económico.
- Series temporales (ARIMA, Prophet y LSTM).
- Modelos de Machine Learning.
- Redes neuronales.
- Dashboards interactivos con Power BI o Tableau.
- Visualizaciones geoespaciales.
- Indicadores de competitividad.
- Comercio internacional.
- Inversión extranjera directa.
- Productividad sectorial.

---

# ✅ Conclusiones

El análisis exploratorio evidencia que América Latina mantiene una elevada sincronización en sus ciclos económicos durante el período 2000–2024.

No obstante, dicha sincronización no implica convergencia económica.

Brasil y México continúan concentrando una parte significativa del Producto Bruto Interno regional, mientras que las economías medianas y pequeñas presentan trayectorias similares, aunque con diferentes niveles de crecimiento.

La matriz de correlación demuestra que la mayoría de los países reaccionan de forma semejante frente a choques internacionales, reforzando la hipótesis de una fuerte dependencia del contexto económico global.

Asimismo, la presencia de una elevada multicolinealidad justifica el uso de técnicas como el **Análisis de Componentes Principales (PCA)** y el **Clustering**, permitiendo identificar factores comunes de crecimiento y bloques económicos con comportamientos homogéneos.

En conjunto, este proyecto muestra cómo el uso de herramientas de Ciencia de Datos puede aportar una comprensión más profunda de la evolución económica latinoamericana, integrando análisis estadístico, visualización e interpretación económica para generar conocimiento útil para investigadores, analistas y responsables de la formulación de políticas públicas.

---

## 👨‍💻 Autor

**Gabriel Mena López**

Ingeniería • Data Analytics • Machine Learning • Comercio Internacional • Agroindustria

**Si este proyecto te resultó útil, considera darle una ⭐ al repositorio.**
