En el contexto de las mejores prácticas para un buen "prompt", **usar delimitadores** se refiere a la práctica de **ayudar al modelo de inteligencia artificial a comprender las diferentes partes de su instrucción** [1].

Los delimitadores son caracteres o símbolos específicos que se utilizan para **separar distintas secciones de su prompt** [1]. Esto es importante porque:

*   **Conduce a mejores respuestas** [1]. Al demarcar claramente cada parte, el modelo puede procesar la información de manera más organizada y generar una salida más precisa y relevante.
*   **Ofrece protección contra las "inyecciones de prompt"** [1]. Esto significa que ayuda a prevenir que usuarios malintencionados inserten instrucciones no deseadas que puedan manipular el comportamiento del modelo.

Ejemplo:
	En el contexto de las mejores prácticas para un buen "prompt", **usar delimitadores** se refiere a la práctica de ayudar al modelo de inteligencia artificial a comprender las diferentes partes de su instrucción [1].

Los delimitadores son caracteres o símbolos específicos que se utilizan para **separar distintas secciones de su prompt** [1]. Esto es importante porque:
*   Conduce a **mejores respuestas** [1].
*   Ofrece **protección contra las "inyecciones de prompt"** [1].

Aquí tiene un ejemplo del uso de delimitadores en un prompt, utilizando `< >` para demarcar diferentes bloques de información, lo que ayuda al LLM a completar sus oraciones o continuar una conversación desde la última parte de sus instrucciones [2]:

"Aquí está mi currículum:
**< currículum >**
Aquí está una descripción del puesto:
**< descripción del puesto >**
Escríbeme una carta de presentación basada en mi experiencia y la descripción del puesto." [3]

Si se reorganizara la información contextual o se pusieran las instrucciones al principio del prompt, se podría aumentar la posibilidad de que el LLM ignorara las instrucciones o adaptara la carta de presentación a algo no relacionado con la descripción del puesto [3].