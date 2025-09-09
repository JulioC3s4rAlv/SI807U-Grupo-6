# SI807U-Grupo-6
Repositorio de trabajo para el cursos de Sistemas de Inteligencia de Negocio
# Justificación del proyecto: Sistema de Inteligencia de Negocios para la Empresa X del Estado

En la **Contraloría General de la República** la información clave de los distintos proyectos para generar o mejorar los servicios de los diferentes organismos del estado proviene principalmente del Ministerio de Economía y Finanzas (MEF); sin embargo, debido a la diversificación de la información y sus fuentes la generación de reportes es mayormente manual, lenta y con duplicidad de cifras, lo que limita la oportunidad y la calidad de las decisiones, así como la rendición de cuentas.

El proyecto propone implementar un **sistema de inteligencia de negocios (BI)** que consolide datos mediante procesos **ETL** hacia un **Datamart** institucional (fuente única de la verdad). Desde este repositorio se habilitarán dos capacidades: **tableros ejecutivos** para la toma de decisiones y **evaluación prospectiva** (analítica predictiva) para anticipar demanda, riesgos y desempeño programático.

La iniciativa se alinea con la **Política Nacional de Modernización de la Gestión Pública**, los principios de **Gobierno Abierto** y la **Transformación Digital**, al fortalecer la gestión basada en evidencia, la transparencia y la interoperabilidad con otras entidades del Estado. Asimismo, facilita el seguimiento del **PEI/POI**, la ejecución presupuestal y los compromisos de servicios a la ciudadanía.

---

## Beneficios esperados

- **Oportunidad y precisión**: reducción drástica del tiempo de preparación de reportes y eliminación de inconsistencias entre áreas.  
- **Trazabilidad y control**: gobierno de datos, catálogos y auditoría del ciclo de vida de la información.  
- **Mejor decisión pública**: tableros con indicadores críticos (finanzas, operación, calidad del servicio, cumplimiento) y alertas tempranas.  
- **Prospectiva y eficiencia**: modelos que anticipen brechas de atención, riesgos de sobrecosto o subejecución y prioricen intervenciones.  
- **Transparencia**: insumos para portales de consulta y reportes de rendición de cuentas.  

---

## Alcance y entregables

- Arquitectura de datos y **procesos ETL automatizados** desde fuentes internas y externas.  
- **Datamart** temático documentado (diccionario, linaje, reglas de calidad).  
- **Dashboards** ejecutivos y operativos con control de acceso y actualización programada.  
- **Módulos analíticos** de evaluación prospectiva (pronósticos/segmentación/alertas).  
- **Gobernanza de datos**: políticas acorde al tipo de datos  

---

## Riesgos y mitigaciones

- **Calidad de datos** → reglas de validación en ETL y responsabilidades claras.  
- **Resistencia al cambio** → pilotos, formación y acompañamiento.  
- **Interoperabilidad** → uso de estándares y APIs; cronograma por oleadas.  

---

### Conclusión

El sistema BI convertirá los datos de la Contraloría General de la República en un **activo estratégico**, habilitando decisiones oportunas, políticas públicas mejor focalizadas y mayor valor para la ciudadanía, con un esquema técnicamente sólido (**ETL → Datamart → Dashboards/Analítica**) y gobernado para perdurar.

---

## Planteamiento de KPIs
#### Variación Prespuestal
**Concepto**: 
**Fórmula:** Variación presupuestal= (Presupuesto inicial-final) de cada proyecto
#### Ratio de Ejecución de Proyecto
**Concepto**: 
**Fórmula:** % de ejecución presupuestal = (Monto ejecutado / Monto presupuestado) × 100.
#### Etapa ponderada de DEMORA
**Concepto**: Etapa en la que se identificó un cuello de botella
**Fórmula:** Etapa ponderada de DEMORA = Etapa de Proyecto * Monto Asignado / Monto Presupuestado Total
