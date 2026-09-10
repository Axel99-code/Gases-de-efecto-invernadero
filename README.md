EMISIONES DE GASES DE EFECTO INVERNADERO (GEI)

Objetivos previos al objetivo principal: comprension de como fue progresando el impacto que tuvo los GEI en las provincias de Argentina
¿Que sector es el que genera mas GEI? ¿Que subsector genera mas GEI? ¿Que Gas es el que mas se produce?

Fuente de datos: DB pública de https://ciam.ambiente.gob.ar/ este muestra la evolución del consumo de GEI en el pais
este contiene datos de un periodo de 1990-2022

Metodologia: Extracción: Descarga de base de datos pública,  Limpieza: Detección de valores nulos o no válidos, descarte de los mismos. Rectificación de tipo de dato de cada base de dato recolectada. EDA: Análisis de los datos. Comparaciones entre categorias, media de búsqueda de Google. Visualización: Creación de gráficos representativos de cada análisis via Matplot

Consumo de hidroclorofluorocarbonos (23, 2)

año
consumo_hcfc_toneladas

Emisiones anuales desagregadas por provincia_2010_2022 (43682, 7)

año
provincia
sector
subsector
tipo_de_gas
valor_toneladas_gas  
valor_toneladas_co2e

Emisiones anuales_1990_2022.csv (33, 3)

año
unidad
cantidad

Emisiones_datos_totales_1990_2022.csv (7778, 8)

año
sector
actividad
subactividad
categoria
id_ipcc
tipo_de_gas
valor_en_toneladas_de_co2e

año
energia
procesos_industriales_y_uso_de_productos
agricultura_y_ganaderia
usos_de_la_tierra_cambios_de_uso_de_la_tierra_y_silvicultura
residuos
total
unidad_de_medida

emisiones_sector_tipo_gas_1990_2022.csv (165, 8)

sector
año  
unidad_de_medida
total
co2
ch4
n2o
otros_gei

emisiones_subsector_no_ipcc_1990_2022.csv (33, 16)

año
agricultura
aguas_residuales
cambio_de_uso_de_suelos_y_silvicultura
combustibles_industrias
combustibles_otros_sectores
combustibles_residencial
emisiones_fugitivas
fabricacion_de_combustibles
ganaderia
generacion_de_electricidad
procesos_industriales
residuos_solidos_urbanos
transporte
total
unidad_de_medida

emisiones_tipo_gas_1990_2022_ic.csv (33, 7)

año
total
unidad_de_medida
co2
ch4
n2o
otros_gei

Principales hallazgos

Las Provincias de Buenos Aires Salta Santiago del Estereo , CABA y Otras Jurisdicciones son los que mas emiten  esto nos dice que pueden ser los que mas concentracion de actividad tienen a nivel actividad de poblacion y/o industrial.
Mientras que por el otro lado hay provincias las cuales la emision total fueron negativas, esto se puede traducir en que el balance de una provincia o jurisdicción absorbió más gases de los que emitió en un sector específico durante el año analizado. En la ciencia del cambio climático, esto se conoce como un sumidero de carbono.

Los valores de CO₂ son muchísimo más altos que los de ch4 o n2o. Sin embargo, los otros gases (especialmente el metano) son más potentes para calentar el planeta por cada tonelada emitida, por lo que muchas bases de datos los convierten a una unidad común llamada CO₂e (Dióxido de Carbono Equivalente) para poder compararlos de forma justa.

Los sectores que mas emiten son los de suelos ,ganaderias y transportes esto es porque como son algo que generalmente son mas utilizados en transportes y los que mas son explotados (En terminos del territorio y siendo un pais de ganaderia)

Conclusiones/Recomendaciones:

Reduccion de gases dañinos (ch4, n2o):
En sistemas donde los animales están confinados (tambos o feedlots), el estiércol acumulado se deriva a biodigestores cerrados. En lugar de liberarse a la atmósfera, el metano se captura y se utiliza como biogás para generar electricidad o calor en el propio campo, transformando un residuo contaminante en energía limpia y biofertilizante.

Agricultura de precisión y rotaciones biológicas
Sensores y aplicación dirigida: El uso de drones, imágenes satelitales y banderilleros satelitales permite fertilizar de forma variable, aplicando más nutrientes solo en las zonas del lote que lo necesitan y dejando en cero las áreas ya ricas en nutrientes.

Manejo de pastizales y captura de carbono (Sumideros)
La ganadería extensiva, posee una ventaja única frente a otras industrias: gestiona millones de hectáreas de biomasa vegetal y suelo. Si se pasa de un manejo tradicional (pastoreo continuo) a un manejo planificado o regenerativo, los pastizales pampeanos y de otras regiones argentinas pueden capturar más dióxido de carbono (CO₂) de la atmósfera del que los animales emiten, transformando los campos en sumideros netos de carbono.

Gestión de estiércol y residuos