# İsmail Kaçın — Portfolio

Frontend & Backend geliştirici portfolyo sitesi. React (Vite), Tailwind CSS, Framer Motion ile geliştirilmiş; GitHub Pages için uyumlu.

---

## Tasarım Dili ve Renk Paleti

**Stil:** Minimalist, premium; Apple / Stripe dokümantasyonu hissi. Bol beyaz alan, tipografi odaklı.  

**Renkler:**  
- Light: Arka plan `#f8fafc` (paper), metin `#0f172a` (ink), vurgu `#0ea5e9` (brand)  
- Dark: Arka plan `#0f172a`, metin `#f8fafc`, vurgu `#0ea5e9`  

**Tipografi:** Inter (Google Fonts)  
**Etkileşimler:** Framer Motion ile scroll/hover animasyonları; WCAG uyumlu odak halkaları

---

## Geliştirme

```bash
npm install
npm run dev

GitHub Pages’e Yükleme

Seçenek 1: GitHub Actions (önerilen)

Repoyu GitHub’a push edin.

Settings → Pages → Build and deployment → Source: “Deploy from a branch” seçin, Branch: gh-pages (klasör: / (root)).

main seçiliyse sayfa beyaz kalır ve /src/main.jsx 404 hatası alırsınız — build çıktısı sadece gh-pages branch’inde olmalı.

Actions sekmesinde “Deploy to GitHub Pages” workflow’unun yeşil (başarılı) çalıştığından emin olun.

Seçenek 2: Manuel (gh-pages)
