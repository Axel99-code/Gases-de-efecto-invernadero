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

Emisiones_fluorados_1990_2022.csv (33, 15)

año 
unidad_de_medida
hfc_125         
hfc_134a        
hfc_143a        
hfc_152a        
hfc_227ea       
hfc_23          
hfc_245fa       
hfc_32          
hfc_365         
pfc_116_c2f6
pfc_143_cf4 
total       
hfc_236fa       

Emisiones_pib_1990_2022_ip.csv (33, 3)

año
unidad_de_medida  
emisiones_por_producto_interno_bruto

emisiones_sector_1990_2022.csv (33, 8)

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

Hay Algunas Provincias las cuales la emision total fueron negativas, esto se puede traducir en que el balance de una provincia o jurisdicción absorbió más gases de los que emitió en un sector específico durante el año analizado. En la ciencia del cambio climático, esto se conoce como un sumidero de carbono.

Los valores de CO₂ son muchísimo más altos que los de ch4 o n2o. Sin embargo, los otros gases (especialmente el metano) son más potentes para calentar el planeta por cada tonelada emitida, por lo que muchas bases de datos los convierten a una unidad común llamada CO₂e (Dióxido de Carbono Equivalente) para poder compararlos de forma justa.

