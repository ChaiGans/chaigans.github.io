# purritify-domain

https://chaigans.github.io/purritify-domain/

Generate keystore command

```
keytool -genkeypair \
  -v \
  -keystore release-key.jks \
  -alias purritify \
  -keyalg RSA \
  -keysize 2048 \
  -validity 10000 \
  -storetype JKS
```
