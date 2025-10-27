# 🏠 360° Sanal Oda Projesi

## 📝 Proje Hakkında
Bu proje, Three.js kütüphanesi kullanılarak oluşturulmuş interaktif bir 3D sanal oda uygulamasıdır. 
Sanal Gerçeklik dersi kapsamında geliştirilmiştir.

## 🌐 Canlı Demo
**[Projeyi Buradan Görüntüle](https://mervetlckn.github.io/sanal-oda-360-/)**

## ✨ Özellikler
- 🔄 360 derece görüntüleme (fare ile döndürme)
- 🔍 Zoom yapabilme (scroll ile)
- ☀️ Gün/Gece modu geçişi
- 🏡 Mobilyalı gerçekçi oda tasarımı
- 📱 Mobil uyumlu (dokunmatik kontrol)
- 🎨 Gerçekçi 3D nesneler ve gölgeler

## 🛠️ Kullanılan Teknolojiler
- **HTML5** - Yapı
- **JavaScript** - Etkileşim ve mantık
- **Three.js (r128)** - 3D grafik kütüphanesi
- **WebGL** - 3D render teknolojisi

## 🎮 Kontroller
- **🖱️ Fare**: Tıklayıp sürükleyerek 360° dönebilirsiniz
- **🔍 Scroll**: Zoom yapabilirsiniz
- **📱 Mobil**: Dokunup sürükleyerek gezinebilirsiniz
- **💡 Işıklar Butonu**: Gün/Gece modunu değiştirir
- **📷 Görünüm Butonu**: Farklı kamera açıları (Normal, Kuş Bakışı, Geniş Açı)
- **🔄 Sıfırla Butonu**: Kamerayı başlangıç pozisyonuna getirir

## 🏗️ Odadaki Nesneler
- 📚 Renkli kitaplarla dolu kitaplık
- 💻 Laptop ve çalışma masası
- 🪑 Sandalye
- 🪴 Saksı bitkisi
- 🖼️ Duvar tablosu
- 💡 Tavan lambası (ışık kaynağı)
- 🚪 Ahşap kapı
- 🪟 Pencere
- 🟥 Zemin halısı

## 🚀 Nasıl Çalıştırılır

### Online (Önerilen)
Yukarıdaki "Canlı Demo" linkine tıklayın.

### Lokal
1. `index.html` dosyasını indirin
2. Herhangi bir modern tarayıcıda açın (Chrome, Firefox, Edge, Safari)
3. İnternet bağlantısı gereklidir (Three.js CDN için)

## 📂 Proje Yapısı
```
sanal-oda-360/
├── index.html          # Ana HTML dosyası (tüm kod içinde)
└── README.md          # Bu dosya
```

## 💡 Teknik Detaylar

### 3D Modelleme
- **Three.js Scene**: Tüm 3D nesnelerin bulunduğu sahne
- **PerspectiveCamera**: 75° görüş açılı kamera
- **WebGLRenderer**: Donanım hızlandırmalı render
- **Shadow Mapping**: Gerçekçi gölgeler için

### Işıklandırma
- **AmbientLight**: Genel ortam ışığı
- **DirectionalLight**: Güneş ışığı (gölge oluşturur)
- **PointLight**: Tavan lambası

### Etkileşim
- Mouse ve touch event'leri ile kamera kontrolü
- Dinamik gün/gece döngüsü
- Responsive tasarım (tüm ekran boyutlarına uyumlu)

## 📱 Tarayıcı Desteği
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Mobil tarayıcılar


## 📄 Lisans
Bu proje eğitim amaçlıdır.

