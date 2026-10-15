# WiFi Connect Pro

Aplicación Android en Flutter para consultar redes Wi‑Fi cercanas, solicitar conexión mediante las API oficiales de Android, leer códigos QR Wi‑Fi y mantener perfiles e historial local.

## Estado del proyecto

**Código fuente en preparación; compilación Android todavía no verificada.** Este repositorio no debe considerarse una versión de producción hasta ejecutar `flutter pub get`, análisis, pruebas y compilación en un entorno con Flutter y Android SDK.

## Funciones incluidas en el prototipo

- Escaneo de redes Wi‑Fi mediante API de Android y permisos del sistema.
- Solicitud de conexión con `WifiNetworkSpecifier` en Android 10 o superior; Android muestra y controla la aprobación.
- Lectura de QR con formato Wi‑Fi.
- Perfiles e historial local con SQLite.
- Generación de informes PDF.
- Interfaz Material 3 y modo oscuro.

## Límites y seguridad

- No recopila ni almacena contraseñas Wi‑Fi en la base de datos.
- No vulnera redes, evita autenticación ni obtiene credenciales de terceros.
- Android puede requerir aprobación explícita para conectarse.
- La medición de velocidad, el cifrado de base de datos y otras funciones avanzadas no deben considerarse implementadas hasta verificarse en código y pruebas.

## Requisitos previstos

- Flutter SDK compatible con las dependencias de `pubspec.yaml`
- Android Studio y Android SDK
- Dispositivo Android 10 o superior para probar las solicitudes de conexión

## Preparación local

1. Instalar Flutter y Android Studio.
2. Abrir el proyecto en Android Studio.
3. Ejecutar `flutter pub get`.
4. Ejecutar `flutter analyze` y `flutter test`.
5. Corregir cualquier error de compilación y probar en un dispositivo real antes de generar APK/AAB.

Consulta `docs/IMPLEMENTATION_STATUS.md` para el estado detallado cuando el código fuente esté publicado.
