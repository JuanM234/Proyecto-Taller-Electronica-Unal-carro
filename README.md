## <p align="center"><b> PROYECTO TALLER DE ELECTRÓNICA - CARRO MANEJADO POR WIFI</b></p>

<p align="center">
  <img src="https://github.com/JuanM234/Proyecto-Taller-Electronica-Unal-carro/assets/44301882/784a3386-ab00-4799-9a4a-0ec6e99949c8" alt="Descripción de la imagen">
</p>

## DESCRIPCIÓN
Este proyecto consiste en el diseño y desarrollo de un carrito controlado de forma remota mediante WiFi utilizando el potente módulo ESP32. El carrito ofrece movilidad ágil y emite una red WiFi, lo que permite su control desde cualquier dispositivo dentro del alcance de la red.

## IDEA INICIAL
se tenia pensado que el carrito se manejara con un guante mediante wifi, pero por tiempo y otras circusntancias no se logro, sin embargo, se busco culminar el proyecto, y que se controle mediante wifi, Tambien en un principio se queria usar una esp32 cam pero dado que en un error se daño una, y al conseguir otra no nos daba la señal wifi, optamos por una esp 32 normal.
## INTRODUCCIÓN
nuestro proeycto consiste de un carrito controlado por WiFi mediante un ESP32. Este carrito inteligente se conecta a una red WiFi y se puede controlar desde cualquier lugar dentro del alcance. Utilizando una interfaz en un dispositivo móvil o computadora, se pueden enviar comandos de control para avanzar, retroceder, girar y detenerse.  Este proyecto es una oportunidad fascinante para aprender sobre programación, electrónica y comunicación inalámbrica en un contexto práctico y universitario.
## MOTIVACIÓN
Uno de los principales impulsos para emprender este proyecto era nuestro deseo de aprender más sobre electrónica. La creación de un carrito controlado por WiFi mediante un ESP32 nos brinda la oportunidad de sumergirme en los fundamentos de la electrónica y adquirir conocimientos prácticos en esta área. A través de este proyecto, espero explorar los conceptos y componentes electrónicos, así como fortalecer mis habilidades de diseño y resolución de problemas en el campo de la electrónica. Esta experiencia de aprendizaje será valiosa no solo para este proyecto en particular, sino también para futuros proyectos y el crecimiento de nuestras habilidades en el ámbito de la electrónica.
## GUÍA DE USO
1. Conecte su dispositivo (teléfono, computadora, etc.) a la red que emite el esp 32 la cual es MyWifiCar.
   
