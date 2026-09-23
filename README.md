# ONE-TOUCH SENSE
> **Sistema integral de apoyo, seguimiento y atención remota para pacientes con esquizofrenia**

---

| Datos del Proyecto | Información |
| :--- | :--- |
| **Institución** | Instituto Tecnológico Superior de la Región de los Llanos (ITSRLL) |
| **Carrera** | Ingeniería Informática |
| **Alumno** | Manuela Guadalupe Serrano García |
| **No. de Control** | 23030022 |
| **Profesor** | Sergio Valdéz Rodela |
| **Fecha** | 22 SEP 2026 |

---

## 1. Introducción
**One-Touch Sense** es una propuesta de sistema informático orientada al apoyo, seguimiento y acompañamiento remoto de personas con esquizofrenia y otros trastornos psiquiátricos que requieren atención profesional continua. El proyecto integra una aplicación móvil para pacientes y una plataforma web destinada a profesionales de la salud mental en formación que realizan prácticas profesionales.

La aplicación permitirá registrar información relacionada con el estado emocional, actividades, síntomas, episodios de crisis y avances del paciente. También incorporará recursos de apoyo y contención emocional, tales como ejercicios guiados, actividades y mensajes de orientación. Por su parte, la plataforma web permitirá a los profesionales autorizados consultar la información generada, dar seguimiento a los pacientes asignados y documentar observaciones y avances.

El sistema se plantea como una herramienta complementaria a la atención profesional y no como sustituto del diagnóstico, tratamiento o atención médica presencial. Debido a la naturaleza sensible de la información administrada, el proyecto contempla mecanismos de autenticación, autorización, privacidad, seguridad y auditoría.

---

## 2. Planteamiento del problema
El seguimiento de pacientes con trastornos psiquiátricos puede requerir observación continua de cambios emocionales, síntomas, crisis, actividades y otros factores que no siempre pueden identificarse durante una consulta aislada. Además, algunas personas pueden encontrar dificultades para mantener un seguimiento constante debido a barreras económicas, geográficas, de disponibilidad o de acceso a servicios especializados.

Ante esta situación, surge la necesidad de una herramienta tecnológica que permita recopilar información de manera estructurada y facilitar su consulta por profesionales autorizados. One-Touch Sense propone centralizar estos registros mediante una aplicación móvil y una plataforma web, creando un canal de seguimiento complementario entre pacientes y profesionales.

---

## 3. Justificación
El desarrollo de One-Touch Sense busca aprovechar las tecnologías móviles y los servicios web para facilitar el seguimiento de pacientes y apoyar a profesionales que realizan prácticas en el área de salud mental. La disponibilidad de registros organizados puede ayudar a identificar patrones y cambios que posteriormente puedan ser considerados por el profesional durante el proceso de atención.

El sistema también pretende ofrecer recursos de apoyo emocional previamente definidos y validados por profesionales, así como un mecanismo de asignación de pacientes a profesionales disponibles. De esta manera, el proyecto integra registro de información, seguimiento, comunicación y gestión de pacientes dentro de una misma plataforma.

---

## 4. Objetivo general
Desarrollar un sistema integral compuesto por una aplicación móvil y una plataforma web que facilite el seguimiento remoto y el acompañamiento profesional de pacientes con esquizofrenia, mediante el registro de actividades, estado emocional, síntomas, crisis y avances, así como la asignación de pacientes a profesionales en prácticas autorizados.

---

## 5. Objetivos específicos
- Permitir el registro y autenticación segura de pacientes y profesionales.
- Facilitar el registro periódico del estado emocional, actividades, síntomas y avances del paciente.
- Permitir el registro de episodios de crisis y acontecimientos relevantes.
- Proporcionar actividades y recursos de apoyo emocional.
- Permitir a los profesionales autorizados consultar el historial de seguimiento de sus pacientes.
- Implementar un mecanismo de solicitud y asignación de pacientes.
- Generar indicadores y representaciones gráficas que faciliten la observación de tendencias.
- Implementar controles de acceso, seguridad y auditoría para proteger la información.
- Registrar las acciones relevantes realizadas dentro del sistema.

