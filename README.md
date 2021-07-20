###### Nicolas Riedel, 102130
##### Caso de estudio de Kotlin

### ¿Cuáles son las razones que llevan a tantas aplicaciones a migrar de Java a Kotlin?

Kotlin fue lanzado por JetBrains en 2016, y desde entonces no ha dejado de crecer en popularidad. Ésta fue la razón principal por la cual en 2019 Google decidió que el desarrollo en Android se volviese **Kotlin-first**. Obviamente, su prestigio no hizo más que aumentar.

A su vez, un incontable número de aplicaciones Android decidieron migrar su código nativo en Java a Kotlin. **¿Qué las llevó a hacer esto?** **¿Qué ventajas trae Kotlin frente a Java?** En este texto, se buscarán las respuestas a estas preguntas.

##### Ventajas de Kotlin
Comencemos enumerando los principales beneficios que conlleva la utilización de Kotlin por sobre la de Java.
* Kotlin es un lenguaje con una sintaxis mucho más simple y concisa, reduciendo las líneas de código en aproximadamente un 40%. Esto resulta en código mucho más claro y modular, sin mencionar que los errores son mucho más fáciles de encontrar.
* A diferencia de Java, los arreglos en Kotlin son invariantes, lo que nos protege de distintos errores que pueden ocurrir en tiempo de ejecución.
* Kotlin no chequea el manejo de **exceptions** en tiempo de compilación. Esta característica implica tanto ventajas como desventajas. Para más información, se recomienda este [artículo](https://radio-weblogs.com/0122027/stories/2003/04/01/JavasCheckedExceptionsWereAMistake.html).
* Los templates en Kotlin son mucho más estrictos y complejos a comparación de los de Java, lo cual conduce a menos errores.
* A diferencia de Java, Kotlin implementa [null safety](https://kotlinlang.org/docs/null-safety.html), que en conjunción con un código más conciso, se llega a que Kotlin es mucho más seguro.
* Kotlin soporta expresiones Lambda, a diferencia de Java.
* Kotlin implementa [Extension functions](https://kotlinlang.org/docs/extensions.html), que nos brinda un código mucho más flexible y dinámico.
* SmartCast y verificaciones de tipo más completas.
* Diferencia entre variables inmutables y mutables, lo que genera en consecuencia un código mucho menos propenso a errores y más robusto.
* Constructores primarios con una sintaxis mucho más simple.
* Patrones como **Singleton** ya incorporados.
* Declaración  de rangos y progresiones numéricas.
* Sobrecarga de operadores.
* Diferentes interfaces para colecciones de solo lectura y para colecciones mutables.
* Corrutinas (de gran utilidad para programación concurrente).
* Kotlin tiene prioridad en el desarrollo del framework asociado a Android.

##### ¿Qué aplicaciones decidieron dar este paso?

Entre las compañías más célebres, se encuentran las siguientes:

1. Netflix
2. Airbnb
3. Slack
4. Tinder
5. Uber
6. Pinterest
7. Trello
8. Kickstarter
9. Evernote
10. Shadowsocks
11. Coursera
12. Postmates

Una característica en común entre todos los ejemplos mencionados es que todas estas aplicaciones son de uso masivo y con un gran respaldo económico.

##### Considerando estos aspectos, ¿vale la pena migrar de Java a Kotlin?

En resumidas cuentas, sí. Kotlin no sólo es un lenguaje con muchas ventajas frente a Java, que se mencionaron en secciones anteriores; sino que además fue creado específicamente para que la transición de Java a Kotlin fuese lo más fluida y sin complicaciones posible. Android Studio (El IDE más utilizado en el desarrollo de Android) tiene una herramienta para automáticamente transformar código de Java a Kotlin. Cabe destacar que no es el camino que produce el código más eficiente ni prolijo, mas es una opción que funciona perfectamente.

Kotlin es una alternativa más robusta que Java, lo que en proyectos grandes y masivos es una gran ventaja. También es perfectamente compatible con cualquier dispositivo que pueda correr código en Java, ya que ambos lenguajes son compilados a bytecode de JVM. Todo esto sumado a que Kotlin es completamente interoperable con Java hace que el proyecto pueda ir siendo transformado en partes o simplemente ir agregando los módulos nuevos en Kotlin, por lo cual la transición de un lenguaje a otro es incluso más accesible.

A su vez, es imprescindible destacar que Google prioriza Kotlin en todo lo relacionado a Android. Esto, sumado a que existe una disputa legal entre Google y Oracle, nos da un indicio de que en los próximos años podría llegar a descontinuar el soporte de Java. Está claro que quienes apunten a que su proyecto perdure en el tiempo, deberían pasarse a Kotlin cuanto antes.

##### Entonces, ¿por qué las aplicaciones migran de Java a Kotlin?
La respuesta sencilla es que las aplicaciones migran de Java a Kotlin porque es la opción más conveniente. El código producido es más robusto y fue más sencillo de programar, lo que se traduce en menos errores y menos costos. El claro apoyo de Google por el lenguaje no es tomado a la ligera. El sello de aprobación de esta célebre compañía provoca seguridad en las empresas que pretenden que sus herramientas y aplicaciones tengan soporte por el mayor tiempo posible.

En cualquier caso, está claro que las empresas que tienen el capital y los recursos para hacerlo, preferieren cada vez más migrar sus aplicaciones a Kotlin. Lo cual, basándonos en toda la información aquí presentada y en la experiencia de nuestro grupo (al haber programado nuestro trabajo en Kotlin) parece la opción indicada.

###### Fuentes utilizadas :
1. https://www.appventurez.com/blog/apps-switched-from-java-to-kotlin/
2. https://levelup.gitconnected.com/why-you-should-migrate-your-apps-to-kotlin-if-you-havent-already-30fec1b05be9
3. https://www.spec-india.com/blog/top-apps-built-with-kotlin
4. https://kotlinlang.org/docs/comparison-to-java.html
5. https://radio-weblogs.com/0122027/stories/2003/04/01/JavasCheckedExceptionsWereAMistake.html