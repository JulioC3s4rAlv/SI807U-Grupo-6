# 1. Instalación de Hortonworks Sandbox en VirtualBox


---

## Requisitos mínimos

- **Sistema Operativo:** Windows, macOS o Linux  
- **CPU:** Al menos 4 núcleos  
- **Memoria RAM dedicada al clúster:** Mínimo 8 GB  
- **Almacenamiento:** 65 GB de espacio libre en disco como mínimo    

---

## Software requerido
![Descarga](Descarga.png)

---

## 1. Instalación de VirtualBox

### Ya se contaba con el VirtualBox Instalado

---

## 2. Importación del HDP Sandbox

![Importar OVA](Captura_1.png)

4. Asignar recursos recomendados:

Falta Evidencia

---

## 3. Configuración de red

![Configuración de red](Captura_2.png)

---

## 4. Primer arranque de la VM 

![Inicio de Ambari](Captura_3.png)
![Inicio de Ambari](Captura_4.png)

4. Cambiar la contraseña del usuario `root` 

![Inicio de Ambari](Captura_5.png)


5. También puedes usar el usuario por defecto:  
   - **Usuario:** `maria_dev`  
   - **Contraseña:** `maria_dev`

![Inicio de Ambari](Captura_6.png)
![Inicio de Ambari](Captura_7.png)


6. Verificar que los servicios principales estén activos:  
   - HDFS  
   - YARN  
   - Hive  
   - Spark  
   - Zeppelin

![Servicios activos](validacion_tools.png)

---

## 5. Comprobación inicial

![Validacion](lista_hdfs.png)

---
# 2. EXPLORANDO AMBARI
## Dashboards
![Inicio de Ambari](Captura_7.png)
## HOSTS
![Exploracion](Captura_8.png)
## ALERTAS
![Exploracion](Captura_9.png)

---
# 3. Subida del archivo
![Archivo](Captura_10.png)
![Archivo](Captura_11.png)
![Archivo](Captura_12.png)
