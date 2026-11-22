# 🌍 Hava Kalitesi ve Kirlilik Takibi (Android APK)

Modern, şık ve anlık verilerle çalışan mobil Hava Kalitesi (AQI) ve Kirlilik Takip uygulaması.

---

### ✨ Öne Çıkan Özellikler
- **Gerçek Zamanlı Hava Kalitesi İndeksi (AQI):** US AQI ve Avrupa standartlarına göre anlık hava kalitesi derecelendirmesi (İyi, Orta, Hassas, Sağlıksız, Tehlikeli).
- **Detaylı Kirletici Analizi:**
  - **PM2.5** (İnce partikül maddeler)
  - **PM10** (Toz ve kaba partiküller)
  - **NO₂** (Azot Dioksit)
  - **O₃** (Ozon)
  - **SO₂** (Kükürt Dioksit)
  - **CO** (Karbonmonoksit)
- **Hava Durumu Bilgileri:** Sıcaklık (°C), Bağıl Nem (%) ve Rüzgar Hızı (km/s).
- **24 Saatlik Değişim & Tahmin:** Chart.js destekli interaktif saatlik AQI tahmin grafiği.
- **Sağlık & Önlem Önerileri:** Dış mekan aktiviteleri, ev havalandırması, hassas gruplar (astım/alerji) ve maske kullanımı için dinamik rehber.
- **Hızlı Şehir Seçimi & Arama:** İstanbul, Ankara, İzmir, Antalya gibi büyük şehirlerin yanında küresel arama ve tek dokunuşla GPS üzerinden konum tespiti.

---

### 🚀 Otomatik APK Derleme (GitHub Actions)
Bu repo, her commit veya push işleminde GitHub Actions bulut ortamında otomatik olarak:
1. Gerekli kütüphaneleri yükler.
2. Capacitor Android projesini senkronize eder.
3. Gradle ile Android `.apk` dosyasını derler.
4. Hem **Artifacts** bölümüne hem de doğrudan indirilebilir **GitHub Releases** sayfasına yükler.
