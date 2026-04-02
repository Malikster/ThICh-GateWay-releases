# ThICh GateWay Releases

Acest repository public conține doar artefactele de distribuție pentru aplicația Android **ThICh GateWay**: APK-uri release, checksums și release notes per versiune. Codul sursă rămâne în repository-ul privat.

## Ce este aplicația

ThICh GateWay este o aplicație Android folosită în familie pentru deschiderea garajului sau a porții după autentificare locală pe telefon și trimiterea unei comenzi prin MQTT în rețeaua internă.

## Ce găsești în acest repository

- APK-ul `universal`, compatibil cu ABI-urile suportate
- APK-uri dedicate pentru `arm64-v8a` și `armeabi-v7a`
- fișierul `SHA256SUMS.txt` pentru verificarea integrității
- release notes pentru fiecare versiune publicată

## Cum alegi APK-ul potrivit

- Folosește `thich-gateway-vX.Y.Z-universal.apk` dacă nu știi ce ABI are telefonul sau vrei varianta cea mai simplă.
- Folosește `thich-gateway-vX.Y.Z-arm64-v8a.apk` pentru majoritatea telefoanelor Android moderne cu procesor 64-bit ARM.
- Folosește `thich-gateway-vX.Y.Z-armeabi-v7a.apk` doar pentru dispozitive Android mai vechi, pe 32-bit ARM.

În general, varianta `universal` este cea mai comodă, iar varianta per-ABI este utilă dacă vrei un APK mai mic.

## Pași de instalare

1. Intră în secțiunea [Releases](../../releases).
2. Descarcă APK-ul potrivit pentru telefonul tău.
3. Compară checksum-ul fișierului descărcat cu intrarea din `SHA256SUMS.txt`.
4. Activează temporar instalarea din surse necunoscute, dacă Android cere asta.
5. Deschide APK-ul și finalizează instalarea.

## Release notes

Fiecare versiune publicată are propriile note în secțiunea [Releases](../../releases), împreună cu APK-urile și checksums aferente.

## Politica acestui repository public

- Nu conține codul sursă al aplicației.
- Nu conține keystore, chei, token-uri sau alte secrete.
- Este folosit exclusiv pentru distribuția privată a versiunilor APK.
