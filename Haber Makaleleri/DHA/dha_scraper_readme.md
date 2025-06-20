# DHA Web Scraper

Bu proje, [Demirören Haber Ajansı (DHA)](https://www.dha.com.tr) web sitesinden makaleleri otomatik olarak çekmek için geliştirilmiştir. Projede temel amaç, doğru sınıflandırılmış türkçe veri toplamaktır.

## Çekilen Veriler
Proje tarafından sağlanan veriler şunlardır:
- **Makale ID** (URL'deki sayı, makaleyi benzersiz şekilde tanımlar)
- **Başlık** (Makaleyi tanımlayan temel ifade)
- **Yazar** (Makalenin yazarı veya kaynak bilgisi)
- **Yayınlanma Tarihi** (İlk yayın tarihi)
- **Makale Bölümü** (spor, gündem, ekonomi vb.)
- **Makale Özeti** (İçeriğin kısa özeti veya giriş bölümü)
- **Makale İçeriği** (Tam metin, düzenlenmiş ve okunabilir formda)

## Veri Kalitesi
Projede veri kalitesi ve doğruluğu en büyük önceliğimizdir. Veriler, yapılandırılmış ve kolay erişilebilir şekilde saklanır ve hataların minimum seviyede tutulmasına özen gösterilir.

## Kullanım
Çekilen veriler HuggingFace'de Parquet tipi dosyalarda saklanır ve analiz, raporlama veya içerik yönetim sistemleri gibi çeşitli uygulamalarda doğrudan kullanılabilir.

## Lisans
Bu proje MIT lisansı altında yayınlanmıştır. Ayrıntılar için [LICENSE](LICENSE) dosyasına bakınız.

