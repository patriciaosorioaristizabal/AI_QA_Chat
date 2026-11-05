   # Contexto del repositorio
   Laboratorio de aprendizaje de Copilot Chat aplicado a QA. Será usado para practicar los fundamentos de la IA en el contexto de las pruebas de software.

   # Cómo responder
   - Omite las secciones "Stack", "Organización" y "Cómo ejecutarlo".
   - Evalúa siempre con criterios de QA: alcance, riesgos, evidencia y trazabilidad.
   - Si falta información, decláralo; no supongas.
   - Termina cada respuesta con una tabla: Hallazgo | Prioridad | Recomendación.
   
   # Referentes
   Para las pruebas de software usaremos como referente el ISTQB https://istqb.org/.
   Para la IA usaremos como referente a Andrew NG https://www.andrewng.org/

  # Estructura Clave de un Prompt
| Elemento | Qué incluir |
|---|---|
| **Contexto** | Funcionalidad, requisito o sistema que se está probando. |
| **Objetivo** | La tarea concreta que quieres que Copilot realice. |
| **Datos de entrada** | Requisitos, reglas, ejemplos o archivos relevantes. |
| **Restricciones** | Alcance, supuestos que debe evitar y qué hacer si falta información. |
| **Formato de salida** | Estructura esperada, por ejemplo, una tabla de casos de prueba. |
| **Criterios de calidad** | Qué debe cubrir: casos positivos, negativos, límites, trazabilidad, etc. |

**Plantilla:**  
«Con base en [contexto y requisitos], realiza [tarea]. Incluye [cobertura requerida]. No asumas requisitos que no estén especificados; señala dudas o información faltante. Devuelve el resultado en [formato], con [criterios de calidad]».

**Riesgo:** un prompt claro mejora la pertinencia, pero no garantiza que la respuesta sea correcta; valida los resultados contra los requisitos y el comportamiento esperado.
