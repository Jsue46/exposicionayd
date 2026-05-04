# Casos de Uso Expandidos - Caso b-learning UNS

## Criterio aplicado

Los casos de uso expandidos se derivan de los drivers funcionales identificados en el enunciado. En esta fase participan stakeholders directos e indirectos cuando intervienen en un driver funcional concreto.

Se mantiene la siguiente regla de modelado:

- Los casos base representan la entrada principal al módulo de negocio.
- Los RF se modelan como ovalos derivados cuando agrupan dos o mas acciones observables del stakeholder.
- Los RF obligatorios se conectan con `<<include>>`.
- Los RF opcionales, condicionales o de mejora se conectan con `<<extend>>`.
- Las variantes de una decision o tipo de oferta se modelan con generalización.
- No se usan diagonales en actores ni ovalos, porque ya no es el diagrama de core de negocio.

## Drivers funcionales RF

| ID | Driver funcional | Módulo / CUN |
|---|---|---|
| RF-01 | Relevar necesidades de capacitación de destinatarios empresariales. | CUN-01 |
| RF-02 | Definir objetivos, destinatarios y alcance de la propuesta formativa. | CUN-01 |
| RF-03 | Seleccionar y actualizar contenidos académicos del programa. | CUN-01 |
| RF-04 | Configurar una oferta flexible en diplomaturas, programas, módulos o cursos sueltos. | CUN-01 |
| RF-05 | Seleccionar y vincular docentes según especialidad tematica. | CUN-01 |
| RF-06 | Incorporar docentes invitados de otras universidades cuando la oferta lo requiera. | CUN-01 |
| RF-07 | Difundir la propuesta de capacitación por canales institucionales y medios externos. | CUN-02 |
| RF-08 | Gestionar campañas dirigidas a graduados de la UNS. | CUN-02 |
| RF-09 | Atender consultas de estudiantes interesados. | CUN-02 |
| RF-10 | Gestionar inscripciónes al programa, diplomatura, módulo o curso. | CUN-02 |
| RF-11 | Aplicar bonificación especial a graduados cuando corresponda. | CUN-02 |
| RF-12 | Administrar información académica y administrativa de alumnos a distancia. | CUN-02 |
| RF-13 | Elaborar material teórico de estudio para cada curso. | CUN-03 |
| RF-14 | Integrar bibliografía, articulos, ensayos y vínculos web de apoyo. | CUN-03 |
| RF-15 | Diseñar actividades prácticas y propuestas de participacion. | CUN-03 |
| RF-16 | Producir recursos gráficos para la experiencia e-learning. | CUN-03 |
| RF-17 | Producir videos educativos y videos de presentación cuando aporten valor didactico o promocional. | CUN-03 |
| RF-18 | Publicar y organizar materiales educativos en el LMS. | CUN-03 |
| RF-19 | Administrar el alojamiento de cursos en la plataforma LMS. | CUN-04 |
| RF-20 | Gestionar usuarios, grupos y recursos de aprendizaje. | CUN-04 |
| RF-21 | Habilitar herramientas de comunicación docente-alumno. | CUN-04 |
| RF-22 | Mantener compatibilidad, usabilidad y recursos de aprendizaje del LMS. | CUN-04 |
| RF-23 | Brindar soporte tecnológico para continuidad de los cursos a distancia. | CUN-04 |
| RF-24 | Revisar e innovar la plataforma educativa cuando los avances de e-learning lo justifiquen. | CUN-04 |
| RF-25 | Gestionar el encuentro presencial inicial no obligatorio. | CUN-05 |
| RF-26 | Facilitar clases virtuales con materiales y actividades. | CUN-05 |
| RF-27 | Mediar tutorias y comunicación asincrónica en foros, correo o chat. | CUN-05 |
| RF-28 | Evaluar actividades, participacion e interacciones de aprendizaje. | CUN-05 |
| RF-29 | Evaluar examen o trabajo final del curso. | CUN-05 |
| RF-30 | Emitir certificación o acreditación del curso aprobado. | CUN-05 |
| RF-31 | Generar reportes estadísticos del programa. | CUN-06 |
| RF-32 | Analizar perfil de alumnos y alcance geográfico de la propuesta. | CUN-06 |
| RF-33 | Analizar aprobación, abandono y deserción del programa. | CUN-06 |
| RF-34 | Identificar nuevas necesidades y datos útiles para profundizar la evaluación. | CUN-06 |
| RF-35 | Definir estrategias de mejora didáctica, tecnológica y de marketing. | CUN-06 |
| RF-36 | Planificar crecimiento de la EaD para incorporar nuevos programas sin detener los actuales. | CUN-06 |

## Diagramas draw.io

| Módulo | Diagrama |
|---|---|
| CUN-01 Diseñar y actualizar la oferta formativa | [Oferta formativa](./diagramas/CUN_Expandido_01_Oferta_Formativa_BLearning.drawio) |
| CUN-02 Captar e inscribir alumnos | [Captación e inscripción](./diagramas/CUN_Expandido_02_Captacion_Inscripcion_BLearning.drawio) |
| CUN-03 Producir contenidos y recursos educativos | [Producción de contenidos](./diagramas/CUN_Expandido_03_Produccion_Contenidos_BLearning.drawio) |
| CUN-04 Administrar plataforma y servicio EaD | [Plataforma EaD](./diagramas/CUN_Expandido_04_Plataforma_EaD_BLearning.drawio) |
| CUN-05 Impartir, evaluar y certificar cursos b-learning | [Impartición y certificación](./diagramas/CUN_Expandido_05_Imparticion_Certificacion_BLearning.drawio) |
| CUN-06 Analizar resultados y mejorar el programa | [Mejora continua](./diagramas/CUN_Expandido_06_Mejora_Continua_BLearning.drawio) |

## Resumen de modelado corregido

Los RF no se modelan como casos base. Los casos base son los puntos de entrada principales de cada módulo; los RF son los ovalos derivados que salen de ellos mediante `<<include>>`, `<<extend>>` o generalización.

| CUN | Casos base | RF derivados |
|---|---|---|
| CUN-01 | Investigar necesidades de capacitación | RF-01 |
| CUN-01 | Diseñar propuesta académica | RF-02, RF-03, RF-04 |
| CUN-01 | Gestionar cuerpo docente | RF-05, RF-06 |
| CUN-02 | Promocionar oferta de capacitación | RF-07, RF-08 |
| CUN-02 | Atender postulacion de alumno | RF-09, RF-10, RF-11, RF-12 |
| CUN-03 | Elaborar material académico | RF-13, RF-14, RF-15 |
| CUN-03 | Diseñar recursos multimedia | RF-16, RF-17 |
| CUN-03 | Publicar recursos en aula virtual | RF-18 |
| CUN-04 | Gestionar cursos en LMS | RF-19, RF-20, RF-21 |
| CUN-04 | Mantener servicio tecnológico EaD | RF-22, RF-23, RF-24 |
| CUN-05 | Desarrollar actividades de aprendizaje | RF-25, RF-26, RF-27 |
| CUN-05 | Evaluar aprendizaje del alumno | RF-28, RF-29 |
| CUN-05 | Acreditar curso aprobado | RF-30 |
| CUN-06 | Analizar desempeño del programa | RF-31, RF-32, RF-33 |
| CUN-06 | Definir mejora estratégica | RF-34, RF-35, RF-36 |

> En CUN-01, `Configurar oferta flexible` se especializa mediante generalización en las variantes mencionadas por el caso: diplomatura, programa y curso suelto.
