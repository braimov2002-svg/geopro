# GeoPro — ijro sxemalari uchun dastur

Taxeometr / nivelir TXT faylidan tayyor ijro sxemasi (DXF, PDF, Excel) — AutoCAD va Civil 3D'siz.

- Sayt: https://braimov2002-svg.github.io/geopro/ (GitHub Pages, `docs/`; domen ulangach — https://geopro.uz)
- Yuklab olish (Windows 10/11): https://raw.githubusercontent.com/braimov2002-svg/geopro/main/docs/dl/GeoPro_Setup_1.3.4.exe
- Yangilanishlar: dastur ishga tushganda [`latest-v2.json`](latest-v2.json) (1.3.3+; `latest.json` — 1.3.1/1.3.2 uchun muzlatilgan) ni tekshiradi va bir tugma bilan o'zi yangilanadi
- Telegram: https://t.me/geopro_uz · Instagram: https://instagram.com/geopro.uz

## Yangi versiya chiqarish

1. Kompyuterda `build.bat` → `dist\GeoPro_Setup_<v>.exe`
2. `python tools\release.py latest dist\GeoPro_Setup_<v>.exe https://raw.githubusercontent.com/braimov2002-svg/geopro/main/docs/dl/GeoPro_Setup_<v>.exe "nima yangi"` → `release\latest.json`
3. `GeoPro_Setup_<v>.exe` → `docs/dl/`, `release\latest.json` → repo ildiziga **`latest-v2.json`** nomi bilan, commit + push (`main`). `latest.json` ga tegmang (1.3.1/1.3.2 uchun muzlatilgan)
4. Barcha foydalanuvchilarda dastur ochilganda «… ga yangilash» tugmasi chiqadi.

© 2026 Bekzod Raimov, Toshkent.
