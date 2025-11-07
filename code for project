writ your code here: ^_^

/* 
//  testing for MHZ19 sensor

#include <MHZ19.h>
#include <SoftwareSerial.h>

SoftwareSerial mySerial(2, 3); // RX = 2, TX = 3

MHZ19 myMHZ19;

void setup() {
  Serial.begin(9600);        // USB serial for monitoring
  mySerial.begin(9600);      // UART to MH-Z19B
  myMHZ19.begin(mySerial);
}

void loop() {
  int co2ppm = myMHZ19.getCO2();
  Serial.print("CO2 ppm: ");
  Serial.println(co2ppm);

  delay(2000); // update every 2 seconds
}
*/


/*
// Testing for PMS sensor

#include <SoftwareSerial.h>
#include "PMS.h"

// Create a SoftwareSerial port on pins 8 (RX) and 9 (TX)
SoftwareSerial pmsSerial(8, 9);  // RX, TX
PMS pms(pmsSerial);
PMS::DATA data;

void setup() {
  Serial.begin(9600);       // For your PC Serial Monitor
  pmsSerial.begin(9600);    // PMS5003 default baud rate
  Serial.println("PMS5003 sensor starting...");
}

void loop() {
  if (pms.read(data)) {
    Serial.println("=== PMS5003 Read ===");
    Serial.print("PM 1.0 (ug/m3): "); Serial.println(data.PM_AE_UG_1_0);
    Serial.print("PM 2.5 (ug/m3): "); Serial.println(data.PM_AE_UG_2_5);
    Serial.print("PM 10.0 (ug/m3): "); Serial.println(data.PM_AE_UG_10_0);
    Serial.println();
  }

  // Add a short delay to avoid flooding Serial
  delay(1000);
}
*/