---

## 6. Alcance
El proyecto contempla el desarrollo de una aplicación móvil para pacientes y una plataforma web para profesionales y administradores. Se incluirán módulos de autenticación, perfiles, seguimiento, registro emocional, crisis, actividades, avances, solicitudes de atención, asignaciones, notificaciones y auditoría.

El sistema no pretende sustituir la consulta médica presencial, emitir diagnósticos autónomos, modificar tratamientos farmacológicos ni atender por sí mismo emergencias psiquiátricas. Las situaciones de riesgo inmediato deberán canalizarse hacia servicios de emergencia o mecanismos de ayuda previamente establecidos.

---

## 7. Usuarios del sistema
- **Paciente:** Utiliza la aplicación móvil para registrar información, consultar recursos de apoyo, reportar crisis, revisar su progreso y solicitar seguimiento profesional.
- **Profesional en prácticas:** Utiliza la plataforma web para consultar pacientes asignados, revisar registros autorizados, documentar seguimiento y registrar avances.
- **Administrador:** Gestiona usuarios, profesionales, contenido, asignaciones, permisos, incidencias y registros de auditoría.

---

## 8. Requerimientos funcionales
- **RF-01:** El sistema deberá permitir registrar cuentas de pacientes y profesionales.
- **RF-02:** El sistema deberá autenticar a los usuarios y aplicar permisos según su rol.
- **RF-03:** El paciente deberá poder registrar su estado emocional.
- **RF-04:** El paciente deberá poder registrar actividades y síntomas.
- **RF-05:** El paciente deberá poder reportar episodios de crisis.
- **RF-06:** El paciente deberá poder consultar recursos de apoyo y contención emocional.
- **RF-07:** El paciente deberá poder solicitar atención profesional.
- **RF-08:** El sistema deberá administrar una lista de espera de pacientes.
- **RF-09:** El sistema deberá permitir asignar pacientes a profesionales disponibles.
- **RF-10:** El profesional deberá poder consultar información de los pacientes que tenga autorizados.
- **RF-11:** El profesional deberá poder registrar notas y avances.
- **RF-12:** El sistema deberá generar notificaciones relacionadas con seguimiento y asignaciones.
- **RF-13:** El administrador deberá poder gestionar usuarios y contenido.
- **RF-14:** El sistema deberá registrar acciones relevantes mediante auditoría.

---

## 9. Requerimientos no funcionales
- **Seguridad:** La información deberá protegerse mediante autenticación, autorización y almacenamiento seguro de credenciales.
- **Privacidad:** El acceso a información sensible deberá limitarse según permisos y consentimiento.
- **Disponibilidad:** El sistema deberá procurar disponibilidad adecuada para permitir el registro y consulta de información.
- **Usabilidad:** Las interfaces deberán ser claras, accesibles y sencillas de utilizar.
- **Escalabilidad:** La arquitectura deberá permitir incorporar nuevos usuarios, módulos y servicios.
- **Mantenibilidad:** El código deberá organizarse por módulos y documentarse adecuadamente.
- **Auditoría:** Las operaciones relevantes sobre información sensible deberán poder rastrearse.

---

## 10. Arquitectura general
One-Touch Sense utilizará una arquitectura cliente-servidor. La aplicación móvil y la plataforma web funcionarán como clientes, mientras que un backend central proporcionará servicios mediante una API. La base de datos almacenará la información estructurada y los servicios complementarios gestionarán autenticación, notificaciones y otras funciones.

+-------------------+      +--------------------+      +------------------+
| Aplicación Móvil  | ---> |                    | ---> |                  |
+-------------------+      | API REST / Backend |      |  Base de Datos   |
|   Plataforma Web  | ---> |                    | ---> |                  |
+-------------------+      +--------------------+      +------------------+

---

