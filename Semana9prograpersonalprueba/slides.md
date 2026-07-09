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

transition: fade-out
--------------------

# ¿Qué es un Analista de Datos Jr?

Un **Analista de Datos Junior** es un profesional que:

- 📈 **Recopila y procesa** datos de diversas fuentes
- 🔍 **Analiza patrones** para extraer insights valiosos
- 📊 **Crea visualizaciones** para comunicar hallazgos
- 🛠️ **Usa herramientas** SQL, Python, Power BI
- 🤝 **Colabora** con equipos multidisciplinarios
- 💡 **Apoya decisiones** basadas en datos

### Oportunidades en Costa Rica

- **Empresas locales:** Financieras, retail, seguros
- **Multinacionales:** Tech, consultoría, manufactura
- **Startups:** Fintech, e-commerce, SaaS

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

layout: two-cols
layoutClass: gap-16
-------------------

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

# 📚 Requisitos Técnicos Esenciales

## Nivel Básico (Mes 1-2)

- ✅ Conceptos de BD relacionales
- ✅ Queries SQL básicos (SELECT, WHERE, JOIN)
- ✅ Excel avanzado (tablas dinámicas, gráficos)
- ✅ Lógica de programación

## Nivel Intermedio (Mes 3-4)

- 🐍 Python: pandas, numpy, matplotlib
- 📊 Fundamentos de estadística
- 🎨 Herramientas de visualización
- 🔐 Conceptos de seguridad de datos

## Nivel Avanzado (Mes 5+)

- ⚙️ Automatización de ETL
- 🤖 Introducción a ML
- ☁️ Herramientas en la nube
- 📈 Análisis predictivo

---

layout: image-right
image: https://images.unsplash.com/photo-1517694712202-14dd9538aa97?w=600&h=400&fit=crop
----------------------------------------------------------------------------------------

# 🛠️ Stack Tecnológico

### **Imprescindible**

```
SQL (PostgreSQL, MySQL, SQL Server)
Excel / Google Sheets
Python (pandas, NumPy, Matplotlib)
```

### **Recomendado**

```
Power BI / Tableau
Git & GitHub
Jupyter Notebooks
```

### **Bueno Tener**

```
R (ggplot2, dplyr)
Airflow (ETL)
Spark básico
AWS / GCP / Azure
```

### **Certificaciones Valiosas**

- Google Data Analytics Certificate
- Microsoft Data Analyst
- Tableau Desktop Specialist
- AWS Cloud Practitioner

---

# 💼 Oportunidades Laborales en CR

### Empresas Locales

| Sector                       | Ejemplos                         |
| ---------------------------- | -------------------------------- |
| **Financiero**         | BAC, BNCR, Scotiabank, BCAC      |
| **Retail**             | Walmart, Pricesmart, Tiendas Max |
| **Seguros**            | INS, CCSS, Seguros Universal     |
| **Telecomunicaciones** | Kolbi, Claro, Movistar           |

### Multinacionales & Startups

- **Amazon, Google, Meta** (sedes regionales)
- **Startups Fintech:** Qlip, Sinpe, Prpaybox
- **E-commerce:** Shopify, Didi, Uber
- **Consultorías:** Deloitte, EY, PWC

### Salarios (Rango aproximado 2024-2026)

- **Junior:** ₡900k - ₡1.5M/mes
- **Semi-Senior:** ₡1.5M - ₡2.5M/mes
- **Senior:** ₡2.5M+/mes

---

# 🎓 Recursos para Aprender

### **Plataformas Online Gratuitas**

- 📖 **YouTube:** Maven Analytics, Alex The Analyst, DataCamp
- 💻 **Kaggle:** Datasets y competitions
- 🐍 **Codecademy:** Cursos interactivos
- 📊 **Mode Analytics:** Tutorial SQL

### **Cursos Pagados (Recomendados)**

