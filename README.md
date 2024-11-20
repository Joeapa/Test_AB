# Proyecto de AB Testing

Este proyecto tiene como objetivo evaluar la existencia de diferencias significativas entre dos o tres muestras de datos mediante pruebas estadísticas. El enfoque sigue un flujo estructurado que incluye exploración de datos, visualización, formulación de hipótesis, pruebas estadísticas y conclusiones. Además, se aplican pruebas post-hoc en uno de los conjuntos de datos.

## Estructura del Proyecto

1. **Exploración de Datos**
   - Análisis descriptivo de los datos para comprender su distribución y características clave.
   - Identificación de valores duplicados y datos faltantes.

2. **Visualización**
   - Creación de gráficos de barras para representar la distribución de las muestras.

3. **Formulación de Hipótesis**
   - Definición de hipótesis nula (H₀) y alternativa (H₁) para cada conjunto de datos:
     - **H₀**: No hay diferencias significativas entre las muestras.
     - **H₁**: Existen diferencias significativas entre las muestras.

4. **Pruebas Estadísticas**
   - Verificación de supuestos como normalidad y homogeneidad de varianza.
   - Realización de pruebas estadísticas adecuadas al tipo de datos.

6. **Pruebas Post-Hoc**
   - Aplicación de pruebas post-hoc en uno de los conjuntos de datos para analizar diferencias específicas entre grupos.

7. **Conclusiones**
   - Interpretación de los resultados estadísticos.
   - Determinación de la validez de las hipótesis y su implicación para cada conjunto de datos.

## Conjuntos de Datos Utilizados
- Se trabaja con tres conjuntos de datos diferentes relacionados con el análisis web.

## Tecnologías y Herramientas
- Python para análisis de datos, visualización y pruebas estadísticas.
- Bibliotecas utilizadas:
  - `pandas` para manipulación de datos.
  - `matplotlib.pyplot` y `seaborn` para visualización.
  - `scipy.stats` para pruebas estadísticas.
  - `scikit_posthocs` para pruebas post-hoc específicas.
  - `warnings` para ignorar alertas innecesarias y mantener el código limpio.
  - Módulo personalizado `soporte_abtesting` (ubicado en `src`) con funciones específicas desarrolladas para este proyecto.

## Resultados Clave
- Se identificaron diferencias significativas entre muestras en uno o más conjuntos de datos.
- Las pruebas post-hoc permitieron identificar específicamente qué grupos presentan diferencias significativas.

