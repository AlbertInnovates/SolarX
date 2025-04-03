#include <WiFi.h>
#include <HTTPClient.h>
#define VOLTAGE_PIN 34  // Example pin
#define CURRENT_PIN 35  // Example pin
#define TEMP_PIN 32     // Example pin

void setup() {
  Serial.begin(115200);
  WiFi.begin("Your_SSID", "Your_PASSWORD");
  while (WiFi.status() != WL_CONNECTED) {
    delay(1000);
    Serial.println("Connecting...");
  }
}

void loop() {
  float voltage = analogRead(VOLTAGE_PIN) * (5.0 / 1023.0);
  float current = analogRead(CURRENT_PIN) * (5.0 / 1023.0);
  float temp = analogRead(TEMP_PIN) * (5.0 / 1023.0);

  String data = "voltage=" + String(voltage) + "&current=" + String(current) + "&temperature=" + String(temp);
  HTTPClient http;
  http.begin("http://yourserver.com/log");
  http.POST(data);
  http.end();
  delay(5000);
}
