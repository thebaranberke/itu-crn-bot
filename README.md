# 🎓 İTÜ CRN Bot

İstanbul Teknik Üniversitesi ders kayıt sisteminde CRN kodlarını otomatik dolduran ve formu gönderen bir **Bookmarklet** araçı.

---

## ✨ Özellikler

- CRN kodlarını otomatik doldur
- Formu tek tıkla gönder
- Onay popup'ını otomatik kabul et
- Kullanıcı dostu arayüzle CRN düzenleme
- CRN ekle / sil özelliği
- GitHub Pages ile canlı yayın

---

## 🚀 Nasıl Kullanılır

### Yöntem 1 — Bookmarklet

1. Siteyi açaç → **Copy** butonuna bas
2. Yer imleri çubuğunu göster → `Ctrl + Shift + B`
3. Çubuğa sağ tık → **Yeni yer imi ekle**
4. URL alanına kodu yapıştır (`javascript:` dahil)
5. İTÜ ders kayıt sayfasında yer imi butonuna **tek tık**

### Yöntem 2 — Konsol

1. İTÜ ders kayıt sayfasına git
2. Geliştirici araçları aç → `F12`
3. **Console** sekmesine geç
4. Kodu yapıştır (`javascript:` olmadan)
5. **Enter** tusa bas

---

## 📁 Dosya Yapısı

```
itu-crn-bot/
├── index.html      # Ana sayfa ve arayüz
└── README.md       # Bu dosya
```

---

## 🛠️ Kurulum

```bash
git clone https://github.com/[kullanıcı-adın]/itu-crn-bot.git
cd itu-crn-bot
```

Dosyaları indirdikten sonra `index.html` dosyasını tarayıcında açabilirsin. Herhangi bir bağımlılık veya kurulum gerekli değildir.

---

## 🌐 Yayına Alma (GitHub Pages)

1. GitHub'da repo'na git → **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: **main**, Folder: **/ (root)**
4. **Save** bas

Birkaç saniye sonra siteni şu adreste görebilirsin:

```
https://[kullanıcı-adın].github.io/itu-crn-bot/
```

---

## ⚠️ Uyarı

Bu araç yalnızca kişisel kullanım amaçlıdır. İTÜ'nün ders kayıt politikalarına lütfen uygun hareket edin.

---

## 👤 Geliştirici

**Baran Berke**
