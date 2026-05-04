# Primera Descomposicion del Core del Negocio - Caso b-learning UNS

## Criterio aplicado

La primera descomposicion toma el core del negocio definido previamente:

**Gestionar la capacitación continua en gerenciamiento empresarial mediante modalidad b-learning.**

Segun la guia de identificacion de casos de uso de negocio, los macroprocesos deben representar procesos que generan valor observable para los actores del negocio y que agrupan actividades relacionadas. Por eso no se modelan tareas pequenas como "usar foros", "subir archivos", "enviar mailings" o "grabar videos"; esas actividades quedan contenidas dentro de macroprocesos mas amplios.

## Primera descomposicion propuesta

| ID | Macroproceso de negocio | Justificacion en el caso |
|---|---|---|
| CUN-01 | Diseñar y actualizar la oferta formativa | El programa define objetivos, destinatarios, contenidos, cursos, diplomaturas, programas y actualizaciónes anuales según demandas del entorno. |
| CUN-02 | Captar e inscribir alumnos | Continuar.UNS difunde la propuesta, atiende interesados, gestióna inscripciónes y administra información académica y administrativa de alumnos. |
| CUN-03 | Producir contenidos y recursos educativos | Docentes, coordinadores, diseno grafico y produccion audiovisual elaboran materiales, actividades, articulos, videos y recursos para la modalidad b-learning. |
| CUN-04 | Administrar plataforma y servicio EaD | El programa depende de la gestión del LMS, alojamiento de cursos, comunicación docente-alumno, administración de usuarios y soporte tecnológico educativo. |
| CUN-05 | Impartir, evaluar y certificar cursos b-learning | Los docentes acompañan, orientan, responden dudas, promueven participacion, evalúan actividades, foros y trabajos finales; la certificación acredita formalmente el resultado obtenido por los alumnos. |
| CUN-06 | Analizar resultados y mejorar el programa | La evaluación decenal, los reportes estadísticos, la deserción, la cobertura geográfica y la innovación tecnológica guian la mejora continua del programa. |

## Stakeholders directos considerados

| ID | Stakeholder directo | Macroprocesos relacionados |
|---|---|---|
| SH-01 | Coordinadora del Programa - Renee Otero | CUN-01, CUN-02, CUN-05, CUN-06 |
| SH-02 | Equipo Operativo de Continuar.UNS | CUN-02, CUN-03, CUN-04, CUN-06 |
| SH-03 | Dirección de Tecnologia para la Educacion - Luis | CUN-04, CUN-06 |
| SH-04 | Coordinadores del Departamento de Economia | CUN-01, CUN-03 |
| SH-05 | Cuerpo Docente | CUN-01, CUN-03, CUN-05 |
| SH-06 | Equipo de Produccion Audiovisual | CUN-03 |
| SH-07 | Alumnos | CUN-02, CUN-05 |

## Diagrama de primera descomposicion

Archivo editable en draw.io:

[Primera_Descomposicion_BLearning.drawio](./diagramas/Primera_Descomposicion_BLearning.drawio)

El diagrama mantiene la notacion de casos de negocio: actores de negocio con diagonal en la cabeza y ovalos de macroproceso con diagonal. La frontera rectangular representa el core del negocio descompuesto en sus macroprocesos principales.
