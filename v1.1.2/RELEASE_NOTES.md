# ThICh GateWay v1.1.2

## Ce e nou
- Repara sincronizarea butoanelor MQTT pentru `Iluminat`, `Incalzire` si `Exterior`.
- Corecteaza cazul in care mai multe ecrane porneau in paralel si unele `subscribe()` la topicurile de status nu se mai inregistrau corect.
- Pastreaza controalele adaugate in `1.1.1`, dar cu actualizare stabila din `LIGHTS/STATUS` si `WEBHOOKS/STATUS`.

## APK-uri
- `thich-gateway-v1.1.2-universal.apk`: recomandat daca nu stii ABI-ul telefonului.
- `thich-gateway-v1.1.2-arm64-v8a.apk`: pentru majoritatea telefoanelor Android moderne pe 64-bit.
- `thich-gateway-v1.1.2-armeabi-v7a.apk`: pentru telefoane Android mai vechi pe 32-bit.

## Instalare
1. Descarca APK-ul potrivit.
2. Verifica fisierul in `SHA256SUMS.txt`.
3. Permite instalarea din surse necunoscute daca telefonul cere asta.
4. Instaleaza APK-ul si deschide aplicatia.

## Observatii
- Fixul vizeaza in special pornirea aplicatiei cu mai multe pagini active care folosesc acelasi broker MQTT.
- Varianta `universal` ramane alegerea cea mai simpla pentru majoritatea telefoanelor.
