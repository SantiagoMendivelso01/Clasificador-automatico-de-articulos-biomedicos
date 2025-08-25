# Clasificador-automatico-de-articulos-biomedicos
Este proyecto desarrolla un clasificador automático de artículos biomédicos a partir del título y el resumen (abstract), asignándolos a uno de los siguientes dominios médicos:
- 🫀 Cardiovascular
- 🧠 Neurological
- 🧬 Oncological
- 🩸 Hepatorenal

La solución está basada en Machine Learning supervisado, utilizando un pipeline de TF-IDF para vectorizar el texto y un Support Vector Machine (SVM) como modelo de clasificación. El SVM fue elegido por su capacidad para manejar datos de alta dimensionalidad y por permitir la aplicación de regularización y penalización de clases, mejorando el rendimiento en escenarios desbalanceados.


[Ir a la aplicación web ❤️](https://v0-medical-text-classifier.vercel.app/)

