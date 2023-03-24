
https://github.com/jamesleeat/TeachYourselfCS-ES/blob/main/TeachYourselfCS-ES.md
Enseñate Ciencias de la Computación
Este documento es una traduccion de TeachYourselfCS, escrito por Ozan Onay y Myles Byrne. Para más información acerca de esta traducción, ir al final del documento.

Esta versión es una traducción de la última versión de la original hecha en Mayo 2020.

Si eres un ingeniero autodidacta o un graduado de un bootcamp, te mereces aprender por ti mismo ciencias de la computación. Afortunadamente puedes obtener una educación de alta calidad sin necesidad de invertir muchos años ni una fortuna en un título de Pregrado 💸.

Existen muchos recursos en internet, pero unos definitivamente mejores que otros. No necesitas otra lista de "200+ Cursos Online Gratis!". Necesitas respuestas a las siguientes preguntas:

¿Cuales temas debes aprender, y por que?

¿Cual es el mejor libro o clase para un tema?

Esta guía es nuestro intento para darle una respuesta definitiva a esas preguntas.

TL;DR: (Resumelo por favor)
Estudia todos los siguientes temas, en más o menos el orden presentado, usando el libro sugerido o la serie de videos, idealmente ambos. Trata de estudiar 100-200 horas en cada tema, luego repasa tus temas preferidos a lo largo de tu carrera 🚀.

Tema	¿Por qué estudiarlo ?	Libro	Videos
Programacion	No seas la persona que nunca entendió algo como la recursión.	Structure and Interpretation of Computer Programs	Brian Harvey Berkeley CS 61A
Arquitectura de Computadores	Si no tienes un modelo mental sólido sobre cómo un computador funciona realmente, entonces todas tus abstracciones de alto nivel se quebraban fácilmente.	Computer Systems: A Programmer's Perspective	Berkeley CS 61C
Algoritmos y Estructura de Datos	Si no sabes como usar estructuras de datos ubicuas como las pilas, colas, árboles, y grafos, no serás capaz de resolver problemas desafiantes.	The Algorithm Design Manual	Clases de Steven Skiena
Matemática para Ciencias de la computación	Las ciencias de la computación son básicamente una rama de las matemáticas aplicadas, así que aprender matemáticas te dará una ventaja competitiva.	Mathematics for Computer Science	Tom Leighton MIT 6.042J
Sistemas Operativos	La mayor parte del código que escribes es ejecutado por un sistema operativo, así que deberías saber cómo ambos interactúan.	Operating Systems: Three Easy Pieces	Berkeley CS 162
Redes de Computadores	El internet resultó ser una gran cuestión. Entiende cómo funciona para desbloquear todo su potencial	Computer Networking: A Top-Down Approach	Stanford CS 144
Base de Datos	Los datos son el centro de los programas más importantes, pero muy pocos entienden cómo funcionan realmente los sistemas de bases de datos.	Readings in Database Systems	Joe Hellerstein Berkeley CS 186
Lenguajes y Compiladores	Si entiendes cómo funcionan los lenguajes y los compiladores, entonces serás capaz de escribir mejor código y aprender nuevos lenguajes más fácilmente.	Crafting Interpreters	Curso de Alex Aiken en edX
Sistemas Distribuidos	Hoy en día, la mayoría de los sistemas son sistemas distribuidos.	Designing Data-Intensive Applications by Martin Kleppmann	MIT 6.824
¿Te parece demasiado?
Si la idea de aprender 9 temas a lo largo de varios años te parece abrumadora, te sugerimos enfocarte en dos libros: Computer Systems: A Programmer 's Perspective y Designing Data-Intensive Applications. En nuestra experiencia, estos dos libros proveen la mayor utilidad por tiempo invertido, especialmente para aquellos ingenieros autodidactas y graduados de bootcamps que trabajan en aplicaciones en red. También pueden servir como un "delicioso abrebocas" para otros temas y recursos listados.

