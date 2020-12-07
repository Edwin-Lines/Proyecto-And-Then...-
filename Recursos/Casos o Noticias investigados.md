# Casos reales a usar
- Aquí pueden pegar la información sobre los casos que hayan buscado.
- Poner el nombre de empresa o persona que le sucedió.
- Dar pequeño resumen de lo sucedido o el contexto donde ocurrió

## Caso 1 - Agencia de la NASA
* El sistema de control de la nave en la Tierra usaba el sistema métrico anglosajón mientras que el sistema de navegación de la nave esperaba valores en el sistema métrico decimal; tras cada encendido de motores y por los parámetros de movimiento incorrectos tras el uso de diferentes unidades de medida, la trayectoria de la nave se acercó  demasiado a Marte y acabó desintegrada por la fuerza de fricción atmosférica del planeta.

* En este caso, el error tuvo su origen en el incumplimiento de los requisitos del sistema que especificaba que todo el software debía usar el sistema métrico decimal. Muy buen ejemplo de la importancia de cumplir (y testear) que la implementación del software cumple con su especificación.

## Caso 2 - Empresa Toyota
* El problema consiste en que, en caso de una aceleración fuerte, puede sobrecargarse el sistema de control híbrido, por lo que se iluminan señales de advertencia y se activa un programa de emergencia con una potencia reducida; aunque en el mundo ya hubo 400 incidentes de este tipo, no se reportaron ni accidentes ni heridos.

* Explicación técnica por parte de la compañía reparó en que la falla se hallaba en el software usado para controlar el convertidor "boost" en un módulo que forma parte del sistema híbrido.

## Caso 3 - Error sucedido en España
* Millones de ordenadores en el mundo no pudieran procesar los dígitos del año 2000 o el nuevo milenio, esto sucedió debido a un bug en la programación de las fechas en los sistemas informáticos.

* Se utilizaban dos dígitos al indicar el día, el mes y el año, y en este último apartado, los sistemas siempre asumían que el año pertenecía al siglo XX, siendo que si se incluía allí "98", el sistema sabía que se estaba haciendo referencia a 1998; al llegar el año 2000, los ordenadores lo representaron como al año 1900.

## Caso 4 - Amazon (2017)
* EL martes 28 de febrero de 2017 internet registró uno de esos grandes fallos que terminó afectando gran parte de las webs, 
    servicios y aplicaciones que usamos diariamente. Esto se debió a una caída del servicio S3 (Simple Storage Service) de Amazon Web Services (AWS), 
    uno de los más grandes de internet y donde compañías como Hootsuite, Twitch, Airbnb, Giphy, Trello, IFTTT, y otras más están alojadas.
    Un miembro autorizado del equipo ejecutó un comando de acuerdo a lo establecido en el manual, desafortunadamente, 
    una de las entradas del comando se ingresó de forma errónea y terminó deshabilitando un conjunto de servidores más grande de lo previsto.
    
## Caso 5 - AT&T (1990)
* La empresa AT&T perdió unos $60 millones de dólares al dejar aproximadamente a 60.000 clientes sin comunicación en llamadas de larga distancia. 
    El motivo de esta caída fue debido a los interruptores que se reseteaban cada pocos segundos debido a un fallo en una actualización del software. 
    Este fallo provocaba una caida cascada entre los diferentes interruptores.
  
## Caso 6 - American Airlines (2013)
* En 2013, un error de programación provocó el caos en la compañía de aviación American Airlines. 
    La unión de dos sistemas como resultado de la fusión de varias compañías aéreas originó un fallo en el sistema de reserva de pasajes.
    
## Caso 7 - Problema de software Knight Capital (2013)
* En 2013, un fracaso del programa casi llevó a la compañía de inversión Knight Capital a la bancarrota. La firma perdió medio billón de dólares en media hora porque las computadoras comenzaron a comprar y vender millones de acciones sin ningún control humano. Como resultado, los precios de las acciones de la compañía cayeron un 75% en dos días.

* El problema fue causado por una actualización que no llegó a todos los sistemas informáticos, dejando algunos sistemas funcionando con código antiguo;a finales de Julio del 2012, Knight desplegó su nuevo código RLP progresivamente en un número limitado de servidores SMARS durante varios días. Sin embargo, durante este despliegue uno de los técnicos de Knight olvidó copiar el código nuevo en uno de los servidores SMARS. Knight no tenía procesos de revisión para estos despliegues, así que nadie se percató de que uno de los servidores no estaba actualizado como debía.

* El 1 de agosto del mismo año, Knight recibió órdenes de sus brokers para empezar a participar en el RLP. Los siete servidores con el código nuevo procesaban las órdenes correctamente, pero había uno que aún mantenía el código antiguo. Como resultado, el servidor no actualizado comenzaba a enviar sin parar órdenes hijo por cada orden padre recibida a ciertos centros de trading para su ejecución sin tener en cuenta el número de ejecuciones ya realizadas; Knight ejecutó 4 millones de operaciones en 154 stocks por más de 397 millones de acciones en aproximadamente 45 minutos (la continua compra/venta devaluó las acciones), lo que conllevó unas pérdidas estimadas en 460 millones de dólares.

## Caso 8 - Explosión de ariane en 1996
* El 4 de junio de 1996, el cohete Ariane 5 lanzado por la Agencia Espacial Europea estalló 38 segundos después de su despegue desde Kourou tras una década de desarrollo, y las pérdidas se estimaron en 500 millones de dólares; la causa de la explosión fue un error en el software, un error no detectado por falta de control de la calidad del software crítico del cohete.
* Todo sucedió porque un número real de 64 bits (coma flotante) relacionado con la velocidad horizontal del cohete se convirtió en un entero de 16 bits.

## Caso 9 - La catástrofe del Hartford Coliseum
* Sólo unas horas después de que miles de aficionados al hockey abandonaran el Hartford Coliseum, la estructura de acero de su techo se desplomaba debido al peso de la nieve.

* El desarrollador del software de diseño asistido (CAD) utilizado para diseñar el coliseo asumió incorrectamente que los soportes de acero del techo sólo debían aguantar la compresión de la propia estructura; sin embargo, cuando uno de estos soportes se dobló debido al peso de la nieve, inició una reacción en cadena que hizo caer a las demás secciones del techo como si se tratara de piezas de dominó.

## Caso 10 - Therac-25, un caso dramático
* Therac-25 era una máquina de radioterapia, producida por la empresa estatal canadiense de energía nuclear, que fue la causante directa de la muerte de, al menos, 
    tres pacientes entre 1985 y 1987 a los que se suministró sobredosis masivas de radicación.
* La comisión investigadora concluyó que la razón de estos accidentes podía atribuirse a malas prácticas en desarrollo, mal análisis en los requerimientos y un mal diseño del software, al ser que el código fuente no habia sido revisado de forma independiente.

