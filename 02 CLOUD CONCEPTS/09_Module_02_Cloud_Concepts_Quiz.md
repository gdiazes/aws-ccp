# Evaluación Modular: Conceptos de la Nube (AWS Cloud Concepts)

Este documento constituye la **evaluación formativa integral del Módulo 02: Conceptos de la Nube**, diseñada bajo los estándares de evaluación y dominios de conocimiento del examen oficial **AWS Certified Cloud Practitioner (CLF-C02)**. Contiene 20 preguntas de opción múltiple estructuradas con justificación técnica exhaustiva y sustentación bajo normas APA 7.ª edición.

> 🚀 **Simulador Interactivo en Tiempo Real:**  
> Puede ejecutar esta evaluación con temporizador, selección de opciones y cálculo automático de nota vigesimal de dos formas:  
> - 🌐 **[Ejecutar Simulador Online con 1 Clic (Navegador Web)](https://htmlpreview.github.io/?https://github.com/gdiazes/aws-ccp/blob/main/02%20CLOUD%20CONCEPTS/09_Module_02_Cloud_Concepts_Interactive_Quiz.html)**  
> - 💻 **En su equipo local:** Abrir haciendo doble clic en el archivo [09_Module_02_Cloud_Concepts_Interactive_Quiz.html](09_Module_02_Cloud_Concepts_Interactive_Quiz.html) en Chrome, Edge o su navegador favorito.

---

## 📊 Baremo de Calificación en Sistema Vigesimal (Escala 0 a 20)

La evaluación asigna **1.00 punto** por cada respuesta correcta, totalizando una escala vigesimal de **0 a 20 puntos**, alineada proporcionalmente con el puntaje escalado oficial de AWS (100 a 1000 puntos):

| Calificación Vigesimal (0 - 20) | Aciertos (/20) | Porcentaje (%) | Equivalencia Escala AWS (100 - 1000) | Condición Académica |
| :---: | :---: | :---: | :---: | :---: |
| **19.0 – 20.0** | 19 – 20 | 95% – 100% | 955 – 1000 | **Excelente (Sobresaliente)** |
| **17.0 – 18.0** | 17 – 18 | 85% – 90% | 865 – 910 | **Muy Bueno (Avanzado)** |
| **14.0 – 16.0** | 14 – 16 | 70% – 80% | **730 – 820** | **Aprobado (Criterio Mínimo)** |
| **11.0 – 13.0** | 11 – 13 | 55% – 65% | 595 – 685 | **En Desarrollo (Requiere Repaso)** |
| **0.0 – 10.0** | 0 – 10 | 0% – 50% | 100 – 550 | **Desaprobado (Revisión Completa)** |

> ⚠️ **Criterio de Aprobación Oficial:** La nota mínima aprobatoria es **14.00 / 20 puntos (70%)**, equivalente a obtener $\ge 700 / 1000$ puntos en el examen oficial de AWS (Amazon Web Services, 2023a).

## Cuestionario de Evaluación (20 Preguntas)

### Pregunta 01
**¿Cuál de las siguientes afirmaciones describe con mayor precisión la definición de computación en la nube según el estándar NIST SP 800-145 y Amazon Web Services?**

- A) Un modelo de entrega que requiere la compra previa de servidores físicos dedicados para garantizar la soberanía de los datos.
- B) La entrega bajo demanda de recursos de TI a través de Internet con una estructura de precios basada en el pago por uso.
- C) Una plataforma exclusiva de virtualización local que elimina la necesidad de conectividad a redes públicas.
- D) Un entorno de desarrollo de software propietario gestionado exclusivamente por el equipo interno de operaciones de TI.

<details>
<summary><b>Ver Respuesta y Justificación Técnica</b></summary>

> **Respuesta Correcta: B**
> 
> **Justificación Técnica:**  
> Según el National Institute of Standards and Technology (Mell & Grance, 2011) y Amazon Web Services (2021), la computación en la nube se define como la entrega bajo demanda de potencia de cómputo, almacenamiento de bases de datos, aplicaciones y otros recursos de TI a través de Internet, con un esquema de precios de pago por uso (*pay-as-you-go*), eliminando inversiones anticipadas en infraestructura.
> 
> **Análisis de Opciones Incorrectas:**
> - **A:** Es incorrecta porque la compra previa de servidores físicos corresponde al modelo tradicional de inversión de capital (*CapEx*) en centros de datos locales.
> - **C:** Es incorrecta porque la nube se fundamenta en el acceso ubicuo a través de la red y no se restringe a virtualizaciones locales aisladas.
> - **D:** Es incorrecta porque la computación en la nube no se limita a entornos propietarios ni a la gestión interna exclusiva de TI.
> 
> **Referencia Primaria:** (Mell & Grance, 2011; Amazon Web Services, 2021).
</details>

