# Matrices de trazabilidad - Caso b-learning UNS

## Alcance

Estas matrices trazan la relacion entre:

- **Stakeholders** (SH-01..SH-13) definidos en `Stakeholders_BLearning.md`.
- **Requerimientos funcionales / Drivers** (RF-01..RF-36) definidos en `Casos_Uso_Expandidos_BLearning.md`.
- **Casos base (CB)** que estructuran el **CDU expandido** por modulo (CUN).

## Leyenda

- `X` = existe relacion de trazabilidad (participa, ejecuta o recibe impacto directo).

## Codigos

### Stakeholders

| ID | Stakeholder |
|---|---|
| SH-01 | Coordinadora del Programa |
| SH-02 | Equipo Operativo de Continuar.UNS |
| SH-03 | Dirección de Tecnologia para la Educacion |
| SH-04 | Coordinadores del Departamento de Economia |
| SH-05 | Cuerpo Docente |
| SH-06 | Equipo de Produccion Audiovisual |
| SH-07 | Alumnos |
| SH-08 | Autoridades Institucionales UNS |
| SH-09 | Empresas y Organizaciones Empleadoras |
| SH-10 | Graduados de la UNS |
| SH-11 | Servicios Centralizados de Apoyo |
| SH-12 | Universidades Invitadas como Instituciones |
| SH-13 | Medios de Comunicación Locales |

### Casos base (CDU)

| ID | Caso base (CB) | CUN |
|---|---|---|
| CB-01 | Investigar necesidades de capacitación | CUN-01 |
| CB-02 | Diseñar propuesta académica | CUN-01 |
| CB-03 | Gestionar cuerpo docente | CUN-01 |
| CB-04 | Promocionar oferta de capacitación | CUN-02 |
| CB-05 | Atender postulacion de alumno | CUN-02 |
| CB-06 | Elaborar material académico | CUN-03 |
| CB-07 | Diseñar recursos multimedia | CUN-03 |
| CB-08 | Publicar recursos en aula virtual | CUN-03 |
| CB-09 | Gestionar cursos en LMS | CUN-04 |
| CB-10 | Mantener servicio tecnológico EaD | CUN-04 |
| CB-11 | Desarrollar actividades de aprendizaje | CUN-05 |
| CB-12 | Evaluar aprendizaje del alumno | CUN-05 |
| CB-13 | Acreditar curso aprobado | CUN-05 |
| CB-14 | Analizar desempeño del programa | CUN-06 |
| CB-15 | Definir mejora estratégica | CUN-06 |

> Nota: los requerimientos se mantienen con su ID original `RF-01..RF-36`.

---

## Matriz 1: Stakeholders vs Requerimientos (RF)

### Matriz 1A (RF-01 .. RF-18)

| Stakeholder | RF-01 | RF-02 | RF-03 | RF-04 | RF-05 | RF-06 | RF-07 | RF-08 | RF-09 | RF-10 | RF-11 | RF-12 | RF-13 | RF-14 | RF-15 | RF-16 | RF-17 | RF-18 |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| SH-01 Coordinadora del Programa | X | X | X | X | X | X |  |  |  |  |  |  |  |  |  |  |  |  |
| SH-02 Equipo Operativo de Continuar.UNS |  |  |  |  |  |  | X | X | X | X | X | X |  |  |  | X |  | X |
| SH-03 Dirección de Tecnologia para la Educacion |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| SH-04 Coordinadores del Departamento de Economia |  | X | X | X | X | X |  |  |  |  |  |  | X | X | X |  |  |  |
| SH-05 Cuerpo Docente |  | X | X | X | X | X |  |  |  |  |  |  | X | X | X | X | X |  |
| SH-06 Equipo de Produccion Audiovisual |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | X |  |
| SH-07 Alumnos |  |  |  |  |  |  |  |  | X | X |  | X |  |  |  |  |  | X |
| SH-08 Autoridades Institucionales UNS |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| SH-09 Empresas y Organizaciones Empleadoras | X |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| SH-10 Graduados de la UNS |  |  |  |  |  |  |  | X |  | X | X |  |  |  |  |  |  |  |
| SH-11 Servicios Centralizados de Apoyo |  |  |  |  |  |  |  |  |  |  |  |  |  | X |  |  |  |  |
| SH-12 Universidades Invitadas como Instituciones |  |  |  |  |  | X |  |  |  |  |  |  |  |  |  |  |  |  |
| SH-13 Medios de Comunicación Locales |  |  |  |  |  |  | X |  |  |  |  |  |  |  |  |  |  |  |

