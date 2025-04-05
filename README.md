# ESpark AVM 3D Kat Planı

Bu proje, Mapbox GL JS kullanılarak geliştirilmiş interaktif bir alışveriş merkezi kat planı görselleştirmesidir. Kullanıcılar, AVM içerisindeki mağazaları harita üzerinde görebilir, bilgi alabilir ve yön tarifi özelliklerinden faydalanabilirler.

## Özellikler

* Mağaza konumlarını görüntüleme
* Mağaza sınırlarını ve etiketlerini gösterme
* Giriş/çıkış noktalarını işaretleme
* Yürüyen merdiven ve bilgi ekranı konumlarını gösterme
* İnteraktif harita kontrolleri (yakınlaştırma, uzaklaştırma, kaydırma)
* Renk kodlu mağaza ve tesis gösterimi
* Açıklayıcı lejant

## Mağazalar ve Tesisler

Projede aşağıdaki mağazalar ve tesisler modellenmiştir:

* Koton
* Sevil
* Greyder
* Adidas
* Nike
* Sevil Kozmetik
* Saat
* Giriş & Çıkış Noktaları
* Yürüyen Merdiven
* Kiosk Board (Bilgi Ekranı)

## Kurulum

1. Projeyi bilgisayarınıza indirin
2. İndirilen klasörde yerel bir HTTP sunucusu başlatın:

```bash
python -m http.server 8000
```

3. Tarayıcınızda `http://localhost:8000` adresine gidin

## Kullanım

* Mağazaları görmek için haritayı yakınlaştırıp uzaklaştırabilirsiniz
* Harita üzerindeki renk kodlu alanlar farklı mağazaları gösterir
* Sağ alttaki lejant, hangi rengin hangi mağazaya ait olduğunu belirtir
* Giriş/çıkış noktaları, yürüyen merdiven ve bilgi ekranı özel sembollerle işaretlenmiştir

## Teknolojiler

* HTML, CSS, JavaScript
* Mapbox GL JS

## Geliştirici Bilgileri

Bu proje, BeeAI World tarafından geliştirilmiştir. Daha fazla bilgi için: https://github.com/beeaiworld 