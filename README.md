# Segmentacion_covid

# Objetivo 

Identificar patologías en tomografías pulmonares asociadas al COVID por medio de machine learning.


La idea de este proyecto consiste en tener 2 distintas formas de extraer las caracteristicas de las tomografías pulmonares y a cada tecnica probarla con 3 modelos:

1. Naive Bayes
2. SVM
3. Red Neuronal

Clasificando pixel por pixel a que clase pertenece. Siendo las clases:
* Vidrio esmerilado la clase 1
* Consolidacion la clase 2
* Efisema pleural la 3
* La clase 0 son los pixeles que no presentan ninguna irregularidad

Las imagenes provienen de la página web: http://medicalsegmentation.com/covid19/

