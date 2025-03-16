## **Practica 3: WIFI y BLUETOOTH**
Esta práctica tiene como objetivo trabajar con WiFi y Bluetooth utilizando el microprocesador ESP32. Se creará un servidor web en la placa y, mediante una aplicación móvil y Bluetooth, se establecerá una comunicación serie.

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

Este código tiene como objetivo configurar la placa ESP32 para que funcione como un servidor, generando una página web accesible desde un navegador mediante su IP.

En la función setup(), se establece la comunicación serial, se conecta a la red Wi-Fi y se inicia el servidor web. En la función loop(), se gestionan las solicitudes de los clientes al servidor. El código utiliza las librerías WiFi.h y WebServer.h para llevar a cabo estas tareas.

Lo que aparece en el terminal del código:
```
Try Connecting to 
Nautilus
...........................
WiFi connected successfully
Got IP: 192.168.50.114
HTTP server started
```

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
Este código establece una comunicación Bluetooth entre la placa ESP32 y un dispositivo móvil, permitiendo el envío y recepción de datos.

A través del puerto serie, se pueden ver los datos enviados y recibidos entre los dos dispositivos. Los datos pueden enviarse de dos maneras: desde el ESP32 al dispositivo o del dispositivo al ESP32.

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
