# Koton Mağaza Konum Haritası

Bu proje, AVM içerisindeki Koton mağazalarının konumlarını Mapbox kullanarak gösteren bir wayfinding (yön bulma) uygulamasıdır.

## Özellikler

- Koton mağazalarının konumlarını haritada gösterir
- Her mağaza için tıklanabilir işaretçiler
- Mağaza bilgilerini popup olarak gösterir
- Tam ekran modu
- Konum takibi
- Yakınlaştırma ve yön kontrolleri

## Kurulum ve Çalıştırma

1. Projeyi bilgisayarınıza indirin
2. `index.html` dosyasını bir web tarayıcısında açın
3. Alternatif olarak, basit bir HTTP sunucusu kullanabilirsiniz:

```bash
# Python 3 ile basit bir HTTP sunucusu başlatma
python -m http.server

# Tarayıcınızda şu adresi açın
# http://localhost:8000
```

## Kullanılan Teknolojiler

- HTML5
- CSS3
- JavaScript
- [Mapbox GL JS](https://docs.mapbox.com/mapbox-gl-js/api/)

## Harita Kontrollerini Kullanma

- **Yakınlaştırma/Uzaklaştırma**: Sağ üst köşedeki + ve - butonları veya fare tekerleği
- **Haritayı Döndürme**: Sağ tıklayıp sürükleme
- **Haritayı Kaydırma**: Sol tıklayıp sürükleme
- **Tam Ekran**: Sağ üstteki tam ekran butonu
- **Konum Takibi**: Sağ üstteki konum butonu

## GeoJSON Verileri

Harita, aşağıdaki koordinatlara sahip Koton mağazalarını göstermektedir:

- Koton 1: 30.510751101037727, 39.78351713722205
- Koton 2: 30.511335038076254, 39.78306502728435
- Koton 3: 30.510575341707437, 39.78328281398464
- Koton 4: 30.511281723664723, 39.78298869530573
- Koton 5: 30.511158772290514, 39.78295194086061
- Koton 6: 30.51088965609395, 39.7831048390492
- Koton 7: 30.51108450141291, 39.783283383427886

Bu koordinatlar Eskişehir'deki bir AVM'ye ait olabilir ve wayfinding uygulaması için kullanılmaktadır. 