Connect-NodeMCU-to-WiFi

This github includes the complete code to connect the NodeMCU ESP8266 Board to any WiFi Network

Below are some commands and there explanation in order to understand the code.

#include <ESP8266WiFi.h> //Library

WiFi.begin("WiFiName", "WiFiPassword"); //Command to connect to a WiFi Network

WiFi.status(); //To check if it is connected to a Network or not.

WiFi.status() values can be:

WL_CONNECTED

WL_IDLE_STATUS

WL_CONNECT_FAILED