---

### Pregunta 02
**Una empresa emergente desea evitar la adquisición anticipada de infraestructura de servidores antes de conocer la demanda real de sus clientes. ¿Cuál de las seis ventajas de la nube de AWS aborda directamente esta necesidad?**

- A) Cambiar el gasto de capital (CapEx) por un gasto variable (OpEx).
- B) Aumentar la velocidad y la agilidad de desarrollo.
- C) Desplegar aplicaciones a escala global en cuestión de minutos.
- D) Beneficiarse de economías de escala masivas.

<details>
<summary><b>Ver Respuesta y Justificación Técnica</b></summary>

> **Respuesta Correcta: A**
> 
> **Justificación Técnica:**  
> Cambiar los gastos de capital (*Capital Expenditures - CapEx*) por gastos variables u operativos (*Operational Expenditures - OpEx*) permite a las organizaciones pagar únicamente por los recursos informáticos consumidos en tiempo real, en lugar de invertir elevadas sumas financieras en centros de datos y hardware físico antes de iniciar operaciones (Amazon Web Services, 2021).
> 
> **Análisis de Opciones Incorrectas:**
> - **B:** Se refiere a la rapidez con la que los desarrolladores aprovisionan recursos mediante APIs, pero no describe primariamente el cambio en la estructura financiera de inversión.
> - **C:** Se enfoca en la reducción de latencia y alcance geográfico mediante regiones internacionales.
> - **D:** Se refiere a la reducción de precios unitarios que AWS traslada a los clientes gracias al volumen agregado de cientos de miles de usuarios.
> 
> **Referencia Primaria:** (Amazon Web Services, 2021, 2023a).
</details>

---

### Pregunta 03
**¿Por qué los clientes de AWS obtienen precios unitarios más bajos por gigabyte de almacenamiento o ciclo de procesamiento en comparación con lo que lograrían administrando su propio centro de datos?**

- A) Debido a acuerdos comerciales obligatorios de permanencia a largo plazo.
- B) Debido a que el uso agregado de cientos de miles de clientes genera economías de escala masivas que AWS traslada en reducciones de precios.
- C) Debido a que AWS subvenciona el hardware mediante publicidad en la consola de gestión.
- D) Debido al uso exclusivo de hardware reacondicionado en todas las regiones globales.

<details>
<summary><b>Ver Respuesta y Justificación Técnica</b></summary>

> **Respuesta Correcta: B**
> 
> **Justificación Técnica:**  
> Gracias a la agregación del tráfico y consumo de cientos de miles de clientes en la nube, AWS logra niveles de adquisición y eficiencia operativa de escala extrema, lo cual se traduce en menores costos de operación que son trasladados periódicamente a los clientes en forma de reducciones sistemáticas de tarifas (Amazon Web Services, 2021, 2024a).
> 
> **Análisis de Opciones Incorrectas:**
> - **A:** AWS no exige contratos forzosos ni acuerdos de permanencia para acceder a los precios base bajo demanda.
> - **C:** AWS no incluye publicidad en sus consolas de administración ni subvenciona infraestructura bajo ese esquema.
> - **D:** La infraestructura de AWS utiliza hardware de grado empresarial de última generación diseñado específicamente para alta resiliencia.
> 
> **Referencia Primaria:** (Amazon Web Services, 2021, 2024a).
</details>

---

### Pregunta 04
**¿Qué principio de la nube de AWS elimina el riesgo de sobreaprovisionar hardware innecesario o quedarse sin capacidad ante picos imprevistos de tráfico de usuarios?**

- A) Dejar de gastar dinero en la ejecución y mantenimiento de centros de datos.
- B) Dejar de adivinar la capacidad (*Stop guessing capacity*).
- C) Despliegue global en cuestión de minutos.
- D) Delegación del cumplimiento normativo al proveedor de nube.

<details>
<summary><b>Ver Respuesta y Justificación Técnica</b></summary>

> **Respuesta Correcta: B**
> 
> **Justificación Técnica:**  
> La capacidad elástica de AWS permite a las organizaciones aprovisionar exactamente los recursos necesarios y escalarlos automáticamente hacia arriba (*scale-out*) o hacia abajo (*scale-in*) en respuesta a la demanda real, eliminando la necesidad de estimar o adivinar previamente la capacidad de infraestructura estática (Amazon Web Services, 2021, 2024b).
> 
> **Análisis de Opciones Incorrectas:**
> - **A:** Se refiere a delegar la gestión física de racks, climatización y energía, pero no al dimensionamiento dinámico de capacidad.
> - **C:** Se refiere a la distribución geográfica en múltiples regiones de AWS.
> - **D:** La seguridad y el cumplimiento normativo se rigen por el modelo de responsabilidad compartida, no por una delegación total al proveedor.
> 
> **Referencia Primaria:** (Amazon Web Services, 2021, 2024b).
</details>

