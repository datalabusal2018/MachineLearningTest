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
    * Valor 0: < 50% estrechamiento del diámetro
    * Valor >=1: > 50% estrechamiento del diámetro
    
**¡Ojo!** num está categorizado de 0-4 según el grado de estrechamiento 0 (no enfermo) 1-2-3-4 (enfermo)
La idea es clasificar enfermo/no enfermo. Sin embargo, si tenéis tiempo podéis clasificar los 5 grupos.
		
## Envío de soluciones

Cada participante deberá crear una carpeta con el nombre del algoritmo que haya usado para ajustar el modelo.

En la carpeta existirán tres archivos:

1. Jupyter notebook explicando cómo ha desarrollado el modelo.
2. Archivo test con las soluciones.

Ejemplo: Si has usado el modelo ``Modelo_ejemplo`` deberás crear una carpeta con el mismo nombre. En la misma existirá un Jupyter notebook (el nombre del mismo tiene que coincidir con el modelo) y por último un archivo test.csv igual que el que se adjunta en ``data`` añadiendo una columna ``num`` con los resultados (1/0 únicamente) y una columna ``prob`` con la probabilidad de que esté enfermo el paciente.

Una vez creada la carpeta y habiendo introducido los elementos explicados anteriormente. Procede a hacer ``merge`` de tu rama.

## Resultados

REGRESIÓN LOGÍSTICA
accuracy_score > 0.79487179487179482
True Negatives > 14
True Positives > 17
False Negatives > 7
False Positives > 1
Log_loss > 0.638

SVM
accuracy_score > 0.71794871794871795
True Negatives > 13
True Positives > 15
False Negatives > 9
False Positives > 2
Log_loss > 1.405
