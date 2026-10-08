# LISTA DE COMPROBACIÓN DE LA ESCENA

_Al llegar a la escena de un cyber crimen necesitamos seguir unas pautas, en este documento vamos a explicar que es lo que haría yo como analista forense al llegar a la escena._

## Lista:

#### Al llegar:

1. Entraría a la escena preguntando, ¿cual ha sido el problema?.

2. Alejar a todo tipo de persona ajena a la investigación forense es decir, testigos, sospechoso. [ENFSI 8.2](https://enfsi.eu/wp-content/uploads/2016/09/1._forensic_examination_of_digital_technology_0.pdf) 

3. De un vistazo y conociendo la respuesta del punto 1, buscar las fuentes que debemos priorizar. [ENFSI 8.2](https://enfsi.eu/wp-content/uploads/2016/09/1._forensic_examination_of_digital_technology_0.pdf) 

4. Localizar todo tipo de evidencias básicas es decir sobremesas, portátiles, almacenamiento y medios extraibles. [NIST SP 800-86 3.1.1](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-86.pdf)

5. Preguntar sobre los servidores centrales, si tienen un registro de logs o si los tienes ISP, los portátiles que son de la empresa y si se pueden investigar o los que son personales. [NIST SP 800-86 3.1.1](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-86.pdf)

#### Antes de tocar nada:

6. Es necesario que intervengan otras disciplinas (huellas dactilares, ADN). [ENFSI 8.2](https://enfsi.eu/wp-content/uploads/2016/09/1._forensic_examination_of_digital_technology_0.pdf)    

7. Observaremos antes de empezar el estado de los dispositivos, ¿están encendidos? Documentar el estado de cada uno. [ENFSI 9.2](https://enfsi.eu/wp-content/uploads/2016/09/1._forensic_examination_of_digital_technology_0.pdf)

8. ¿Se ha eliminado las vias externas es decir desconectar al equipo de la red, se ha aislado las VLAN? [RFC 3227 3.2](https://www.rfc-editor.org/info/rfc3227/#section-3.2)

9. Hay dispositivos que haya que aplicar las medidas de blindaje como por ejemplo los infrarrojo, RF. [ENFSI 8.2](https://enfsi.eu/wp-content/uploads/2016/09/1._forensic_examination_of_digital_technology_0.pdf)

10. Identificar equipos que puedan ser dañados por descargar electrostáticas (ESD) y con ello aplicaremos el etiquetado anti-ESD. [ENFSI 8.2](https://enfsi.eu/wp-content/uploads/2016/09/1._forensic_examination_of_digital_technology_0.pdf)

11. Podremos hacerlo todo solo o tendremos que recurrir a un tercero de confianza como es un administrador del sistema en vez de hacerlo nosotros y asumir perdidas o fallos. [ENFSI 9.2](https://enfsi.eu/wp-content/uploads/2016/09/1._forensic_examination_of_digital_technology_0.pdf)

#### Al decidir que se adquiere y en qué orden.

12.  ¿Que sistemas estuvieron involucrados? Los involucrados nos lo quedaremos. [RFC 3227 3.2](https://www.rfc-editor.org/info/rfc3227/#section-3.2)
    
13. Todo lo que tengamos que hacer para conseguir datos, ¿merece la pena? [NIST SP 800-86 3.1.1](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-86.pdf)

14. Recoger evidencias basándonos en el orden de volatilidad
    -  Registros, caché

    -  Tabla de enrutamiento, caché ARP, tabla de procesos,      
       estadísticas del núcleo, memoria

    -  Sistemas de archivos temporales

    -  Discos

    -  Datos de registro y supervisión remotos relevantes para el
       sistema en cuestión

    -  Configuración física, topología de red

    -  Medios de archivo

[RFC 3227 2.1](https://www.rfc-editor.org/info/rfc3227/#section-2.1)

15. Necesitamos generar hashes de todas las evidencias adquiridas para establecer la cadena de custodia al instante. [RFC 3227 3.2](https://www.rfc-editor.org/info/rfc3227/#section-3.2)

16. Etiquetado completo de todos los elementos con una referencia única, descripción, donde fue encontrado, su fecha y hora y el responsable de el. [ENFSI 9.2](https://enfsi.eu/wp-content/uploads/2016/09/1._forensic_examination_of_digital_technology_0.pdf)

17. Por ultimo, documentación completa de los testigos y el contexto que estaban haciendo todos los testigos mientras estábamos analizando evidencias. [RFC 3227 3.2](https://www.rfc-editor.org/info/rfc3227/#section-3.2)