# Introducción a Allkun Raptor 3.4



## Qué es Allkun Raptor

Allkun Raptor es un software desarrollado por Kudaw, que permite la obtención, procesamiento y entrega de información de transacciones financieras en tiempo real, mediante la captura de tráfico de red.  
Allkun Raptor es capaz de capturar tráfico directamente desde la red, entender muchos protocolos de comunicación y entregar esta información hacia múltiples destinos para su posterior análisis o visualización.

![](/assets/images/about_raptor.png)

## Características clave


*   **Captura en tiempo real:**
    
    *   Mediante su tecnología de flujos de información, permite capturar y entregar la información en tiempo real.
        

*   **Entiende comunicación de red:**
    
    *   Dada las complejidades en las comunicaciones TCP, donde se deben considerar elementos de conexiones, transmisiones, acuso de recibo, retransmisiones, ordenamientos, entre otros, este software es capaz de manejar dicha complejidad y entregar resultados coherentes.
        

*   **Sin intervención en sistemas productivos y sin agentes:**
    
    *   Debido a su arquitectura de captura de red, basta configurar un port-mirror de tráfico en una máquina dedicada, para que este software comience a procesar las transacciones. No requiere instalación de agentes u otro software en los sistemas productivos.
        

*   **Múltiples protocolos de mensajes:**
    
    *   Los múltiples protocolos utilizados hoy en la comunicación de transacciones financieras, hacen que este producto sea adaptable y pueda interpretar correctamente muchos tipos de mensajerías, como por ejemplo: ISO 8583, Visa/Mastercard, H2H, NDC+ también protocolos personalizados.
        

*   **Múltiples destinos:**
    
    *   Dado el crecimiento constante de múltiples herramientas para el procesamiento de información, este software permite enviar a distintos destinos y con distintos protocolos los mensajes capturados y procesados. Alguno de los protocolos son: HTTP(s), TCP, UDP, Syslog, Archivo, Azure Event Hub, y esta lista continúa creciendo.
        

*   **Ofuscación o Encriptación:**
    
    *   La mayoría de las veces la información financiera transaccional contiene datos que no deben ser visualizados o almacenados en texto plano, debido a la privacidad y además al cumplimiento de estándares de seguridad.
        

*   **Modular:**
    
    *   Debido a la naturaleza diversa de los mensajes a capturar, este software permite incrementar la capacidad de entendimiento de mensajes mediante módulos que pueden ser incorporados para expandir dicha capacidad.
        