¿Por qué aprender Ciencias de la computación?
Existen 2 tipos de ingenieros de software: Aquellos que entienden bien las ciencias de la computación para trabajar en cosas desafiantes e innovativas, y aquellos que se las arreglan solo porque conocen una que otra herramienta de alto nivel.

Ambos se autodenominan como ingenieros de software, y ambos tienden a ganar salarios similares cuando comienzan sus carreras. Pero los ingenieros de Tipo 1 progresan a trabajo satisfactorio y bien remunerado a través del tiempo, ya sea en trabajo comercialmente valioso o en proyectos innovadores de código abierto, liderazgo técnico o contribuciones individuales de alta calidad.

El sistema global de SMS maneja 20 billones de mensajes al día. WhatsApp maneja 42 billones. Con 57 ingenieros. pic.twitter.com/zZrtSIzhlR

— Benedict Evans (@BenedictEvans) 2 de Febrero, 2016

Los ingenieros de Tipo 1 encuentran formas de aprender ciencias de la computación a profundidad, ya sea mediante medios convencionales o aprendiendo implacablemente a lo largo de sus carreras. Los ingenieros de Tipo 2 típicamente se quedan en la superficie, aprendiendo herramientas y tecnologías en vez de sus fundamentos subyacentes, adquiriendo nuevas habilidades sólo cuando los vientos de la moda tecnológica cambian.

Actualmente, el número de personas entrando en la industria está creciendo rápidamente, mientras el número de profesionales en las ciencias de la computación se ha mantenido estático. La oferta excesiva de ingenieros de Tipo 2 está empezando a reducir sus oportunidades de empleo y los mantiene fuera de los trabajos más satisfactorios de la industria. Ya sea que te estés esforzando por ser un ingeniero de Tipo 1 o simplemente quieras mayor seguridad laboral, aprender ciencias de la computación es el único camino confiable.

Lol oh pero lo estaban….pic.twitter.com/XVNYlXAHar

— Jenna Bilotta (@jenna) 4 de Marzo, 2017

Guia de Temas
Programacion
La mayoría de programas de ciencias de la computación comienzan con una "introducción" a la programación. Las mejores versiones de estos cursos no se orientan exclusivamente a novatos, sino también a aquellos que se perdieron de conceptos beneficiosos y modelos de programación mientras aprenden a programar por primera vez.

Nuestra recomendacion estandar para este tema es el clasico Structure and Interpretation of Computer Programs, el cual esta disponible gratuitamente como un libro y un conjunto de clases de MIT. A pesar de que esas clases son buenas, nuestra recomendacion son las clases de Brian Harvey de SICP. Estas son más refinadas y mejor orientadas a nuevos estudiantes que las de MIT.

Recomendamos estudiar por lo menos los tres primeros capítulos de SICP y hacer los ejercicios. Para práctica adicional, hacer algunos ejercicios de problemas de programación como aquellos que aparecen en exercism

Desde que esta guía fue publicada por primera vez en 2016, una de las preguntas que más se han preguntado ha sido sí recomendamos unas versiones actualizadas de el curso 61A enseñadas por John DeNero, y/o el libro correspondiente, Composing Programs, el cual "sigue la tradicion de SICP" pero usa Python. Consideramos que los recursos de DeNero también son buenos, y algunos estudiantes terminarán prefiriendo, pero aun asi sugerimos SICP, Scheme, y las clases de Brian Harvey como el primer recurso para revisar.

¿Por qué? Porque SICP es único en su habilidad--Al menos potencialmente-- de alterar tus creencias fundamentales sobre los computadores y la programación. No todos experimentaran esto. Algunos odiarán el libro, otros no pasarán de las primeras páginas. Pero la potencial recompensa hace que intentarlo valga la pena.

Si no disfrutas SICP,intenta Composing Programs. Si eso tampoco te sirve, intenta How To Design Programs. Si ninguno de estos parece recompensar tu esfuerzo, tal vez sea una señal de que debes enfocarte en otros temas por un tiempo, y revisar la disciplina de la programación en un año o dos.

