# 🤖 Programación con Inteligencia Artificial

Esta guía presenta puntos importantes y una metodología para utilizar la Inteligencia Artificial (IA) de manera efectiva en su proceso de programación.

---

## 📌 Puntos Importantes

* **¡El Humano es Usted!**
    * El proceso de pensar y de crear es del ser humano que escribe el código.
    * Usted es quien posee el dominio de todo el contexto de su código.
    * Utilice la IA como una herramienta para pulir lo que está creando.
* **Sea Bastante Crítico**
    * Analice bien todas las soluciones dadas por la IA antes de implementarlas.
* **La IA Puede Ser el Punto de Partida**
    * A veces, podemos tener un poco de dificultad para iniciar un algoritmo.
    * Por lo tanto, utilice la IA como un medio para comenzar a codificar lo que necesita.
* **¡Vayamos por Partes!**
    * Trabaje con fragmentos de código más pequeños que, si es posible, posean un contexto completo dentro de sí mismos.
    * Esto ayuda a que el análisis de la IA sea mejor y con menos errores.

---

## 🛠️ Metodología

Tenga sentido crítico y analice su código, eligiendo las partes que cree que necesitan mejora. Un buen comienzo es pensar en **cuatro pilares**: **rendimiento (performance)**, **errores**, **seguridad** y **patrones de estilo del lenguaje**.

### 1. Enviar

* Después de elegir el fragmento de código a analizar, envíelo a la IA.
* Recuerde enviar todo y cualquier fragmento de código, lo que ayudará a la IA a comprender el contexto.
* Al enviar el código, puede enviar un texto explicando su funcionamiento y cuál es el resultado esperado.
* *Consejo:* Pida a la IA que solo responda que ha recibido el código y que no tome ninguna acción.

### 2. Analizar

* Pida a la IA que analice un fragmento de código y señale los problemas potenciales, de acuerdo con el enfoque elegido, **sin hacer modificaciones en el código**.
* Lea los problemas potenciales enumerados y verifique si todos tienen sentido.

### 3. Ajustar

* Ajuste el fragmento de código necesario a partir de la explicación de la IA.
* Si la IA le ha respondido con una posible solución, este es el momento de aplicar el código sugerido por la IA a su código.
* Si ve la necesidad, modifique ese código.

### 4. Verificar

* Después de corregir un problema, pida a la IA que **verifique si el mismo ha sido resuelto**.

### 5. Probar

* Después de la solución del problema, **pruebe si la funcionalidad del código permanece igual**.
* Es necesario garantizar que las alteraciones no hayan creado ningún **efecto secundario o nuevos errores**.

---

## 📝 Lista de Prompts

A continuación, una lista de ejemplos de *prompts* para ser utilizados con cualquier IA para ayudar en su programación.

