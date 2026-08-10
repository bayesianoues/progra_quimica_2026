## Conjunto de datos de derrames de petróleo

El conjunto de datos de derrames de petróleo es un referente estándar en el aprendizaje automático, utilizado para clasificación binaria. El objetivo es predecir si una determinada porción de una imagen satelital contiene un derrame de petróleo —como resultado de vertidos ilegales o accidentales en el mar— a partir de un vector de características que describe el contenido visual de dicha porción.

El conjunto de datos contiene 937 casos. Cada caso incluye 48 características numéricas derivadas de técnicas de visión por computadora, un identificador de la porción y una etiqueta de clase. El caso normal (sin derrame) se etiqueta como 0, mientras que la presencia de un derrame de petróleo se etiqueta como 1. El conjunto de datos está muy desequilibrado: 896 casos corresponden a «sin derrame» y solo 41 casos a «con derrame».

Las características varían significativamente en escala: algunas alcanzan valores de miles (por ejemplo, la segunda columna), mientras que otras son fraccionarias. Varias columnas contienen muy pocos valores únicos, lo que hace que este conjunto sea especialmente útil para practicar la preparación de datos.

Al revisar el archivo de datos oil_spill.csv, tenga en cuenta que la primera columna contiene números enteros que identifican la porción de imagen. Las 48 columnas restantes son características numéricas de valores reales, cada una con diferentes rangos y distribuciones.
