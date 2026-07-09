---
# Presentación: Ruta para Analista de Datos Jr en Costa Rica
theme: seriph
background: https://images.unsplash.com/photo-1551288049-bebda4e38f71?w=1200&h=675&fit=crop
title: Analista de Datos Jr - Costa Rica
info: |
  ## Ruta Profesional: Analista de Datos Junior
  Guía completa para iniciar una carrera en análisis de datos
  en empresas costarricenses e internacionales

class: text-center
drawings:
  persist: false
transition: slide-left
comark: true
duration: 45min
---
# 📊 Ruta: Analista de Datos Jr

## Costa Rica 🇨🇷

### Tu camino hacia la carrera en análisis de datos

<div @click="$slidev.nav.next" class="mt-12 py-1" hover:bg="white op-10">
  Presiona Espacio para continuar <carbon:arrow-right />
</div>

<div class="abs-br m-6 text-xl">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="slidev-icon-btn">
    <carbon:edit />
  </button>
  <a href="https://github.com" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
</div>

---

# ¿Qué es un Analista de Datos Jr?

Un **Analista de Datos Junior** es un profesional que:

- 📈 Recopila y procesa datos
- 🔍 Analiza patrones
- 📊 Crea visualizaciones
- 🛠️ Usa SQL, Python, Power BI
- 🤝 Colabora en equipos
- 💡 Apoya decisiones

