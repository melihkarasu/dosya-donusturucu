# Evrensel Dosya & Format Dönüştürücü (Standalone Edition)

Görsel (PNG, WEBP, JPG) ve yapısal veri (JSON, CSV, XML, Markdown) dosyaları için çok formatlı dönüştürücü.

- **Canlı Demo (GitHub Pages):** https://melihkarasu.github.io/dosya-donusturucu/
- **Ana Proje (Monorepo):** [melihkarasu/VibeCodedApps](https://github.com/melihkarasu/VibeCodedApps)

## Mimari & Gizlilik Özellikleri
- **Sıfır Backend (Zero-Backend):** Tamamen tarayıcı üzerinde çalışır; kullanıcı verileri VibeRuntime üzerinden yalnızca localStorage içinde saklanır.
- **KVKK & GDPR Uyumu:** Google Fonts CDN veya 3. taraf takip betiği içermez; tüm fontlar (vendor/fonts/*.woff2) yerel olarak paketlenmiştir.

## Lokal Çalıştırma
```bash
npx serve .
```
