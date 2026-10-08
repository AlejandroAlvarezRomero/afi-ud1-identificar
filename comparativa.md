# TABLA COMPARATIVA

## Introducción

En esta primera parte del trabajo, realizaremos una tabla y en ella compararemos textos de referencia de libre acceso, son la RFCC 3227, la guía NIST SP 800-86 y el manual de buenas prácticas de ENFSI.



| Textos de referencia | ¿Qué identifica? | ¿Qué fuentes de evidencia se mencionan? | ¿Qué criterio propone para decidir qué proteger primero? |
|---|---|---|---|
| RFC3227 | Al llegar al lugar, localizaremos los sistemas que estuvieron involucrados en el incidente y los que son verdaderamente importantes. Luego obtendremos el orden de volatilidad para cada sistema y también identificaremos a las personas involucradas. | Memoria RAM, registros, caché, tabla de procesos, discos duros y metadatos. Indica que tengamos cuidado con el cambio de los metadatos y hace hincapié en los sistemas de memoria volátiles. | El criterio indicado es simplemente proteger o asegurar lo volátil es decir lo que podemos perder, por ello habla del orden de volatilidad, por donde debemos empezar y por donde acabar. |
| NIST SP 800-86 | Fuentes de evidencia, equipos principales, almacenamiento externo y medios, datos volátiles de cada equipo y dispositivos móviles y multimedia como cámaras y grabadoras. | Equipos principales, ordenadores, portátiles, NAS, dispositivos de almacenamiento, todo lo que haya es importante, datos volatiles, dispositivos móviles y multimedia, tables, cámaras...  | Como indica el apartado de recolección de datos sección 3.1.3, el criterio que seguiremos sera si el valor de los datos nos compensa todo lo que tengamos que hacer para conseguirlos o si hay que paralizar por ejemplo a la empresa. |
| MBP de ENFSI | Identificaremos todo tipo de pruebas junto a las configuraciones de cada dispositivo y de la red, además de otras disciplinas forenses, como huellas dactilares y ADN. | Ademas de todas las evidencias normales, se indica también los equipos que sean capaces de comunicarse fuera de las bandas de RF (Radio Frecuencia) y que hay que hacer fotos y capturas de pantallas y los datos físicos y lógicos.| Nos indica que evitemos posible contaminaciones o destrucción de datos alejando a sospechosos o testigos de las pruebas, hay que tomar medidas anti-ESD para que una prueba no sufra, hay que tener cuidado con la incautación de equipos conectados a una red de radiofrecuencia. Y tener cuidado con el acceso remoto, como también la perdida de batería de un dispositivo que se quede encendido. |  
---  
### Y, ¿Cuales son sus similitudes o diferencias?  

  >Coincidencias

Viendo las 3 diría que en lo que mas coinciden es tener siempre el dispositivo encendido, en ninguno de los casos apagadlos, como también la memoria volátil hay que acordarse de ella es decir que siempre esta ahi y es de las cosas mas importantes como también asegurar los datos.

>Diferencias 

Como hemos comentado a que le dan prioridad para asegurar, por ejemplo la RFC 3227 es directa, fuente de evidencias identificarlas y asegurar al momento la memoria volátil siguiendo el orden, en cambio la guía NIST SP 800-86 nos comenta que busca el coste o el tiempo que conlleva conseguir una prueba si realmente merece la pena y ENFSI es como mas técnico vamos a decir tienes que ir preparado de antes (no significa que las otras guías vayas como un pollo sin cabeza) en el sentido de que cualquier imprevisto sea solucionado eficazmente, es como la policía, alejan a las personas, testigos, sospechosos de las pruebas del crimen para que no cambie nada de la escena.

