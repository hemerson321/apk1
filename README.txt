Projeto Android WebView - Gold Itinerarios

URL fixa:
https://server.geratec.com.br/itinerarios/gold/

Recursos configurados:
- WebView tela cheia
- Sem ActionBar / sem barra superior
- Barras de rolagem do WebView desativadas
- Autoplay liberado no WebView: setMediaPlaybackRequiresUserGesture(false)
- JavaScript e DOM Storage ativados
- Permissão automática para câmera/microfone dentro do WebView

Para gerar o APK no Android Studio:
1. Abra a pasta GeratecGoldWebView no Android Studio.
2. Aguarde sincronizar o Gradle.
3. Vá em Build > Build Bundle(s) / APK(s) > Build APK(s).
4. O APK ficará em: app/build/outputs/apk/debug/app-debug.apk
