# LIOX Power — dizel generatorlar katalogi

Statik sayt (GitHub Pages): katalog, buyurtma kartasi, jismoniy va yuridik shaxslar uchun to‘lov turlari.

## Fayllar

| Fayl | Nima |
|---|---|
| `index.html` | Sayt va admin panel |
| `catalog.json` | Mahsulotlar, to‘lov turlari, sozlamalar |
| `img/` | Rasmlar |

## Saytni internetga chiqarish

1. Repozitoriy → **Settings → Pages**.
2. **Source:** Deploy from a branch → `main` → `/ (root)` → **Save**.
3. 1–2 daqiqadan keyin sayt `https://<foydalanuvchi>.github.io/<repozitoriy>/` manzilida ochiladi.

## Admin panel

Saytning eng pastidagi **Admin panel** tugmasi yoki manzil oxiriga `#admin` qo‘shing.

Birinchi marta:

1. https://github.com/settings/personal-access-tokens/new — fine-grained token yarating.
   - Repository access: **Only select repositories** → shu repozitoriy.
   - Permissions → Repository → **Contents: Read and write**.
2. Admin panel → **Sozlamalar → GitHub ulanishi** → tokenni kiriting → **Ulanishni tekshirish**.

Shundan keyin mahsulot qo‘shish, narx, rasm va to‘lov turlarini o‘zgartirib, **Saqlash va e’lon qilish** tugmasini bosasiz. O‘zgarishlar `catalog.json`ga yoziladi va sayt 1–2 daqiqada yangilanadi.

Token faqat sizning brauzeringizda saqlanadi, `catalog.json`ga yozilmaydi. Tokenni hech kimga bermang.

## Buyurtmalar

Mijoz buyurtma kartasini to‘ldiradi, sayt tayyor matn yaratadi va mijoz uni Instagram Direct, Telegram, WhatsApp yoki qo‘ng‘iroq orqali sotuvchiga yuboradi. Telegram va WhatsApp admin paneldagi Sozlamalar orqali yoqiladi. Saytda karta raqami so‘ralmaydi, onlayn to‘lov yo‘q: to‘lovni menejer tasdiqlaydi.
