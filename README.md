# OpenClaw AI Assistant - JARVIS Tarzı Yapay Zeka Asistanı

## Proje Hakkında

Bu proje, Marvel filmlerindeki J.A.R.V.I.S. yapay zeka asistanından ilham alınarak geliştirilen çoklu-mimariye sahip bir AI asistan sistemidir. Web tabanlı arayüzü, gerçek sistem bilgilerini çekebilen Python backend'i ve konuşma tabanlı arayüzü içerir.

## 🚀 Özellikler

- **3D Holografik Arayüz**: Three.js/React Three Fiber ile oluşturulmuş parçacık bazlı yüz efekti
- **Gerçek Zamanlı Sistem Monitörü**: Python/Flask backend ile gerçek sistem bilgileri (RAM, CPU, Disk, Ağ)
- **Sesli İletişim**: Web Speech API ile ses tanıma (STT) ve sentez (TTS)
- **Mikrofon Görselleştirme**: Gerçek zamanlı ses seviyesi göstergesi
- **Monorepo Yapısı**: Turborepo ile yönetilen paket yapısı

## 📁 Proje Yapısı

```
Asistan/
├── packages/
│   ├── api/           # Python Flask sistem monitör sunucusu
│   ├── web/          # React + Three.js web uygulaması
│   ├── voice/        # Ses işleme paketi
│   ├── core/        # Çekirdek fonksiyonlar
│   ├── agents/      # Agent yönetimi
│   ├── platforms/   # Platform entegrasyonları
│   └── shared/     # Paylaşılan tipler ve yardımcılar
├── package.json
└── turbo.json
```

## 🛠️ Kurulum

### Gereksinimler

- Node.js >= 20.0.0
- npm >= 10.0.0
- Python >= 3.8
- psutil (Python paketi)

### Adımlar

```bash
# Repoyu klonla
git clone https://github.com/immistercool/openclaw-bot.git
cd openclaw-bot

# Bağımlılıkları yükle
npm install

# Python bağımlılıklarını yükle
pip install flask flask-cors psutil

# Geliştirme modunda çalıştır
npm run dev
```

## 🖥️ Servisler

| Servis | Port | Açıklama |
|--------|------|----------|
| Web UI | 5173-5176 | React web uygulaması |
| API | 5000 | Python Flask sistem monitörü |

## 📋 Yapılan İşler

### ✅ Tamamlanan

- [x] Monorepo yapılandırması (Turborepo)
- [x] Web paketi oluşturuldu (React + Three.js)
- [x] Shared paketi oluşturuldu
- [x] Core paketi oluşturuldu
- [x] Voice paketi oluşturuldu
- [x] Agents paketi oluşturuldu
- [x] Platforms paketi oluşturuldu
- [x] Python Flask sistem monitör backend'i
- [x] Three.js parçacık sistemi ile holografik yüz
- [x] Anatomik yüz yapısı (13 bölge, 2000+ parçacık)
- [x] Konuşma animasyonu (ağız bölgesi hareketi)
- [x] Boşta kasırga efekt
- [x] Web Speech API entegrasyonu (STT/TTS)
- [x] Mikrofon seviye göstergesi
- [x] Sistem bilgileri paneli (RAM, CPU, Disk, Ağ)

### ⏳ Yapılacaklar

- [ ] Pleksus tarzı çizgi bağlantıları eklemek
- [ ] Daha hacimli yüz yapısı
- [ ] D-ID veya HeyGen API entegrasyonu (dudak senkronizasyonu)
- [ ] Docker containerization
- [ ] Mobil uygulama geliştirme

## 🔧 Teknolojiler

### Frontend
- React 18
- Three.js / React Three Fiber
- TailwindCSS
- Framer Motion

### Backend
- Python 3.8+
- Flask
- psutil

### Diğer
- Turborepo
- TypeScript

## 📝 API Endpoints

### Python Backend (http://localhost:5000)

```
GET /                    - Ana sayfa
GET /api/health         - Sağlık kontrolü
GET /api/system-info   - Sistem bilgileri (RAM, CPU, Disk, Ağ)
```

## 🎯 Kullanım

1. Web uygulamasını aç (http://localhost:5173)
2. Mikrofon butonuna basarak sesli komut ver
3. Asistan yanıtlar ve sesli olarak söyler
4. Sol panelde sistem bilgilerini görüntüle

## 📄 Lisans

MIT License

## 👤 Geliştirici

- GitHub: [immistercool](https://github.com/immistercool)"# openclaw_projects" 
#
