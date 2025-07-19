# Trafik Tahmin Projesi

Bu proje, Mayıs-Haziran 2025 tarihleri arasında Ankara’daki belirli caddelerde gözlemlenen trafik yoğunluğunu analiz etmeyi ve çeşitli parametreler (saat, hava durumu, gün türü vb.) üzerinden tahmin etmeyi amaçlamaktadır.

## 🔍 Problem Tanımı

Trafik, şehir yaşamının önemli sorunlarından biridir. Özellikle işe gidiş ve çıkış saatlerinde (08:30 ve 17:00 civarı), hava durumu gibi dış faktörlerle birleşerek ciddi yoğunluklara yol açabilir. Bu çalışmada Ankara’daki trafik yoğunluğu, çeşitli değişkenler üzerinden analiz edilecek ve tahmin modeli geliştirilecektir.

## 📁 Veri Seti

- **Zaman Aralığı:** 01 Mayıs – 30 Haziran 2025
- **Saatler:** 07:30, 08:30, 09:30, 16:30, 17:30, 18:30
- **Gün Türü:** Hafta içi ve hafta sonu ayrı değerlendirildi.
- **Hava Durumu:** Güneşli, parçalı bulutlu, yağmurlu, sağanak, sisli vb.

## 🛠️ Kullanılan Yöntemler

- Manuel veri oluşturma
- Basit doğrusal regresyon (veya logistic regression)
- Özellik mühendisliği (saat, hava durumu kodlama)
- Model performansı: doğruluk, loss vb.

## 🧠 Eğitim ve Modelleme

Kodlar ve modeller `notebooks/` ve `src/` klasörlerinde yer alacaktır. Modeller farklı hava koşulları ve saat dilimlerinde test edilmiştir.

## 📊 Sonuçlar

Modellerin eğitimi ve testleri sonucunda aşağıdaki gözlemler elde edilmiştir:
- Yağmurlu havalarda trafik belirgin şekilde artmaktadır.
- Sabah ve akşam saatleri arasında farklı trafik profilleri gözlemlenmiştir.
- Hafta sonları trafik genellikle daha düşüktür.

## 📎 Kaynaklar

- Veri gözlemleri ve hava durumu verileri manuel olarak oluşturulmuştur.
- Kodlar ve sonuçlar bu repository’de yer almaktadır.
