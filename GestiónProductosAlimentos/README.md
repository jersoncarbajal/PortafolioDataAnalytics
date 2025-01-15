# Proyecto Rotación de Produstos 

## **Introducción**

El presente proyecto se desarrolla bajo el perfil de un Data Analyst y tiene como objetivo la elaboración de un dashboard sobre la rotación de productos para la Alimentos S.A. Este proyecto busca proporcionar una solución accesible y efectiva para el seguimiento de productos vendidos, por vencer y vencidos. La implementación del dashboard no solo permitirá tomar decisiones estratégicas sobre la rotación de productos, sino que también facilitará la optimización del inventario, reduciendo pérdidas por caducidad de los productos.


## 📊 Alcance del Proyecto

El siguiente proyecto contiene los siguientes desarrollos:

- Macros para la creación de dimensiones, limpieza de los datos con Power Query y Power Pivot para el modelo. 
- Análisis y Creación del Dashboard con Excel.

## **Datos**

Los datos utilizados para este proyecto de análisis, estan en el siguiente [enlace de descarga](https://docs.google.com/spreadsheets/d/1YtzxUmVJH8QCahaZhRGZ6MF3mbRS4xSP/edit?usp=sharing&ouid=115793885910200133810&rtpof=true&sd=true)


## **DESARROLLO DEL PROYECTO ** :

## **1. Etapa del proceso ETL** :
- Creación de las dimensiones con macros a partir del conjunto de datos.
- Se realizó la limpieza de datos y se hicieron diversas transformaciones con Power Query cumpliéndose con la estandarización de los datos.

## **2. Modelado de Datos** :
- Se creó el modelo de datos con Power Pivot.

## **3. Análisis de Datos (Dashboard)**

<p align=center>
<img src="src\dashboard.png" height="425" weight="500">
</p>

*Métricas Globales:*
Se evidencia una situación crítica en la gestión de productos donde el 22% de los productos se encuentran en situación de riesgo, dividido entre un 19% próximos a vencer (558 unidades) y un 3% ya vencidos (92 unidades), lo cual representa una amenaza para la rentabilidad de la empresa.

*Análisis temporal:*
El año inició en enero con una composición de 70% de productos por vencer y 15% de productos vencidos, situación que empeoró en febrero alcanzando un 80% de productos por vencer y disminuyendo a 8% los productos vencidos. Este fue el punto más crítico del periodo analizado en términos de productos por vencer.

Se observa una mejora relativa en los meses subsiguientes, con marzo mostrando una reducción a 55% de productos por vencer y 11% de vencidos. Esta tendencia de mejora continuó hasta abril, donde los productos por vencer representaron un 42% y los vencidos un 10%. Sin embargo, en mayo se mostró un retroceso aumentando a 62% los productos por vencer, aunque con una ligera mejora en vencidos (8%). El período de junio a octubre mostró una alta volatilidad: comenzó con el mejor rendimiento en junio (42% total de productos en riesgo), seguido por un deterioro significativo en julio (85% en riesgo), para finalmente mostrar una recuperación gradual hasta octubre, cerrando con solo 28% de productos en riesgo.


*Distribución por Canal:*
Los supermercados regionales y grandes cuentas presentan el mayor volumen de ventas mientras que los demás canales muestran un bajo rendimiento. 
Los canales "Minimercados" y "Superetes" muestran un rendimiento inferior al esperado, sugiriendo oportunidades de mejora.

*Comportamiento Regional:*
La gestión de 41 ciudades por solo 5 supervisores sugiere una sobrecarga operativa que afecta la eficiencia.

*Análisis por Sucursal:*

## **4. Conclusión:** 
La situación actual muestra un problema sistémico en la gestión de inventarios y distribución. El 22% combinado de productos vencidos y próximos a vencer requiere acción inmediata. La estructura actual con 5 supervisores para 41 ciudades puede estar contribuyendo a la ineficiencia operativa. Se recomienda una intervención inmediata enfocada en los canales de mayor riesgo y una reestructuración del sistema de distribución a mediano plazo.

## **5. Recomendaciones**
- Implementar un plan para la gestión de los 558 productos próximos a vencer.
- Investigar el éxito de la región Occidente y Santander para replicar mejores prácticas
- Establecer alertas tempranas para los productos con baja rotación.
- Desarrollar promociones para generar ventas (combos, ofertas, etc.) 
- Balancear cargas de supervisores.
- Implementar sistema de incentivos basado en rotación efectiva.


