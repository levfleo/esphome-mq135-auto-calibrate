# esphome-mq135-auto-calibrate
Yaml code for MQ135 sensor with auto calibration function<br/>

1. Compile YAML , Publish bin to ESP32 C6, and visit ESP32's web site, and wait at least 15 minutes<br/>
2. Obtain the 'RZERO reading' and 'PPM CO2 reading' values on the street, yard or outside not in other room in your house, at least 1-2 hours<br/>
3. If the values above are stable, then press button named 'Calibrate Sensor' and wait until 'CO₂ level' value are stable<br/>
4. Move esp32 to living room. CO₂ level values displays relativly Air Quality from outside air quailty to living rooms values.<br/>
5. CO₂ PPM values meanings in YAML file, below the 1000 meanings is clear air conditions.<br/>
6. To reset to factory settings, press 'Return to Factory settings' button. And needs re-calibrate sensor<br/>
7. Calibration settings is persistent but only based for calibrated outside values. No need to re-calibrate on restart, re-power and awake from deepsleep.<br/>
8. If you move another new apartment, city, country etc must re-calibrate.<br/> 
9. DHT11 sensor for Humidity & Temperature. You can easly change different sensor type.<br/>

MQ135 sensor supply voltage 5V , GPIO Pin GPIO4
DHT11 sensor supply voltage 3.3V , GPIO Pin GPIO0


# esphome-mq135-auto-calibrate
MQ135 sensörü ile hava kalitesi ölçümü, otomatik kalibrasyon özellikli <br/>

1. YAML dosyasını indirin  ve derleyip esp32 makinanıza kurun, esp32'nin web sayfasını açın, <br/>
2. Aleti odadan dşarıya, bahçeye veya açık havaya çkarın, 'RZERO Okunan' ve 'PPM CO2 Okunan' değerlerini, ev dışında açık havada 1-2 saat gözleyin<br/>
3. Değerler artık neredeyse sabitlendiğinde 'Kalibre et' butonuna basın.<br/>
4. Ayarlama işlemi tamamdır, esp32'yi odanıza getirin değerlerin 1-2 dk sonra değiştiğini göreceksiniz, değerler dışardakinden yüksek olacaktır ki normal, yaml dosyasında CO₂ değerlerinin anlamı var, ona göre ne yapacağınıza karar verirsiniz, 1000 değeri altı tertemiz hava demek.<br/>
5. Ayarları sıfırlamak için 'Fakrika ayarlarına Dön' butonuna basabilirsiniz.<br/>
6. Kalibrasyon değerleri kalıcıdır, Makina yeniden başladığnda, uykudan uyandığında, tekrar güç verildiğinde,  tekrar kalibre etmenize GEREK YOKTUR.<br/>
7. Başka bir eve, semte, ya da şehir veya ülkeye giderseniz tekrar kalibre etmelisiniz.<br/>
8. Sıcaklık ve nem için DHT11 sensörü kullanılmıştır. Başka sensörle kolayca değiştirebilirsiniz.<br/>

MQ135 sensorü besleme voltajı 5V , GPIO Pin GPIO4
DHT11 sensorü besleme voltajı 3.3V , GPIO Pin GPIO0
