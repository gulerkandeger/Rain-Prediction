# Rain Prediction in Australia
 ![image](https://github.com/gulerkandeger/Rain-Prediction/assets/77187949/b948e8ba-8153-4ce8-82c3-e3472b2afab4)


#### Projenin Amacı : "Yağış Tahmini"

Bu proje, Avustralya genelinde 10 yıl boyunca toplanan günlük hava gözlemleri veri seti üzerinde odaklanmaktadır. Temel amacı, bir sonraki günün yağış durumunu tahmin etmek için sınıflandırma modelleri oluşturmak ve bu modelleri kullanarak etkili bir yağış tahmini yapmaktır.

#### Data Content

* Date: Gözlem tarihi
* Location: Hava istasyonunun ortak adı <br>
* MinTemp: Derece Celsius cinsinden minimum sıcaklık<br>
* MaxTemp: Derece Celsius cinsinden maksimum sıcaklık<br>
* Rainfall: Gün boyunca kaydedilen yağış miktarı (mm)<br>
* Evaporation: 9 sabahına kadar olan 24 saatlik süre içinde meydana gelen sözde A sınıfı buharlaşma (mm)<br>
* Sunshine: Günde parlak güneş ışığı süresi (saat)<br>
* WindGustDir: Gece yarısına kadar olan 24 saat içinde en güçlü rüzgar püskürmesinin yönü<br>
* WindGustSpeed: Gece yarısına kadar olan 24 saat içinde en güçlü rüzgar püskürmesinin hızı (km/saat)<br>
* WindDir9am: Sabah 9'da rüzgarın yönü<br>
* WindDir3pm: Öğleden sonra 3'te rüzgarın yönü<br>
* WindSpeed9am: Sabah 9'da rüzgarın hızı<br>
* WindSpeed3am: Öğleden sonra 3'te rüzgarın hızı<br>
* Humidity9am: Sabah 9'da nem<br>
* Humidity3pm: Öğleden sonra 3'te nem<br>
* Pressure9am: Sabah 9'da basınç<br>
* Pressure3pm: Öğleden sonra 3'te basınç<br>
* Cloud9am: Sabah 9'da bulut örtüsü<br>
* Cloud3pm: Öğleden sonra 3'te bulut örtüsü<br>
* Temp9am: Sabah 9'da sıcaklık<br>
* Temp3pm: Öğleden sonra 3'te sıcaklık<br>
* RainToday: Bugün yağmur yağdı mı?<br>
* RainTomorrow: Sonraki gün yağmur yağdı mı?<br>

#### Proje Özet
###### 1. Import Libraries <br>
* Gerekli kütüphaneler import edildi.
###### 2. Read Data and Analysis<br>
* 'WeatherAUS' veri setinden veriler okundu ve analiz edildi.
###### 3. Preprocessing<br>
* Missing Value<br>
* Encoding Categorical Features<br>
* Scaling<br>
* Train/Test Split<br>
###### 4. Modelling<br>
* Logistic Regression ve K-NN algoritmaları kullanılarak 2 farklı model oluşturuldu.
###### 5. Evaluation of Models<br>
* Modellerin confusion matrix ve accuracy değerlerine bakılarak model başarıları karşılaştırıldı. <br>
  

#### Sonuç
![rain_cm_logr](https://github.com/gulerkandeger/Rain-Prediction/assets/77187949/67302141-3351-457a-9d6c-ad02516c4391)
![rain_cm_knn](https://github.com/gulerkandeger/Rain-Prediction/assets/77187949/eb17294d-05f9-4500-b577-6117587f987e) <br>
Modellerin accuracy değerleri şu şekildedir ; <br>
Logistic Regression Accuracy : 0.8478605058122578 <br>
K-NN Accuracy : 0.8422982375734345
