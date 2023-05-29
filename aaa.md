<div align="center">

# Monitoreo Consumo Energético Universidad

</div>

## 1. Análisis de la situación

**1.1) Diagrama de clases UML**

![image](https://github.com/diegolopezrm/diegolopezrm/assets/63005462/bcd9e284-ad56-471b-8ac9-b75d84997831)

**1.2) Diagrama de casos de uso**

![image](https://github.com/diegolopezrm/diegolopezrm/assets/63005462/5904f24d-3cd0-494c-b3cd-34add51ef1dd)

**1.3) Análisis de estado - Diagrama de estados del espacio monitoreado**

![image](https://github.com/diegolopezrm/diegolopezrm/assets/63005462/3e37e004-7b5b-431e-95d0-566af554b195)

**1.4) Diagrama de actividades - Creación de un espacio a monitorear**

![image](https://github.com/diegolopezrm/diegolopezrm/assets/63005462/2d169b88-f367-4cfd-b4c2-7d8d21580494)

**1.5) Requerimientos no funcionales**

- :stopwatch: Rendimiento: El sistema debe ser capaz de procesar y mostrar los datos de consumo energético en tiempo real con un retraso máximo de 5 segundos. Esto garantizará que los auditores y los usuarios siempre tengan acceso a los datos más recientes.

- :lock: Seguridad: Todos los datos transmitidos entre los sensores y el sistema de monitoreo deben estar encriptados para proteger la integridad y la confidencialidad de la información. Además, solo los usuarios autorizados deben tener acceso a los datos de consumo energético.

- :repeat: Disponibilidad: El sistema de monitoreo debe tener una disponibilidad del 99.9% para garantizar que los usuarios puedan acceder a la información en cualquier momento que lo necesiten. Para lograr esto, se podría implementar una arquitectura redundante y medidas de recuperación en caso de fallos.

**1.6) Preguntas adicionales**

- :bulb: ¿Cuál es la cantidad y la distribución geográfica de los edificios y espacios dentro de cada campus que se quieren monitorear?
- :computer: ¿Cuál es la capacidad técnica y la infraestructura existente en cada campus?
- :busts_in_silhouette: ¿Cuántos usuarios se espera que interactúen con el sistema y qué tipos de roles tendrán?
- :chart_with_upwards_trend: ¿Cómo se determina el valor de referencia de consumo energético para cada espacio?
- :exclamation: ¿Cómo se espera que se manejen las situaciones en las que el consumo energético excede el valor de referencia?

---

<div align="center">

# Plataforma de arriendo de propiedades por días

</div>

## 2. Análisis de la situación

**2.1) Diagrama de clases UML**

![image](https://github.com/diegolopezrm/diegolopezrm/assets/63005462/e4271a85-8da6-4f23-8a82-4c16942440bd)

**2.2) Diagrama de casos de uso**

![image](https://github.com/diegolopezrm/diegolopezrm/assets/63005462/7dcdc148-a8bc-416c-9677-c56d475ecce2)

**2.3) Análisis de estado - Diagrama de estados de la reserva**

![image](https://github.com/diegolopezrm/diegolopezrm/assets/63005462/bf2b37f4-e462-452f-bebf-bfae6e802d9e)

**2.4) Diagrama de actividades - Realizar una reserva**

![image](https://github.com/diegolopezrm/diegolopezrm/assets/63005462/ee79012f-1877-421f-a76f-abdd903f3c18)

**2.5) Preguntas adicionales**

- :mag_right: ¿Cuáles son los criterios específicos que los usuarios pueden usar para buscar una propiedad en la plataforma?
- :clock2: ¿Hay límites en el tiempo de suspensión de la propiedad por parte del propietario para realizar reparaciones u otras actividades?
- :speech_balloon: ¿Cómo se gestiona la comunicación entre el propietario y el cliente una vez se realiza una reserva?
- :shield: ¿Hay alguna garantía o seguro involucrado en caso de daños a la propiedad durante la estancia del cliente?
- :moneybag: ¿Cómo se gestiona el proceso de pago?

---

<div align="center">

# Modelos de procesos software

</div>

**3.1) ¿Cuál es el objetivo central de un modelo de procesos de desarrollo software?**

El objetivo central de un modelo de procesos de desarrollo de software es proporcionar una estructura que facilite la planificación, organización y control de las actividades involucradas en el desarrollo de un sistema de software. Esto incluye el diseño, codificación, pruebas, mantenimiento, entre otras. Un modelo de proceso actúa como una guía para coordinar y dirigir las tareas de desarrollo, ayudando a garantizar que el resultado final cumpla con los requisitos del cliente y se entregue de manera oportuna y eficiente.

