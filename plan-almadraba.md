# PLAN ALMADRABA

### ENUNCIADO

Almadraba Diseño es un estudio de arquitectura de interiores de Cádiz con catorce personas en plantilla. Ocupa la primera planta de un edificio de oficinas en la avenida principal: una zona abierta con ocho puestos, dos despachos, una sala de reuniones y un cuarto pequeño junto al baño donde está «lo de informática». No tienen departamento de TI. Del mantenimiento se encarga una consultora externa, Bahía Sistemas, que viene un día al mes y el resto lo resuelve en remoto.

El lunes 20 de marzo, a las 9:15, te llama Elena Ruiz, la gerente. Su mejor cliente, una cadena hotelera, le ha enseñado el render de un vestíbulo que el estudio presentó en exclusiva hace dos semanas. Ese render ha aparecido en la propuesta de un estudio de Sevilla que ha abierto hace poco Lucía Navarro, antigua compañera de trabajo.

Elena sospecha de Marta García (cuenta mgarcia), diseñadora sénior que pidió hace diez días una excedencia «por motivos personales» a partir del 1 de abril. Marta y Lucía son amigas: se las ha visto comer juntas varias veces. Elena te firma la autorización y llegas a las 10:30.

---

#### Datos

Desglosamos el enunciado como cuando lo hacíamos en matemáticas:

Un render en exclusiva ha sido filtrado en un estudio de Sevilla que ha abierto Lucia Navarro, ex compañera de trabajo.

Elena, la gerente sospecha de Marta (CUENTA: mgarcia). Amiga de Lucia y ha pedido una excedencia hace 10 días.

Vamos a la empresa y llego a las 10:30

---

### PRIMER VISTAZO

Marta está en su puesto. Te saluda con cierta tensión y sigue trabajando mientras hablas con Elena en el despacho. Cuando vuelves, se ha levantado a por un café y ha dejado el portátil con la pantalla bloqueada. Es un Dell de empresa, conectado a un dock USB-C que alimenta dos monitores, el teclado, el ratón y un disco externo negro de 2 TB. Elena comenta que el portátil «se carga con el cacharro ese», y que Marta lo usa también en casa: «los viernes teletrabaja, se conecta con la VPN que nos montó Bahía».

En la mesa hay un iPhone con la funda del estudio: es el móvil de empresa, que usa para WhatsApp con clientes. Al lado, el bolso de Marta, del que asoma otro móvil. En la pantalla del sobremesa compartido de la entrada, que usa todo el equipo para imprimir y escanear, hay una sesión abierta de Outlook web a nombre de otra compañera.

Mientras esperas, hablas con Javier, el compañero de la mesa de al lado. Te cuenta que el día 14, un jueves, Marta se quedó hasta tarde, «hasta las siete y pico, que es raro en ella». También que esa semana le pidió un pendrive «porque el suyo no le funcionaba», y que se lo devolvió al día siguiente. Javier lo tiene en su cajón.

Llamas a Bahía Sistemas. El técnico, algo sorprendido, te explica que todos los portátiles tienen BitLocker y que las claves de recuperación «están en el portal de Microsoft». Los documentos de los proyectos están en el servidor de ficheros del cuartito y además se sincronizan con OneDrive. El cortafuegos guarda un registro de conexiones, «pero se va pisando, creo que aguanta una semana o así». La copia de seguridad se hace cada noche a un NAS que hay en el mismo cuarto, y se conservan las últimas catorce. La impresora multifunción escanea directamente al correo de quien la usa «y guarda un historial de trabajos, no sé cuánto».

Al salir te fijas en una cámara domo en el techo del pasillo, apuntando hacia la puerta de la oficina. Elena dice que es del edificio, no suya: «la gestiona la administración de la comunidad, creo que graba en un aparato en conserjería».

Cuando vuelves al puesto, Marta ha regresado. Pregunta, con educación, si va a poder seguir trabajando o si se puede ir a casa, y añade que en el móvil personal «no hay nada del trabajo».

---

### BÚSQUEDA DE EVIDENCIAS Y EXPLICACIÓN.  

