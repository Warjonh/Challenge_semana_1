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