![photo_4956718763454081924_y (1)](https://github.com/JuanM234/Proyecto-Taller-Electronica-Unal-carro/assets/44301882/80e4e110-9c03-45cf-9639-a608be373065)

2.Introduzca la contraseña la cual es 12345678.

![photo_4956718763454081925_y (1)](https://github.com/JuanM234/Proyecto-Taller-Electronica-Unal-carro/assets/44301882/ec9edd27-a842-4444-8d33-505517e33ff4)

3. Abra una aplicación de terminal o navegador web y acceda a la dirección IP asignada al ESP32. (192.168.4.1)
   
![photo_4956718763454081926_y (1)](https://github.com/JuanM234/Proyecto-Taller-Electronica-Unal-carro/assets/44301882/936f7b68-6aa9-445d-8121-fe5c2f8fc3a3)

4. Desde la interfaz de control, podrá enviar comandos para controlar el movimiento del carrito, como avanzar, retroceder, girar y detenerse.
   
![photo_4956718763454081927_y (1)](https://github.com/JuanM234/Proyecto-Taller-Electronica-Unal-carro/assets/44301882/7bde8e6d-7f44-47c0-95e7-08d176db77ae)

5. Experimente con diferentes comandos y ajuste la velocidad según sea necesario.

## Lista de Materiales

Componentes usados en el proeycto:

- L298N: Controlador de motor de puente H.
- ESP32: Módulo de desarrollo con conectividad WiFi.
- 4 motores DC: Para proporcionar la tracción al carrito.
- Chasis: Estructura que sostiene y protege los componentes del carrito.
- 4 ruedas: Para permitir el movimiento del carrito.
- Cables: Para realizar las conexiones entre los componentes.
- Pin headers o regleta de pines: Para facilitar la conexión de los componentes al ESP32.

## Objetivos del Proyecto

El objetivo principal de este proyecto es diseñar y desarrollar un carro manejado por WiFi utilizando un ESP32, con el fin de explorar y aplicar conocimientos de electrónica y programación. A continuación se detallan los objetivos específicos:

1. Construir o conseguir un chasis que albergue los componentes del carro.
2. Conectar y configurar el ESP32 para establecer la conectividad WiFi y permitir el control remoto.
3. Implementar el control de los motores DC para lograr el movimiento del carro en diferentes direcciones.
4. Optimizar el consumo de energía del sistema para una mayor autonomía y eficiencia energética.
5. Realizar pruebas exhaustivas y depuración para asegurar el correcto funcionamiento del carro.
6. Documentar detalladamente el proceso de construcción, configuración y uso del carro en el archivo README.
7. Promover la colaboración y participación del grupo de Taller.

## Limitaciones del Proyecto

A pesar de los esfuerzos realizados, es importante tener en cuenta las siguientes limitaciones del proyecto:

1. Alcance del control: El carrito podrá ser controlado de forma remota dentro del alcance de la red WiFi. Fuera de este rango, no se podrá establecer la conexión ni controlar el carrito.
2. Obstáculos y terreno: El desempeño del carrito puede verse afectado por la presencia de obstáculos y el tipo de terreno en el que se utilice. Se recomienda utilizarlo en superficies lisas y sin obstrucciones para obtener un mejor rendimiento.
3. Estabilidad de la conexión: La calidad de la conexión WiFi puede variar dependiendo de la interferencia y la congestión de la red. Esto puede afectar la respuesta y la estabilidad del control remoto.
4. Autonomía limitada: La duración de la batería del carrito dependerá del consumo de energía y la capacidad de la batería utilizada. Es posible que se requiera recargar o reemplazar la batería después de un período de uso prolongado.
5. Capacidades de carga: El carrito está diseñado para transportar cargas ligeras y no está diseñado para transportar objetos pesados o voluminosos. Se recomienda respetar las limitaciones de carga especificadas en el diseño del chasis y los motores.

## PROCESO DEL PROYECTO
   El proyecto se inició utilizando Arduino como plataforma inicial para realizar pruebas y prototipado. En esta etapa, el equipo se enfocó en comprender los conceptos básicos de la electrónica y la programación necesarios para construir un carrito controlado por WiFi. Durante este proceso, enfrentaron un desafío relacionado con la alimentación. Descubrieron que era necesario alimentar por separado tanto el Arduino como el módulo L298N, que se utilizaba para controlar los motores del carrito. Esta configuración generaba una mayor complejidad y requería fuentes de alimentación adicionales.

A medida que el proyecto avanzaba, el equipo se dedicó a buscar una solución más integrada y eficiente en términos de alimentación. Después de investigar y explorar diferentes opciones, se decidió utilizar baterías de ion de litio 18650. Estas baterías ofrecían una mayor capacidad y permitían alimentar de manera simultánea todos los componentes del sistema, incluyendo el Arduino, el módulo L298N y el ESP32. Esta mejora fue clave para simplificar la configuración y lograr un solo sistema compacto y autónomo.

Además de las mejoras en la alimentación, el equipo decidió migrar de Arduino a ESP32CAM en un momento para aprovechar sus capacidades de conectividad WiFi y Camara, pero en un descuido se nos daño, y al conseguir otra no nos daba la señal que necesitamoss.

asi que emigramos a la ESP32 estandar. La ESP32 proporcionaba una mayor flexibilidad y posibilitaba el control remoto del carrito a través de una conexión inalámbrica. Esta transición permitió expandir las funcionalidades del proyecto y abrir nuevas posibilidades de interacción y control.

A medida que el proyecto avanzaba, el equipo adquirió experiencia en el diseño de circuitos impresos y decidió crear una PCB personalizada. Esta PCB, diseñada específicamente para el proyecto, permitió una mejor organización y conexión de los componentes, reduciendo el espacio ocupado y mejorando la estética general del carrito. El diseño de la PCB implicó la disposición adecuada de los componentes, la conexión de las pistas de cobre y la verificación de la integridad del circuito.

Con el paso del tiempo, el proyecto evolucionó hasta llegar a su estado final. El carrito, completamente funcional, es capaz de ser controlado de forma remota mediante una conexión WiFi gracias al ESP32. Todas las mejoras y optimizaciones realizadas a lo largo del desarrollo se encuentran integradas en el diseño final del proyecto. La PCB personalizada se encuentra implementada y proporciona una solución robusta y compacta.

En resumen, el proceso de desarrollo del proyecto implicó la superación de desafíos iniciales relacionados con la alimentación y la integración de componentes. A través de iteraciones y mejoras continuas, el equipo logró diseñar una PCB personalizada y alcanzar el estado final del proyecto, donde el carrito es capaz de ser controlado de forma remota y cuenta con un sistema de alimentación integrado y eficiente.

