# GitHub Pages'e Yükleme Talimatları

Web sitenizi GitHub Pages'de yayınlamak için aşağıdaki adımları izleyin:

## 1. GitHub'da Yeni Repo Oluşturma

1. GitHub.com'a giriş yapın
2. Sağ üstteki **+** butonuna tıklayın ve **New repository** seçin
3. Repository adını **`iince43.github.io`** olarak girin (ÖNEMLI: Tam olarak bu ismi kullanın!)
4. Public seçeneğini işaretleyin
5. **Create repository** butonuna tıklayın

## 2. Dosyaları GitHub'a Yükleme

### Seçenek A: GitHub Web Arayüzü ile Yükleme (Kolay Yol)

1. Oluşturduğunuz repo'ya gidin
2. **uploading an existing file** linkine tıklayın
3. `iince43.github.io` klasöründeki tüm dosyaları sürükleyip bırakın:
   - index.html
   - cv.html
   - dersler.html
   - style.css
4. Sayfanın altındaki **Commit changes** butonuna tıklayın

### Seçenek B: Git Komutları ile Yükleme

Eğer Git yüklüyse, terminal/command prompt'ta şu komutları çalıştırın:

```bash
cd /mnt/d/sporcub/iince43.github.io
git init
git add .
git commit -m "İlk yükleme"
git branch -M main
git remote add origin https://github.com/iince43/iince43.github.io.git
git push -u origin main
```

## 3. GitHub Pages'i Aktifleştirme

1. Repo'nuzda **Settings** sekmesine gidin
2. Sol menüde **Pages** bölümünü bulun
3. **Source** kısmında:
   - Deploy from a branch seçin
   - Branch: **main** seçin
   - Folder: **/ (root)** seçin
4. **Save** butonuna tıklayın

## 4. Sitenize Erişim

- Birkaç dakika bekleyin (genelde 5-10 dakika)
- Siteniz şu adreste yayında olacak: **https://iince43.github.io**

## Önemli Notlar

- İlk yayınlanma 10 dakika kadar sürebilir
- Sonraki güncellemeler 1-2 dakika içinde yansır
- Eğer site görünmüyorsa, tarayıcı önbelleğini temizleyin (Ctrl+F5)

## Site İçeriğini Özelleştirme

Sitenizdeki bilgileri güncellemek için:

1. **index.html** - Ana sayfa bilgilerinizi düzenleyin:
   - Üniversite adı
   - Bölüm
   - Araştırma alanları
   - Sosyal medya linkleri

2. **cv.html** - CV bilgilerinizi ekleyin:
   - Eğitim bilgileri
   - Deneyim
   - Yayınlar
   - Projeler

3. **dersler.html** - Ders notlarınızı yükleyin:
   - Ders kodları ve isimleri
   - Ders materyalleri

## Sorun Giderme

- **404 Hatası**: Repo adının tam olarak `iince43.github.io` olduğundan emin olun
- **Site güncellenmiyor**: Tarayıcı önbelleğini temizleyin
- **Dosyalar görünmüyor**: Tüm dosyaların main branch'te olduğundan emin olun

## Destek

Herhangi bir sorun yaşarsanız:
- GitHub Pages dokümantasyonu: https://docs.github.com/en/pages
- GitHub Community: https://github.community/