1. Las fuentes de evidencia. Haz el inventario de todo lo que puede contener información sobre lo ocurrido, tanto lo que está en la mesa de Marta como lo que está en otros sitios, en otras manos o en la nube. Del relato se deduce más de lo que se ve a primera vista.

2. La prioridad. Ordena esas fuentes según lo que antes se va a perder y explica por qué. No pienses solo en la memoria RAM: también caducan otras cosas.

3. Las medidas inmediatas. Para cada fuente, qué harías ahora mismo para que no se pierda ni se altere: no apagar, aislar, fotografiar, pedir que se conserven unos registros, solicitar algo a un tercero…

4. Los límites. Qué no puedes tocar o no puedes tocar todavía, por qué, y qué harías en su lugar.

5. De dónde sale cada decisión. Indica qué punto de tu lista de comprobación, y por tanto qué norma, te llevó a cada una.

----

#### 1. Fuentes De Evidencia:

Portátil Dell. 
Disco externo negro de 2TB 
Impresora para ver que ha imprimido Marta
Sobremesa impresora.
Pendrive Javi
Registro de conexiones a la red, cortafuegos.
Cámara de seguridad
Onedrive
Portal Microsoft
Copias de seguridad en un NAS 14 Dias
Movil empresa.

#### 2. Prioridad:

Logs del cortafuegos, el técnico de Bahia Sistemas nos ha comentado que duran una semana o asi, asi que hay que proceder.

Portátil Dell, la memoria ram hay que ponerla a salvo.

Sobremesa compartido para imprimir y escanear, ram también.

Iphone de empresa.

Mirar cámaras de grabación, ya que se van borrando con el paso de los Dias las ultimas grabaciones

Por ultimo seria todo lo demás, disco duro de 2TB, el pendrive de Javi, el portal de Microsoft, las copias de seguridad en el NAS

#### 3. Medidas Inmediatas

El portátil Dell no se puede apagar, lo desconectaremos de la red y procedemos a hacerlo un volcado de datos a nivel de bits y calcularemos el hash para que asi las pruebas tenga validez judicial.

Tendremos que hablar con Bahia Sistemas para que nos faciliten las copias de seguridad del NAS, los logs por conexión a la red y como consejo que marta desde su casa no pueda hacer nada, desactivando el punto de acceso.

El iphone de empresa deberemos de desconectarlo de la red poniéndolo en modo avión.

El disco y pen drive tendremos que hacerle una copia a nivel de bits y calcularemos de nuevo el hash.

PC compartido y impresora, salvar la RAM, desconectar de la red y volcado de datos a nivel de bits junto a calculo del hash.

Camara de vigilancias, tendremos que pedirle a la comunidad el acceso a las camaras, para ellos hablaremos con Elena.

#### 4. Limites

Son cosas fáciles pero que hay que tener en cuenta por si no nos damos cuenta y meternos en un lio legal, el Movil personal que vimos sobresaliendo en el bolso de Marta no podemos ni mirarlo ni tocarlo, es un objeto suyo personal que solo podremos acceder a el si la empresa mete de por medio un juez y este ordena que se pueda hacer un analisis.

Las cámaras como nos ha comentado Elena son de la comunidad es decir, no podemos ir al libre albedrío y gestionarlas nosotros, antes debemos pedir permiso.

Tampoco podemos obligar nosotros a Marta a nada, en cualquier caso hablar con Elena.

#### 5. Justificación basada en la Lista de Comprobación.

En el punto 3 y 4 de mi lista de comprobación indicamos lo que viene siendo identificar equipos y todo tiempo de evidencias en realidad.

En el punto 5 y 11, indicamos que hay que pedir el registro de los logs y preguntar sobre las copias de seguridad, donde se almacenan y todo y en el otro punto indicamos que si necesitamos ayuda de terceros y pensar si la necesitamos.

Punto 7 documentar estado de los dispositivos, están encendidos, tienen bitlocker.

Punto 8, desconectar todos los dispositivos de la red. 

Punto 14, seguir el orden de volatilidad.

Punto 15 y 16, generar hashes de todo los volcados que realicemos como también el etiquetado de todos los dispositivos.