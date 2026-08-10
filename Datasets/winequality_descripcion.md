Estos conjuntos de datos están disponibles públicamente para investigación. Los detalles se describen en [Cortez et al., 2009].  
Por favor, incluya esta cita si planea usar esta base de datos:

P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis.  
Modeling wine preferences by data mining from physicochemical properties.  
In Decision Support Systems, Elsevier, 47(4):547-553. ISSN: 0167-9236.

Disponible en: [@Elsevier](http://dx.doi.org/10.1016/j.dss.2009.05.016)  
[Pre-press (pdf)](http://www3.dsi.uminho.pt/pcortez/winequality09.pdf)  
[bib](http://www3.dsi.uminho.pt/pcortez/dss09.bib)

**1. Título:** Wine Quality

**2. Fuentes**  
Creado por: Paulo Cortez (Univ. Minho), Antonio Cerdeira, Fernando Almeida, Telmo Matos y Jose Reis (CVRVV) @ 2009

**3. Usos anteriores:**

P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis.  
Modeling wine preferences by data mining from physicochemical properties.  
In Decision Support Systems, Elsevier, 47(4):547-553. ISSN: 0167-9236.

En la referencia anterior, se crearon dos conjuntos de datos utilizando muestras de vino tinto y blanco.  
Las entradas incluyen pruebas objetivas (por ejemplo, valores de pH) y la salida se basa en datos sensoriales  
(mediana de al menos 3 evaluaciones realizadas por expertos en vino). Cada experto calificó la calidad del vino  
entre 0 (muy mala) y 10 (muy excelente). Se aplicaron varios métodos de minería de datos para modelar  
estos conjuntos de datos bajo un enfoque de regresión. El modelo de máquina de vectores de soporte logró los  
mejores resultados. Se calcularon varias métricas: MAD, matriz de confusión para una tolerancia al error fija (T),  
etc. Además, se representaron las importancias relativas de las variables de entrada (medidas mediante un procedimiento  
de análisis de sensibilidad).

**4. Información relevante:**

Los dos conjuntos de datos están relacionados con las variantes tinta y blanca del vino portugués "Vinho Verde".  
Para más detalles, consulte: http://www.vinhoverde.pt/en/ o la referencia [Cortez et al., 2009].  
Debido a problemas de privacidad y logísticos, solo están disponibles las variables fisicoquímicas (entradas) y sensoriales (la salida)  
(por ejemplo, no hay datos sobre tipos de uva, marca de vino, precio de venta, etc.).

Estos conjuntos de datos pueden verse como tareas de clasificación o regresión.  
Las clases están ordenadas y no equilibradas (por ejemplo, hay muchos más vinos normales que  
excelentes o malos). Se podrían usar algoritmos de detección de valores atípicos para detectar los pocos vinos excelentes  
o malos. Además, no estamos seguros de si todas las variables de entrada son relevantes. Por lo tanto,  
podría ser interesante probar métodos de selección de características.

**5. Número de instancias:** vino tinto - 1599; vino blanco - 4898.

**6. Número de atributos:** 11 + atributo de salida

Nota: varios de los atributos pueden estar correlacionados, por lo que tiene sentido aplicar algún tipo de  
selección de características.

**7. Información de los atributos:**

Para más información, lea [Cortez et al., 2009].

Variables de entrada (basadas en pruebas fisicoquímicas):  
1 - acidez fija  
2 - acidez volátil  
3 - ácido cítrico  
4 - azúcar residual  
5 - cloruros  
6 - dióxido de azufre libre  
7 - dióxido de azufre total  
8 - densidad  
9 - pH  
10 - sulfatos  
11 - alcohol  

Variable de salida (basada en datos sensoriales):  
12 - calidad (puntuación entre 0 y 10)

**8. Valores de atributos faltantes:** Ninguno
