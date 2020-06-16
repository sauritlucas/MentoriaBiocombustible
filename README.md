# Reducción de Emisiones Contaminantes por el Uso de Biocombustibles en Transporte de Cargas y Pasajeros
Mentora: Nindirí Armenta Guerrero

## Motivación
La Bioenergía es considerada elemento esencial en el ahorro de emisiones mundiales; sobretodo en medios con alternativas limitadas de descarbonización, como el transporte de cargas y pasajeros, la aviación y la marítima internacional.
Una de las alternativas más beneficiosas para mitigar la generación de dióxido y monóxido de carbono al ambiente son los biocombustibles, como el biodiesel. Estudios a nivel internacional lo corroboran, así como la Agencia Mundial de Energía (en 2050, un 27 % del combustible utilizado en el transporte en todo el mundo debe basarse en biocarburantes para alcanzar los objetivos de cuidado ambiental, definidos en las diferentes convenciones mundiales).
En Argentina, las Cámaras, Empresas, y Provincias, están trabajando en un proyecto de Ley que declare de interés Nacional el uso de Biocombustibles, dentro de un mercado regulado y controlado. Uno de los objetivos del proyecto de Ley es que Argentina sea el número uno de Latinoamérica en el uso y producción de Biocombustibles, con la finalidad de reducir los gases que generar efecto invernadero, y sustituir el uso e importación de combustibles fósiles.
El programa Rango Verde, se dedica a coordinar iniciativas para la sustentabilidad, el ahorro energético en empresas del sector y reducir las emisiones de Gases de Efecto Invernadero (GEI). En este marco, Cintelink, plataforma tecnológica de Gestión y Control de Combustibles, en conjunto con las Cámaras, la FADEEAC, y cientos de Transportistas que utilizan la plataforma para sus operaciones diarias, estamos gestando una solución colaborativa para el uso de Biocombustibles controlados basados en datos de telemetría (IoT). Con lo cual, sin necesidad de inversiones de capital para el reemplazo del parque automotor existente, Argentina podría reducir considerablemente sus emisiones y alcanzar los objetivos planteados a escala global.

## Este tema es interesante porque…
Las restricciones en el uso extensivo de Biocombustibles pueden eliminarse mediante la implementación de tecnología basada en datos, que facilite realizar las gestión necesaria para ello.
En general, es necesario que se provea a tiempo, que se asegure su calidad, que la distribución sea eficiente, que se detecten adulteraciones intencionales, que los sistemas de despacho y de control de inventarios registren correctamente la información, y que pueda conocerse públicamente la información de la matriz energética utilizada en Transporte y sus eficiencias comparativas. Todo esto es posible con la Ciencia de Datos aplicada.

## Trataremos de responder algunas de las siguientes preguntas:
¿Qué beneficios reporta el empleo de biocombustibles frente al de combustibles fósiles?
Comparativa en volumen de consumo fósil vs combustible
¿Cuáles son los niveles de demanda de biocombustible? Que permita prever los niveles de inventario, con el fin de lograr abastecer a tiempo y reducir los costos tanto de almacenamiento como de distribución.
¿Podemos detectar anomalías presentes en las transacciones de consumo en cada empresa transportista?
¿Podemos detectar anomalías y/o adulteraciones presentes en la distribución del biocombustible?

## Datos:
Datos propios:
Se ubican en: https://github.com/DiegoFabianTondo/DS20_MainProject/
Se cuenta con los siguientes datasets:
Sitios: Centros Operativos de las empresas de Transporte. Más de 300.
Tanques de almacenamiento: Infraestructura de almacenamiento en los sitios de las empresas de Transporte. Más de 1000.
Bombas o picos de despacho: Infraestructura de despacho en los sitios de las empresas de transporte. Más de 500.
Productos : Productos almacenados en los sitios de las empresas de transporte.
Transacciones: Transacciones de consumo de combustibles, por unidad, por tanque, por pico. 100K-rows/mes.
Historiales: Historial de inventarios de los tanques de los centros operativos de las empresas de Transporte. 2M-rows/mes.
Datos públicos:
Estadística de biodiesel y bioetanol (disponible en: https://datos.gob.ar/dataset/energia-estadisticas-biodiesel-bioetanol)

## Hitos de la mentoría
**Análisis y visualización de datos**
- Determinar las gráficas más acordes para la visualización en función de los tipos de datos que se manejan, y realizar un análisis de los mismos.
- Desarrollo de estadísticas descriptivas pertinentes al objeto de estudio y a los datos disponibles: identificar los tipos de variables, elegir los estadísticos descriptivos más acordes para su análisis, realizar los cálculos pertinentes y el análisis de los resultados obtenidos.
- Desarrollo de estadística descriptiva de consumo y administración de inventarios de combustibles fósiles.
- Realizar agregaciones y gráficos útiles para el transportista en cuanto al uso, eficiencia y anomalías. 

**Análisis exploratorio y curación de datos**
- Entender el dominio del problema y validar los resultados obtenidos
- Exploración de los datos: cantidad de registros, cantidad de características disponibles, tipos de datos, revisión de categorías y valores de cada campo, comprensión de los mismos.
- Limpieza de datos: tratamiento de valores nulos, duplicados, outliers, seleccionar columnas relevantes del dataset, identificación y tratamiento de outliers o valores atípicos.
- Detección de anomalías en las transacciones y distribuciones del combustible, mediante estadística descriptiva.
- Ingeniería de atributos: transformación de los datos,codificación de variables, binning, escalado.
- Descripción de la dispersión y forma de la distribución de los datos.
- Análisis exploratorio de las series temporales, curación sobre los datos recolectados.

**Introducción al aprendizaje automático**
- Extracción de características.
- Determinar los algoritmos más adecuados para abordar los objetivos propuestos.
- Selección de las métricas para la evaluación del modelo.
- Obtener un modelo (“baseline”) para forecasting de consumos.
- Identificar existencia de overfitting y underfitting

**Aprendizaje Supervisado**
- Mejoras del modelo de forecasting de consumos: validación cruzada y evaluación de hiperparámetros.

**Aprendizaje No Supervisado**
- Definir algoritmos para la detección de anomalías tanto en las transacciones con las empresas como en la distribución del combustible.

PRESENTACIÓN: 06/11/2020 – 07/11/2020
