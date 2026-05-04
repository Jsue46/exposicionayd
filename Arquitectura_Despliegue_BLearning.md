# Arquitectura de Despliegue - Caso b-learning UNS

## Criterio aplicado

El diagrama de despliegue muestra cómo funcionará físicamente la solución propuesta para el programa b-learning de la UNS. En esta versión se adopta la arquitectura indicada por el material de clase: **Arquitectura CAPAS/SOA**.

La solución sigue siendo coherente con el caso:

- mantener la modalidad b-learning;
- conservar el LMS institucional como pieza central;
- operar los cursos actuales sin interrupción;
- incorporar nuevos programas de licenciatura y posgrado;
- gestionar inscripción, cursado, evaluación, certificación y reportes;
- mejorar la toma de decisiones mediante indicadores de deserción, alcance geográfico, perfil y satisfacción.

## Estilo arquitectónico seleccionado

Se propone una **Arquitectura CAPAS/SOA**.

Este estilo combina una separación por capas con servicios expuestos mediante interfaces. Para el caso UNS permite ordenar la solución sin sobredimensionarla: el usuario entra por una capa de presentación, las capacidades institucionales se exponen mediante servicios web, los casos de uso se ejecutan en la capa de negocio, la información se conserva en una base centralizada y la integración conecta el LMS con servicios externos de apoyo.

## Capas de la solución

| Capa | Aplicación al caso UNS | Responsabilidad principal |
|---|---|---|
| Presentación | Portal web del campus virtual y acceso móvil | Permitir interacción de alumnos, docentes, coordinación y equipo operativo. |
| Servicios Web | API de acceso académico y API institucional | Exponer servicios para inscripción, oferta, cursos, reportes e integración con universidades/programas externos. |
| Negocio | Capacidades agrupadas a partir de los drivers funcionales | Ejecutar los casos de uso principales del programa b-learning sin saturar el despliegue con los 36 drivers individuales. |
| Datos | BD centralizada b-learning UNS | Persistir alumnos, cursos, inscripciones, registros académicos, resultados, certificaciones, reportes y KPI. |
| Integración | LMS institucional, campus virtual, bibliotecas, medios audiovisuales, telecomunicaciones, correo y pagos si aplica | Conectar la solución con sistemas y servicios institucionales o externos. |

## Componentes de negocio desplegados

| Componente | Drivers funcionales agrupados |
|---|---|
| Diseñar y actualizar oferta formativa | Necesidades, objetivos, contenidos, modalidades flexibles y estructura de cursos. |
| Gestionar cuerpo docente invitado | Selección de docentes por especialidad e incorporación de universidades invitadas. |
| Captar e inscribir alumnos | Difusión, campañas, consultas e inscripción al programa, diplomatura, módulo o curso. |
| Administrar alumnos y bonificaciones | Información académica/administrativa de alumnos y beneficios para graduados. |
| Producir contenidos y actividades | Material teórico, bibliografía, actividades prácticas y recursos de apoyo. |
| Diseñar recursos multimedia | Recursos gráficos, videos educativos y videos de presentación. |
| Administrar cursos en LMS | Alojamiento de cursos, usuarios, grupos y recursos de aprendizaje. |
| Mantener servicio tecnológico EaD | Comunicación docente-alumno, compatibilidad, soporte e innovación de la plataforma. |
| Impartir cursos b-learning | Encuentro presencial inicial, clases virtuales, tutorías y comunicación asincrónica. |
| Evaluar y certificar aprendizaje | Evaluación de actividades, trabajo final, aprobación y emisión de certificación. |
| Analizar resultados del programa | Reportes estadísticos, perfil de alumnos, alcance geográfico, aprobación y deserción. |
| Definir mejora y crecimiento EaD | Nuevas necesidades, mejora didáctica/tecnológica/marketing y expansión del programa. |

## Calidad reflejada en la arquitectura

| Necesidad de calidad | Decisión de despliegue |
|---|---|
| Disponibilidad y continuidad | La capa de negocio se despliega en servidor aplicativo con monitoreo, backups y operación incremental. |
| Desempeño | Se separan presentación, servicios, negocio, datos e integración para evitar concentrar toda la carga en un solo punto lógico. |
| Usabilidad | El usuario accede desde navegador web o móvil mediante portal académico y campus virtual. |
| Seguridad | La capa de servicios web controla autenticación, autorización y roles antes de llegar a negocio y datos. |
| Interoperabilidad | La capa de integración conecta LMS, SCORM/AICC, bibliotecas, medios audiovisuales, correo y servicios externos. |
| Escalabilidad y modificabilidad | Nuevos programas se agregan por servicios y configuración sin detener los cursos actuales. |
| Trazabilidad | La BD centralizada conserva evidencia académica, reportes, certificación y KPI. |

## Diagrama

Archivo editable en draw.io:

[Diagrama_Despliegue_BLearning_UNS.drawio](./diagramas/Diagrama_Despliegue_BLearning_UNS.drawio)

El diagrama representa nodos grandes tipo servidor. Dentro de cada nodo aparecen carpetas que representan las capas; dentro de cada carpeta se ubican componentes concretos de la solución. Las conexiones se realizan mediante interfaces y protocolos como HTTPS, REST/SOA, JDBC e integraciones institucionales.
