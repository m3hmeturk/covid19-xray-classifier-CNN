# CNN ile Akciğer Röntgeni Sınıflandırma (COVID-19)

Bu proje, akciğer röntgen görüntülerini Konvolüsyonel Sinir Ağları (CNN) kullanarak analiz etmek ve görüntüleri 3 farklı sağlık durumuna göre sınıflandırmak amacıyla geliştirilmiş bir derin öğrenme modelidir.

## 📌 Veri Seti
Modelin eğitiminde Kaggle üzerinde bulunan [COVID-19 Radiography Database](https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database) kullanılmıştır. 

Modelin dengeli ve verimli bir şekilde eğitilebilmesi için her bir sınıftan eşit sayıda (1.000'er adet) görsel çekilerek özel bir alt veri seti oluşturulmuştur.

* **Sınıflar (3 Adet):** COVID-19, Normal, Viral Pnömoni
* **Sınıf Başına Görsel:** 1.000 adet
* **Toplam Kullanılan Görsel:** 3.000 adet

## 🚀 Kullanılan Teknolojiler
* Python
* TensorFlow / Keras (veya PyTorch)
* NumPy & Pandas (Veri işleme)
* Matplotlib & Seaborn (Görselleştirme)

## 🧠 Model Mimarisi
* Görüntü işleme ve özellik çıkarımı için özel olarak tasarlanmış Konvolüsyonel Sinir Ağı (CNN) katmanları.
* Sınıflandırma için Fully Connected (Tam Bağlı) katmanlar.
* Çoklu sınıflandırma (Multi-class classification) olduğu için çıkış katmanında 3 nöron ve Softmax aktivasyon fonksiyonu kullanılmıştır.

## 📊 Eğitim Sonuçları ve Başarım
*(Not: Bu bölüme modelinin eğitim sonundaki test accuracy - doğruluk oranını, loss grafiğini veya karmaşıklık matrisini (confusion matrix) ekleyebilirsin. Örneğin: "Model test verisi üzerinde %94 doğruluk oranına ulaşmıştır.")*

## 🛠️ Nasıl Çalıştırılır?
Projeyi kendi bilgisayarında denemek istersen aşağıdaki adımları izleyebilirsin:

1. Repoyu bilgisayarına klonla: 
   ```bash
   git clone [https://github.com/KULLANICI_ADIN/reponun-ismi.git](https://github.com/KULLANICI_ADIN/reponun-ismi.git)
