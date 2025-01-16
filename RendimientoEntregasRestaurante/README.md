# Proyecto de Gestión de Pedidos en Food & Drinks


## **Introducción**

El presente proyecto tiene como finalidad el análisis logístico de las entregas en el restaurante Food & Drinks, específicamente en la eficiencia de los envíos a tiempo y en las demoras. Este requerimiento surge de la necesidad crítica de mejorar los tiempos de entrega y la satisfacción del cliente en un mercado donde la puntualidad y calidad del servicio son factores determinantes para el éxito operativo. La implementación de este proyecto permitirá a los interesados en el negocio tomar decisiones fundamentadas para optimizar los procesos de entrega y mejorar la experiencia del cliente.

## **Contexto**
El servicio de delivery en Food & Drinks enfrenta desafíos significativos que impactan directamente en la rentabilidad y satisfacción del cliente. Este servicio se ha convertido en un componente importante del negocio, en el cual la optimización de los tiempos de entrega y la eficiencia operativa son factores críticos para su sostenibilidad.

## 📊 Alcance del Proyecto

El siguiente proyecto contiene los siguientes desarrollos:

- Limpieza de los datos a través de Python 
- Análisis y creación del informe en Power BI

## **Datos**

Los datos utilizados para este proyecto de análisis, estan en el siguiente [enlace de descarga](https://drive.google.com/drive/folders/1q_CB6sNsFPNmGh2QgZQtZshCPA8vMTyt?usp=sharing)


## **DESARROLLO DEL PROYECTO ** :

## **1. Etapa del proceso ETL** :
- Etapa realizada con el lenguaje Python
- Carga del archivo base con extensión xlsx
- Luego se realizó el trabajo Extracción y Transformación de los datos. Se hicieron diversas transformaciones cumpliéndose con la estandarización de los datos se revisaron nulos,duplicados, se eliminaron columnas redundantes, entre otras tareas.

## **2. Análisis de Datos**

<p align=center>
<img src="src\dashboard001.png" height="425" weight="500">
</p>

Se observa una baja significativa en las entregas puntuales, pasando de 71.65% en enero a un alarmante 18.74% en abril. 
El tiempo promedio de entrega se ha incrementado en los meses de febrero, marzo y abril considerablemente, paso de 43 minutos en enero a 95 minutos en abril. 

<p align=center>
<img src="src\dashboard002.png" height="400" weight="450">
</p>
La puntualidad ha caído drásticamente de tener 13 mil entregas en enero a 3.4 mil en abril. Las entregas tardías aumentaron de 5.1 mil a 14.7 mil. El promedio general muestra que el 52% de las entregas son tardías, una cifra alarmante para el rubro. El volumen de pedidos se mantiene constante lo que daría a entender que el problema no es por aumento de demanda, sino operativo. 

<p align=center>
<img src="src\dashboard003.png" height="400" weight="450">
</p>

La mayor parte de las ganancias (84.25%) se generan en el turno de la mañana. Los miércoles y jueves muestran picos de ganancia.
<p align=center>
<img src="src\dashboard003.png" height="400" weight="450">
</p>

Las mayores ganancias se concentran entre las 00:00-04:00 horas y existe una caída significativa después de las 05:00.  
Los días 3, 12, 23 y 29 muestran picos de ganancia mientras que se observan caídas notables los días 4, 14, 24 y 31. 

## **4. Dashboard**
El dashboard desarrollado se encuentra en el siguiente enlace [Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMDUwNDlmYTktY2JmMS00NmI3LWFkYTUtOWY4NjcxMjliOWVlIiwidCI6ImM0YTY2YzM0LTJiYjctNDUxZi04YmUxLWIyYzI2YTQzMDE1OCIsImMiOjR9)



