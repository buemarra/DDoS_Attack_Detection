# DDoS_Attack_Detection
________________________________________
Un ataque de denegación de servicio distribuido (DDoS) es una amenaza crítica para la seguridad de las redes. Estos ataques intentan saturar la red de destino mediante tráfico malicioso, provocando interrupciones en los servicios legítimos. A pesar del desarrollo de diversos métodos estadísticos, la detección eficaz en tiempo real sigue siendo un reto, especialmente con recursos computacionales limitados.

La evaluación de nuevos enfoques de detección requiere conjuntos de datos bien estructurados, lo cual motiva el presente desarrollo.

________________________________________

El presente repositorio recopila y detalla el desarrollo de Pruebas de Concepto (PoC) en Python para la detección de ataques de denegación de servicio distribuido (DDoS). Estas pruebas utilizan el conjunto de datos CICDDoS2019 y se enfocan en explorar y evaluar diversos métodos de Inteligencia Artificial (IA) y Aprendizaje Automático (ML/DL). El objetivo principal es validar la eficacia de estas técnicas para identificar tráfico de red malicioso en tiempo real.
El cuaderno representa una versión actualizada y consolidada de todas las PoC desarrolladas. Su propósito final es servir como base para el diseño de un Sistema de Detección de Intrusiones (IDS) con capacidad para dotar de conciencia situacional a Smart-Grids frente a ataques DDoS.
Este trabajo se fundamenta en la necesidad de sistemas de detección de bajo coste computacional y alta precisión para mitigar eficazmente las amenazas DDoS. Para la evaluación de los modelos, se utiliza el conjunto de datos CICDDoS2019, provisto por el Instituto Canadiense de Ciberseguridad (CIC). Es importante destacar que el uso de este conjunto de datos se adhiere a los términos de su licencia, la cual exige la citación del artículo de investigación original correspondiente.

________________________________________
Estructura de los Cuadernos
El presente estudio se organiza en cinco partes interconectadas, cada una enfocada en una etapa crucial del proceso de detección:
1.	Ingeniería de Datos: Se exploran diversas técnicas para preprocesar, limpiar y transformar los datos del CICDDoS2019, optimizándolos para su uso en modelos de IA.
2.	Modelos de Aprendizaje Automático (ML): Se implementan y comparan distintos algoritmos de ML supervisado y no supervisado para la clasificación de tráfico de red.
3.	Modelos de Aprendizaje Profundo (DL): Se desarrollan modelos de redes neuronales y otras arquitecturas de DL para mejorar la precisión y la capacidad de detección.
4.	Sistema Multi-Agente: Se crea un sistema distribuido utilizando contenedores Docker para simular un entorno de detección en tiempo real con múltiples agentes de IA.
5.	Visualización y Análisis de Flujos: Se aplican técnicas para identificar, analizar y visualizar los flujos de tráfico de red, facilitando la comprensión de los patrones de ataque.
Cada sección contribuye a la construcción de un sistema robusto y eficiente para la detección de ataques DDoS, proporcionando una visión integral desde el tratamiento inicial de los datos hasta la implementación de soluciones avanzadas.

________________________________________

Conjunto de Datos
Conjunto de Datos relativo a la documentación de un Ataque de Denegación Distribuida de Servicio (DDoS), realizado a partir del conjunto de datos publicado por el Instituto de Ciber Seguridad Canadiense (CIC) el año 2019.

Licencia

Según la información proporcionada por el Instituto Canadiense de Ciberseguridad es posible redistribuir, volver a publicar y reflejar el conjunto de datos CICDDoS2019 en cualquier forma.
https://www.unb.ca/cic/datasets/ddos-2019.html
Sin embargo, cualquier uso o redistribución de los datos debe incluir una cita al conjunto de datos CICDDoS2019 y el artículo publicado relacionado. Un trabajo de investigación en el que se esbozan los detalles de analizar el conjunto de datos IDS/IPS similar y principios relacionados:

- Iman Sharafaldin, Arash Habibi Lashkari, Saqib Hakak y Ali A. Ghorbani, ” Developing Realistic Distributed Denial of Service of Service (DDoS) Attack Dataset and Taxonomy “, IEEE 53rd International Carnahan Conference on Security Technology, Chennai, India, 2019. DOI: 10.1109/CCST.2019.8888419


