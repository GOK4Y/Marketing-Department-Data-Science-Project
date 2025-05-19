<details> <summary><strong>README.md içeriğini görmek için tıkla</strong></summary>
🎯 Marketing Department Customer Segmentation Project
Bu proje, bir kredi kartı müşteri veri seti üzerinde müşteri segmentasyonu gerçekleştirmek amacıyla geliştirilmiştir. Makine öğrenmesi ve derin öğrenme tabanlı yöntemlerle müşterilerin davranış kalıplarını keşfetmeyi ve pazarlama stratejilerini destekleyecek öngörücü modeller oluşturmayı hedefler.

📊 Proje Amacı
Kredi kartı müşteri verilerini analiz ederek müşteri segmentleri belirlemek

Farklı segmentlerin harcama ve ödeme alışkanlıklarını incelemek

Pazarlama kampanyalarını hedef segmentlere yönelik optimize etmek

🧠 Kullanılan Yöntemler
Veri Yükleme ve Ön İşleme

Keşifsel Veri Analizi (EDA) ve görselleştirme

Özellik Mühendisliği

K-Means Kümeleme

Optimum küme sayısını Elbow Method ile belirleme

Boyut İndirgeme

PCA (Principal Component Analysis) ile görselleştirme

Autoencoder tabanlı boyut indirgeme

Model Değerlendirme

Silhouette Score

Küme içi ve küme dışı mesafe analizleri

🛠️ Kullanılan Teknolojiler
Python

pandas, numpy, matplotlib, seaborn

scikit-learn

keras (TensorFlow backend)

Google Colab / Jupyter Notebook

📁 Dosya Yapısı
Dosya	Açıklama
Marketing_Department_Skeleton().ipynb	Projenin ana Jupyter defteri. Tüm adımlar bu dosyada yer alır.
README.md	Proje tanıtımı ve çalışma adımları hakkında özet belge.
data/	Kredi kartı müşteri verilerini içeren CSV dosyası.

🔍 Veri Kümesi
Kaggle’dan indirilen kredi kartı müşteri veri seti;
yaş, cinsiyet, eğitim, yıllık gelir, kredi limiti,
alışveriş tutarları, nakit avans bilgileri ve ödeme istatistikleri
gibi demografik ve finansal özellikleri içerir.

🚀 Nasıl Kullanılır?
Google Colab üzerinde veya yerel Jupyter ortamında Marketing_Department_Skeleton().ipynb dosyasını açın.

Gerekli kütüphaneleri yükleyin:

bash
Kopyala
Düzenle
pip install pandas numpy scikit-learn keras matplotlib seaborn
Drive’ınızı bağlayın ve data/ccdata.csv dosyasının yolunu belirtin.

Hücreleri sırayla çalıştırarak tüm analiz ve modelleme adımlarını gerçekleştirin.

Tüm hücreleri tek seferde çalıştırmak için: Runtime > Run all

📈 Model Performansı
Elbow Method sonucu optimum 4–5 küme olarak belirlendi.

Silhouette Score ile her bir kümenin ayrışma ve iç tutarlılığı değerlendirildi.

PCA ve Autoencoder çıktıları, veri setinin iki boyuta indirgenmiş görselleştirmelerini içerir.

✍️ Katkıda Bulunma
Eğitim ve araştırma amaçlı hazırlanmıştır.
İyileştirme önerileriniz ve katkılarınız için lütfen pull request gönderin!

📜 Lisans
MIT Lisansı

</details>
