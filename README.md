# GeoPro — ijro sxemalari uchun dastur

Taxeometr / nivelir TXT faylidan tayyor ijro sxemasi (DXF, PDF, Excel) — AutoCAD va Civil 3D'siz.

- Sayt: https://braimov2002-svg.github.io/geopro/ (GitHub Pages, `docs/`; domen ulangach — https://geopro.uz)
- Yuklab olish (Windows 10/11): https://raw.githubusercontent.com/braimov2002-svg/geopro/main/docs/dl/GeoPro_Setup_1.3.5.exe
- Yangilanishlar (1.3.5+): dastur ishga tushganda va har 4 soatda [`latest-v3.json`](latest-v3.json) ni tekshiradi, yangi versiyani fonda yuklab oladi va yopilganda eski versiya o'rniga o'rnatadi (yoki «Yangilash» tugmasi bilan darhol); yuklangan o'rnatuvchi keyin o'chiriladi. `latest.json` va `latest-v2.json` muzlatilgan: 1.0–1.3.4 o'zi yangilana olmaydi — bir marta 1.3.5 ni o'rnatish kerak
- Telegram: https://t.me/geopro_uz · Instagram: https://instagram.com/geopro.uz

## Yangi versiya chiqarish

1. Kompyuterda `build.bat` → `dist\GeoPro_Setup_<v>.exe`
2. `python tools\release.py latest dist\GeoPro_Setup_<v>.exe https://raw.githubusercontent.com/braimov2002-svg/geopro/main/docs/dl/GeoPro_Setup_<v>.exe "nima yangi"` → `release\latest-v3.json`
3. `GeoPro_Setup_<v>.exe` → `docs/dl/` (eskisini o'chiring), `release\latest-v3.json` → repo ildiziga, commit + push (`main`). `latest.json` / `latest-v2.json` ga tegmang (muzlatilgan)
4. Foydalanuvchilarda dastur yangi versiyani o'zi yuklab oladi va yopilganda o'rnatadi.

© 2026 Bekzod Raimov, Toshkent.
