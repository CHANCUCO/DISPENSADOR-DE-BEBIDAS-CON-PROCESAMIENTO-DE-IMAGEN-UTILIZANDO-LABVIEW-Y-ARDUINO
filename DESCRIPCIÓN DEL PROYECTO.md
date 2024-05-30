El objetivo del proyecto es crear un sistema automatizado que dispense diferentes tipos de gaseosas basándose en la lectura de un código QR. El sistema utiliza una cámara para capturar 
la imagen del código QR, la cual es procesada mediante LabVIEW. Dependiendo del código QR leído, se envía una instrucción específica a un Arduino que activa las motobombas correspondientes
para dispensar la bebida seleccionada.

Estructura del Repositorio
--------------------------------------------------------------------------------------------------------------------------

   -Código LabVIEW: Contiene los archivos de LabVIEW utilizados para el procesamiento de imágenes y la interfaz de control.
   
   -Código Arduino: Recibe las instrucciones de LabVIEW mediante MakerHub Linx y controla las motobombas.
   
   -Esquema Eléctrico: Diagramas esquemáticos del circuito utilizado, incluyendo conexiones de Arduino y las motobombas.
   
   -Documentación: Librerías necesarias.

¿Cómo Funciona el Código?
--------------------------------------------------------------------------------------------------------------------------


(1) Captura de Imagen: La cámara conectada al sistema captura la imagen del código QR.
--------------------------------------------------------------------------------------------------------------------------

(2) Procesamiento de Imagen en LabVIEW:
--------------------------------------------------------------------------------------------------------------------------

   -La imagen capturada se procesa en LabVIEW utilizando librerías especializadas.
   
   -Se decodifica el contenido del código QR.
 
(3) Envío de Instrucción:
--------------------------------------------------------------------------------------------------------------------------

   -LabVIEW envía una señal al Arduino a través de MakerHub Linx.
   
   -La señal contiene la instrucción específica basada en el código QR decodificado.
 
(4) Control de Motobombas:
--------------------------------------------------------------------------------------------------------------------------

   -El Arduino recibe la instrucción y activa las motobombas correspondientes.
   
   -Las motobombas dispensan la bebida seleccionada.
