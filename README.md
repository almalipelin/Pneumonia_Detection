# Pneumonia_Detection
# Derin Öğrenme ile Zatürre (Pneumonia) Tespiti 🫁

Bu proje, Derin Öğrenme (Deep Learning) yöntemleri kullanılarak akciğer röntgen görüntüleri üzerinden Zatürre teşhisi koyan bir yapay zeka uygulamasıdır. **Transfer Learning (VGG16)** mimarisi kullanılarak geliştirilmiştir.

## 🎯 Projenin Amacı
Zatürre, dünya genelinde ciddi sağlık sorunlarına yol açan bir hastalıktır. Bu proje, radyologların iş yükünü azaltmak ve röntgen görüntülerinden otomatik analiz yaparak erken teşhis için bir **karar destek sistemi** sunmayı amaçlar.

## 📊 Veri Seti
Projede Kaggle'dan alınan **"Chest X-Ray Images (Pneumonia)"** veri seti kullanılmıştır.
- **Eğitim ve Test:** Veriler eğitim ve doğrulama setlerine ayrılarak modelin başarısı ölçülmüştür.
- **Veri Ön İşleme:** Modelin ezberlemesini önlemek için Data Augmentation (Resim döndürme, yakınlaştırma) teknikleri uygulanmıştır.

## ⚙️ Kullanılan Yöntemler
- **Model:** VGG16 (ImageNet ağırlıkları ile Transfer Learning)
- **Platform:** Google Colab (T4 GPU)
- **Arayüz:** Gradio (Web tabanlı kullanıcı arayüzü)
- **Başarı Oranı:** %88+ (Test Doğruluğu)

## 📈 Sonuç Grafikleri
Eğitim süresince elde edilen Başarı (Accuracy) ve Kayıp (Loss) grafikleri aşağıdadır:

![Başarı Grafiği](sonuc_grafikleri.png)
<img width="990" height="374" alt="image" src="https://github.com/user-attachments/assets/be49b446-186a-46e8-82ff-eaef3e59c1d3" />


## 🚀 Kurulum ve Test
Proje dosyasını (`.ipynb`) Google Colab üzerinde açarak çalıştırabilirsiniz. Model eğitildikten sonra Gradio arayüzü otomatik olarak açılacaktır.

---
