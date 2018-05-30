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

Caso acontece erro de build tente:
<pre>
brew install gradle
</pre>

