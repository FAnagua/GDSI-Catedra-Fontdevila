# The New User Story Backlog is a Map 

## Idea central
Jeff Patton critica la práctica común en Agile de mantener un **backlog plano** (una simple lista de historias de usuario) y propone reemplazarlo por un **user story map**, una estructura visual que muestra **cómo encajan las historias dentro del contexto general del sistema**.  
El objetivo es **mantener la visión completa del producto**, facilitar la priorización y planificar lanzamientos de forma más coherente.

---

##  Problemas de backlog plano

### 1. Pierde el contexto del sistema
- Un backlog plano es solo una lista de tareas o historias ordenadas por prioridad.  
- No explica **qué hace el sistema** ni **cómo las partes se relacionan entre sí**.  
- Los equipos y stakeholders pierden la “**big picture**”.  
- Patton compara esto con **arrancar todas las hojas de un árbol y tirarlas en una bolsa**: se pierde la estructura que da sentido al conjunto.

### 2. Difícil detectar huecos o ausencias
- Con solo una lista, es difícil saber si **faltan historias importantes** o si el sistema está completamente descrito.  
- El equipo siempre siente que algo se está olvidando.

### 3. Priorización tediosa
- Revisar cientos de historias una por una para priorizarlas es **aburrido, lento y poco productivo**.  
- No ayuda a visualizar qué partes son más críticas o dependientes entre sí.

---

## La propuesta: construir un User Story Map

###  Concepto general
Un **story map** organiza las historias **en dos dimensiones**:

- **De izquierda a derecha:** el flujo o secuencia de actividades del usuario (cómo usan el sistema).  
- **De arriba hacia abajo:** los detalles y niveles de descomposición (de lo más general a lo más específico).

Esto permite **contar una historia coherente del producto** mientras se conserva la jerarquía y el contexto.

---

##  Estructura del Story Map

###  Nivel 1 – Actividades (o “backbone”)
- Son las **grandes acciones** que los usuarios realizan.  
- Ejemplo: en un sistema de correo electrónico → “gestionar correo”, “configurar servidor”, “responder mensajes”.  
- Estas actividades son como la **columna vertebral del sistema**.

###  Nivel 2 – Tareas del usuario
- Son los **pasos concretos** que el usuario hace dentro de cada actividad.  
- Ejemplo: dentro de “gestionar correo”: “enviar mensaje”, “leer mensaje”, “borrar mensaje”, “marcar como spam”.  
- Estas tareas se colocan **debajo** de la actividad correspondiente.

### Orden y flujo
- El tiempo o flujo de uso **avanza de izquierda a derecha**.  
- Si las acciones se pueden hacer en cualquier orden, se las ordena según **cómo explicarías el sistema** al contar su historia.  
- Así, el mapa refleja tanto el **flujo del usuario** como la **estructura conceptual** del producto.

---

## Terminología: no más “épicas”

- Patton critica el término **“épica”** por ser poco descriptivo.  
- Prefiere usar **“actividades”** (para lo grande) y **“tareas de usuario”** (para lo más pequeño).  
- Eliminar un “epic” del backlog rompe el contexto; mejor mantener la jerarquía completa dentro del mapa.

---

## Cómo usar el Story Map

### 1. Construir el mapa colaborativamente
- Se hace con tarjetas, post-its o herramientas digitales.  
- Se identifican primero las actividades grandes (en la parte superior) y luego se van desglosando en tareas más pequeñas.  
- Esto se hace junto a usuarios, stakeholders y desarrolladores.

### 2. “Caminar” el mapa
- Revisar el mapa con usuarios y stakeholders.  
- Permite **detectar omisiones**, **errores de flujo** o **problemas reales**.  
- Facilita que todos hablen el mismo lenguaje visual.

### 3. Priorizar visualmente
- No se prioriza el **backbone** (las actividades principales), porque son esenciales.  
- Se priorizan las tareas **verticalmente**:  
  - Arriba → indispensables.  
  - Abajo → opcionales o de menor valor.  
- Esto revela el **“walking skeleton”**: la versión mínima del sistema que ofrece un flujo de valor completo de punta a punta.

### 4. Planificar lanzamientos
- Se dibujan **líneas horizontales** (swim lanes) que separan **releases** o **iteraciones**.  
- Así se ve claramente qué funcionalidades entran en cada versión y cómo progresa el producto de manera incremental.

### 5. Usar el mapa como radiador de información
- El mapa se **mantiene visible** durante todo el proyecto.  
- Sirve para comunicar el progreso y mantener presente el contexto general.  
- Durante la ejecución de sprints, se marcan directamente en el mapa las historias que se implementarán.

---

##  El “Backbone” y el “Walking Skeleton”

- Las **actividades principales** (backbone) son el esqueleto esencial del sistema.  
- Las **tareas prioritarias más altas** conforman el **walking skeleton**: el sistema más simple posible que funciona de extremo a extremo.  
- Este enfoque evita construir un producto incompleto (por ejemplo, “un auto sin frenos”).

---

## Aplicaciones en sistemas existentes
- Cuando se agregan nuevas funcionalidades a un producto ya existente:
  - El producto original ya tiene su backbone.  
  - Se puede crear **mini story maps** para cada nueva funcionalidad.  
  - Ayuda a mantener la coherencia y a priorizar internamente cada conjunto de historias.

---

##  Es un patrón, no una invención
- Patton reconoce que **no inventó** el concepto de story mapping: muchos otros lo desarrollaron de forma paralela.  
- Lo importante es que **funciona en la práctica**, y ha sido adoptado por muchas organizaciones.  
- Cumple la definición de un **patrón**: algo que varias personas descubren independientemente porque resuelve un problema recurrente.

---

##  Conclusión

| Problema | Solución que aporta el Story Map |
|-----------|----------------------------------|
| Pérdida del contexto | Muestra la estructura completa y cómo se relacionan las historias |
| Dificultad para explicar el sistema | Permite “contar la historia” del producto visualmente |
| Omisiones y huecos en el alcance | Facilita detectar pasos o funcionalidades faltantes |
| Priorización confusa | Organiza visualmente qué es esencial y qué no |
| Falta de visión del progreso | Funciona como radiador de información del proyecto |

---

El **User Story Map** transforma un backlog plano en una **representación viva y narrativa del producto**, que ayuda a todos los involucrados a **comprender, priorizar y construir software con propósito y contexto.**
