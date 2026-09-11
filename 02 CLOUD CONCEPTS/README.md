# Módulo 02: Conceptos de la Nube (AWS Cloud Concepts)

## 📋 Resumen Ejecutivo del Módulo

El **Módulo 02: Conceptos de la Nube** cubre la totalidad de las competencias evaluadas en el **Dominio 1 (Conceptos de la Nube - 24% del examen CLF-C02)**. Se exploran las definiciones formales de computación en la nube bajo el estándar NIST SP 800-145, las seis ventajas estratégicas de AWS, los modelos de servicios (*IaaS, PaaS, SaaS*), los modelos de despliegue (*Pública, Híbrida, Privada*), los componentes de la infraestructura global (*Regiones, Zonas de Disponibilidad y Puntos de Presencia*), la gobernanza de la Capa Gratuita (*AWS Free Tier*), las herramientas integradas en la consola web y la comparativa exhaustiva de los Planes de Soporte de AWS.

---

## 🎯 Objetivos de Aprendizaje

Al finalizar el estudio y las evaluaciones de este módulo, el estudiante será capaz de:

1. **Definir la Computación en la Nube:** Explicar el modelo de aprovisionamiento y entrega bajo demanda de recursos de TI a través de Internet con tarificación de pago por uso (*pay-as-you-go*).
2. **Analizar las 6 Ventajas Cardinales de la Nube de AWS:**
   - *Cambiar gasto de capital (CapEx) por gasto variable (OpEx).*
   - *Beneficiarse de economías de escala masivas.*
   - *Dejar de adivinar la capacidad (elasticidad y auto-scaling).*
   - *Incrementar la velocidad y la agilidad de desarrollo.*
   - *Dejar de gastar dinero en ejecutar y mantener centros de datos.*
   - *Desplegar aplicaciones a escala global en cuestión de minutos.*
3. **Diferenciar los Modelos de Servicios Cloud:** Identificar las delimitaciones de control y capas de responsabilidad en **IaaS** (ej. Amazon EC2), **PaaS** (ej. AWS Elastic Beanstalk) y **SaaS** (ej. Amazon QuickSight).
4. **Distinguir los Modelos de Despliegue:** Identificar las características arquitectónicas de la **Nube Pública**, la **Nube Híbrida** (con AWS Direct Connect / VPN) y entornos **On-Premises / Nube Privada**.
5. **Comprender la Infraestructura Global de AWS:** Describir la relación física y lógica entre **Regiones**, **Zonas de Disponibilidad (AZs)** con enlaces de fibra óptica de latencia $< 2\text{ ms}$, y **Puntos de Presencia (*Edge Locations*)** para distribución de contenido vía Amazon CloudFront.
6. **Aplicar Mejores Prácticas de Gobernanza y Seguridad Inicial:** Gestionar la Capa Gratuita (*Always Free*, *12 Months Free*, *Trials*), asegurar el **Usuario Raíz (*Root User*)** mediante MFA y delegar operaciones a usuarios IAM bajo el principio de privilegio mínimo.
7. **Utilizar Herramientas de la Consola de AWS:** Operar la barra de navegación, interactuar con la terminal web integrada **AWS CloudShell** y evaluar la salud arquitectónica con los 5 pilares de **AWS Trusted Advisor**.
8. **Evaluar los Planes de Soporte de AWS:** Comparar los niveles *Basic*, *Developer*, *Business*, *Enterprise On-Ramp* y *Enterprise* en función de sus Acuerdos de Nivel de Servicio (SLAs), tiempos de respuesta y asignación de *Technical Account Managers* (TAM).

---

## 📑 Guías Técnicas del Módulo

