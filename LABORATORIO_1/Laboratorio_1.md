# 1. Instalación de Hortonworks Sandbox en VirtualBox

## 1.1. Requisitos y Software requerido
El dispositivo usado cuenta con los requisitos mínimos:
- **Sistema Operativo:** Windows, macOS o Linux  
- **CPU:** Al menos 4 núcleos  
- **Memoria RAM dedicada al clúster:** Mínimo 8 GB  
- **Almacenamiento:** 65 GB de espacio libre en disco como mínimo    

Se procedió a descargar el Hortonworks Data Platform:
![Descarga](IMAGENES/Descarga.png)

## 1.2. Importación del HDP Sandbox

![Importar OVA](IMAGENES/Captura_1.png)

## 1.3. Asignar recursos recomendados:

Falta Evidencia

## 1.4. Configuración de red

![Configuración de red](IMAGENES/Captura_2.png)

## 1.5. Primer arranque de la VM 

![Inicio de Ambari](IMAGENES/Captura_3.png)
![Inicio de Ambari](IMAGENES/Captura_4.png)

## 1.6. Cambiar la contraseña del usuario `root` 

![Inicio de Ambari](IMAGENES/Captura_5.png)


## 1.7. Verificación del usuario por defecto:  
   - **Usuario:** `maria_dev`  
   - **Contraseña:** `maria_dev`

![Inicio de Ambari](IMAGENES/Captura_6.png)
![Inicio de Ambari](IMAGENES/Captura_7.png)

## 1.8. Verificar que los servicios principales estén activos:  
   - HDFS  
   - YARN  
   - Hive  
   - Spark  
   - Zeppelin

![Servicios activos](IMAGENES/validacion_tools.png)

## 1.9. Comprobación inicial

![Validacion](IMAGENES/lista_hdfs.png)

---
# 2. EXPLORANDO AMBARI
## 1. Dashboards
![Inicio de Ambari](IMAGENES/Captura_7.png)
## 2. HOSTS
![Exploracion](IMAGENES/Captura_8.png)
## 3. ALERTAS
![Exploracion](IMAGENES/Captura_9.png)

---
# 3. Subida del archivo
![Archivo](IMAGENES/Captura_10.png)
![Archivo](IMAGENES/Captura_11.png)
![Archivo](IMAGENES/Captura_12.png)
