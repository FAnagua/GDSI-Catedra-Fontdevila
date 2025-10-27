# 📘 Estimaciones — Resumen de Lecturas

---

## 1. Parametric vs Analogous Estimating — Project Management Academy  


###  Resumen  
**Título:** *The Difference Between Parametric vs. Analogous Estimating*

**Concepto central:**  
Comparación entre dos técnicas tradicionales de estimación en gestión de proyectos:

- **Estimación análoga:** usa proyectos pasados similares para generar una “aproximación rápida” (*top-down*).  
- **Estimación paramétrica:** utiliza datos históricos más detallados con variables definidas (por ejemplo, costo por metro cuadrado o horas por unidad) y los escala para estimar nuevos proyectos.

**Cuándo usar cada una:**

- **Análoga:** cuando hay poca información detallada y se necesita una estimación rápida.  
- **Paramétrica:** cuando los componentes del proyecto son bien definidos, repetibles y se dispone de datos sólidos.

**Ventajas y desventajas:**

| Técnica | Ventajas | Desventajas |
|----------|-----------|-------------|
| **Análoga** | Rápida, simple, poco esfuerzo | Menor precisión, depende mucho del juicio experto |
| **Paramétrica** | Más precisa, basada en datos, escalable | Requiere datos históricos fiables, más esfuerzo |

**Implicaciones para gestión de proyectos:**  
Ambas técnicas son reconocidas por el PMI en el área de “estimar costos” o “duración”. Entender la diferencia entre velocidad y precisión es clave para elegir la técnica adecuada.

---

## 2. 12 técnicas para la estimación de costes en proyectos — OBS Business School  


###  Resumen  
**Título:** *12 técnicas para la estimación de costes en proyectos*

**Contenido principal:**  
El artículo presenta 12 técnicas de estimación, desde las más simples hasta las más elaboradas:

1. Juicio de expertos  
2. Estimación por analogía  
3. Estimación paramétrica  
4. Estimación de tres puntos (PERT)  
5. Reservas o contingencias  
6. Análisis de propuestas de proveedores  

**Puntos destacados:**

- **Tres puntos (PERT):** usa tres estimaciones —optimista, más probable y pesimista— para obtener una media ponderada que refleje la incertidumbre.  
- **Análisis de propuestas:** solicita estimaciones externas (por ejemplo, de proveedores) para comparar opciones.

**Observaciones prácticas:**

- Panorama completo de técnicas de estimación de costos.  
- Útil para distintos tipos de proyectos (construcción, software, servicios).  
- Recomendado como material de referencia general.

---

## 3.  Método Monte Carlo: Simula y toma decisiones — Asana  


###  Resumen  
**Título:** *Método Monte Carlo: Simula y toma decisiones*

**Concepto esencial:**  
El método Monte Carlo es una técnica de simulación probabilística para analizar la incertidumbre en la planificación y toma de decisiones.

**Pasos del método:**

1. Definir variables inciertas (ejemplo: duración de tareas).  
2. Asignar distribuciones de probabilidad.  
3. Ejecutar miles de simulaciones aleatorias.  
4. Analizar los resultados (por ejemplo, “80 % de probabilidad de terminar antes del día X”).

**Ventajas:**

- Muestra un rango de resultados posibles en lugar de un valor fijo.  
- Permite tomar decisiones basadas en probabilidad.  
- Mejora la gestión del riesgo y las reservas del proyecto.

**Limitaciones:**

- Requiere datos confiables y modelado estadístico.  
- Puede percibirse como complejo o técnico.  
- No elimina la incertidumbre, solo la cuantifica.

**Aplicación:**  
Ideal para proyectos con alto nivel de incertidumbre o muchas variables. Puede combinarse con técnicas tradicionales como PERT.

---

## 4.  Story Points: Estimation Guide — Asana  


###  Resumen  
**Título:** *Story Points: Estimation Guide for User Stories in Agile*

**Definición:**  
Los *story points* son una técnica de estimación relativa usada en entornos ágiles.  
Miden **esfuerzo**, **complejidad** y **riesgo**, no tiempo.