---

### Pregunta 05
**En un entorno tradicional on-premises, la adquisición de nuevos servidores puede demorar entre semanas y meses. En AWS, los desarrolladores pueden desplegar instancias en minutos. ¿Qué ventaja de la nube representa esta capacidad?**

- A) Aumentar la velocidad y la agilidad (*Increase speed and agility*).
- B) Alta disponibilidad mediante redundancia activa.
- C) Recuperación ante desastres (*Disaster Recovery*).
- D) Gobernanza unificada de cuentas.

<details>
<summary><b>Ver Respuesta y Justificación Técnica</b></summary>

> **Respuesta Correcta: A**
> 
> **Justificación Técnica:**  
> La disponibilidad instantánea de recursos informáticos mediante interfaces programables (APIs) y la consola de administración reduce el tiempo necesario para poner recursos a disposición de los desarrolladores de meses a minutos, incrementando drásticamente la agilidad operativa y la capacidad de experimentación e innovación de la organización (Amazon Web Services, 2021).
> 
> **Análisis de Opciones Incorrectas:**
> - **B:** La alta disponibilidad es una propiedad arquitectónica de tolerancia a fallos, no la métrica de tiempo de aprovisionamiento.
> - **C:** La recuperación ante desastres describe las estrategias de continuidad de negocio ante contingencias graves.
> - **D:** La gobernanza unificada se asocia a servicios como AWS Organizations y Control Tower.
> 
> **Referencia Primaria:** (Amazon Web Services, 2021, 2023a).
</details>

---

### Pregunta 06
**Una organización desea enfocar a su personal técnico en el desarrollo de software y en la diferenciación del negocio, en lugar de gestionar sistemas de enfriamiento, cableado y racks de servidores. ¿Qué ventaja de AWS describe este cambio estratégico?**

- A) Dejar de gastar dinero en ejecutar y mantener centros de datos.
- B) Aumento de los costos de capital.
- C) Despliegue en entornos multi-nube privados.
- D) Contratación obligatoria de soporte Enterprise.

<details>
<summary><b>Ver Respuesta y Justificación Técnica</b></summary>

> **Respuesta Correcta: A**
> 
> **Justificación Técnica:**  
> Al migrar a AWS, las organizaciones delegan las tareas de infraestructura no diferenciadas (*heavy lifting* de infraestructura física, como electricidad, cableado estructurado, mantenimiento de servidores físicos y refrigeración), permitiendo que los equipos se concentren exclusivamente en proyectos de valor de negocio (Amazon Web Services, 2021).
> 
> **Análisis de Opciones Incorrectas:**
> - **B:** La nube reduce los costos de capital al convertirlos en gastos operativos variables.
> - **C:** El enfoque no promueve la gestión de infraestructura física privada, sino la adopción de servicios gestionados en la nube.
> - **D:** Ningún nivel de soporte es obligatorio para aprovechar la reducción de mantenimiento físico en AWS.
> 
> **Referencia Primaria:** (Amazon Web Services, 2021).
</details>

---

### Pregunta 07
**Una empresa basada en América Latina necesita expandir sus servicios de comercio electrónico a usuarios en Europa y Asia con tiempos mínimos de latencia. ¿Qué ventaja de AWS permite habilitar esta expansión de manera inmediata?**

- A) Desplegar globalmente en minutos (*Go global in minutes*).
- B) Pago por uso reservado con compromiso a 3 años.
- C) Conversión de OpEx en CapEx.
- D) Aprovisionamiento estático mediante hardware dedicado.

<details>
<summary><b>Ver Respuesta y Justificación Técnica</b></summary>

> **Respuesta Correcta: A**
> 
> **Justificación Técnica:**  
> La infraestructura global de AWS, compuesta por múltiples regiones interconectadas y una red perimetral de Puntos de Presencia (*Edge Locations*), permite desplegar aplicaciones en múltiples zonas geográficas del mundo con unos pocos clics, reduciendo la latencia percibida por los usuarios finales (Amazon Web Services, 2021, 2023a).
> 
> **Análisis de Opciones Incorrectas:**
> - **B:** Las instancias reservadas representan una opción de precios para optimizar costos estables, no el mecanismo de alcance global inmediato.
> - **C:** La nube convierte CapEx en OpEx, no a la inversa.
> - **D:** El aprovisionamiento estático limita la elasticidad y la rapidez de expansión geográfica.
> 
> **Referencia Primaria:** (Amazon Web Services, 2021, 2023a).
</details>

