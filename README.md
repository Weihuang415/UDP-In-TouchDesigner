# UDP-In-TouchDesigner
To send MPU9250 data to TouchDesigner via UDP In

esp8266 base library required
and these
#include<Wire.h>
#include <ESP8266WiFi.h>
#include <WiFiUdp.h>
 
Remember to type in these
#define WIFI_SSID "YOUR_SSID_HERE"
#define WIFI_PASS "YOUR_WIFIPASSWORD_HERE"
and unique port number
