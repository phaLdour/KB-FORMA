# KB Spor — Prototype

Tek dosyada çalışan, hub'lar arası sinematik geçişli interaktif KB Spor prototipi.

## İçerik

- **KB Spor** anasayfa (kinetic)
- **KB Futbol** — saha kimliği, lig filtreleri
- **KB Basket** — parke kimliği, NBA + BSL, yakında ayakkabı
- **Maison KB** — editorial mood, klasik koleksiyon
- **KB.LAB** — interaktif 3D-feel forma konfigüratörü
- **PDP** — forma detay sayfası
- **Kayıt / Giriş / Hesap** — localStorage tabanlı
- **İletişim** — AI destekli KB Asistan

## Çalıştırma

`index.html` dosyasını bir tarayıcıda açın. Statik bir dosya, build adımı yok.

## Yapı

```
index.html              Giriş noktası
src/
  styles.css            Tasarım sistemi (renkler, tipografi, mood'lar)
  shared.jsx            Header, Footer, Brand, Router, Auth, JerseyArt
  tweaks-panel.jsx      Tweaks paneli bileşenleri
  page-*.jsx            Sayfalar
  app.jsx               Boot + router
```

## GitHub Pages

`Settings → Pages → Source: main / root` ile yayınlanır.

---

© 2026 KB Spor — Crafted for Champions.