Finalmente, un punto a clarificar: Esta guía NO está diseñada para aquellos que son nuevos en la programación. Asumimos que eres un programador competente sin estudios en ciencias de la computación, buscando llenar vacíos. El hecho de que hemos incluido una sección sobre "programación" es simplemente un recordatorio de que tal vez existen más cosas que aprender. Para aquellos que nunca han programado antes, pero que les gustaría hacerlo, podrían preferir esta guia.

Arquitectura de Computadores
La Arquitectura de Computadores --a veces llamada "Sistemas Computacionales" o "Organizacion Computacional"--es una mirada importante a la computación debajo de la superficie de software. En nuestra experiencia, es el área más ignorada entre los ingenieros de software autodidactas.

Nuestro libro introductorio favorito es Computer Systems: A Programmer's Perspective, y una introduccion tipica a la arquitectura de computadoras usando el libro cubriria la mayor parte de los capítulos 1 al 6.

Amamos este libro por el enfoque práctico y orientado a programadores. Aunque hay mucho más allá de lo que cubre el libro, este sirve como un gran punto de partida para aquellos que les gustaría entender los sistemas computacionales primeramente para escribir software más rápido, más eficiente, y más confiable.

Para aquellos que prefieren una introducción más gentil y un balance de hardware y software, sugerimos The Elements of Computing Systems, también conocido como "Nand2Tetris". Este es un libro ambicioso que intenta dar un entendimiento cohesivo sobre cómo todo funciona dentro de un computador. Cada capítulo consiste en construir una pequeña parte de todo el sistema, desde escribir puertas de lógica básicas usando HDL, una CPU, un ensamblador hasta una aplicación del tamaño de un juego de Tetris.

Recomendamos leer los primeros seis capítulos del libro y completar los proyectos incluidos. Esto desarrolla tu entendimiento de la relación entre la arquitectura de la máquina y el software que corre allí.

La primera mitad del libro (y todos sus proyectos), están disponibles gratuitamente desde el sitio web oficial de Nand2Tetris. También está disponible como curso de Coursera.

Buscando la simplicidad y la cohesión, Nand2Tetris intercambia la profundidad. Particularmente, dos conceptos muy importantes en la arquitectura de computadores moderna, como la jerarquía de memoria y el pipelining, están casi totalmente ausentes del texto.

Una vez que te sientas cómodo con el contenido de Nand2Tetris, sugerimos intentar Computer Systems: A Programmer's Perspective, o considerar Computer Organization and Design de Patterson y Hennessy, un excelente y clasico libro. No todas las secciones del libro son esenciales; sugerimos seguir el curso de Berkeley CS61C "Great Ideas in Computer Architecture" para lecturas específicas. Las notas de clase y los laboratorios estan disponible en linea, y las clases anteriores estan en el Internet Archive

Algoritmos y Estructura de Datos
Concordamos con que con décadas de sabiduría común que estar familiarizados con algoritmos y estructuras de datos común es uno de los aspectos más empoderantes de una educación en ciencias de la computación. Este también es un gran lugar para entrenar la capacidad para resolver problemas, lo cual será de gran beneficio en las otras áreas de estudio.

Hay cientos de libros disponibles, pero nuestro favorito es [The Algorithm Design Manual](The Algorithm Design Manual) por Steven Skiena. El claramente ama la resolución algorítmica de problemas y típicamente es exitoso en fomentar el mismo entusiasmo en sus estudiantes y lectores. En nuestra opinión, los dos textos comúnmente sugeridos (CLRS y Sedgewick) tienden a ser un poco densos en pruebas para aquellos que están aprendiendo el material principalmente para mejorar sus habilidades de resolución de problemas.

Para aquellos que prefieren videos, Skiena generosamente proporciona los suyos en linea. Tambien nos gusta el curso de Tim Roughgarden, disponible en Coursera y en su pagina. El que prefieras el estilo de Skiena o Roughgarden será una cuestión de preferencia personal. De hecho, hay una docena de buenas alternativas, así que si te llegas a encontrar una que te guste, ¡te motivamos a quedarte con ella!

