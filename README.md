# FL_DP_CANCER
Proyecto ejemplo de implementación de Aprendizaje Federado y Privacidad Diferencial en la clasificación de cáncer de mama con Deep Learning.
# Implementación de Aprendizaje Federado y Privacidad Diferencial en la Clasificación de Cáncer de Mama

## Descripción del Proyecto
Este proyecto demuestra la aplicación de técnicas de Aprendizaje Federado (FL) y Privacidad Diferencial (DP) en la clasificación de cáncer de mama utilizando el conjunto de datos Breast Cancer Wisconsin (Diagnostic). El objetivo es entrenar un modelo de clasificación de manera descentralizada y privada, donde cada cliente entrena un modelo local utilizando sus propios datos y, posteriormente, los modelos locales se agregan en un servidor para obtener un modelo global.

## Características Principales
- **Aprendizaje Federado (FL):** El proyecto implementa un enfoque de Aprendizaje Federado donde diferentes clientes (o nodos) entrenan modelos de clasificación localmente, y un servidor centralizado agrega estos modelos locales para formar un modelo global.
- **Privacidad Diferencial (DP):** Para proteger la privacidad de los datos, se incorpora Privacidad Diferencial durante el proceso de entrenamiento, permitiendo que el modelo aprenda patrones útiles sin comprometer información sensible de los pacientes.
- **Preprocesamiento de Datos:** El conjunto de datos se normaliza y se divide en subconjuntos asignados a cada cliente para el entrenamiento local.
- **Evaluación del Modelo:** Se presenta la evaluación del rendimiento del modelo global y los modelos locales en términos de precisión (accuracy), y se visualiza la pérdida y el epsilon a lo largo del entrenamiento.

## Tecnologías y Herramientas Utilizadas
- Python
- PyTorch
- Opacus (para Privacidad Diferencial)
- Jupyter Notebook

## Cómo Ejecutar el Proyecto
1. Asegúrate de tener instaladas todas las bibliotecas y herramientas necesarias.
2. Abre y ejecuta el Jupyter Notebook “FL+DP+CANCER+V2.ipynb”.

## Conclusiones
Este proyecto sirve como un ejemplo práctico de cómo implementar Aprendizaje Federado y Privacidad Diferencial en un problema de clasificación de cáncer de mama. Las técnicas utilizadas aquí pueden ser extendidas y aplicadas a otros problemas de aprendizaje de máquina en el ámbito de la salud y más allá, donde la privacidad de los datos es una preocupación clave.

### Agradecimientos

Este proyecto se inspiró y guió significativamente por el trabajo presentado en el paper “PrivateFL: Accurate, Differentially Private Federated Learning via Personalized Data Transformation” por Yuchen Yang, Bo Hui, Haolin Yuan, Neil Gong, y Yinzhi Cao, presentado en las Proceedings of the USENIX Security Symposium (Usenix'23) del año 2023. La estructura del código y las técnicas implementadas en este proyecto se desarrollaron con referencia al código fuente disponible en el repositorio de GitHub asociado al trabajo mencionado. Agradecemos a los autores originales por su contribución al campo y por proporcionar recursos de código abierto que facilitan el desarrollo de proyectos relacionados.

## ✨ Inspiración

Este proyecto se inspiró en el innovador trabajo realizado por PrivateFL: Accurate, Differentially Private Federated Learning via Personalized Data Transformation. In Proceedings of the USENIX Security Symposium (Usenix'23), el cual ofreció valiosas percepciones sobre el aprendizaje federado y la privacidad diferencial. Queremos expresar nuestro agradecimiento a los autores originales y contribuyentes del proyecto que nos inspiró por compartir su conocimiento y recursos con la comunidad de código abierto.


### Referencias

- Yang, Y., Hui, B., Yuan, H., Gong, N., & Cao, Y. (2023). PrivateFL: Accurate, Differentially Private Federated Learning via Personalized Data Transformation. In Proceedings of the USENIX Security Symposium (Usenix'23). [GitHub Repository](https://github.com/BHui97/PrivateFL)