**Proceso de estimación (6 pasos):**

1. Presentar el concepto al equipo.  
2. Definir una escala (Fibonacci o tallas: XS, S, M, L, XL).  
3. Crear una matriz de referencia con historias anteriores.  
4. Usar *planning poker* para estimar colaborativamente.  
5. Planificar el sprint según la “velocidad” del equipo.  
6. Revisar y ajustar el proceso tras cada iteración.

**Beneficios:**

- Permite estimar más rápido y de forma colaborativa.  
- Considera riesgo e incertidumbre.  
- Fomenta el aprendizaje continuo del equipo.

**Errores comunes:**

- Convertir puntos en horas.  
- Asignar valores sin calibración.  
- Promediar sin discusión.  
- Estimar historias demasiado grandes.

---

## 5.  Q&A with Vasco Duarte on #NoEstimates — InfoQ  


###  Resumen  
**Título:** *Q&A with Vasco Duarte on the #NoEstimates Book*

**Contexto:**  
El movimiento **#NoEstimates** propone reducir la dependencia de estimaciones detalladas, priorizando la entrega continua de valor.

**Ideas clave:**

- No se trata de “no estimar nunca”, sino de enfocar la energía en **medir valor y progreso real**.  
- En lugar de “¿Cuántas horas llevará esto?”, se pregunta “¿Qué valor aporta?”.  
- Busca evitar sesgos y sobreplanificación provocados por estimaciones tradicionales.

**Ventajas:**

- Mayor agilidad y adaptabilidad.  
- Menos tiempo perdido en estimaciones inciertas.  
- Foco en resultados tangibles y feedback rápido.

**Críticas / limitaciones:**

- Difícil de aplicar en proyectos regulados o de gran escala.  
- Requiere madurez organizacional y confianza.  
- No elimina toda estimación, pero la minimiza y reemplaza por métricas de flujo o *throughput*.

---

## 6.  #NoEstimates Project Planning Using Monte Carlo — InfoQ  

###  Resumen  
**Título:** *#NoEstimates Project Planning Using Monte Carlo*

**Tema central:**  
Combina el enfoque **#NoEstimates** con la simulación de **Monte Carlo** para estimar proyectos sin usar descomposición tradicional por tareas.

**Metodología:**

1. Identificar una **clase de referencia**: proyectos similares en contexto y tamaño.  
2. Construir una **distribución histórica**: con datos reales de entregas pasadas.  
3. Ubicar el nuevo proyecto dentro de esa distribución para calcular probabilidades de duración.  
4. **Simular con Monte Carlo:** miles de escenarios posibles para obtener una curva de probabilidad.

**Ventajas:**

- Sustituye las estimaciones puntuales por rangos probabilísticos.  
- Reconoce la incertidumbre y ayuda a gestionar riesgos.  
- Permite planificar sin detallar exhaustivamente cada tarea.

**Limitaciones:**

- Requiere datos históricos confiables.  
- Puede ser difícil de comunicar a *stakeholders* acostumbrados a “fechas fijas”.  
- Demanda cambio cultural hacia pensamiento probabilístico.

---

## Comparativa General

| Técnica / Enfoque | Tipo | Precisión | Requisitos | Cuándo usar |
|--------------------|-------|------------|-------------|--------------|
| **Análoga** | Tradicional | Media | Proyectos previos similares | Cuando hay poca información |
| **Paramétrica** | Tradicional | Alta | Datos cuantitativos confiables | Cuando el trabajo es repetible y medible |
| **Tres puntos (PERT)** | Tradicional | Alta | Valores optimista, probable, pesimista | Cuando existe incertidumbre moderada |
| **Monte Carlo** | Simulación | Muy alta | Distribuciones de probabilidad | Proyectos con alta incertidumbre |
| **Story Points** | Ágil / Relativa | Media | Experiencia del equipo | En equipos ágiles maduros |
| **#NoEstimates** | Enfoque moderno | Variable | Datos históricos / métricas de flujo | Entornos ágiles, foco en entrega continua |