Para practicar, nuestra forma preferida es que los estudiantes resuelvan problemas en Leetcode. Estos tienden a ser problemas interesantes con soluciones y discusiones incluidas. También te ayudarán a evaluar tu progreso con preguntas que son comúnmente usadas en entrevistas técnicas en compañías de software más competitivas. Sugerimos resolver alrededor de 100 problemas de leetcode al azar como parte de tus estudios.

Finalmente, recomendamos mucho How to Solve It como una guia excelente y unica a la resolucion general de problemas; es tan aplicable a las ciencias de la computacion como a las matematicas.

Matemáticas para las Ciencias de la Computación
De cierta forma, las ciencias de la computación son una rama madura de las matemáticas aplicadas. Mientras que algunos ingenieros de software intentan--En variados grados de éxito--ignorarla, te motivamos a que te tomes el trabajo de estudiarla directamente. Hacerlo exitosamente te dará una enorme ventaja competitiva sobre aquellos que no lo hagan.

El área más relevante de las matemáticas para las ciencias de la computación es ampliamente llamada "matemáticas discretas", donde "discreto" es lo opuesto de "continuo" y es vagamente una colección de temas interesantes de la matemática aplicada fuera del cálculo. Dada la definición vaga, no es significativo tratar de cubrir la totalidad de las "matemáticas discretas". Una meta más realista es tener un entendimiento funcional de la lógica, combinatoria y probabilidad, teoría de conjuntos, teoría de grafos, y un poco de teoría de números relacionado con la criptografía. Álgebra lineal es un área adicional que vale la pena estudiar, dada su importancia en los gráficos de computadora y en machine learning.

Nuestro punto de partida sugerido para las matemáticas discretas es el conjunto de notas de László Lovász. El profesor Lovász hizo un buen trabajo en hacer el contenido accesible e intuitivo, así que este sirve como un punto de partida mejor que otros textos más formales.

Para un estudio más avanzado, sugerimos Mathematics for Computer Science, las notas del tamaño de un libro del curso de MIT del mismo nombre. Los videos de ese curso estan gratuitamente disponibles, y son nuestra recomendacion para videos de matematiacs discretas.

Para algebra lineal, sugerimos empezar con la serie de videos Essence of linear algebra, seguida del libro y clases por Gilber Strang.

Sistemas Operativos
Operating System Concepts y Modern Operating Systems son los libros "clásicos" sobre sistemas operativos. Ambos han atraído criticismos por su falta de claridad y general dificultad para los estudiantes.

Operating Systems: Three Easy Pieces es una buena alternativa que esta gratuitamente disponible en linea. Particularmente nos gusta la estructura y legibilidad del libro, y sentimos que los ejercicios valen la pena.

Luego, te recomendamos explorar las decisiones de diseño de diferentes sistemas operativos, a través de libros del tipo "Partes Internas de {Sistem Operativo}" como Lion's commentary on Unix, The Design and Implementation of the FreeBSD Operating System, y Mac OS X Internals. Para Linux, recomendamos el fantástico libro de Robert Love, Linux Kernel Development

Una gran forma de consolidar tu entendimiento de los sistemas operativos es leer el código de un kernel pequeño y añadir funcionalidades. Una opcion es xv6, un puerto de Unix V6 a ANSI C y x86 mantenido para un curso en MIT. OSTEP tiene un apendice de laboratorios potenciales de xv6 llenos de grandes ideas para projectos potenciales.

Redes de Computadores
Dado que gran parte de la ingeniería de software es en servidores y clientes web, una de las áreas de inmediato valor de las ciencias de la computación es la de redes. Nuestros estudiantes autodidactas que metódicamente estudian redes encuentran que finalmente entienden conceptos, términos, y protocolos que los habían rodeado por años.

Nuestro libro favorito para este tema es Computer Networking: A Top Down Approach. Los pequeños proyectos y ejercicios en el libro valen mucho la pena hacer, y nos gusta particularmente los "Wireshark labs" los cuales estan generosamente en linea.

Para aquellos que prefieran videos, sugerimos el curso de Stanford Introduction to Computer Networking disponible previamente en la plataforma de MOOC de Stanford Lagunita, pero tristemente ahora solo se encuentra como playlists no oficiales en Youtube.

