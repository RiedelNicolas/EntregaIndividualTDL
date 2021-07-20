###### Nicolas Riedel, 102130

##### Caso de estudio sobre Kotlin 


### ¿Cuáles son las razones que llevan a tantas aplicaciones a migrar desde Java a Kotlin?

Desde que Kotlin fue lanzado por JetBrains en 2016 no ha dejado de crecer en popularidad, esto (entre muchas otras cosas) fue lo que llevó  a Google en 2019 a volver el desarrollo en Android **Kotlin-first**. Obviamente esto lo que hizo fue incrementar aún más su popularidad.

De la mano de esto, un incontable número  de aplicaciones Android decidieron migrar desde su código nativo en Java hacia Kotlin.
**¿Qué las llevo a hacer esto?** **¿Qué ventajas trae Kotlin frente a Java?** Vamos a intentar encontrar una respuesta a estas preguntas.
##### ¿Qué ventajas trae Kotlin frente a Java?
Primero vamos a intentar responder esto, que ventajas trae Kotlin.
* Kotlin es un lenguaje con una sintaxis mucho más  simple y concisa, reduciendo las líneas de código  en aproximadamente un 40%. Esto trae como ventaja un código  mucho más claro y hace que cualquier error sea mucho más fácil de encontrar.
* A diferencia de Java, los arreglos en Kotlin son invariantes. Lo que nos protege de distintos errores que pueden ocurrir en tiempo de ejecución.
* Los templates en Kotlin son mucho más  seguros que en Java.
* Kotlin no chequea el manejo de **exceptions** en tiempo de compilación, esto trae tanto ventajas como desventajas (dejo una [lectura](https://radio-weblogs.com/0122027/stories/2003/04/01/JavasCheckedExceptionsWereAMistake.html) sobre el tema).
* A diferencia de Java, Kotlin implementa [null safety](https://kotlinlang.org/docs/null-safety.html) y esto sumado a un código  más conciso hace que Kotlin sea mucho más  seguro.
* Expresiones Lambda.
* [Extension functions](https://kotlinlang.org/docs/extensions.html) lo que nos brinda un código  mucho más flexible y dinámico.
* SmartCast y verificaciones de tipo más  completas.
* Diferencia entre variables inmutables y mutables, lo que genera un código  mucho menos propenso a errores.
* Constructores primarios con una sintaxis mucho más  simple, lo que suma a tener menos código .
* Patrones como **Singleton** ya incorporados.
* Declaración  de rangos y progresiones  numéricas.
* Sobrecarga de operadores.
* Interfaces diferentes para colecciones de solo lectura y para colecciones mutables.
* Corrutinas (de gran utilidad para programación concurrente).
* Último pero no por eso menos importante : Kotlin tiene prioridad en el desarrollo del framework asociado a Android.

##### ¿Qué aplicaciones decidieron dar este paso?

Entre las más conocidas se pueden encontrar a :

1. Uber
2. Pinterest
3. Trello
4. Kickstarter
5. Evernote
6. Shadowsocks
7. Coursera
8. Postmates
9. Slack
10. Tinder
11. Netflix
12. Airbnb

Entre muchas otras!

Algo que se puede ver en común es que todas estas aplicaciones son de uso masivo y con un gran respaldo económico.
##### Sumando estas dos cosas, ¿Cuáles pueden ser las razones que lleven a tantas aplicaciones a migrar hacia Kotlin?

* Kotlin es una alternativa más  robusta que Java, lo que en proyectos grandes y masivos es una gran ventaja.
* Por otro lado Google prioriza Kotlin en todo lo relacionado a Android, lo que nos da un indicio de que en los próximos años podría llegar a descontinuar el soporte a Java (esto sumado a que tiene una disputa legal con Oracle). Entonces quienes apunten a que su proyecto perdure en el tiempo deberían ir pasándose a Kotlin.
* Cualquier dispositivo que corra Java puede perfectamente correr Kotlin, ya que ambos son compilados a bytecode de JVM.
* Android Studio (El IDE más utilizado en el desarrollo de Android) tiene una herramienta para automáticamente transformar código  de Java en Kotlin (este no es tan eficaz ni prolijo como el código  hecho por una persona pero sirve perfectamente).

Todo esto sumado a que Kotlin es completamente interoperable con Java hace que el proyecto pueda ir siendo transformado en partes o simplemente ir agregando los módulos nuevos en Kotlin, lo que es otra gran ventaja. 

##### Conclusión
Se puede decir que muchas de estas aplicaciones decidieron dar el paso, ya que al ser empresas multimillonarias donde gran parte de sus ingresos depende de las aplicaciones móviles quieren apuntar a que las mismas sean lo más robustas posibles y las herramientas con las que estén desarrolladas tengan soporte por el mayor tiempo posible.

###### Fuentes utilizadas :
1. https://www.appventurez.com/blog/apps-switched-from-java-to-kotlin/
2. https://levelup.gitconnected.com/why-you-should-migrate-your-apps-to-kotlin-if-you-havent-already-30fec1b05be9
3. https://www.spec-india.com/blog/top-apps-built-with-kotlin
4. https://kotlinlang.org/docs/comparison-to-java.html
5. https://radio-weblogs.com/0122027/stories/2003/04/01/JavasCheckedExceptionsWereAMistake.html