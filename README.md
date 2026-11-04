# Vohk One App

Aplicación móvil Flutter de Vohk One. El proyecto vive directamente en la raíz
del repositorio; no debe volver a anidarse dentro de una carpeta `vohk_app`.

## Requisitos

- Flutter compatible con Dart `^3.8.1`
- Android Studio/Xcode según la plataforma que se quiera compilar

## Desarrollo

```bash
flutter pub get
flutter run
```

## Verificación

```bash
flutter analyze lib test
flutter test
flutter build apk --debug
```

El nombre interno del paquete Dart continúa siendo `vohk_app` para mantener
compatibilidad con el código existente. El repositorio y producto se llaman
`vohk_one_app`.
