# 🔍 Robotzade Web Scraping Projesi

Bu proje, [Robotzade.com](https://www.robotzade.com)'daki ürünleri otomatik olarak tarayıp her ürünün detay sayfasından şu bilgileri çeker:

- ✅ Ürün adı
- ✅ KDV dahil fiyat
- ✅ Stok durumu (stokta var / yok)
- ✅ Ürün bağlantı linki

---

## ⚙️ Kullanılan Teknolojiler

- `Python 3.8+`
- `requests`
- `BeautifulSoup`
- `pandas`

---
## 📌 Notlar
Sayfa sayısı otomatik algılanır: Ürün olmayan sayfalarda tarama durur.

Detay sayfasından alınan bilgiler daha doğrudur (fiyat/indirim/etiket).
