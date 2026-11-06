# Ejercicio Estimación de Pi con Hadoop MapReduce

**Equipo 5**

## Objetivo
Ejecutar el algoritmo de cálculo de Pi en Hadoop variando el número de Mappers y el número de muestras por Mapper para observar cómo influye en la precisión del resultado.

## Requisitos
- Tener en ejecución el contenedor de Docker con Hadoop 3.3.6 (`hadoop`).

## Instrucciones
1. Entra al contenedor de Docker con el usuario `hadoop`:
   ```bash
   docker exec -it hadoop su - hadoop
hadoop jar $HADOOP_HOME/share/hadoop/mapreduce/hadoop-mapreduce-examples-3.3.6.jar pi 8 2000
