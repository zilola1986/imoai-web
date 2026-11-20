# ImoAI Web v1.0 — GitHub Pages

Bu versiya Python dasturining brauzerga moslashtirilgan **demo** varianti. Besh qo‘l holatiga shartli ravishda SALOM, TO‘XTA, YAXSHI, BIR, IKKI so‘zlari bog‘langan. **Bu haqiqiy o‘zbek imo-ishora tili tarjimoni emas.**

## GitHub Pages'ga joylashtirish

1. GitHub hisobingizga kiring: https://github.com
2. **New repository** → nomi `imoai-web` → **Public** → **Create repository**.
3. **Add file → Upload files** orqali `index.html`, `style.css`, `app.js` fayllarini repozitoriy **asosiy (root)** qismiga yuklang. ZIP faylning o‘zini yuklamang.
4. **Commit changes** bosing.
5. **Settings → Pages → Build and deployment → Deploy from a branch** ni tanlang. Branch: **main**, Folder: **/(root)** → **Save**.
6. Biroz kuting. Sayt odatda `https://USERNAME.github.io/imoai-web/` manzilida ochiladi (USERNAME o‘rnida GitHub foydalanuvchi nomingiz bo‘ladi). **Settings → Pages** da haqiqiy manzilni tekshiring.
7. Saytni ochib **Kamerani boshlash** ni bosing va brauzer kamera ruxsatini so‘raganda tasdiqlang.

## Talablar va cheklovlar

- Internet kerak: MediaPipe Hands JS va uning model fayllari CDN orqali olinadi.
- GitHub Pages HTTPS bilan ishlaydi; kamera uchun HTTPS zarur.
- Kamera tasviri serverga yuborilmaydi, ishlov brauzer ichida bajariladi.
- `Ovozli o‘qish` brauzerning speechSynthesis funksiyasiga bog‘liq; o‘zbekcha ovoz bo‘lmasligi yoki talaffuz noto‘g‘ri bo‘lishi mumkin.
- Qo‘lni aniqlash Python demo qoidalariga yaqinlashtirilgan, ammo brauzer va kamera farqi sababli aniqlikni alohida tekshirish zarur.
- Ishora 0,65 soniya ushlab turilgach matnga qo‘shiladi. Takrorlash uchun qo‘lni kadrdan olib qayta ko‘rsating.
- Bosh barmoq yuqoriga qaraganda YAXSHI, gorizontal/bukilgan mushtda TO‘XTA deb belgilash ko‘zlangan.
- GitHub repozitoriyga shaxsiy video, yuz tasviri, maxfiy fayllar yoki parollarni yuklamang.

## Fayllar
- `index.html` — interfeys
- `style.css` — dizayn
- `app.js` — kamera va qo‘l holati klassifikatori

## Muammo bo‘lsa
- Kamera ishlamasa: brauzer ruxsatlari, HTTPS va boshqa kamera ishlatayotgan dasturlarni tekshiring.
- MediaPipe yuklanmasa: internet/CDN bloklanmaganini tekshiring.
- Telefonda brauzer qo‘llab-quvvatlashi turlicha bo‘lishi mumkin; tanlov oldidan aynan ishlatiladigan qurilmada sinang.
