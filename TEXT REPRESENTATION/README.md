# TEXT REPRESENTATION

### **en qué consiste BOW, bag of words, que inconvenientes tiene**
Es una forma de convertir texto en vectores, tiene el incoveniente que es muy grande el vector por que contiene todo el vocabulario de esa lengua.
### **en qué consisten la técnica de Bag of n-grams, cuales son sus desventajas**
Es tambine una tecnica para convertir texto a vectores pero se puede definir en que tamanyo lo genera, y va cojiendo de dos en dos or tres en tres las palabras conservando el significado o la similaridad.

Desventaja es que cuesta mucho applicarlo a un documento entero y por eso no sirve para grandes cantidades de texto.
### **en qué consiste TF-IDF, ¿por qué es es mejor que el método anterior?**
Nos permite evaluar la relevancia de las palabras, atravez de una formula que tiene el TF-IDF, en un texto dando le mas valor al texto donde palabras aparece menos veces y asi puede identificar sobre que va el texto y comparando los para saber si tienen similtud.

Eso es mejor a comparacion de el Bag of n-grams porque no tenemos un vocabulario entero y en el TF-IDF solo tenemos las palabras utilizadas en el texto y podemos realizar calculos vectoriales con ellos para saber si hay relacion entre texto y texto o no.
