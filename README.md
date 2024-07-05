# Ejercicios del curso de Procesamiento de Lenguaje Natural

En este repositorio se encontrarán los archivos con los ejecicios resultos del curso de Procesamiento de Lenguaje Natural.

Adicionalmente, estos archivos fueron trabajados desde Google Colab, por lo que se puede acceder a ellos directamente desde colab con los links abajo indicados. Estos links permitirán ver los resultados e imágenes almacenados en Colab.

## Desafío 1
Se experimenta con vectorización de documentos en base a conteo de palabras y modelo de clasificación Naïve Bayes con el dataset 20 newsgroups. Se usan vectores para analizar la similaridad de los documentos.
Adicionalmente, se realiza similaridad de palabras en base al conteo de apariciones en documentos con clases definidas.

## Desafío 2
Entrenamos embeddings de palabras en base al libro "Orgullo y Prejuicio" de Jane Austen.
![image](https://github.com/JossySoo/natural_language_processing_excercises/assets/67722266/58becbfd-9462-477a-a6dc-c815469ccf51)
![image](https://github.com/JossySoo/natural_language_processing_excercises/assets/67722266/7633c20c-655f-4057-a909-2601dcf82246)

Para poder visualizar los gráficos en baja dimensionalidad, abrir el archivo en colab con el siguiente link:

https://colab.research.google.com/drive/1oosYmiGFOOYgDvFUXS6IxpTHJHegy2yO?usp=sharing

## Desafío 3

Se crean modelos que predicen la siguiente palabra en una oración y pueden generar secuencias usando como corpus de entrenamiento el libro "Orgullo y Prejuicio".

![image](https://github.com/JossySoo/natural_language_processing_excercises/assets/67722266/aa319adc-9269-4894-a65d-c8a59c07f389)


Modelo en base a palabras:

https://colab.research.google.com/drive/1UUsYZ8J8eWZR8cNYGV4s-iE2x7RdVE3G?usp=sharing

Modelo en base a caracteres:

https://colab.research.google.com/drive/1P4alTRgV3JaoSUP2JmQeoOZ57f54fzZ6?usp=sharing

## Desafío 4

Se realizó un bot que responde preguntas básicas en inglés utilizando los embeddings de fasttext 300 y una arquitectura encoder-decoder.

![image](https://github.com/JossySoo/natural_language_processing_excercises/assets/67722266/21b9ad04-f4ad-4f3f-b632-7b6f17275cc3)


https://colab.research.google.com/drive/1Ipowf4kX6qgCNR1K1a-STQ_SB6z4R28I?usp=sharing

## Desafío 5

Se realizó un modelo de sentiment analysis de comentarios de un App, usando como base el modelo BERT. Se lograron buenos resultados con el modelo de 5 clases de BERT + 2 capas densas con sus respectivos dropouts.
![image](https://github.com/JossySoo/natural_language_processing_excercises/assets/67722266/2dfe9456-523c-477c-820a-e24d1c88b184)


Modelo con 3 variables:

https://colab.research.google.com/drive/1APRPP0XUd6DCn981LQczzGokvr7NpiLX?usp=sharing

Modelo con 5 variables:

https://colab.research.google.com/drive/1S2ViBef6XkoyX-7pI-Dg8uW1fTOT9Txc?usp=sharing

Modelo con 5 variables y con capa densa adicional:

https://colab.research.google.com/drive/1JyfQas_SVxvpHEqO2vGBQWjTV_M7JwuH?usp=sharing
