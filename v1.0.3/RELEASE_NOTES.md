# ThICh GateWay v1.0.3

## Ce e nou
- Adauga interfata noua pe swipe cu ecrane separate pentru Acces, Iluminat si Incalzire.
- Muta comenzile de iluminat pe brokerul MQTT local, pe topicul `LIGHTS/SWITCH`, cu maparea actualizata a butoanelor.
- Pastreaza autentificarea Android si fallback-ul remote doar pentru ecranul de Acces.
- Adauga optiunea `Debug` in Setari pentru afisarea configuratiei de conectivitate si relay remote.
- Repara cererile de activare retained care reapareau dupa restart.

## APK-uri
- `thich-gateway-v1.0.3-universal.apk`: recomandat daca nu stii ABI-ul telefonului.
- `thich-gateway-v1.0.3-arm64-v8a.apk`: pentru majoritatea telefoanelor Android moderne pe 64-bit.
- `thich-gateway-v1.0.3-armeabi-v7a.apk`: pentru telefoane Android mai vechi pe 32-bit.

## Instalare
1. Descarca APK-ul potrivit.
2. Verifica fisierul in `SHA256SUMS.txt`.
3. Permite instalarea din surse necunoscute daca telefonul cere asta.
4. Instaleaza APK-ul si deschide aplicatia.

## Observatii
- Aplicatia este distribuita privat, in afara Google Play.
- Pentru majoritatea telefoanelor, varianta `universal` este cea mai simpla alegere.
