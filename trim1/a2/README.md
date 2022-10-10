Jorge Francisco Reyes Castilla

¿Qué niveles OSI son los niveles de soporte de red?
El nivel 1(Fisico); El nivel 2(Enlace), El nivel 3(Red)
¿Qué niveles OSI son los niveles de soporte de usuario?
El nivel 5(Sesion), El nivel 6(Presentación), El nivel 7(aplicación)
¿Cómo están OSI e ISO relacionadas entre sí?
Están relacionados porque ISO es la organización de estándares que creo el modelo de interconexión de sistemas abiertos OSI. 
Enumere los niveles del modelo OSI.
    1. Capa física
    2. Capa de enlace de datos
    3. Capa de red
    4. Capa de transporte
    5. Capa de sesión
    6. Capa de presentación
    7. Capa de aplicación

¿Cómo pasa la información de un nivel OSI al siguiente?
Los datos van de la capa de transporte del emisor y serán allí segmentados. Después, esos segmentos serán divididos en trozos más pequeños, (paquetes) en la capa de red y en trozos aún más pequeños, (tramas) en la capa de enlace de datos. La capa de enlace de datos enviará las tramas a la capa física para que puedan ser convertidas por esta en una secuencia de bits formada por unos y ceros que viajaran a través de un medio físico.
¿Qué son las cabeceras y cola y cómo se añaden y se quitan?
Las cabeceras y las colas son datos de control sumados al comienzo y al final de cada unidad de datos en cada capa del emisor y eliminados en las correspondientes capas del receptor. Las cabeceras y las colas proporcionan las direcciones de origen y destino, puntos de sincronización, información para la detección de errores...etc
¿Cuáles son las responsabilidades del nivel físico?
Proporciona los medios mecánicos eléctricos funcionales y procedimentales para activar mantener y desactivas conexiones físicas para la transmisión de bits
¿Cuáles son las responsabilidades del nivel de enlace?
El nivel de enlace se encarga de detectar corregir los errores que ocurren en el nivel físico y así proporcionar una linea libre de errores de transmisión al nivel de red


¿Cuáles son las responsabilidades del nivel de red?
Se encargar de encaminar los datos hacia su destino estableciendo el camino de transmisión.
¿Cuáles son las responsabilidades del nivel de transporte?
Es el encargado de la transferencia libre de errores de los datos entre el emisor y el receptor aunque no estén directamente conectados así como de mantener el flujo de la red
El nivel de transporte crea una conexión entre el origen y el destino. ¿Cuáles son los tres eventos involucrados en la conexión?
Están involucrados tres elementos el TCP protocolo de control de transmisión el UDP el protocolo de datagramas de usuario y el SCTP Protocolo de transmisión para el control de flujo
¿Cuál es la diferencia entre una dirección de punto en servicio, una dirección lógica y una dirección fisica?
La principal direferencia es que la direcion logica  es creada por la cpu durante la ejecucion del programa mientras que la direccion fisica se refiere a una ubicación en la unidad de memoria
¿Cuáles son las responsabilidades del nivel de sesión?
El nivel de sesión proporciona mecanismos para controlar el dialogo entre las aplicaciones de los sistemas finales
¿Cuáles son las responsabilidades del nivel de presentación?
Garantiza que la información que enviá la capa de aplicación de un sistema pueda ser leída por la capa de aplicación de otro
¿Cuál es el objetivo de la traducción en el nivel de presentación?
Enseña al usuario la información y captura la información del usuario en un mínimo proceso
Indique alguno de los servicios proporcionados por el nivel de aplicación.
Alguno de los servicios son:
Terminal virtual de red
Transferencia acceso y gestión de archivos remotos 
servicios de correo
servicios de directorios 
gestión de base de datos compartidas
¿Cómo se relacionan los niveles de la familia del protocolo TCP/IP con los niveles del modelo OSI?
TCP/IP combina varias capas OSI en una unica capa o no lo utiliza determinadas capas.




El nivel SESIÓN decide la localización de los puntos de sincronización.
    • transporte
    • sesión -
    • presentación
    • aplicación
      
En el nivel RED, la unidad de datos se denomina trama.
                • físico
                • enlace de datos
                • red -
                • transporte
Los servicios de correo y de directorio están disponibles a los usuarios de la red a través del nivel:
                • enlace de datos
                • sesión
                • transporte
                • aplicación -


A medida que los paquetes de datos se mueven de los niveles inferiores a los superiores las cabeceras:
                • añadidas
                • eliminadas -
                • recolocadas
                • modificadas