---

### Pregunta 08
**¿Cuál de los siguientes modelos de servicios en la nube proporciona al cliente el mayor nivel de control y responsabilidad sobre el sistema operativo, las configuraciones de red y los entornos de ejecución?**

- A) Software as a Service (SaaS).
- B) Infrastructure as a Service (IaaS).
- C) Platform as a Service (PaaS).
- D) Function as a Service (FaaS) completamente gestionado.

<details>
<summary><b>Ver Respuesta y Justificación Técnica</b></summary>

> **Respuesta Correcta: B**
> 
> **Justificación Técnica:**  
> En el modelo de Infraestructura como Servicio (*IaaS*), como Amazon EC2, AWS administra la infraestructura física subyacente y la capa de virtualización, mientras que el cliente retiene el control total sobre la elección, configuración, parches y administración del sistema operativo, el software de red y las aplicaciones (Mell & Grance, 2011; Amazon Web Services, 2021).
> 
> **Análisis de Opciones Incorrectas:**
> - **A:** En SaaS el proveedor gestiona la totalidad de la pila tecnológica; el usuario solo interactúa con la interfaz final de la aplicación.
> - **C:** En PaaS el proveedor gestiona el sistema operativo, parches de seguridad y runtime, dejando al cliente solo la gestión del código y los datos.
> - **D:** En FaaS (ej. AWS Lambda), el entorno de ejecución está 100% abstraído y gestionado por AWS.
> 
> **Referencia Primaria:** (Mell & Grance, 2011; Amazon Web Services, 2021, 2023b).
</details>

---

### Pregunta 09
**Un equipo de desarrollo web desea desplegar una aplicación en la nube sin tener que instalar parches en el sistema operativo, administrar el software del servidor web ni configurar la infraestructura subyacente. ¿Qué modelo de computación en la nube representa este escenario?**

- A) Infrastructure as a Service (IaaS).
- B) Platform as a Service (PaaS).
- C) On-Premises Bare Metal.
- D) Disaster Recovery as a Service (DRaaS).

<details>
<summary><b>Ver Respuesta y Justificación Técnica</b></summary>

> **Respuesta Correcta: B**
> 
> **Justificación Técnica:**  
> Plataforma como Servicio (*PaaS*), ejemplificado por servicios como AWS Elastic Beanstalk, abstrae la complejidad de la gestión de sistemas operativos, parches, balanceadores de carga y aprovisionamiento de hardware, permitiendo que el equipo se enfoque exclusivamente en el desarrollo e implementación de su código de aplicación (Mell & Grance, 2011; Amazon Web Services, 2021).
> 
> **Análisis de Opciones Incorrectas:**
> - **A:** En IaaS el cliente es responsable directo del mantenimiento y parcheo del sistema operativo.
> - **C:** On-Premises Bare Metal exige la administración física completa del hardware y el hipervisor.
> - **D:** DRaaS es una solución específica para continuidad operativa, no un modelo estándar de plataforma de desarrollo de aplicaciones.
> 
> **Referencia Primaria:** (Mell & Grance, 2011; Amazon Web Services, 2021).
</details>

---

### Pregunta 10
**¿Cuál de las siguientes opciones describe un servicio clasificado dentro del modelo Software as a Service (SaaS)?**

- A) Aprovisionamiento de una instancia Amazon EC2 con Ubuntu Linux.
- B) Creación de una VPC con subredes públicas y privadas.
- C) Una aplicación web completa para visualización de métricas de negocio (como Amazon QuickSight) donde el usuario no gestiona ningún componente de infraestructura ni plataforma.
- D) Configuración de un volumen de almacenamiento en bloque Amazon EBS.

<details>
<summary><b>Ver Respuesta y Justificación Técnica</b></summary>

> **Respuesta Correcta: C**
> 
> **Justificación Técnica:**  
> El modelo *Software as a Service (SaaS)* entrega un producto de software terminado y completamente operativo que es ejecutado y gestionado por el proveedor de servicios (Amazon Web Services, 2021). El usuario final consume la funcionalidad directamente sin preocuparse por servidores, sistemas operativos, bases de datos o capas de red.
> 
> **Análisis de Opciones Incorrectas:**
> - **A, B y D:** Amazon EC2, Amazon VPC y Amazon EBS son componentes fundamentales clasificados bajo el modelo de Infraestructura como Servicio (*IaaS*).
> 
> **Referencia Primaria:** (Mell & Grance, 2011; Amazon Web Services, 2021).
</details>

---

### Pregunta 11
**Una institución financiera mantiene su base de datos confidencial en sus servidores locales por requisitos de auditoría interna, pero ejecuta sus portales web públicos elásticos en AWS conectados mediante una conexión dedicada segura. ¿Qué modelo de despliegue en la nube se está utilizando?**

