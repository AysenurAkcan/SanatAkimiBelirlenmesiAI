# Sanat Eserlerinde Akımın Belirlenmesi

## Proje Özeti
Bu proje, sanat eserlerinin görüntülerinden Kübizm, Empresyonizm, Ekspresyonizm, Realizm ve Surrealizm akımlarını belirlemek için bir yapay zeka modeli geliştirmeyi amaçlamaktadır. Çeşitli web kaynaklarından veri çekilerek veriler toplanmış ve akımlara uygun olmayan veriler elenerek bir veri seti oluşturulmuştur. Görüntülerin doğru sınıflandırılabilmesi için veri setinde döndürme, parlaklık değiştirme, yansıma ve satürasyon gibi veri artırma teknikleri rastgele kullanılmıştır.

## Geliştirme Ortamı
- **Python**: Programlama Dili
- **Jupyter Notebook**: IDE

## Kütüphaneler

- **Web Scraping**:
  - **Selenium**: Dinamik sayfalardan veri çekme için tercih edilmiştir.
  - **Requests**: Selenium kütüphanesiyle beraber çekilen verileri indirme işlemi için kullanılmıştır.

- **Görüntü İşleme**:
  - **OpenCV**: Döndürme, parlaklık değiştirme, yansıma ve satürasyon görüntü işlemelerini gerçekleştirmek için kullanılmıştır.
  - **Pillow**: Çekilen görüntülerde akımların içerisinde bulunabilecek aynı görüntülerin pHash değerinin tespit edilip ikililiği kaldırma işlemi yapılmıştır.

## Sonuç ve Değerlendirme
İsterlere göre uygun görüntü verileri toplanıp veri seti oluşturarak modelleme kısmı için temel oluşturulmuştur.

##
- **Görüntü Verileri Linki**: https://drive.google.com/file/d/1onDgCLA4vOZKTtHiuMMhsHo3F2cRUQ6l/view?usp=sharing
- **Elenmiş Görüntü Verileri Linki**: https://drive.google.com/file/d/1V_1OeG-juVnKmuptz-4X1TKgypXjj_hn/view?usp=sharing
- **Proje Raporu Linki**: https://docs.google.com/document/d/1rGa2CpWS73XF_La88lgJ8iabOvBRP2uk/edit?usp=sharing&ouid=111960309572738603205&rtpof=true&sd=true
