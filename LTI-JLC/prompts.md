# Historial de prompts

## Prompt 001

### Prompt original

> Estamos en el capítulo 4 de la formación. En este ejercicio, nos piden diseñar un sistema desde cero.  
> Este sistema se denomina LTI, etse sistema es una startup que quiere desarrollar el ATS (Applicant-Tracking System) del futuro. Te adjunto una imagen que describe lo que es un ATS. En resumen es un sistema que:  
> 1. Crea vacantes para uno o varios trabajos específicos  
> 2. Las publica en diferentes medios  
> 3. Los aspirantes reciben esas vacantes y entregan su solicitud  
> 4. Las solicitudes se revisan.  
> 5. Se realizan pruebas o exámenes online a los candidatos  
> 6. Se agendan entrevistas  
> 7. Los aspirantes elegidos son contratados  
> Queremos que nuestro sistema LTI:  
> - Aumente la eficiencia para los departamentos de HR  
> - Mejore la colaboración en tiempo real entre reclutadores y managers  
> - Automatizaciones  
> - Asistencia de IA en diversas tareas  
> Eres un experto en producto, con amplia experiencia en sistemas LTI como el que te he descrito. Vas diseñar y documentar este sistema software LTI siguiendo las fases:  
> 1. Investigación y análisis  
> 1.1 Descripción breve del software LTI, valor añadido y ventajas competitivas.  
> 1.2 Explicación de las funciones principales.  
> 1.3 Añadir un diagrama Lean Canvas para entender el modelo de negocio.  
> 2. Descripción de los 3 casos de uso principales, con el diagrama asociado a cada uno.  
> 3. Modelo de datos que cubra entidades, atributos (nombre y tipo) y relaciones.  
> 4. Diseño de alto nivel  
> 4.1 Diseño del sistema a alto nivel, tanto explicado como diagrama adjunto.  
> 4.2 Diagrama C4 que llegue en profundidad a uno de los componentes del sistema (lo elijiremos cuando lleguemos a este punto).  
> ¡NORMAS MUY IMPORTANTES!: en cada prompt que te pida:  
> 1. Me ofrecerás un link de descarga del archivo "prompts.md" con los prompts que te vaya pidiendo, por ejemplo, este prompt es el primero, cuando generes la respuesta a este prompt, me ofrecerás además el enlace de descarga de "prompts.md" con este prompt en formato Markdown (puedes adornarlo y enriquecerlo si lo consideras), en el siguiente prompt, me mostrarás la respuesta a dicho prompt y además me ofrecerás otra vez el link de descarga de "prompts.md" con los dos prompts, el primero y el segundo, y así sucesivamente.  
> 2. Si el enlace de descarga de "prompts.md" falla, te lo haré saber y me copiaras el contenido en formato Markdown íntegro del archivo en el chat para que me lo pueda copiar a mi archivo "prompt.md" que tenga en local.  
> 2. Cuando me muestres una respuesta a un prompt, la revisaré, y si está todo ok, te adjuntaré el archivo "LTI-JLC.md" en el que añadirás al final, en formato Markdown, la respuesta que acabas de generar.  
> Antes de empezar a trabajar, dime si te ha quedado todo claro y si tienes alguna pregunta que hecerme

### Versión estructurada

```md
# Objetivo

Diseñar y documentar desde cero el sistema **LTI**, una startup que quiere construir el **ATS (Applicant Tracking System) del futuro**.

# Contexto del dominio

Un ATS debe cubrir, al menos, este flujo:

1. Crear vacantes para uno o varios puestos.
2. Publicarlas en distintos canales.
3. Recibir candidaturas.
4. Revisar solicitudes.
5. Realizar pruebas o exámenes online.
6. Agendar entrevistas.
7. Contratar a los candidatos seleccionados.

# Objetivos de negocio de LTI

- Aumentar la eficiencia de los departamentos de HR.
- Mejorar la colaboración en tiempo real entre recruiters y hiring managers.
- Incorporar automatizaciones.
- Incorporar asistencia de IA en distintas tareas.

# Entregables que iremos construyendo

1. **Investigación y análisis**
   1.1 Descripción breve del software LTI, su valor añadido y ventajas competitivas.  
   1.2 Explicación de las funciones principales.  
   1.3 Diagrama Lean Canvas para entender el modelo de negocio.

2. **Casos de uso principales**
   - Descripción de los 3 casos de uso principales.
   - Diagrama asociado a cada caso de uso.

3. **Modelo de datos**
   - Entidades.
   - Atributos (nombre y tipo).
   - Relaciones.

4. **Diseño de alto nivel**
   4.1 Diseño del sistema a alto nivel, explicado y acompañado de diagrama.  
   4.2 Diagrama C4 con profundidad sobre uno de los componentes del sistema.

# Reglas de trabajo

1. En cada interacción se debe ofrecer un enlace de descarga del archivo `prompts.md` con el histórico acumulado de prompts en formato Markdown.
2. Si el enlace de descarga falla, se copiará íntegramente el contenido del archivo en el chat.
3. Cuando una respuesta quede validada, se añadirá al final del archivo `LTI-JLC.md` que el usuario adjunte.

# Estado actual

Este es el **primer prompt** del historial.
Antes de empezar, se debe confirmar si todo ha quedado claro y plantear cualquier duda necesaria.
```

## Prompt 002

Te respondo en orden:
1. Toda la documentación, diagramas, modelos de datos, código, etc debe estar en inglés.
2. Entrégame los diagramas en formato textual compatible con Mermaid/PlantUML dentro de Markdown
3. En el punto 4.2, cuando lleguemos al C4, me parece bien que el componente profundo sea uno claramente diferencial de LTI, por ejemplo el motor de IA/copilot
Si está todo claro, y no tienes más preguntas, empieza con la fase de investigación y análisis, para ello puedes responder a las siguientes preguntas, (añade tu las que consideres importantes que yo no haya tenido en cuenta):
1. ¿Qué funcionalidades básicas tiene un sistema LTI? Descríbemelas en un listado, ordenado de mayor a menor prioridad
2. ¿Qué beneficios obtiene el candidato y el reclutador para determinar si les merece la pena usar el sistema LTI?
3. ¿Qué alternativas al sistema LTI tienen los candidatos y los reclutadores y cuando pueden ser relevantes?

## Prompt 2
Constraints:
- All documentation must be in English
- Diagrams must be delivered in Mermaid or PlantUML
- The deep C4 component will be the AI Copilot

## Prompt 3
Research & analysis:
- Core functionalities of the LTI system
- Benefits for candidates and recruiters
- Alternatives to LTI and when they are relevant

## Prompt 4
Product definition:
- Product description
- Value proposition
- Competitive advantages
- Lean Canvas
- Lean Canvas diagram

## Prompt 5
Use cases:
- Define the 3 main use cases
- Add an associated diagram for each one

## Prompt 6
Data model:
- Define entities
- Define attributes (name and type)
- Define relationships
- Add a textual diagram in Mermaid

## Prompt 7
High-level design:
- Explain the system at a high level
- Add a high-level architecture diagram in Mermaid
- Include architectural rationale and design considerations

## Prompt 8
C4 modeling:
- Create a C4-style decomposition
- Focus on the AI Copilot Service
- Include System Context, Container, and Component-level diagrams
- Add design rationale, risks, and recommendations