# Alhambra-EmisorIR

Documentación sobre como hacer un emisor infrarrojos para la placa FPGA Icezum Alhambra o Alhambra II



![](https://raw.githubusercontent.com/makerventura/Mundo_FPGA_libre/master/Imagenes/Alhambra_emisorIR.bmp)



## Construcción de un emisor IR basado en el diodo Led LD274-3

La construcción del circuito electrónico correspondiente a un **emisor IR** es tan sencilla como la de cualquier otro Led de luz visible . 

Solamente hay que colocar el diodo led IR en serie con su resistencia de absorción ( según datasheet del fabricante ) y tener en cuenta la polaridad del diodo .

En nuestro caso la resistencia de absorción será de 180 Ω y el aspecto final se puede apreciar en la siguiente fotografía , donde además hemos encapsulado el led con un poco de tubo retráctil negro para mejorar el enfoque del Led , evitando en lo posible su dispersión .



![](https://raw.githubusercontent.com/makerventura/Mundo_FPGA_libre/master/Imagenes/circuito_emisor.jpg)



Para evitar malos contactos y darle un mejor aspecto al emisor , he construido con FreeCad una versión compacta a la que he denominado **Alhambra EmisorIR** , con el aspecto que  podéis ver en la siguiente imagen :

![](https://raw.githubusercontent.com/makerventura/Mundo_FPGA_libre/master/Imagenes/Alhambra_emisorIR.bmp)





### Instrucciones para la construcción del Alhambra EmisorIR

- Material necesario :

  - Piezas impresas .
  - 1 Diodo Led IR ref. LD 274-3 , o similar . Revisar datasheet del que se utilice , para calcular resistencia necesaria de absorción correspondiente .
  - 1 resistencia de 180 Ω
  - 20 mm de tubo aislante retráctil de 5 mm negro a ser posible .
  - Conector acodado macho de 3 pines

- Pasos a seguir :

  - Acopio de las piezas necesarias para el montaje .

  ![](https://raw.githubusercontent.com/makerventura/Mundo_FPGA_libre/master/Imagenes/IMG_20190419_183538.jpg)

  

  - Enfundar el Led con un poco de tubo retráctil de 5 mm , de unos 15 mm de longitud para que sobre un poco y después se pueda cortar .

  ![IMG_20190419_184033](https://raw.githubusercontent.com/makerventura/Mundo_FPGA_libre/master/Imagenes/IMG_20190419_184033.jpg)

  

  - Imprimir las dos piezas de plástico en 3D con los archivos STL que se adjuntan.

  ![IMG_20190419_191715](https://raw.githubusercontent.com/makerventura/Mundo_FPGA_libre/master/Imagenes/IMG_20190419_191715.jpg)

  

  - Colocación del Led emisor en su alojamiento cuidando que la posición del polo + sea la correcta según la imagen .

  ![IMG_20190419_191936](https://raw.githubusercontent.com/makerventura/Mundo_FPGA_libre/master/Imagenes/IMG_20190419_191936.jpg)

  

  - Soldamos componentes según aprecia en la imagen . Nota : El pin central carece de contacto con ningún elemento y solamente se mantiene a efectos de compatibilizar este sensor con las conexiones de la tarjeta Icezum Alhambra.

  ![IMG_20190419_193110](https://raw.githubusercontent.com/makerventura/Mundo_FPGA_libre/master/Imagenes/IMG_20190419_193110.jpg)

  

  - Comprobamos que funciona y cerramos pegando la tapa inferior para evitar malos contactos .

  ![IMG_20190419_193708](https://raw.githubusercontent.com/makerventura/Mundo_FPGA_libre/master/Imagenes/IMG_20190419_193708.jpg)