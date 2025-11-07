# WordMemorizer - Android App (Kotlin + Jetpack Compose)

Bu arşiv Android Studio'da açılıp **APK oluşturulabilecek** bir başlangıç projesidir.
**Not:** Bu ortamda APK oluşturamıyorum; sizden Android Studio (ve SDK) ile projeyi açıp `Build > Build Bundle(s) / APK(s)` yapmanızı isteyeceğim.

## Özellikler (skeleton)
- Kelime ekleme (ing/tr anlam, örnek cümle B1/C1, IPA)
- Testler: çoktan seçmeli, boşluk doldurma, eşleştirme (skeleton UI)
- Basit istatistik ve "zor" işaretleme
- Offline: Room veritabanı için hazır yer
- Material 3 + Koyu/Açık tema

## Nasıl kullanılır
1. Bu zip'i açın.
2. Android Studio'yu açın ve `Open` > klasörü seçin.
3. Gradle ve Android SDK indirilmesini bekleyin.
4. Sol üstten `Build > Build Bundle(s) / APK(s) > Build APK(s)` seçin.
5. Oluşan APK `app/build/outputs/apk/debug/app-debug.apk` altında bulunacaktır.

## Sınırlamalar
- Bu paket **Gradle wrapper jar** veya SDK içermez. Android Studio wrapper'ı indirecektir.
- Cambridge Dictionary otomatik çekme için network kodu şablonu var; ama API kullanım şartlarını kontrol edin.
- Proje bir iskelet (skeleton) — tüm test mantıkları örnek/placeholder olarak konmuştur. İsterseniz uygulamayı genişletip tam işlevsel hâle getirebilirim.

## Yardım
- Projeyi açarken hata alırsanız Android Studio sürümünüzü 8.x ve Kotlin 1.9.x olarak güncelleyin.
- Benim tarafımdan daha fazla özellik eklensin ister misiniz? (ör. backup/restore, CSV import/export, TTS)