- A) Nube Pública pura.
- B) Nube Híbrida.
- C) Nube Privada aislada.
- D) Entorno Multi-Tenant On-Premises.

<details>
<summary><b>Ver Respuesta y Justificación Técnica</b></summary>

> **Respuesta Correcta: B**
> 
> **Justificación Técnica:**  
> El modelo de despliegue de **Nube Híbrida** conecta de manera transparente la infraestructura local (*on-premises*) existente de una organización con los recursos basados en la nube pública (utilizando tecnologías como AWS Direct Connect o AWS Site-to-Site VPN), permitiendo extender y combinar lo mejor de ambos mundos (Amazon Web Services, 2021, 2024b).
> 
> **Análisis de Opciones Incorrectas:**
> - **A:** La nube pública pura implica que la totalidad de las cargas de trabajo reside en el proveedor de nube.
> - **C:** La nube privada implica que todos los recursos residen exclusivamente dentro de la infraestructura local o dedicada de una sola organización.
> - **D:** No describe la integración bidireccional entre centros de datos locales y servicios elásticos en la nube pública.
> 
> **Referencia Primaria:** (Amazon Web Services, 2021, 2024b).
</details>

---

### Pregunta 12
**¿Cuál es una característica fundamental de una Región de AWS (*AWS Region*)?**

- A) Es un centro de datos físico individual ubicado en una ciudad específica.
- B) Es una ubicación geográfica en el mundo que contiene múltiples Zonas de Disponibilidad (AZs) aisladas e interconectadas mediante enlaces de red redundantes de baja latencia.
- C) Es una partición lógica de software que solo puede contener un máximo de 10 servidores virtuales.
- D) Es un punto de presencia perimetral utilizado exclusivamente para el almacenamiento en frío de respaldos.

<details>
<summary><b>Ver Respuesta y Justificación Técnica</b></summary>

> **Respuesta Correcta: B**
> 
> **Justificación Técnica:**  
> Una **Región de AWS** es una ubicación física y geográfica separada en el mundo compuesta por un clúster de múltiples **Zonas de Disponibilidad (AZs)** completamente aisladas e independientes en términos de alimentación, refrigeración y seguridad física, pero conectadas mediante enlaces de fibra óptica dedicados de altísimo ancho de banda y latencia inferior a 2 milisegundos (Amazon Web Services, 2023a, 2024b).
> 
> **Análisis de Opciones Incorrectas:**
> - **A:** Una Región nunca es un único centro de datos; está compuesta obligatoriamente por al menos 3 Zonas de Disponibilidad.
> - **C:** Las regiones no imponen restricciones arbitrarias de 10 servidores y abarcan una infraestructura masiva a nivel de hardware.
> - **D:** Describe incorrectamente los Puntos de Presencia (*Edge Locations*) o las bóvedas de Amazon S3 Glacier.
> 
> **Referencia Primaria:** (Amazon Web Services, 2023a, 2024b).
</details>

---

### Pregunta 13
**¿Por qué las Zonas de Disponibilidad (AZs) dentro de una misma Región de AWS están físicamente separadas por distancias significativas (generalmente decenas de kilómetros)?**

- A) Para evitar el cumplimiento de las normativas fiscales del país donde operan.
- B) Para garantizar el aislamiento ante desastres físicos locales (inundaciones, cortes eléctricos generalizados, terremotos) y mitigar el riesgo de fallas correlacionadas.
- C) Para incrementar deliberadamente la latencia entre bases de datos primarias y secundarias.
- D) Para permitir que diferentes clientes utilicen diferentes proveedores de hardware dentro de la misma región.

<details>
<summary><b>Ver Respuesta y Justificación Técnica</b></summary>

> **Respuesta Correcta: B**
> 
> **Justificación Técnica:**  
> La separación física entre Zonas de Disponibilidad está calculada para asegurar que un desastre físico local (como un corte energético metropolitano, incendio o fenómeno climático) no afecte a las demás zonas de la misma región, permitiendo a los clientes diseñar arquitecturas altamente disponibles y con tolerancia a fallos (Amazon Web Services, 2023a, 2024b).
> 
> **Análisis de Opciones Incorrectas:**
> - **A:** Todas las AZs de una región cumplen con los marcos legales y regulatorios de la jurisdicción geográfica correspondiente.
> - **C:** La red entre AZs está diseñada para minimizar la latencia (< 2 ms) para permitir replicación sincrónica.
> - **D:** No tiene relación con la ingeniería de resiliencia y aislamiento geográfico de fallas.
> 
> **Referencia Primaria:** (Amazon Web Services, 2023a, 2024b).
</details>

