# f_random_user_template

Implementar:
- UserRemoteDataSource
- UserLocalDataSource con los métodos sqflite (recordar el uso de await con métodos que retornan un futuro)
- UserRepository

<img src="https://github.com/mvlopez02/RandomUserApp/blob/a7cd7d36869ea2b7b108680f0e8a2478574f8953/videoprueba_random_user.gif" width="300" />

Se recomienda ver el video completo: ![VideoPrueba](https://github.com/mvlopez02/RandomUserApp/blob/f8b3c94dee3d06185e403a3c3af882484ceecdc3/videoprueba_random_user.webm)

Implementación en: https://github.com/augustosalazar/f_local_database_sqlite

Referencias:

https://pub.dev/packages/sqflite

Run the integration test with:

flutter drive --driver test_driver/integration_test.dart --target integration_test/app_test.dart
