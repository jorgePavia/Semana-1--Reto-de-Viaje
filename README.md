# "AZURE: CONCEPTOS BÁSICOS "

#  - Azure
Azure es un servicio de computación en la nube creado por Microsoft para construir, probar, desplegar y administrar aplicaciones y servicios mediante el uso de sus centros de datos. Proporciona (SaaS), (PaaS) e (IaaS) y es compatible con muchos lenguajes, herramientas y marcos de programación diferentes, incluidos software y sistemas específicos de Microsoft y de terceros.

![image](https://user-images.githubusercontent.com/83620170/117591676-1e814400-b0fb-11eb-90b6-f0c6cf24b170.png)

#  - ¿Qué es la nube?
La definición de la nube puede parecer poco clara, pero, básicamente, es un término que se utiliza para describir una red mundial de servidores, cada uno con una función única. La nube no es una entidad física, sino una red enorme de servidores remotos de todo el mundo que están conectados para funcionar como un único ecosistema. Estos servidores están diseñados para almacenar y administrar datos, ejecutar aplicaciones o entregar contenido o servicios, como streaming de vídeos, correo web, software de ofimática o medios sociales. En lugar de acceder a archivos y datos desde un equipo personal o local, accede a ellos en línea desde cualquier dispositivo conectado a Internet, es decir, la información está disponible dondequiera que vaya y siempre que la necesite.

![image](https://user-images.githubusercontent.com/83620170/117591654-0c070a80-b0fb-11eb-850c-af840f213021.png)

#  "Metodos de implementacion de la nube"
#  - Nube Pública
La nube pública es entonces un conjunto compartido de recursos, que sirven a muchas organizaciones, startups y personas, a realizar cómputo, almacenamiento de bases de datos, entrega de contenido y otra funcionalidad para ayudar a las empresas a escalar y crecer, sin un coste y desembolso inicial fuerte, pagando sólo lo que usa, para crear aplicaciones sofisticadas y cada vez más flexibles, escalables y fiables.
El beneficio de este paradigma se resume en el ahorro de costos (no hay inversión inicial en equipamiento o licencias de software), y en la agilidad con que varía la utilización de recursos de TI, la elasticidad de adaptarse a los cambios o nuevas necesidades.

![image](https://user-images.githubusercontent.com/83620170/117592138-20e49d80-b0fd-11eb-9223-4dc2968a55f7.png)

#  - Nube Privada
Una nube privada virtual1 o VPC (sigla del inglés virtual private cloud) es un conjunto de recursos computacionales configurables por demanda al interior de un ambiente de computación en la nube pública, el cual provee un cierto nivel de aislamiento entre las diferentes organizaciones o usuarios que utilizan dichos recursos. El aislamiento entre una VPC y los demás usuarios de la nube (tanto otras VPC como usuarios de la nube pública) se logra normalmente a través de la utilización de una subred IP y un mecanismo de comunicación virtual como una red privada virtual (VPN) o un grupo de canales encriptados) para cada usuario.

![image](https://user-images.githubusercontent.com/83620170/117592147-2e018c80-b0fd-11eb-81f6-b49f6e7235d5.png)

#  - Nube hibrida
En los entornos de nube híbrida se utilizan tanto la nube pública como la privada. Los entornos multinube incluyen dos o más proveedores de nube pública que ofrecen servicios basados en la nube a una empresa que puede tener una nube privada o no. Los entornos de nube híbrida también pueden ser entornos multinube.

![image](https://user-images.githubusercontent.com/83620170/117592234-715bfb00-b0fd-11eb-93a8-87f429da92e2.png)

# "Tipos de servicio en la Nube"
# -Software as a Service (SAAS)
Es un modelo de distribución de software donde el soporte lógico y los datos que maneja se alojan en servidores de una compañía de tecnologías de información y comunicación (TIC), a los que se accede vía Internet desde un cliente. Algunos ejemplos comunes son el correo electrónico, los calendarios y las herramientas ofimáticas (como Microsoft Office 365).

![image](https://user-images.githubusercontent.com/83620170/117591630-f85ba400-b0fa-11eb-81fa-c53ca6c36eac.png)

# -Platform as a Service (PAAS)
Marco de desarrollo. PaaS proporciona un marco que los desarrolladores pueden ampliar para desarrollar o personalizar aplicaciones basadas en la nube. De forma similar a la creación de una macro en Excel, PaaS permite a los desarrolladores crear aplicaciones usando componentes de software integrados. Algunos ejemplos pueden ser Google App Engine y Bungee Connect son dos ejemplos de plataformas como servicios y tienen las siguientes características. Google App Engine: este servicio de Google está enfocado a que el cliente pueda publicar aplicaciones web online, sin tener que preocuparse por la infraestructura donde hacerlo.

![image](https://user-images.githubusercontent.com/83620170/117591808-b54e0080-b0fb-11eb-9b28-90fdb69a9f6b.png)
# -Infrastructure as a Service (IAAS)
Se refiere a los servicios en línea que proporcionan un alto-nivel de APIs utilizadas para indireccionar detalles a bajo nivel de infraestructura como recursos de informática física, ubicación, dato partitioning, scaling, seguridad, copia de seguridad etc. Un hypervisor, como Xen, Oracle VirtualBox, Oracle VM, KVM, VMware ESX/ESXi, o Hyper-V, LXD, corre las máquinas virtuales como huéspedes. Pools de hypervisors dentro del sistema operacional de la nube pueden apoyar gran cantidad de máquinas virtuales y la capacidad de adaptarse a los servicios según los requisitos de los clientes. Contenedores de Linux funcionan en particiones aisladas de un Linux kernel, que a la vez se ejecuta directamente en el hardware. Linux cgroups y namespaces son las tecnologías subyacentes de Linux  para aislar, asegurar y dirigir los distintos contenedores. Containerisation ofrece un rendimiento más alto que la virtualizacion, porque hay no hypervisor por encima.

![image](https://user-images.githubusercontent.com/83620170/117591876-f6461500-b0fb-11eb-8cd5-c579f51e9a43.png)
# - Kernel
Kernel o núcleo, es una parte fundamental del sistema operativo que se encarga de conceder el acceso al hardware de forma segura para todo el software que lo solicita, el Kernel es una pequeña e invisible parte del sistema operativo, pero la más importante, ya que sin esta no podría funcionar. Todos los sistemas operativos tienen un Kernel, incluso Windows 10, pero quizá el más famoso es el Kernel de Linux, que ahora además está integrado en Windows 10 con sus últimas actualizaciones.

Este núcleo de los sistemas operativos se ejecuta en modo privilegiado con acceso especial a los recursos del sistema para poder realizar las peticiones de acceso que le va pidiendo el software que lo necesita, además como los recursos no son ilimitados, también hace de arbitro a la hora de asignarlos, decidiendo el orden de las peticiones recibidas según la prioridad e importancia de estas. 

El Kernel o núcleo de un sistema operativo sirve para administrar los recursos de hardware solicitados por los diferentes elementos de software y hacer de intermediario decidiendo a que y cuando se concede este acceso evitando así sobrecarga del sistema, recursos innecesarios y acceso a software malicioso al propio Kernel y llegar a poder controlar así todo el sistema. De este modo el Kernel sirve como elemento de seguridad teniendo que pasar por varias capas antes de poder tener acceso, además tiene que distribuir los recursos de manera eficiente y ordenada para que el Hardware trabaje junto al Software de la mejor manera posible.

![image](https://user-images.githubusercontent.com/83620170/117592392-f34c2400-b0fd-11eb-9de7-c0343e062e64.png)

# - Servicios de Azure

-Compute: Son los servicios que proporcionan los servicios de computo, como lo son las máquinas virtuales.

-Networking: Permite conectar a todos para conectar los recursos y tener una comunicación.

-Storage: Almacena archivos, fotos,etc. Un ejemplo de esto es Netflix, donde guarda todas las series y películas de su plataforma.

-Bases de datos: Se encarga de guardar datos y registros. Un ejemplo, siguiendo con lo de Netflix, se encargaría de verificar tu cuenta de Netflix para darte acceso.

-IoT: Servicio para el internet de las cosas, puede mandar información y guardar datos en una base de datoss, y constantemente está recibiendo datos dependiendo que implementación se use.

-Big Data: Está optimizada para el manejo de grandes cantidades de datos, como lo con los petabytes

-DevOps: Se encarga de automatizar el desarrollo de softwarer. Un ejemplo de esto es GitHub.

-Inteligencia artificial: Se encarga de los cognitive service y de los servicios de machine learning.

![image](https://user-images.githubusercontent.com/83620170/117592428-1a0a5a80-b0fe-11eb-8af0-73e8f1fb7244.png)
