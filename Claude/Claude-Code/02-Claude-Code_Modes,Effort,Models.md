# 🚀🌐🔐 Anthropic - Claude Code: `Modes, Effort & Models`

![My Video](https://user-images.githubusercontent.com/94720207/165892585-b830998d-d7c5-43b4-a3ad-f71a07b9077e.gif)

### 🐦 Twitter  : [@fz3r0_OPs](https://twitter.com/Fz3r0_OPs)
### 🐱 Github  : [Fz3r0](https://github.com/fz3r0)

---

#### Keywords:

`claude-code` `anthropic-claude` `ai-coding` `ai-assisted-development` `llm-development` `ai-programming` `prompt-engineering` `ai-workflows` `developer-productivity` `coding-assistant`

---

<br>

# 📄 `Index`

- [🎛️ Claude Code: `Modes`](#️-claude-code-modes)
  - [🧠 ¿Qué son los Modes?](#-qué-son-los-modes)
  - [🧠 Plan Mode (Modo de Planeación)](#-plan-mode-modo-de-planeación)
  - [🙋 Ask Before Edits (Modo Recomendado por Defecto)](#-ask-before-edits-modo-recomendado-por-defecto)
  - [✏️ Edit Automatically (Modo de Ejecución Directa)](#️-edit-automatically-modo-de-ejecución-directa)
  - [⚡ Auto Mode (Modo Inteligente)](#-auto-mode-modo-inteligente)
  - [☠️ Bypass Permissions (Modo Avanzado)](#️-bypass-permissions-modo-avanzado)
  - [🧠 Estrategia Inteligente para Ahorrar Tokens](#-estrategia-inteligente-para-ahorrar-tokens)

- [🧠⚙️ Claude Code Effort Levels](#️-claude-code-effort-levels)
  - [🔄 ¿Qué es un Loop Iterativo?](#-qué-es-un-loop-iterativo)
  - [📊 Niveles de Effort](#-niveles-de-effort)
  - [🟢 Low Effort (Rápido y Económico)](#-low-effort-rápido-y-económico)
  - [🟡 Medium Effort (Modo Balanceado)](#-medium-effort-modo-balanceado)
  - [🔴 High Effort (Máxima Calidad)](#-high-effort-máxima-calidad)
  - [🎯 Estrategia Inteligente de Uso de Effort](#-estrategia-inteligente-de-uso-de-effort)
  - [🧠 Effort vs Modes (Relación Importante)](#️-effort-vs-modes-relación-importante)

- [📂 Contexto Adicional (Muy Importante)](#-contexto-adicional-muy-importante)
  - [⚡ Slash Commands Relacionados con Effort](#️-slash-commands-relacionados-con-effort)

- [🧠 Claude Code Models (Haiku, Sonnet, Opus)](#-claude-code-models-haiku-sonnet-opus)

# 🎛️ Claude Code: `Modes, Effort & Models`

En esta sección se presentan tres de los controles más importantes dentro de **Claude Code**:

- 🎛️ **Modes**
- 🧠 **Effort**
- ⚡ **Models**

Estos tres elementos funcionan como los **controles principales del comportamiento del agente**, permitiendo ajustar cómo piensa, cómo actúa y qué tan profundo analiza una tarea.

Mientras que los **Modes** determinan **qué puede hacer Claude**, el **Effort** define **cuánto intentará mejorar un resultado**, y el **Model** selecciona **qué tan potente será el razonamiento utilizado**.

Dominar estos tres parámetros es fundamental para:

- 💰 Optimizar el uso de **tokens**
- ⚡ Aumentar la velocidad de desarrollo
- 🧠 Mejorar la calidad de los resultados
- 🔐 Mantener control sobre cambios en el sistema

En la práctica, la mayoría de errores comunes en Claude Code no se deben a malos prompts, sino a un **uso incorrecto de Modes, Effort o Models**.

Por esta razón, comprender estos conceptos desde el inicio permite trabajar de forma más eficiente, predecible y profesional.

# 🎛️ Claude Code: `Modes`

Uno de los conceptos más importantes dentro de **Claude Code** es el uso correcto de los **Modes**.

<img width="608" height="267" alt="image" src="https://github.com/user-attachments/assets/6b3f9a55-932c-41d2-b462-032b937b8383" />

Los **Modes** controlan **qué tanto permiso tiene Claude para modificar archivos o ejecutar acciones**, y su uso correcto impacta directamente en:

* 💰 Uso de **tokens**
* ⚡ Velocidad de trabajo
* 🔐 Seguridad del entorno
* 🧠 Control sobre los cambios realizados

Elegir el modo correcto en cada momento puede marcar una gran diferencia en la eficiencia del workflow.

## 🧠 ¿Qué son los Modes?

Los **Modes** definen el nivel de autonomía que tiene Claude al interactuar con tu proyecto.

En la interfaz de Claude Code, normalmente encontrarás opciones como:

* **Plan mode**
* **Ask before edits**
* **Edit automatically**
* **Auto mode**
* **(Opcional) Bypass permissions**

Cada uno está diseñado para un momento distinto del workflow.

| Mode                  | Nivel de Autonomía | ¿Modifica archivos?    | Uso típico                          |
| --------------------- | ------------------ | ---------------------- | ----------------------------------- |
| 🧠 Plan mode          | Bajo               | ❌ No                   | Diseño y planificación              |
| 🙋 Ask before edits   | Medio              | ⚠️ Solo con aprobación | Validar cambios antes de aplicarlos |
| ✏️ Edit automatically | Alto               | ✅ Sí                   | Edición directa de archivos         |
| ⚡ Auto mode           | Dinámico           | ✅ Sí                   | Decisión automática del mejor modo  |
| ☠️ Bypass permissions | Máximo             | ✅ Sí (sin preguntar)   | Automatización avanzada en sandbox  |


## 🧠 Plan Mode (Modo de Planeación)

**Plan mode** permite que Claude **analice el proyecto y proponga cambios**, pero **sin ejecutarlos**.

Este modo convierte a Claude en algo similar a un **consultor técnico**.

### 🔍 Características

* ❌ No modifica archivos
* 📋 Genera planes detallados
* 🧠 Analiza estructura del proyecto
* 💰 Reduce consumo innecesario de tokens

### 🎯 Cuándo usarlo

Este modo es ideal cuando:

* Estás diseñando una solución
* Estás explorando ideas
* Quieres entender un proyecto existente
* Aún no deseas modificar archivos

### 🧪 Ejemplo práctico

```text
Create a plan to refactor this project into modular Python structure.
Do not apply any changes yet.
```

Resultado esperado:

👉 Claude genera un plan detallado
👉 No modifica archivos


## 🙋 Ask Before Edits (Modo Recomendado por Defecto)

Este modo permite que Claude **proponga cambios**, pero **requiere aprobación antes de ejecutarlos**.

Es el modo más equilibrado entre seguridad y productividad.

### 🔍 Características

* ⚠️ Propone cambios
* 🙋 Pide aprobación antes de aplicarlos
* 🔐 Alto control del usuario
* 📉 Reduce errores inesperados

### 🎯 Cuándo usarlo

Ideal cuando:

* Estás aprendiendo Claude Code
* Estás trabajando en código importante
* Quieres validar cada cambio

### 🧪 Ejemplo práctico

```text
Rename all variables to follow snake_case convention.
```

Claude:

👉 Propone cambios
👉 Espera confirmación
👉 Luego los ejecuta

## ✏️ Edit Automatically (Modo de Ejecución Directa)

Este modo permite que Claude **modifique archivos directamente sin solicitar confirmación**.

Es rápido, pero requiere confianza en el modelo.

### 🔍 Características

* ✅ Aplica cambios automáticamente
* ⚡ Alta velocidad
* 📂 Trabaja sobre archivos reales
* ⚠️ Menor control manual

### 🎯 Cuándo usarlo

Ideal cuando:

* Sabes exactamente qué quieres
* El cambio es simple
* El entorno es seguro

Ejemplo:

```text
Fix syntax errors in this file.
```

Resultado:

👉 Claude modifica el archivo directamente



## ⚡ Auto Mode (Modo Inteligente)

**Auto mode** permite que Claude **decida automáticamente qué nivel de permiso usar**, dependiendo de la tarea.

Es útil cuando el workflow mezcla tareas simples y complejas.

### 🔍 Características

* 🧠 Selección automática del modo
* ⚡ Flujo continuo
* 🔄 Reduce decisiones manuales

### 🎯 Cuándo usarlo

Ideal cuando:

* Trabajas en tareas repetitivas
* Tienes confianza en el workflow
* Quieres velocidad sin micro-gestión



## ☠️ Bypass Permissions (Modo Avanzado)

Este modo permite que Claude **ejecute acciones sin solicitar ningún permiso**, incluso si pueden ser riesgosas.

⚠️ **Debe usarse solo en entornos controlados (sandbox).**

### 🔍 Características

* 🚫 Sin confirmaciones
* ⚡ Máxima autonomía
* 🔥 Alto riesgo si se usa incorrectamente

### 🎯 Cuándo usarlo

Solo cuando:

* Estás en laboratorio
* Estás en VM aislada
* Necesitas máxima automatización

Ejemplo típico:

```text
Refactor entire project structure automatically.
```

Claude:

👉 Ejecuta todo sin preguntar



## 🧠 Estrategia Inteligente para Ahorrar Tokens

Uno de los beneficios más importantes de usar correctamente los **Modes** es el **ahorro de tokens**.

Workflow recomendado:

```text
1️⃣ Plan mode → Diseñar cambios
2️⃣ Ask before edits → Validar cambios
3️⃣ Edit automatically → Ejecutar cambios
```

Este flujo evita:

* Cambios innecesarios
* Repeticiones
* Consumo excesivo de tokens

Y mejora:

* Precisión
* Velocidad
* Control

Los **Modes** no solo controlan permisos, también influyen en:

* número de operaciones ejecutadas
* cantidad de tokens consumidos
* velocidad de iteración

Por esta razón, dominar los **Modes** es una de las habilidades más importantes al trabajar con **Claude Code**.













# 🧠⚙️ Claude Code Effort Levels

Además de los **Modes**, Claude Code permite ajustar el nivel de **Effort**, que define **cuánto esfuerzo computacional realizará Claude para completar una tarea**.

<img width="341" height="251" alt="image" src="https://github.com/user-attachments/assets/6481e4cf-9142-4718-b379-798a8c677a58" />

Este parámetro controla directamente:

* 🔄 Número de **iteraciones internas (loops)**
* 🧠 Nivel de refinamiento del resultado
* 💰 Consumo de **tokens**
* ⏱️ Tiempo de ejecución

Comprender cómo usar correctamente el **Effort** permite obtener mejores resultados sin desperdiciar recursos.


## 🔄 ¿Qué es un Loop Iterativo?

Un concepto fundamental para entender **Effort** es el **loop iterativo**.

Un **loop** es un ciclo interno que Claude ejecuta repetidamente para mejorar un resultado hasta que alcanza un nivel aceptable.

Ejemplo conceptual:

```text
1️⃣ Generar resultado inicial
2️⃣ Evaluar resultado
3️⃣ Detectar mejoras posibles
4️⃣ Aplicar mejoras
5️⃣ Repetir proceso
```

Este proceso se repite varias veces dependiendo del **Effort seleccionado**.

**Este comportamiento es una de las principales diferencias entre:**

* 🤖 Un **chatbot simple**
* 🧠 Un **AI agent iterativo**



## 📊 Niveles de Effort

| Effort Level | Iteraciones | Consumo de Tokens | Calidad esperada | Uso típico       |
| ------------ | ----------- | ----------------- | ---------------- | ---------------- |
| 🟢 Low       | Pocas       | Bajo              | Básica           | Tareas rápidas   |
| 🟡 Medium    | Moderadas   | Medio             | Balanceada       | Uso general      |
| 🔴 High      | Muchas      | Alto              | Alta calidad     | Tareas complejas |



## 🟢 Low Effort (Rápido y Económico)

El modo **Low Effort** ejecuta pocos loops internos.

Esto significa:

* ⚡ Respuesta rápida
* 💰 Bajo consumo de tokens
* 🧠 Menor refinamiento

### 🎯 Cuándo usarlo

Ideal para:

* Pruebas rápidas
* Cambios pequeños
* Ediciones simples
* Validaciones rápidas

### 🧪 Ejemplo práctico

```text
Fix indentation errors in this file.
```

No requiere análisis profundo.



## 🟡 Medium Effort (Modo Balanceado)

Este es el modo más equilibrado y generalmente recomendado.

Realiza un número moderado de loops.

Esto permite:

* ⚖️ Balance entre velocidad y calidad
* 🧠 Mejora progresiva del resultado
* 💰 Consumo moderado de tokens

### 🎯 Cuándo usarlo

Ideal para:

* Desarrollo diario
* Refactorización moderada
* Generación de código estándar

Este suele ser el **modo recomendado por defecto**.



## 🔴 High Effort (Máxima Calidad)

El modo **High Effort** ejecuta múltiples iteraciones internas.

Esto permite:

* 🧠 Mayor refinamiento
* 🔍 Mejor razonamiento
* 🎯 Resultados más precisos

Pero implica:

* 💰 Mayor consumo de tokens
* ⏱️ Mayor tiempo de ejecución

### 🎯 Cuándo usarlo

Ideal para:

* Generación de proyectos completos
* Diseño complejo
* Refactorizaciones grandes
* One-shot prompts importantes

Ejemplo:

```text
Create a full modular Python project with documentation and tests.
```

Aquí sí vale la pena invertir más loops.



## 🎯 Estrategia Inteligente de Uso de Effort

Una buena práctica es **ajustar el Effort según la fase del proyecto**.

Workflow recomendado:

```text
Exploración → Low
Desarrollo → Medium
Producción → High
```

Esto evita:

* consumo excesivo
* resultados innecesariamente complejos
* pérdida de tiempo



##  🧠 Effort vs Modes (Relación Importante)

Effort y Modes trabajan juntos.

Ejemplo típico:

```text
Plan mode + High effort
```

Resultado:

👉 Plan detallado
👉 Análisis profundo
👉 Sin modificar archivos

Otro ejemplo:

```text
Edit automatically + Low effort
```

Resultado:

👉 Cambios rápidos
👉 Sin análisis profundo

Esta combinación permite crear workflows muy eficientes.



# 📂 Contexto Adicional (Muy Importante)

Dentro de la interfaz también existen opciones relacionadas con **contexto y archivos**, que influyen indirectamente en el Effort.

Por ejemplo:

* 📎 Adjuntar archivos
* 📄 Incluir documentos
* 📚 Agregar contexto adicional
* 🌐 Habilitar uso de navegador web

Agregar más contexto permite:

* mejorar precisión
* reducir iteraciones innecesarias
* optimizar resultados

Esto es especialmente útil cuando Claude necesita comprender proyectos completos. 



## ⚡ Slash Commands Relacionados con Effort

Claude Code permite usar comandos rápidos mediante:

```text
/
```

Esto abre opciones como:

* cambiar modelo
* ajustar Effort
* limpiar contexto
* cambiar modo
* gestionar memoria

Ejemplos comunes:

```text
/clear
/model
/effort
/context
```

Estos comandos permiten ajustar el comportamiento del sistema en tiempo real.





# 🧠 Claude Code Models (Haiku, Sonnet, Opus)

El nivel de Effort también interactúa con el **modelo seleccionado**.

Modelos comunes:

| Model     | Características    | Uso recomendado  |
| --------- | ------------------ | ---------------- |
| ⚡ Haiku   | Rápido y económico | Tareas simples   |
| ⚖️ Sonnet | Balanceado         | Uso general      |
| 🧠 Opus   | Avanzado           | Tareas complejas |

Un modelo más avanzado combinado con **High Effort** produce resultados más sofisticados, pero consume más recursos. 

Para la mayoría de workflows, el patrón recomendado es:

```text
Low → Medium → High
```

Primero:

* probar rápido
  Luego:

* refinar
  Finalmente:

* perfeccionar

Este enfoque maximiza calidad y minimiza desperdicio de tokens.




# 🗃️ Resources

- [CLAUDE CODE 2026: Curso Completo en Español](https://www.youtube.com/watch?v=73eFWU-edO4)
  
---

<span align="center"> <p align="center"> ![giphy](https://user-images.githubusercontent.com/94720207/166587250-292d9a9f-e590-4c25-a678-d457e2268e85.gif) </p> </span> 

&nbsp;

<span align="center"> <p align="center"> _I hope this information was useful for someone_ </p> </span> 
<span align="center"> <p align="center"> _and please, don't forget to enjoy your days..._ </p> </span> 
<span align="center"> <p align="center"> _...It is getting dark... so dark..._ </p> </span> 

&nbsp;

<span align="center"> <p align="center"> _In the mist of the night you could see me come, where shadows move and Demons lie..._ </p> </span> 
<span align="center"> <p align="center"> _I am [Fz3r0 💀](https://github.com/Fz3r0/) and the Sun no longer rises..._ </p> </span> 

---

---

> ![hecho en mexico 5](https://user-images.githubusercontent.com/94720207/166068790-fa1f243d-2db9-4810-a6e4-eb3c4ad23700.png)
>
> _- Hecho en México - by [Fz3r0 💀](https://github.com/Fz3r0/)_  
>
> _"In the mist of the night you could see me come, where shadows move and Demons lie..."_ 


