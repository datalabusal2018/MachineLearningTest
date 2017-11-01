# MachineLearningTest

El grupo [DatalabUsal](http://medialab.usal.es/datalab) 2018 explorará distintas técnicas Machine Learning con una base de datos de pacientes de corazón.

## Objetivo

Cada participante/grupo escogera una técnica de clasificación/regresión para ajustar un modelo con los datos train.csv y lo aplicará sobre los datos test.csv.

El participante/grupo explicará al resto de componentes de qué se trata la técnica de Machine Learning así como el ejemplo aplicado a la base de datos.

Cada participante obtendrá un certificado acreditando su participación como el haber dado una charla sobre la técnica en concreto.

Aquel participante/grupo que obtenga el mejor ajuste se llevará una mención honorífica en su certificado.

## Información

* [Angiografía](https://www.wikiwand.com/es/Angiograf%C3%ADa)
* [Vídeo explicativo angiografa](https://www.youtube.com/watch?v=EkAA9lRGgl4)
* [Angina de pecho](https://www.wikiwand.com/es/Angina_de_pecho)

## Características de la base de datos

1. (age) edad en años
2. (sex) sexo (1 = masculino; 0 = femenino)
3. (cp) dolor de pecho
    * Valor 1: angina típica
    * Valor 2: angina atípica
    * Valor 3: dolor no relacionado con angina
    * Valor 4: asintomático
4. (trestbps) presión sanguínea en el momento de ingresar (mm Hg momento de admisión)
5. (chol) colesterol serum (mg/dl)
6. (fbs) (nivel de azúcar en ayunas > 120 mg/dl)  (1 = verdadero; 0 = falso) 
7. (restecg) resultados del electrocardiograma
    * Valor 0: normal
    * Valor 1: onda ST-T anormal (inversiones de la onda T y/o elevación o depresión ST de > 0.05 mV)
    * Valor 2: hipertropia probable o definitiva del ventrículo izquierdo (criterio Estes)
8. (thalach) frecuencia cardíaca máxima alcanzada
9. (exang) ejercicio induce angina (1 = sí; 0 = no)
10. (oldpeak) depresión ST inducida por ejercicio relativo a reposo
11. (slope) pendiente del segmento ST (pico de ejercicio)
    * Value 1: pendiente positiva
    * Value 2: sin pendiente
    * Value 3: pendiente negativa
12. (ca) número de vasos principales (0-3) coloreados por fluoroscopia       
13. (thal) 3 = normal; 6 = defecto fijo; 7 = defecto reversible
14. (num) diagnosis enfermedad corazón (estado post-angiografía)
    * Valor 0: < 50% extrechamiento del diámetro
    * Valor 1: > 50% extrechamiento del diámetro
		
