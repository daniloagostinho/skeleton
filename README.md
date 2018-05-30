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


</pre>

sera pedido uma senha para a key
88ab15cd98ef12

continuar...
