# 📱 İş Takip Uygulaması (Task Tracker App)

Mobil telefonda kullanabileceğiniz modern ve kullanıcı dostu bir iş takip uygulaması.

## ✨ Özellikler

### 📋 Görev Yönetimi
- ✅ Yeni görev oluşturma
- ✏️ Görev düzenleme
- 🗑️ Görev silme
- 📊 Görev durumu takibi (Yapılacak → Yapılıyor → Tamamlandı)

### 🎯 Öncelik Seviyeleri
- 🔴 Yüksek Öncelik
- 🟠 Orta Öncelik
- 🟢 Düşük Öncelik

### 📅 İstatistikler
- Toplam görev sayısı
- Tamamlanan görevler
- Devam eden görevler
- Yapılacak görevler
- Tamamlama oranı (%)

### 👤 Profil Yönetimi
- Profil bilgilerini düzenleme
- İstatistik görüntüleme
- Versiyon bilgisi
- Verileri temizleme seçeneği

### 💾 Veri Depolama
- Yerel SQLite veritabanı (internet gerektirmez)
- AsyncStorage ile profil verisi

## 🚀 Kurulum

### Ön Gereksinimler
- Node.js v16 veya üstü
- npm veya yarn
- Android cihaz/emülatör veya iPhone/iOS simulator

### Adım 1: Projeyi Klonlayın
```bash
git clone https://github.com/Fatih1644/task-tracker-app.git
cd task-tracker-app
```

### Adım 2: Bağımlılıkları Yükleyin
```bash
npm install
# veya
yarn install
```

### Adım 3: Uygulamayı Çalıştırın

#### Android cihazda çalıştırmak için:
```bash
npm run android
# veya
expo start --android
```

#### iPhone'da çalıştırmak için:
```bash
npm run ios
# veya
expo start --ios
```

#### Web tarayıcıda çalıştırmak için:
```bash
npm run web
# veya
expo start --web
```

## 📦 APK/IPA İndirme

### Android APK İndirme (Expo üzerinden):
1. `npm start` komutu çalıştırın
2. Telefonda Expo uygulamasını açın
3. QR kodu tarayın
4. "Build APK" seçeneğini seçin
5. Uygulamanız oluşturulacak ve indirilebilir hale gelecek

Veya doğrudan Expo Dashboard'dan: https://expo.dev/projects

## 📱 Ekran Görüntüleri

### 1️⃣ Görevler Sayfası
- Tüm görevler listelenir
- Kategori filtresi (Tümü, Yapılacak, Yapılıyor, Tamamlandı)
- Durumu değiştir ve sil seçenekleri

### 2️⃣ Yeni Görev Ekleme
- Başlık, açıklama giriş
- Öncelik seçimi
- Bitiş tarihi belirtme

### 3️⃣ Profil & İstatistikler
- Kişisel bilgiler
- Görev istatistikleri
- Tamamlama yüzdesi

## 🛠️ Teknoloji Stack

```
Frontend:
- React Native
- Expo
- React Navigation (Tab Navigator)
- AsyncStorage

Backend/Database:
- SQLite (Yerel Depolama)
- No server required (Offline first)
```

## 📁 Proje Yapısı

```
task-tracker-app/
├── App.js                          # Ana uygulama dosyası
├── app.json                        # Expo konfigürasyonu
├── package.json                    # Bağımlılıklar
├── src/
│   └── screens/
│       ├── TasksScreen.js         # Görevler listesi ekranı
│       ├── AddTaskScreen.js       # Yeni görev ekleme ekranı
│       └── ProfileScreen.js       # Profil ekranı
└── README.md                       # Dokümantasyon
```

## 💡 Kullanım Rehberi

### Görev Ekleme
1. "Ekle" sekmesine tıklayın
2. Görev başlığını girin (zorunlu)
3. Açıklama ekleyin (opsiyonel)
4. Öncelik seçin
5. Bitiş tarihi girin (opsiyonel)
6. "Görev Ekle" butonuna tıklayın

### Görev Durumunu Değiştirme
1. "Görevler" sekmesinde görevinizi bulun
2. "Durum Değiştir" butonuna tıklayın
3. Durum otomatik olarak ilerleme kaydedecek

### Görev Silme
1. "Görevler" sekmesinde görevinizi bulun
2. "Sil" butonuna tıklayın
3. Onayı verdikten sonra görev silinecek

### Profil Bilgilerini Düzenleme
1. "Profil" sekmesine gidin
2. "Düzenle" butonuna tıklayın
3. Bilgilerinizi güncelleyin
4. "Kaydet" butonuna tıklayın

## 🐛 Sorun Giderme

### "Modül bulunamadı" hatası
```bash
rm -rf node_modules
npm install
```

### Veritabanı hatası
- Uygulamayı tamamen kapatıp açmayı deneyin
- Veya "Profil" > "Tüm Verileri Sil" seçeneğini kullanın

### Expo QR kodu çalışmıyor
- Cihazınızda "Expo Go" uygulaması yüklü olduğundan emin olun
- Bilgisayarınız ve cihazınız aynı WiFi ağında olduğundan emin olun

## 📝 Lisans

Bu proje açık kaynak kodludur.

## 👨‍💻 Geliştirici

- **Fatih1644** - [GitHub Profili](https://github.com/Fatih1644)

## 🤝 Katkıda Bulunun

Pull request'ler açıktır! Büyük değişiklikler için lütfen önce bir issue açınız.

## 📞 Destek

Sorunuz veya öneriniz varsa lütfen bir issue açınız.

---

**Uygulamayı beğendiyseniz ⭐ yıldız vermeyi unutmayın!**
