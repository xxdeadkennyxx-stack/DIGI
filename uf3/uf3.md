## EC3.1 Identifica las 9 THD

| # | Acrónimo / tecnología | Nombre completo / Significado |
|---|---|---|
| **1** | IoT | *Internet of Things* (Internet de las Cosas) |
| **2** | Big Data | Grandes volúmenes de datos (*Big Data & Analytics*) |
| **3** | IA | Inteligencia Artificial |
| **4** | Cloud | *Cloud Computing* (Computación en la Nube) |
| **5** | Ciberseguridad | Ciberseguridad y Seguridad de la Información |
| **6** | Blockchain | Cadena de Bloques / Tecnologías de Registro Distribuido (DLT) |
| **7** | RPA | *Robotic Process Automation* (Automatización Robótica de Procesos) |
| **8** | Fabricación aditiva | Impresión 3D / Fabricación Aditiva |
| **9** | AR/VR | *Augmented Reality / Virtual Reality* (Realidad Aumentada y Realidad Virtual) |

---

## EC3.2 Quién es quién

| # | Situación | THD correspondiente |
|---|---|---|
| **1** | Un script lee correos, descarga PDFs y extrae datos para rellenar un ERP. | **RPA** |
| **2** | Tres empresas comparten un registro de certificados académicos sin confiar en una autoridad central. | **Blockchain** |
| **3** | Una consultora audita aplicaciones web y hace pruebas de penetración. | **Ciberseguridad** |
| **4** | Una startup lanza su producto sin comprar servidores propios. | **Cloud** |
| **5** | Un almacén imprime la pieza exacta de una máquina cuando esta se rompe. | **Fabricación aditiva** |
| **6** | Una consultora forma equipos de ciberseguridad en simulaciones inmersivas. | **AR/VR** |
| **7** | Un sistema de analítica de logs detecta patrones de ataque en millones de eventos por segundo. | **Big Data** |
| **8** | Sensores en una planta envían datos de temperatura a una plataforma en la nube. | **IoT** |
| **9** | Un asistente virtual resuelve dudas frecuentes de una app. | **IA** |

---

## EC3.3 ¿Qué THD resuelve qué problema de negocio? 

| Problema de negocio | THD propuesta | Justificación |
|---|---|---|
| Tenemos millones de logs pero no sacamos conclusiones operativas. | **Big Data** | Permite procesar, agregar y analizar grandes volúmenes de datos masivos no estructurados en tiempo real. |
| El soporte técnico pierde demasiadas horas en preguntas repetitivas. | **IA (Conversacional)** | Implementa un bot conversacional inteligente para resolver consultas de primer nivel 24/7 sin intervención humana. |
| Debemos garantizar que un certificado digital que emitimos no se falsifique. | **Blockchain** | Permite sellar e inmutabilizar la huella del certificado en un registro distribuido no alterable por terceros. |
| Queremos ofrecer un producto sin invertir en CPD propio. | **Cloud** | Proporciona infraestructura bajo demanda escalable mediante modelo de pago por uso sin costes de capital iniciales. |
| Queremos analizar imágenes de productos para detectar defectos visuales. | **IA (Visión por Computador)** | Entrena modelos de aprendizaje profundo para clasificar e identificar anomalias físicas en tiempo real. |
| Queremos simular entornos industriales para formar personal técnico. | **AR/VR** | Ofrece un entorno inmersivo controlado e interactivo donde el personal practica tareas de riesgo sin peligro real. |

---

## EC3.4 THD y sostenibilidad 

| THD | Cómo contribuye a la sostenibilidad | Ejemplo concreto en una empresa TIC |
|---|---|---|
| **IoT** | Optimiza el uso de recursos energéticos e hídricos mediante monitorización continua y automatización del apagado/regulación. | Monitorización con sensores del consumo en CPDs para optimizar la climatización (*PUE - Power Usage Effectiveness*) en tiempo real. |
| **Cloud** | Consolida servidores físicos infrautilizados en Data Centers eficientes con mayor tasa de ocupación y energía de fuentes renovables. | Migración de servidores locales a AWS/Azure, reduciendo la huella de carbono de la infraestructura mediante virtualización masiva. |
| **RPA** | Elimina completamente la impresión de papel y optimiza flujos de trabajo reduciendo ciclos de cómputo innecesarios. | Automatización de la digitalización y validación de facturas electrónicas, reduciendo a cero el uso de soporte físico de papel. |

---

## EC3.5 Nuevos mercados generados por las THD

### 1. Perfil / Mercado: Especialista en MLOps (DevOps para Machine Learning)
* **THD que lo ha hecho posible:** IA (Inteligencia Artificial) / Cloud.
* **Descripción:** Profesionales dedicados al ciclo de vida del despliegue, monitorización y reentrenamiento continuo de modelos de IA en producción.
* **Ejemplos de actores en el sector TIC catalán / español:** **Predimedical**, **Noddus**, **Clarity AI**, o consultoras especializadas como **NTT DATA España** o **Sener**.

### 2. Perfil / Mercado: Auditor de Contratos Inteligentes / Ciberseguridad Web3
* **THD que lo ha hecho posible:** Blockchain.
* **Descripción:** Mercado dedicado a la revisión del código fuente de *Smart Contracts* para detectar vulnerabilidades informáticas antes de su despliegue en redes descentralizadas.
* **Ejemplos de actores en el sector TIC catalán / español:** **Grant Thornton España** (área Blockchain/Cyber), **Freeverse.io** (Barcelona), **Caelum Labs**.

---

## EC3.6 Parte de negocio vs. parte de planta

| THD | Negocio | Planta | Ambas |
|---|:---:|:---:|:---:|
| **IoT** | | | **X** |
| **Big Data** | | | **X** |
| **IA** | | | **X** |
| **Cloud** | | | **X** |
| **Ciberseguridad** | | | **X** |
| **Blockchain** | | | **X** |
| **RPA** | **X** | | |
| **Fabricación aditiva** | | **X** | |
| **AR/VR** | | | **X** |

---

## EC3.7 Mejoras IT y OT gracias a las THD 

| THD | Mejora IT | Mejora OT |
|---|---|---|
| **IA** | Predicción precisa de demanda para optimizar la compra de licencias, cálculo de costes y planificación financiera en el ERP. | Optimización de ritmos de producción y planificación de paradas de máquinas según previsiones de uso real. |
| **IoT** | Automatización en la entrada de datos al ERP sin necesidad de introducción manual de inventarios por parte del personal. | Captura en tiempo real del estado del stock físico mediante etiquetas RFID/sensores en líneas de montaje. |
| **Big Data** | Capacidad de correlacionar datos de demanda de clientes con factores externos (mercado, meteorología, logística global). | Identificación de cuellos de botella y patrones anómalos de funcionamiento en la maquinaría del taller. |
| **Cloud** | Acceso centralizado, escalable y en movilidad a la información del sistema de gestión desde cualquier sede. | Sincronización continua de datos entre diferentes plantas de producción e integración multi-fábrica. |
