# Predicción de evento coronario a 10 años - Framingham_CHD

# Generación y validación de un modelos predictivos de riesgo cardiovascular:
---
# Framingham_CHD
---
* El Framingham Heart Study es un estudio epidemiológico longitudinal que comenzó en 1948 en la ciudad de Framingham, Massachusetts, y ha sido fundamental para la comprensión de las enfermedades cardiovasculares (ECV).

* El Framingham CHD (Coronary Heart Disease) Dataset es un subconjunto de datos de este estudio y se utiliza comúnmente en investigaciones médicas y proyectos de machine learning relacionados con la predicción del riesgo de enfermedad coronaria (CHD).

* Este dataset es popular para modelos de clasificación que predicen la probabilidad de desarrollar una enfermedad coronaria a lo largo de 10 años.
 
---
## Estructura del Dataset:
---
**Este dataset contiene una variedad de variables clínicas y de estilo de vida, como:**

* Edad **(age):** Edad de la persona.
* Sexo **(sex):** Género (generalmente codificado como 1 para hombres y 0 para mujeres).
* Cantidad de medicamentos que toma si tiene HTA **(BPMeds)**
* Presión Arterial **(sysBP y diaBP):** Presión arterial sistólica y diastólica.
* Colesterol Total **(totChol):** Nivel de colesterol total.
* Nivel de Glucosa **(glucose):** Nivel de glucosa en sangre.
* Fumador **(currentSmoker):** Indicador de si la persona es fumadora.
* Diabetes **(diabetes):** Indicador de si la persona tiene diabetes.
* Índice de Masa Corporal (IMC) **(BMI):** Una medida basada en la altura y el peso de la persona.
* Historia Familiar de ECV **(prevalentStroke y prevalentHyp):** Indicadores de si la persona tiene historia familiar de accidente cerebrovascular o hipertensión.
* Enfermedad Coronaria **(TenYearCHD):** Objetivo del dataset, que indica si la persona desarrolló una enfermedad coronaria en un periodo de 10 años.
---
## Modelos desarrollados:
* Regresión Logística.
* Redes neuronales.
* Árboles de decisión.
* SVM.

---

## Etapas:
* Análisis de los datos (variables, distribución, utilidad de los datos).
* Visualización de datos.
* Preprocesamiento (selección de variables, split en entrenamiento y prueba, escalamiento / normalización, downsampling).
* Construcción del modelo.
* Entrenamiento del modelo.
* Evaluación de métricas de desempeño.
* Guardamos los modelos entrenados.
* LLamamos al modelo para predicción por consola o con un dataset nuevo.

---
---  
