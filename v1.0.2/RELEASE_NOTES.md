# ThICh GateWay v1.0.2

## Ce e nou
- Adauga fallback remote prin flespi atunci cand brokerul MQTT local nu raspunde.
- Introduce relay securizat AES-GCM pentru comenzile trimise din afara retelei locale.
- Adauga configurare mai simpla pentru deploy-ul de pe Raspberry Pi.

## APK-uri
- `thich-gateway-v1.0.2-universal.apk`: recomandat daca nu stii ABI-ul telefonului.
- `thich-gateway-v1.0.2-arm64-v8a.apk`: pentru majoritatea telefoanelor Android moderne pe 64-bit.
- `thich-gateway-v1.0.2-armeabi-v7a.apk`: pentru telefoane Android mai vechi pe 32-bit.

## Instalare
1. Descarca APK-ul potrivit.
2. Verifica fisierul in `SHA256SUMS.txt`.
3. Permite instalarea din surse necunoscute daca telefonul cere asta.
4. Instaleaza APK-ul si deschide aplicatia.

## Observatii
- Aplicatia este distribuita privat, in afara Google Play.
- Configureaza in aplicatie adresa brokerului local daca difera de valoarea implicita.
