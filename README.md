# Limpieza de Datos de Taxis de la Ciudad de Nueva York

Este repositorio contiene el código y la documentación del proceso de limpieza de un conjunto de datos de viajes en taxi de la Ciudad de Nueva York (NYC). El objetivo principal de este proyecto es preparar los datos para su posterior análisis, modelado o visualización, garantizando su calidad y coherencia.

## Descripción del Proyecto

El conjunto de datos de taxis de NYC es una fuente rica en información sobre los patrones de transporte, la demanda y otros aspectos relacionados con los viajes en taxi en la ciudad. Sin embargo, como cualquier conjunto de datos del mundo real, a menudo contiene inconsistencias, valores faltantes, valores atípicos y otros problemas que pueden afectar la calidad de cualquier análisis posterior.

Este proyecto aborda estos problemas mediante un proceso sistemático de limpieza de datos. Las etapas clave incluyen:

* **Carga y Exploración Inicial:** Cargar el conjunto de datos y realizar una exploración inicial para comprender su estructura, tipos de datos y posibles problemas.
* **Manejo de Valores Faltantes:** Identificar y tratar los valores faltantes utilizando estrategias apropiadas (eliminación, imputación, etc.).
* **Detección y Tratamiento de Valores Atípicos:** Identificar y manejar valores atípicos que puedan distorsionar el análisis. Esto podría implicar la eliminación o la transformación de estos valores.
* **Corrección de Tipos de Datos:** Asegurar que las columnas tengan los tipos de datos correctos para facilitar el análisis.
* **Estandarización y Formateo:** Estandarizar formatos de fechas, horas y otras variables para garantizar la coherencia.
* **Creación de Nuevas Características (Opcional):** Derivar nuevas variables que puedan ser útiles para el análisis (por ejemplo, duración del viaje, distancia en línea recta, día de la semana, hora del día).
* **Eliminación de Datos Irrelevantes o Duplicados:** Identificar y eliminar columnas que no son relevantes para el análisis o filas que representan duplicados.
* **Validación de la Limpieza:** Verificar la calidad de los datos limpios mediante pruebas y visualizaciones.

## Conjunto de Datos

El conjunto de datos utilizado en este proyecto proviene de un CSV, estos conjuntos de datos contienen información como:

* ID del viaje
* ID del vehículo
* ID del conductor
* Fecha y hora de recogida
* Fecha y hora de entrega
* Ubicación de recogida (latitud y longitud o ID de zona)
* Ubicación de entrega (latitud y longitud o ID de zona)
* Número de pasajeros
* Distancia del viaje
* Tiempo de viaje
* Tarifa base
* Impuestos
* Recargo
* Propina
* Peaje
* Tarifa total
* Método de pago

## Estructura del Repositorio