- **Coursera:** Google Data Analytics, IBM Data Analysis
- **Udemy:** "The Complete Hands-On Introduction to Data Science"
- **Maven Analytics:** Business Intelligence Bootcamp
- **DataCamp:** Data Analyst tracks

### **Comunidades en CR**

- **Data Science Costa Rica** (Meetup, Facebook)
- **Dev.cr** - Comunidad tech local
- **AI Costa Rica** - Grupo de IA y ML
- **Tech Talks San José** - Conferencias locales

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

# 💡 Tips para Entrevistas

### **Antes de la Entrevista**

- ✅ Domina tu portfolio y proyectos
- ✅ Practica SQL queries comunes
- ✅ Aprende sobre la industria de la empresa
- ✅ Prepara ejemplos STAR (Situation, Task, Action, Result)

### **Durante la Entrevista**

- 🎯 Muestra curiosidad por los datos
- 📊 Explica tu pensamiento analítico
- 🤝 Destaca trabajo en equipo
- 💬 Pregunta sobre desafíos reales

### **Preguntas que te Harán**

```
1. Explica un análisis que hayas hecho
2. ¿Cómo manejarías datos inconsistentes?
3. Diferencia entre correlación y causalidad
4. Caso práctico: "Analiza este dataset"
5. ¿Por qué quieres ser analista de datos?
```

### **Rojo Flags a Evitar**

- ❌ No investigar la empresa
- ❌ No tener ejemplos concretos
- ❌ Mentir sobre habilidades
- ❌ Despreciar el trabajo manual

---

# 🚀 Plan de Acción (12 Meses)

```
MESES 1-2: Fundamentos
├─ SQL básico + intermedio
├─ Excel avanzado
└─ Estadística 101

MESES 3-4: Herramientas
├─ Python para análisis
├─ Visualización (Power BI)
└─ Git & GitHub

MESES 5-7: Proyectos
├─ 3-5 proyectos portfolio
├─ Kaggle competitions
└─ Contribuciones GitHub

MESES 8-12: Especialización & Búsqueda
├─ Certificaciones
├─ Networking en comunidades
├─ Entrevistas técnicas
└─ Aplicar a posiciones
```

---

# 🌟 Ventajas Competitivas en CR

### **Ser Bilingüe**

- Español + Inglés = acceso a empresas gringas
- Valora mucho + dinero en multinationales

### **Ubicación Geográfica**

- Hub tech de América Latina
- Atrae inversión extranjera
- Salarios competitivos

### **Mercado en Crecimiento**

- Demanda > Oferta (2024-2026)
- Empresas buscan talento junior
- Oportunidades de remoto 100%

### **Soft Skills Importantes**

- 💬 Comunicación clara
- 🤝 Trabajo en equipo
- ⏱️ Gestión de proyectos
- 🎯 Resolución de problemas

---

layout: center
class: text-center
------------------

# 🎯 Próximos Pasos

## Hoy mismo:

1. Elige una plataforma (Coursera, DataCamp)
2. Registrate en Kaggle
3. Crea una carpeta para proyectos

## Esta semana:

1. Completa primer módulo SQL
2. Configura GitHub
3. Únete a comunidades locales

## Este mes:

1. Primer proyecto en portfolio
2. Establece meta clara
3. Busca mentor en tech

---

# 📞 Recursos Finales

### **En Costa Rica**

- 🌐 [LinkedIn CR Tech Community](https://linkedin.com)
- 👥 [Data Science Costa Rica](https://www.meetup.com)
- 💼 [LinkedIn Jobs CR](https://linkedin.com/jobs)

### **Plataformas Globales**

- 🐍 [Python.org](https://python.org)
- 📊 [Kaggle.com](https://kaggle.com)
- 📖 [Mode Analytics SQL](https://mode.com/sql-tutorial)
- 🎓 [Coursera](https://coursera.org)

### **Síguenos**

- 📧 Newsletter de Data Science
- 🐦 Expertos en Twitter/X
- 📺 Canales de YouTube recomendados

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
