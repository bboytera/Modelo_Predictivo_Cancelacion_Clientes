# 📌Modelo predictivo de cancelación de clientes
  
Predicción
de la tasa de cancelación de clientes de una empresa de telecomunicaciones (Interconnect)


# Introducción
  
Buscamos predecir la tasa de cancelación de los clientes de una empresa de telecomunicaciones llamada Interconnect para anticiparse a posibles bajas. Con esta información; la empresa podrá ofrecer promociones y planes personalizados a los usuarios que muestren señales de querer cancelar sus servicios. Para ello, se han recopilado datos personales y de suscripción de los clientes, lo que permitirá el análisis para desarrollar modelos predictivos que optimicen las estrategias de retención."

El equipo de marketing de Interconnect ha recopilado algunos de los datos personales de sus clientes, incluyendo información sobre sus planes y contratos.

# Descripción de los datos
Los datos consisten en archivos obtenidos de diferentes fuentes:

- `contract.csv` — información del contrato;
- `personal.csv` — datos personales del cliente;
- `internet.csv` — información sobre los servicios de Internet;
- `phone.csv` — información sobre los servicios telefónicos.
que estan en el archivo `datasets_final_provider.csv`
# Habilidades técnicas
- `Python`
-	`Pandas`
-	`Numpy`
-	`Matplotlib`
-	`Scikit-learn`


# Conclusión General
En nuestro proyecto, desarrollamos un modelo para predecir la cancelación de clientes con una precisión del 80%, lo que significa que, en general, el modelo acierta en el 80% de los casos.

El modelo es más efectivo para identificar a los clientes que no cancelarán, con una precisión del 84% Sin embargo, su precisión baja al 65% cuando se trata de predecir a los clientes que sí planean cancelar. que es muy bueno en detectar a los que no cancelarán, con un 90% de éxito, pero menos efectivo para identificar a los que podrían irse, con un 53% de éxito.

Finalmente, el modelo tiene una buena capacidad para diferenciar entre los clientes que se quedan y los que se van, con una puntuación AUC-ROC de 0,8443.

En resumen, este modelo ofrece una herramienta útil para anticipar la cancelación de clientes, aunque hay margen de mejora en la predicción de aquellos que planean irse."

