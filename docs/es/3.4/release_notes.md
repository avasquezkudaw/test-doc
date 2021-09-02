# Registro de Cambios Allkun Raptor 3.3

Esta versión de Allkun Raptor trae importantes mejoras de seguridad, portabilidad, estabilidad y rendimiento. A continuación se detallan las novedades.
 


## 3.4.0

#### Nuevas características

|Nuevas características o Mejoras|Descripción|
|---|---|
|Cambio en estructura de directorios|Se establece una nueva estructura de directorios para los archivos de configuración y logs del producto|
|Incorporación de nuevos tipos de output|Se agrega como fuente de salida de mensajes, Azure Event Hub.|
|Producto autocontenido|Ya no se requiere tener una versión de python o librerías externas para su funcionamiento. Esto permite que el producto sea autocontenido y facilmente instalable. Además le aporta un mayor rendimiento en su ejecución.|

#### Issues corregidos
|Fecha de Resolución|Código de Issue|Descripción|
|---|----|----|
|14 Oct 2019 |PRAP-17|Corrección de lógica para término de licencia post días de expiración. Se modifica el módulo de licencia para establecer días de expiración en base a fechas.|
|27 Sep 2019 |PRAP-18|Corrección problema de codificación. Para mensajes con codificación,  diferente a ASCII, se utiliza el parámetro UTF-8|


#### Issues Conocidos
|Fecha de Resolución|Código de Issue|Descripción|
|---|----|----|
|---|----|----|