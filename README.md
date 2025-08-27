<div style="background-color: #e6f2ff; padding: 15px; border-radius: 5px; border-left: 4px solid #0066cc; margin-bottom: 20px;"> <strong>Descripción General</strong> <p>Este proyecto es un <strong>laboratorio educativo</strong> para aprender a diseñar, simular y evaluar una <strong>cadena de suministro automotriz</strong> usando <strong>Python</strong> y <strong>datos sintéticos</strong>.</p> <p>Tomamos como referencia un caso tipo <em>Stellantis</em> y lo llevamos paso a paso, aplicando conceptos de <strong>Logística, Analítica de Datos y Ciencia de Datos</strong>.</p> <p>El objetivo no es solo programar, sino <strong>entender cómo la tecnología puede transformar la logística moderna</strong>.</p> </div>



##  Objetivo Didáctico
Que los alumnos aprendan a:
- Leer, limpiar y analizar datos logísticos.
- Calcular **KPIs clave** (OTIF, Fill Rate, Lead Time).
- Diseñar y simular **redes de distribución y almacenes**.
- Resolver problemas de transporte con optimización.
- Crear un flujo **ETL + Mini-DB** y desplegar un **dashboard interactivo** en Streamlit.
- Presentar hallazgos con un enfoque profesional.

---

##  Estructura del Repositorio
/data
/raw → datos originales (sintéticos)
/processed → datos transformados

/notebooks → notebooks por unidad (U0_setup, U1_KPIs, ...)
U0_setup.ipynb

/src
/etl → scripts de extracción y limpieza
/models → scripts de simulación y optimización
/viz → funciones de visualización

/app/streamlit → tablero interactivo final

/reports → reportes PDF y entregables

---

##  Tecnologías y Librerías
- **Python 3**
- pandas, numpy, matplotlib  
- scikit-learn (analítica básica)  
- pulp / ortools (optimización)  
- sqlite3 (mini-base de datos)  
- streamlit (dashboard)  

---

##  Itinerario de Aprendizaje
- **Fase 0:** Preparación del entorno y datos sintéticos iniciales.
- **Fase 1:** KPIs (OTIF, Fill Rate, Lead Time).
- **Fase 2:** Diseño de la cadena (S&OP, MRP, proveedores).
- **Fase 3:** Operación de almacén (slotting & picking).
- **Fase 4:** Transporte (selección de modos y ruteo VRP).
- **Fase 5:** Tecnología de la Información (ETL + Dashboard).
- **Fase 6:** Configuración de red (facility location).

---

##  Metodología
1. **Aprendizaje paso a paso**: teoría mínima + código corto.  
2. **Tareas guiadas**: cada unidad tiene entregables claros.  
3. **Validación continua**: se revisan errores y se proponen soluciones.  
4. **Presentación ejecutiva**: reporte final y pitch de resultados.

---

##  Resultados Esperados
- Notebooks limpios y bien documentados.  
- Datos sintéticos reproducibles (CSV).  
- Gráficas y KPIs claros para la toma de decisiones.  
- Un **dashboard interactivo** que consolida toda la cadena de suministro.  
- Un **reporte ejecutivo** de máximo 5 páginas, con mejoras propuestas.  

---

##  Autores y Colaboradores
Proyecto desarrollado en el marco del **Proyecto Integrador de Logística y Cadena de Suministro**, con enfoque educativo en **Data Science aplicada**.

---


