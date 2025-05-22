# Asistan Uygulaması

Material Design bileşenleri ile oluşturulmuş, görev ve notları yönetmek için kusursuz bir kullanıcı deneyimi sunan modern bir Android uygulaması.

## Özellikler

- **Kimlik Doğrulama**
  - E-posta ve şifre ile kullanıcı kaydı
  - Güvenli giriş sistemi
  - Şifre onaylama
  - Form doğrulama

- **Kullanıcı Arayüzü**
  - Material Design 3 bileşenleri
  - Modern ve temiz arayüz
  - Duyarlı düzenler
  - Akıcı animasyonlar
  - Karanlık/Aydınlık tema desteği

- **Ekranlar**
  - Açılış Ekranı
  - Giriş Ekranı
  - Kayıt Ekranı
  - Ana Ekran
  - Araçlar Ekranı
  - Ayarlar Ekranı
  - Profil Ekranı
  - Notlar Ekranı

## Proje Yapısı

```
app/
├── src/
│   ├── main/
│   │   ├── java/com/example/assistantapp/
│   │   │   ├── MainActivity.java
│   │   │   ├── SplashScreen.java
│   │   │   ├── LoginScreen.java
│   │   │   └── RegisterScreen.java
│   │   ├── res/
│   │   │   ├── layout/
│   │   │   │   ├── activity_main.xml
│   │   │   │   ├── activity_splash.xml
│   │   │   │   ├── activity_login.xml
│   │   │   │   └── activity_register.xml
│   │   │   ├── values/
│   │   │   │   ├── colors.xml
│   │   │   │   └── styles.xml
│   │   └── AndroidManifest.xml
│   └── build.gradle
```

## Kurulum Talimatları

1. **Gereksinimler**
   - Android Studio Arctic Fox veya daha yeni
   - JDK 11 veya daha yeni
   - Android SDK 21 veya daha yeni

2. **Kurulum**
   ```bash
   # Depoyu klonlayın
   git clone [depo-url]
   
   # Projeyi Android Studio'da açın
   # Dosya -> Aç -> Proje dizinini seçin
   ```

3. **Derleme ve Çalıştırma**
   - Projeyi Android Studio'da açın
   - Gradle senkronizasyonunun tamamlanmasını bekleyin
   - "Çalıştır" düğmesine tıklayın veya Shift + F10 tuşlarına basın
   - Hedef cihazınızı seçin (emülatör veya fiziksel cihaz)

## Bağımlılıklar

- AndroidX Core: 1.6.1
- Material Design: 1.11.0
- ConstraintLayout: 2.1.4

## Katkıda Bulunma

1. Depoyu fork edin
2. Özellik dalınızı oluşturun (`git checkout -b feature/YeniOzellik`)
3. Değişikliklerinizi commit edin (`git commit -m 'Yeni özellik eklendi'`)
4. Dalınıza push yapın (`git push origin feature/YeniOzellik`)
5. Pull Request açın
