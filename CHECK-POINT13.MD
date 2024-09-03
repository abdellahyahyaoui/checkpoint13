### 1. What are the parts of a class diagram?

Un **diagrama de clases** es una representación visual de la estructura de un sistema orientado a objetos. Es parte esencial de UML (Unified Modeling Language) y se utiliza para modelar la estructura estática de un sistema, mostrando las clases que lo componen, sus atributos, métodos y las relaciones entre ellas. Las partes principales de un diagrama de clases son:

- **Clases**: Representan las entidades u objetos del sistema. Se dibujan como un rectángulo dividido en tres secciones:
  - **Nombre de la clase**: Parte superior del rectángulo, contiene el nombre de la clase.
  - **Atributos**: Parte central, lista los atributos (o propiedades) de la clase.
  - **Métodos**: Parte inferior, muestra las operaciones o funciones que la clase puede realizar.

- **Relaciones**: Indican cómo interactúan o están conectadas las clases entre sí. Pueden ser:
  - **Asociaciones**: Conexión entre dos clases que indica que una instancia de una clase conoce a la otra.
  - **Generalización/Especialización (Herencia)**: Relación jerárquica donde una clase hija hereda los atributos y métodos de una clase padre.
  - **Agregación**: Relación donde una clase está compuesta por otras clases (relación todo/parte), pero las partes pueden existir independientemente del todo.
  - **Composición**: Un tipo de agregación fuerte donde las partes no pueden existir independientemente del todo.
  - **Dependencias**: Indica que una clase depende de otra para su funcionamiento.

- **Interfaces**: Se representan de manera similar a las clases, pero con el nombre en cursiva o precedido por el estereotipo <<interface>>. Una clase que implementa una interfaz se conecta a ella mediante una relación de realización.

- **Visibilidad de los miembros**: Los atributos y métodos de una clase pueden tener diferentes niveles de visibilidad:
  - **Pública (+)**: Accesible desde cualquier clase.
  - **Privada (-)**: Accesible solo desde dentro de la misma clase.
  - **Protegida (#)**: Accesible desde la misma clase y sus subclases.

---

### 2. Are deployment diagrams structural or behavioral?

Los **diagramas de despliegue** son **estructurales**. Un diagrama de despliegue en UML muestra la disposición física de los nodos de hardware y la asignación de artefactos de software en esos nodos. Estos diagramas se centran en la arquitectura física del sistema y cómo los componentes del sistema se distribuyen y se ejecutan en la infraestructura de hardware.

---

### 3. What is an activity diagram?

Un **diagrama de actividades** en UML es un diagrama **comportamental** que muestra el flujo de trabajo o las actividades dentro de un sistema o proceso. Representa cómo se realiza una operación en términos de la secuencia de pasos o actividades. Los diagramas de actividades son útiles para modelar procesos de negocio, casos de uso complejos y flujos de trabajo detallados.

Componentes principales de un diagrama de actividades:
- **Actividades**: Representan tareas o pasos individuales dentro del proceso.
- **Flujos**: Conectan las actividades y muestran el orden en el que se realizan.
- **Decisiones**: Puntos donde el flujo se bifurca en función de una condición.
- **Acciones**: Operaciones concretas que ocurren dentro de una actividad.
- **Estado inicial y final**: Marcan el comienzo y el final del proceso.

---

### 4. In what way does system design help the development process?

El **diseño de sistemas** es crucial en el proceso de desarrollo porque proporciona una hoja de ruta clara y detallada que guía la implementación del sistema. Ayuda a:

- **Definir la arquitectura**: Establece la estructura de los componentes del sistema y sus interacciones.
- **Reducir la complejidad**: Divide el sistema en partes manejables, facilitando su comprensión y desarrollo.
- **Identificar dependencias**: Ayuda a detectar y gestionar las relaciones entre componentes.
- **Facilitar la comunicación**: Proporciona un lenguaje común para los desarrolladores, arquitectos y otros interesados.
- **Garantizar la calidad**: Un buen diseño reduce errores, mejora la mantenibilidad y asegura que el sistema cumpla con los requisitos.

---

### 5. Why would we use a deployment diagram?

Usamos un **diagrama de despliegue** para:

- **Visualizar la arquitectura física**: Muestra cómo el software se distribuye y se ejecuta en la infraestructura de hardware.
- **Planificar la implementación**: Ayuda a diseñar y organizar la disposición de los componentes del sistema en los servidores, redes y dispositivos.
- **Identificar cuellos de botella**: Ayuda a detectar posibles problemas de rendimiento o de configuración en la infraestructura.
- **Documentar la configuración**: Sirve como referencia para futuras configuraciones, actualizaciones o resolución de problemas.