| N.° | Guía Técnica | Tópicos Clave y Conceptos Abordados |
| :---: | :--- | :--- |
| **00** | **[¿Qué es la Computación en la Nube?](00_What_is_Cloud_Computing.md)** | Estándar NIST SP 800-145, modelo bajo demanda, las 6 ventajas de AWS y casos de uso empresariales. |
| **01** | **[Modelos de Servicios Cloud (IaaS, PaaS, SaaS)](01_What_are_Cloud_Computing_Models.md)** | Pirámide de abstracción, matriz de control y responsabilidades cliente vs AWS. |
| **02** | **[On-Premises vs Computación en la Nube](02_On_Premises_vs_Cloud_Computing.md)** | Comparativa financiera CapEx vs OpEx, modelos de despliegue (Pública, Híbrida, Privada) y casos reales de éxito. |
| **03** | **[¿Qué es la Nube de AWS?](03_What_is_AWS_Cloud.md)** | Evolución histórica de AWS desde 2006, infraestructura global (Regiones, AZs, PoP) y catálogo de servicios. |
| **04** | **[Beneficios de la Nube de AWS](04_Benefits_of_the_AWS_Cloud.md)** | Elasticidad, resiliencia empresarial, optimización de costos y aceleración del *Time-to-Market*. |
| **05** | **[Creación de Cuenta en AWS Free Tier](05_Setting_Up_AWS_Free_Tier_Account.md)** | Modalidades de la capa gratuita, mejores prácticas para el Usuario Raíz (*Root User*) y activación de MFA. |
| **07** | **[Familiarización con la Consola de AWS](07_Getting_Familiar_with_AWS_Console.md)** | Navegación de consola, terminal integrada AWS CloudShell (1 GB persistente) y AWS Trusted Advisor. |
| **08** | **[Comparativa de Planes de Soporte de AWS](08_AWS_Support_Plans_Comparison.md)** | Matriz detallada entre *Basic*, *Developer*, *Business*, *Enterprise On-Ramp* y *Enterprise* (SLAs y TAM). |

---

## 📝 Evaluaciones del Módulo

| Formato | Recurso | Características |
| :---: | :--- | :--- |
| 📄 **Guía de Estudio** | **[Evaluación Modular (Quiz de 20 Preguntas)](09_Module_02_Cloud_Concepts_Quiz.md)** | Cuestionario formal con 20 preguntas, opciones A-D, respuestas correctas, análisis técnico de opciones incorrectas y baremo vigesimal. |
| 🌐 **Simulador Web** | **[Simulador Interactivo Online (1 Clic)](https://htmlpreview.github.io/?https://github.com/gdiazes/aws-ccp/blob/main/02%20CLOUD%20CONCEPTS/09_Module_02_Cloud_Concepts_Interactive_Quiz.html)** / [Archivo Local](09_Module_02_Cloud_Concepts_Interactive_Quiz.html) | Aplicación web interactiva con temporizador, calificación automática sobre **20.0 Puntos** ($\ge 14.0\text{ Ptos}$ para aprobar), equivalencia AWS (100-1000 pts) y retroalimentación inmediata. |

---

## 📚 Referencias Bibliográficas (Normas APA 7.ª Edición)

- Amazon Web Services. (2021). *Overview of Amazon Web Services* (AWS Whitepaper). AWS Documentation. https://docs.aws.amazon.com/whitepapers/latest/aws-overview/
- Amazon Web Services. (2023a). *AWS Certified Cloud Practitioner (CLF-C02) Exam Guide*. AWS Training and Certification. https://d1.awsstatic.com/training-and-certification/docs-cloud-practitioner/AWS-Certified-Cloud-Practitioner_Exam-Guide.pdf
- Amazon Web Services. (2023b). *AWS Security Best Practices: Managing AWS Root User and IAM* (AWS Whitepaper). AWS Documentation. https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html
- Amazon Web Services. (2024a). *How AWS Pricing Works: Understanding AWS Free Tier and Cost Optimization*. AWS Documentation. https://aws.amazon.com/pricing/
- Amazon Web Services. (2024b). *AWS Well-Architected Framework: Reliability and Operational Excellence Pillars*. AWS Documentation. https://aws.amazon.com/architecture/well-architected/
- Amazon Web Services. (2024c). *AWS Support Plans Comparison and Service Level Agreements*. AWS Documentation. https://aws.amazon.com/premiumsupport/plans/
- Mell, P., & Grance, T. (2011). *The NIST Definition of Cloud Computing* (Special Publication 800-145). National Institute of Standards and Technology. https://doi.org/10.6028/NIST.SP.800-145