### Matriz 1B (RF-19 .. RF-36)

| Stakeholder | RF-19 | RF-20 | RF-21 | RF-22 | RF-23 | RF-24 | RF-25 | RF-26 | RF-27 | RF-28 | RF-29 | RF-30 | RF-31 | RF-32 | RF-33 | RF-34 | RF-35 | RF-36 |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| SH-01 Coordinadora del Programa |  |  |  |  |  |  |  |  |  |  |  | X | X | X | X | X | X | X |
| SH-02 Equipo Operativo de Continuar.UNS | X | X | X | X | X | X |  |  |  |  |  | X | X | X | X | X | X | X |
| SH-03 Dirección de Tecnologia para la Educacion | X | X | X | X | X | X |  |  |  |  |  |  |  |  |  |  | X | X |
| SH-04 Coordinadores del Departamento de Economia |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| SH-05 Cuerpo Docente |  |  | X |  |  |  | X | X | X | X | X |  |  |  |  |  |  |  |
| SH-06 Equipo de Produccion Audiovisual |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| SH-07 Alumnos |  |  | X | X | X |  | X | X | X | X | X | X |  |  |  |  |  |  |
| SH-08 Autoridades Institucionales UNS |  |  |  |  |  | X |  |  |  |  |  |  | X | X | X | X | X | X |
| SH-09 Empresas y Organizaciones Empleadoras |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| SH-10 Graduados de la UNS |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| SH-11 Servicios Centralizados de Apoyo |  |  |  |  | X |  |  |  |  |  |  |  |  |  |  |  |  |  |
| SH-12 Universidades Invitadas como Instituciones |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| SH-13 Medios de Comunicación Locales |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |

---

## Matriz 2: Requerimientos vs CDU (RF vs CB)

| RF \ CB | CB-01 | CB-02 | CB-03 | CB-04 | CB-05 | CB-06 | CB-07 | CB-08 | CB-09 | CB-10 | CB-11 | CB-12 | CB-13 | CB-14 | CB-15 |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| RF-01 | X |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| RF-02 |  | X |  |  |  |  |  |  |  |  |  |  |  |  |  |
| RF-03 |  | X |  |  |  |  |  |  |  |  |  |  |  |  |  |
| RF-04 |  | X |  |  |  |  |  |  |  |  |  |  |  |  |  |
| RF-05 |  |  | X |  |  |  |  |  |  |  |  |  |  |  |  |
| RF-06 |  |  | X |  |  |  |  |  |  |  |  |  |  |  |  |
| RF-07 |  |  |  | X |  |  |  |  |  |  |  |  |  |  |  |
| RF-08 |  |  |  | X |  |  |  |  |  |  |  |  |  |  |  |
| RF-09 |  |  |  |  | X |  |  |  |  |  |  |  |  |  |  |
| RF-10 |  |  |  |  | X |  |  |  |  |  |  |  |  |  |  |
| RF-11 |  |  |  |  | X |  |  |  |  |  |  |  |  |  |  |
| RF-12 |  |  |  |  | X |  |  |  |  |  |  |  |  |  |  |
| RF-13 |  |  |  |  |  | X |  |  |  |  |  |  |  |  |  |
| RF-14 |  |  |  |  |  | X |  |  |  |  |  |  |  |  |  |
| RF-15 |  |  |  |  |  | X |  |  |  |  |  |  |  |  |  |
| RF-16 |  |  |  |  |  |  | X |  |  |  |  |  |  |  |  |
| RF-17 |  |  |  |  |  |  | X |  |  |  |  |  |  |  |  |
| RF-18 |  |  |  |  |  |  |  | X |  |  |  |  |  |  |  |
| RF-19 |  |  |  |  |  |  |  |  | X |  |  |  |  |  |  |
| RF-20 |  |  |  |  |  |  |  |  | X |  |  |  |  |  |  |
| RF-21 |  |  |  |  |  |  |  |  | X |  |  |  |  |  |  |
| RF-22 |  |  |  |  |  |  |  |  |  | X |  |  |  |  |  |
| RF-23 |  |  |  |  |  |  |  |  |  | X |  |  |  |  |  |
| RF-24 |  |  |  |  |  |  |  |  |  | X |  |  |  |  |  |
| RF-25 |  |  |  |  |  |  |  |  |  |  | X |  |  |  |  |
| RF-26 |  |  |  |  |  |  |  |  |  |  | X |  |  |  |  |
| RF-27 |  |  |  |  |  |  |  |  |  |  | X |  |  |  |  |
| RF-28 |  |  |  |  |  |  |  |  |  |  |  | X |  |  |  |
| RF-29 |  |  |  |  |  |  |  |  |  |  |  | X |  |  |  |
| RF-30 |  |  |  |  |  |  |  |  |  |  |  |  | X |  |  |
| RF-31 |  |  |  |  |  |  |  |  |  |  |  |  |  | X |  |
| RF-32 |  |  |  |  |  |  |  |  |  |  |  |  |  | X |  |
| RF-33 |  |  |  |  |  |  |  |  |  |  |  |  |  | X |  |
| RF-34 |  |  |  |  |  |  |  |  |  |  |  |  |  |  | X |
| RF-35 |  |  |  |  |  |  |  |  |  |  |  |  |  |  | X |
| RF-36 |  |  |  |  |  |  |  |  |  |  |  |  |  |  | X |

