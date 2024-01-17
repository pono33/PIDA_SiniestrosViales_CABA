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
- **.gitignore:** File to specify untracked files and directories that Git should ignore.

- **EDA.ipynb:** Jupyter Notebook para Exploratory Data Analysis.

- **ETL.ipynb:** Jupyter Notebook que se concentra únicamente en extraer y transformar los datos necesarios en relación a la población de CABA para los años de 2016 a 2021.

- **KPIs.ipynb:** Jupyter Notebook para el cálculo de 3 indicadores clave de desempeño sobre accidentes en CABA.

