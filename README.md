# jewelry-tryit-on-AI
jewelry-tryit-on-AI
[readme_tryit-on-Ai.md](https://github.com/user-attachments/files/21898682/readme_tryit-on-Ai.md)
# Virtual Jewelry Try-On with AI 💎✨

*[English](#english) | [Türkçe](#turkce)*

---

## English

### 🎯 Project Overview

Virtual Jewelry Try-On is an AI-powered web application that allows users to virtually try on different types of jewelry using their camera. The application uses MediaPipe for real-time face and hand detection, Three.js for 3D rendering, and provides an immersive shopping experience with product catalogs, wishlists, and virtual try-on capabilities.

### 🚀 Features

- **Real-time AI Detection**: Face and hand tracking using MediaPipe
- **3D Jewelry Rendering**: Realistic jewelry visualization with Three.js
- **Multiple Jewelry Types**: Earrings, necklaces, rings, tiaras, and bracelets
- **Material Customization**: Gold, silver, rose gold, and platinum options
- **Product Catalog**: Browse and try on different jewelry collections
- **Photo Capture**: Save your virtual try-on photos
- **Wishlist & Cart**: Add items to wishlist and shopping cart
- **Responsive Design**: Works on desktop and mobile devices
- **Performance Monitoring**: Built-in FPS and memory usage tracking

### 🛠️ Tech Stack

#### Frontend
- **HTML5/CSS3/JavaScript**: Core web technologies
- **Three.js**: 3D graphics and rendering
- **MediaPipe**: AI-powered face and hand detection
- **WebRTC**: Camera access and video streaming

#### AI & Computer Vision
- **MediaPipe Face Mesh**: Facial landmark detection
- **MediaPipe Hands**: Hand tracking and gesture recognition
- **WebGL**: Hardware-accelerated graphics rendering

#### Storage & Data
- **LocalStorage**: Client-side data persistence
- **JSON**: Data structure for products and user preferences

### 📋 Installation & Setup

1. **Clone the repository**
```bash
git clone https://github.com/Edanurseymen/jewelry-tryit-on-AI
cd virtual-jewelry-try-on
```

2. **Start a local server**
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server

# Using PHP
php -S localhost:8000
```

3. **Open in browser**
Navigate to `http://localhost:8000` and open the HTML file.

4. **Allow camera permissions**
The application requires camera access for virtual try-on functionality.

### 🎮 How to Use

1. **Start Camera**: Click the "Start Camera" button to activate your webcam
2. **Select Jewelry**: Choose from earrings, necklaces, rings, tiaras, or bracelets
3. **Customize**: Adjust material, size, opacity, and brightness
4. **Try Products**: Browse the product catalog and try specific items
5. **Capture Photos**: Save your virtual try-on sessions
6. **Shopping Features**: Add items to wishlist or cart

### 🏗️ Project Structure

```
virtual-jewelry-try-on/
├── jewelry_tryit_day4.1.2_fixed.html  # Main application file
├── one_ring.glb                        # 3D ring model
├── README.md                           # Project documentation
└── assets/                             # Additional assets (if any)
```

### 🎨 Features in Detail

#### AI Detection System
- **Face Detection**: 468 facial landmarks for precise jewelry placement
- **Hand Tracking**: 21 hand landmarks for ring and bracelet positioning
- **Real-time Processing**: 30+ FPS performance on modern devices

#### 3D Rendering Engine
- **Realistic Materials**: Physically-based rendering for metals
- **Dynamic Lighting**: Multiple light sources for jewelry sparkle
- **Shadow Mapping**: Realistic shadows and reflections

#### E-commerce Features
- **Product Database**: Comprehensive jewelry catalog with ratings and reviews
- **Shopping Cart**: Full cart functionality with quantity management
- **Wishlist System**: Save favorite items for later
- **Order Simulation**: Demo checkout process

### 🔧 Development Notes

#### Known Issues & Solutions
- **CORS Errors**: MediaPipe assets may have CORS issues on some servers
- **Performance**: Heavy 3D rendering may impact older devices
- **Browser Compatibility**: Requires modern browsers with WebGL support

#### Future Enhancements
- [ ] AI-powered size recommendations
- [ ] Social sharing features
- [ ] Advanced material textures
- [ ] Voice commands integration
- [ ] AR mode for mobile devices

### 📊 Performance

- **Face Detection**: ~30 FPS on modern devices
- **Memory Usage**: ~200-500 MB depending on features used
- **Load Time**: ~3-5 seconds for full initialization
- **Browser Support**: Chrome, Firefox, Safari, Edge (modern versions)

### 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### 📄 License

This project is part of an AI-First Capstone program and is for educational purposes.

### 🙏 Acknowledgments

- MediaPipe team for computer vision capabilities
- Three.js community for 3D rendering
- Course instructors for guidance and requirements

---

## Türkçe

### 🎯 Proje Genel Bakış

Virtual Jewelry Try-On, kullanıcıların kameralarını kullanarak farklı mücevher türlerini sanal olarak deneyebilecekleri yapay zeka destekli bir web uygulamasıdır. Uygulama, gerçek zamanlı yüz ve el algılama için MediaPipe, 3D rendering için Three.js kullanır ve ürün katalogları, istek listeleri ve sanal deneme özellikleri ile sürükleyici bir alışveriş deneyimi sunar.

### 🚀 Özellikler

- **Gerçek Zamanlı AI Algılama**: MediaPipe ile yüz ve el takibi
- **3D Mücevher Rendering**: Three.js ile gerçekçi mücevher görselleştirme
- **Çoklu Mücevher Türleri**: Küpe, kolye, yüzük, taç ve bilezik
- **Malzeme Özelleştirme**: Altın, gümüş, rose altın ve platin seçenekleri
- **Ürün Kataloğu**: Farklı mücevher koleksiyonlarını inceleyin ve deneyin
- **Fotoğraf Çekimi**: Sanal deneme fotoğraflarınızı kaydedin
- **İstek Listesi & Sepet**: Ürünleri istek listesine ve sepete ekleyin
- **Responsive Tasarım**: Masaüstü ve mobil cihazlarda çalışır
- **Performans İzleme**: Yerleşik FPS ve bellek kullanımı takibi

### 🛠️ Teknoloji Yığını

#### Frontend
- **HTML5/CSS3/JavaScript**: Temel web teknolojileri
- **Three.js**: 3D grafik ve rendering
- **MediaPipe**: AI destekli yüz ve el algılama
- **WebRTC**: Kamera erişimi ve video akışı

#### AI & Bilgisayarla Görü
- **MediaPipe Face Mesh**: Yüz işaret noktası algılama
- **MediaPipe Hands**: El takibi ve jest tanıma
- **WebGL**: Donanım hızlandırmalı grafik rendering

#### Depolama & Veri
- **LocalStorage**: İstemci tarafı veri kalıcılığı
- **JSON**: Ürünler ve kullanıcı tercihleri için veri yapısı

### 📋 Kurulum & Ayarlama

1. **Repoyu klonlayın**
```bash
git clone https://github.com/Edanurseymen/jewelry-tryit-on-AI
cd virtual-jewelry-try-on
```

2. **Yerel sunucu başlatın**
```bash
# Python kullanarak
python -m http.server 8000

# Node.js kullanarak
npx http-server

# PHP kullanarak
php -S localhost:8000
```

3. **Tarayıcıda açın**
`http://localhost:8000` adresine gidin ve HTML dosyasını açın.

4. **Kamera izinlerini verin**
Sanal deneme işlevselliği için uygulama kamera erişimi gerektirir.

### 🎮 Nasıl Kullanılır

1. **Kamerayı Başlat**: Web kameranızı etkinleştirmek için "Start Camera" butonuna tıklayın
2. **Mücevher Seç**: Küpe, kolye, yüzük, taç veya bilezik arasından seçin
3. **Özelleştir**: Malzeme, boyut, opaklık ve parlaklığı ayarlayın
4. **Ürünleri Deneyin**: Ürün kataloğuna göz atın ve belirli ürünleri deneyin
5. **Fotoğraf Çekin**: Sanal deneme seanslarınızı kaydedin
6. **Alışveriş Özellikleri**: Ürünleri istek listesine veya sepete ekleyin

### 🏗️ Proje Yapısı

```
virtual-jewelry-try-on/
├── jewelry_tryit_day4.1.2_fixed.html  # Ana uygulama dosyası
├── one_ring.glb                        # 3D yüzük modeli
├── README.md                           # Proje dokümantasyonu
└── assets/                             # Ek varlıklar (varsa)
```

### 🎨 Detaylı Özellikler

#### AI Algılama Sistemi
- **Yüz Algılama**: Hassas mücevher yerleştirme için 468 yüz işaret noktası
- **El Takibi**: Yüzük ve bilezik konumlandırma için 21 el işaret noktası
- **Gerçek Zamanlı İşleme**: Modern cihazlarda 30+ FPS performans

#### 3D Rendering Motoru
- **Gerçekçi Malzemeler**: Metaller için fizik tabanlı rendering
- **Dinamik Aydınlatma**: Mücevher parlaması için çoklu ışık kaynakları
- **Gölge Haritalama**: Gerçekçi gölgeler ve yansımalar

#### E-ticaret Özellikleri
- **Ürün Veritabanı**: Derecelendirme ve yorumlarla kapsamlı mücevher kataloğu
- **Alışveriş Sepeti**: Miktar yönetimi ile tam sepet işlevselliği
- **İstek Listesi Sistemi**: Favori ürünleri daha sonra için kaydet
- **Sipariş Simülasyonu**: Demo ödeme süreci

### 🔧 Geliştirme Notları

#### Bilinen Sorunlar & Çözümler
- **CORS Hataları**: MediaPipe varlıkları bazı sunucularda CORS sorunları yaşayabilir
- **Performans**: Ağır 3D rendering eski cihazları etkileyebilir
- **Tarayıcı Uyumluluğu**: WebGL desteği olan modern tarayıcılar gerektirir

#### Gelecek Geliştirmeler
- [ ] AI destekli boyut önerileri
- [ ] Sosyal paylaşım özellikleri
- [ ] Gelişmiş malzeme dokuları
- [ ] Sesli komut entegrasyonu
- [ ] Mobil cihazlar için AR modu

### 📊 Performans

- **Yüz Algılama**: Modern cihazlarda ~30 FPS
- **Bellek Kullanımı**: Kullanılan özelliklere bağlı olarak ~200-500 MB
- **Yüklenme Süresi**: Tam başlatma için ~3-5 saniye
- **Tarayıcı Desteği**: Chrome, Firefox, Safari, Edge (modern sürümler)

### 🤝 Katkıda Bulunma

1. Repoyu fork edin
2. Özellik dalı oluşturun (`git checkout -b feature/muhteşem-özellik`)
3. Değişikliklerinizi commit edin (`git commit -m 'Muhteşem özellik ekle'`)
4. Dalı push edin (`git push origin feature/muhteşem-özellik`)
5. Pull Request açın

### 📄 Lisans

Bu proje AI-First Capstone programının bir parçasıdır ve eğitim amaçlıdır.

### 🙏 Teşekkürler

- Bilgisayarla görü yetenekleri için MediaPipe takımı
- 3D rendering için Three.js topluluğu
- Rehberlik ve gereksinimler için kurs eğitmenleri

---

### 📞 İletişim

Proje hakkında sorularınız için [GitHub Issues]( https://github.com/Edanurseymen/jewelry-tryit-on-AI/issues) bölümünü kullanabilirsiniz.

**Demo**: [Canlı Demo Linki](https://jewelry-tryit-on-ai.vercel.app/)
**Video**: [Demo Videosu](-)
