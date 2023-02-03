
![ZKP Alí baba](https://academy.bit2me.com/wp-content/uploads/2019/05/cueva-de-alibaba.jpg)


# Aprendiendo Zero Knowledge Proofs (ZKP)

>Este proyecto fue creado por H.E.R. DAO LATAM.
>
>**¿Te gustaría ayudar a financiar este proyecto?**
>
>Envia un DM a [@herdaolatam](https://mobile.twitter.com/herdaolatam) en Twitter.

Teniendo en cuenta la importancia que tienen las pruebas de conocimiento cero en la seguridad de la información, los casos de uso que se conocen y los que aún no se descubren, decidimos crear un repositorio confiable en español que sirva como base para seguir construyuendo conocimiento, pues en internet hay muy poca información relacionada en este idioma.


# Glosario

| ***Palabra*** | ***Definición*** | ***Fuente*** |
| --- | --- | --- |
| **Aleatoriedad** | Es una condición necesaria para el correcto funcionamiento del las pruebas de conocimiento cero. En el lado del verificador se necesita para generar consultas al probador y en el lado del probador, se utiliza  para lograr un conocimiento cero.| [Cointelegraph](https://es.cointelegraph.com/explained/zero-knowledge-testing-zkp-the-state-of-the-art-in-cryptography), [Medium](https://medium.com/starkware/stark-math-the-journey-begins-51bd2b063c71) |
| **Argumento Sucinto No interactivo del Conocimiento (SNARK)** | Es una construcción de prueba en la que se puede demostrar la posesión de cierta información, sin revelarla y sin ninguna interacción entre el probador y el verificador. | [Zcash](https://z.cash/technology/zksnarks/) |
| **Argumento de Conocimiento Escalable y Transparente (STARK)** |Tecnología que busca mejorar el problema de privacidad y escalabilidad de blockchain con un método de transacción transparente. Podría convertirse en la próxima etapa de las SNARKs  | [Medium](https://medium.com/starkware/stark-math-the-journey-begins-51bd2b063c71) |
| **Bulletproofs** | Son pruebas cortas no interactivas de conocimiento cero que no requieren una configuración confiable. Se puede usar para convencer a un verificador de que un texto sin formato cifrado está bien formado. |[Stanford University](https://crypto.stanford.edu/bulletproofs/)|
| **Campos Finitos** | Consiste de un conjunto finito de elementos sobre el cual se definen un par de operaciones binarias + y ·, las cuales satisfacen algunas propiedades aritméticas.|[IPN](https://www.repositoriodigital.ipn.mx/bitstream/123456789/7845/6/DOC6.pdf)|
| **Cifrado de Flujos** | Algoritmo de cifrado que utiliza una clave simétrica para cifrar y descifrar una determinada cantidad de datos. Aplican esta clave a cada dígito binario en un flujo de datos, un bit a la vez. |[Kryptonsolid](https://kryptonsolid.com/que-es-un-cifrado-de-flujo/#:~:text=Un%20cifrado%20de%20flujo%20es%20un%20algoritmo%20de%20cifrado%20que,cifrado%20como%20en%20el%20descifrado.)|
| **Cifrado Homomórfico** | Método de cifrado que permite realizar cálculos en datos cifrados sin descifrarlos primero con una clave secreta. Los resultados de estos cálculos solo pueden ser descifrados por el propietario de la clave privada. |[Ciberseguridad](https://ciberseguridad.com/guias/prevencion-proteccion/criptografia/cifrado-homomorfico/)|
| **Circuito Aritmético** | Divide en pasos individuales un programa. Consiste en las operaciones aritméticas básicas de suma, resta, multiplicación y división |[Zcash](https://z.cash/technology/zksnarks/)|
| **Claves Privadas** | Es una cadena de letras y números que le permite acceder a sus fondos en criptomonedas y administrarlos desde cualquier parte del mundo donde haya conexión a Internet. Esta clave no debe ser compartida con nadie. |[Coinbase](https://www.coinbase.com/es-LA/learn/crypto-basics/what-is-a-private-key#:~:text=Una%20clave%20privada%20es%20una,fondos%20en%20criptomonedas%20y%20administrarlos.)|
| **Conocimiento Cero** | Garantiza el anonimato. Si la verificación es verdadera, ningún verificador puede saber más que eso.|[Cointelegraph](https://es.cointelegraph.com/explained/zero-knowledge-testing-zkp-the-state-of-the-art-in-cryptography)|
| **Curvas Elípticas** | Es una de las herramientas más útiles para la criptografía moderna. Fueron propuestas en la década de 1980 y se generalizaron después de 2004. Ofrecen buenos niveles de seguridad con longitudes de clave cortas y permiten implementaciones más rápidas que otros métodos.| [Not a Monad Tutorial](https://www.notamonadtutorial.com/need-for-speed-elliptic-curves-chapter/) |
| **Escalabilidad** |  | []() |
| **Fiat Shamir Transform** | Es una técnica para tomar una prueba interactiva de conocimientos y crear una firma digital basada en ella.| []() |
| **Firmas Ciegas** | Creadas por David Chaum en el año de 1982. Fueron un diseño criptográfico que permitía firmar digitalmente documentos, archivos y mensajes de manera que no se revelará información a las partes involucradas en el intercambio de firmas.|[Cointelegraph](https://es.cointelegraph.com/explained/zero-knowledge-testing-zkp-the-state-of-the-art-in-cryptography)|
| **Halo** | Novedoso avance en criptografía descubierto por investigadores de ECC.|[Zcash](https://z.cash/technology/zksnarks/)|
| **Integridad Computacional** | Es una propiedad fundamental que significa que la salida de cierto cálculo es correcta. Las cadenas de bloques lo logran sin que se desconfie de ello. |[Medium](https://medium.com/starkware/stark-math-the-journey-begins-51bd2b063c71) |
| **Interpolación** | Encontrar una representación del sistema de restricciones aritméticas en términos de polinomios durante el proceso de compilación STARK. | []() |
| **Nodo** | Es un punto terminal de una red, o cualquiera de sus intersecciones. Su origen está en la ráiz indoeuropea ned, que en latín produjo nodus, origen del español nodo y nudo, y que da origen a la propia "net" en inglés. | [Jose Antonio Millán](http://jamillan.com/v_nodo.htm) |
| **Oráculo** |  | []() |
| **Polinomios** | Expresión formada por indeterminados (también llamados variables) y coeficientes, que sólo implica las operaciones de suma, resta, multiplicación y exponenciación entera no negativa de variables. | []() |
| **Polinomio de Bajo Grado** | El grado es el número de términos del polinomio. | []() |
| **Probador** | Parte esencial para el funcionamiento del Protocolo de Conocimiento Cero. Su misión es generar el secreto y mantener el control total sobre el mismo. |[Cointelegraph](https://es.cointelegraph.com/explained/zero-knowledge-testing-zkp-the-state-of-the-art-in-cryptography)|
| **Programa Aritmético Cuadrático (QAP)** |  | []() |
| **Protocolo Criptográfico** |  | []() |
| **Protocolo Pinocchio** | Es un "sistema construido para verificar eficazmente cálculos generales basándose únicamente en supuestos criptográficos". | []() |
| **Protocolo Protegido de Orchard** | Se basa en pruebas de conocimiento cero que utilizan el sistema de prueba de Halo 2. Define un nuevo grupo protegido con claves de gasto y direcciones de pago que se prestan a futuras mejoras de escalabilidad.  | [Zcash](https://z.cash/technology/zksnarks/)|
| **Pruebas Sucintas** | Son elementos que pueden verificarse en unos pocos milisegundos, con una longitud de prueba de sólo unos cientos de bytes incluso para declaraciones sobre programas que son muy grandes. | [Zcash](https://z.cash/technology/zksnarks/)|
| **Restricciones** | | []() |
| **Sistemas de Prueba** |  | []() |
| **Sistema de Prueba de Conocimiento Cero** | Es un sistema de prueba en el que existe información secreta conocida por el probador y desconocida por el verificador. Los militares por ejemplo pueden usar sistemas de cifrado ZKP para asegurar sus comunicaciones evitando que el enemigo las descifre. |[Cointelegraph](https://es.cointelegraph.com/explained/zero-knowledge-testing-zkp-the-state-of-the-art-in-cryptography)|
| **Sistema de Prueba Interactivo** | Es una máquina abstracta que modela la computación como el intercambio de mensajes entre dos partes: un probador y un verificador. Los mensajes se envían en ambas direcciones entre el verificador y el probador hasta que el verificador tiene una respuesta al problema y se ha "convencido" a sí mismo de que es correcta. | []() |
| **Sistema de Prueba No Interactivo** | Es un método mediante el cual una parte puede demostrar "probador" a otra parte "verificador" que una afirmación dada es verdadera y no requiere interacción bidireccional entre ambos. | []() |
| **Sistema de Restricciones de Rango 1** | Verifica que los valores de entrada "se desplazan correctamente" por el circuito.| [Zcash](https://z.cash/technology/zksnarks/)|
| **Trabajo Computacional** |  | []() |
| **Transacciones Realizables** |  | []() |
| **Transacciones Protegidas** |  | []() |
| **Turing Complete** | Sistema de reglas de manipulación de datos que puede utilizarse para simular cualquier modelo de computación que describa una máquina abstracta. | []() |
| **Validéz** |  | []() |
| **Valor Hash** |  | []() |
| **Valores de Entrada** |  | []() |
| **Valores de Salida** |  | []() |
| **Verificador** | Parte esencial para el funcionamiento del Protocolo de Conocimiento Cero. Su misión es verificar la autenticidad de un secreto por medio de pruebas criptográficas que así se lo permitan. |[Cointelegraph](https://es.cointelegraph.com/explained/zero-knowledge-testing-zkp-the-state-of-the-art-in-cryptography)|

### ¿Te gustaría Contribuir?

Este glosario se irá haciendo cada vez más nutritivo en la medida en que puedas contribuir con nosotrxs.
Da clic [Aquí](https://github.com/Cmolosa/ZKP-en-Espanol/blob/main/Contribuciones.md) para enterarte de como puedes aportar.
Estaremos felices de contar con tu ayuda :)


> Si tienes preguntas, encuentras algún problema o error, no dudes en hacernoslo saber dando clic [Aquí](https://github.com/Cmolosa/ZKP-en-Espanol/issues)

