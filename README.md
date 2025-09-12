# EcoTrack

App prototipo para registrar notas informativas con fotos y GPS.

## Cómo generar el APK con GitHub Actions

1. Crea una cuenta en [GitHub](https://github.com).
2. Sube este proyecto a un repositorio.
3. Ve a la pestaña **Actions** y espera que compile.
4. Descarga el APK desde los **Artifacts**.

Si quieres compilar localmente:
```bash
flutter pub get
flutter build apk --release
```
El APK estará en `build/app/outputs/flutter-apk/app-release.apk`.
adb devices
