# ThICh GateWay v1.1.5

## Ce e nou
- Repara abonarea MQTT pe topicuri partajate intre mai multe pagini.
- Corecteaza cazul in care `Incalzire` si `Exterior` ascultau acelasi topic `WEBHOOKS/STATUS`, dar subscribe-ul real putea sa nu mai fie trimis catre broker.
- Imbunatateste urmarirea topicurilor abonate si curatarea starii interne dupa deconectari MQTT.

## APK-uri
- `thich-gateway-v1.1.5-universal.apk`: recomandat daca nu stii ABI-ul telefonului.
- `thich-gateway-v1.1.5-arm64-v8a.apk`: pentru majoritatea telefoanelor Android moderne pe 64-bit.
- `thich-gateway-v1.1.5-armeabi-v7a.apk`: pentru telefoane Android mai vechi pe 32-bit.

## Instalare
1. Descarca APK-ul potrivit.
2. Verifica fisierul in `SHA256SUMS.txt`.
3. Permite instalarea din surse necunoscute daca telefonul cere asta.
4. Instaleaza APK-ul si deschide aplicatia.

## Observatii
- Aceasta versiune tinteste exact scenariul in care `Iluminat` continua sa mearga, dar `Incalzire` si `Exterior` nu mai primesc update-uri de status.
- Varianta `universal` ramane alegerea cea mai simpla pentru majoritatea telefoanelor.
