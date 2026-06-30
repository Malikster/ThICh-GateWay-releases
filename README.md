# ThICh GateWay Releases

Ultima versiune publicata: v1.2.4

Ultima versiune publicata: v1.2.3

Ultima versiune publicata: v1.2.2

Ultima versiune publicata: v1.2.1

Ultima versiune publicata: v1.2.0

Acest repository public contine doar artefactele de distributie pentru aplicatia Android **ThICh GateWay**: APK-uri release, checksums si release notes per versiune. Codul sursa ramane in repository-ul privat.

## Ce este aplicatia

ThICh GateWay este o aplicatie Android folosita in familie pentru deschiderea garajului sau a portii dupa autentificare locala pe telefon si trimiterea unei comenzi prin MQTT in reteaua interna.

## Ce gasesti in acest repository

- APK-ul `universal`, compatibil cu ABI-urile suportate
- APK-uri dedicate pentru `arm64-v8a` si `armeabi-v7a`
- fisierul `SHA256SUMS.txt` pentru verificarea integritatii
- release notes pentru fiecare versiune publicata

## Cum alegi APK-ul potrivit

- Foloseste `thich-gateway-vX.Y.Z-universal.apk` daca nu stii ce ABI are telefonul sau vrei varianta cea mai simpla.
- Foloseste `thich-gateway-vX.Y.Z-arm64-v8a.apk` pentru majoritatea telefoanelor Android moderne cu procesor 64-bit ARM.
- Foloseste `thich-gateway-vX.Y.Z-armeabi-v7a.apk` doar pentru dispozitive Android mai vechi, pe 32-bit ARM.

In general, varianta `universal` este cea mai comoda, iar varianta per-ABI este utila daca vrei un APK mai mic.

## Pasi de instalare

1. Intra in sectiunea [Releases](../../releases).
2. Descarca APK-ul potrivit pentru telefonul tau.
3. Compara checksum-ul fisierului descarcat cu intrarea din `SHA256SUMS.txt`.
4. Activeaza temporar instalarea din surse necunoscute, daca Android cere asta.
5. Deschide APK-ul si finalizeaza instalarea.

## Release notes

Fiecare versiune publicata are propriile note in sectiunea [Releases](../../releases), impreuna cu APK-urile si checksums aferente.

## Politica acestui repository public

- Nu contine codul sursa al aplicatiei.
- Nu contine keystore, chei, token-uri sau alte secrete.
- Este folosit exclusiv pentru distributia privata a versiunilor APK.





