# Landing Page - Testimonials & Contact

Tailwind CSS ile hazırlanmış, müşteri yorumları ve iletişim formu içeren tek sayfalık landing page.

---

## Bölümler

| Bölüm | Açıklama |
|-------|----------|
| **Header** | Sol: 3 navigasyon linki (ilk aktif/altı çizili), orta: mor logo, sağ: arama kutusu + "Log in" butonu |
| **Hero** | Büyük başlık (mor vurgulu kelimeler), kısa açıklama, "Get started" butonu ve "Learn more" linki |
| **Testimonials** | "What our customers are saying about us" başlığı, 4 adet beyaz kart (tırnak işareti, metin, avatar, mor alt şerit – isim ve unvan) |
| **Contact us** | Beyaz kart içinde "Contact us" başlığı, Name / Email / Message alanları ve "Send" butonu |
| **Footer** | Sol: Shop, About, Blog, Pricing, Contact linkleri; sağ: Instagram, Pinterest, Twitter, Facebook, Google yuvarlak ikonlar |

---

## Dosya yapısı

```
landing-testimonials-contact/
├── index.html
└── README.md
```

---

## Çalıştırma

`index.html` dosyasını tarayıcıda açın. Tailwind CDN kullanıldığı için ek kurulum gerekmez.

```bash
cd landing-testimonials-contact
npx serve .
# veya
python3 -m http.server 8080
```

---

## Teknolojiler

- HTML5
- Tailwind CSS (CDN)
- Google Fonts (Inter)
