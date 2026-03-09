# 🔧 PartsLand — AI Otomotiv Parça Tanımlama

**PartsLand**, fotoğraf çekerek veya şase (VIN) numarası girerek araç parçalarını yapay zeka ile tanımlayan, OEM kodlarını bulan ve PartSouq'a yönlendiren ücretsiz bir web uygulamasıdır.

---

## ✨ Özellikler

- 📷 **Fotoğrafla Tanıma** — Parça fotoğrafını yükle, Gemini Vision ile anında tanımla
- 🔍 **VIN ile OEM Arama** — 17 haneli şase numarasıyla araca özel parça listesi
- 🔗 **PartSouq Entegrasyonu** — Tek tıkla parça kataloğuna yönlendir
- 📋 **Tanımlama Geçmişi** — Önceki aramalar otomatik kaydedilir
- 💰 **Tamamen Ücretsiz** — Gemini 1.5 Flash: günlük 1500 istek, 0₺

---

## 🚀 Canlı Demo

👉 [partsland.vercel.app](https://partsland.vercel.app)

---

## 🛠️ Kurulum

### 1. Repoyu klonla
```bash
git clone https://github.com/KULLANICI_ADIN/partsland.git
cd partsland
```

### 2. Tarayıcıda aç
```bash
# Direkt olarak aç (Node.js gerekmez)
open index.html
```

### 3. Gemini API Anahtarı Al
1. [aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey) adresine git
2. Google hesabınla giriş yap
3. **"Create API Key"** butonuna tıkla
4. Oluşan anahtarı kopyala
5. Uygulamada API alanına yapıştır → **KAYDET**

---

## 📦 Vercel'e Deploy

### Yöntem 1 — Vercel Dashboard (Önerilen)
1. [vercel.com](https://vercel.com) → **"Add New Project"**
2. GitHub reposunu seç: `partsland`
3. Framework: **"Other"** seç
4. **Deploy** — bitti!

### Yöntem 2 — Vercel CLI
```bash
npm i -g vercel
vercel --prod
```

---

## 📁 Proje Yapısı

```
partsland/
├── index.html        # Tek sayfa uygulama (tüm kod burada)
├── vercel.json       # Vercel yapılandırması
└── README.md         # Bu dosya
```

---

## 🔑 API Güvenliği

API anahtarı yalnızca **tarayıcınızda** (localStorage) saklanır. Sunucuya gönderilmez.  
Üretim ortamı için anahtarı backend proxy üzerinden kullanmanız önerilir.

---

## 🗺️ Yol Haritası

- [ ] PWA desteği (telefona yükleme)
- [ ] Türkçe VIN veritabanı genişletme
- [ ] Parça fiyat karşılaştırma
- [ ] Çoklu fotoğraf analizi
- [ ] QR kod ile parça paylaşımı

---

## 📄 Lisans

MIT License — dilediğiniz gibi kullanabilirsiniz.
