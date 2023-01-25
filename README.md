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

