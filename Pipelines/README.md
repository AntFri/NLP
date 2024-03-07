# Pipelines

### **Qué son los pipelines en spacy?**
Es una secuencia de trabajos a la hora de utilizar Spacy (NLP), se puede elegir que tarea y en cual orden lo realiza, por ejemplo tokenizar, analisis sintactico, lematizar, etc

### **¿qué diferencias hay entre usar?**
En el **spacy.blank("es")** nos crea una instacia bazia en el cual solo hay un tokenizador y podemos personalizar, a contrario en el **spacy.load("es_core_news_sm")** es un modelo completo en espanyol para poder processar directamente.

### **enumera algunos de los metodos mas importantes de los pipelines**
- doc.ents: nos sirve para conseguir la entidad del documento
- token.ent_type: sirve para sacar el el tipo de entidad es la palabra tokenizada
- token.tag: para sacar la etiqueta de la palabra 

### **¿qué podemos hacer con pipelines que no se pueda hacer solamente con tokens?**
- Podemos personalizarlo como lo queremos para con diferentes componentes
- Son mas rapidos en analizar un document/texto porque no tokenizan todo primero y despues trabajan sobre eso sino lo hacen uno detras del otro.
