<h1 align=center>PIDA SiniestrosViales CABA</h1>


El proyecto "PIDA SiniestrosViales CABA" es el segundo de los proyectos integradores finales del Bootcamp de Data Science de Henry. El proyecto se centra en los datasets que cubren información sobre accidentes fatales en la Ciudad Autónoma de Buenos Aires entre los años 2016 y 2021. El objetivo principal de este proyecto fue realizar un análisis profundo de los datos.# Directory Details

- **datasets/**
  _La carpeta datasets esta subdividida en dos sub-carpetas_

   **procesados/**

    **homicidios.csv:** Data procesada sobre homicidios en accidentes viales en CABA.

    **homicidios_avenidas:** Data procesada sobre homicidios específicamente en avenidas, utilizada para calcular KPI.

    **homicidios_moto:** Data procesada sobre homicidios específicamente de víctimas en motocicletas, utilizada para calcular KPI.

    **homicidios_semestres:** Data procesada sobre homicidios clasificada por semestres, utilizada para calcular KPI.


   **originales/**

    **homicidios.xlsx:** Data original sobre homicidios en accidentes viales en CABA.

    **NOTAS_HOMICIDIOS_SINIESTRO_VIAL.pdf:** información complementaria.

_La subcarpeta "originales" incluye los datos sobre homicidios proporcionados por Henry para el análisis, mientras que la subcarpeta "procesados" contiene los dataframes resultantes del proceso EDA y ETL._
- **.gitignore:** Archivo para especificar archivos y directorios no rastreados que Git debería ignorar.

- **EDA.ipynb:** Jupyter Notebook para Exploratory Data Analysis.

- **ETL.ipynb:** Jupyter Notebook que se concentra únicamente en extraer y transformar los datos necesarios en relación a la población de CABA para los años de 2016 a 2021.

- **KPIs.ipynb:** Jupyter Notebook para el cálculo de 3 indicadores clave de desempeño sobre accidentes en CABA.

---

# **EDA**

El EDA realizado sobre el conjunto de datos de accidentes de tránsito en la Ciudad Autónoma de Buenos Aires (CABA) proporciona información valiosa sobre las tendencias y factores que contribuyen a estos accidentes.

**Principales hallazgos**

Los principales hallazgos del EDA son los siguientes:

* **Los accidentes de tránsito son más comunes en las primeras horas de la mañana, tanto en avenidas como en calles.** Esto se debe a una serie de factores, como el tráfico intenso, la fatiga de los conductores y la distracción.
* **Los accidentes entre vehículos motorizados y peatones son los más comunes, representando el 37,37% del total.** Los peatones son los usuarios más vulnerables de la carretera y los que más probabilidades tienen de sufrir lesiones o la muerte en un accidente.
* **Las motocicletas son los vehículos más involucrados en accidentes viales, con una participación del 42,75%.** Esto se debe a que las motocicletas son más vulnerables a las colisiones y a que los conductores de motocicletas suelen tener menos experiencia que los conductores de otros vehículos.
* **La comuna 1 tiene la mayor cantidad de accidentes, con un total de 90.** Las comunas 4, 8, 9 y 15 también tienen una cantidad significativa de accidentes.

**Implicaciones para la seguridad vial**

Los hallazgos del EDA tienen implicaciones importantes para la seguridad vial. Por ejemplo, sugieren que es importante tomar medidas para reducir el tráfico en las primeras horas de la mañana, para aumentar la concienciación sobre los peligros de los peatones y las motocicletas, y para mejorar la seguridad de las avenidas.

**Recomendaciones para futuros análisis**

Los siguientes son algunos consejos para futuros análisis de los datos de accidentes de tránsito:

* **Se podría agregar información sobre las condiciones climáticas y el estado de la carretera.** Esto podría ayudar a comprender mejor los factores que contribuyen a los accidentes.
* **Se podría analizar la información sobre los conductores involucrados en los accidentes.** Esto podría ayudar a identificar factores de riesgo específicos, como el consumo de alcohol o drogas.
* **Se podría utilizar información de seguimiento para evaluar la eficacia de las medidas de seguridad vial.** Esto podría ayudar a garantizar que las medidas estén teniendo el efecto deseado.


