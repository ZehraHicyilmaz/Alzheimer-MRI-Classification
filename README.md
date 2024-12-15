# Alzheimer-MRI-Classification
Alzheimer MRI görüntüleriyle sınıflandırma yapan bir CNN modeli.


## Proje Açıklaması
Bu proje, Alzheimer hastalığının erken teşhisini kolaylaştırmak amacıyla Kaggle'dan alınan **Alzheimer MRI Disease Classification Dataset** kullanılarak bir Derin Öğrenme modeli geliştirmeyi hedeflemektedir. Proje kapsamında bir **Convolutional Neural Network (CNN)** modeli eğitilmiş ve yüksek doğruluk oranı ile sonuç alınmıştır.

## Veri Seti
**Kaynak:** [Kaggle - Alzheimer MRI Disease Classification Dataset](https://www.kaggle.com/)

Veri seti, Alzheimer hastalığını dört farklı kategoriye ayıran MRI görüntülerini içermektedir:
- **Mild Demented**
- **Moderate Demented**
- **Non Demented**
- **Very Mild Demented**

### Veri Seti Özeti:
- Toplam Görüntü Sayısı:  
- Görüntü Boyutları: 
- Kategori Dağılımı:
  - Non Demented: 
  - Mild Demented: 
  - Moderate Demented: 
  - Very Mild Demented: 

## Kullanılan Teknolojiler ve Kütüphaneler
- **Python 3.x**
- **TensorFlow/Keras**
- **NumPy**
- **Matplotlib**
- **Pandas**

## Model
Proje kapsamında kullanılan model bir **Convolutional Neural Network (CNN)** yapısıdır.

### Model Mimarisi
- **Conv2D:** 2D konvolüsyonel katmanlar
- **MaxPooling2D:** Boyut azaltma
- **Dropout:** Overfitting'i önlemek için
eklendi
- **Dense:** Fully connected katmanlar

### Eğitim Parametreleri:
- **Epoch Sayısı:** 
- **Batch Size:** 
- **Learning Rate:** 
- **Optimizer:** Adam
- **Loss Function:** Categorical Crossentropy

### Performans:
- **Eğitim Doğruluğu:** 
- **Doğrulama Doğruluğu:** %97

## Nasıl Çalıştırılır?
1. Bu repository'yi klonlayın:
    ```bash
    git clone https://github.com/kullaniciadi/Alzheimer-MRI-Classification.git
    ```
2. Gerekli kütüphaneleri yükleyin:
    ```bash
    pip install -r requirements.txt
    ```
3. Modeli çalıştırmak için notebook'u açın ve hücreleri sırayla çalıştırın.

## Sonuçlar
Bu proje, Alzheimer MRI görüntülerinde sınıflandırma için etkili bir yöntem sunmuştur. Modelin yüksek doğruluk oranı, hastalığın teşhisinde yardımcı olabileceğini göstermektedir.

## Katkıda Bulunun
Herhangi bir öneriniz veya geliştirme fikriniz varsa lütfen pull request gönderin veya issue oluşturun.

## Lisans
Bu proje [MIT Lisansı](LICENSE) ile lisanslanmıştır.
