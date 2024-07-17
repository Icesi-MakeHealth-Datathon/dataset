![banner](https://github.com/user-attachments/assets/9474436d-8954-463f-9bf6-83add23defec)

# Dataset Repository

## Dataset 1, disponible en la carpeta dataset1
### Clasificación del tiempo de ventana en pacientes con ACV al despertar a partir de imágenes de tomografía computarizada de cráneo simple.

**Contexto:** El abordaje y tratamiento del ataque cerebrovascular isquémico (ACV) actualmente se define teniendo en cuenta la ventana terapéutica. Sin embargo, hasta el 25% de los pacientes ingresan con ACV de tiempo de inicio desconocido. El uso de algoritmos de inteligencia artificial podría apoyar el abordaje diagnóstico mediante la estimación del tiempo de ventana de pacientes con ACV isquémico de tiempo de inicio desconocido con el fin de apoyar la toma de decisiones desde la perspectiva terapéutica.

**Datos:** Los datos son obtenidos a partir del procesamiento de imágenes médicas volumétricas, generación de máscaras y extracción de radiomics utilizando Python y los paquetes pydicom y pyradiomics (https://pyradiomics.readthedocs.io/en/latest/). 

## Dataset 2, disponible en la carpeta dataset2
### Clasificación del tipo de parénquima mamario a partir de imágenes de mamografía digital.
**Contexto:** La imagen de mamografía digital es una imagen diagnóstica que utiliza radiación ionizante para explorar el seno. Se realizan dos proyecciones, una medio lateral oblicua y una cráneo caudal. Este estudio permite identificar signos tempranos de cáncer de mama. Existen múltiples algoritmos que intentan identificar estos signos, sin embargo, debido a la composición del parénquima mamario, en algunos casos este proceso es un reto. Identificar el tipo de tejido mamario (A, B, C, D) podría ser útil como un paso previo a la aplicación de técnicas de procesamiento de imágenes y algoritmos de inteligencia artificial para mejorar el desempeño general de estas metodologías. 

**Datos:** Los datos son obtenidos a partir del procesamiento de imágenes médicas bidimensionales, generación de máscaras y extracción de radiomics utilizando Python y los paquetes pydicom y pyradiomics (https://pyradiomics.readthedocs.io/en/latest/). 
Encuentra la descripción conceptual y matemática de cada uno de los radiomics en este enlace https://pyradiomics.readthedocs.io/en/latest/features.html. 

## Dataset 3, disponible en la carpeta dataset3
### Identificación de inasistencias en pacientes con citas programadas para estudios de resonancia magnética en un centro de alta complejidad en Cali.

**Contexto:** El problema de las inasistencias a citas médicas genera pérdidas económicas significativas y afecta la eficiencia operativa de las instituciones de salud en Colombia, y en general en cualquier país del mundo. Para abordar el problema de inasistencias de los pacientes a las citas agendadas se puede utilizar un modelo de clasificación en dos clases previamente definidas, que son: “ASISTE” o “NO ASISTE”. De este modo, se ayuda a las instituciones a tomar decisiones informadas, optimizar la asignación de recursos, reducir costos operativos y mejorar la satisfacción y adherencia de los pacientes a sus tratamientos. 


**Datos:** Los datos obtenidos han sido recibidos directamente del personal involucrado en el área, de la Fundación Valle del Lili. Estos datos son un historial generado por los sistemas internos de gestión de pacientes de la FVL, por lo cual cuentan con las características y atributos de interés para la institución. El conjunto de datos abarca información detallada sobre citas médicas y datos sociodemográficos de los pacientes. Incluye datos sobre el agendamiento y la asistencia a citas, confirmaciones, antecedentes del paciente, y tipo de estudio médico realizado. Además, proporciona información personal y social de los pacientes, como edad, sexo, y residencia. Este conjunto de datos es útil para analizar la gestión de citas médicas y el perfil demográfico y socioeconómico de los pacientes atendidos.

## Dataset 4, disponible en la carpeta dataset4
### Prediccion de Apnea del sueño
**Contexto:** La apnea del sueño es un trastorno del sueño caracterizado por pausas repetidas en la respiración o períodos de respiración superficial durante el sueño. Estas pausas pueden durar desde unos pocos segundos hasta minutos y pueden ocurrir 30 veces o más por hora. La apnea del sueño puede ser obstructiva (la más común), central (menos común), o una combinación de ambas. La Apnea Obstructiva del Sueño (AOS) ocurre cuando los músculos de la garganta se relajan excesivamente, bloqueando parcialmente o completamente las vías respiratorias superiores.

**Datos:** Los datos representan las variables principales de la Historia Clinica Electronica. Entre éstas están: Diagnosticos, Médicamentos, Motivos de consulta y Sintomas.
