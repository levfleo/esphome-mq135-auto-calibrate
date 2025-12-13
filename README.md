# esphome-mq135-auto-calibrate
Yaml code for MQ135 sensor with auto calibration function<br/>

1. Download the firmware with the file. Compile and visit ESP32's web site<br/>
2. Obtain the 'RZERO Okunan'(en: RZERO actual readings)  and 'PPM CO2 Okunan' (en: 'PPM CO  Actual readings') values on the street.<br/>
3. Push button named 'Kalibre et' (en:Make Calibration)<br/>
4. Download the firmware again.<br/>
5. To reset to factöry setings, press 'Fakrika ayarlarına Dön' (en: Factory reset) button.<br/>
6. Calibration settings is persistent. No need to calibrate restart, re-power and awake from deepsleep.<br/>
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
