# C5_Project_IoT
Proyecto Cuatrimestre 5 IoT

# Objetivo
Crear una dispositivo que logre realizar ciertas tareas por medio de comandos de voz

# Integrantes
- Osmar Israel Villegas Martínez
- Mario Alberto Rangel Márquez
- Martin Gabriel Godinez Morales
- Omar Martín Gonzalez Hernandez

# Historia de usuario
- Como usuario quiero poder tener un dispositivo con el cual facilitar actividades, para poder realizar mis actividades de forma más practica
- Como usuario quiero que el dispositivo pueda traducir


# Materiales
- Bocina
-	Pantalla led 6*32
-	Micrófono
-	Botones
-	Leds	
-	Extensión

# Objetivo general

El objetivo general de este proyecto es la realización y con diferentes herramientas la identificación de voz y transcripción a texto. Con la finalidad de utilizar una IA para hacer peticiones de voz hacia esta, por lo cual consideramos es un reto interesante y el cual nos entusiasma. 

# Obetivos Especificos

- Identificar el reconocimiento de voz para permitir a los usuarios dictar notas y mensajes de texto. La aplicación utilizaría una API de ChatGTP-3
- El sistema utilizaría una API de reconocimiento de voz para transcribir la voz a texto y luego utilizar una IA para interpretar la pregunta y proporcionar una      respuesta adecuada.
- La información que responda la IA será plasmada esa información de la LCD
- Traducir el texto que el usario desee. 

# Tabla de Software Utilizado y otros

| ID | Software | Versión |  Tipo  |
| ---|----------|---------|--------| 
| 1  | VSCode   | 1.53.3  |  IDE   |
| 2  | Whisper  |         |protocol|
| 3  | python   | 3.10    |lenguaje|
| 4  |  ESP32   |         |Libreria|
| 5  |ChatGPT-3 |  3      |  IA    |


# Tabla con el hardware utilizado}
| ID | Componente | Descripción | Imagen | Cantidad | Costo total  |
|----|------------|-------------|--------|----------|--------------|
|  1 |     ESP32  |El módulo ESP32 es una solución de Wi-Fi/Bluetooth todo en uno, integrada y certificada que proporciona no solo la radio inalámbrica, sino también un procesador integrado con interfaces para conectarse con varios periféricos       |    ![image](https://user-images.githubusercontent.com/114530252/214478669-80e0ca57-6980-4700-8018-2760aaa64181.png) |   1  |     $280      |
| 2 | LED  RGB| Un diodo LED es un dispositivo que permite el paso de corriente en un solo sentido y que al ser polarizado emite un haz de luz |  ![image](https://user-images.githubusercontent.com/114530252/214479407-d698c1e5-f40e-4472-9487-e633f25aa8c5.png)  | 1 | $10 |
|3| Módulo de pantalla LED 6*32| Una placa de LED o módulo de LED para pantallas led, es un pequeño circuito que integra los leds y el resto de electrónica necesaria para que los leds puedan reproducir imágenes y videos.| ![image](https://user-images.githubusercontent.com/114530252/214479995-0cf591ec-51ea-45f1-8218-8d2e1bc73221.png)  |  1  |  180  |
|4|  Extensión |  La extensión eléctrica es un conjunto formado por un cable flexible o cordón equipado con un enchufe y un conector no desmontable, encargado de conectar un artefacto eléctrico al suministro de energía eléctrica. | ![image](https://user-images.githubusercontent.com/114530252/214481698-d10f1a18-7254-4d88-ab7d-4393ebd52c2e.png) | 1 |  $70 | 
|  5  |Push button | Switch push miniatura momentáneo normalmente abierto. Un interruptor eléctrico es en su acepción más básica un dispositivo que permite desviar o interrumpir el curso de una corriente eléctrica. | ![image](https://user-images.githubusercontent.com/114530252/214482548-a215b421-6105-4f88-82b4-ad74080f733a.png) |   1 | $5 |
|6| Rasperry pi | Raspberry Pi es una placa de microordenador, que como su propio nombre indica, es de pequeñas dimensiones a la cual se le pueden dar multitud de usos | ![image](https://user-images.githubusercontent.com/114530252/214484326-d021eeca-3c90-4751-bd6f-c55c14efb654.png) |  1 | $200 |
|7|  Modulo Mp3 | El Módulo reproductor MP3 Arduino es un mini reproductor mp3 muy económico utilizado para reproducir estos formatos de audio en Arduino con una salida directa hacia un speaker |  ![image](https://user-images.githubusercontent.com/114530252/214484671-a196ef62-c279-43dd-8248-ff4dc3dff09d.png)| 1  | $72 |
|8 | INMP441 Módulo de Micrófono | El INMP441 es un micrófono omnidireccional con salida digital I2S, el Chip incorpora un sensor MEMS, circuito de acondicionamiento, ADC, filtros y una interfaz I2S. de esta manera se puede conectar directamente a otros dispositivos que soporten I2C sin necesidad de un códec de audio. | ![image](https://user-images.githubusercontent.com/114530252/214485123-9ab8c481-e099-4f30-8d08-12883e1022c7.png) | 1 | $54.14 |
| 9 |Buzzer| es un pequeño transductor capaz de convertir la energía eléctrica en sonido. Para hacerlos funcionar solo basta conectar el positivo con el + y la tierra o negativo con el – de una batería o cualquier fuente de corriente directa|![image](https://user-images.githubusercontent.com/114530252/214485442-7cbbc188-f39a-495d-a6a3-8a8e7d0edbe2.png) | 1 | $50 |  

# Boceto
![image](https://user-images.githubusercontent.com/114530252/214487367-8af4e1f9-d06c-48fc-af61-58fbc8c36c2c.png)
