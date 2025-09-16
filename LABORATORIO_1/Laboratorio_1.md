# 1. Instalación de Hortonworks Sandbox en VirtualBox

### 1.1. Requisitos y Software requerido
El dispositivo usado cuenta con los requisitos mínimos:
- **Sistema Operativo:** Windows, macOS o Linux  
- **CPU:** Al menos 4 núcleos  
- **Memoria RAM dedicada al clúster:** Mínimo 8 GB  
- **Almacenamiento:** 65 GB de espacio libre en disco como mínimo    

Se procedió a descargar el Hortonworks Data Platform:
<p align="center">
   <img src="IMAGENES/Descarga.png" alt="Descarga" width="600">
</p>

### 1.2. Importación del HDP Sandbox
Acorde a lo explicado se procedió a importar el OVA descargado:
<p align="center">
   <img src="IMAGENES/Captura_1.png" alt="Importar OVA" width="600">
</p>

### 1.3. Configuración de red
<p align="center">
   <img src="IMAGENES/Captura_2.png" alt="Configuración de red" width="600">
</p>

### 1.4. Primer arranque de la VM 
<p align="center">
   <img src="IMAGENES/Captura_3.png" alt="Inicio de Ambari" width="600">
   <img src="IMAGENES/Captura_4.png" alt="Inicio de Ambari" width="600">
</p>

### 1.5. Cambiar la contraseña del usuario `root` 
<p align="center">
   <img src="IMAGENES/Captura_5.png" alt="Inicio de Ambari" width="600">
</p>

### 1.6. Verificación del usuario por defecto:  
   - **Usuario:** `maria_dev`  
   - **Contraseña:** `maria_dev`
<p align="center">
   <img src="IMAGENES/Captura_6.png" alt="Inicio de Ambari" width="600">
   <img src="IMAGENES/Captura_7.png" alt="Inicio de Ambari" width="600">
</p>

### 1.7. Verificar que los servicios principales estén activos:  
   - HDFS  
   - YARN  
   - Hive  
   - Spark  
   - Zeppelin
<p align="center">
   <img src="IMAGENES/validacion_tools.png" alt="Servicios activos" height="500">
</p>

### 1.8. Comprobación inicial
<p align="center">
   <img src="IMAGENES/lista_hdfs.png" alt="Validacion" height="300">
</p>

---
# 2. EXPLORANDO AMBARI
### 1. Dashboards
La pantalla inicial de Ambari muestra un **DASHBOARD** con información predeterminada:
<p align="center">
   <img src="IMAGENES/Captura_7.png" alt="Inicio de Ambari" height="300">
</p>

### 2. HOSTS
En el apartado HOSTS se pueden observar los nodos en los cuales se podría operar:
<p align="center">
   <img src="IMAGENES/Captura_8.png" alt="Exploracion" height="300">
</p>

### 3. ALERTAS
En la pantalla de ALERTAS al inciio se muestran todos los elementos en alerta **CRÍTICA** pero esto se corrige luego de un tiempo en el que se termina de configurar:
<p align="center">
   <img src="IMAGENES/Captura_9.png" alt="Exploracion" height="300">
</p>

---
# 3. PRUEBA INICIAL CON ARCHIVO
### 3.1. Subida del archivo 
Usando la interfaz propia de Ambari se realizó la carga del archivo `test_flights` al sistema:
<p align="center">
   <img src="IMAGENES/Captura_10.png" alt="Archivo" height="300">
   <img src="IMAGENES/Captura_11.png" alt="Archivo" height="300">
</p>

Preview del archivo en el entorno de Ambari:
<p align="center">
   <img src="IMAGENES/Captura_12.png" alt="Archivo" height="300">
</p>

Posteriormente se generó la Tabla que recepcionará la información del archivo y se cargaron los datos:

<p align="center">
   <img src="IMAGENES/Captura_13.png" alt="Archivo" height="300">
</p>

### 3.2. Exploración Inicial del Archivo
Usando la herramienta de `Query` se realizó la consulta de llamado a los datos del archivo:
<p align="center">
   <img src="IMAGENES/Captura_14.png" alt="Archivo" height="300">
</p>

Se obtuvo el siguiente resultado:
<p align="center">
   <img src="IMAGENES/Captura_15.png" alt="Archivo" height="300">
</p>
