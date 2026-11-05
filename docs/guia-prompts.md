# Guía para escribir prompts de QA en Copilot Chat

## Estructura clave de un prompt

| Elemento | Qué incluir |
|---|---|
| **Contexto** | Funcionalidad, requisito o sistema que se está probando. |
| **Objetivo** | La tarea concreta que quieres que Copilot realice. |
| **Datos de entrada** | Requisitos, reglas, ejemplos o archivos relevantes. |
| **Restricciones** | Alcance, supuestos que debe evitar y qué hacer si falta información. |
| **Formato de salida** | Estructura esperada, por ejemplo, una tabla de casos de prueba. |
| **Criterios de calidad** | Qué debe cubrir: casos positivos, negativos, límites, trazabilidad, etc. |

## Plantilla

> Con base en [contexto y requisitos], realiza [tarea]. Incluye [cobertura requerida]. No asumas requisitos que no estén especificados; señala dudas o información faltante. Devuelve el resultado en [formato], con [criterios de calidad].

## Riesgo

Un prompt claro mejora la pertinencia, pero no garantiza que la respuesta sea correcta. Valida los resultados contra los requisitos y el comportamiento esperado.
