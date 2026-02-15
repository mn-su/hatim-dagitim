# 📖 Ramazan ve Yıllık Hatim Takip Sistemi (v2)

Bu depo, Ramazan ayı için günlük ve yıl boyunca haftalık Kur'an-ı Kerim okuma programları oluşturmak amacıyla geliştirilmiş hafif, tek sayfa (vanilla) HTML uygulamasıdır.

## 🌙 Özellikler

- **📅 Ramazan Günlük Program**: 30 gün boyunca her gün bir cüz takibi.
- **📆 Yıllık Haftalık Program**: 46 haftalık döngüde yıl boyunca okuma programı.
- **🎯 Farklı Başlangıç Cüzleri**: Her kişi istediği cüzden başlayabilir.
- **🔎 Tek Cüz Gösterimi**: Belirli bir cüz için sadece o cüzün programını görüntüleyin.
- **🖨️ Yazdırma Özelliği**: A4 yatay 5 sütunlu yazdırma için optimize.
- **📱 Modern Arayüz**: Basit, tarayıcıda çalışır, bağımlılık yok.

## 🚀 Kullanım

### Online
- Demo: https://mn-su.github.io/hatim-takip

### Yerel
- Tarayıcınızda `index.html` dosyasını açın. Not: eski sürüm `v1.html` olarak saklanmıştır; `v2.html` içeriği şimdi `index.html` olarak kullanılmaktadır.

## 📋 Nasıl Çalışır

1. Başlangıç tarihlerini seçin (`Ramazan Başlangıcı` ve `Yıllık Başlangıç`).
2. `RAMAZAN (GÜNLÜK)` veya `YILLIK (HAFTALIK)` butonuna tıklayarak liste oluşturun.
3. (Opsiyonel) `Cüz Numarası` girerek sadece o cüzü gösterin ya da `Sadece Bu Cüzü Göster` butonunu kullanın.
4. Yeni: `🔄 İkisini Birlikte Getir` ile aynı sayfada hem Ramazan hem Yıllık programı yan yana oluşturun.
5. `🖨️ Listeyi Yazdır` ile PDF/kağıda yazdırın.

## Yeni — v2 Değişiklikleri

- **Hadis Kutusu**: Arayüzün üstünde dual amaçlı bilgi/hadis kutusu eklendi (tasarımda yeşil degrade ve alıntı görünümü).
- **İkisini Birlikte Getir**: `showBothCuz()` / `renderBothPrograms()` fonksiyonları eklendi — seçilen cüz için Ramazan (günlük) ve Yıllık (haftalık) programları tek sayfada yan yana render eder.
- **Bildirimler (Toast)**: Başarı/hata bildirimleri için kayan animasyonlu bildirim kutuları (`showNotification`) eklendi.
- **Form Geliştirmeleri**: Tarih ve cüz alanlarında validasyon ve temizleme düğmesi (`Listeyi Temizle`).
- **Yazdırma ve Sayfa Düzeni İyileştirmeleri**: A4 yatay üzerinde sütun genişlikleri, sayfa boş sütun görünürlüğü kontrolü ve `@page` ayarları düzenlendi.
- **JS Fonksiyonları (geliştirici notları)**: `renderList`, `renderBothPrograms`, `showSingleCuz`, `showBothCuz`, `showAll`, `showNotification` gibi yardımcı fonksiyonlar eklendi/iyileştirildi.

## 🛠️ Teknik Detaylar

- Tek HTML dosyası (`index.html`, v2 olarak) ve dahili CSS/JS. Not: eski sürüm `v1.html` olarak korunmuştur.
- Modern tarayıcılarda çalışır; ek bağımlılık gerektirmez.
- Yazdırma için özel CSS kuralları ve `@media print` içerir.

## 📊 Kullanım Senaryoları

- Cami veya kurumlarda farklı cüzlerden başlanarak toplu hatim planlama.
- Bireysel kullanım için Ramazan veya yıl boyunca okuma programı oluşturma.

## 🤝 Katkıda Bulunma

1. Depoyu fork edin.
2. Yeni bir branch oluşturun: `git checkout -b feature/YeniOzellik`.
3. Değişikliklerinizi commit edin.
4. Branch'i push edin ve pull request açın.

---

# 📖 Ramadan & Annual Quran Reading Tracker (v2)

A lightweight single-file HTML tool to generate daily Ramadan and weekly annual Quran reading schedules.

## Features (English)

- Daily Ramadan schedule: one juz per day (30 days).
- Weekly annual schedule: 46-week cycle to continue the reading through the year.
- Custom starting juz for each person.
- Single juz view.
- Print-ready A4 landscape 5-column layout.
- No external dependencies.

## What's New in v2 (English)

- Hadith/info box added to the UI for contextual text.
- "Show Both" feature: render both Ramadan (daily) and Annual (weekly) programs side-by-side for a selected juz (`renderBothPrograms`).
- Animated toast notifications for success/error (`showNotification`).
- Form validation, clear list button, and improved print layout.
- Developer helpers: `renderList`, `showSingleCuz`, `showBothCuz`, `showAll`.

## Local Usage

Open `index.html` in your browser, select dates and options, then generate and print as needed. Note: the previous index was saved as `v1.html` and the v2 content is now `index.html`.

---

Made with ❤️ — katkılarınız ve geliştirmeleriniz için teşekkürler.