Bases de datos
Toma mucho más trabajo aprender de forma autodidacta acerca de sistemas de bases de datos que la mayoría de otros temas. Es un campo de estudio (post 1970s) relativamente nuevo con incentivos fuertemente comerciales para que las ideas se queden en secreto. Adicionalmente, muchos posibles autores de textos han preferido unirse o empezar compañías.

Debido a estas circunstancias, motivamos a los estudiantes evitar libros y empezar con las grabaciones de la clase CS 186, el curso de Joe Hellerstein de bases de datos en Berkeley, y luego leer artículos.

Un articulo particularmente util para nuevos estudiantes es "Architecture of a Database System", el cual provee un vistazo de alto nivel de como funcionan los sistemas de base de datos relacional (RDBMS). Esto servirá como una base útil para profundizar más adelante.

Readings in Database Systems, mejor conocido como el "Libro Rojo" de las bases de datos, es una coleccion de artículos compilados y editados por Peter Bailis, Je Hellerstein y Michael Stonebraker. Para aquellos que han progresado más allá del nivel del contenido de CS 186, el Libro Rojo debe ser la próxima parada.

Si realmente quieres usar un libro introductorio, te recomendamos Database Management Systems por Ramakrishnan y Gehrke. Para estudiantes mas avanzados, el clasico de Jim Gray Transaction Processing: Concepts and Techniques vale la pena, pero no recomendamos usar este como primer recurso.

Finalmente, el modelado de datos es un aspecto descuidado y pobremente enseñado al trabajar con bases de datos. Nuestro libro recomendado en el tema es Data and Reality: A Timeless Perspective on Perceiving and Managing Information in Our Imprecise World

Lenguajes y Compiladores
La mayoría de los programadores aprenden lenguajes, mientras que la mayoría de los que científicos computacionales aprenden sobre lenguajes. Esto les otorga una ventaja distintiva sobre el programador, incluso en el dominio de la programación! Su conocimiento generaliza; son capaces de entender de forma más profunda y rápida el funcionamiento de un nuevo lenguaje que aquellos que simplemente han aprendido lenguajes específicos.

Nuestro texto introductorio recomendado es el excelente Crafting Interpreters por By Nystrom, disponible gratuitamente en línea. Está bien organizado, es altamente entretenido, y muy adecuado para aquellos cuyo objetivo principal es simplemente tener un mejor entendimiento de los lenguajes que usan y sus herramientas. Sugerimos tomar el tiempo necesario para trabajar todo el libro, intentando cualquiera de los "desafíos" para sostener tu interés.

Una recomendacion mas tradicional es Compilers: Principles, Techniques & Tools, comunmente conocido como "El Libro del Dragon". Desafortunadamente, no está diseñado para un estudio autodidacta, pero para ser usado como material de temas por uno o dos semestres.

Si decides usar el Libro del Dragón, es casi esencial que seas muy selectivo con los temas, idealmente con la ayuda de un mentor. De hecho, la forma en que sugerimos usar el Libro del Dragón, si así lo deseas, es como una referencia suplementaria a una serie de videos. Nuestra recomendación es la de Alex Aiken en edX

Sistemas Distribuidos
A medida que los computadores han incrementado en cantidad, también se han propagado. Donde antes los negocios compraban mainframes grandes y más grandes, ahora es normal para incluso aplicaciones muy pequeñas ejecutarse a través de múltiples máquinas. Los sistemas distribuidos son el estudio de cómo razonar sobre los trade-offs de implementarlos.

Nuestro libro sugerido para estudiar es Designing Data-Intensive Applications. De lejos mejor que un libro tradicional, DDIA es un libro altamente legible diseñado para practicantes, el cual de alguna forma evita sacrificar profundidad o rigor.

Para aquellos que busquen un texto mas tradicional, o que prefieran uno que este gratuitamente disponible en linea, sugerimos Distributed Systems, 3rd Edition

Para aquellos que prefieran videos, 6.824 DE MIT es un excelente curso enseñado por Robert Morris con lecturas disponibles aqui.

