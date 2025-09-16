# Instalación de Hortonworks Sandbox en VirtualBox


---

## Requisitos mínimos

- **Sistema Operativo:** Windows, macOS o Linux  
- **CPU:** Al menos 4 núcleos  
- **Memoria RAM dedicada al clúster:** Mínimo 8 GB  
- **Almacenamiento:** 65 GB de espacio libre en disco como mínimo    

---

## Software requerido

![Descarga](INSTALACION_ENTORNO/Descarga.png)

---

## 1. Instalación de VirtualBox

![Instalación de VirtualBox](ruta/a/imagen1.png)

---

## 2. Importación del HDP Sandbox

![Importar OVA](ruta/a/imagen2.png)

4. Asignar recursos recomendados:

![Importar OVA](ruta/a/imagen2.png)

5. Finalizar y esperar a que se complete la importación  

![Configuración de recursos](ruta/a/imagen3.png)

---

## 3. Configuración de red

![Configuración de red](ruta/a/imagen4.png)

4. Guardar cambios

![Configuración de red](ruta/a/imagen4.png)

---

## 4. Primer arranque de la VM 

![Inicio de Ambari](ruta/a/imagen5.png)

4. Cambiar la contraseña del usuario `root` 

![Inicio de Ambari](ruta/a/imagen5.png)

5. También puedes usar el usuario por defecto:  
   - **Usuario:** `maria_dev`  
   - **Contraseña:** `maria_dev`

![Inicio de Ambari](ruta/a/imagen5.png)


6. Verificar que los servicios principales estén activos:  
   - HDFS  
   - YARN  
   - Hive  
   - Spark  
   - Zeppelin

![Servicios activos](ruta/a/imagen6.png)

---

## 5. Comprobación inicial

Puedes realizar algunos comandos desde la terminal de la VM o usando el WebShell Client:

```bash
# Listar archivos en HDFS
hdfs dfs -ls /

# Ver versión de Spark
spark-shell --version

# (Opcional) Reiniciar contraseña de Ambari
ambari-admin-password-reset
