#### NLP-2024: Posgrado FAMAF - Curso Minería de Datos para Texto

#### Título

## Evaluación de la Red Neuronal Recurrente Mamba para Extracción de Respuestas con PLN

Palabras clave: Answer extraction, redes neuronales recurrentes, Mamba, PLN, Large Language Models, Modelos de lenguage, Desempeño, métricas, benchmarcks.

#### Autor

Lic.  Horacio Brizuela

#### Marco académico

- Este trabajo se propone como Proyecto del curso de posgrado “Minería de Datos para Texto, edición 2024”, a cargo de la Dra. Laura Alsonso Alemany, Profesora Asociada del Grupo de Procesamiento de Lenguaje Natural, del Departamento de Ciencias de la Computación, FaMAF, UNC.

#### Motivación

La extracción de respuestas es una actividad de alta relevancia actual en el campo del Procesamiento del Lenguaje Natural (PLN). 

Hasta el presente, los modelos de redes neuronales como GPT-3 o BERT ([Devlin et al., 2019](https://arxiv.org/abs/1810.04805)), basados en transformers, han dominado esta tarea, pero su uso está limitado por sus altos requisitos computacionales ([Brown et al., 2020](https://arxiv.org/abs/2005.14165)). 

En contraste, las arquitecturas de las Redes Neuronales Recurrentes (RNNs), como por ejemplo Mamba, pueden manejar datos secuenciales con menores recursos ([Gu, Dao, 2023](https://arxiv.org/abs/2312.00752)).

Este trabajo evaluará las características y el desempeño de la Red Neuronal Recurrente Mamba para la extracción de respuestas en entornos de recursos limitados.

####  Introducción

Las RNNs pueden ofrecer ventajas sobre modelos como GPT-3 y BERT en entornos donde se necesita optimización de recursos. Las RNNs, como Mamba, podrían ser capaces de mantener el contexto a lo largo de secuencias de texto y ser útiles en tareas secuenciales.

Mamba es una arquitectura de deep learning con modelado secuencial. Está basada en el modelo S4 (Structured State Space sequence). Se trata de una red neuronal recurrente que se destaca por su eficiencia en tareas que requieren manejo de contexto, como la extracción de respuestas en textos largos. Su implementación en entornos con recursos computacionales limitados la convierte en candidata para una opción viable y eficiente ([Graves, 2013](https://arxiv.org/abs/1308.0850)).

#### Hipótesis de Trabajo

Mamba RNN puede realizar la extracción de respuestas de manera efectiva y eficiente en entornos locales. El desempeño de Mamba puede ser comparable a otros modelos grandes en términos de precisión y coherencia.

#### Objetivo Principal

Evaluar el desempeño y características de Mamba en la extracción de respuestas, específicamente su rendimiento computacional y precisión.

#### Actividades

##### Instalación y Configuración de Mamba RNN

El primer paso es la instalación y correcta configuración de Mamba RNN en un entorno local, asegurando que dicha configuración sea adecuada para su funcionamiento.
Determinación del Dataset

Se analizará el tipo de dataset necesario para la extracción de respuestas. Se determinarán los requisitos del dataset y se evaluarán diversas opciones, especialmente aquellas que permitan usar benchmarks.

##### Análisis de Características

Se ejecutará el código instalado y se estudiará su funcionamiento. El análisis se centrará en la evaluación de la gestión de datos secuenciales y los mecanismos presentes en Mamba. Se investigarán "scores" y métodos de análisis.

##### Evaluación Individual del Desempeño

1) Estudio de Métricas

Se investigarán métricas para la evaluación de RNNs aplicadas a la extracción de respuestas.

2) Pruebas y Reportes

Se realizarán pruebas en Mamba y se medirá su desempeño según las métricas. Se generarán reportes basados en estándares.

#####  Evaluación Comparada del Desempeño

1) Estudio de Benchmarks

Se investigarán benchmarks adecuados para la evaluación comparativa de RNNs aplicadas a la extracción de respuestas.

2) Pruebas Comparativas y Reportes

Se realizarán pruebas comparativas entre Mamba y otras redes neuronales, y se medirá su desempeño según las métricas y benchmarks. Se generarán reportes según los estándares establecidos.

#### Planificación

Se divide el volumen total de actividad en los siguientes paquetes de trabajo (Work Packages, WP):

    WP 1 (0,5 meses): Setup
    Actividad 4.1: Definición de requerimientos para instalación y configuración de Mamba RNN.
    Actividad 4.2: Determinación del dataset.
    Entregable: Reporte de requerimientos y reporte de instalación

    WP 2 (0,5 meses): Análisis
    Actividad 4.3: Análisis de características.
    Entregble: 	Reporte de análisis de características

    WP 3 (2 meses): Evaluación individual del desempeño
    Actividad 4.4: Evaluación individual del desempeño.
    Entregable: Reporte de evaluación individual.
    
    WP 4 (3 meses): Evaluación comparada
    Actividad 4.5: Evaluación comparada del desempeño.
    Entregable: Reporte de Evaluacio2n comparada del desempeño.

    WP 5 (1 mes): elaboración del reporte final del proyecto. Redacción de artículo científico-tecnológico.
    Entregables: 
    Reporte final.
    Artículo científico-tecnológico.

**Cuadro sintético**
https://github.com/FAMAphonic/NLP-2024/blob/main/images/Tabla%201%20-%20%20Planificación.png

#### Referencias

Rajpurkar, P., Zhang, J., Lopyrev, K., Liang, P. (2016). SQuAD: 100,000+ Questions for Machine Comprehension of Text. Proceedings of the 2016 Conference on Empirical Methods in Natural Language Processing (EMNLP) . [Link](https://aclanthology.org/D16-1264/). 

Devlin, J., Chang, M.-W., Lee, K., Toutanova, K. (2019). BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding. Proceedings of NAACL-HLT. [Link](https://arxiv.org/abs/1810.04805). 

Brown, T. B., Mann, B., Ryder, N., et al. (2020). Language Models are Few-Shot Learners. Advances in Neural Information Processing Systems. [Link](https://arxiv.org/abs/2005.14165).

Bahdanau, D., Cho, K., Bengio, Y. (2015). Neural Machine Translation by Jointly Learning to Align and Translate. ICLR. [Link](https://arxiv.org/abs/1409.0473).

Graves, A. (2013). Generating Sequences With Recurrent Neural Networks. arXiv preprint arXiv:1308.0850. [Link](https://arxiv.org/abs/1308.0850).

Merity, S., Keskar, N. S., Socher, R. (2017). Regularizing and Optimizing LSTM Language Models. arXiv preprint arXiv:1708.02182. [Link](https://arxiv.org/abs/1708.02182).

`enter code here`Gu, A., Dao, T. (2023). Mamba: Linear-Time Sequence Modeling with Selective State Spaces. arXiv:2312.00752. [Link](https://arxiv.org/abs/2312.00752).