---

### Pregunta 14
**¿Qué componente de la infraestructura global de AWS se utiliza para almacenar en caché contenido web y distribuirlo con latencias ultrabajas a los usuarios finales de todo el mundo mediante Amazon CloudFront?**

- A) Zonas de Disponibilidad Secundarias.
- B) Puntos de Presencia (*Edge Locations* / PoP).
- C) Puertas de enlace de clientes (*Customer Gateways*).
- D) Servidores de administración de consola local.

<details>
<summary><b>Ver Respuesta y Justificación Técnica</b></summary>

> **Respuesta Correcta: B**
> 
> **Justificación Técnica:**  
> Los **Puntos de Presencia (*Edge Locations*)** forman la red perimetral de distribución de contenido de AWS (*Content Delivery Network - CDN*). Servicios como Amazon CloudFront y AWS Route 53 utilizan estos puntos distribuidos en cientos de ciudades globales para almacenar en caché datos estáticos y dinámicos cerca del usuario final, reduciendo drásticamente la latencia de red (Amazon Web Services, 2023a).
> 
> **Análisis de Opciones Incorrectas:**
> - **A:** Las Zonas de Disponibilidad alojan las cargas de trabajo de cómputo y bases de datos principales dentro de regiones, no la red perimetral distribuida en cientos de ciudades.
> - **C:** Es el recurso de red on-premises utilizado para configurar un túnel VPN hacia AWS.
> - **D:** No existe tal componente en la taxonomía de infraestructura global de AWS.
> 
> **Referencia Primaria:** (Amazon Web Services, 2023a).
</details>

---

### Pregunta 15
**Una empresa desea comenzar a utilizar los servicios de AWS bajo el modelo de la Capa Gratuita (*AWS Free Tier*). ¿Cuáles son los tres tipos de ofertas disponibles bajo este programa?**

- A) Gratuito para siempre (*Always Free*), 12 meses gratis (*12 Months Free*) y Pruebas a corto plazo (*Trials*).
- B) Básico, Comercial y Empresarial.
- C) Descuento por volumen, Pago anticipado y Créditos gubernamentales.
- D) Comunitario, Educativo e Industrial.

<details>
<summary><b>Ver Respuesta y Justificación Técnica</b></summary>

> **Respuesta Correcta: A**
> 
> **Justificación Técnica:**  
> El programa *AWS Free Tier* se divide formalmente en tres tipos de beneficios (Amazon Web Services, 2024a):
> 1. **Siempre Gratis (*Always Free*):** Servicios disponibles de manera continua sin caducidad mientras no se superen los límites mensuales (ej. 1 millón de invocaciones en AWS Lambda).
> 2. **12 Meses Gratis (*12 Months Free*):** Beneficios activos durante el primer año tras la creación de la cuenta (ej. 750 horas de EC2 t2.micro/t3.micro y 5 GB en S3).
> 3. **Pruebas (*Trials*):** Acceso gratuito temporal por un periodo corto desde la activación del servicio específico (ej. 2 meses de Amazon Redshift).
> 
> **Análisis de Opciones Incorrectas:**
> - **B:** Corresponde a los niveles de planes de soporte técnico de AWS (*AWS Support Plans*).
> - **C y D:** No representan la clasificación formal de las modalidades de la capa gratuita de AWS.
> 
> **Referencia Primaria:** (Amazon Web Services, 2024a).
</details>

---

### Pregunta 16
**Al crear una nueva cuenta de AWS, ¿cuál es la mejor práctica de seguridad crítica que debe aplicarse de forma inmediata sobre el Usuario Raíz (*Root User*)?**

- A) Compartir las credenciales de acceso con todos los ingenieros de desarrollo.
- B) Habilitar la Autenticación Multifactor (MFA), abstenerse de generar claves de acceso de API para uso diario y crear usuarios IAM con privilegios mínimos.
- C) Desactivar las políticas de contraseñas complejas para agilizar los inicios de sesión.
- D) Utilizar el usuario raíz para ejecutar scripts automatizados de despliegue continuo (CI/CD).

<details>
<summary><b>Ver Respuesta y Justificación Técnica</b></summary>

> **Respuesta Correcta: B**
> 
> **Justificación Técnica:**  
> El usuario raíz posee acceso irrestricto y absoluto a todos los recursos, configuraciones y facturación de la cuenta de AWS. Las mejores prácticas de seguridad de AWS establecen que debe asegurarse inmediatamente con **MFA (Autenticación Multifactor)**, bloquear sus claves de acceso y crear usuarios administrativos en **AWS IAM** bajo el principio de privilegio mínimo para las actividades operativas cotidianas (Amazon Web Services, 2023b).
> 
> **Análisis de Opciones Incorrectas:**
> - **A, C y D:** Representan violaciones graves a los principios elementales de seguridad y exponen la cuenta a compromisos catastróficos.
> 
> **Referencia Primaria:** (Amazon Web Services, 2023b).
</details>