## 11. Módulos principales
- **Autenticación:** Registro, inicio de sesión, recuperación de contraseña, sesiones y control de roles.
- **Pacientes:** Administración de datos personales, estado y seguimiento.
- **Profesionales:** Administración del perfil, disponibilidad, validación y pacientes asignados.
- **Seguimiento:** Registro y consulta de estado emocional, síntomas, actividades y evolución.
- **Crisis:** Registro de episodios, intensidad, síntomas, desencadenantes y resultado.
- **Contención emocional:** Catálogo de frases, actividades y recursos de apoyo.
- **Asignación:** Gestión de solicitudes, lista de espera y asignación de pacientes.
- **Notificaciones:** Avisos sobre asignaciones, seguimiento y eventos del sistema.
- **Auditoría:** Registro de acciones relevantes realizadas por los usuarios.

---

## 12. Flujo general
1. El paciente crea una cuenta.
2. Completa la información inicial requerida.
3. Solicita atención profesional.
4. La solicitud pasa a una lista de espera.
5. El sistema identifica un profesional disponible o el administrador realiza la asignación.
6. El paciente registra información mediante la aplicación móvil.
7. El profesional consulta los registros autorizados desde la plataforma web.
8. El profesional documenta seguimiento y avances.
9. La información permanece disponible como historial para el seguimiento autorizado.

---

## 13. Diseño de la base de datos
La base de datos propuesta utiliza un modelo relacional. Las principales entidades son usuarios, pacientes, profesionales, asignaciones, registros emocionales, crisis, actividades, avances, notas clínicas, contenido de contención, solicitudes de atención, notificaciones y auditoría.

### Tabla `usuarios`
| Campo | Tipo | Descripción |
| :--- | :--- | :--- |
| `id_usuario` | INT PK | Identificador |
| `correo` | VARCHAR | Correo electrónico |
| `password_hash` | VARCHAR | Contraseña almacenada mediante hash |
| `rol` | VARCHAR | Rol del usuario |
| `estado` | BOOLEAN | Estado de la cuenta |
| `fecha_registro` | DATETIME | Fecha de registro |

### Tabla `pacientes`
| Campo | Tipo | Descripción |
| :--- | :--- | :--- |
| `id_paciente` | INT PK | Identificador |
| `id_usuario` | INT FK | Usuario asociado |
| `nombre` | VARCHAR | Nombre |
| `apellido_paterno` | VARCHAR | Apellido |
| `apellido_materno` | VARCHAR | Apellido |
| `fecha_nacimiento` | DATE | Fecha de nacimiento |
| `telefono` | VARCHAR | Teléfono |
| `contacto_emergencia` | VARCHAR | Contacto de emergencia |
| `telefono_emergencia` | VARCHAR | Teléfono de emergencia |
| `fecha_ingreso` | DATE | Fecha de incorporación |
| `estado` | VARCHAR | Estado del paciente |

### Tabla `profesionales`
| Campo | Tipo | Descripción |
| :--- | :--- | :--- |
| `id_profesional` | INT PK | Identificador |
| `id_usuario` | INT FK | Usuario asociado |
| `nombre` | VARCHAR | Nombre |
| `apellidos` | VARCHAR | Apellidos |
| `institucion` | VARCHAR | Institución educativa |
| `semestre` | INT | Semestre |
| `periodo_practicas` | VARCHAR | Periodo de prácticas |
| `especialidad` | VARCHAR | Área |
| `disponibilidad` | BOOLEAN | Disponibilidad |
| `estado_validacion` | VARCHAR | Estado de validación |

### Tabla `asignaciones`
| Campo | Tipo | Descripción |
| :--- | :--- | :--- |
| `id_asignacion` | INT PK | Identificador |
| `id_paciente` | INT FK | Paciente |
| `id_profesional` | INT FK | Profesional |
| `fecha_asignacion` | DATETIME | Fecha de asignación |
| `fecha_finalizacion` | DATETIME | Fecha de finalización |
| `estado` | VARCHAR | Estado |

