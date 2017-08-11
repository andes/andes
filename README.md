![ANDES](https://github.com/andes/andes.github.io/raw/master/images/logo.png)

## Qué es ANDES

ANDES es un **ecosistema de aplicaciones de salud** coordinado a través de una capa de interoperabilidad, basado en estándares internacionales tales como **HL7/FHIR, SNOMED, LOINC y DICOM**, distribuido en forma **absolutamente libre y gratuita** bajo el licenciamiento GPL.

Desde un punto de vista funcional, ANDES es una plataforma digital de servicios de salud que implementa la Historia Unificada Digital de Salud (HUDS) y permite a pacientes y profesionales de la salud acceder a los datos registrados en un modo seguro.

## Orígenes

Hacia fines del año 2015 se sanciona la Ley de **Historia Unificada Digital de Salud (HUDS)** en la provincia de Neuquén (Argentina), que involucra todo el ámbito público y privado de la salud.

Pocos meses después comienza a gestarse un proyecto que tiene como desafío integrar todos los sistemas y herramientas informáticas existentes, permitiendo acceder a la información de salud en forma ordenada y segura. Este proyecto pasó a denominarse con el acrónimo **A.N.De.S: Aplicaciones Neuquinas de Salud**.

## Arquitectura

![Arquitectura](https://github.com/andes/andes.github.io/raw/master/images/arquitectura.png)

1. **Core**: componentes básicos del núcleo de ANDES
2. **Apps nativas**: aplicaciones básicas que implementan las herramientas administrativas y asistenciales más usadas en el ámbito de la salud.
3. **Apps externas**: aplicaciones y sistemas existentes que interoperan con el Core
4. **Interoperabilidad**: capa segura de comunicación HL7/FHIR entre las aplicaciones externas y los componentes del core

### Core

| Componente  | Descripción | Docs |
| ------------- | ------------- | ------------- |
| MPI  | Master Patient Index  | *Próximamente* |
| HUDS  | Historia de Salud  | *Próximamente* |
| TM  | Tablas Maestras | *Próximamente* |
| TERM  | Servidor de terminología | *Próximamente* |

### Apps nativas

| Componente  | Descripción | Docs |
| ------------- | ------------- | ------------- |
| CITAS  | Agendas & Turnos | *Próximamente* |
| RUP  | Registro Universal de Prestaciones  | *Próximamente* |
| Mobile App | Aplicación móvil para acceso de pacientes y profesionales | *Próximamente* |

## Proyecto

El proyecto está integramente construido por profesionales médicos e informáticos del [Ministerio de Salud y Desarrollo Social del Neuquén](http://www.saludneuquen.gob.ar) utilizando las últimas tecnologías de desarrollo de aplicaciones.

### Tecnologías
| Componente  | Tecnología | Lenguaje de programación |
| ------------- | ------------- | ------------- |
| APP  | Angular 4  | Typescript / HTML |
| API  | Node.JS  | Typescript |
| Base de datos  | MongoDB | Typescript |
| Mobile APP  | Ionic | Typescript |


### Metodología de trabajo

El desarrollo se realiza utilizado metologías ágiles (Scrum) con dos equipos sincronizados que trabajan en locaciones diferentes (Subsecretaría de Salud y Hospital Provincial Neuquén). Trabajamos en sprints de 2 semanas guiados por un [Roadmap](https://github.com/andes/andes/wiki/Roadmap).

## Integrantes del equipo

### Project managers
- Lic. Juan F. Gabriel
- Lic. Marcelo D. Carrascal
- Lic. Hugo H. Fernandez

### Equipo médico
- Dra. Laura Monteverde
- Dr. Matías Neira
- Dra. Adelaida Goldmann
- Dr. Roberto D'Angelo

### Developers
- A.S. Luis Parada
- A.S. Manuel Urbano
- Lic. Silvina Roa
- Lic. Natalia Huenchuman
- A.S. Carolina Celeste
- Andrés Velazquez Boc-Ho
- Nicolás Dinolfo
- Tec. Fernando Sastre
- Lic. Mariano Botta

### UI/UX Designer
- Lic. Julio Santarelli

### Q&A
- Silvina Garcia

### Plataforma & ANDES Cloud
- Ing. Edgardo Kristensen
- A.S. Pablo Silveira
- Pablo Jeldrés
- Manuel Pereyra




## Sitio oficial

https://www.andes.gob.ar

## Documentación

https://github.com/andes/andes/wiki

## Roadmap

https://github.com/andes/andes/wiki/Roadmap

## Partners

![Ministerio de Salud y Desarrollo Social](https://github.com/andes/andes.github.io/raw/master/images/logo-ministerio.png)

![Facultad de Informática de la Universidad Nacional del Comahue](https://github.com/andes/andes.github.io/raw/master/images/logo-uncoma.png)

![Colegio Médico de Neuquén](https://raw.githubusercontent.com/andes/andes.github.io/master/images/logo-colegiomedico.png)


