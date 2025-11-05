# FinGraph: Red de Correlaciones Financieras

**FinGraph** es un proyecto personal orientado al análisis de correlaciones entre activos financieros mediante técnicas de clustering y teoría de grafos.  

El objetivo es identificar grupos de empresas con comportamientos similares y analizar su influencia dentro de la red de mercado.

## Características
- Descarga de datos históricos reales con `yfinance`
- Cálculo de rendimientos y matriz de correlación
- Construcción de un grafo financiero con `networkx`
- Agrupamiento automático de empresas mediante `KMeans`
- Análisis de métricas de red: grado, centralidad, coeficiente de agrupamiento
- Visualizaciones limpias y comparativas por clúster
- Estimación de rentabilidad y volatilidad anual por grupo

## Requisitos
Instala las dependencias con:
```bash
pip install -r requirements.txt
