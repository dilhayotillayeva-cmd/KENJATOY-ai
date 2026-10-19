KENJATOY AI APK — faqat telefon orqali cloud build

1) GitHub hisobingiz bo'lmasa github.com saytida ro'yxatdan o'ting.
2) New repository bosing, nomi KENJATOY-AI-APK bo'lsin, Public yoki Private tanlang, Create repository.
3) Add file > Upload files orqali KENJATOY_AI_ANDROID_Project.zip faylini yuklang va Commit changes bosing.
4) Add file > Create new file bosing. Fayl nomi maydoniga aynan shuni yozing: .github/workflows/build.yml
5) Build workflow matnini ushbu paketdagi .github/workflows/build.yml faylidan ochib nusxalang, GitHub'dagi yangi faylga joylang va Commit changes bosing.
6) Reponing Actions bo'limiga kiring. “Build KENJATOY AI APK” ishga tushadi. Agar ishga tushmasa, Actions > Build KENJATOY AI APK > Run workflow ni bosing.
7) Ish muvaffaqiyatli tugagach, run ichidan Artifacts bo'limidagi KENJATOY-AI-debug-APK ni bosing va ZIP'ni yuklab oling.
8) Yuklangan artifact ZIP'ni telefoningizda oching, app-debug.apk faylini bosing va Android so'rasa ushbu manbadan ilova o'rnatishga ruxsat bering.

Eslatma: bu usul APK faylini build qiladi, ammo ilova ichidagi AI chat/rasm yaratish ishlashi uchun backendni internetga joylash va ilovadagi BACKEND_BASE_URL ni shu HTTPS manzilga sozlash kerak. Hozirgi loyiha boshlang'ich interfeys; tayyor ishlaydigan to'liq AI xizmat emas. API kalitini ilova ichiga yozmang.
