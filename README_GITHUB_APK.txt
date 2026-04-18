AFTEM Mobil Istasyon - GitHub Actions ile APK Alma

Bu klasoru oldugu gibi yeni bir GitHub reposuna yukle.

Adimlar:
1. Bu klasordeki tum dosyalari GitHub'da yeni bir repoya at
2. Repo acilinca Actions sekmesine gir
3. "Build Android APK" workflow'unu sec
4. "Run workflow" de
5. Islem bitince artifact icinden APK dosyasini indir

Olusan dosya:
- app-debug.apk

Not:
- Bu surum debug APK uretir
- Telefon ilk acilista istasyon ve API adresi ister
- API icin PC'de AFTEM_MOBIL_SERVER_BASLAT.bat calisiyor olmali
