1. Título: Pima Indians Diabetes Database

2. Fuentes:
(a) Propietarios originales: National Institute of Diabetes and Digestive and Kidney Diseases
(b) Donante de la base de datos: Vincent Sigillito (vgs@aplcen.apl.jhu.edu)
Research Center, RMI Group Leader
Applied Physics Laboratory
The Johns Hopkins University
Johns Hopkins Road
Laurel, MD 20707
(301) 953-6231
(c) Fecha de recepción: 9 de mayo de 1990

3. Usos anteriores:

    Smith, J. W., Everhart, J. E., Dickson, W. C., Knowler, W. C., y Johannes, R. S. (1988). Using the ADAP learning algorithm to forecast the onset of diabetes mellitus. En Proceedings of the Symposium on Computer Applications and Medical Care (pp. 261–265). IEEE Computer Society Press.

    La variable diagnóstica investigada, de valor binario, indica si el paciente muestra signos de diabetes según los criterios de la Organización Mundial de la Salud (es decir, si la glucosa plasmática dos horas después de una carga fue de al menos 200 mg/dl en cualquier examen de seguimiento o si se detectó durante la atención médica de rutina). La población vive cerca de Phoenix, Arizona, EE. UU.

    Resultados: Su algoritmo ADAP produce una predicción de valor real entre 0 y 1. Esto se transformó en una decisión binaria utilizando un umbral de 0.448. Usando 576 instancias de entrenamiento, la sensibilidad y especificidad de su algoritmo fue del 76% en las 192 instancias restantes.

4. Información relevante:
Se impusieron varias restricciones en la selección de estas instancias a partir de una base de datos más grande. En particular, todas las pacientes aquí son mujeres de al menos 21 años de herencia Pima. ADAP es una rutina de aprendizaje adaptativo que genera y ejecuta análogos digitales de dispositivos tipo perceptrón. Es un algoritmo único; consulte el artículo para más detalles.

5. Número de instancias: 768

6. Número de atributos: 8 más la clase

7. Por cada atributo: (todos son valores numéricos)

    Número de veces embarazada

    Concentración de glucosa plasmática a las 2 horas en una prueba de tolerancia oral a la glucosa

    Presión arterial diastólica (mm Hg)

    Grosor del pliegue cutáneo del tríceps (mm)

    Insulina sérica a las 2 horas (mu U/ml)

    Índice de masa corporal (peso en kg / (altura en m)^2)

    Función de pedigrí de diabetes

    Edad (años)

    Variable de clase (0 o 1)

8. Valores de atributos faltantes: Sí

9. Distribución de la clase: (el valor de clase 1 se interpreta como "resultado positivo para diabetes")

| Valor de clase | Número de instancias |
|----------------|----------------------|
| 0              | 500                  |
| 1              | 268                  |





