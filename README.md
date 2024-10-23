# -Kaggle-Balik-Tur-Siniflandirma-Projesi
Kaggle Balık Türü Sınıflandırma Projesi
Proje Hakkında
Bu proje, farklı balık türlerini sınıflandırmak için derin öğrenme yöntemleri kullanarak bir yapay sinir ağı modeli geliştirmeyi amaçlamaktadır. Proje, Kaggle'da bulunan büyük bir balık görüntüleri veri seti üzerinde çalışmaktadır. Model, görüntüleri analiz ederek belirli balık türlerini doğru bir şekilde tanımlamak için eğitilmiştir.

İçindekiler:
Gerekli Kütüphaneler
Veri Seti
Modelin Eğitimi
Sonuçların Değerlendirilmesi
Kullanım Talimatları
Gerekli Kütüphaneler
Bu projede kullanılan kütüphaneler:

NumPy
Pandas
OpenCV
Keras
Matplotlib
Seaborn
scikit-learn
Veri Seti
Proje, /kaggle/input/a-large-scale-fish-dataset/train/ dizininde bulunan balık görüntülerinden oluşan bir veri seti kullanmaktadır. Veri seti, çeşitli balık türlerinin görüntülerini içerir. Proje, bu görüntüleri yükler, ön işler ve sınıflandırma için hazırlamaktadır.

Modelin Eğitimi
Görüntü Yükleme ve Ön İşleme: Görüntüler, belirtilen boyutlarda (128x128) yeniden boyutlandırılır ve normalizasyon işlemi yapılır.
Etiketleme: Balık türleri sayısal hale getirilir ve kategorik etiketler oluşturulur.
Eğitim ve Test Setlerine Ayırma: Veri, eğitim (%80) ve doğrulama (%20) setlerine ayrılır.
Model Oluşturma: Basit bir yapay sinir ağı modeli (ANN) oluşturulur.
Modeli Eğitme: Model, eğitim verisi ile eğitilir ve doğrulama verisi ile değerlendirilir.
Sonuçların Değerlendirilmesi
Modelin performansı, doğruluk grafikleri ve kayıp grafikleri ile görselleştirilir. Ayrıca, karmaşıklık matrisi ve sınıflandırma raporu ile modelin başarısı değerlendirilir.

Kullanım Talimatları
Projeyi yerel bir makinede çalıştırmak için gerekli kütüphanelerin yüklü olduğundan emin olun.
Balık veri setini Kaggle'dan indirin ve projede belirtilen dizine yerleştirin.
Python ortamında script'i çalıştırarak modeli eğitin ve sonuçları değerlendirin.
Sonuç
Bu proje, derin öğrenme kullanarak balık türlerini sınıflandırmak için etkili bir yöntem sunmaktadır. Proje, görüntü işleme ve makine öğrenimi alanındaki uygulamalar için bir temel oluşturmaktadır.

