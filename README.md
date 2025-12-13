# esphome-mq135-auto-calibrate
Yaml code for MQ135 sensor with auto calibration function<br/>

1. Download the firmware with the file. Compile and visit ESP32's web site, and wait at least 15 minutes<br/>
2. Obtain the 'RZERO reading'  and 'PPM CO2 reading' values on the street, yard or outside not in other room in your house, at least 1-2 hours<br/>
3. If the values above are stable, then press button named 'Calibrate Sensor' and wait until 'CO₂ level' value are stable<br/>
4. Move esp32 to living room. CO₂ level values displays relativly Air Quality from outside air quailty to living rooms values.<br/>
5. To reset to factory setings, press 'Return to Factory settings' button. And needs re-calibrate sensor<br/>
6. Calibration settings is persistent but only based for outside values. No need to re-calibrate on restart, re-power and awake from deepsleep.<br/>
7. If you move another new apartment, City, Country etc must re-calibrate.<br/> 
8. DHT11 sensor for Humidit & Temperature. You can easly change diffent sensor type.<br/>

#esphome-mq135-auto-calibrate
 
# esphome-mq135-auto-calibrate
MQ135 sensörü ile hava kalitesi ölçümü, otomatik kalibrasyon özellikli <br/>

1. YAML dosyasını indirin  ve derleyip esp32 makianaıza kurun, esp32 nin web sayfasını açın, <br/>
2. 'RZERO Okunan' ve  'PPM CO2 Okunan' değerlerini, ev dışında açık havada 1-3 saat gözleyin<br/>
3. Değerler artık neredeyse sabitlendiğinde 'Kalibre et' butonuna basın<br/>
4. Ayarlama işlemi tamamdır<br/>
5. Ayarları sıfırlamak için 'Fakrika ayarlarına Dön' butonuna basabilirsiniz.<br/>
6. Makina yeniden başladğnda tekrar kalibre etmenize GEREK YOKTUR.
7. 7. Bşka bir eve, semte, ya da şehir veya ülkeye giderseniz tekrar kalibre etmelisiniz.<br/>
8. Sıcaklık ve nem için DHT11sensörü kullanılmıştır.<br/>
