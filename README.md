## **Practica 3: WIFI y BLUETOOTH**
La principal función de la práctica está destinada a trabajar con el wifi y el bluetooth.
Con la ayuda del microprocesador ESP32, utilizado en las prácticas anteriores, se llevará a
cabo una práctica dónde se generará un web server desde la placa, también con la ayuda de una 
aplicación que se descargará en el móvil y con la ayuda del bluetooth, de este anterior, 
elaboraremos una comunicación serie.

## **Practica A: generación de una pagina web**
**Codigo main.cpp:**
```
#include <Arduino.h>
#define LED_BUILTIN 48
#define DELAY 500


 void setup() {
  pinMode(LED_BUILTIN, OUTPUT);
  }
  void loop() {
  digitalWrite(LED_BUILTIN, HIGH);
  delay(DELAY);
  digitalWrite(LED_BUILTIN, LOW);
  delay(DELAY);
  }

```

Principalmente el fucionamiento de este código és configurar la placa ESP32, para que esta actue como un servidor, así para que genere una página web, donde esa página web es una página HTML, dónde se accede a su IP, desde un navegador.

En la función setup(), se inicializa la comunicación serial, se conecta a la red Wi-Fi y se inicia el servidor web.
En la función loop(), se manejan las solicitudes de los clientes al servidor web.
El código incluye de las librerías WiFi.h y WebServer.h, para hacer lo dicho anteriormente.

La salida que se muestra por terminal del código:

## **Practica B comunicación bluetooth con el movil**
**Codigo main.cpp:**
```
#include <Arduino.h>
#define LED_BUILTIN 48
#define DELAY 500


 void setup() {
  pinMode(LED_BUILTIN, OUTPUT);
  }
  void loop() {
  digitalWrite(LED_BUILTIN, HIGH);
  delay(DELAY);
  digitalWrite(LED_BUILTIN, LOW);
  delay(DELAY);
  }

```
Este código trabajamos con bluetooth, donde se establece una comunicación entre la placa ESP32 
y un dispositivo móvil a traves del bluetooth, donde se puede enviar i recibir datos.

Las salidas que se obtienen:

Las salidas que obtenemos a traves del puerto serie son los datos de que se envian y reciben 
en la comunicacón de los 2 dispositivos. Los datos pueden ser enviados de 2 formas: . ESP32 
al dispositivo . Del dispositivo al ESP32

## **Ejercicios de mejora de nota**
**Codigo main.cpp:**
```
#include <Arduino.h>
#define LED_BUILTIN 48
#define DELAY 500


 void setup() {
  pinMode(LED_BUILTIN, OUTPUT);
  }
  void loop() {
  digitalWrite(LED_BUILTIN, HIGH);
  delay(DELAY);
  digitalWrite(LED_BUILTIN, LOW);
  delay(DELAY);
  }

```
