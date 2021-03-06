# [ENGLISH] Project 4: Motion Detector
***Please note that some parts in this project are not available in Internet of Things Maker Kit. You can found them in [Arduino Maker Kit](https://github.com/userdw/Arduino_Maker_Kit).***

How to add movement detection feature to your project? The answer is PIR sensor, which is an abbreviation for Passive Infrared sensor. PIR sensor works by measuring infrared light emitted by objects in its field of view. When there is a change in the amount of infrared light PIR sensor received, it will send a signal to our system. Every objects emit infrared light, therefore PIR sensor should be able to detect their movement as long as the emitted infrared light is high enough to pass the PIR's threshold. The most common application of PIR is an automatic door which can open automatically when someone walking closer to it. On this project we will make a simple system that will detect our body movement utilizing PIR Sensor and LED Module. If the system is detecting our body movement, then it will light up the LED Module.

<img src="/images/04_motion_detector.png" height="400">

### In this project you will need:
* ESP8266 IoT v2.0 (1),
* ESP8266 Expansion Shield (1),
* LED Module (1),
* PIR Sensor (1).

### Assemble the modules following these steps:
1. Plug the ESP8266 Expansion Shield to the top of ESP8266 IoT v2.0,
2. Plug the LED Module to the header on the ESP8266 Expansion Shield labelled **3**,
3. Plug the PIR Sensor to the header on the ESP8266 Expansion Shield labelled **5**,
4. Upload the [Motion_Detector](/04_Motion_Detector/Motion_Detector) code into ESP8266 IoT v2.0.

If there are no mistakes, LED Module should blink as long as there is movevment detected by PIR Sensor.

# [BAHASA INDONESIA] Proyek 4: Motion Detector
***Beberapa peralatan yang digunakan pada proyek ini tidak tersedia pada Internet of Things Maker Kit. Peralatan-peralatan tersebut dapat ditemukan pada [Arduino Maker Kit](https://github.com/userdw/Arduino_Maker_Kit).***

Bagaimana kita dapat menambahkan fitur pendeteksi gerakan pada sistem kita? Jawabannya adalah dengan menggunakan sensor PIR, dimana PIR sendiri merupakan kependekan dari Passive Infrared. Sensor PIR bekerja dengan cara mengukur cahaya infra merah yang dipancarkan oleh obyek yang berada pada area pendeteksiannya. Apabila terdapat perubahan dari intensitas cahaya infra merah yang diterima oleh sensor PIR, maka sensor PIR akan mengirimkan sinyal pada sistem kita. Sensor PIR akan dapat mendeteksi gerakan dari obyek-obyek selama cahaya infra merah yang dipancarkan melebihi nilai threshold dari sensor PIR tersebut. Aplikasi yang paling umum dari PIR adalah pintu otomatis yang akan membuka sendiri apabila ada orang yang berjalan mendekat. Pada proyek ini kira akan membuat sebuah sistem sederhana yang akan mendeteksi gerakan tubuh kita memanfaatkan PIR Sensor dan LED Module. Apabila sistem mendeteksi gerakan tubuh kita, maka sistem akan menyalakan LED Module.

<img src="/images/04_motion_detector.png" height="400">

### Modul-modul yang dibutuhkan pada proyek ini:
* ESP8266 IoT v2.0 (1),
* ESP8266 Expansion Shield (1),
* LED Module (1),
* PIR Sensor (1).

### Hubungkan modul-modul di atas mengikuti langkah-langkah di bawah ini:
1. Pasang I/O Expansion Shield di atas ESP8266 IoT v2.0,
2. Hubungkan LED Module ke header ESP8266 Expansion Shield yang berlabel **3**,
3. Hubungkan PIR Sensor ke header ESP8266 Expansion Shield yang berlabel **5**,
4. Upload kode program [Motion_Detector](/04_Motion_Detector/Motion_Detector) ke ESP8266 IoT v2.0.

Apabila tidak terdapat kesalahan, LED Module akan berkedip selama terdapat gerakan yang dideteksi oleh PIR Sensor.
