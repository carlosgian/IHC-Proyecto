# IHC - PC2 Interacción Humano-Computador

**Alumnos:**

- Armijo Ramos Carlos Gianfranco
- Yarleque Ramos Gabriel

### Descripción de las características importantes de los usuarios del sistema

**Diseño figma:** [HealthAndSalud Design](https://www.figma.com/design/Hr4LcTNhSV0cIbpC8Eeshv/HealthAndSalud?node-id=2005-42&t=v2ftjTUD7wXvc11i-1)  
**Prototipo funcional:** [HealthAndSalud Prototype](https://www.figma.com/proto/Hr4LcTNhSV0cIbpC8Eeshv/HealthAndSalud?node-id=2006-59&starting-point-node-id=2006%3A59&t=R7UnqR27gIZIBYOZ-1)

### Usuarios Objetivos:

#### Pacientes:

- Con enfermedades crónicas que requieren monitoreo constante.
- Adultos mayores o personas con dificultades físicas que necesitan interfaces más accesibles (e.g., comandos por voz).
- Tecnológicamente inexpertas que buscan simplicidad en la interacción.

#### Profesionales médicos:

- Doctores que realizan consultas a distancia.
- Especialistas que realizan diagnósticos o pruebas médicas.
- Personal administrativo encargado de la programación y seguimiento de citas.

#### Cuidadores:

- Familiares o asistentes que ayudan a pacientes, especialmente adultos mayores, con la interacción de la app.

#### Administradores del Sistema:

- Personal encargado de la administración de la plataforma (configuraciones, mantenimiento de datos, etc.).

### Impacto en el diseño:

- Los pacientes que requieren monitoreo constante usarán frecuentemente la aplicación, por lo que debemos asegurarnos de que las tareas que realicen frecuentemente tomen poco tiempo.
- Las personas con dificultades físicas podrían beneficiarse de más accesibilidad, como control por comandos de voz o lectores de pantalla.
- Los pacientes mayores o tecnológicamente inexpertos necesitan una usabilidad simplificada con botones grandes y navegación sencilla.

### Visión general de lo que los usuarios intentan lograr y lo que el sistema hará y por qué es necesario.

#### Objetivos de los Usuarios:

**Pacientes:**

- Acceder a atención médica rápidamente: Programar citas médicas de manera remota, sin necesidad de desplazarse y en horarios convenientes.
- Recibir consultas médicas a distancia: Comunicarse con profesionales médicos a través de videollamadas.
- Acceder a su historial médico: Consultar fácilmente sus diagnósticos previos, recetas y resultados médicos.

**Médicos:**

- Gestionar la agenda de citas: Tener una programación clara y organizada de las citas con sus pacientes.
- Atender consultas de manera eficiente: Realizar consultas remotas mediante videollamadas.
- Prescribir tratamientos: Generar recetas y tratamientos basados en las consultas.

**Administradores del sistema:**

- Mantener el funcionamiento del sistema: Asegurar que la aplicación esté disponible y que los datos de pacientes y médicos estén actualizados.
- Gestionar la programación de citas: Resolver conflictos de horarios, reprogramar citas y garantizar que el calendario de médicos y pacientes esté actualizado.
- Supervisar el rendimiento del sistema: Monitorear la seguridad y estabilidad del sistema para prevenir fallos o problemas técnicos.

### ¿Qué hará el sistema?

- **Programación de citas:** Permite a los pacientes programar, modificar o cancelar citas médicas, y a los administradores gestionar la disponibilidad de los médicos.
- **Video Consultas:** Facilita consultas médicas remotas mediante videollamadas, donde los médicos pueden interactuar con los pacientes y acceder a su historial médico en tiempo real.
- **Gestión del historial médico:** Los médicos podrán acceder y actualizar el historial médico de los pacientes durante las consultas, y los pacientes podrán revisar su información personal en cualquier momento.
- **Mantenimiento del sistema:** Los administradores podrán gestionar usuarios, actualizar datos, realizar copias de seguridad automáticas y supervisar el rendimiento del sistema para asegurar su estabilidad.

### ¿Por qué es necesario este sistema?

- **Aumentan la eficiencia:** Los pacientes pueden programar citas y recibir atención médica sin necesidad de desplazarse.
- **Facilitan la comunicación:** El sistema permite una comunicación fluida entre médicos y pacientes con funciones de videollamadas y mensajes en tiempo real.
- **Mejoran la gestión del tiempo y los recursos:** Los administradores pueden manejar las citas de manera más organizada y evitar solapamientos de horarios.
- **Aumentan la accesibilidad:** Los profesionales médicos pueden atender a más pacientes, incluidos aquellos que requieren seguimiento remoto o consultas rápidas.

### Análisis de tareas

#### Pacientes

| Actividad                  | Requerimiento                                                              |
| -------------------------- | -------------------------------------------------------------------------- |
| Reporte de Síntomas        | Un formulario simple o un sistema de voz para ingresar los síntomas.       |
| Consultar historial médico | Una sección del perfil donde los pacientes puedan visualizar su historial. |
| Programar citas            | Formulario interactivo.                                                    |
| Ver tratamientos           | Listado de tratamientos filtrados por categorías.                          |

#### Profesionales Médicos

| Actividad                        | Requerimiento                                                          |
| -------------------------------- | ---------------------------------------------------------------------- |
| Diagnóstico                      | Información clave (síntomas, historial médico) en una interfaz limpia. |
| Prescripción                     | Base de datos de medicamentos para facilitar las prescripciones.       |
| Revisar historial médico         | Interfaz clara y organizada, accesible solo por personal médico.       |
| Atención de consulta a distancia | Videollamada integrada y acceso al historial médico.                   |

#### Administradores del Sistema

| Actividad                  | Requerimiento                                           |
| -------------------------- | ------------------------------------------------------- |
| Mantenimiento de registros | Interfaz de gestión de datos intuitiva.                 |
| Gestionar Citas            | Calendario dinámico para la gestión eficiente de citas. |

### Priorización de los Requerimientos:

- **Alta:** Reportar síntomas, revisar historial médico, programar citas.
- **Baja:** Responder preguntas frecuentes, generar informes médicos automáticamente.

### Casos de Uso (según los requerimientos)

#### Caso de uso 1: Reportar síntomas

**Actor principal:** Paciente  
**Actor secundario:** Validación de síntomas  
**Flujo del sistema:**

1. El paciente accede al módulo "Reportar síntomas" desde la pantalla de inicio.
2. El sistema presenta un formulario para ingresar síntomas o usar comandos de voz.
3. El paciente ingresa los síntomas.
4. El sistema valida que la información ingresada esté completa.
5. El sistema guarda los síntomas y muestra una confirmación al paciente.
6. El paciente puede continuar usando la aplicación.

#### Caso de uso 2: Programar una Cita Médica

**Actor principal:** Paciente  
**Actor secundario:** Sistema de Calendario  
**Flujo del sistema:**

1. El paciente confirma su nombre, la especialidad, y fecha y hora.
2. El sistema verifica disponibilidad en el calendario.
3. El paciente confirma la cita.
4. El sistema guarda la cita y envía notificación.

#### Caso de uso: Atención de una Consulta a Distancia

**Actor principal:** Médico  
**Actor secundario:** Paciente, Sistema de Videollamada, Sistema de Historial Médico  
**Flujo del sistema:**

1. El médico inicia la videollamada con el paciente.
2. El sistema permite al médico acceder al historial médico del paciente.
3. El médico realiza la consulta y registra información en tiempo real.

#### Caso de uso: Revisar Historial Médico

**Actor principal:** Médico  
**Actor secundario:** Sistema de Historial Médico  
**Flujo del sistema:**

1. El médico accede al perfil del paciente.
2. El sistema muestra el historial médico.
3. El médico filtra la información según la necesidad.
4. El médico revisa el historial y toma decisiones clínicas.

### Análisis de Aplicaciones Similares

#### Medic+

**Descripción:** MediConnect es una aplicación de telemedicina.  
**Funciones Clave:**

- Programación de citas virtuales y presenciales.
- Historial médico disponible para pacientes y médicos.
- Videollamadas integradas para consultas.
- Envío de recetas electrónicas y recordatorios de tratamiento.

#### SANNA

**Descripción:** HealthSync es una plataforma integral de atención médica.  
**Funciones Clave:**

- Videollamadas para consultas a distancia.
- Revisión de signos vitales en tiempo real.
- Sincronización con dispositivos de monitoreo de salud.

### Criterios de Usabilidad Propuestos

- **Simplicidad:** Interfaz intuitiva y fácil de navegar.
- **Eficiencia:** Completar tareas rápidamente.
- **Accesibilidad:** Cumplimiento con estándares de accesibilidad como WCAG.
- **Consistencia:** Diseño y comportamiento coherente.
- **Feedback inmediato:** Retroalimentación clara y rápida.
- **Error Prevention:** Minimizar errores y facilitar su corrección.
