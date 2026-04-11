# ThICh GateWay v1.1.3

## Ce e nou
- Repara resubscribe-ul MQTT dupa reconnect la broker.
- Stabilizeaza actualizarea butoanelor din `Iluminat`, `Incalzire` si `Exterior` dupa deconectari sau reconectari automate.
- Pastreaza fixurile din `1.1.2`, dar adauga refacerea explicita a abonamentelor active la `connectComplete`.

## APK-uri
- `thich-gateway-v1.1.3-universal.apk`: recomandat daca nu stii ABI-ul telefonului.
- `thich-gateway-v1.1.3-arm64-v8a.apk`: pentru majoritatea telefoanelor Android moderne pe 64-bit.
- `thich-gateway-v1.1.3-armeabi-v7a.apk`: pentru telefoane Android mai vechi pe 32-bit.

## Instalare
1. Descarca APK-ul potrivit.
2. Verifica fisierul in `SHA256SUMS.txt`.
3. Permite instalarea din surse necunoscute daca telefonul cere asta.
4. Instaleaza APK-ul si deschide aplicatia.

## Observatii
- Aceasta versiune tinteste exact scenariul in care brokerul se deconecteaza, iar ecranele raman fara update de status.
- Varianta `universal` ramane alegerea cea mai simpla pentru majoritatea telefoanelor.
