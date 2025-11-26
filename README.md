# Proyecto final

- No usen chatgpt
- Crea un fork de este repositorio y agregale _nombre donde nombre es tu nombre para que puedas entregar la liga del repositorio.
- Los datos se encuentran en el link: https://drive.google.com/drive/folders/106hrTwEGPvbAWKYNCwP-Dw90nLCwrF0V?usp=sharing , selecciona un año y que no se repita entre tus compañeros.
- 430 puntos en total


## Fecha de entrega

3 de diciembre, miércoles, 4 pm


Para el proyecto final tendrás que realizar lo siguiente:

1. Limpiar el conjunto de datos de un año meteorológico del IER  (55 puntos)
    - Importar los datos con tipos adecuados y fecha en formato datetime y en indice (30 puntos)
    - Identificar datos faltantes (10 puntos)
    - Exportar en formato parquet (5 puntos)
    - Documentar proceso de importación, limpiza (10 puntos)

2. Crear una clase que haga lo siguiente  (45 puntos)
    - Cargue un parquet con datos meteorologicos y renombre aceptando un diccionario columnas de acuerdo a lo siguiente (20 puntos)
        - Ig para la radiación solar global 
        - Id para la radiación solar difusa
        - Ib para la radiación solar directa
        - ws para wind speed
        - wd para dirección del viento
        - To para la temperatura exterior
        - rh para la humedad relativa
        - P para la presión atmosférica
    - Cargue los datos y guarde como una propiedad el inicio y final de los datos (10 puntos)
    - reporte la cantidad de datos al cargarlos (10 puntos)
    - tenga una propiedad llamada "columnas" que regrese las columnas con el nombre que tengan (5 puntos)

3. Tenga un método que (40 puntos)
    - Haga una gráfica con valores mensuales que de una columna muestre 
        - valor promedio (10 puntos)
        -  n-veces la desviación estándard, especificada por quien usa la función, con un default n=1 (20 puntos)
        - visualice los valores máximos y mínimos mensuales si quien usa la función lo especifica, default no (10 puntos)
    
4. Tenga un método que (70 puntos)
    - Visualice en el intervalo de un dia, una linea por cada día que contenga la serie temporal de la columna seleccionada por quien usa la función (40 puntos)
    - regrese, si lo especifica quien usa la función, la serie temporal en un df con el indice como datetime (30 puntos)
     

5. Tenga un método que (40 puntos)
    - Visualice un mapa de calor de la columna especificada y que por default sea la temperatura To (30 puntos)
    - regrese, si lo especifica quien usa la función, la serie temporal un df de los datos (10 puntos)

6. Tenga un método que (70 puntos)
    - Calcule la energía de cada una de las componentes de la radiación solar para todo el periodo de tiempo del conjunto de datos o de un periodo específico si se indica, mediante los argumentos "inicio", "fin" (30 puntos)
    - Regrese un dataframe si se especifica (10 puntos)
    - Haga una gráfica de barras de las componentes de la radiación solar del periodo especificado e indique el periodo en la gráfica (30 puntos)

7. Documentado con instrucciones por función, tipado y con una narrativa adecuada (50 puntos)

8. Documentado en github utilizando uv, con un conjunto de datos que no sobrepase los 100 MB por archivo y publico (30 puntos)

    
9. La clase debe estar implementada como un paquete local (30 puntos)




