# 🚀🌐🔐 Anthropic - Claude Code: `Modes`

![My Video](https://user-images.githubusercontent.com/94720207/165892585-b830998d-d7c5-43b4-a3ad-f71a07b9077e.gif)

### 🐦 Twitter  : [@fz3r0_OPs](https://twitter.com/Fz3r0_OPs)
### 🐱 Github  : [Fz3r0](https://github.com/fz3r0)

---

#### Keywords:

`claude-code` `anthropic-claude` `ai-coding` `ai-assisted-development` `llm-development` `ai-programming` `prompt-engineering` `ai-workflows` `developer-productivity` `coding-assistant`

---

<br>

# 📄 `Index`



# 🎛️ Claude Code Modes (Permisos y Control de Ejecución)

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


