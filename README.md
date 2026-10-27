# GeoPro — ijro sxemalari uchun dastur

Taxeometr / nivelir TXT faylidan tayyor ijro sxemasi (DXF, PDF, Excel) — AutoCAD va Civil 3D'siz.

- Sayt: https://braimov2002-svg.github.io/geopro/ (GitHub Pages, `docs/`; domen ulangach — https://geopro.uz)
- Yuklab olish (Windows 10/11): https://raw.githubusercontent.com/braimov2002-svg/geopro/main/docs/dl/GeoPro_Setup_1.4.3.exe
- To'liq qo'llanma (PDF): [o'zbekcha](docs/GeoPro_qollanma_uz.pdf) · [ruscha](docs/GeoPro_qollanma_ru.pdf)
- Yangilanishlar (1.3.5+): dastur ishga tushganda va har 4 soatda [`latest-v3.json`](latest-v3.json) ni tekshiradi, yangi versiyani fonda yuklab oladi va yopilganda eski versiya o'rniga o'rnatadi (yoki «Yangilash» tugmasi bilan darhol); yuklangan o'rnatuvchi keyin o'chiriladi. `latest.json` va `latest-v2.json` muzlatilgan: 1.0–1.3.4 o'zi yangilana olmaydi — bir marta joriy o'rnatuvchini o'rnatish kerak
- Telegram: https://t.me/geopro_uz · Instagram: https://instagram.com/geopro.uz

## 1.4 da nima yangi

1.4.3: natija fayli (Excel, PDF, DWG) boshqa dasturda ochiq qolsa, dastur fayl nomi bilan aniq xabar beradi (ilgari inglizcha «Permission denied» chiqardi); DWG bosqichi to'xtasa ham vaqtinchalik DXF'lar qolmaydi.

1.4.2: AutoCAD o'rnatilgan kompyuterda listlar DWG formatida ham yoziladi («Tanlab eksport qilish…» oynasida «DWG» belgisi).

1.4.1: ruscha PDF qo'llanma, «Namuna» fayli bepul ekanligi qo'llanmada to'g'rilandi, ichki qo'llanmaga chizma taklifi haqida band.

- Yangi boshlang'ich oyna (TXT tashlash maydoni, «Loyihalar», «Loyiha chizmasi», «Namuna», «Qo'llanma», oxirgi fayllar) va qayta ishlangan menyular.
- **Loyiha chizmasini dastur o'zi topadi**: TXT ochilganda oxirgi ishlatilgan va TXT papkasidagi chizmalardan s'yomka tushadiganini taklif qiladi; «Chizma → Shu s'yomkaning chizmasini topish…» (Ctrl+Shift+F) AutoCAD'da ochiq chizmalarni ham tekshiradi.
- «Chizma» menyusi: AutoCAD'da ochiq chizmani bir bosishda olish (Ctrl+Shift+D), oxirgi chizmalar, qatlamlar, ikki nuqta bo'yicha bog'lash; birlik (m/mm/sm) o'zi aniqlanadi.
- Masofa o'lchash (M), bekor qilish / qaytarish (Ctrl+Z / Ctrl+Y), nuqta qidirish (Ctrl+F), har 90 soniyada avtosaqlash va nosozlikdan keyin tiklash.
- Noutbuk ekranlari uchun ixcham sarlavha; to'liq PDF qo'llanma.

## Yangi versiya chiqarish

1. Kompyuterda `build.bat` → `dist\GeoPro_Setup_<v>.exe`
2. `python tools\release.py latest dist\GeoPro_Setup_<v>.exe https://raw.githubusercontent.com/braimov2002-svg/geopro/main/docs/dl/GeoPro_Setup_<v>.exe "nima yangi"` → `release\latest-v3.json`
3. `GeoPro_Setup_<v>.exe` → `docs/dl/` (eskisini o'chiring), `release\latest-v3.json` → repo ildiziga, commit + push (`main`). `latest.json` / `latest-v2.json` dagi versiyaga tegmang (muzlatilgan; faqat havola yangi o'rnatuvchiga)
4. Foydalanuvchilarda dastur yangi versiyani o'zi yuklab oladi va yopilganda o'rnatadi.

© 2026 Bekzod Raimov, Toshkent.
