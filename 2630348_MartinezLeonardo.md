# Investigación sobre el SDLC (Software Development Life Cycle)

**Estudiante:** Leonardo Enrique Martinez Guevara  
**Matrícula:** 2630348  
**Materia:** Ingeniería de Software  
**Catedrático:** M.C. Carlos Antonio Tovar García  

---

## Resumen Ejecutivo

El Ciclo de Vida del Desarrollo de Software (SDLC, por sus siglas en inglés *Software Development Life Cycle*) es un marco de trabajo estructurado que define las fases y procesos necesarios para planificar, construir, probar, desplegar y mantener aplicaciones de software de alta calidad. Su propósito principal es mitigar riesgos, optimizar el uso de recursos, garantizar el cumplimiento de los requisitos del usuario y asegurar que el producto final sea sostenible en el tiempo.

Este documento presenta un análisis detallado del SDLC, desglosando sus siete fases fundamentales (Planificación, Análisis de requisitos, Diseño, Implementación, Pruebas, Despliegue y Mantenimiento) mediante la especificación de sus objetivos, actividades, entregables clave y riesgos asociados. Finalmente, se incluye una reflexión sobre su aplicación en entornos académicos y profesionales.

---

## Fases del SDLC

### 1. Planificación (Planning)
* **Objetivo:** Definir el alcance del proyecto, evaluar su viabilidad técnica y financiera, estimar recursos y establecer el cronograma inicial.
* **Actividades típicas:**
  * Estudio de factibilidad técnica, económica y operativa.
  * Estimación de costos, tiempos y asignación de personal.
  * Definición de métricas de éxito y análisis inicial de riesgos.
* **Entregables:** Plan del proyecto, matriz de riesgos y acta de constitución del proyecto (*Project Charter*).
* **Riesgos comunes:** Estimaciones de tiempo/presupuesto poco realistas y falta de alineación entre los involucrados.

### 2. Análisis de Requisitos (Requirements/Analysis)
* **Objetivo:** Identificar, documentar y validar las necesidades exactas de los usuarios y del negocio para determinar qué debe hacer el software.
* **Actividades típicas:**
  * Entrevistas con stakeholders y recolección de historias de usuario.
  * Definición de requisitos funcionales y no funcionales.
  * Modelado de procesos de negocio y casos de uso.
* **Entregables:** Documento de Especificación de Requisitos de Software (SRS - *Software Requirements Specification*).
* **Riesgos comunes:** Requisitos ambiguos o incompletos y el fenómeno de corrupción del alcance (*scope creep*).

### 3. Diseño (Design)
* **Objetivo:** Transformar los requisitos recopilados en una arquitectura técnica detallada y comprensible para el equipo de desarrollo.
* **Actividades típicas:**
  * Diseño de la arquitectura de software (patrones, componentes, microservicios).
  * Modelado de bases de datos (diagramas entidad-relación) y diseño de APIs.
  * Creación de prototipos de interfaz de usuario (UI/UX).
* **Entregables:** Documento de Diseño de Software (SDD - *Software Design Document*), esquemas de base de datos y *wireframes*.
* **Riesgos comunes:** Sobreingeniería del sistema y elecciones arquitectónicas rígidas que limiten la escalabilidad.

### 4. Implementación (Implementation)
* **Objetivo:** Traducir las especificaciones de diseño en código fuente funcional utilizando las mejores prácticas de programación.
* **Actividades típicas:**
  * Escritura de código en los lenguajes y frameworks seleccionados.
  * Creación de pruebas unitarias y revisión de código (*code review*).
  * Control de versiones e integración en el repositorio.
* **Entregables:** Código fuente compilable, repositorio de versiones y resultados de pruebas unitarias.
* **Riesgos comunes:** Acumulación de deuda técnica, falta de estándares de codificación y retrasos por complejidad no prevista.

### 5. Pruebas (Testing)
* **Objetivo:** Detectar y corregir defectos o errores en el software antes de su liberación, asegurando la calidad y el cumplimiento de requisitos.
* **Actividades típicas:**
  * Ejecución de pruebas de integración, sistema, rendimiento y seguridad.
  * Pruebas de Aceptación del Usuario (UAT - *User Acceptance Testing*).
  * Reporte y seguimiento de errores (*bug tracking*).
