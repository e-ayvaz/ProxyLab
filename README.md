# ProxyLab

> **Mobile developer companion** — iPhone, Android ve simülatörden gelen HTTPS trafiğini **görün, değiştirin ve tekrar oynatın.** Cihazınız ile internet arasında çalışan bir ortadaki-adam (MITM) proxy.

---

## ▶ Canlı İnteraktif Önizleme

Uygulamayı kurmadan, doğrudan tarayıcıda deneyin — gerçek arayüzün çalışan birebir taklidi. Trafiği başlatın, satırlara tıklayın, detayları gezin; rehberli tur ve cihaz kurulum sihirbazları dahil.

### 👉 **[İnteraktif Önizlemeyi Aç →](https://e-ayvaz.github.io/ProxyLab/guide/proxylab-preview.html)**

### 📘 **[Kurulum & Cihaz Bağlama Rehberi (önizleme gömülü) →](https://e-ayvaz.github.io/ProxyLab/guide/proxylab-kurulum-rehberi.html)**

> İçinde üç mod var: **🎯 Rehberli Tur** (adım adım hotspot anlatımı), **▶ Otomatik Tur** (kendiliğinden oynayan demo) ve **Serbest gez**. Soldaki listeden istediğiniz ekranın ya da cihaz kurulumunun turunu başlatabilirsiniz.

---

## Önizlemede neler var?

**Arayüz turları**
- **See** — canlı trafik listesi, satır detayları (request/response · body/headers/raw), sağ tık hızlı aksiyonları ve **Diff (Set A / Set B)** karşılaştırma ekranı
- **Kurallar (Map Local)** — eşleşen isteğe sunucuya gitmeden kendi yanıtınızı döndürün
- **Breakpoint'ler** — istek/yanıtı duraklatıp gönderirken düzenleyin
- **SSL Proxying List** — Kapsam (Focus), SSL pinning bypass
- **Remote** — yerleşik istek oluşturucu, kayıtlı istek **gruplama** ve **cURL içe aktarma**
- **Replay** — mock snapshot kaydet/etkinleştir + **2 snapshot karşılaştırma** (örn. Android ↔ iOS login akışının request/response farkları) + içe/dışa aktar + PDF
- **Format** — JSON inceleyici/formatlayıcı
- **Settings** — port, CA, sistem proxy koruması, güncelleme

**Cihaz kurulumu (adım adım sihirbazlar + telefon ekranı taklitleri)**
- **iOS Simulator** — tek tıkla CA
- **iPhone (Wi-Fi)** — 5 adım: Mac'e CA → QR/indir → yükle & güven → PAC proxy → manuel fallback
- **Android (Emülatör / USB · adb)** — otomatik CA + proxy
- **Android (Wi-Fi)** — 5 adım (Chrome + Güvenlik ayarları + PAC)

---

## İndir

En son sürüm için: **[Releases →](https://github.com/e-ayvaz/ProxyLab/releases)**

---

<sub>Önizleme tamamen tarayıcıda çalışan bir taklittir (backend yoktur, trafik simüledir). Ekran görüntülerindeki IP/adresler örnektir — gerçek uygulamada kendi Mac'inizin LAN IP'si görünür.</sub>
