# springbootssl
Spring boot application with SSL communication

### Steps:-

1. Clone app.

2. Generate keystore with the following command:-

   keytool -genkey -alias tomcat -storetype PKCS12 -keyalg RSA -keysize 2048 -keystore keystore.p12 -validity 3650

3. Run the app

4. Access the app https://localhost:8443