* **Entregables:** Plan de pruebas, casos de prueba ejecutados y reporte final de calidad de software.
* **Riesgos comunes:** Cobertura de pruebas insuficiente debido a limitaciones de tiempo y entornos de prueba poco representativos.

### 6. Despliegue (Deployment)
* **Objetivo:** Liberar el software probado y funcional en un entorno de producción accesible para los usuarios finales.
* **Actividades típicas:**
  * Configuración de servidores y canalizaciones de CI/CD (*Continuous Integration / Continuous Deployment*).
  * Migración de bases de datos y ejecución del despliegue (estrategias *Blue/Green* o *Canary*).
  * Capacitación de usuarios finales y elaboración de guías de instalación.
* **Entregables:** Aplicación disponible en producción, manuales de usuario y notas de versión (*Release Notes*).
* **Riesgos comunes:** Fallos no detectados durante la migración en vivo y tiempos de inactividad no planificados.

### 7. Mantenimiento (Maintenance)
* **Objetivo:** Garantizar que el software continúe funcionando de forma óptima a lo largo del tiempo mediante correcciones y mejoras.
* **Actividades típicas:**
  * Corrección de errores reportados en producción (mantenimiento correctivo).
  * Actualización de librerías y parches de seguridad (mantenimiento preventivo).
  * Implementación de nuevas funcionalidades (mantenimiento evolutivo).
* **Entregables:** Reportes de incidentes, parches de actualización y versiones mejoradas del software.
* **Riesgos comunes:** Obsolescencia tecnológica y degradación de la arquitectura por cambios no planificados.

---

## Resumen de Fases del SDLC

| Fase | Objetivo Principal | Entregable Clave | Riesgo Principal |
| :--- | :--- | :--- | :--- |
| **1. Planificación** | Definir alcance y viabilidad | Plan del Proyecto | Estimaciones poco realistas |
| **2. Análisis** | Identificar requisitos del sistema | Documento SRS | Corrupción del alcance (*Scope creep*) |
| **3. Diseño** | Definir arquitectura y UI | Documento SDD | Sobreingeniería técnica |
| **4. Implementación** | Codificar la solución | Código Fuente | Deuda técnica acumulada |
| **5. Pruebas** | Validar la calidad del producto | Reporte de Pruebas | Cobertura de pruebas insuficiente |
| **6. Despliegue** | Liberar el sistema en producción | Software en Producción | Caídas o fallos en la migración |
| **7. Mantenimiento** | Optimizar y actualizar la aplicación | Parches y Actualizaciones | Obsolescencia del sistema |

---

## Conclusiones

La adopción rigurosa del SDLC representa la diferencia entre la construcción improvisada de software y la ingeniería de software profesional. En el contexto académico, aplicar estas fases ayuda a disciplinar el proceso de desarrollo, evitando la tentación de comenzar a programar sin una fase adecuada de análisis y diseño. 

En el ámbito profesional, comprender el SDLC es indispensable para colaborar eficazmente en equipos multidisciplinarios. Aunque los modelos tradicionales (como Cascada) han dado paso a metodologías ágiles (Scrum, Kanban) que iteran rápidamente sobre estas fases, los principios del SDLC siguen siendo la base fundamental para construir sistemas seguros, escalables y orientados a aportar valor real.

---

## Referencias

1. Pressman, R. S., & Maxim, B. R. (2020). *Software Engineering: A Practitioner's Approach* (9th ed.). McGraw-Hill Education.
2. Sommerville, I. (2016). *Software Engineering* (10th ed.). Pearson.
3. IEEE Computer Society. (2014). *Guide to the Software Engineering Body of Knowledge (SWEBOK Guide v3.0)*. IEEE.
4. Martin, R. C. (2017). *Clean Architecture: A Craftsman's Guide to Software Structure and Design*. Prentice Hall.
5. Amazon Web Services (AWS). (2023). *What is SDLC (Software Development Life Cycle)?*. AWS Resources. Recuperado de https://aws.amazon.com/what-is/sdlc/