No importa cual sea tu elección de libro o recursos secundarios, estudiar sistemas distribuidos requiere absolutamente leer artículos. Esta es una buena lista, y recomendamos mucho atender tu sección local de Papers We Love.

Preguntas Frecuentes
¿Quién es la audiencia ideal de esta guía?
Tenemos en mente que eres un ingeniero de software autodidacta, un graduado de un bootcamp, un estudiante de secundaria precoz, o un estudiante universitario buscando suplementar tu educación formal con estudios adicionales. La pregunta de cuando embarcarse en este viaje es enteramente personal, pero la mayoría tiende a beneficiarse más cuando ya tienen algo de experiencia profesional antes de estudiar de fondo la teoría de las ciencias de la computación. Por ejemplo, nos dimos cuenta de que a los estudiantes les encanta aprender sobre sistemas de base de datos si ya han trabajado con bases de datos profesionalmente, o sobre redes de computador si han trabajado en un proyecto web o dos.

¿Qué hay de la IA/gráficos/tema-de-moda-x?
Hemos tratado de limitar nuestra lista a temas de las ciencias de la computación que sentimos que todo practicante de la ingeniería de software debería saber, sin importar la especialidad o la industria, pero con un enfoque en los sistemas. En nuestra experiencia, estos temas tendrán el más alto ROI (Retorno de la Inversión) para la gran mayoría de ingenieros autodidactas y graduados de bootcamps, y proveerán una sólida fundación para estudios adicionales. Subsecuentemente, estarás en una mejor posición para leer libros o artículos y aprender los conceptos centrales sin mucha ayuda. Los siguientes son algunos puntos de partida para algunas "electivas" comunes.

Para inteligencia artificial: Realiza el curso de introducción a la AI de Berkeley mirando los videos y completando los excelentes proyectos de Pacman. Usa el Artificial Intelligence: A Modern Approach de Russell y Norvig.

Para machine learning: Has el curso de Andrew Ng de coursera. Se paciente, y asegurate de que entiendas los fundamentos antes de correr a los temas nuevos de moda como el deep learning.

Para graficos de computadoras: Estudia el material del curso CS 184 de Berkeley, y usa Computer Graphics: Principles and Practice como libro de referencia.

¿Qué tan estricto es el orden sugerido?
Realisticamente, todos estos temas tienen una cantidad significativa de superposición, y hacen referencia entre ellos cíclicamente. Toma por ejemplo la relación entre las matemáticas discretas y los algoritmos: aprender matemáticas primero te ayudará a analizar y entender tus algoritmos en mayor profundidad, pero aprender algoritmos primero te dará mayor motivación y contexto para las matemáticas discretas. Idealmente, volverás a estos temas muchas veces durante tu carrera.

Como tal, nuestro orden sugerido está allí para ayudarte a empezar... si tienes una razón de fondo para preferir una secuencia diferente, entonces adelante. Los "prerrequisitos" más esenciales, en nuestra opinión, son: arquitectura de computadores antes de sistemas operativos o bases de datos, y redes y sistemas operativos antes de sistemas distribuidos.

¿Cómo se compara esto al currículo del Open Source Society o freeCodeCamp?
Cuando esta guía fue escrita en 2016, la guía de OSS tenía demasiados temas, sugería recursos inferiores para muchos de ellos, y no explicaba la razón o la guía de porqué o qué aspectos de un curso en particular son valiosos. Tratamos de limitar nuestra lista de cursos a aquellos que realmente deberías saber como ingeniero de software, sin importar de tu especialidad, y de ayudarte a entender porqué cada curso está incluido. En los años siguientes, la guia de OSS ha mejorado, pero aún pensamos que este es un camino más claro y cohesivo.

freeCodeCamp está enfocado principalmente a la programación, no a las ciencias de la computación. Para saber porque deberías aprender ciencias de la computación, mira arriba. Si eres totalmente nuevo en la programación, te sugerimos priorizar su aprendizaje, y luego retornar a esta guía en un año o dos.

