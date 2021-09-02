# Guía de Instalación



## Público Objetivo

Esta información está destinada a cualquier persona que desee instalar, configurar, administrar o desarrollar en Allkun Raptor. La información está escrita para administradores de sistemas Linux experimentados, que están familiarizados con la tecnología de línea de comandos, archivos de configuración y sobre todo amplio conocimiento en tráfico de redes de comunicación.

## Antes de instalar

### Checklist de preinstalación

* Asegúrese de cumplir con los siguentes requisitos antes de comenzar la instalación del software Allkun Raptor:

* Máquina física dedicada para la captura de tráfico de red.

* Port-mirror conectado y configurado, que permita ver pasar el tráfico transaccional.

* Software Allkun Raptor 3.3 descargado y en la máquina donde se realizará la captura de tráfico.

* Acceso como super usuario a máquina donde se instalará el producto.

* Archivo de licencia entregado y vigente.


### Plataformas soportadas y especificaciones

Las plataformas soportadas por el producto, y las especificaciones necesarias son las siguientes:

|Especificación|Detalle|
|---|---|
|Linux|CentOS 6.x, RHEL 6.x, CentOS 7.x, RHEL 7.x (Arquitectura: x86-64 64-bit)|
|CPU|Recomendado 2x six-core, 2+GHz (Ver Sizing)|
|Memoria|Recomendado 12GB RAM (Ver Sizing)|
|Disco|50GB de espacio en disco disponible para el directorio de instalación.|
|Red|3 tarjetas de red de 1Gbps para administración, recepción y transmisión de datos.|



### Puertos requeridos

No requiere puertos de comunicación adicionales para que el producto pueda funcionar.



### Sizing

Se recomiendan las siguientes configuraciones de capacidad de acuerdo a la tasa de ingesta promedio:

|Opción|Tasa de Ingesta promedio|CPUs|Memoria|
|---|---|---|---|
|Small|50 mensajes/segundo|8|16|
|Medium|100 mensajes/segundo|16|32|
|Large|200 mensajes/segundo|32|64|


## Instalación

En primer lugar, se debe obtener el paquete de instalación de Allkun Raptor, provisto por Kudaw.

### Procedimiento

Para comenzar la instalación del paquete de instalación de Allkun Raptor, se recomienda que este quede instalado en el directorio "/opt", por tanto ahí se debe copiar el instalador. Para instalar realice los siguientes pasos:


1. Abra una terminal y conéctese a la máquina donde se instalará el producto.

2. Ejecute el siguiente comando, con un usuario con privilegios de “super usuario”, el cual ejecutará el producto.


	```
	sudo tar xvzf raptor-<version>-<build>-<system>.tar.gz
	```

	Esto desempaquetará los archivos y directorios del producto en una carpeta llamada "raptor". Por lo que desde ahora, llamaremos esta ruta completa \$RAPTOR_HOME (/opt/raptor)

3. Copiar los archivos de licencia <file>.lic y <file>.dat en el directorio $RAPTOR_HOME/etc/license/

4. En este instante el producto está instalado y listo para su ejecución.


## Próximos pasos

Una vez instalado el producto, debe ser configurado para poder ejecutarlo correctamente. Esta configuración se explica en el siguiente capítulo “Guía de Configuración”.