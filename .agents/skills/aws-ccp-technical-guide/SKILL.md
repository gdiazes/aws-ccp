---
name: aws-ccp-technical-guide
description: >-
  Estandariza la conversión de transcripciones y apuntes de AWS Certified Cloud Practitioner (.txt)
  a guías técnicas en Markdown (.md) redactadas en español con voz pasiva y en tercera persona,
  integrando fuentes primarias oficiales de AWS y estándares (NIST), citas textuales bilingües
  (inglés/español), citación rigurosa bajo normas APA 7.ª edición (Autor, año), exclusión total
  de intermediarios comerciales (ej. Whizlabs), generación e incrustación automática de imágenes
  de diagramación arquitectónica (estilo técnico minimalista Fortinet/line-art con verde oscuro y verde azulado / teal),
  y sincronización/publicación automática a GitHub de los archivos Markdown (.md), diagramas y estructura.
---

# Skill: Conversión de Transcripciones a Guías Técnicas de AWS CCP (CLF-C02) y Sincronización con GitHub

Este skill define la metodología, directrices de redacción, formato académico-técnico, flujo automatizado de generación visual y sincronización con GitHub para transformar transcripciones de cursos y notas de preparación de AWS en guías técnicas de referencia estructuradas en Markdown con diagramas arquitectónicos de alta fidelidad.

---

## 1. Directrices de Estilo y Redacción

1. **Idioma:** Español formal técnico.
2. **Tono y Voz:** Uso estricto de **tercera persona** y **voz pasiva / impersonal** (*"se define"*, *"se establece"*, *"se analiza"*, *"se recomienda"*). Evitar la primera persona (*"yo"*, *"nosotros"*).
3. **Exclusión Estricta de Intermediarios:** Se prohíbe taxativamente toda mención, cita o atribución a plataformas comerciales de cursos o intermediarios de formación (por ejemplo, *Whizlabs*, *Wiz Labs*, nombres de instructores particulares o portales de cursos de terceros). Todo el sustento conceptual, citas y referencias bibliográficas deben provenir **única y exclusivamente de fuentes primarias oficiales** (Amazon Web Services, NIST, Gartner, ISO/IEC).
4. **Preservación de Archivos Fuente:** Los archivos originales `.txt` y `.pdf` **nunca deben eliminarse** del entorno local de trabajo; deben conservarse íntegros como fuente de consulta y mantenerse ignorados en el control de versiones vía `.gitignore`.
5. **Estructura Modular:**
   - **Título y Resumen Ejecutivo:** Definición formal del tema y objetivos evaluativos.
   - **Desarrollo Técnico y Conceptual:** Desglose detallado con subtítulos numerados.
   - **Tablas Comparativas y Diagramas:** Cuadros resumen de características, servicios, modelos o ponderaciones con diagramas Mermaid cuando corresponda.
   - **Integración Orgánica de Fuentes Primarias:** Incorporación de citas textuales bilingües de AWS o estándares dentro de la narrativa técnica.
   - **Diagramas Técnicos Generados e Incrustados:** Generación visual e incrustación obligatoria de imágenes de diagramas técnicos por cada apartado temático (`![Descripción](../assets/images/<nombre>.jpg)`).
   - **Prompts de Diagramación Técnica Arquitectónica:** Inclusión del bloque textual del prompt utilizado para transparencia y reproducibilidad técnica.
   - **Referencias Bibliográficas:** Sección final bajo la 7.ª edición de las Normas APA (únicamente fuentes primarias oficiales).

---

## 2. Pautas de Citación e Integración de Fuentes Primarias (Norma APA 7.ª Edición)

1. **Citación dentro del texto:**
   - Toda afirmación conceptual, límite de servicio o definición formal debe sustentarse con citación en formato `(Autor, año)` o `(Autor, año, p. X)` (ej. `(AWS, 2023)`, `(Mell & Grance, 2011)`).
2. **Citas Textuales Bilingües:**
   - Para conceptos cardinales, incluir el bloque textual original en inglés de la fuente primaria oficial seguido inmediatamente de su traducción profesional al español:
   ```markdown
   > **Cita textual en inglés (Fuente primaria):**
   > "[Texto exacto del documento oficial de AWS/NIST]" (Amazon Web Services, 2023, p. X).
   >
   > **Traducción al español:**
   > "[Traducción técnica al español]."
   ```
