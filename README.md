# 🔍 UML Antipattern Detection via Machine Learning

> Detección automática de antipatrones de diseño en modelos de negocio UML mediante aprendizaje automático y reglas de negocio.

**Universidad Nacional de La Rioja · INDELLaR · 2023–2024**  
Director Ejecutivo: Cristian Tomas Britos · Director Consultor: Marcelo Martinez

---

## 📌 Descripción del Proyecto

Este proyecto de investigación, presentado ante la Secretaría de Ciencia y Tecnología (SECyT) de la UNLaR, propone un modelo de **aprendizaje automático** capaz de detectar **antipatrones de diseño** en modelos de negocio representados con **diagramas UML**, con foco en las reglas de negocio subyacentes.

La detección temprana de antipatrones permite prevenir errores en etapas posteriores del ciclo de desarrollo de software, orientando hacia código más limpio y arquitecturas más sólidas.

---

## 🎯 Objetivos

- Identificar los antipatrones de diseño más recurrentes en diagramas UML de modelos de negocio
- Aplicar técnicas de **minería de datos** y **feature engineering** para representar modelos UML en formatos compatibles con ML
- Entrenar y evaluar clasificadores supervisados (árboles de decisión, SVM, redes neuronales)
- Producir recomendaciones concretas para mejorar la calidad del diseño en etapas tempranas

---

## 🧠 Stack Tecnológico

| Área | Tecnologías |
|---|---|
| Modelado | UML 2.0, Extensiones Eriksson-Penker |
| Machine Learning | Python, scikit-learn, TensorFlow/Keras |
| Análisis de datos | pandas, NumPy, matplotlib |
| Procesamiento de modelos | XMI/XML parsing, PlantUML |

---

## 📐 Metodología

```
1. Revisión del estado del arte
        ↓
2. Recopilación y limpieza de dataset (diagramas UML correctos + con antipatrones)
        ↓
3. Feature Engineering (estructura del diagrama, coherencia de reglas, complejidad)
        ↓
4. Selección y entrenamiento de modelos de clasificación supervisada
        ↓
5. Evaluación: Precisión · Sensibilidad · Especificidad · F1-score · AUC-ROC
        ↓
6. Documentación y transferencia de resultados
```

---

## 📊 Métricas de Evaluación

El desempeño del modelo se evalúa con:

- **Precisión** y **Recall** por clase de antipatrón
- **F1-score** como métrica balanceada
- **Curva ROC / AUC** para análisis multiescenario
- **Validación cruzada** k-fold

---

## 🔬 Antipatrones objetivo (iniciales)

Los antipatrones de diseño más frecuentemente detectados en modelos de negocio UML incluyen, entre otros:

- **God Class / Blob**: clases con responsabilidades excesivas
- **Spaghetti Business Rules**: reglas de negocio sin estructura clara
- **Ambiguous Associations**: relaciones entre entidades mal definidas
- **Missing Constraints**: ausencia de restricciones en el modelo

---

## 📁 Estructura del Repositorio

```
📦 UML-Antipattern-Detection-Investigation
 ┣ 📂 data/              # Datasets de diagramas UML (raw y procesados)
 ┣ 📂 notebooks/         # Jupyter notebooks de exploración y modelado
 ┣ 📂 src/               # Código fuente del pipeline de ML
 ┃ ┣ 📂 features/        # Extracción de características
 ┃ ┣ 📂 models/          # Modelos entrenados y configuraciones
 ┃ ┗ 📂 utils/           # Parsers UML, helpers
 ┣ 📂 docs/              # Documentación técnica y resultados
 ┗ 📜 README.md
```

---

## 👥 Equipo de Investigación

| Rol | Nombre | Institución |
|---|---|---|
| Director Ejecutivo | Cristian Tomas Britos | UNLaR - Sede Chamical |
| Director Consultor | Marcelo Martinez | UNLaR |
| Co-Director | Juan Nicolás Aguero | UNLaR - Sede Chamical |
| Integrante | Gabriela Romero | UNLaR |
| Integrante | Federico Saravia | UNLaR (Estudiante) |

**Instituto:** INDELLaR – Instituto de Desarrollo de los Llanos Riojanos  
**Departamento:** Ciencias Exactas, Físicas y Naturales

---

## 📚 Referencias Clave

- Brown et al. (1998). *AntiPatterns: Refactoring Software, Architectures, and Projects in Crisis*. Wiley.
- Gamma et al. (1994). *Design Patterns: Elements of Reusable Object-Oriented Software*. Addison-Wesley.
- Pressman, R. S. (2014). *Software Engineering: A Practitioner's Approach* (8th ed.). McGraw-Hill.
- Cortez & Naveda (2013). *Antipatrones en los Modelos de Software*. II CONECC.

---

## 📬 Contacto

**Cristian Tomas Britos**  
📧 cbritos@unlar.edu.ar  
🔗 [github.com/cristianbritos](https://github.com/cristianbritos)  
🏛️ Universidad Nacional de La Rioja · Sede Chamical

---

> *Este proyecto busca contribuir a la formación de estudiantes avanzados y profesionales en el área de ingeniería de software, mejorando la calidad del diseño desde las etapas más tempranas del desarrollo.*

Research in progress.
