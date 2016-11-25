# mqtt4iot
Simple chat implementing MQTT on Android

This project pretends to start developers on the IoT world using the MQTT protocol
by implementing a simple chat app that connects to the "iot eclipse" broker and
publishes to the "mqtt4iotdemo" topic as well as subscribe to this same topic in
order to receive the messages. All the devices using this app will receive the
messages that others apps are publishing.

This is a simple way to understand the pub/sub patter as well as the MQTT protocol.

### Technologies
* Android SDK v19 to v23
  * Gradle 1.3.0
  * Android Studio 1.4.1
* Eclipse Paho Android Service
* iot eclipse - Broker
