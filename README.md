# SkinCanser
## 📊 Veri Seti

Bu proje, not defterinde `Skin_Data.zip` olarak adlandırılan harici bir veri
seti ile eğitilmiştir.

**ÖNEMLİ NOT: VERİ SETİ BU DEPOYA DAHİL DEĞİLDİR.**

Veri seti, boyutu ve bilinmeyen lisans/kaynak durumu nedeniyle bu depoya
yüklenmemiştir. `.gitignore` dosyası ile yüklenmesi engellenmiştir.

### Projeyi Çalıştırmak İçin

Bu not defterini kendi verilerinizle çalıştırmak için:

1.  **HAM10000 (Skin Cancer MNIST)** veya **ISIC Arşivi** gibi halka açık ve
    güvenilir kaynaklardan kendi cilt kanseri veri setinizi temin etmeniz
    gerekmektedir.
    * *Örnek Kaynak (HAM10000):*
        `https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000`
2.  İndirdiğiniz veri setini, not defterindeki kodun (`cv2.imread`, `pd.read_csv`
    vb.) okuyabileceği şekilde yeniden düzenlemelisiniz.
3.  Not defterindeki veri okuma yollarını (path) kendi dosya yapınıza göre
    güncellemelisiniz.