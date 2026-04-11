# ThICh GateWay v1.1.1

## Ce e nou
- Adauga controale MQTT live pentru ecranul de `Incalzire`, cu butoane on/off si sincronizare automata din `WEBHOOKS/STATUS`.
- Adauga pagina noua `Exterior` pentru `Lumina foisor` si `Pompa piscina`, controlate prin `WEBHOOKS/COMMANDS`.
- Permite mai multi listeneri pe acelasi topic MQTT, astfel incat ecranele care asculta status sa se actualizeze corect in paralel.

## APK-uri
- `thich-gateway-v1.1.1-universal.apk`: recomandat daca nu stii ABI-ul telefonului.
- `thich-gateway-v1.1.1-arm64-v8a.apk`: pentru majoritatea telefoanelor Android moderne pe 64-bit.
- `thich-gateway-v1.1.1-armeabi-v7a.apk`: pentru telefoane Android mai vechi pe 32-bit.

## Instalare
1. Descarca APK-ul potrivit.
2. Verifica fisierul in `SHA256SUMS.txt`.
3. Permite instalarea din surse necunoscute daca telefonul cere asta.
4. Instaleaza APK-ul si deschide aplicatia.

## Observatii
- Statusul pentru `Incalzire` si `Exterior` urmareste ordinea bitilor din bridge-ul `WEBHOOKS/STATUS`: `Dressing`, `DMare`, `DMic`, `BM`, `Foisor`, `Piscina`.
- Varianta `universal` ramane alegerea cea mai simpla pentru majoritatea telefoanelor.
