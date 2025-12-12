# 🧠 Análisis de la anchura craneal en el Predinástico Egipcio

Este ejercicio analiza si existen diferencias en la anchura craneal (en milímetros) entre dos grupos arqueológicos:  
**Periodo Predinástico Temprano (Periodo 1)** y **Periodo Predinástico Tardío (Periodo 2)**.

El objetivo es aplicar técnicas de estadística básica para evaluar si la anchura del cráneo cambió con el paso del tiempo.

---

## 🎯 Objetivos del proyecto

- Calcular estadísticos descriptivos para ambos periodos  
- Analizar la distribución de los datos (asimetría, curtosis, rangos…)  
- Evaluar normalidad mediante el test de Kolmogorov–Smirnov  
- Visualizar los datos con boxplots e histogramas  
- Construir intervalos de confianza del 90%, 95% y 99%  
- Realizar un contraste de hipótesis entre medias  
- Comentar la validez y limitaciones de los resultados  

---

## 📊 Métodos y análisis realizados

### **1. Estadística descriptiva**
Para cada periodo se calcularon:
- Media, mediana y moda  
- Desviación estándar, varianza, rango  
- Cuartiles y rango intercuartílico  
- Asimetría y curtosis  

Se incluyen representaciones gráficas:
- Boxplots  
- Histogramas  

---

### **2. Test de normalidad (Kolmogorov–Smirnov)**

- **Periodo 1:** no sigue una distribución normal  
- **Periodo 2:** sí se ajusta a una distribución normal  

Se discuten las implicaciones de cara a los contrastes paramétricos posteriores.

---

### **3. Intervalos de confianza**

Se construyen intervalos del 90%, 95% y 99% para la diferencia de medias  
(Periodo 1 – Periodo 2).

En todos los casos los límites son **negativos**, lo que indica:

➡️ **Los cráneos del periodo temprano son más estrechos que los del periodo tardío.**

---

### **4. Contraste de hipótesis entre medias**

Se realiza un contraste t de dos muestras bajo homogeneidad de varianzas.  
Pese a que el Periodo 1 no es normal, se aplica el contraste y se comentan sus limitaciones.

**Resultado:** se rechaza la igualdad de medias → existe diferencia significativa.

También se menciona la posible alternativa no paramétrica (Mann–Whitney).

---

## 🧾 Conclusiones principales

- La anchura craneal **aumenta** del Periodo Temprano al Tardío.  
- El Periodo 1 muestra una distribución menos normal y con mayor curtosis.  
- En ambos grupos aparece un outlier.  
- La evidencia estadística respalda que  
  **los cráneos predinásticos tardíos son significativamente más anchos.**

---

## 📁 Contenido del repositorio

- PDF del ejercicio completo con todos los cálculos y explicaciones  
- Notebook de Python para reproducir el estudio
- Excel con datos

---

## 👤 Autora  
**Ane Acha González**

