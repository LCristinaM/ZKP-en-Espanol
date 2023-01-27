# Aprendiendo Zero Knowledge Proofs  (ZKP en Español)

####### Este proyecto fue creado y financiado por H.E.R. DAO LATAM en alianza con .....
---
![Logo HER DAO](https://web.telegram.org/k/
https://web.telegram.org/k/download/1603182316)

# Glosario

| ***Palabra*** | ***Definición*** | ***Fuente*** |
| --- | --- | --- |
| **Aleatoriedad** | Es una condición necesaria para el correcto funcionamiento del las pruebas de conocimiento cero. En el lado del verificador se necesita para generar consultas al probador y en el lado del probador, se utiliza  para lograr un conocimiento cero.| [Cointelegraph](https://es.cointelegraph.com/explained/zero-knowledge-testing-zkp-the-state-of-the-art-in-cryptography), [Medium](https://medium.com/starkware/stark-math-the-journey-begins-51bd2b063c71) |
| **Argumento Sucinto No interactivo del Conocimiento (SNARK)** | Es una construcción de prueba en la que se puede demostrar la posesión de cierta información, sin revelarla y sin ninguna interacción entre el probador y el verificador. | [Zcash](https://z.cash/technology/zksnarks/) |
| **Argumento de Conocimiento Escalable y Transparente (STARK)** |Tecnología que busca mejorar el problema de privacidad y escalabilidad de blockchain con un método de transacción transparente. Podría convertirse en la próxima etapa de las SNARKs  | [Medium](https://medium.com/starkware/stark-math-the-journey-begins-51bd2b063c71) |
| **Bulletproofs** | Son pruebas cortas no interactivas de conocimiento cero que no requieren una configuración confiable. Se puede usar para convencer a un verificador de que un texto sin formato cifrado está bien formado. |[Stanford University](https://crypto.stanford.edu/bulletproofs/)|
| **Campos Finitos** | Es un campo con un orden finito de elementos. El orden de un campo finito es siempre un primo o una potencia de primo. Para cada potencia de primo q = p^r, existe exactamente un campo finito con q elementos, hasta el isomorfismo.|[]()|
| **Cifrado de Flujos** | |[]()|
| **Cifrado Homomórfico** | |[]()|
| **Circuito Aritmético** | Divide en pasos individuales un programa. Consiste en las operaciones aritméticas básicas de suma, resta, multiplicación y división |[Zcash](https://z.cash/technology/zksnarks/)|
| **Claves Privadas** | |[]()|
| **Conocimiento Cero** | Garantiza el anonimato. Si la verificación es verdadera, ningún verificador puede que eso.|[Cointelegraph](https://es.cointelegraph.com/explained/zero-knowledge-testing-zkp-the-state-of-the-art-in-cryptography)|
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

# Contribuciones
.
.
.
