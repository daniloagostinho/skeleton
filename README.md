# skeleton 

Config de Build app apk

### Passo a passo

1. Rm plugin cordova console

<pre>
ionic cordova plugin rm cordova-plugin-console
</pre>
2. Buil da versao android

<pre>
ionic cordova build --release android
</pre>

Caso acontece erro de build tente, e rode o build apk novamente.
<pre>
brew install gradle
</pre>

Apk sera gerado no endereco:
<pre>
/Users/danilosilva/Desktop/skeleto/platforms/android/app/build/outputs/apk/release/app-release-unsigned.apk
</pre>

3. Gera um aprivate key
<pre>
keytool -genkey -v -keystore nome-key.keystore -alias nome-key -keyalg RSA -keysize 2048 -validity 10000
</pre>

sera pedido uma senha para a key
88ab15cd98ef12

4. Emular ios
<pre>
ionic cordova build ios 
ionic cordova emulate ios -l
</pre>

5. Emular Android
<pre>
ionic cordova build android
ionic cordova emulate android -l
</pre>

6. Build Android
<pre>
ionic cordova platform add android
ionic cordova build android
ionic cordova build android -prod
</pre>

