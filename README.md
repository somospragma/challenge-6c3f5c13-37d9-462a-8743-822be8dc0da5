# Desarrollo de servicio REST para gestión de usuarios

La empresa necesita un servicio REST que permita la gestión de usuarios. Cada usuario tiene un nombre, email y rol. El sistema debe manejar adecuadamente los códigos HTTP y verbos para crear, leer, actualizar y eliminar usuarios. Es crucial que el servicio sea robusto y maneje correctamente los errores y casos límite del dominio.

## Informacion General

| Campo | Valor |
|-------|-------|
| **Tema** | Servicios REST |
| **Nivel** | junior-l2 |
| **Tipo** | practical |
| **Tiempo estimado** | 3-4 horas |

## Fases del Reto

### Fase 0: Configuración del Proyecto

**Objetivo:** Obtener el proyecto base funcional enviando el Código Base a un asistente de IA, que lo analizará, corregirá errores y generará un ZIP listo para usar.

**Tiempo estimado:** 15-30 minutos

**Instrucciones:**

- Asegúrate de tener instalado para ejecutar el proyecto: Un IDE o editor de código.
- Copia todo el contenido del campo **Código Base** de este reto — incluyendo el texto de instrucciones que aparece al inicio.
- Abre un asistente de IA (Claude en claude.ai, ChatGPT o Gemini — se recomienda Claude), pega el contenido copiado en el chat y envíalo.
- El asistente analizará los archivos, corregirá errores y generará un archivo ZIP descargable. Descárgalo y extráelo en la carpeta donde quieras trabajar.
- Verifica que el proyecto arranca sin errores.

**Entregable:** El proyecto compila/arranca sin errores.

<details>
<summary>Pistas de conocimiento</summary>

- Copia el Código Base completo incluyendo el texto de instrucciones al inicio — esas instrucciones le indican al asistente exactamente qué hacer con los archivos.
- Si el asistente no genera el ZIP automáticamente al terminar el análisis, escríbele: "genera el ZIP ahora".
- Si el proyecto tiene errores al arrancar, comparte el mensaje de error con el mismo asistente para que lo corrija.

</details>

### Fase 1: Definición de recursos y endpoints

**Objetivo:** Definir los recursos y endpoints necesarios para la gestión de usuarios.

**Tiempo estimado:** 1 hora

**Instrucciones:**

- Identifica los recursos y operaciones necesarias para la gestión de usuarios.
- Define los endpoints correspondientes a cada operación, considerando los verbos HTTP adecuados.

**Entregable:** Descripción de los recursos y endpoints definidos.

<details>
<summary>Pistas de conocimiento</summary>

- Recuerda que cada recurso debe tener un identificador único.
- Considera los códigos HTTP adecuados para cada operación.

</details>

### Fase 2: Implementación de endpoints

**Objetivo:** Implementar los endpoints definidos en la fase anterior.

**Tiempo estimado:** 2 horas

**Instrucciones:**

- Crea los endpoints definidos en la fase anterior, asegurándote de manejar adecuadamente los códigos HTTP y verbos.
- Implementa la lógica necesaria para crear, leer, actualizar y eliminar usuarios.

**Entregable:** Implementación de los endpoints con manejo adecuado de códigos HTTP y verbos.

<details>
<summary>Pistas de conocimiento</summary>

- Recuerda manejar los errores y casos límite del dominio.
- Considera la validación de datos de entrada.

</details>

## Dimensiones Evaluadas

- **queEs**: ¿Qué es un recurso en el contexto de un servicio REST?
- **paraQueSirve**: ¿Para qué sirven los códigos HTTP en un servicio REST?
- **comoSeUsa**: ¿Cómo se usan los verbos HTTP en la implementación de un servicio REST?
- **erroresComunes**: ¿Cuáles son los errores comunes al implementar un servicio REST y cómo se manejan?

## Criterios de Evaluacion

- Definición de recursos y endpoints adecuados para la gestión de usuarios.
- Implementación correcta de endpoints con manejo adecuado de códigos HTTP y verbos.
- Manejo de errores y casos límite del dominio en la implementación.
- Validación de datos de entrada en la implementación.

---

*Reto generado automaticamente por Challenge Generator - Pragma*
