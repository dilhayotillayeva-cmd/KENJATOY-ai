# KENJATOY AI — Android Studio loyihasi

Bu APK emas, balki Android Studio orqali APK yig‘ish uchun boshlang‘ich loyiha. Qora-binafsha dizaynli chat interfeysi bor.

## APK qilish
1. Android Studio o‘rnatilgan kompyuterda shu papkani oching.
2. `app/src/main/java/com/kenjatoy/ai/MainActivity.kt` ichidagi `BACKEND_BASE_URL` ni o‘zingizning HTTPS backend manzilingizga almashtiring.
3. Gradle Sync qiling.
4. Build > Build APK(s) ni bosing.
5. APK odatda `app/build/outputs/apk/debug/app-debug.apk` ichida paydo bo‘ladi.

AI ishlashi uchun KENJATOY backendini internetga joylash kerak. API kalitini APK ichiga yozmang — faqat serverda saqlang. AI va rasm yaratish API xizmatlari pulli bo‘lishi mumkin.

Ushbu muhitda Android SDK bilan APKni build qilib tekshirish imkoni yo‘q.