3. **Catálogo de Fuentes Primarias Oficiales Autorizadas:**
   - *Definiciones de Cloud:* NIST SP 800-145 (Mell & Grance, 2011) y *Overview of Amazon Web Services* (AWS, 2021).
   - *Guía Oficial del Examen:* *AWS Certified Cloud Practitioner CLF-C02 Exam Guide* (AWS, 2023).
   - *Seguridad y Cumplimiento:* *AWS Security Best Practices* y Modelo de Responsabilidad Compartida (AWS, 2023b).
   - *Economía y Precios:* *How AWS Pricing Works* (AWS, 2024a).
   - *Arquitectura y Resiliencia:* *AWS Well-Architected Framework* (AWS, 2024b).
   - *Límites y Casos de Uso:* *AWS FAQs Documentation Hub* (AWS, 2024c).
   - *Análisis de Mercado:* Gartner Magic Quadrant for Strategic Cloud Platform Services (Gartner, 2023).

---

## 3. Estándar de Prompt Engineering y Generación Visual de Diagramas

Cada sección o apartado técnico de la guía debe incorporar un diagrama técnico generado automáticamente e incrustado en el documento, junto con el prompt utilizado:

### Plantilla Canónica del Prompt:
```text
Prompt: Hand-drawn technical network diagram, isolated on a transparent background (pure solid white for easy cutout), no whiteboard, no background elements. COLORING INSTRUCTION: Highlight ALL components with solid dark green and teal fill colors. Layout: [DESCRIPCIÓN DE LÍMITES GEOMÉTRICOS, COMPONENTES CONECTADOS, FLECHAS Y ETIQUETAS ESPECÍFICAS EN ESPAÑOL]. Simple line art, Fortinet documentation style, minimalist, Spanish text labels --ar 16:9
```

### Reglas de Diseño y Generación Visual:
1. **Estilo visual:** Dibujo técnico lineal a mano (*Hand-drawn technical diagram / Simple line art*), estilo de documentación técnica de ingeniería (similar a manuales de redes Fortinet).
2. **Fondo e Integración:** Aislado sobre fondo blanco puro y sólido (*isolated on a transparent background (pure solid white for easy cutout)*), sin marcos de pizarra ni elementos decorativos superfluos.
3. **Paleta cromática:** Relleno sólido obligatorio en **verde oscuro (*dark green*)** y **verde azulado (*teal*)** para destacar todos los componentes y contenedores lógicos.
4. **Etiquetado y Nomenclatura:** Nombres claros en español para cada contenedor, servicio o flujo técnico.
5. **Relación de aspecto:** Formato panorámico `--ar 16:9`.
6. **Almacenamiento e Incrustación:** Guardar el artefacto en la ruta relativa `assets/images/<nombre_del_diagrama>.jpg` e insertarlo antes del bloque de prompt con `![Texto descriptivo](../assets/images/<nombre_del_diagrama>.jpg)`.

---

## 4. Flujo de Ejecución y Sincronización con GitHub

1. **Lectura y Análisis:** Leer el archivo fuente `.txt` local (manteniendo el archivo `.txt` intacto).
2. **Depuración de Intermediarios:** Filtrar saludos, referencias a instructores, menciones a portales de terceros y publicidad de cursos.
3. **Investigación y Selección de Fuentes Primarias:** Mapear los conceptos técnicos a las publicaciones oficiales de AWS o estándares equivalentes.
4. **Diseño y Ejecución de Prompts Arquitectónicos:** Generar las imágenes mediante el motor visual para cada sección.
5. **Generación del Markdown (.md):** Crear la guía técnica formal incrustando las imágenes renderizadas y los bloques de prompt correspondientes.
6. **Actualización del README y Estructura:** Actualizar el índice del repositorio `README.md` si se incorporan nuevos módulos.
7. **Sincronización Automática con GitHub:**
   - Ejecutar `git add .` (verificando que `.gitignore` excluya `.txt` y `.pdf`).
   - Crear un commit descriptivo: `git commit -m "docs: actualización de guías técnicas y diagramas"`.
   - Realizar el push a la rama principal: `git push origin main`.
