# Mi introducción a Blockchain

En el camino que comencé a recorrer para aprender sobre blockchain, decidí registrar y compartir algunos conceptos para fijar el conocimiento y al mismo tiempo ponerlo disponible para aquellos que les interese el tema.

Comenzaré con una introducción a blockchain y planeo seguir con una serie de artículos que nos permitan profundizar en el tema.

## ¿Qué es blockchain?
Blockchain o cadena de bloques es una base de datos distribuida que funciona como un libro de cuentas para el registro de movimientos o transacciones, de allí surge la denominación de Distributed Ledger Technology (ledger significa libro mayor). Los registros crecen continuamente y tienen la característica de ser inmutables.

La información se guarda en bloques que se unen unos con otros de forma encriptada y cronológica. Al utilizar claves criptográficas y estar distribuido entre muchos ordenadores presenta ventajas en la seguridad frente a manipulaciones y fraudes. Una modificación en una de las copias no serviría de nada, sino que hay que hacer el cambio en todas las copias porque la base es abierta y pública. En otras palabras, todo se resuelve por consenso de las partes siendo esto y la descentralización lo que permite des intermediar ¿Será este el fin de los intermediarios?

## ¿Cómo funciona una blockchain?

Según su diseño original concebido por Satoshi Nakamoto (pseudonimo), se trata de una red peer-to-peer compuesta por clientes y servidores (mineros, que verifican y mantienen la integridad de los registros y del libro mayor).
Los nodos clientes solicitan a los servidores para almacenar las transacciones, cambios en el estado de cualquier registro anterior en el libro mayor. Las transacciones se firman utilizando un esquema de clave publica garantizando su autenticidad y al mismo tiempo asegurando la participación de las partes.

Los servidores se encargan entonces de ingresar la transacción en bloques en el libro mayor (minar), mediante la resolución de acertijos criptográficos, probando así que se comprometieron recursos para tal fin. Este proceso se conoce como prueba de trabajo (proof of work, se abrevia PoW). Esta prueba de trabajo es fácilmente verificable, pero su producción es muy costosa. Existen otros métodos de minado que más adelante pienso mencionar.

Una vez generado el bloque y su PoW, ambos se retrasmiten a los servidores restantes los cuales verificarán su validez. Los bloques aceptados se agregan al libro mayor y el servidor que generó la actualización recibe su recompensa por el trabajo realizado (generalmente en criptomoneda).

Al ser las mismas reglas de aceptación para todos los nodos, la red alcanza el consenso: todos los nodos acuerdan mantener una única copia autenticada del libro mayor.

## ¿Pero qué significa minar?

Como dejé ver anteriormente, los mineros son nodos que participan de la red y se encargan de minar: todas las operaciones que se realizan en la red se van agrupando en bloques, y para validarlas los mineros deben encontrar una especie de clave informática llamada hash. Se trata de fórmulas matemáticas que sintetizan en muy pocos caracteres una gran cantidad de información. No hay dos hash iguales, y no se pueden modificar. Cada bloque cuenta con un hash nuevo y con el hash del bloque inmediatamente anterior. Todo va enlazado, de ahí el porqué de cadena.

Cada vez que un minero encuentra un hash válido (debe reunir una serie de condiciones), recibirá su recompensa en criptomoneda, tras la comprobación de al menos el 51% de los mineros.
Si no quedó claro, el proceso anteriormente expuesto se denomina minar.

## ¿Qué es Bitcoin?

Bitcoin es una red consensuada que permite un nuevo sistema de pago y una moneda completamente digital. Es la primera red entre pares de pago descentralizado impulsado por sus usuarios sin una autoridad central o intermediarios, en otras palabras, se trata de la primera implementación de blockchain que se conoce.

## ¿Qué es Ethereum y qué es Ether?

[Ethereum](https://ethereum.org/) es una plataforma descentralizada que permite la ejecución de contratos inteligentes entre pares. Cualquier desarrollador puede crear y publicar aplicaciones distribuidas que realicen contratos inteligentes.

El [Ether](https://ethereum.org/ether), al igual que el Bitcoin es una criptomoneda y a su vez es el combustible necesario para que las aplicaciones distribuidas operen sobre la plataforma de Ethereum. Ether es el incentivo que promueve que los desarrolladores escriban aplicaciones de calidad (el código con desperdicio consume más Ether) y la red permanezca saludable (los recursos aportados se recompensan con Ether).

## ¿Qué es Solidity?

[Solidity](https://github.com/ethereum/solidity) es un lenguaje de programación orientado a contratos, el cual se utiliza para crear contratos inteligentes en distintas plataformas de blockchain (Ej.: Ethereum).

## ¿Qué es Truffle?

Es un framework de desarrollo para Ethereum el cual permite entre otras cosas compilar, vincular y desplegar contratos inteligentes. Soporta la creación de pruebas automatizadas.

## ¿Cómo armar tu ambiente de desarrollo para crear y probar Smart Contracts?

Esta y otras preguntas las responderé próximamente en nuevas publicaciones.

## Conclusión

Blockchain se presenta como una tecnología claramente disruptiva, la cual está siendo adoptada por diferentes organizaciones con diferentes finalidades. Su impacto claramente trasciende la industria financiera.

Desde su primera implementación ha evolucionado, dando lugar a la aparición de nuevas plataformas entre las cuales, además de Ethereum, podemos nombrar a [Corda](https://www.corda.net/), [Hyperledger](https://www.hyperledger.org/) y [Lisk](https://lisk.io/) como las más resonantes.

Como dicen, no todo lo que brilla es oro, aún quedan cuestiones por mejorar, como por ejemplo la cantidad de transacciones por minuto que dista mucho de lo que se requiere a nivel corporativo y el costo de minar en terminos de consumo energético es elevado también. Blockchain no es la solución a todos los problemas de la humanidad, pero a mi humilde entender, es una clara posibilidad de remover a los intermediarios poniendo ante nosotros una oportunidad de mejora a evaluar e implementar, cosa que muchos de los grandes actores están haciendo.

Próximamente estaré compartiendo mi experiencia al adentrarme en este nuevo paradigma, ya con un enfoque más orientado al desarrollo de software.