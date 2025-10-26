# Gestión de Riesgos

## 1. Introducción

**Definición básica:**  
La gestión de riesgos en el desarrollo de software es el proceso sistemático de **identificar, evaluar, priorizar y controlar amenazas** que podrían afectar el éxito del producto, como:

- Factibilidad técnica  
- Atractivo a los usuarios  
- Sostenibilidad del negocio  
- Calidad (por ejemplo, fallos en el producto)

En contextos de productos informáticos, la gestión de riesgos es **explícita** cuando se integra formalmente en el ciclo de vida (desde *discovery* hasta *deployment*), reduciendo incertidumbres en equipos **ágiles o predictivos**.

**Cuándo:**  
Siempre se realiza gestión de riesgos, aunque con diferente nivel de detalle.  
Después de los **story maps** (que mapean necesidades y flujos de usuario), los riesgos emergen al **priorizar features**.  
La gestión de riesgos ayuda a **alinear el producto con los objetivos reales**, evitando *deuda técnica* o fallos en el logro de los objetivos de *releases*.

**Enlace con releases:**  
La gestión de *releases* (planificar, probar y desplegar versiones iterativas) actúa como una **forma natural de gestión de riesgos**, ya que permite entregas controladas, *feedback* temprano y ajustes que minimizan impactos negativos.

**Ejemplo:**  
En un *story map*, un *release* mínimo viable (*MVP*) reduce el riesgo de invertir en *features* no validadas.

---

## 2. Evaluación de riesgos: Matriz de probabilidad / impacto / exposición

**Concepto clave:**  
La evaluación cuantifica los riesgos para priorizarlos.  
Usa una matriz que combina los siguientes factores:

- **Probabilidad:** Likelihood de ocurrencia (baja/media/alta, o escala 1–5).  
- **Impacto:** Severidad si ocurre (en tiempo, costo, calidad o usuarios; baja/media/alta).  
- **Exposición:** Producto de `probabilidad × impacto`, midiendo el *riesgo total* (por ejemplo, exposición alta > 20 en escala 1–25).

**Cómo construir la matriz:**  
Tabla 5×5 (probabilidad en filas, impacto en columnas).  
Celdas coloreadas: verde (bajo), amarillo (medio), rojo (alto).

| Probabilidad \ Impacto | Bajo (1) | Medio (3) | Alto (5) |
|------------------------:|:--------:|:----------:|:--------:|
| **Alta (5)** | 5 (Bajo) | 15 (Medio) | 25 (Alto) |
| **Media (3)** | 3 (Bajo) | 9 (Medio) | 15 (Medio) |
| **Baja (1)** | 1 (Bajo) | 3 (Bajo) | 5 (Bajo) |

**Cálculo:**  
`Exposición = Probabilidad × Impacto`  
Prioriza riesgos con exposición **> 10**.

**Aplicación en software:**  
Ejemplo:  
- Riesgo: *dependencia de un proveedor externo*  
- Probabilidad: media  
- Impacto: alto  
- → Exposición: 15  

**Enlace con releases:**  
Evalúa riesgos por *release* para decidir **qué features posponer o adelantar**.

---

## 3. Mecanismos de gestión de riesgos

**Estrategias principales:**

- **Mitigación:** Reducir probabilidad o impacto antes de que ocurra.  
  *Ejemplo:* Implementar pruebas automatizadas para mitigar *bugs* en *releases*.

- **Transferencia:** Pasar el riesgo a terceros.  
  *Ejemplo:* Contratar seguros o *outsourcing* para componentes críticos, transfiriendo el riesgo técnico.

- **Contingencia:** Plan de respuesta si el riesgo se materializa.  
  *Ejemplo:* Reserva de presupuesto o equipo de respaldo (*backup*) para retrasos en un *release*.

- **Otras estrategias:**
  - **Evitar:** Eliminar el riesgo (por ejemplo, no usar una tecnología inestable).  
  - **Aceptar:** Monitorear sin acción si la exposición es baja.

**Integración con releases como mitigador:**  
Los *releases* frecuentes (por ejemplo, en *agile*) mitigan riesgos al **validar hipótesis tempranamente**, reduciendo la exposición acumulada.  
*Ejemplo:* Un *release* semanal permite contingencias rápidas frente a un gran lanzamiento anual.

**Ejemplo práctico:**  
- Riesgo: Integración con otras aplicaciones de la empresa  
- Probabilidad: alta  
- Impacto: medio  
- Mitigación: *Releases* modulares que manejen pocas integraciones a la vez  
- Transferencia: Soporte de un experto en la herramienta  
- Contingencia: Plan de vuelta atrás (*Rollback*)

---

## 4. Recomendaciones

- **Foco:** Presta atención a los riesgos más importantes.  
- **Herramientas simples:** Usa matrices en Excel o Miro; integra los riesgos en los *story maps* para priorizar.  
- **Integra al proceso (en la planificación):**  
  - Pregunta en cada *release* o *sprint*:  
    > “¿Qué riesgos ven en este *release* / *sprint*?”  
  - Ejercicio rápido:  
    > “¿Qué pasaría si la integración con tarjetas nos falla?”

---
