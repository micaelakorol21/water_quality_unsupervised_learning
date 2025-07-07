# Integrantes: Korol Micaela, Lescano Guadalupe
# 💧 Tema elegido: Clasificación de Agua Potable
## Predicción de la potabilidad del agua según parámetros físico-químicos establecidos por el Código Alimentario Argentino.

---

### 🧾 Descripción del Proyecto:

**Este proyecto tiene como objetivo desarrollar un modelo de machine learning capaz de predecir si una muestra de agua es potable o no potable, utilizando algoritmos de aprendizaje no supervisado.**
Se emplean parámetros físico-químicos como pH, turbidez, color, olor, plomo, cobre, flúor, cloruro, entre otros, que son comparados con los límites establecidos por el Código Alimentario Argentino (CAA).

Aunque el dataset cuenta con una columna llamada "Objetivo", que indica si el agua es potable o no, en este trabajo se busca explorar **técnicas de aprendizaje no supervisado**, como el clustering, para analizar si los datos permiten identificar agrupamientos consistentes que reflejen la calidad del agua sin usar directamente esa etiqueta.**  


Este modelo puede servir como una herramienta de apoyo para el monitoreo de la calidad del agua, especialmente en zonas donde los análisis de laboratorio son costosos o inaccesibles.

**Columnas más importantes del dataset:**  
*['pH', 'Hierro', 'Nitrato', 'Cloruro', 'Plomo', 'Zinc', 'Color', 'Turbidez', 'Flúor', 'Cobre', 'Olor', 'Sulfato', 'Conductividad', 'Cloro', 'Manganeso', 'Sólidos Disueltos Totales', ..., 'Objetivo']*

---

### 🧪 Parámetros regulados por el Código Alimentario Argentino (CAA)  
🔗 [Código Alimentario Argentino - Capítulo 12: Agua potable](https://alimentosargentinos.magyp.gob.ar/contenido/marco/CAA/Capitulo_12.php)

---

### 🚰 Dataset utilizado  
🔗 [Water_quality.csv (GitHub)](https://media.githubusercontent.com/media/micaelakorol21/dataset_water_quality/refs/heads/main/Water_quality.csv)
