# Challenge semana 1

![Azure_Logo](https://user-images.githubusercontent.com/83623695/117381668-3611c000-aea2-11eb-9f91-a6a6fbb89962.png)

-[Microsoft Azure](https://azure.microsoft.com/es-mx/overview/what-is-azure/?&ef_id=Cj0KCQjwp86EBhD7ARIsAFkgakh1Y5FeWz8VT8ndJxxvrp5fhm-FVXO7KxPm_4SvCwHoqB6zffl_1NwaAmnWEALw_wcB:G:s&OCID=AID2100073_SEM_Cj0KCQjwp86EBhD7ARIsAFkgakh1Y5FeWz8VT8ndJxxvrp5fhm-FVXO7KxPm_4SvCwHoqB6zffl_1NwaAmnWEALw_wcB:G:s&gclid=Cj0KCQjwp86EBhD7ARIsAFkgakh1Y5FeWz8VT8ndJxxvrp5fhm-FVXO7KxPm_4SvCwHoqB6zffl_1NwaAmnWEALw_wcB)


## ¿Qué es la nube?

![nube](/images/nube.jpg)

La nube es el nombre que le damos a una red de servidores que estan por todo el mundo, cada uno con una función específica. Es también un medio para el procesamiento y almacenamiento de información del usuario. Existen múltiples servicios, algunos de manera gratuita y otro de pago. Busca principalmente el acceso inmediato y en cualquier lugar a la información.

> ### Tipos de Nube

Existen varios modelos de implementación que normalmente se conocen como tipos de nube o de computación en la nube. Anteriormente estos modelos solo se separaban en dos pero se fueron añadiendo otros tipos que no son mas que la combinación de los primeros dos modelos.

#### 1. Nube Pública

Es la más común y es la que ofrece recursos de baja demanda y de manera inmediata a través de internet. Todo lo que tiene que ver con la infraestructura física es propiedad del proveedor del servicio, quien es encargado del mantenimiento y administración. Se puede implementar cualquier aplicación. 

AWS y Google Cloud Platform son algunos ejemplos de nube pública.

#### 2. Nube privada

Ya que muchas empresas no se confíaban de que un proveedor de servicios tuviera el control de la infraestructura a utilizar, existe el sector privado para la nube, donde está compuesto por recursos utilizados únicamente por una institución, la infraestructura siempre se mantiene en una red privada, y tanto el hardware como el software es dedicado solo para la organización.

Aclarando qu eno es lo mismo que una infraestructura local, debe cumplir con ciertas características de computación en la nube. OpenStack, OpenNebula y CloudStack son alternativas de código abierto.

#### 3. Nube Híbrida

Es la composición de los dos modelos de computación en la nube anteriormente mencionados. Dónde se pretende combinar los estos dos modelos obteniendo lo mejor de ambos. 

#### 4. Multicloud

Es la combinación de dos o más implementaciones de nube del mismo tipo ya sea pública o privada. Por ello es posible combinar servicios de distintos proveedores de nube.

> ### Servicios de la Computación en la Nube

![servicios_nube](/images/servicios_nube.jpg)

Además de los tipos de computación en la nube, existen los llamados modelos de servicio de computación en la nube que permiten elegir ya sea la flexibilidad, administración de la información y el nivel de control. Siendo los siguientes:

<table>
    <tr>
        <th><strong>IaaS</strong></th>
        <th><strong>PaaS</strong></th>
        <th><strong>SaaS</strong></th>
    </tr>
    <tr>
        <td> <strong>Infraestructura como servicio o Infraestructure as a service por sus siglas en inglés (IaaS)</strong> es utilizado por administradores de sistemas. En este servicio se proporcionan recursos necesarios, redes, servidores, almacenamiento y firewalls todo en modo de servicio. <br> Como cliente tienes un control de la información mayor ya que puedes realizar acciones como implementar y ejecutar software de acuerdo a tus necesidades. A partir de la capa de virtualización eres dueño de todo, teniendo control del sistema operativo, almacenamiento y aplicaciones.</td>
        <td> <strong>Plataforma como servicio o Platform as a service por sus siglas en inglés (PaaS)</strong> es utilizado de manera principal para desarrolladores de software. Aquí el proveedor maneja ya el sistema operativo, los lenguajes de programación, librerías y herramientas. Es una plataforma escalable y muy completa, donde el desarrollador solo se preocupa por el código de la aplicación. <br> Se debe de tomar en cuenta que aquí no se gestiona lo mismo que el servicio anterior, aquí se tiene control sobre las aplicaciones implementadas y algunos casos configuraciones del entorno.</td>
        <td><strong> Software como servicio o Software as a service por sus siglas en inglés (SaaS) </strong> es el tipo de servicio donde un producto de proporciona de manera completa, se ofrece a través de un proveedor quien es el encargado de la administración. Aquí no existe la preocupación de la infraestructura ni el como se mantiene el servicio, simplemente se debe de consumir el servicio por lo que la única labor es aprender a utilizarlo. Este tipo de aplicaciones son accesibles a través de internet y en cualquier dispositivo usando un navegador web. </td>
    </tr>
</table>

# Servicios de Azure
![Servicios Azure](https://docs.microsoft.com/es-es/learn/azure-fundamentals/intro-to-azure-fundamentals/media/azure-services.png#lightbox)

> ### Proceso
Los servicios de proceso a menudo son una de las razones principales de por qué las compañías se cambian a la plataforma Azure. Azure proporciona una amplia gama de opciones para hospedar aplicaciones y servicios. Estos son algunos ejemplos de servicios de proceso en Azure.

<table>
    <tr>
        <th><strong>Nombre del servicio</strong></th> <th><strong>Función del servicio</strong></th>
    </tr>
    <tr>
        <td>Azure Virtual Machines</td>	<td>Máquinas virtuales (VM) Windows o Linux hospedadas en Azure.</td>
    </tr>
    <tr>
        <td>Azure Virtual Machine Scale Sets</td> <td>Escalado de máquinas virtuales Windows o Linux hospedadas en Azure.</td>
    </tr>
    <tr>
        <td>Azure Kubernetes Service</td> <td>Administración de clústeres para máquinas virtuales que ejecutan servicios en contenedores.</td>
    </tr>
    <tr>
        <td>Azure Service Fabric</td> <td>Plataforma de sistemas distribuidos que se ejecuta en Azure o en el entorno local.</td>
    </tr>
    <tr>
        <td>Azure Batch</td> <td>Servicio administrado para aplicaciones informáticas de alto rendimiento y paralelas.</td>
    </tr>
     <tr>
        <td>Azure Container Instances</td> <td>Aplicaciones en contenedores que se ejecutan en Azure sin necesidad de aprovisionar servidores ni máquinas virtuales.</td>
    </tr>
    <tr>
        <td>Azure Functions</td> <td>Un servicio de procesos sin servidor y controlado por eventos</td>
    </tr>
        </table>
        
> ### Redes
La vinculación de recursos de proceso y el suministro de acceso a las aplicaciones es la función clave de la red de Azure. La funcionalidad de red de Azure incluye una gama de opciones para conectar el mundo exterior a servicios y características de los centros de datos globales de Azure.

Estos son algunos ejemplos de los servicios de red de Azure.

<table>
    <tr>
        <th><strong>Nombre del servicio</strong></th> <th><strong>Función del servicio</strong></th>
    </tr>
    <tr>
        <td>Azure Virtual Network</td> <td>Conecta máquinas virtuales a conexiones de red privada virtual (VPN) entrantes.</td>
    </tr>
    <tr>
        <td>Azure Load Balancer</td> <td>Equilibra las conexiones entrantes y salientes a aplicaciones o puntos de conexión de servicio.</td>
    </tr>
    <tr>
        <td>Azure Application Gateway</td> <td>Optimiza la entrega de granjas de servidores de aplicaciones y, al mismo tiempo, aumenta la seguridad de las aplicaciones.</td>
    </tr>
    <tr>
        <td>Azure VPN Gateway</td> <td>Accede a redes de Azure Virtual Network mediante puertas de enlace de VPN de alto rendimiento.</td>
    </tr>
    <tr>
        <td>Azure DNS</td> <td>Proporciona respuestas DNS ultrarrápidas y disponibilidad de dominio extremadamente alta.</td>
    </tr>
    <tr>
        <td>Azure Content Delivery Network</td> <td>Entrega contenido de gran ancho de banda a los clientes globalmente.</td>
    </tr>
    <tr>
        <td>Azure DDoS Protection</td> <td>Protege las aplicaciones hospedadas en Azure frente a ataques por denegación de servicio distribuido (DDoS).</td>
    </tr>
    <tr>
        <td>Azure Traffic Manager</td> <td>Distribuye el tráfico de red entre las regiones de Azure en todo el mundo.</td>
    </tr>
    <tr>
        <td>Azure ExpressRoute</td> <td>Se conecta a Azure mediante conexiones seguras de gran ancho de banda dedicadas.</td>
    </tr>
    <tr>
        <td>Azure Network Watcher</td> <td>Supervisa y diagnostica problemas de red mediante el análisis basado en el escenario.</td>
    </tr>
    <tr>
        <td>Azure Firewall</td> <td>Implementa un firewall de alta seguridad y alta disponibilidad con escalabilidad ilimitada.</td>
    </tr>
    <tr>
        <td>Azure Virtual WAN</td> <td>Crea una red de área extensa (WAN) unificada que conecta sitios locales y remotos.</td>
    </tr>
</table>	
	
> ### Almacenamiento
Azure proporciona cuatro tipos principales de servicios de almacenamiento.

<table>
    <tr>
        <th><strong>Nombre del servicio</strong></th> <th><strong>Función del servicio</strong></th>
    </tr>
    <tr>
        <td>Azure Blob Storage</td> <td>Servicio de almacenamiento para objetos muy grandes, como archivos de vídeo o mapas de bits.</td>
    </tr>
    <tr>
        <td>Azure File storage</td> <td>Recursos compartidos de archivos que puede administrar como un servidor de archivos y acceder a ellos del mismo modo.</td>
    </tr>
    <tr>
        <td>Azure Queue Storage</td> <td>Almacén de datos para la puesta en cola y la entrega confiable de mensajes entre aplicaciones.</td>
    </tr>
    <tr>
        <td>Azure Table storage</td> <td>Table Storage es un servicio que almacena datos estructurados no relacionales (también conocidos como datos NoSQL estructurados) en la nube, lo que proporciona un almacén de claves y atributos con un diseño sin esquema.
</td>
    </tr>
</table>
 
Todos estos servicios comparten varias características:

* Durabilidad y alta disponibilidad con redundancia y la replicación.
* Seguridad mediante el cifrado automático y control de acceso basado en rol.
* Escalabilidad con un almacenamiento prácticamente ilimitado.
* Administración y control del mantenimiento y de cualquier problema crítico que pueda surgir.
* Accesibilidad desde cualquier parte del mundo a través de HTTP o HTTPS.

> ### Móvil
Con Azure, los desarrolladores pueden crear servicios de back-end móviles para aplicaciones iOS, Android y Windows de forma rápida y sencilla. Las características que solían tardar tiempo y aumentaban los riesgos del proyecto, como la incorporación del inicio de sesión corporativo y la posterior conexión a recursos locales como SAP, Oracle, SQL Server y SharePoint, ahora se incluyen con facilidad.

Estas son otras características de este servicio:

* Sincronización de datos sin conexión.
* Conectividad a datos locales.
* Difusión de notificaciones de inserción.
* Escalado automático para satisfacer las necesidades del negocio.

> ### Bases de datos
Azure proporciona varios servicios de base de datos para almacenar una gran variedad de volúmenes y tipos de datos. Y con la conectividad global, los usuarios disponen de estos datos al instante.

TABLA 4
Nombre del servicio	Función del servicio
Azure Cosmos DB	Base de datos distribuida globalmente que admite opciones NoSQL.
Azure SQL Database	Base de datos relacional totalmente administrada con escalado automático, inteligencia integral y seguridad sólida.
Azure Database for MySQL	Base de datos relacional MySQL totalmente administrada y escalable con alta disponibilidad y seguridad.
Azure Database for PostgreSQL	Base de datos relacional PostgreSQL totalmente administrada y escalable con alta disponibilidad y seguridad.
SQL Server en Azure Virtual Machines	Servicio que hospeda aplicaciones empresariales de SQL Server en la nube.
Azure Synapse Analytics	Almacén de datos totalmente administrado con seguridad integral en todos los niveles de escala sin costo adicional.
Azure Database Migration Service	Servicio que migra bases de datos a la nube sin cambios en el código de aplicación.
Azure Cache for Redis	Servicio totalmente administrado que almacena en caché datos estáticos y usados con frecuencia para reducir la latencia de datos y aplicaciones.
Azure Database for MariaDB	Base de datos relacional MariaDB totalmente administrada y escalable con alta disponibilidad y seguridad.

> ### Web
En el mundo empresarial actual es fundamental tener una experiencia web excelente. Azure incluye soporte técnico de primera clase para compilar y hospedar aplicaciones web y servicios web basados en HTTP. Los siguientes servicios de Azure se centran en el hospedaje web.

TABLA 5
Nombre del servicio	Descripción
Azure App Service	Creación rápida de aplicaciones en la nube eficaces basadas en web.
Azure Notification Hubs	Envíe notificaciones push a cualquier plataforma desde cualquier back-end.
Azure API Management	Publique API para desarrolladores, asociados y empleados de forma segura y a escala.
Azure Cognitive Search	Esta búsqueda completamente administrada se implementa como servicio.
Característica Web Apps de Azure App Service	Cree e implemente rápidamente aplicaciones web críticas a escala.
Servicio Azure SignalR	Agregue funcionalidades web en tiempo real con facilidad.

> ### IoT
Los usuarios pueden tener acceso a más información que nunca. Los asistentes digitales personales llevaron a los smartphones y ahora existen relojes inteligentes, termostatos inteligentes e incluso frigoríficos inteligentes. Los equipos estaban a la orden del día. Ahora, Internet permite que cualquier objeto capaz de conectarse tenga acceso a valiosa información. Esta capacidad de los dispositivos de obtener y luego retransmitir información para el análisis de datos se conoce como IoT (Internet de las cosas).

Muchos servicios pueden ayudar e impulsar soluciones de un extremo a otro para IoT en Azure.

TABLA 6
Nombre del servicio	Descripción
IoT Central	Solución global de software como servicio (SaaS) de IoT totalmente administrada que facilita la conexión, la supervisión y la administración de los recursos de IoT a escala.
Azure IoT Hub	Centro de mensajería que proporciona comunicaciones y supervisión seguras entre millones de dispositivos de IoT.
IoT Edge	Servicio totalmente administrado que permite insertar los modelos de análisis de datos directamente en los dispositivos IoT, lo que les permite responder rápidamente a los cambios de estado sin necesidad de consultar modelos de IA basados en la nube.

> ### Macrodatos
Los datos se presentan en cualquier formato y tamaño. Cuando hablamos sobre macrodatos, nos referimos a grandes volúmenes de datos. Los datos de los sistemas del tiempo, sistemas de comunicaciones, investigación genómica, plataformas de imágenes y muchos otros escenarios generan cientos de gigabytes de datos. Esta cantidad de datos hace que resulte difícil analizar y tomar decisiones. A menudo es tan grande que las formas de procesamiento y análisis tradicionales ya no son adecuadas.

Se han desarrollado tecnologías de clúster de código abierto para tratar con estos grandes conjuntos de datos. Azure admite una amplia gama de tecnologías y servicios para proporcionar soluciones de análisis y macrodatos.

TABLA 7
Nombre del servicio	Descripción
Azure Synapse Analytics	Ejecute análisis a gran escala mediante un almacenamiento de datos empresarial basado en la nube que aprovecha las ventajas del procesamiento paralelo masivo para ejecutar rápidamente consultas complejas en petabytes de datos.
HDInsight de Azure	Procese grandes cantidades de datos con los clústeres administrados de Hadoop en la nube.
Azure Databricks	Integre este servicio de análisis colaborativo basado en Apache Spark con otros servicios de macrodatos en Azure.

> ### INTELIGENCIA ARTIFICIAL
En el contexto de la informática en la nube, la inteligencia artificial se basa en una amplia gama de servicios, donde el principal es el aprendizaje automático. El aprendizaje automático es una técnica de ciencia de datos que permite a los equipos utilizar datos existentes para prever tendencias, resultados y comportamientos futuros. Mediante el aprendizaje automático, los equipos aprenden sin necesidad de programarlos explícitamente.

Las previsiones o predicciones del aprendizaje automático pueden hacer que las aplicaciones y los dispositivos sean más inteligentes. Por ejemplo, al comprar en línea, el aprendizaje automático le recomienda otros productos que le pueden gustar según lo que haya comprado. O bien, al pasar la tarjeta de crédito, el aprendizaje automático compara la transacción con una base de datos de transacciones y ayuda a detectar fraudes. Y cuando la aspiradora robot aspira una sala, el aprendizaje automático le ayuda a decidir si se ha terminado el trabajo.

Estos son algunos de los tipos de servicios de inteligencia artificial y aprendizaje automático más comunes de Azure.

TABLA 8
Nombre del servicio	Descripción
Azure Machine Learning Service	Entorno basado en la nube que puede usar para desarrollar, entrenar, probar, implementar, administrar y realizar un seguimiento de los modelos de aprendizaje automático. Puede generar y ajustar automáticamente un modelo. Le permite comenzar a entrenar en el equipo local y luego escalar horizontalmente a la nube.
Azure ML Studio	Área de trabajo visual colaborativa donde puede compilar, probar e implementar soluciones de aprendizaje automático mediante algoritmos de aprendizaje automático predefinidos y módulos de control de datos.
Cognitive Services es un conjunto de productos estrechamente relacionados. Puede usar estas API precompiladas en las aplicaciones para solucionar problemas complejos.

TABLA 9
Nombre del servicio	Descripción
Visión	Use algoritmos de procesamiento de imágenes para identificar, subtitular, indexar y moderar imágenes y vídeos.
Voz	Convierta voz en texto, use la voz para la comprobación o agregue reconocimiento del hablante a la aplicación.
Asignación de conocimiento	Asigne información y datos complejos para resolver tareas como las de recomendaciones inteligentes y búsqueda semántica.
Bing Search	Agregue las Bing Search API a sus aplicaciones y aproveche la capacidad de combinar miles de millones de páginas web, imágenes, vídeos y noticias con una sola llamada API.
Procesamiento de lenguaje natural	permita que las aplicaciones procesen lenguaje natural con scripts precompilados, evalúen opiniones y aprendan a reconocer lo que quieren los usuarios.

> ### DevOps
DevOps reúne a individuos, procesos y tecnología mediante la automatización de la entrega de software para ofrecer un valor continuo a los usuarios. Con Azure DevOps puede crear, compilar y publicar canalizaciones que proporcionan integración, entrega e implementación continuas a las aplicaciones. Puede integrar los repositorios y las pruebas de aplicaciones, realizar la supervisión de aplicaciones y trabajar con artefactos de compilación. También puede trabajar con elementos de trabajo pendiente para realizar el seguimiento, automatizar la implementación de la infraestructura e integrar una gama de herramientas y servicios de terceros como Jenkins y Chef. Todas estas funciones y muchas más están estrechamente integradas con Azure para permitir implementaciones coherentes y reproducibles para que las aplicaciones proporcionen unos procesos de compilación y lanzamiento optimizados.

TABLA 10
Nombre del servicio	Descripción
Azure DevOps	Use herramientas de colaboración de desarrollo como canalizaciones de alto rendimiento, repositorios Git privados gratuitos, paneles Kanban configurables y completas pruebas de carga basadas en la nube y automatizadas. Anteriormente conocido como Visual Studio Team Services.
Azure DevTest Labs	Cree rápidamente entornos de Windows y Linux a petición para probar o realizar demostraciones de las aplicaciones directamente desde canalizaciones de implementación.
