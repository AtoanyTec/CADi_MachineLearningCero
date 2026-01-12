# 📘 Machine Learning desde Cero para Docentes  
## Día 1 – Fundamentos y Modelos de Regresión (Teoría)

**Duración estimada de estudio:** 2–3 horas  
**Objetivo del documento:**  
Brindar a los profesores una **base conceptual sólida** sobre qué es el *Machine Learning*, cómo funciona y para qué sirve, así como introducir **regresión lineal y regresión logística** desde una perspectiva **intuitiva, aplicada y pedagógica**.

---

## 1️⃣ ¿Qué es Machine Learning?


::contentReference[oaicite:0]{index=0}


El **Machine Learning (ML)** es una rama de la inteligencia artificial que permite a las computadoras **aprender patrones a partir de datos**, sin ser programadas explícitamente con reglas fijas.

En lugar de decirle a la computadora *qué hacer en cada caso*, se le proporcionan **datos de ejemplo** para que **aprenda una relación** y pueda hacer **predicciones o decisiones** sobre datos nuevos.

### Ejemplo intuitivo
- Programación tradicional:  
  > *Si un alumno tiene menos de 70 → reprobado*
- Machine Learning:  
  > A partir de datos históricos, el modelo **aprende** qué variables influyen en aprobar o reprobar.

---

## 2️⃣ ¿Qué NO es Machine Learning?

Es importante aclarar falsas ideas comunes:

❌ No es magia  
❌ No “piensa” como un humano  
❌ No garantiza decisiones correctas  
❌ No reemplaza el criterio docente  

✔ Es una **herramienta estadística avanzada**  
✔ Depende totalmente de los **datos**  
✔ Requiere **interpretación humana**

---

## 3️⃣ Tipos de aprendizaje en Machine Learning

### 🔹 Aprendizaje Supervisado
El modelo aprende usando **datos con etiquetas** (respuestas conocidas).

Ejemplos:
- Calificación final (número)
- Aprobado / No aprobado (categoría)

Se usa cuando:
- Ya sabemos qué queremos predecir
- Tenemos ejemplos previos

👉 **Aquí se encuentran la regresión lineal y la regresión logística**

---

### 🔹 Aprendizaje No Supervisado
El modelo **no tiene etiquetas**, solo datos.

Ejemplo:
- Agrupar estudiantes por comportamiento
- Detectar perfiles similares

👉 Se verá en el **Día 2 (K-means)**

---

## 4️⃣ Flujo general de un proyecto de Machine Learning


::contentReference[oaicite:1]{index=1}


1. Definir el problema  
2. Recolectar datos  
3. Preparar datos  
4. Entrenar el modelo  
5. Evaluar resultados  
6. Interpretar y tomar decisiones  

⚠️ El **modelo no es el final**, lo más importante es la **interpretación**.

---

## 5️⃣ Regresión Lineal


::contentReference[oaicite:2]{index=2}


### 🔍 ¿Qué es?
La **regresión lineal** es un modelo que permite **predecir un valor numérico continuo** a partir de una o más variables.

Ejemplos:
- Predecir calificación final
- Estimar consumo de energía
- Relación horas de estudio → desempeño

---

### 🧠 Idea intuitiva
El modelo busca la **mejor recta posible** que se ajuste a los datos.

> “La mejor recta” es la que **comete menos error en promedio**.

No es necesario entender la fórmula matemática; basta con comprender que:
- Hay una **entrada**
- Hay una **salida numérica**
- El modelo aprende una relación entre ambas

---

### 📊 ¿Cómo se evalúa?
- Error promedio
- Qué tan lejos están las predicciones de los valores reales
- Interpretación visual (gráficas)

---

## 6️⃣ Regresión Logística


::contentReference[oaicite:3]{index=3}


### 🔍 ¿Qué es?
La **regresión logística** es un modelo de **clasificación**, usado cuando la respuesta es **una categoría**, normalmente binaria.

Ejemplos:
- Aprobado / Reprobado
- Sí / No
- Riesgo / No riesgo

---

### 🧠 Idea intuitiva
Aunque su nombre dice “regresión”, **no predice números**, sino **probabilidades**.

El modelo responde preguntas como:
> “¿Qué probabilidad hay de que ocurra esto?”

Luego convierte esa probabilidad en una decisión.

---

### 📈 Función sigmoide (intuición)
La sigmoide:
- Convierte cualquier valor en una probabilidad entre 0 y 1
- Permite tomar decisiones con umbrales

Ejemplo:
- Probabilidad ≥ 0.5 → Sí
- Probabilidad < 0.5 → No

---

## 7️⃣ Diferencia clave entre ambos modelos

| Característica | Regresión Lineal | Regresión Logística |
|---------------|-----------------|---------------------|
| Tipo de salida | Número continuo | Categoría / Probabilidad |
| Tipo de problema | Predicción | Clasificación |
| Ejemplo | Calificación | Aprobado / Reprobado |

---

## 8️⃣ Interpretación y pensamiento crítico

Un modelo **no es una verdad absoluta**.

Preguntas clave que todo docente debe hacerse:
- ¿Los datos representan bien la realidad?
- ¿Qué variables influyen más?
- ¿Qué casos falla el modelo?
- ¿Es ético usar este modelo para tomar decisiones?

---

## 9️⃣ Consideraciones éticas iniciales

⚠️ Especialmente importantes en educación:

- Sesgos en los datos
- Decisiones automatizadas
- Interpretaciones incorrectas
- Uso responsable de resultados

👉 **El modelo apoya la decisión humana, no la reemplaza**