---

### Pregunta 17
**¿Cuál de las siguientes herramientas integradas en la Consola de Administración de AWS permite ejecutar comandos de AWS CLI directamente desde el navegador web mediante un entorno Linux autenticado con 1 GB de almacenamiento persistente sin costo adicional?**

- A) AWS CloudShell.
- B) AWS Systems Manager Fleet Manager.
- C) Amazon Elastic Compute Cloud (EC2) Dedicated Host.
- D) AWS Outposts Terminal.

<details>
<summary><b>Ver Respuesta y Justificación Técnica</b></summary>

> **Respuesta Correcta: A**
> 
> **Justificación Técnica:**  
> **AWS CloudShell** es un shell basado en navegador que permite administrar, interactuar y ejecutar scripts con herramientas de línea de comandos de AWS preinstaladas (AWS CLI, SDKs, Node.js, Python) desde la propia consola web, proporcionando 1 GB de almacenamiento persistente en el directorio personal `$HOME` por cada región sin costo adicional (Amazon Web Services, 2023a).
> 
> **Análisis de Opciones Incorrectas:**
> - **B:** Fleet Manager es una función de Systems Manager para administración remota de nodos gestionados en servidores, no la consola shell basada en navegador.
> - **C:** Es un servidor físico dedicado de EC2 para cumplir requerimientos de licenciamiento.
> - **D:** AWS Outposts extiende la infraestructura física de AWS a centros de datos locales.
> 
> **Referencia Primaria:** (Amazon Web Services, 2023a).
</details>

---

### Pregunta 18
**¿Qué herramienta disponible desde la Consola de Administración de AWS proporciona recomendaciones automatizadas organizadas en cinco pilares clave (Optimización de Costos, Rendimiento, Seguridad, Tolerancia a Fallos y Límites de Servicio)?**

- A) AWS Trusted Advisor.
- B) AWS Billing Conductor.
- C) AWS Application Discovery Service.
- D) AWS Fault Injection Simulator.

<details>
<summary><b>Ver Respuesta y Justificación Técnica</b></summary>

> **Respuesta Correcta: A**
> 
> **Justificación Técnica:**  
> **AWS Trusted Advisor** es una herramienta de inspección automatizada que analiza los recursos de la cuenta de AWS y emite recomendaciones operativas en tiempo real estructuradas en 5 categorías fundamentales: **Optimización de Costos, Rendimiento, Seguridad, Tolerancia a Fallos y Límites de Servicio / Cuotas** (Amazon Web Services, 2024b).
> 
> **Análisis de Opciones Incorrectas:**
> - **B:** Se utiliza para personalizar y estructurar la facturación para clientes o unidades de negocio.
> - **C:** Ayuda a planificar migraciones recopilando información sobre servidores on-premises.
> - **D:** Es una plataforma para realizar pruebas de ingeniería del caos.
> 
> **Referencia Primaria:** (Amazon Web Services, 2024b).
</details>

---

### Pregunta 19
**¿Cuál de los siguientes servicios NO está incluido dentro del alcance de los Planes de Soporte estándar de AWS (*AWS Support Plans*)?**

- A) Asistencia para la resolución y depuración de errores en los servicios de AWS.
- B) Orientación técnica sobre la configuración de servicios y mejores prácticas de arquitectura general.
- C) Consultoría profunda y diseño integral de la arquitectura personalizada de software y aplicaciones de un cliente.
- D) Acceso al centro de soporte para consultas operativas sobre facturación y límites de cuenta.

<details>
<summary><b>Ver Respuesta y Justificación Técnica</b></summary>

> **Respuesta Correcta: C**
> 
> **Justificación Técnica:**  
> Los planes de soporte de AWS brindan asistencia técnica, resolución de incidentes y orientación de mejores prácticas, pero **no incluyen consultoría de desarrollo ni diseño integral a medida de la arquitectura de aplicaciones del cliente**. Para consultoría estratégica y diseño de software personalizado, los clientes deben contratar los servicios de **AWS Professional Services** o socios certificados de la red de socios de AWS (*APN Partners*) (Amazon Web Services, 2023a, 2024c).
> 
> **Análisis de Opciones Incorrectas:**
> - **A, B y D:** Son capacidades y coberturas explícitamente ofrecidas en los planes de soporte técnico de AWS (Developer, Business, Enterprise).
> 
> **Referencia Primaria:** (Amazon Web Services, 2023a, 2024c).
</details>

