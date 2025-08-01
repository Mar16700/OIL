# OIL
El proyecto busca identificar las mejores ubicaciones para abrir 200 nuevos pozos de petróleo para la compañía OilyGiant, utilizando datos geológicos de tres regiones diferentes. Para ello, se entrenan modelos de regresión lineal en Python para predecir el volumen de reservas de petróleo en pozos nuevos.

El proceso incluye ajustar las predicciones para que el volumen medio esperado coincida con un valor deseado (111.2) mediante un factor de corrección calculado con numpy. Posteriormente, se guardan las predicciones junto con los valores reales para su análisis posterior.

Finalmente, se evalúa el desempeño del modelo con métricas clave, como el RMSE (Raíz del Error Cuadrático Medio), que en este caso fue aproximadamente 43.32, indicando la precisión de las predicciones.

El proyecto también contempla el uso de técnicas estadísticas como bootstrapping para evaluar riesgos y seleccionar la región óptima que maximice las ganancias y minimice pérdidas.

Tecnologías usadas:

Python (principal lenguaje de programación)

Librerías como numpy para cálculos numéricos,

pandas para manipulación de datos,

y scikit-learn para modelado y evaluación estadística.
