# 🚀🌐🔐 Anthropic - Claude Code: `Claude Code + VS Code @ Kali Linux`

![My Video](https://user-images.githubusercontent.com/94720207/165892585-b830998d-d7c5-43b4-a3ad-f71a07b9077e.gif)

### 🐦 Twitter  : [@fz3r0_OPs](https://twitter.com/Fz3r0_OPs)
### 🐱 Github  : [Fz3r0](https://github.com/fz3r0)

---

#### Keywords:

`claude-code` `anthropic-claude` `ai-coding` `ai-assisted-development` `llm-development` `ai-programming` `prompt-engineering` `ai-workflows` `developer-productivity` `coding-assistant`

---

<br>

# 📄 `Index`



# 🛠️ Instalación de Claude Code en Kali Linux (VMware + VS Code)

En este laboratorio, **Claude Code se instalará dentro de una máquina virtual Kali Linux**, utilizando **VMware** como entorno de virtualización y **VS Code** como **IDE principal**.

Este enfoque permite trabajar en un entorno aislado, reproducible y seguro para pruebas y automatización.


### 📋 Requisitos previos

Antes de comenzar, asegúrate de tener:

* 🖥️ **VMware** instalado y funcionando
* 🐉 **Kali Linux VM** operativa
* 🧰 **VS Code** instalado en Kali
* 🌐 Conexión a internet activa
* 🔐 Cuenta Claude con **Pro Plan** o superior

Opcional pero recomendado:

* VMware Tools instalado
* Clipboard sharing habilitado


## 🔧 Paso 1 - Abrir VS Code en Kali Linux

Dentro de Kali Linux:

1. Abrir **VS Code** con `code`
2. Verificar que la interfaz carga correctamente
3. Confirmar conexión a internet

Este será el entorno donde se ejecutará **Claude Code**.

<img width="1543" height="262" alt="image" src="https://github.com/user-attachments/assets/9d87ca6f-2ef0-42ee-8ec1-ecaf255f914a" />

## 🔧 Paso 2 — Instalar la extensión Claude Code

Dentro de **VS Code**:

1. Ir a: **Extensions Panel** o `Ctrl + Shift + X`
2. Buscar: **Claude Code**
3. Seleccionar la extensión **oficial**: `Claude Code for VS Code`
4. Hacer clic en **Install**

<img width="1834" height="878" alt="image" src="https://github.com/user-attachments/assets/be314955-ec0a-4c4c-acf5-bb9defcc53b3" />

Una vez instalada, aparecerá el icono de **Claude Code** dentro de VS Code:

<img width="1802" height="931" alt="image" src="https://github.com/user-attachments/assets/551359ee-fe52-44f5-bb70-b653022a144c" />

## 🔧 Paso 3 - Autenticación con la cuenta Claude

Después de instalar la extensión:

1. Abrir el panel de **Claude Code**
2. Seleccionar: **Sign In**
3. Autorizar acceso a tu cuenta Claude
4. Confirmar que la autenticación fue exitosa

Una vez autenticado, el sistema quedará listo para interactuar con Claude Code. 

<img width="1579" height="899" alt="image" src="https://github.com/user-attachments/assets/071fb73f-be77-44a2-a7cb-b326a0ab107f" />


## 🔧 Paso 4 - Crear carpeta de trabajo

Antes de comenzar a usar Claude Code, es recomendable trabajar dentro de una carpeta específica. 

1. Crear una carpeta nueva: `Fz3r0_claude-code-lab-1` (Esta carpeta será el **workspace inicial**)

<img width="669" height="217" alt="image" src="https://github.com/user-attachments/assets/5ae0c7fd-a70a-49f1-a5de-59075b2caae7" />

2. Utilizarla desde VS Code (Open Folder) 

<img width="1067" height="748" alt="image" src="https://github.com/user-attachments/assets/72bbacb8-b024-46c6-a82e-b18bdb2769d6" />



## 🔧 Paso 5 - Primera prueba de funcionamiento

Una vez abierta la carpeta:

<img width="1583" height="898" alt="image" src="https://github.com/user-attachments/assets/862f1adb-f111-4cc4-b95f-2eb5d6fad58a" />

Abrir el **panel de Claude Code** y escribir:

```text
Hello Claude, create a simple test file named test.md with a spicy joke in Mexican spanish.
```

Si el sistema responde correctamente y crea el archivo, **la instalación fue exitosa.**

- **NOTA: Es posible se deban dar permisos adicionales la primera vez para poder hacer cambios en los archivos:**

<img width="1584" height="594" alt="image" src="https://github.com/user-attachments/assets/c435fadd-7813-4119-a23a-fc4be373cb96" />

- Una vez que se dan los permisos el archivo .md es creado:

<img width="2183" height="599" alt="image" src="https://github.com/user-attachments/assets/38b59edb-945e-47d9-bdf4-e6533d5688b0" />



# 🧠 Notas técnicas importantes

Claude Code trabaja directamente con:

* archivos reales
* carpetas reales
* terminal del sistema

Esto significa que:

> Todo cambio que Claude haga se reflejará inmediatamente en el sistema de archivos. Este comportamiento es normal y esperado.


# You are in...

Ahora estás dentro... muahahaha!!!!!

### Ejemplo Hello World

<img width="2829" height="1149" alt="image" src="https://github.com/user-attachments/assets/1f31cbad-ebe5-47a7-b129-4d7f613d5c42" />


### Ejemplo Sniffer

Primero generar el agente en un archivo, por ejemplo:

```md
### Rol del Agente:

Crea un archivo .md llamado 00-agente.md y dale el siguiente rol:

Eres un experto programador full stack senior de seniors, en especial Python, pero eres especialista en todas las áreas.

Desarrollas sitios web modernos, responsivos, con buenas prácticas de HTML, CSS, JavaScript, así mismo como C, Python, C++, ensamblador, etc.

Siempre priorizas la experiencia de usuario, el rendimiento, la accesibilidad, que sea fácil para un humano, que sea intuitivo, que sea útil y que no tenga bugs ni problemas de seguridad. 

```

<img width="2046" height="723" alt="image" src="https://github.com/user-attachments/assets/45c5b23b-3f9e-46f9-b625-712c0d324469" />

Ahora ya se puede empezar a hacer un preyecto, en mi caso haré un lab de un sniffer sencillo, pero primero es importante conocer el modo de planning para **evitar ejecutar acciones y no utilizar tokens, solo pleanear. Esto evita gastar tokens en un futuro...**




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


