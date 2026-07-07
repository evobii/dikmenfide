# Dikmen Tarım — dikmenfide.com

Dikmen Tarım Ürünleri Ltd. Şti. (Dikmen Fide) tanıtım sitesi. Statik HTML/CSS/JS — framework yok, derleme adımı yok.

🌱 **Canlı:** https://dikmenfide.com · dikmentarim.com buraya yönlenir ([evobii/dikmentarim-redirect](https://github.com/evobii/dikmentarim-redirect))

## Yapı

| Dosya | İçerik |
|---|---|
| `index.html` | Tek sayfa: hero, hakkımızda, fide kataloğu, öne çıkan çeşitler, üretim süreci, neden biz, tesis bandı, iletişim/teklif formu, footer |
| `style.css` | Tasarım — koyu yeşil `#14301f` + krem `#faf7f0` + altın `#c9a961`; Fraunces (başlık) + Manrope (metin) |
| `script.js` | Navbar, mobil menü, scroll-reveal animasyonları, istatistik sayaçları, WhatsApp'a giden teklif formu |
| `assets/` | Optimize edilmiş görseller ve logolar |

## Güncelleme

```bash
# düzenle → sonra:
git add -A && git commit -m "açıklama" && git push
# GitHub Pages 1-2 dakikada otomatik yayınlar
```

`style.css` değiştiyse `index.html` içindeki `style.css?v=N` sürüm numarasını artırın (tarayıcı önbelleği için).

## İçerik kuralları

- **Aşılı fide üretilmiyor** — sitede "aşı/aşılı" ifadesi kullanılmaz
- Slogan: *"Tohumdan Fidenin Hikayesi"* · Ana marka **Dikmen Tarım**, fide markası **Dikmen Fide**
- Tohum iş ortağı: [Casta Tarım](https://castatarim.com)

## Barındırma

GitHub Pages (`main` branch, kök dizin) + özel alan adı `dikmenfide.com` (HTTPS zorunlu). DNS, Wix panelinde yönetiliyor: 4 A kaydı (185.199.108-111.153) + `www` CNAME → `evobii.github.io`.
