# Bek loyiha — GitHub orqali APK yig‘ish

Android Studio o‘rnatish shart emas.

1. GitHub.com saytidan **New repository** tanlang. Nomi: `Bek-loyiha`. **Public** yoki **Private** bo‘lishi mumkin. **Add README** tanlamang.
2. Ushbu ZIP arxivini kompyuteringizda **oching**. GitHub repository sahifasida **uploading an existing file** tugmasi orqali **ZIP ichidagi fayl va papkalarni** yuklang (ZIP faylning o‘zini emas). **`.github` papkasi** va uning ichidagi `workflows/android-apk.yml` ham yuklanganini tekshiring. Ba’zi tizimlarda yashirin `.github` papkasini ko‘rish kerak bo‘lishi mumkin.
3. **Commit changes** bosing va **Actions** sahifasiga o‘ting.
4. **Bek loyiha Android APK** → **Run workflow** → **Run workflow** tanlang. Birinchi `push` dan keyin build avtomatik ham ishga tushishi mumkin.
5. Ish muvaffaqiyatli tugasa, Actions dagi bajarilgan run sahifasining **Artifacts** bo‘limidan `Bek-loyiha-debug-apk` arxivini yuklab oling.
6. Arxivni ochib, ichidagi `app-debug.apk` ni Android telefoningizga ko‘chiring va o‘rnating.

**Muhim:** build faqat GitHub Actions muvaffaqiyatli ishlagandan keyin APK chiqaradi. Bu dastlabki **debug APK**, Google Play uchun imzolangan release emas. Android 8+ talab qilinishi mumkin; haqiqiy minimal versiya Android platforma build sozlamalariga bog‘liq. Yangi 6 burchakli xona funksiyasi bu v0.9 manbaga hali kiritilmagan. Poydevor sxemasi muhandislik loyihasi emas.

GitHub Actions xato bersa, muvaffaqiyatsiz qadamning logini yuboring.
