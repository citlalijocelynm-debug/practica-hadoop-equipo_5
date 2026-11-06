# Solución del Ejercicio

## Comandos de Ejecución

```bash
# 1. Acceso al contenedor
docker exec -it hadoop su - hadoop

# 2. Ejecución del job MapReduce con 8 Mappers y 2000 muestras
hadoop jar $HADOOP_HOME/share/hadoop/mapreduce/hadoop-mapreduce-examples-3.3.6.jar pi 8 2000