---

## Matriz 3: Stakeholders vs CDU (Stakeholders vs CB)

| Stakeholder | CB-01 | CB-02 | CB-03 | CB-04 | CB-05 | CB-06 | CB-07 | CB-08 | CB-09 | CB-10 | CB-11 | CB-12 | CB-13 | CB-14 | CB-15 |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| SH-01 Coordinadora del Programa | X | X | X |  |  |  |  |  |  |  |  |  | X | X | X |
| SH-02 Equipo Operativo de Continuar.UNS |  |  |  | X | X |  | X | X | X | X |  |  | X | X | X |
| SH-03 Dirección de Tecnologia para la Educacion |  |  |  |  |  |  |  |  | X | X |  |  |  |  | X |
| SH-04 Coordinadores del Departamento de Economia |  | X | X |  |  | X |  |  |  |  |  |  |  |  |  |
| SH-05 Cuerpo Docente |  | X | X |  |  | X | X |  | X |  | X | X |  |  |  |
| SH-06 Equipo de Produccion Audiovisual |  |  |  |  |  |  | X |  |  |  |  |  |  |  |  |
| SH-07 Alumnos |  |  |  |  | X |  |  | X |  |  | X | X | X |  |  |
| SH-08 Autoridades Institucionales UNS |  |  |  |  |  |  |  |  |  | X |  |  |  | X | X |
| SH-09 Empresas y Organizaciones Empleadoras | X |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| SH-10 Graduados de la UNS |  |  |  | X | X |  |  |  |  |  |  |  |  |  |  |
| SH-11 Servicios Centralizados de Apoyo |  |  |  |  |  | X |  |  |  | X |  |  |  |  |  |
| SH-12 Universidades Invitadas como Instituciones |  |  | X |  |  |  |  |  |  |  |  |  |  |  |  |
| SH-13 Medios de Comunicación Locales |  |  |  | X |  |  |  |  |  |  |  |  |  |  |  |

---

## Observaciones

- Las matrices se basan en la definicion de stakeholders y en el mapeo **RF -> CB** del documento de expandidos.
- Los stakeholders indirectos (SH-08..SH-13) se vinculan solo a los RF/CB donde el caso muestra intervencion concreta (difusion, bonificacion, soporte, innovacion, evaluacion y crecimiento).