<style>
h1 {
  background-color: #0066CC;
  background-image: linear-gradient(45deg, #00A8E8 10%, #004B87 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---

# 🌍 Oportunidades en Costa Rica

### **Empresas Locales**

- Financieras: BAC, BNCR
- Retail: Walmart, Pricesmart
- Seguros: INS, CCSS
- Telecomunicaciones

### **Multinacionales**

- Amazon, Google, Meta
- Deloitte, EY, PWC

### **Startups**

- Fintech: Qlip, Sinpe
- E-commerce: Didi, Uber

---

# 🎯 Ruta de Aprendizaje

**Fase 1: Fundamentos (3-4 meses)**

- Estadística básica
- SQL fundamentals
- Excel avanzado
- Lógica y programación

**Fase 2: Herramientas (2-3 meses)**

- Python/R para análisis
- Visualización (Power BI, Tableau)
- Git y control de versiones

::right::

**Fase 3: Proyectos (2-3 meses)**

- Proyectos portfolio
- Casos reales
- Kaggle competitions
- GitHub projects

**Fase 4: Especialización**

- Machine Learning básico
- Big Data intro
- Cloud (AWS, GCP)
- Certificaciones profesionales

---

# 📚 Requisitos: Nivel Básico

**Mes 1-2**

- ✅ BD relacionales
- ✅ SQL: SELECT, WHERE, JOIN
- ✅ Excel avanzado
- ✅ Lógica programación

---

# 📚 Requisitos: Nivel Intermedio

**Mes 3-4**

- 🐍 Python: pandas, numpy
- 📊 Estadística
- 🎨 Power BI / Tableau
- 🔐 Seguridad de datos

---

# 📚 Requisitos: Nivel Avanzado

**Mes 5+**

- ⚙️ ETL / Airflow
- 🤖 Machine Learning
- ☁️ AWS / GCP / Azure
- 📈 Análisis predictivo

---

layout: image-right
image: https://images.unsplash.com/photo-1517694712202-14dd9538aa97?w=600&h=400&fit=crop
----------------------------------------------------------------------------------------

# 🛠️ Stack Tecnológico

### **Imprescindible**

- SQL (PostgreSQL, MySQL)
- Excel / Google Sheets
- Python (pandas, NumPy)

### **Recomendado**

- Power BI / Tableau
- Git & GitHub
- Jupyter Notebooks

### **Bueno Tener**

- R, Airflow, Spark
- AWS / GCP / Azure

---

# 🎓 Certificaciones Valiosas

- Google Data Analytics
- Microsoft Data Analyst
- Tableau Desktop Specialist
- AWS Cloud Practitioner

---

# � Salarios en Costa Rica

### **Junior**

₡900k - ₡1.5M/mes

### **Semi-Senior**

₡1.5M - ₡2.5M/mes

### **Senior**

₡2.5M+/mes

> Empresas internacionales: +30-50%

---

# 🎓 Recursos Gratuitos

- 📖 **YouTube:** Maven Analytics, Alex The Analyst
- 💻 **Kaggle:** Datasets y competitions
- 🐍 **Codecademy:** Cursos interactivos
- 📊 **Mode Analytics:** SQL tutorial

---

# 💳 Cursos Pagados

- **Coursera:** Google Data Analytics
- **Udemy:** Data Science Bootcamp
- **Maven Analytics:** BI Bootcamp
- **DataCamp:** Data Analyst tracks

---

# 🤝 Comunidades en CR

- Data Science Costa Rica (Meetup)
- Dev.cr - Comunidad tech
- AI Costa Rica - IA y ML
- Tech Talks San José

---

layout: two-cols
layoutClass: gap-16
-------------------

# 📈 Primer Proyecto: Portfolio

Crear 3-5 proyectos que demuestren:

**Proyecto 1: Análisis SQL**

```sql
-- Análisis de ventas
SELECT 
  DATE_TRUNC(fecha, MONTH) as mes,
  SUM(monto) as total,
  COUNT(DISTINCT cliente_id) as clientes
FROM ventas
WHERE año = 2025
GROUP BY DATE_TRUNC(fecha, MONTH)
ORDER BY mes DESC;
```

::right::

**Proyecto 2: Python & Visualización**

```python
import pandas as pd
import matplotlib.pyplot as plt

df = pd.read_csv('datos.csv')
df.groupby('categoria')['ventas'].sum() \
  .plot(kind='bar', figsize=(10,6))
plt.title('Ventas por Categoría')
plt.show()
```

**Proyecto 3: Dashboard Real**

- Datos públicos (INEC, BCCR)
- Power BI o Tableau
- Insights accionables
- GitHub repository

---

# 💡 Tips para Entrevista

**Antes:**

- ✅ Domina tu portfolio
- ✅ Practica SQL queries
- ✅ Aprende de la empresa
- ✅ Prepara ejemplos STAR

**Durante:**

- 🎯 Muestra curiosidad
- 📊 Explica pensamiento
- 🤝 Destaca trabajo en equipo
- 💬 Pregunta sobre desafíos

---

# 🎤 Preguntas Comunes

1. Explica un análisis que hayas hecho
2. ¿Cómo manejas datos inconsistentes?
3. Correlación vs causalidad
4. Caso práctico: analiza este dataset
5. ¿Por qué quieres ser analista?

---

# ⛔ Red Flags a Evitar

- ❌ No investigar la empresa
- ❌ Sin ejemplos concretos
- ❌ Mentir sobre habilidades
- ❌ Despreciar trabajo manual

---

# 🚀 Timeline: 12 Meses

**Meses 1-2:** SQL + Excel + Estadística

**Meses 3-4:** Python + Power BI + Git

**Meses 5-7:** 3-5 proyectos + Kaggle

**Meses 8-12:** Certificaciones + Búsqueda

---

# 🌟 Tus Ventajas Competitivas

### **Bilingüe**

- Acceso a empresas gringas
- +30% más en salario

### **Ubicación**

- Hub tech de Latinoamérica
- Demanda > Oferta
- 100% remoto disponible

### **Soft Skills**

- Comunicación clara
- Trabajo en equipo
- Resolución de problemas

---

layout: center
class: text-center
------------------

# 🎯 Próximos Pasos

**Hoy:** Elige plataforma (Coursera, DataCamp)

**Esta semana:** SQL + GitHub + comunidades

**Este mes:** Primer proyecto portfolio

---

# 📞 Enlaces Útiles

### **Costa Rica**

- [Data Science CR](https://www.meetup.com)
- [Dev.cr](https://dev.cr)
- [LinkedIn Jobs](https://linkedin.com/jobs)

### **Globales**

- [Kaggle.com](https://kaggle.com)
- [Mode SQL](https://mode.com/sql-tutorial)
- [Coursera](https://coursera.org)

---

layout: center
class: text-center text-2xl
---------------------------

# ¡Éxito en tu Camino! 🚀

### **Recuerda:**

> La consistencia vence al talento cuando el talento no es consistente.
> — Jeff Bezos

### Tu carrera como Analista de Datos Jr

### ¡Comienza hoy! 💪