### Tabla `registros_emocionales`
| Campo | Tipo | Descripción |
| :--- | :--- | :--- |
| `id_registro` | INT PK | Identificador |
| `id_paciente` | INT FK | Paciente |
| `fecha` | DATETIME | Fecha |
| `nivel_animo` | INT | Nivel de ánimo |
| `nivel_ansiedad` | INT | Nivel de ansiedad |
| `observaciones` | TEXT | Observaciones |
| `sintomas` | TEXT | Síntomas registrados |

### Tabla `crisis`
| Campo | Tipo | Descripción |
| :--- | :--- | :--- |
| `id_crisis` | INT PK | Identificador |
| `id_paciente` | INT FK | Paciente |
| `fecha_inicio` | DATETIME | Inicio |
| `fecha_fin` | DATETIME | Fin |
| `intensidad` | INT | Nivel de intensidad |
| `desencadenante` | TEXT | Posible desencadenante |
| `sintomas` | TEXT | Síntomas |
| `descripcion` | TEXT | Descripción |
| `resultado` | TEXT | Resultado |

### Tabla `actividades`
| Campo | Tipo | Descripción |
| :--- | :--- | :--- |
| `id_actividad` | INT PK | Identificador |
| `nombre` | VARCHAR | Nombre |
| `descripcion` | TEXT | Descripción |
| `categoria` | VARCHAR | Categoría |
| `duracion` | INT | Duración |
| `instrucciones` | TEXT | Instrucciones |
| `estado` | BOOLEAN | Estado |

### Tabla `actividades_paciente`
| Campo | Tipo | Descripción |
| :--- | :--- | :--- |
| `id_registro` | INT PK | Identificador |
| `id_paciente` | INT FK | Paciente |
| `id_actividad` | INT FK | Actividad |
| `fecha` | DATETIME | Fecha |
| `resultado` | VARCHAR | Resultado |
| `observaciones` | TEXT | Observaciones |

### Tabla `avances`
| Campo | Tipo | Descripción |
| :--- | :--- | :--- |
| `id_avance` | INT PK | Identificador |
| `id_paciente` | INT FK | Paciente |
| `id_profesional` | INT FK | Profesional |
| `fecha` | DATETIME | Fecha |
| `descripcion` | TEXT | Descripción |
| `observaciones` | TEXT | Observaciones |

### Tabla `notas_clinicas`
| Campo | Tipo | Descripción |
| :--- | :--- | :--- |
| `id_nota` | INT PK | Identificador |
| `id_paciente` | INT FK | Paciente |
| `id_profesional` | INT FK | Profesional |
| `fecha` | DATETIME | Fecha |
| `contenido` | TEXT | Contenido |
| `tipo` | VARCHAR | Tipo de nota |

### Tabla `contenido_contencion`
| Campo | Tipo | Descripción |
| :--- | :--- | :--- |
| `id_contenido` | INT PK | Identificador |
| `titulo` | VARCHAR | Título |
| `tipo` | VARCHAR | Tipo de contenido |
| `contenido` | TEXT | Contenido |
| `categoria` | VARCHAR | Categoría |
| `creado_por` | INT FK | Usuario creador |
| `estado` | BOOLEAN | Estado |

### Tabla `solicitudes_atencion`
| Campo | Tipo | Descripción |
| :--- | :--- | :--- |
| `id_solicitud` | INT PK | Identificador |
| `id_paciente` | INT FK | Paciente |
| `fecha_solicitud` | DATETIME | Fecha |
| `prioridad` | VARCHAR | Prioridad |
| `estado` | VARCHAR | Estado |
| `fecha_asignacion` | DATETIME | Fecha de asignación |

### Tabla `notificaciones`
| Campo | Tipo | Descripción |
| :--- | :--- | :--- |
| `id_notificacion` | INT PK | Identificador |
| `id_usuario` | INT FK | Usuario destinatario |
| `titulo` | VARCHAR | Título |
| `mensaje` | TEXT | Mensaje |
| `fecha` | DATETIME | Fecha |
| `leida` | BOOLEAN | Estado de lectura |

