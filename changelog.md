# Changelog Fleur Roleplay SA:MP
Todos los cambios notables a este proyecto se documentarán en este archivo.

Contamos con una [web](https://fleur-roleplay.es) para que obtengas más información sobre nosotros, puedes visitarnos en [nuestro discord](https://discord.gg/erCaR7q).

## [Versiones publicadas]

## [1.0.5] - 16/02/2020

- Se cambio la versión del servidor a [SA:MP 0.3.DL](https://forum.sa-mp.com/showthread.php?t=648633).
- Seteadas las coordenadas de las gasolineras de Red County en la gamemode.
- Ahora al rellenar gasolina te mandara una factura el servidor.
- Ahora al revisar a alguien si tienes mas de 800 dólares no saldrá la cantidad exacta a la hora de ser revisado.
- Se comienza con el desarrollo del velocímetro 3D aprovechando la versión 0.3.DL. (no implementado aun hasta la versión 1.1.0)
- Cambiado el hostname del servidor por la nueva versión.
- Fixeados algunos bugs con el sistema de heridas, los headshots no los reconocía.
- Se agrego una función al sistema de muebles, ahora los puedes clonar y editar mas rápido.
- Se editó toda la tabla de precios de vehículos a la venta.
- Ahora al llegar a nivel 1 recibirás una recompensa extra.
- Ahora en cada payday se cobraran intereses los cuales serán seteados por el líder de la alcaldía.
- Creados algunos textos 3D en el servidor. (newsdisplay)
- Fixeado algunos bugs de textdraws con la resolución de la pantalla de los jugadores.
- Terminada la función TIMER_HideTextdraw y resueltos sus bugs.
- Mejorar la vista previa de /muebles y los diálogos del sistema entero.
- Se acomodo la cabecera de la gamemode y su organización de cada modulo.
- Ahora los niveles 0 no podrán portar armas por restricción.
- Creado un comando administrativo para dar permiso de portar armas a jugadores con nivel 0.
- Terminado los textos informativos del tutorial de inicio.


## [1.0.4] - 08/02/2020

- Modificado el tiempo de logeo, de 60 segundos a 120 segundos.
- Cambiado el lugar de spawn del servidor.
- Arregladas algunas funciones del anticheat.
- Aumentado el tiempo de uso del /reaparecer.
- Agregado un mensaje informativo con los comandos disponibles dentro de cada negocio.
- Modificadas las estadísticas iniciales en las nuevas cuentas.
- Terminado el comando /balance para dentro de algunos negocios.
- Se agregó un sistema de cadáveres básico.
- Ahora cada cadaver desaparecerá despues de 5 minutos.
- Ahora cada log administrativo tendrá una ID única para identificarlo mejor.
- Optimizada la gamemode a la hora de ser encendido el servidor.
- Se comienza a crear el artconfig.txt por si en un futuro nos pasamos a 0.3.DL.
- Fixeado un buf del comando /mutearb.
- Ahora los reportes del servidor y dudas llegaran a discord.
- Terminado el comando /discord.
- Terminadas las funciones para mapname.



## [1.0.3] - 25/01/2020

- Se agregó el infernus al catalogo de vehículos para comprar.
- Agregado un diálogo de confirmación antes de enviar un MP a un staff duty.
- Agregado un diálogo de confirmación antes de enviar un reporte.
- Fixeado un bug del comando /log para la administración.
- Fixeado un error en la carga de vehículos que ocasionaba que los últimos vehículos comprados no aparecieran ni respondieran en el servidor.
- Removidos algunos mapeos sin uso de Los Santos.
- Re modificada la función de sacar vehículos.
- Creado el comando /mutearb para bloquear el uso del /b a un jugador.
- Terminado el /reportes, agregada información de hace cuantos minutos se envió el reporte.
- Terminado de traducir la mayor parte de la gamemode.
- Arreglados algunos bugs del procesamiento de la base de datos.
- Creado el comando /cambiar hora y /cambiar clima para el staff.
- Removidos 5 semáforos de Dillmore.
- Fixeado un bug del /setplaca para el líder de la SD.
- Limpiado el GM de códigos inútiles que lo sobrecargaban.
- Arreglados e insertados parkings para vehículos.
- Bug del hospital de Montgomery solucionado.



## [1.0.2] - 18/01/2020

- Se agregaron mas de nuevas 15 drogas al servidor.
- Ahora la droga depende el tipo se puede empaquetar.
- Los paquetes de la droga se podrán guardar en propiedades y vehículos.
- Creado un comando para la sheriff, podrá revisar el interior de un paquete.
- Se agregaron 3 membresías al servidor. (bronce, plata y oro)
- Agregadas 6 partes nuevas del cuerpo. (para el sistema de heridas)
- Fixeados algunos errores de sincronización a la hora de un tiroteo.
- Ahora un staff si espectea a alguien podrá ver toda la información en un textdraw.
- Aumentada la distancia de dibujado en los mapeos de Montgomery.
- Removidos 4 semáforos nuevos en Montgomery.
- Fixeado un error del sistema de heridas.
- Agregadas nuevas columnas a la base de datos.
- Agregado un /ayuda solo para usuarios premium.
- Removidos 6 semaforos en Palomino Creek.
- Fixeado un error visual en el velocímetro.
- Arreglados algunos callbacks del MDC policial.
- Agregados más de 800 objetos nuevos por todo Palomino Creek decorando y dando el entorno correspondiente.
- Divididos los mapeos de la gamemode por módulos.
- Ahora el /reaparecer solo se puede usar cuando pasen 120 segundos de tu estado de muerte.



## [1.0.1] - 06/01/2020

- Ahora el dueño de una propiedad puede contratar a un amueblador (mapper) para editar los muebles de su casa, el dueño podrá retirar dicho permiso con un comando.
- Agregado un comando para el staff, ahora podrán ver todo el historial de sanciones, kicks y baneos dentro del servidor.
- Ahora cada cuenta tendrá una DBID. (una ID única por cuenta, no se podrá cambiar)
- Ahora los reportes de los jugadores se categorizan por prioridad para el staff.
- Removida la restricción de solo poder tener un coche activo.
- Ahora los coches al desconectar un jugador se quedaran en el servidor.
- Agregado un limite, solo puedes retirar máximo 5 mil dolares por payday en el banco.
- Ahora un jugador podrá solicitar un cambio de nombre ingame vía comando.
- Creados dos comandos para el staff, podrán rechazar o aceptar el cambio de nombre de un jugador.
- Agregado un dialogo de advertencia a la hora de cambiar un nombre.
- Ahora los desarrolladores podrán desactivar o activar el anticheat de armas y munición dentro del servidor. (por default está activado)
- Ahora si estas encarcelado ingame podrás usar /qcondena para salir de prisión si tu tiempo termino.
- Re modificado el dialogo del MDC. (https://i.imgur.com/GUPkMAL.png)
- Agregado un anti gbug para evitar que la gente se suba a vehículos mientras están muertos.
- Re modificados los comandos básicos de rol. 
- Se agregaron once categorías en los concesionarios.
- Más de 300 muebles nuevos para el sistema de amueblar.
- Ahora si tu estado es "MUERTO" no podrás escribir por el chat normal.



## [1.0.0] - 02/01/2020

- Agregado un mensaje informativo al conectar y detectar si un jugador fue sancionado. (ej: El staff Mugsy te sancionó mientras no estabas en el servidor, 30 minutos por hermoso.)
- Se creó una base para conectar el servidor SA:MP al servidor Discord. De esta forma el staff podrán interactuar con los jugadores sin necesidad de estar conectados en el juego.
- Ahora podrás entrar a un restaurante de comida, comprar tu comida y deberas llevar la bandeja a la mesa, acomodarla y comer. (todo por sistema y comandos)
- Agregado el comando /st para hablar por bajo en teléfono. (formato en chat: Nombre_Apellido dice por teléfono en bajo: Hola)
- Se fixearon errores críticos de la base de datos.
- Creado el comando /mismultas donde podrás ver en un dialogo la lista de tus multas.
- Creado el comando /pagarmulta para poder pagar la multa según la ID de la mismas.
- Se agregó una función de poder imprimir la información de la multa en el chat.
- Removidos 7 semaforos en Montgomery y agregadas señales de tráfico.
- Terminado el comando /staff para consultar la administración en linea.
- Agregadas nuevas camaras de inicio del servidor.
- Mejorado el registro de los pasos del login de cada jugador en el server_log.
- Agregados mapeos en las granjas mas importantes de Red County.
- Terminado el menú del comando /mdc. Ahora contiene más funciones que la gamemode base.
- Agregadas todas las señales de las calles en todo Red County.
- Fixeado los bugs de la gamemode base.
- Fixeado un bug grave que no guardaba el dinero al logear.
- Ahora podrás llamar al 788 y reportar un vehículo como robado con su matricula. (llegara un aviso a SD)
- Ahora los lideres podrán setear una placa a un miembro. (/setplaca)
- Los miembros de facción ahora podrán enseñar su /placa o mirarla.
- Se crearon 15 módulos nuevos para dividir comandos y sistemas
- Editados los textlabels de las propiedades en venta.
- Se comienza con el comando /soporte para la versión próxima.
- Ahora podrás colocar música dentro de propiedades.
- Cambiado el máximo de muebles por propiedad, antes eran 200 muebles ahora son 400 muebles.
- Agregados nuevos valores informativos para el /cuenta.
- Eliminado el sistema por completo de IRC y sus comandos.
- Creado el comando /ayudantes para ver los ayudantes online.
- Agregados más de 30 parámetros informativos para el /acocheinfo.
- Creado el comando /mappers para ver los mappers online.
- Separados todos los news en módulos de la gamemode.
- Ahora los vehículos se podrán asegurar, si tienes un vehículo sin seguro los sheriffs podrán multarte.
- Se terminó el sistema de teléfonos de prepago. (temporales)
- Cambiados los precios de los negocios para comprar dentro.
- Se agregó el comando /interiores para el staff.
- Aumentadas las pagas de los trabajos principales de la gamemode.
- Terminado el /sir para la sheriff y fire department.
