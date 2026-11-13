# 002 / Recycle

**Gözden çıkarma.**

Scribble’ın geri dönüşüm farkındalığı üzerine kurgulanan ikinci dünyası. İsim ve logo ortak; bu dünyanın renk, tipografi ve sayfa sistemi bağımsız.

[Deneyimi keşfet ↗](https://scribble-worlds.github.io/scribble-recycle/) · [Kaynaklar ve referanslar](https://scribble-worlds.github.io/scribble-recycle/references.html)

## Deneyim

- Lafour referanslı tam ekran fotoğraf, ince işaretli menü ve kullanıcı kontrollü görsel seçimi.
- Lament referanslı büyük numaralı başlıklar, kaydırmayla genişleyen ve açılıp kapanan medya bölümleri.
- Gerçek 4000–4800 piksel fotoğraflar: ekran boyutuna göre 960 / 1920 / 3840 piksel sunum ve tam ekran görüntüleyici.
- Kobalt mavi, beyaz ve siyah; Barlow Condensed, Space Grotesk ve IBM Plex Mono.
- OECD ve UNEP kaynaklarıyla tarih ve kapsamı belirtilmiş veriler; 100 sembolle %9 geri dönüşüm grafiği.
- Türkçe / İngilizce, mobil menü, klavye desteği ve azaltılmış hareket tercihi.
- Jarcos referanslı siyah bilgi satırlarından beyaz büyük kelime işaretine geçen footer.

## Çalıştırma

Derleme ve bağımlılık kurulumu gerekmez:

```sh
python3 -m http.server 8000
```

`index.html` ana sayfa, `references.html` kaynak arşivi, `recycle.css` görsel sistem, `recycle.js` etkileşimlerdir. `build_site.py` iki HTML dosyasını üretir. GitHub Pages `main` dalının kökünden yayınlanır.

Fotoğraflar Unsplash kaynaklarından responsive olarak, fontlar Google Fonts üzerinden sunulur. Önceki sürümün kullanılmayan dosyaları mevcut olabilir; güncel HTML yeni `recycle.css` ve `recycle.js` dosyalarını kullanır.

Fotoğrafçılar: Alex Varela (4000 × 2250), Marcus Lange (4800 × 2702), Naja Bertolt Jensen (4032 × 3024). Fotoğraflar Unsplash lisansı kapsamında kullanılır; ortaklık veya destek iddia edilmez. Özgün bağlantılar, verilerin kapsamları ve tasarım referansları kaynak sayfasındadır.

Bir **Scribble** tasarım ve geliştirme projesi / **muham²ed**
