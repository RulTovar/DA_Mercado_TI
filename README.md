# 📊 Análisis del Mercado Laboral TI en México

## 📌 Descripción del Proyecto

Este proyecto analiza las tendencias del mercado laboral en el sector tecnológico mexicano utilizando datos de 5,000 ofertas de trabajo. El objetivo es identificar **roles mejor pagados**, **habilidades más demandadas**, **concentración geográfica de oportunidades** y **curva de crecimiento salarial por experiencia**.

El análisis combina **Python** para limpieza y procesamiento de datos, y **Tableau** para visualización interactiva.

---

## 🎯 Objetivos

- Identificar los roles TI con mayor remuneración.
- Determinar las habilidades técnicas más demandadas.
- Analizar la distribución geográfica de ofertas (CDMX, GDL, MTY, Querétaro, Puebla).
- Evaluar el crecimiento salarial según años de experiencia.
- Comparar salarios por modalidad (remoto, presencial, híbrido).

---

## 🛠️ Tecnologías Utilizadas

| Herramienta                | Propósito                                    |
| -------------------------- | -------------------------------------------- |
| **Python** (Pandas, NumPy) | Limpieza, transformación y análisis de datos |
| **Matplotlib / Seaborn**   | Visualizaciones exploratorias                |
| **SciPy**                  | Prueba estadística ANOVA                     |
| **Jupyter Notebook**       | Desarrollo y documentación del análisis      |
| **Tableau Public**         | Dashboard interactivo                        |

---

## 📁 Estructura del Repositorio

DA_Mercado_TI/
│
├── dashboard/ # Dashboard interactivo en Tableau Public
│
├── datos/
│ ├── raw/ # Dataset original (CSV)
│ └── processed/ # Datos limpios y procesados
│
├── insight/ # Presentación de resultados
│
├── notebooks/ # Análisis en Jupyter
│ ├── 01_eda_y_limpieza.ipynb
│ └── 02_feature_engineering.ipynb
│
├── outputs/ # Visualizaciones generadas en Python
│ └── graficos/
│
└── README.md

---

## 📈 Principales Hallazgos

| Categoría                   | Hallazgo                                          |
| --------------------------- | ------------------------------------------------- |
| **Rol mejor pagado**        | ML Engineer: **$55,381 MXN** mensuales            |
| **Segundo mejor pagado**    | DevOps: **$50,521 MXN** mensuales                 |
| **Habilidad más demandada** | Python (3,162 ofertas)                            |
| **Segunda habilidad**       | AWS (2,537 ofertas)                               |
| **Tercera habilidad**       | Docker (2,180 ofertas)                            |
| **Ciudad con más ofertas**  | CDMX (mayor concentración para todos los roles)   |
| **Crecimiento salarial**    | De 1 a 5 años de experiencia: incremento del ~70% |

> 📌 **Recomendación:** Priorizar formación en **Python**, complementada con **AWS** y **Docker** para maximizar empleabilidad.

---

## 🖥️ Dashboard Interactivo

El dashboard fue desarrollado en **Tableau Public** e incluye las siguientes visualizaciones:

1. Distribución de salarios mensuales (histograma)
2. Salario promedio por rol (barras horizontales)
3. Ofertas por rol y ciudad (tabla)
4. Top 10 habilidades más demandadas
5. Salario promedio por años de experiencia

🔗 **[Ver dashboard en Tableau Public](https://public.tableau.com/app/profile/rultovar/viz/Mercado_Laboral_Mxico/DashboardMercadoTIMxico)**  
_(Asegúrate de aceptar cookies si es necesario)_