| Número | Categoría | Prompt |
| :---: | :---: | :--- |
| 1 | Debug | "Puedes ayudarme a depurar este mensaje de error de mi programa en [lenguaje]: [mensaje]" |
| 2 | Debug | Describa el comportamiento inesperado que está observando en el código y proporcione cualquier mensaje de error o rastreo de pila para un análisis posterior. |
| 3 | Debug | "Ayúdame a depurar este script en [lenguaje] que procesa una lista de objetos y sugiere posibles correcciones." |
| 4 | Debug | Destaque cualquier mecanismo de manejo de errores en el código y explique cómo están actualmente manejando o fallando en manejar el problema encontrado. |
| 5 | Debug | "Depura el código [lenguaje] proporcionado. Se supone que debe realizar [comportamiento esperado], pero está produciendo [comportamiento actual]." |
| 6 | Debug | "Depura el siguiente código [lenguaje]: Se espera que ejecute [comportamiento esperado], pero en su lugar, está produciendo [comportamiento actual] cuando se le dan las entradas (*inputs*): [ejemplos de input]." |
| 7 | Issues | "¿Podrías encontrar problemas potenciales en este código [lenguaje]:" |
| 8 | Issues | "¿Puedes identificar algún *bug* en este fragmento de código [lenguaje]:" |
| 9 | Issues | "Revisa este *script* en [lenguaje] para verificar si hay algún *bug*." |
| 10 | Issues | "Ayúdame a entender por qué esta función [lenguaje] no está funcionando como se esperaba." |
| 11 | Issues | "¿Cuáles son los problemas potenciales con esta función recursiva [lenguaje]:" |
| 12 | Issues | "Encuentra cualquier problema potencial en este código [lenguaje] que procesa un *array* de *strings*:" |
| 13 | Issues | "¿Puedes identificar el *bug* en esta función [lenguaje] que maneja la conexión a la base de datos:" |
| 14 | Issues | "¿Qué está mal con este método [lenguaje] que se supone que debe analizar un archivo CSV:" |
| 15 | Issues | "Encuentra el error de lógica en esta función [lenguaje] destinada a invertir el *array*, dadas estas entradas (*inputs*): [parámetros de entrada], y se espera que produzca [salida], pero actualmente proporciona [salida incorrecta]." |
| 16 | Issues | "Encuentra *bugs* potenciales en el *script* [lenguaje] que procesa [tipo de input] y genera [tipo de output]:" |
| 17 | Issues | "Identifica el error de lógica en esta función [lenguaje] destinada a verificar la fortaleza de la contraseña con estas entradas (*inputs*): [parámetros de entrada] y salida (*output*) esperada: [salida]" |
| 18 | Performance | "¿Puedes encontrar algún problema de rendimiento en este código [lenguaje]:" |
| 19 | Performance | "¿Existen fugas de memoria (*memory leaks*) en este código [lenguaje]:" |
| 20 | Performance | "Revisa la siguiente función [lenguaje]. Por favor, identifica cualquier *bug* potencial, problema de rendimiento y no conformidad." |
| 21 | Performance | "Por favor, revisa la función [lenguaje] en busca de fugas de memoria o problemas de rendimiento potenciales al procesar un *Array* de un millón de registros." |
| 22 | Performance | "Encuentra las fugas de memoria en el siguiente código [lenguaje] y sugiere posibles optimizaciones:" |
| 23 | Performance | "Revisa el código [lenguaje] proporcionado en busca de problemas potenciales de escalabilidad:" |
| 24 | Performance | Revisa los algoritmos y estructuras de datos utilizados en el código para asegurar que estén optimizados para el rendimiento. |
| 25 | Review | "Revisa esta función [lenguaje] en busca de errores:" |
| 26 | Review | "¿Puedes revisar esta función [lenguaje] y sugerir áreas para el manejo de errores (*error handling*)" |
| 27 | Review | "Revisa la siguiente función [lenguaje] y proporciona sugerencias para el manejo de errores y posibles cuellos de botella (*bottlenecks*)." |
| 28 | Review | "¿Puedes identificar algún problema potencial con esta definición de clase [lenguaje]:" |
| 29 | Review | "¿Puedes analizar este código [lenguaje] y señalar errores potenciales?" |
| 30 | Review | "Por favor, revisa este código [lenguaje] en cuanto a estilo y mejores prácticas:" |
| 31 | Review | "Por favor, revisa lo siguiente [lenguaje] para verificar si está siguiendo la Guía de Estilo de Google (*Google Style Guide*):" |
| 32 | Review | "Por favor, revisa este código [lenguaje] que debe calcular el factorial dadas las entradas (*inputs*) [variables de entrada] y devolver [salida]:" |
| 33 | Security | "¿Existen vulnerabilidades de seguridad en este código [lenguaje]:" |
| 34 | Security | Identifica vulnerabilidades potenciales en el código y propón estrategias de mitigación. |
| 35 | Security | Analiza el código en busca de cualquier posible *brecha* de seguridad y sugiere maneras de abordarlas. |
| 36 | Security | "Me preocupan los problemas de seguridad en este código [lenguaje]. ¿Cuáles son tus consideraciones?" |
| 37 | Security | Examina el código en busca de posibles riesgos de seguridad y proporciona recomendaciones para mejorar su postura de seguridad. |
| 38 | Security | Inspecciona el código en busca de cualquier vulnerabilidad de seguridad y describe los pasos para remediarlas. |
| 39 | Security | Ayuda a identificar cualquier problema de seguridad potencial en el siguiente código Java relacionado con *cross-site scripting* (XSS). |
| 40 | Security | Examina el código en busca de cualquier debilidad o *brecha* de seguridad y sugiere medidas para fortalecer su postura de seguridad. |
