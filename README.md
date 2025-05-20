# TensorFlow ile IMDB Duygu Analizi

Bu proje, IMDB film yorumları veri seti kullanılarak derin öğrenme tabanlı bir duygu analizi modeli oluşturmayı amaçlamaktadır. Amaç, bir film yorumunun olumlu mu yoksa olumsuz mu olduğunu otomatik olarak sınıflandırmaktır.

## Veri Seti

- IMDB veri seti TensorFlow Keras kütüphanesi üzerinden otomatik olarak yüklenmektedir.
- Toplam 50.000 film yorumu içerir.
- 25.000 yorum eğitim, 25.000 yorum test verisi olarak kullanılır.
- Etiketler: `positive` (olumlu) veya `negative` (olumsuz)

## Proje Hedefleri

- Veri setini ön işleyip sayısal verilere dönüştürmek
- TensorFlow ve Keras kullanarak basit bir sinir ağı modeli kurmak
- Modeli eğitip doğruluk ve kayıp gibi metriklerle değerlendirmek
- Eğitim sürecini grafiklerle analiz etmek

## Kullanılan Teknolojiler

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib

## Model Özeti

- Gömme (Embedding) katmanı ile kelimeler vektörleştirilir
- Yoğun (Dense) katmanlar ile sınıflandırma yapılır
- Kayıp fonksiyonu: Binary Cross-Entropy
- Optimizasyon: Adam
- Test verisi doğruluğu: Yaklaşık %85–90

## Nasıl Çalıştırılır?

1. `IMDB_Duygu_Analizi_Projesi_TensorFlow.ipynb` dosyasını açın
2. Tüm hücreleri sırayla çalıştırın
3. Veri seti manuel olarak indirilmeden TensorFlow üzerinden otomatik yüklenir

## Gelecekteki Geliştirmeler

- LSTM veya GRU gibi sıralı modellerle daha iyi doğruluk elde edilmesi
- İki yönlü (Bidirectional) RNN yapılarının denenmesi
- GloVe veya Word2Vec gibi önceden eğitilmiş kelime vektörlerinin kullanımı
- Çok dilli duygu analizi için veri genişletme

## Geliştirici
Ahmet Rahmanoğlu
https://www.linkedin.com/in/ahmet-rahmanoglu-675248207/
