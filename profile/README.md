# Connect Tag (كونكت تاق) — Open-Source Libraries 🚀

مرحباً بك في المستودع المركزي للمكتبات مفتوحة المصدر من **Connect Tag**.
حزمة مكتبات حديثة وموثوقة لأنظمة **Android** و **Kotlin Multiplatform (KMP)** تم تصميمها وفق أفضل الممارسات، خفيفة الوزن، ومستقلة بدون أي ربط غير ضروري.

---

## 📦 كيفية التضمين (Installation Setup)

أضف مستودع JitPack إلى ملف `settings.gradle.kts`:

```kotlin
dependencyResolutionManagement {
    repositories {
        google()
        mavenCentral()
        maven { url = uri("https://jitpack.io") }
    }
}
```

---

## 📚 المكتبات المتاحة (Available Libraries)

| المكتبة (Library) | الإصدار (Badge) | الوصف (Description) | التضمين (Dependency) |
|---|---|---|---|
| **[crypto-suite](https://github.com/connecttag/crypto-suite)** | [![JitPack](https://jitpack.io/v/connecttag/crypto-suite.svg)](https://jitpack.io/#connecttag/crypto-suite) | مكتبة تشفير KMP نقية (AES, RSA, HMAC, Base64) تدعم Android و JVM. | `implementation("com.github.connecttag:crypto-suite:1.0.0")` |
| **[security-kit](https://github.com/connecttag/security-kit)** | [![JitPack](https://jitpack.io/v/connecttag/security-kit.svg)](https://jitpack.io/#connecttag/security-kit) | إدارة وتشفير المفاتيح عبر Android Keystore والتحقق من البصمة. | `implementation("com.github.connecttag:security-kit:1.0.0")` |
| **[integrity-guard](https://github.com/connecttag/integrity-guard)** | [![JitPack](https://jitpack.io/v/connecttag/integrity-guard.svg)](https://jitpack.io/#connecttag/integrity-guard) | فحص سلامة النظام واكتشاف الـ Root والـ Emulators والتلاعب بالتطبيق. | `implementation("com.github.connecttag:integrity-guard:1.0.0")` |
| **[country-picker-compose](https://github.com/connecttag/country-picker-compose)** | [![JitPack](https://jitpack.io/v/connecttag/country-picker-compose.svg)](https://jitpack.io/#connecttag/country-picker-compose) | منتقي دول بـ Jetpack Compose مع أعلام الإيموجي ومربعات البحث. | `implementation("com.github.connecttag:country-picker-compose:1.0.0")` |
| **[country-lib-kmp](https://github.com/connecttag/country-lib-kmp)** | [![JitPack](https://jitpack.io/v/connecttag/country-lib-kmp.svg)](https://jitpack.io/#connecttag/country-lib-kmp) | قاعدة بيانات ومعلومات الدول ومفاتيح الاتصال لـ Kotlin Multiplatform. | `implementation("com.github.connecttag:country-lib-kmp:1.0.0")` |
| **[app-lock-android](https://github.com/connecttag/app-lock-android)** | [![JitPack](https://jitpack.io/v/connecttag/app-lock-android.svg)](https://jitpack.io/#connecttag/app-lock-android) | قفل التطبيقات بالأمان الحيوي (Biometric) ورمز PIN وتتبع المحاولات. | `implementation("com.github.connecttag:app-lock-android:1.0.0")` |
| **[network-monitor-android](https://github.com/connecttag/network-monitor-android)** | [![JitPack](https://jitpack.io/v/connecttag/network-monitor-android.svg)](https://jitpack.io/#connecttag/network-monitor-android) | مراقبة الاتصال بالإنترنت والشبكة لحظياً عبر Flow و ConnectivityManager. | `implementation("com.github.connecttag:network-monitor-android:1.0.0")` |
| **[wifi-kit](https://github.com/connecttag/wifi-kit)** | [![JitPack](https://jitpack.io/v/connecttag/wifi-kit.svg)](https://jitpack.io/#connecttag/wifi-kit) | إدارة وعمليات شبكات الواي فاي واقتراحات الشبكة (Network Suggestions). | `implementation("com.github.connecttag:wifi-kit:1.0.0")` |
| **[file-picker-android](https://github.com/connecttag/file-picker-android)** | [![JitPack](https://jitpack.io/v/connecttag/file-picker-android.svg)](https://jitpack.io/#connecttag/file-picker-android) | منتقي ملفات متوافق مع Android 14+ وواجهات Jetpack Compose. | `implementation("com.github.connecttag:file-picker-android:1.0.0")` |
| **[downloader](https://github.com/connecttag/downloader)** | [![JitPack](https://jitpack.io/v/connecttag/downloader.svg)](https://jitpack.io/#connecttag/downloader) | إدارة تنزيل الملفات في الخلفية مع تتبع التقدم والسرعة عبر Coroutines. | `implementation("com.github.connecttag:downloader:1.0.0")` |
| **[battery-monitor](https://github.com/connecttag/battery-monitor)** | [![JitPack](https://jitpack.io/v/connecttag/battery-monitor.svg)](https://jitpack.io/#connecttag/battery-monitor) | مراقبة تفاعلية لحالة البطارية ونمط توفير الطاقة. | `implementation("com.github.connecttag:battery-monitor:1.0.0")` |
| **[local-web-server](https://github.com/connecttag/local-web-server)** | [![JitPack](https://jitpack.io/v/connecttag/local-web-server.svg)](https://jitpack.io/#connecttag/local-web-server) | خادم ويب محلي (Embedded HTTP Server) خفيف الوزن يعمل داخل نظام أندرويد. | `implementation("com.github.connecttag:local-web-server:1.0.0")` |
| **[common-models](https://github.com/connecttag/common-models)** | [![JitPack](https://jitpack.io/v/connecttag/common-models.svg)](https://jitpack.io/#connecttag/common-models) | نماذج المجال الأساسية (Result, CollectionResult, UiState) لـ KMP مع Serialization. | `implementation("com.github.connecttag:common-models:1.0.0")` |
| **[interaction-feedback](https://github.com/connecttag/interaction-feedback)** | [![JitPack](https://jitpack.io/v/connecttag/interaction-feedback.svg)](https://jitpack.io/#connecttag/interaction-feedback) | ردود الفعل اللمسية والاهتزازات التفاعلية (Haptic Feedback). | `implementation("com.github.connecttag:interaction-feedback:1.0.0")` |

---

## 🛡️ الترخيص (License)
جميع المكتبات مرخصة ومتاحة تحت رخصة [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0.txt).
