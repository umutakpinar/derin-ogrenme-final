# Pneumonia Görüntüleri Üzerinde Sınıflandırma: CNN, Transfer Learning ve Yapay Sinir Ağı Modellerinin Performans Analizi

:information_source: **Dersin Kodu:** [YAZ20411](https://ebp.klu.edu.tr/Ders/dersDetay/YAZ20411/716026/tr)  
:information_source: **Dersin Adı:** [DERİN ÖĞRENME](https://ebp.klu.edu.tr/Ders/dersDetay/YAZ20411/716026/tr)  
:information_source: **Dersin Öğretim Elemanı:** Öğr. Gör. Dr. Fatih BAL  [Github](https://github.com/balfatih)   |    [Web Sayfası](https://balfatih.github.io/)
   
---

## Grup Bilgileri

| Öğrenci No | Adı Soyadı           | Bölüm          		   | Proje Grup No | Grup Üyelerinin Github Profilleri                 |
|------------|----------------------|--------------------------|---------------|---------------------------------------------------|
|1200505033  | Esma KÖROĞLU		    | Yazılım Mühendisliği     | PROJE_19       | [Github](https://github.com/esmakrgl)            |
|1200505041  | Sümeyra AYDIN        | Yazılım Mühendisliği     | PROJE_19       | [Github](https://github.com/balfatih)            |
|1200505068  | Buğra GÖRMÜŞ         | Yazılım Mühendisliği     | PROJE_19       | [Github](https://github.com/bugragormus)         |
|1190505805  | Recep Umut AKPINAR   | Yazılım Mühendisliği     | PROJE_19       | [Github](https://github.com/umutakpinar)         |

---

## Proje Açıklaması

**Projenin Amacı ve Kapsamı** : Projemizde, Zatürre (Pneumonia) hastalığına ait X-ray görüntülerinden oluşan bir veri seti kullanarak farklı yapay zeka teknikleriyle (evrişimli sinir ağları, transfer öğrenme, yapay sinir ağları)  Viral ve Bakteriyel Zatürre'nin sınıflandırma modellerini oluşturduk. Bu modellerin performanslarını karşılaştırarak değerlendirme yaptık. Ayrıca Görüntüleri işleyerek,hastalığın bu iki türü arasındaki farklılıkları tespit etmeyi amaçladık.

**Kullanılan Teknolojiler** : Projemizde X-ray görüntülerinden oluşan bir veri seti kullandık. Python programlama dilini kullandık. Modelleri oluşturmak ve eğitmek için derin öğrenme kütüphaneleri olan TensorFlow ve Keras kütüphanelerini kullandık. Bunun yanı sıra kullandığımız diğer kütüphaneler şunlardır:

- **Numpy **: Sayısal hesaplamalar ve veri işleme için kullandık.
- **OpenCV(CV2)** : X-ray görüntülerinin okunması, boyutlandırılması ve işlenmesi için kullandık.
- **Scikit-learn** : Veri ayrımı ve performans metrikleri hesaplamak için kullandık.
- **Pandas **: Veri manipülasyonu ve analizleri için kulandık.
- ** Matplotlib ve Seaborn** : Görselleştirme ve grafkler için kullandık.
- **Glob** : Dosya ve klasör işlemlerimiz için kullandık.
- ** Tensorflow ** : Derin öğrenme modelleri oluşturmak, eğitmek ve değerlendirmek için kullandık.
- ** Keras ** : Tensorflow üzerinde modeller oluşturmak için kullandık.
- ** KerasTuner ** : Model hiperparametrelerini optimize etmek ve en iyi modeli seçmek için kullandık.
---

## Proje Dosya Yapısı

- Proje kodları tek bir .ipynb dosyası içerisinde barındırılmaktadır.

---

## Kurulum
> Projeyi Google Colab ortamında geliştirdik. Local bilgisayar ortamında projeyi çalıştırmak için proje içerisinde import edilen gereksinimleri oluşturduğunuz Python sanal ortamında (venv) kurmanız, ve proje üzerinde çalışılan veri setini indirerek cihazda kaydettiğiniz lokasyona kod içerisinde erişmeniz gerekmektedir.

> Proje içerisinde kullanılan Transfer Leraning algoritmaları yüksek işlem gücü  gerektirebilir bu nedenle Google Colab kullanımı tavsiye edilmektedir.

## Veri Setine ve Proje Kodlarına Erişme

- Projede kullanılan veri setini Google Drive saklama alanınızın ana klasörüne kısayol olarak kaydedin. [Veri Seti](https://drive.google.com/drive/folders/1N3n4GOmIJzg83cq5je_XlEbdziBYHFLs?usp=share_link "Veri Seti")

- GitHub deposunu klonlamak için, [Colab](https://colab.research.google.com "Colab")'da bir yeni not defteri oluşturun ve aşağıdaki komutu yazın:

```shell
!git clone https://github.com/umutakpinar/derin-ogrenme-final.git
```

- Projenin daha hızlı şekilde çalışması için [Colab](https://colab.research.google.com "Colab")'te ekranın üst kenarında bulunan sekmelerden *Çalışma Zamanı > Çalışma Zamanı Türünü Değiştir > T4 GPU > Kaydet* seçeneklerini uygulayın.

---

## Kullanım

Sırasıyla tüm kod bloklarını, her bir kod bloğunun solundaki *Play* butonuna tıklayarak çalıştırın. 

---

## Katkılar

- https://github.com/Frightera/TensorFlow-2.X-Ogretici-Notebooklar-Turkce/blob/main/11%20-%20Video%20-%20TF%20ile%20G%C3%B6r%C3%BCnt%C3%BC%20S%C4%B1n%C4%B1fland%C4%B1rma.ipynb

- https://medium.com/mlearning-ai/transfer-learning-using-densenet201-525749762ca9

- https://www.youtube.com/watch?v=WW-BUMADPtQ

---

## İletişim

Esma KÖROĞLU: 1200505033@ogr.klu.edu.tr

Sümeyra AYDIN:1200505041@ogr.klu.edu.tr

Buğra GÖRMÜŞ: 1200505068@ogr.klu.edu.tr

Recep Umut AKPINAR: 1190505805@ogr.klu.edu.tr
