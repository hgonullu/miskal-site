# miskal.app

Miskal'ın tanıtım sayfası ve gizlilik politikaları. Dört statik dosya; derleme
adımı yok.

| Adres | Dosya |
|---|---|
| `miskal.app/` | `index.html` |
| `miskal.app/gizlilik` | `gizlilik.html` |
| `miskal.app/privacy` | `privacy.html` |

**Bu dosyalar elle düzenlenmez.** Kaynakları uygulama deposundaki
`docs/gizlilik-politikasi.md` ve `docs/privacy-policy-en.md` dosyaları;
`tools/build-site.py` onlardan üretiyor. Politika metni değişince script
çalıştırılır ve çıkan dosyalar buraya kopyalanır. Böylece yayındaki metin ile
gözden geçirilen metin birbirinden ayrılamaz.

`CNAME` dosyası alan adını GitHub Pages'e bağlar; silmeyin.
