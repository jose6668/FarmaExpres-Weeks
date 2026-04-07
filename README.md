# FarmaExpres · Semanas de desarrollo

Repositorio de seguimiento semanal del proyecto **FarmaExpres**, una plataforma orientada a la gestión empresarial para una pequeña farmacéutica.

## Tabla de contenido
- [Descripción del proyecto](#descripción-del-proyecto)
- [Equipo de trabajo](#equipo-de-trabajo)
- [Avance por semanas](#avance-por-semanas)
- [Enlaces de semanas](#enlaces-de-semanas)
- [Métrica de Avance del Proyecto](#-métrica-de-avance-del-proyecto)
- [Progreso por Semana](#progreso-por-semana)
- [Visualización del Avance](#visualización-del-avance)
- [Interpretación de la Métrica](#interpretación-de-la-métrica).

## Descripción del proyecto
**FarmaExpres** es una plataforma de gestión empresarial diseñada para administrar y controlar el inventario de medicamentos y productos farmacéuticos, bajo un sistema centralizado.

El sistema contempla acceso concurrente de múltiples usuarios para garantizar:
- Integridad de datos
- Consistencia
- Disponibilidad en tiempo real

## Equipo de trabajo
- **Vargas Herrera Jose Leonardo** — Backend
- **Buitrago Murcia Jersson Fabián** — QA
- **Tello Mendez Nicolas** — Frontend
- **Romero Trujillo Marlon David** — Product Owner

## Avance por semanas

### Week 1
**Lo que se hizo:**
- Definición inicial del proyecto.
- Presentación del alcance y propósito de la plataforma FarmaExpres.
- Conformación del equipo y asignación de roles.

**Lo que no se logró hacer:**
- Consolidar una primera versión formal del documento de requerimientos.
- Definir una priorización inicial de funcionalidades por nivel de impacto.

**Lo que se va a hacer:**
- Elaborar el documento de requerimientos versión 1.0.
- Establecer criterios de priorización para funcionalidades clave.

### Week 2
**Diseño del sistema**

**Objetivo:** definir la estructura técnica del sistema.

**Enfoque principal:** levantamiento de requerimientos.

**Lo que se hizo:**
- Identificación de requerimientos funcionales.
- Identificación de requerimientos no funcionales.
- Inicio de priorización de requerimientos.

**Lo que no se logró hacer:**
- Finalizar la validación de todos los requerimientos con el equipo completo.
- Cerrar la lista priorizada de funcionalidades para la siguiente fase.

**Lo que se va a hacer:**
- Completar la validación de requerimientos pendientes.
- Publicar la lista final priorizada de funcionalidades.
- Preparar la transición de actividades hacia la Week 3.

### Week 4
**Implementación**

## Descripción

Durante la Week 4 se trabajó en la implementación de las funcionalidades principales del sistema relacionadas con gestión de usuarios e inventario.

## Historias de Usuario (RF)

- HU-RF-01 – Gestión de Usuarios  
- HU-RF-02 – Autenticación  
- HU-RF-03 – Recuperación de Contraseña  
- HU-RF-04 – Gestión de Sedes  
- HU-RF-05 – Registro de Medicamentos  
- HU-RF-06 – Registro de Entradas  
- HU-RF-07 – Consulta de Inventario  
- HU-RF-08 – Alertas  
- HU-RF-09 – Historial de Movimientos  

## Avance

**Se realizó:**
- Creación y organización de HU en Issues.
- Asignación de responsables.
- Inicio de implementación de autenticación e inventario.

**Pendiente:**
- Finalizar módulo de alertas.
- Integrar pruebas entre funcionalidades.
- Implementar requerimientos no funcionales.


### Week 5

#### Tabla de contenido

- ADR (Architecture Decision Records)
- Descripción
- Historias de Usuario (HU)
- Objetivo
- ¿Qué se hizo?
- ¿Qué no se logró?
- ¿Qué se va a hacer?

#### ADR

Se identificaron y documentaron los Architecture Decision Records (ADR) relevantes para el proyecto, dejando registrados los criterios de diseño y las decisiones de arquitectura tomadas hasta la fecha.

#### Descripción

La Week 5 se centró en formalizar decisiones arquitectónicas y preparar el entorno de staging para validaciones. Se buscó asegurar que las decisiones tomadas queden registradas y que el equipo tenga claridad sobre los próximos pasos técnicos.

#### Historias de Usuario (HU)

No se adicionaron nuevas historias de usuario prioritarias esta semana: el foco estuvo en ADR y estabilizar despliegues.

#### Objetivo

Documentar las decisiones arquitectónicas y validar su impacto en entornos de staging, garantizando rastreabilidad y criterios claros para implementar cambios en semanas posteriores.

#### ¿Qué se hizo?

- Identificación y documentación de ADRs relevantes.
- Verificación de impactos y asignación de tareas relacionadas con las decisiones de arquitectura.
- Validaciones en entorno de staging y verificación de procesos de despliegue.
- Preparación y configuración inicial de monitoreo en staging/producción.

#### ¿Qué no se logró?

- No hubo tareas críticas sin resolver; se dejó pendiente la aplicación completa de algunos ADRs en el código (implementación en próximas semanas).

#### ¿Qué se va a hacer?

- Aplicar las decisiones documentadas (ADR) en los repositorios correspondientes.
- Extender la configuración de monitoreo y alertas a los servicios principales.
- Continuar validaciones en staging y promover despliegues controlados a producción.

### Week 6

#### Tabla de contenido

- Separación de Microservicios
	- Descripción
- Historias de Usuario (HU)
- Objetivo
- ¿Qué se hizo?
- ¿Qué no se logró?
- ¿Qué se va a hacer?

#### Separación de Microservicios

##### Descripción

Se trabajará en la separación del sistema a través de repositorios por cada microservicio, con el fin de mejorar la escalabilidad, mantenibilidad y organización del proyecto FarmaExpres.

Además, se definió una nueva Historia de Usuario (HU) enfocada en la estandarización del sistema, donde cada microservicio deberá ser renombrado y documentado en inglés, ya que anteriormente estaban definidos en español.

De forma paralela, se avanzó en la definición y estructuración del frontend del sistema, alineando las funcionalidades con los microservicios definidos en el backend. Esto permitió establecer una base clara para la comunicación entre servicios y la construcción de la interfaz de usuario.

#### Historias de Usuario (HU)

**Backend**

- `HU-MCI` - Migración del Backend de Español a Inglés
- `HU-doc` - Documentación técnica de microservicios backend

🔗 Ver todos los Issues

**Frontend**

Se definieron las historias de usuario correspondientes al frontend del sistema FarmaExpres:

- `HU-FE-01` – Gestión de Usuarios (Creación)
- `HU-FE-02` – Autenticación (Inicio de Sesión)
- `HU-FE-03` – Gestión de Usuarios (Cambio de Contraseña)
- `HU-FE-04` – Gestión de Medicamentos (Registro)
- `HU-FE-05` – Gestión de Medicamentos (Actualización)
- `HU-FE-06` – Gestión de Medicamentos (Eliminación Lógica)
- `HU-FE-07` – Movimientos (Historial)
- `HU-FE-08` – Inventario (Control Inteligente de Stock)
- `HU-FE-09` – Inventario (Productos Agotados)
- `HU-FE-10` – Auditoría (Gestión de Movimientos)

🔗 Ver todos los Issues

Estas historias permiten cubrir la interacción del usuario con el sistema, asegurando coherencia entre la lógica del backend y la interfaz del frontend.

#### Objetivo

Implementar la división del sistema en microservicios independientes por repositorios y establecer una nomenclatura estándar en inglés para cada uno de ellos, facilitando así la comprensión técnica, la interoperabilidad y futuras integraciones.

Adicionalmente, se busca estructurar el frontend del sistema basado en historias de usuario claras, permitiendo:

- Una mejor organización del desarrollo
- Coherencia entre backend y frontend
- Escalabilidad del sistema
- Una experiencia de usuario clara y funcional

#### ¿Qué se hizo?

- Se estructuró el frontend con enfoque modular por dominio, separando componentes, páginas y servicios.
- Se realizó la maquetación base de la aplicación (layout) por módulos y por roles.
- Se diseñó y publicó la demo visual del sistema en Canva para referencia funcional/UI.
- Se implementaron y documentaron las siguientes historias de usuario frontend:
	- `HU-FE-01`: Gestión de usuarios (crear, listar, editar y activar/desactivar).
	- `HU-FE-03`: Cambio de contraseña de usuarios desde administración.
	- `HU-FE-04`: Registro de medicamentos.
	- `HU-FE-05`: Actualización de medicamentos.
	- `HU-FE-06`: Eliminación lógica de medicamentos.
- Se consolidó documentación QA por HU en la carpeta `doc/` con evidencias visuales en `doc/images/`.
- Se alineó la base visual y funcional del frontend con el documento de layout del sistema.

**Enlaces del DEMO**

- Demo visual del sistema (Canva): FarmaExpres Demo

#### ¿Qué no se logró?

- No se implementó aún la `HU-FE-02` (autenticación de inicio de sesión) como flujo formal completo en frontend.
- No se completaron las historias de usuario de módulos pendientes:
	- `HU-FE-07`: Movimientos (historial).
	- `HU-FE-08`: Inventario (control inteligente de stock).
	- `HU-FE-09`: Inventario (productos agotados).
	- `HU-FE-10`: Auditoría (gestión de movimientos).
- En algunos módulos todavía queda pendiente la validación integral de permisos por rol una vez se cierre completamente el flujo de autenticación.
- Para el alcance de esta semana, `HU-FE-09` y `HU-FE-10` quedan programadas como pendientes para una fase posterior.

#### ¿Qué se va a hacer?

- Implementar la `HU-FE-02` (Autenticación - Inicio de Sesión):
	- Construir el flujo completo de login.
	- Gestionar sesión/token de acceso.
	- Aplicar control de acceso por rol desde el frontend.
- Implementar la `HU-FE-07` (Movimientos - Historial):
	- Mostrar historial de entradas y salidas.
	- Incorporar filtros por tipo, fecha y usuario.
	- Presentar trazabilidad clara de los registros.
- Implementar la `HU-FE-08` (Inventario - Control Inteligente de Stock):
	- Visualizar estado de stock por niveles.
	- Identificar productos críticos.
	- Mostrar apoyo para priorización de reposición.
- `HU-FE-09` y `HU-FE-10` se mantienen fuera del alcance de esta semana y se ejecutarán en la siguiente etapa.
- Mantener el esquema de trabajo por HU: implementación funcional, validaciones, manejo de errores y documentación QA con evidencias por cada entrega.
- Asegurar consistencia entre lo definido en layout, las reglas funcionales del frontend y los endpoints disponibles en backend.

# Week 09

## Tabla de contenido

* Consolidación de HU Backend y QA Frontend

  * Descripción
* Historias de Usuario (HU)
* Objetivo
* ¿Qué se hizo?
* ¿Qué no se logró?
* ¿Qué se va a hacer?

## Consolidación de HU Backend y QA Frontend

### Descripción

Durante la **Week 09** el trabajo estuvo enfocado en dos frentes principales: por un lado, dejar más organizada la documentación de varias historias de usuario del **backend** y, por otro, realizar validaciones **QA en frontend** sobre procesos importantes del sistema. La idea fue dejar más claro qué se ha venido construyendo, qué ya se probó y qué todavía sigue pendiente.

En la parte de backend, la atención se centró en las historias **HU-007 a HU-011**, donde se dejó documentado su alcance, los posibles endpoints y los criterios de aceptación dentro de la rama **Develop**. En frontend, el trabajo real de la semana se enfocó en dos validaciones QA ya documentadas: **HU-QA-FE-02**, relacionada con el inicio de sesión, y **HU-QA-FE-07**, enfocada en el historial de movimientos y sus filtros.

## Historias de Usuario (HU)

### Backend

* **HU-007:** Consulta de movimientos por categoría.
* **HU-008:** Alertas según rango de vencimiento.
* **HU-009:** Resumen de stock y valor total de productos activos.
* **HU-010:** DTO para la tabla de inventario activo.
* **HU-011:** Filtro de movimientos por usuario.

### Frontend

* **HU-QA-FE-02:** Autenticación, inicio de sesión y control de rutas privadas.
* **HU-QA-FE-07:** Historial de movimientos con filtros, trazabilidad y control de acceso por rol.

Estas historias apoyan directamente funciones clave del sistema, sobre todo en temas de **seguridad de acceso**, **control del inventario** y **seguimiento de movimientos**, manteniendo coherencia entre lo que ofrece el backend y lo que muestra la interfaz.

## Objetivo

Organizar el avance de la **Week 09** de una manera más clara, separando lo trabajado en backend y frontend, para que el equipo pueda identificar fácilmente qué historias están documentadas, cuáles ya tienen validaciones y qué hace falta cerrar en la siguiente iteración. También se buscó dejar una base sólida para continuar el desarrollo con mejor trazabilidad técnica y funcional.

## ¿Qué se hizo?

* Se consolidó la documentación en backend de las historias **HU-007 a HU-011**.
* Se dejó definido para cada historia su propósito funcional, sus criterios de aceptación y una propuesta de endpoints.
* Se registraron notas técnicas relacionadas con reportes de inventario y soporte **FEFO** para consumo desde frontend.
* Se mantuvo la trazabilidad de los componentes que deben intervenir en cada historia, como **Controller**, **Service**, **Repository**, **DTO** y pruebas.
* En frontend se implementó y documentó el QA de **HU-QA-FE-02**, incluyendo validación del formulario de login, autenticación, almacenamiento del token, redirección después del ingreso y protección de rutas privadas.
* También se implementó y documentó el QA de **HU-QA-FE-07**, cubriendo visualización del historial, filtros por tipo, fecha y usuario, además de validaciones por rol y estados en tabla.
* Se reunieron evidencias visuales de los casos de prueba en la carpeta correspondiente de imágenes.

## ¿Qué no se logró?

* Aunque las historias del bloque **HU-007 a HU-011** quedaron documentadas, varias todavía siguen en estado de planeación o avance parcial, así que aún falta cerrar completamente su implementación en código y pruebas.
* Quedaron pendientes validaciones más completas de integración entre microservicios.
* También hace falta exponer de forma definitiva algunos endpoints a través del **API Gateway**.
* En frontend, el trabajo de esta semana se limitó únicamente a **HU-QA-FE-02** y **HU-QA-FE-07**, por lo que otras historias no fueron abordadas todavía dentro del alcance de la Week 09.

## ¿Qué se va a hacer?

* Terminar la implementación técnica en backend de las historias **HU-007 a HU-011** que todavía estén incompletas.
* Cerrar pruebas unitarias y de integración por cada endpoint.
* Validar el funcionamiento completo de punta a punta por medio del **API Gateway**.
* Seguir fortaleciendo los contratos de la API, especialmente en reportes y filtros de movimientos.
* Ampliar en frontend la cobertura funcional más allá de **HU-QA-FE-02** y **HU-QA-FE-07**, según la prioridad de la siguiente semana.
* Mantener la forma de trabajo por historias de usuario, acompañada de evidencia QA y soporte documental por cada entrega.


## Enlaces de semanas
- [Week 2](https://github.com/jose6668/Week-2.git)
- [Week 3](https://github.com/JerssonF/Week-3)
- [Week 4](https://github.com/JerssonF/Week-4.git)
- [Week 5](https://github.com/jose6668/Week-5.git)
- [Week 6](https://github.com/jose6668/Weeks-6.git)
- [Week 9](https://github.com/Marlon271/Weeks-9.git)
- [Week 10](https://github.com/Marlon271/Weeks-10.git)
  
## 📊 Métrica de Avance del Proyecto

Para evaluar el progreso del proyecto FarmaExpres se definió una métrica basada en los entregables alcanzados en cada semana del desarrollo. Esta medición permite visualizar el avance del proyecto desde la fase de planificación hasta la implementación.

### Progreso por Semana

| Semana | Actividades principales | Entregables | Avance |
|------|------|------|------|
| Week 1 | Definición inicial del proyecto, alcance y conformación del equipo | Idea del proyecto, propósito del sistema, asignación de roles | 10% |
| Week 2 | Identificación y análisis de necesidades del sistema | Documento de necesidades del sistema | 25% |
| Week 3 | Elaboración de requerimientos funcionales y no funcionales | Documento RF y RNF, estructura inicial del sistema | 40% |
| Week 4 | Diseño y arquitectura del sistema | Diagramas y arquitectura del sistema | 60% |
| Week 5 | ADR y validación en staging | ADR documentados, validaciones en staging | 75% |
| Week 6 | Desarrollo e integración de la sexta semana | Frontend modular; HUs: HU-FE-01,03-06 implemented; HU-FE-02,07-10 pending; Backend: HU-doc, HU-MCI | 78% |

### Visualización del Avance

| Semana | Avance |
|---|---:|
| Week 1 | █░░░░░░░░░░ 10% |
| Week 2 | ██░░░░░░░░░ 25% |
| Week 3 | ████░░░░░░░ 40% |
| Week 4 | ██████░░░░░ 60% |
| Week 5 | ███████░░░ 75% |
| Week 6 | ████████░░ 78% |

### Interpretación de la Métrica

- **10% – 30%:** Fase de planificación y análisis del proyecto.  
- **30% – 60%:** Fase de diseño del sistema y definición de arquitectura.  
- **60% – 90%:** Fase de desarrollo e integración de componentes.  
- **90% – 100%:** Pruebas finales, documentación y entrega del sistema.

<sub>Esta métrica permite monitorear el progreso del proyecto y asegurar que cada fase del desarrollo avance de acuerdo con la planificación establecida.</sub>

---



© 2026 FarmaExpres – Proyecto Académico
