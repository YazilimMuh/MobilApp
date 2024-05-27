Hayvan Sağlığı Takip Mobil Uygulaması
Bu proje, hayvanların sağlığını izlemek için bir mobil uygulamadır. Uygulama, sıcaklık, nem, karbondioksit ve karbonmonoksit seviyelerini sensörler aracılığıyla ölçerek Firebase'e kaydeder ve bu verileri analiz ederek koyun, leylek, bıldırcın ve köpek gibi hayvanların sağlığına olan etkilerini değerlendirir.

Özellikler
Sıcaklık ve Nem İzleme: DHT11 sensörü ile ortamın sıcaklık ve nem değerlerini ölçer.
Karbondioksit İzleme: MQ02 sensörü ile karbondioksit (CO2) seviyelerini ölçer.
Karbonmonoksit İzleme: MQ135 sensörü ile karbonmonoksit (CO) seviyelerini ölçer.
Veri Kaydı: NodeMCU ile elde edilen verileri Firebase'e kaydeder.
Gerçek Zamanlı Görüntüleme: Mobil uygulama ile sıcaklık, nem, karbondioksit ve karbonmonoksit seviyelerini anlık olarak görüntüler.
Hayvan Sağlığı Değerlendirme: Belirli hayvanlar için (koyun, leylek, bıldırcın, köpek) ideal çevresel koşullar dışında olup olmadığını kontrol eder ve kullanıcıya bilgi verir.
Kurulum
Gereksinimler:

NodeMCU
DHT11 sensörü
MQ02 sensörü
MQ135 sensörü
Firebase hesabı
NodeMCU ve Sensörlerin Bağlantısı:

DHT11, MQ02 ve MQ135 sensörlerini NodeMCU'ya bağlayın.
Sensörlerin bağlantı şemaları için ilgili dokümanlara başvurabilirsiniz.
Firebase Ayarları:

Firebase'de yeni bir proje oluşturun.
Proje ayarlarından Firebase gerçek zamanlı veritabanı URL'sini alın.
NodeMCU kodunda gerekli Firebase ayarlarını yapın.
NodeMCU Kodunu Yükleme:

NodeMCU'yu bilgisayarınıza bağlayın.
Arduino IDE veya uygun bir platform kullanarak kodu NodeMCU'ya yükleyin.
Mobil Uygulama Kurulumu:

Projeyi yerel makinenize klonlayın.
Uygulama kodlarını derleyip cihazınıza yükleyin.
Uygulama içindeki Firebase bağlantı ayarlarını güncelleyerek, kendi veritabanınızı kullanacak şekilde yapılandırın.
Kullanım
Uygulamayı açın ve sensörlerden gelen verilerin ekranda görüntülenmesini bekleyin.
Sıcaklık, nem, karbondioksit ve karbonmonoksit seviyelerinin anlık durumunu görebilirsiniz.
Uygulama, belirli hayvanlar için ideal çevresel koşulların dışına çıkıldığında uyarı verir.
Ekran Görüntüleri
![image](https://github.com/YazilimMuh/MobilApp/assets/104653734/b5a27db9-0820-4695-92e5-3a70c97933ee)

Lisans
Bu proje MIT Lisansı ile lisanslanmıştır. Daha fazla bilgi için LICENSE dosyasına bakın.

Katkıda Bulunma
Katkıda bulunmak isterseniz, lütfen bir pull request gönderin ya da bir issue açın. Her türlü geri bildirim ve katkı değerlidir.

İletişim
Herhangi bir soru veya geri bildiriminiz için lütfen iletişime geçin: ibrahimaydn231@gmail.com

Bu proje, hayvanların sağlığını izlemek için çevresel verileri kullanarak önemli bilgiler sunar ve geliştiricilere faydalı bir araç sağlar. Umarız bu projeyi kullanırken keyif alırsınız!

