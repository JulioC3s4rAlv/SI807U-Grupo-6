# Justificación del uso de Datamart y Análisis Prospectivo en la Gestión de la Inversión Pública

La **Subgerencia de Gestión de Inversiones** implica analizar información proveniente de diferentes fuentes del Estado (planes de inversión, presupuestos, ejecución financiera, evaluaciones socioeconómicas, estudios de factibilidad, etc.). Este proceso requiere no solo consolidar datos históricos de manera confiable, sino también anticipar escenarios futuros que orienten la aprobación y priorización de proyectos estratégicos.

---

## 1. Elección de **Datamart** sobre Datawarehouse o Medallion

Se opta por implementar un **Datamart** por las siguientes razones:

- **Enfoque temático y especializado**: un Datamart permite concentrar únicamente los datos relacionados con la **Inversión Pública**, evitando la sobrecarga de un Datawarehouse corporativo que cubriría todas las áreas de la institución.  
- **Menor complejidad y costo**: la arquitectura de un Datawarehouse o un modelo Medallion (Bronze–Silver–Gold) implica altos costos de infraestructura, mayor tiempo de implementación y personal especializado. El Datamart ofrece una solución **ágil y costo-eficiente**, más adecuada al alcance de una entidad estatal.  
- **Velocidad en la toma de decisiones**: los usuarios requieren reportes e indicadores rápidos para aprobar o evaluar proyectos; el Datamart entrega consultas más ligeras y optimizadas, sin necesidad de navegar un repositorio institucional demasiado extenso.  
- **Escalabilidad progresiva**: el Datamart puede ser el primer paso hacia una futura integración con un Datawarehouse central o incluso migrar a un modelo Medallion cuando la institución madure en gobernanza de datos.  

En este contexto, el **Datamart de Inversión Pública** se convierte en una **fuente única de verdad** para la información relacionada con proyectos, presupuestos, cronogramas y evaluaciones de una sola área de la organización.

---

## 2. Justificación del Análisis Prospectivo

La evaluación tradicional de proyectos de inversión suele centrarse en los **datos históricos y presentes** (ejecución presupuestal, indicadores socioeconómicos, cronogramas). Sin embargo, para mejorar la eficiencia y pertinencia de la inversión, es necesario incorporar un **enfoque prospectivo**, el cual permite **anticipar escenarios futuros**.

El análisis prospectivo se justifica por:

- **Anticipación de riesgos y brechas**: prever retrasos, sobrecostos o problemas en la ejecución a partir de patrones detectados en proyectos pasados.  
- **Optimización de priorización**: estimar el impacto futuro de un proyecto (social, económico, territorial) antes de su aprobación, permitiendo asignar recursos de manera más eficiente.  

---

## Conclusión

La combinación de un **Datamart especializado en Inversión Pública** puede incluir un componente de **análisis prospectivo basado en machine learning** proporcionando a la organización una herramienta robusta para:

- Centralizar y simplificar el acceso a datos relevantes para una sola área. 
- Reducir tiempos de evaluación de proyectos.  
- Mejorar la transparencia y la toma de decisiones estratégicas.  

De esta forma, se garantiza que los los procesos de toma de decisiones se realicen de forma más ágil acorde con las políticas de desarrollo sostenible y eficiencia del gasto público.
