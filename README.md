# Proyecto Final MML - 2025

## Introducción

Este repositorio contiene un proyecto orientado a **diseñar, prototipar y evaluar una solución basada en modelos de lenguaje natural**, incorporando todas las etapas del proceso de MLOps. La importancia de este proyecto radica en la necesidad creciente de soluciones efectivas en el ámbito de la **salud**, específicamente en el **sistema de respuesta a preguntas médicas**. Al aprovechar la capacidad de los modelos de lenguaje para entender y generar respuestas relevantes, se busca mejorar la interacción de los pacientes con la información médica, facilitando así la toma de decisiones informadas.

## Descripción General

### Objetivos del Proyecto

El objetivo principal es abordar las siguientes etapas:

1. **Definición del Problema**:
   - Identificar el problema o pregunta de negocio que se desea resolver y justificar su relevancia en el contexto actual de la salud.

2. **Diseño de la Solución**:
   - Crear un sistema basado en modelos de lenguaje para responder preguntas médicas. Esto incluye el desarrollo de modelos de embedding, modelos específicos entrenados para tareas definidas, y la implementación de técnicas de fine-tuning.

3. **Identificación del Conjunto de Datos**:
   - Utilizar el conjunto de datos de **MedQuAD** (Medical Question Answering Dataset), que incluye **47,457 pares de preguntas y respuestas médicas** extraídos de 12 sitios web del NIH. Este conjunto de datos cubre **37 tipos de preguntas** (por ejemplo, tratamiento, diagnóstico, efectos secundarios) y está diseñado para tareas de **IR (Information Retrieval)** y **NLP (Natural Language Processing)**.

4. **Implementación de un Prototipo**:
   - Crear un prototipo funcional que demuestre la aplicabilidad de la solución diseñada utilizando los recursos disponibles.

5. **Evaluación de la Solución**:
   - Establecer criterios claramente definidos para evaluar la solución. Esto incluye:
     - Aspectos a evaluar
     - Pruebas a realizar
     - Métricas a considerar
     - Justificación de la selección de aspectos, pruebas y métricas
     - Limitaciones de dichas pruebas y métricas
     - Cómo estas pruebas apoyan la toma de decisiones sobre la solución

6. **Exploración de Resultados**:
   - Analizar los resultados obtenidos, así como entender el alcance y las limitaciones de la solución implementada.

7. **Lecciones Aprendidas**:
   - Reflexionar sobre el proceso de desarrollo del proyecto y responder a la pregunta: si se realizara nuevamente, ¿qué se haría diferente?

8. **Presentación de Resultados**:
   - Preparar y presentar un resumen de no más de **10 minutos** que aborde los ítems anteriores y destaque los resultados clave del proyecto.

### Datos del Conjunto

El conjunto de datos **MedQuAD** se utiliza como insumo principal para este proyecto. Sus características incluyen:

- **47,457 pares de preguntas y respuestas**.
- Cobertura de múltiples **tipos de preguntas médicas**.
- Incluye anotaciones adicionales que enriquecen el contexto de las preguntas y permiten un análisis más robusto.

Es esencial para nuestra solución, ya que proporciona un marco realista para el entrenamiento y prueba de nuestros modelos de lenguaje natural.

### Requisitos de Instalación

Para ejecutar el proyecto será necesario instalar las siguientes bibliotecas, que son fundamentales para el procesamiento de datos y el entrenamiento de modelos:

```bash
pip install torch transformers datasets rouge-score sacrebleu evaluate torchsummary