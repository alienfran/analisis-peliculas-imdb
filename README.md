# Análisis de Datos — IMDB Top 1000

## Descripción
Análisis exploratorio del Top 1000 de películas mejor calificadas en IMDB, quw corresponde a mi
segundo proyecto de portafolio de mi ruta de aprendizaje en análisis de datos.

## Herramientas utilizadas
- Google Sheets
- Funciones: PROMEDIO, MEDIANA, DESVEST, SUSTITUIR, EXTRAE
- Tablas dinámicas
- Histogramas

## Proceso
1. Limpieza de datos (corrección de formato decimal mal interpretado como fecha)
2. Extracción del género principal desde campos de texto multivalor
3. Estadística descriptiva del Rating
4. Tabla dinámica de rating promedio por género, que fue validada con tamaño de muestra
5. Histograma de distribución del Rating

## Hallazgos principales
- El Rating muestra fuerte sesgo a la derecha, ya que nos arroja un 80% de películas entre 8.0 y 8.2
- Crime es el género con mejor rating promedio (8.16) entre los de muestra robusta (+50 películas)
- Western y Horror muestran promedios más altos pero con muestras de solo 3 películas, no representativas

## Archivo
El análisis completo está en el archivo .xlsx adjunto en este repositorio.
