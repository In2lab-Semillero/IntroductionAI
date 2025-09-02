# 📊 Base de Datos de Pacientes Hospitalizados

Este proyecto contiene información de pacientes hospitalizados y propone una serie de análisis y visualizaciones que van desde lo básico hasta lo muy avanzado.  

---

## 🗂️ Estructura de la Base de Datos  

| No | Nombre de la variable       | Descripción |
|----|-----------------------------|-------------|
| 1  | **numero_historia_clinica** | ID del registro. Ej. `85822412` |
| 2  | **numero_documento**        | ID del paciente. Ej. `2858387914` |
| 3  | **nombres**                 | Nombre del paciente. Ej: `Toni` |
| 4  | **apellidos**               | Apellidos del paciente. Ej. `Sáez Silva` |
| 5  | **genero**                  | Hombre, Mujer y Otro |
| 6  | **edad**                    | Número continuo entre 0 y 100 |
| 7  | **fecha_ingreso**           | Formato `AAAA-MM-DD`. Ej. `2024-06-27` |
| 8  | **fecha_egreso**            | Formato `AAAA-MM-DD`. Ej. `2024-06-27` |
| 9  | **dias_estancia**           | Numérico. Ej: `3.0` |
| 10 | **tipo_admision**           | Urgente, Programado o Remitido |
| 11 | **diagnostico_principal**   | Código ICD-10 y descripción. Ej: `J44 - Enfermedad pulmonar obstructiva crónica` |
| 12 | **diagnostico_secundario_1 al 5** | Códigos ICD-10 y descripciones. Ej: `N18 - Enfermedad renal crónica` |
| 13 | **grupo_etnico**            | Mestizo, Afrocolombiano, Indígena, … |
| 14 | **tipo_seguro**             | Subsidiado o Contributivo |
| 15 | **municipio**               | Ej: Medellín, Bello, Itagüí, Envigado, … |
| 16 | **departamento**            | Ej: Antioquia |

---

## 📝 Preguntas de Análisis  

### 🔹 Básico
1. **Distribución de Edad**  
   📈 Crear un **histograma** de la distribución de edad de los pacientes.  
2. **Proporción por Género**  
   🥧 Crear un **gráfico de pastel** mostrando la proporción de pacientes por género.  

### 🔹 Intermedio
3. **Días de Estancia por Tipo de Admisión**  
   📊 **Boxplot** comparando los días de estancia hospitalaria por tipo de admisión.  
4. **Top 10 Diagnósticos Principales**  
   📊 **Gráfico de barras** con los 10 diagnósticos principales más comunes.  
5. **Correlación entre Edad y Días de Estancia**  
   🔗 Evaluar si existe correlación entre la edad del paciente y los días de estancia.  

### 🔹 Intermedio - Avanzado
6. **Distribución Temporal de Ingresos**  
   📆 Analizar la **distribución mensual** de ingresos hospitalarios durante 2024.  

### 🔹 Avanzado
7. **Análisis de Comorbilidades**  
   🧩 Identificar las comorbilidades más comunes y su relación con los diagnósticos principales.  
8. **Análisis por Tipo de Seguro**  
   🏥 Comparar características de pacientes entre regímenes contributivo y subsidiado.  
9. **Análisis de Municipios**  
   🗺️ Analizar la distribución geográfica de pacientes y su relación con otras variables.  

### 🔹 Muy Avanzado
10. **Modelo Predictivo Simple**  
    🤖 Crear un modelo para **predecir los días de estancia** basado en edad, género y diagnóstico.  

---

## 🎯 Objetivo  

El propósito de este proyecto es **analizar patrones de hospitalización, diagnósticos y factores asociados a los pacientes**, con aplicaciones en **salud pública y gestión hospitalaria**.  

---

## ⚙️ Tecnologías sugeridas  

- Python 🐍  
- Pandas / Numpy (manejo de datos)  
- Matplotlib / Seaborn / Plotly (visualización)  
- Scikit-learn (modelado predictivo)  

---

✍️ Autor: *[Tu Nombre]*  
📌 Proyecto académico / de análisis de datos en salud