¿Qué hay del lenguaje X?
Aprender un lenguaje de programación particular está en un plano totalmente distinto a aprender acerca de un área de las ciencias de la computación -- aprender un lenguaje es mucho mas facil y menos valioso. Si ya sabes unos cuantos lenguajes, te sugerimos simplemente seguir nuestra guía y encajar la adquisición de un lenguaje en los huecos o vacíos, o dejarlo para después. Si has aprendido a programar bien (Como con Structure and Interpretation of Computer Programs), y especialmente si has aprendido sobre compiladores, te debería tomar poco más que un fin de semana para aprender lo esencial de un nuevo lenguaje, para luego despues podras aprender las librerias/herramienta/ecosistema en el trabajo.

¿Qué hay de tecnología de moda X?
No hay ninguna tecnología individual que sea lo suficientemente importante que aprender a usarla deba ser una parte central de tu educación. Por otro lado, es bueno que te apasiona aprender acerca de ella. El truco está en trabajar desde la tecnología particular hacia el concepto o campo que le subyace, y aprender eso en profundidad antes de ver como tu tecnología de moda encaja en la imagen más grande.

¿Por qué sigues recomendando SICP?
Mira, solo intentalo. Algunas personas encuentran SICP una experiencia alucinante, característica compartida por muy pocos otros libros. Si no te gusta, puedes intentar alguna otra cosa y, tal vez, volver a SICP más tarde.

¿Por qué sigues recomendando el libro del Dragón?
El libro del Dragón sigue siendo el recurso más completo sobre compiladores. Tiene algo de mala fama, típicamente por sobreenfatizar ciertos temas que son menos mundanos para cubrir en detalle recientemente, como el parseo. La cuestión es que el propósito del libro nunca fue ser estudiado de tapa a tapa. Su propósito es el de proporcionar el suficiente material a un instructor para poder preparar un curso. De forma similar, un autodidacta puede escoger su propia aventura a través del libro, o mejor aún seguir las sugerencias que las clases de cursos públicos han hecho en su estructura.

¿Cómo puedo conseguir los libros a buen precio?
Muchos de los textos sugeridos están disponibles en línea gratuitamente, gracias a la generosidad de sus autores. Para aquellos que no lo están, sugerimos comprar copias usadas de ediciones antiguas. Como regla general, si han habido más de un par de ediciones de un libro, es muy probable que la edición más vieja sea perfectamente adecuada. Es ciertamente improbable que la nueva edición sea 10x mejor que la anterior, incluso si la diferencia en su precio lo es!

¿Quién hizo esto?
Esta guia fue originalmente escrita por Oz Nova y Myles Byrne, con actualizaciones en 2020 hechas por Oz. Está basada en nuestra experiencia enseñando fundamentos de ciencias computacionales a más de 1000 ingenieros mayormente auto educados y graduados de bootcamp en pequeños grupos en San Francisco y en línea. Gracias a todos nuestros estudiantes por su feedback continuo en recursos para el auto aprendizaje.

Estamos muy confiados en que te puedes enseñar todo lo que está arriba, asumiendo que hay suficiente tiempo y motivación. Pero si prefieres un programa más intensivo, estructurado, y encabezado por un instructor, tal vez te interese nuestro programa Intensivo de Ciencias de la Computacion. NO sugerimos conseguir una maestria.

¿Quién es el traductor?
Soy James Archbold, un desarrollador frontend Colombiano trabajando actualmente en Elemento 43. Esta es una guía que decidí traducir para que las personas que son mayormente autodidactas o que quieren aprender por su cuenta tengan una mejor idea y estructura sobre cómo aprender estos temas.

Todos los libros que referencie tienen links a su versión gratuita online o su libro en amazon. Es posible que algunos de estos tengan traducciones oficiales o no oficiales. Más adelante, incluiré links a aquellos libros que tengan traducciones y estén disponibles en línea o en amazon.

Si quieres hacer alguna recomendación, corrección, o aclaración, siéntete libre de comunicarte conmigo o hacer un pull request con los cambios que sean necesarios.

Feliz aprendizaje!