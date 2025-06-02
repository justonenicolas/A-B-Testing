# 🅰️↔️🅱️ Prueba A/B con priorización de hipótesis
Este proyecto se centra en el análisis estadístico de los resultados de una prueba A/B realizada para una tienda virtual, con el objetivo de determinar si los cambios en la tipografía propuestos por el departamento de marketing generarían un impacto significativo en la conversión de los usuarios. El análisis se enfocó principalmente en la comparación de los volúmenes de conversión, ganancias y pedidos acumulados, valores a partir de los cuales se realizaron las respectivas pruebas de hipótesis y extracción de conclusiones

![Conversion](https://github.com/justonenicolas/A-B-Testing/blob/main/Conversion.JPG)  ![Revenue](https://github.com/justonenicolas/A-B-Testing/blob/main/CumRevenue.JPG)

## 💡 Habilidades destacadas
* Priorización de hipótesis
* Análisis preparatorio de datos
* Análisis estadístico de datos
* Análisis de test A/B
* Visualización de datos

## 🔧 Herramientas y librerías utilizadas
* Pandas
* Numpy
* Scipy
* Seaborn
* Matplotlib

## 📊 Conclusiones generales
* Los datos procesados y sin procesar revelan que la conversión de ambos grupos es significativamente distinta. Esto puede comprobarse a través de las gráficas de conversión, donde se evidencia en ambos escenarios que el grupo B presenta una tasa de conversión 0.5% mayor que la del grupo A en la mayoría de días
* Luego de procesar los datos se evidenció que la diferencia relativa de coversión del grupo B resepcto al A aumentó aproximadamente 6%, pasando de 12.89% a 18.10%
* Los datos procesados y sin procesar demostraron que no existe una diferencia significativa en el tamaño medio de pedidos
* La gráfica procesada de ingresos acumulados demuestra que el grupo B ha mantenido un registro de ingresos superior al del grupo A durante todo el periodo del experimento
* Con base en lo mencionado anteriormente, se recomienda detener el experimento pues se considera que el grupo B ha mostrado un mejor comportamiento a nivel de ingresos y tasa de conversión promedio incluso cuando el promedio de compras diarias suele ser similar o igual al del grupo A
