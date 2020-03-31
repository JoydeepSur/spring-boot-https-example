command to generate self-singed certificate (.jks file)-
keytool -genkey -keyalg RSA -alias https-example -keystore https-example.jks -validity 365 -keysize 2048