### Tabla `auditoria`
| Campo | Tipo | Descripción |
| :--- | :--- | :--- |
| `id_auditoria` | INT PK | Identificador |
| `id_usuario` | INT FK | Usuario |
| `accion` | VARCHAR | Acción |
| `tabla_afectada` | VARCHAR | Tabla afectada |
| `registro_afectado` | INT | Registro afectado |
| `fecha` | DATETIME | Fecha |
| `ip` | VARCHAR | Dirección IP |

---

## 14. Relaciones principales
- Un usuario puede estar asociado con un paciente o con un profesional según su rol.
- Un paciente puede tener múltiples registros emocionales.
- Un paciente puede registrar múltiples episodios de crisis.
- Un paciente puede realizar múltiples actividades.
- Un paciente puede tener múltiples avances y notas de seguimiento.
- Los pacientes y profesionales se relacionan mediante la tabla de asignaciones.
- Las actividades se relacionan con los pacientes mediante la tabla `actividades_paciente`.
- Las acciones relevantes de los usuarios se registran en la tabla de auditoría.

---

## 15. Tecnologías propuestas
- **Aplicación móvil:** Flutter o React Native.
- **Frontend web:** React, Angular o Vue.
- **Backend:** FastAPI con Python.
- **API:** REST.
- **Base de datos:** PostgreSQL o MySQL.
- **Servidor:** Linux/Ubuntu.
- **Notificaciones:** Firebase Cloud Messaging.
- **Visualización de datos:** Chart.js, Recharts u otra biblioteca equivalente.

---

## 16. Seguridad y privacidad
Debido a que el sistema gestionará información personal y potencialmente información relacionada con la salud, la seguridad deberá considerarse un componente fundamental. Se deberán implementar contraseñas protegidas mediante funciones de hash, comunicaciones HTTPS, autenticación, autorización basada en roles, validación de datos, protección contra inyección SQL, control de sesiones, copias de seguridad, auditoría y mecanismos apropiados de cifrado.

También deberá establecerse un modelo de consentimiento informedo y definir claramente qué información puede consultar cada tipo de usuario. El proyecto deberá considerar la legislación y las políticas institucionales aplicables al tratamiento de datos personales y datos relacionados con la salud.

---

## 17. Limitaciones
- El sistema no sustituye la atención médica presencial.
- No deberá emitir diagnósticos psiquiátricos autónomos.
- No deberá modificar tratamientos farmacológicos por decisión automática.
- Los recursos de contención emocional no sustituyen una intervención profesional de emergencia.
- La asignación automática deberá estar sujeta a reglas de seguridad, disponibilidad y supervisión humana.
- La implementación real requerirá validación clínica, legal, ética y de seguridad antes de utilizarse con pacientes reales.

---

## 18. Conclusiones
One-Touch Sense constituye una propuesta de sistema informático que integra una aplicación móvil y una plataforma web para facilitar el seguimiento y acompañamiento de pacientes con esquizofrenia. Su diseño permite centralizar información generada durante el seguimiento, facilitar su consulta por profesionales autorizados y proporcionar recursos complementarios de apoyo emocional.

Desde el punto de vista de ingeniería informática, el proyecto integra elementos de desarrollo móvil, desarrollo web, diseño de bases de datos, APIs, autenticación, seguridad, gestión de usuarios, notificaciones y visualización de información. Para una implementación real, será indispensable complementar el desarrollo tecnológico con validación clínica, protección de datos, supervisión profesional y cumplimiento de la normativa aplicable.

---

## 19. Referencias iniciales
- American Psychiatric Association. (2020). *The American Psychiatric Association Practice Guideline for the Treatment of Patients With Schizophrenia*.
- World Health Organization. (2022). *World mental health report: Transforming mental health for all*. World Health Organization.
- World Health Organization. (2021). *Guidance on ethics and governance of artificial intelligence for health*. World Health Organization.
- OWASP Foundation. (2021). *OWASP Top 10: The Ten Most Critical Web Application Security Risks*.
- FastAPI. Documentación oficial de FastAPI.
- PostgreSQL Global Development Group. Documentación oficial de PostgreSQL.
