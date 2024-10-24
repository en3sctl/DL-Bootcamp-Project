# Akbank Derin Öğrenme Bootcamp Projesi - Balık Türü Sınıflandırma

Bu proje, Kaggle'daki büyük ölçekli bir balık veri setini kullanarak balık türlerini sınıflandırmayı amaçlamaktadır. Projede derin öğrenme teknikleri kullanılarak bir yapay sinir ağı (ANN) modeli geliştirilmiştir.

# Proje Yapısı

Veri Ön İşleme: Balık fotoğraflarından oluşan veri setinin işlenmesi, görüntülerin bir DataFrame'e dönüştürülmesi ve eğitim/veri test setlerine ayrılması.

Model Oluşturma: TensorFlow/Keras ile yapay sinir ağı (ANN) mimarisi kullanılarak sınıflandırma modeli oluşturulmuştur. Modelde katmanlar, aktivasyon fonksiyonları ve dropout katmanları yer almaktadır.

Model Eğitimi ve Değerlendirme: Model, eğitim verileriyle eğitilmiş ve başarı metrikleriyle değerlendirilmiştir. Accuracy (doğruluk) ve loss (kayıp) gibi metrikler kullanılarak performans analiz edilmiştir.

Hiperparametre Optimizasyonu: Modelin performansını artırmak için katman sayısı, düğüm sayısı, dropout oranı ve optimizasyon fonksiyonları üzerinde ince ayarlamalar yapılmıştır.

# Gereksinimler

    Python 3.x
    TensorFlow/Keras
    NumPy
    Pandas
    Matplotlib

# Nasıl Çalıştırılır

    Jupyter notebook'u çalıştırarak modeli eğitin.
    Proje çıktıları ve sonuçları notebook üzerinde görüntülenebilir.

# Kaggle Linki

Projenin Kaggle üzerindeki notebook'una [link](https://www.kaggle.com/code/enescatal/akbank-derin-renme-proje#Ad%C4%B1m-2:-Verileri-g%C3%B6rselle%C5%9Ftirme) buradan ulaşabilirsiniz.
