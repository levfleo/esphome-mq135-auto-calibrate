# esphome-mq135-auto-calibrate
Yaml code for MQ135 sensor with auto calibration function<br/>

1. Download the firmware with the file. Compile and visit ESP32's web site, and wait at least 15 minutes<br/>
2. Obtain the 'RZERO reading'  and 'PPM CO2 reading' values on the street at least 1-2 hours<br/>
3. If the values above are stable, then press button named 'Calibrate Sensor' and wait until 'CO₂ level' value are stable<br/>
4. Re compile and upload the firmware again.<br/>
5. To reset to factöry setings, press 'Return to Factory settings' button.<br/>
6. Calibration settings is persistent but only same room. No need to re-calibrate on restart, re-power and awake from deepsleep.<br/>
7. DHT11 sensor for Humidit & Temperature. You can easly change diffent sensor type.<br/>

#esphome-mq135-auto-calibrate
 
# esphome-mq135-auto-calibrate
MQ135 sensörü ile hava kalitesi ölçümü, otomatik kalibrasyon özellikli <br/>

1. YAML dosyasını indirin  ve derleyip esp32 makianaıza kurun, eso32 nin web sayfasını açın, <br/>
2. 'RZERO Okunan' ve  'PPM CO2 Okunan' değerlerini, ev dışında açık havada 1-3 saat gözleyin<br/>
3. Değerler artık neredeyse sabitlendiğinde 'Kalibre et' butonuna basın<br/>
4. Ayarlama işlemi tamamdır<br/>
5. Ayarları sıfırlamak için 'Fakrika ayarlarına Dön' butonuna basabilirsiniz.<br/>
6. Makina yeniden başladğnda tekrar kalibre etmenize GEREK YOKTUR.
7. Sıcaklık ve nem için DHT11sensörü kullanılmıştır.<br/>