**3.2) ¿Cuáles modelos de proceso de desarrollo software conoce y qué características tienen? Realice un cuadro comparativo de los modelos.**

| Modelo | Características |
| --- | --- |
| Cascada | El proceso se ve como una secuencia de fases que fluyen hacia abajo. Cada fase debe completarse antes de pasar a la siguiente. Los resultados de una fase son los insumos para la siguiente. |
| Iterativo e incremental | El desarrollo se organiza en mini proyectos. Se entregan partes del sistema en cada iteración, permitiendo feedback temprano y adaptación. |
| Espiral | Combina características de los modelos de cascada e iterativo. El desarrollo atraviesa varias iteraciones a lo largo de cuatro fases: determinación de objetivos, análisis de riesgos, desarrollo y planificación. |
| Ágil | Enfatiza la colaboración y la respuesta rápida al cambio. El desarrollo se divide en sprints cortos que producen incrementos funcionales del software. |
| DevOps | Enfatiza la colaboración entre desarrollo y operaciones, buscando acelerar la entrega de software y mejorar su calidad a través de la automatización y la integración continua. |

**3.3) ¿Cuáles son las actividades que están involucradas en el proceso de desarrollo software, con cuál de ellos se siente más afín y por qué?**

Las actividades involucradas en el proceso de desarrollo de software incluyen la especificación de requerimientos, el diseño y arquitectura, la implementación y codificación, las pruebas, el despliegue y el mantenimiento. Personalmente, me siento más afín con la actividad de diseño y arquitectura, ya que es donde se define la estructura y el comportamiento general del sistema. Esta actividad implica un alto nivel de pensamiento abstracto y creatividad, y su éxito es crucial para la eficiencia y eficacia de las etapas posteriores de codificación y pruebas.

**3.4) Identifique y describa un ejemplo donde utilizaría un modelo de proceso ágil (indique cual) y otro donde utilizaría un método tradicional (indique cual)**

- Ejemplo de modelo de proceso ágil (Scrum): Si estuviera desarrollando una aplicación móvil para una start-up que está lanzando su primer producto, usaría Scrum. Este modelo permitiría a nuestro equipo responder rápidamente a los comentarios de los usuarios y hacer ajustes frecuentes a la aplicación para satisfacer mejor sus necesidades y preferencias.

- Ejemplo de método tradicional (Cascada): Si estuviera trabajando en un proyecto de software para una central nuclear, usaría el modelo de Cascada. En este tipo de proyectos, los requisitos son claros desde el inicio y los cambios son costosos y peligrosos. El modelo de cascada permite un mayor control y predicción, que es crucial en estos entornos.

---

<div align="center">

# Ingeniero de Software

</div>

**4.1) ¿Cuál cree que es el rol que juega un ingeniero de software en la industria de tecnologías de la información?**

Un ingeniero de software juega un rol vital en la industria de las tecnologías de la información. Ellos son responsables de diseñar, desarrollar, mantener y probar software que satisface los requisitos específicos de los usuarios y clientes. Además, los ingenieros de software suelen colaborar estrechamente con otros profesionales de TI, como administradores de sistemas y analistas de negocios, para garantizar que el software desarrollado se integre de manera efectiva con los sistemas existentes y soporte los procesos comerciales clave. En esencia, los ingenieros de software son los arquitectos y constructores del mundo digital.

**4.2) ¿Cuáles considera que deben ser las habilidades requeridas por un ingeniero de software para desempeñarse actualmente y cómo cree que pueden ser fortalecidas en el curso de ingeniería de software?**

Existen varias habilidades esenciales para un ingeniero de software hoy en día, que incluyen:

- :computer: Habilidades técnicas: Dominio de lenguajes de programación, sistemas de gestión de bases de datos, entornos de desarrollo y tecnologías web.

- :bulb: Resolución de problemas: Capacidad para desglosar problemas complejos en componentes manejables y encontrar soluciones efectivas.

- :books: Aprendizaje continuo: Habilidad para mantenerse al día con las nuevas herramientas y técnicas a medida que la tecnología evoluciona rápidamente.

- :handshake: Trabajo en equipo y comunicación: Capacidad para colaborar y comunicarse efectivamente con otros desarrolladores y profesionales de TI.

- :briefcase: Entender los requerimientos de negocio: Capacidad para comprender las necesidades y objetivos del negocio y desarrollar soluciones que agreguen valor.

Estas habilidades pueden ser fortalecidas a lo largo del curso de ingeniería de software a través de un enfoque equilibrado de estudio teórico, trabajo práctico en proyectos reales, y aprendizaje de errores y feedback constructivo.

