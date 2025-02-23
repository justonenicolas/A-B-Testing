# A-B-Testing
Proyecto desarrollado entorno a los datos de un Test A/B dedicado a generar conclusiones a partir del análisis estadístico de las muestras

## Etapas que componen el proyecto

## Priorización de hipótesis
En esta etapa se realizará la revisión y priorización de las hipótesis de trabajo planteadas por medio de las metodologías RICE y ICE, con el fin de seleccionar las que se consideren más relevantes y asi mismo, generar conclusiones parciales al respecto

## Análisis del Test A/B
Después de haber priorizado las hipótesis de trabajo, se procederá a cargar, corregir y explorar los datos relacionados con el Test A/B para posteriormente realizar un análisis detallado que conduzca a determinar, con base en el desempeño de los grupos, cuál es la recomendación sobre el futuro de la prueba

### Carga y preparación de datos
### Análisis

## Conclusiones generales
---------------

# Descripción de los datos
- **Tabla Hypothesis** (Tabla con calificaciones para los distintos parámetros de priorización):

    - **Hypotheses**: breves descripciones de las hipótesis
    
    - **Reach**: alcance del usuario, en una escala del uno a diez
    
    - **Impact**: impacto en los usuarios, en una escala del uno al diez
    
    - **Confidence**: confianza en la hipótesis, en una escala del uno al diez
    
    - **Effort**: los recursos necesarios para probar una hipótesis, en una escala del uno al diez. Cuanto mayor sea el valor Effort, más recursos requiere la prueba.
    

- **Tabla Orders** (Datos sobre pedidos):

    - **transactionId**: identificador de pedido

    - **visitorId**: identificador del usuario que realizó el pedido

    - **date**: fecha del pedido

    - **revenue**: ingresos del pedido

    - **group**: grupo del test A/B al que pertenece el usuario


- **Tabla Visits** (Registros del servidor con datos sobre las visitas por grupo):

    - **date**: fecha de visita

    - **group**: grupo de la prueba A/B

    - **visits**: el número de visitas en la fecha especificada en el grupo de pruebas A/B especificado
