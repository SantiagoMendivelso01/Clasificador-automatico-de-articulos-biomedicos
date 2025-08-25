# Clasificador-automatico-de-articulos-biomedicos
Este proyecto desarrolla un clasificador automático de artículos biomédicos a partir del título y el resumen (abstract), asignándolos a uno de los siguientes dominios médicos:
- 🫀 Cardiovascular
- 🧠 Neurological
- 🧬 Oncological
- 🩸 Hepatorenal

La solución está basada en Machine Learning supervisado, utilizando un pipeline de TF-IDF para vectorizar el texto y un Support Vector Machine (SVM) como modelo de clasificación. El SVM fue elegido por su capacidad para manejar datos de alta dimensionalidad y por permitir la aplicación de regularización y penalización de clases, mejorando el rendimiento en escenarios desbalanceados.

[Ir a la aplicación web ❤️](https://v0-medical-text-classifier.vercel.app/)



# Manual de Uso

## 1. Subida de CSV
- Sube un archivo CSV con las columnas: **title**, **abstract**, y opcionalmente **group**  
- El formato debe ser: `title;abstract;group`  
- Haz clic en **"Procesar Predicciones"** para clasificar todos los textos automáticamente  

## 2. Predicción Manual
- Ingresa el **título** y **resumen** del texto biomédico que deseas clasificar  
- Haz clic en **"Clasificar Texto"** para obtener la predicción instantánea  
- Los resultados incluyen la **categoría predicha** y el **nivel de confianza**  

## 3. Categorías de Clasificación
El sistema clasifica textos en las siguientes categorías médicas:

- **Neurological**: Textos relacionados con neurología y sistema nervioso  
- **Cardiovascular**: Textos sobre cardiología y sistema cardiovascular  
- **Oncological**: Textos relacionados con oncología y cáncer  
- **Hepatorenal**: Textos sobre hígado y riñones  

## 4. Dashboard de Resultados
- Visualiza estadísticas de **precisión** y **distribución de categorías**  
- Filtra resultados por **categoría** o **fuente** (CSV vs Manual)  
- Exporta los resultados en formato **CSV** para análisis posterior  
- Las predicciones correctas se marcan en **verde**, las incorrectas en **rojo**  

---

💡 **Consejos**  
- Para mejores resultados, asegúrate de que los textos estén en **Inglés**  
- Los **títulos y resúmenes más descriptivos** obtienen clasificaciones más precisas  

