# GostergeAndButtonBoxV1
Bu depoda sizlere oyunlar için hem gösterge hem de ButtonBox olarak çalışan bir sistemin nasıl yapılacağını anlattım.

# Başlamadan önce...

Bu proje için kullanılan yazılım her oyunu desteklemez. Desteklenilen oyunlar listesi için [burayı](https://www.simhubdash.com/supported-games/ "SimHub desteklenen oyunlar listesi") ziyaret edin. Ayrıca 3D Model ve Pleksi Lazer Kesim için gereken dosyalar depoda mevcuttur.

# Hazırlıklar

### Donanım için gerekenler : 

- Herhangi bir Arduino kartı (Eğer ButtonBox özelliğini istiyorsanız Arduino Leonardo ya da Pro Micro kullanmalısınız, diğer kartlar ButtonBox özelliğini tam olarak desteklemiyor.)
- 10 adet DC184 buton (Bu butonları pleksi üzerindeki buton deliklerinin yarıçapını değiştirerek güncelleyebilir ya da ek yapabilirsiniz.)
- 4*20 LCD Ekran (2*16 LCD ekran kullanılamaz.)
- LCD Ekran için I2C Modülü (ZORUNLU)
- 2 adet WS2812B RGB LED Stick
- 8*8 Dot Matrix (Kartı ile beraber)
- Mini Breadboard
- Bir sürü Jumper Kablo
- Pleksi Levha (Lazer kesim dosyası aşağıdadır.)
- 3B model parçalar (3D Baskı hizmeti veren bir yerden temin edebilirsiniz ya da fotoblok kullanabilirsiniz.)
- 4 adet M3 4mm'lik vida 
- 4 adet M3 somun
- 4 adet M3 8mm Erkek - Dişi Aralayıcı

### Yazılım için gerekenler : 

Proje yazılımı için SimHub adlı uygulamaya ihtiyacımız var. [Bu bağlantıdan](https://www.simhubdash.com/download-2/ "SimHub indirme linki") indirebilir ve bilgisayarınıza kurabilirsiniz.

# Yapım Aşaması

1. Öncelikle devreyi kurun. Ben bu şekilde kurdum. Siz güncelleyebilirsiniz fakat bunları kodda güncellemeyi unutmayın. (LCD Ekran pinlerini değiştiremezsiniz. Sadece arduino modeli değişirse pinler değişir.)
![Devre Şeması](devre.png "Devre Şeması")



