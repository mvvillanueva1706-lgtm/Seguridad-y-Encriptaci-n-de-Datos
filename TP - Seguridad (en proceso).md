# Trabajo Práctico: Seguridad
## Parte 1: Cuestionario de Investigación

1. La encriptación en la seguridad informática garantiza que los datos sean confidenciales y protegidos al hacerlos ilegibles.
   
2. **Encriptación en tránsito:** Protege los datos mientras viajan por la red (como por ejemplo: cuando viajan desde la aplicación hasta el servidor de la base de datos). <br> **Encriptación a nivel de columna / campo:** Cifra datos específicos muy sensibles (como contraseñas o números de tarjetas de crédito), mientras que el resto de la información se mantiene normal. <br> **Encriptación a nivel de tabla / espacio de tablas:** Cifra tablas enteras o grupos de archivos dentro del almacenamiento para que nadie pueda leerlos directamente desde el disco. <br> **Encriptación transparente de datos (TDE) / a nivel de disco:** Cifra toda la base de datos automáticamente en el almacenamiento físico para que nadie pueda leerla sin la clave del servidor.

3. **Cifrado simétrico:** Usa una sola clave para cifrar y descifrar información. <br> **Cifrado asimétrico:** Usa dos claves: **1.** Una publica, que es para cifrar y cualquiera puede conocer, **2.** Una privada, que es para descifrar y solo el destinatario debe poseer.

## Parte 2: Línea de Tiempo: Del Cifrado César al AES (Teoría de Classroom)

• **El Origen:** El Cifrado César (Sustitución Simple) Es uno de los métodos más antiguos y simples. Consiste en desplazar un número fijo de posiciones en el alfabeto hacia adelante.Ejemplo: La A se convierte en D, la B en E, la C en F, etc.
• **La Evolución Intermedia:** DES y 3DES (Cifrado Simétrico Moderno) A mediados del siglo XX nacieron algoritmos matemáticos complejos para computadoras, como el DES (Data Encryption Standard). Usaba una clave secreta para mezclar los bits de los datos. Al volverse inseguro por el avance tecnológico, se creó el 3DES (Triple DES), que aplicaba el proceso tres veces.
• **El Estándar Actual (El más avanzado):** AES (Advanced Encryption Standard) Es el algoritmo de cifrado simétrico más seguro y utilizado en el mundo actual (usado por gobiernos, bancos y bases de datos como MySQL, PostgreSQL u Oracle). Utiliza matrices matemáticas complejas y claves de longitudes específicas. Romper una clave AES robusta por fuerza bruta tomaría miles de millones de años con la tecnología actual.
