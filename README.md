# RFM95 LoRa Shield V0.2

ดาวน์โหลด คู่มือการเชื่อมต่อเข้าระบบ LoRa IoT by CAT ฉบับ Official ได้จาก https://drive.google.com/file/d/1OALHqggIONH6ys-gYKr0pkf06lvrriyg/view

// Pin mapping

const lmic_pinmap lmic_pins = {

  .nss = 10,
  
  .rxtx = LMIC_UNUSED_PIN,
  
  .rst = 9,
  
  .dio = {2, 6, 7},
  
  AS923-upper (923.2-924.6MHz) LMIC-arduino code https://github.com/promwungkwa/LMIC-Arduino-AS923-upper
  
