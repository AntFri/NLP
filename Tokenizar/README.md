# Tokenizar

### **¿Que significa tokenizar?**
Tokenizar es una funcion de Spacy que nos permite separar textos o oraciones en palabras, conservando su significado, por ejemplo si es un tipo de moneda no separa el numero del signo sino lo junta. 
### **enumera algunos métodos interesantes de la librería spacy**
algunos metodo interesantes son:
- .is_num: Para saber si es un valor numeroco o no.
- .is_stop: para saber si la palabra es conectores o de parar, eso pueden se preposiciones, de, des de, etc

### **¿qué tipo de problemas podemos resolver al tokenizar un documento?**
- Podemos eliminar palabras innecesarias
- Entender el significado del texto con otras technicas
- COn un modelo que esta entrenado sobre noticias falsas o correos falso se puede filtrar los, no solo se utiliza tokenizar pero tambien

### **¿Qué ventajas presenta tokenizar frente a utilizar expresiones regulares?**
- Esta seperado en cada palabra y nos deja trabajar mas facil con eso
- Se puede reducir la cantidad de contenido eliminando palabras de conector
- se puede lematizar cada palabra y asi entender lo que significan palabra por palabra.
