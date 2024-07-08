# Derin Öğrenme (Deep Learning)

📒[Ders Slaytları (Lecture Slides)](https://github.com/elifbeyzatok00/Deep-Learning/tree/main/slaytlar)

📌[Laboratuvar Kodları (Laboratory Codes)](https://github.com/elifbeyzatok00/Deep-Learning/tree/main/Labaratuvar%20Kodlar%C4%B1)

📔[Ders Notları (Lecture Notes) ⭐](https://github.com/elifbeyzatok00/Deep-Learning/blob/main/Derin%20%C3%96%C4%9Freme%20Ders%20Notlar%C4%B1%202023-2024.pdf)

---
### 1. Derin Öğrenmeye Giriş (Introduction to Deep Learning)
Derin öğrenme, makine öğrenmesinin bir alt dalıdır ve yapay sinir ağlarının katmanlarının artmasıyla daha karmaşık ve yüksek doğruluklu modeller oluşturmayı hedefler. Derin öğrenme, büyük veri kümelerini ve güçlü işlem kaynaklarını kullanarak görüntü tanıma, ses tanıma, dil işleme gibi birçok alanda etkileyici sonuçlar elde eder.

🔗[Derin Öğrenmeye Giriş (Introduction to Deep Learning)](https://github.com/elifbeyzatok00/Deep-Learning/blob/main/slaytlar/1-Derin%20Ogrenmeye%20Giris.pptx)

### 2. Çok Katmanlı Sinir Ağları (Multilayer Neural Networks)
Çok katmanlı sinir ağları (MLP - Multi-Layer Perceptron), bir giriş katmanı, bir veya daha fazla gizli katman ve bir çıkış katmanından oluşur. Her bir katman, bir önceki katmandan gelen bilgiyi işler ve bir sonraki katmana ileterek, karmaşık ilişkileri öğrenir. Geri yayılım (backpropagation) algoritması, bu ağların eğitilmesinde kullanılır.

🔗[Çok Katmanlı Sinir Ağları (Multilayer Neural Networks)](https://github.com/elifbeyzatok00/Deep-Learning/blob/main/slaytlar/2-%20Cok%20Katmanl%C4%B1%20Sinir%20A%C4%9Flar%C4%B1.pptx)

### 3. Derin Öğrenme Temelleri (Deep Learning Fundamentals)
Derin öğrenme temelleri, sinir ağlarının yapısını, aktivasyon fonksiyonlarını, optimizasyon algoritmalarını ve model değerlendirme metriklerini kapsar. Temel kavramlar arasında lineer olmayan dönüşümler, overfitting/underfitting, dropout, regularizasyon ve veri artırma (data augmentation) bulunur.

🔗[Derin Öğrenme Temelleri (Deep Learning Fundamentals)](https://github.com/elifbeyzatok00/Deep-Learning/blob/main/slaytlar/3-Derin%20Ogrenme%20Temelleri.pptx)

### 4. Evrişimli Sinir Ağları (CNN - Convolutional Neural Networks)
Evrişimli sinir ağları, özellikle görüntü işleme ve bilgisayarla görme alanında kullanılan bir sinir ağı türüdür. CNN'ler, giriş görüntülerinden özellikleri otomatik olarak çıkaran ve bu özellikleri sınıflandıran evrişim katmanları (convolutional layers), havuzlama katmanları (pooling layers) ve tam bağlı katmanlardan (fully connected layers) oluşur.

🔗[Evrişimli Sinir Ağları (CNN - Convolutional Neural Networks)](https://github.com/elifbeyzatok00/Deep-Learning/blob/main/slaytlar/4-Evrisimli%20Sinir%20Aglar%C4%B1.pptx)

### 5. Üretici Çekişmeli Ağlar (GAN - Generative Adversarial Networks)
Üretici çekişmeli ağlar, iki sinir ağından oluşur: bir üretici (generator) ve bir ayrıştırıcı (discriminator). Üretici ağ, gerçekçi veriler üretmeye çalışırken, ayrıştırıcı ağ, gerçek verileri sahte verilerden ayırt etmeye çalışır. Bu iki ağ, birbirine karşı yarışarak, gerçekçi ve yüksek kaliteli veri üretimi sağlar. GAN'lar, görüntü oluşturma, ses sentezi ve veri artırma gibi birçok alanda kullanılır.

🔗[Üretici Çekişmeli Ağlar (GAN - Generative Adversarial Networks)]()

### 6. Perceptron
Perceptron, yapay sinir ağlarının en basit formudur ve tek bir sinir hücresinden (nöron) oluşur. Girdi olarak aldığı verileri ağırlıklarla çarpar, ardından bu ağırlıklı toplamı bir eşik değerle karşılaştırarak karar verir. Eşik değeri aşan çıktılar için bir aktivasyon fonksiyonu uygulanır. Perceptron, iki sınıfı ayırmak için kullanılır ve doğrusal olarak ayrılabilen verilerde etkilidir.

🔗[Perceptron](https://github.com/elifbeyzatok00/Deep-Learning/blob/main/Labaratuvar%20Kodlar%C4%B1/1-Perceptron.ipynb)

### 7. CNN Adımları (CNN Steps)
CNN'lerin temel adımları şunlardır:
1. **Evrişim (Convolution):** Giriş görüntüsü üzerinde filtreler (kernels) uygulanarak özellik haritaları oluşturulur.
2. **Aktivasyon (Activation):** Genellikle ReLU (Rectified Linear Unit) aktivasyon fonksiyonu kullanılarak, negatif değerler sıfırlanır ve doğrusal olmayan dönüşüm sağlanır.
3. **Havuzlama (Pooling):** Özellik haritalarının boyutunu küçültmek ve hesaplama maliyetini azaltmak için maksimum veya ortalama havuzlama (max pooling veya average pooling) uygulanır.
4. **Tam Bağlı Katman (Fully Connected Layer):** Havuzlama katmanlarından gelen veriler, düzleştirilir ve tam bağlı katmanlara iletilir. Bu katmanlar, sınıflandırma veya regresyon görevini yerine getirir.
5. **Çıkış Katmanı (Output Layer):** Son katmanda, genellikle softmax aktivasyon fonksiyonu kullanılarak sınıflandırma sonuçları elde edilir.

🔗[CNN Adımları (CNN Steps)](https://github.com/elifbeyzatok00/Deep-Learning/tree/main/Labaratuvar%20Kodlar%C4%B1/2-CNN%20Ad%C4%B1mlar%C4%B1)

### 8. Yapay Sinir Ağları (ANN - Artificial Neural Networks)
Yapay sinir ağları, insan beynindeki sinir hücrelerinin çalışma prensibini taklit eden hesaplama modelleridir. Temel bileşenleri nöronlar, ağırlıklar, aktivasyon fonksiyonları ve katmanlardır. Bir ANN genellikle bir giriş katmanı, bir veya daha fazla gizli katman ve bir çıkış katmanından oluşur. Nöronlar, girdileri işleyip aktivasyon fonksiyonları aracılığıyla çıktılar üretir. Bu ağlar, öğrenme sürecinde ağırlıklarını ayarlayarak verilerdeki desenleri öğrenirler. ANN'ler, çeşitli makine öğrenmesi ve derin öğrenme görevlerinde kullanılır.

🔗[Yapay Sinir Ağları (ANN - Artificial Neural Networks)](https://github.com/elifbeyzatok00/Deep-Learning/blob/main/Labaratuvar%20Kodlar%C4%B1/3-ANN_Delta.ipynb)