---

### Pregunta 20
**Una empresa con operaciones de misión crítica requiere un acuerdo de nivel de servicio (SLA) que garantice un tiempo de respuesta técnica inferior a 15 minutos para incidentes donde el negocio esté completamente caído (*Business-critical system down*), además de un Technical Account Manager (TAM) dedicado. ¿Cuál es el plan de soporte mínimo de AWS que cumple con este requisito?**

- A) AWS Developer Support.
- B) AWS Business Support.
- C) AWS Enterprise Support.
- D) AWS Basic Support.

<details>
<summary><b>Ver Respuesta y Justificación Técnica</b></summary>

> **Respuesta Correcta: C**
> 
> **Justificación Técnica:**  
> El plan **AWS Enterprise Support** es el único nivel que incluye un **Technical Account Manager (TAM)** designado y dedicado exclusivamente a la organización, además de ofrecer el SLA de respuesta técnica más rápido de la industria: **menos de 15 minutos (24/7)** ante incidentes clasificados como sistemas de misión crítica caídos (Amazon Web Services, 2024c).
> 
> **Análisis de Opciones Incorrectas:**
> - **A:** Developer Support solo cubre horario laboral estándar, con SLA mínimo de 12 horas para sistemas afectados, sin soporte 24/7 ni TAM.
> - **B:** Business Support ofrece respuesta en menos de 1 hora para producción caída y soporte 24/7, pero no incluye TAM dedicado ni SLA de 15 minutos.
> - **D:** Basic Support es gratuito y solo cubre consultas de facturación y límites de servicio, sin soporte técnico para cargas de trabajo.
> 
> **Referencia Primaria:** (Amazon Web Services, 2024c).
</details>

---

## Matriz de Cobertura Temática del Módulo 02

| Dominio Evaluativo | Tópicos Evaluados | Preguntas Asociadas |
| :--- | :--- | :---: |
| **Definición y Fundamentos Cloud** | Estándar NIST SP 800-145, Entrega Bajo Demanda, Pago por Uso | Preguntas 01, 02 |
| **Las 6 Ventajas de la Nube de AWS** | CapEx vs OpEx, Economías de Escala, Elasticidad, Velocidad, Mantenimiento Cero, Alcance Global | Preguntas 02, 03, 04, 05, 06, 07 |
| **Modelos de Servicios (IaaS, PaaS, SaaS)** | Matriz de Control, Capas de Responsabilidad, Servicios Representativos | Preguntas 08, 09, 10 |
| **Modelos de Despliegue** | Nube Pública, Nube Híbrida, Nube Privada | Pregunta 11 |
| **Infraestructura Global de AWS** | Regiones, Zonas de Disponibilidad (AZs), Puntos de Presencia (Edge Locations) | Preguntas 12, 13, 14 |
| **AWS Free Tier y Gobernanza Inicial** | Tipos de Ofertas, Seguridad del Usuario Raíz, MFA | Preguntas 15, 16 |
| **Herramientas de Consola de AWS** | AWS CloudShell, AWS Trusted Advisor | Preguntas 17, 18 |
| **Planes de Soporte de AWS** | Alcance de Soporte vs Professional Services, Niveles de SLA y TAM | Preguntas 19, 20 |

---

## Referencias Bibliográficas

- Amazon Web Services. (2021). *Overview of Amazon Web Services* (AWS Whitepaper). AWS Documentation. https://docs.aws.amazon.com/whitepapers/latest/aws-overview/
- Amazon Web Services. (2023a). *AWS Certified Cloud Practitioner (CLF-C02) Exam Guide*. AWS Training and Certification. https://d1.awsstatic.com/training-and-certification/docs-cloud-practitioner/AWS-Certified-Cloud-Practitioner_Exam-Guide.pdf
- Amazon Web Services. (2023b). *AWS Security Best Practices: Managing AWS Root User and IAM* (AWS Whitepaper). AWS Documentation. https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html
- Amazon Web Services. (2024a). *How AWS Pricing Works: Understanding AWS Free Tier and Cost Optimization*. AWS Documentation. https://aws.amazon.com/pricing/
- Amazon Web Services. (2024b). *AWS Well-Architected Framework: Reliability and Operational Excellence Pillars*. AWS Documentation. https://aws.amazon.com/architecture/well-architected/
- Amazon Web Services. (2024c). *AWS Support Plans Comparison and Service Level Agreements*. AWS Documentation. https://aws.amazon.com/premiumsupport/plans/
- Mell, P., & Grance, T. (2011). *The NIST Definition of Cloud Computing* (Special Publication 800-145). National Institute of Standards and Technology. https://doi.org/10.6028/NIST.SP.800-145
