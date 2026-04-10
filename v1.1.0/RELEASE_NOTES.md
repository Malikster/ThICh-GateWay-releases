# ThICh GateWay v1.1.0

## Ce e nou
- Adauga preview-ul camerei de acces direct in ecranul principal, sub butoanele pentru Garaj si Poarta.
- Leaga aplicatia la controllerul local de la `192.168.1.135`, folosind `camera.jpg` pentru imagine si `status` pentru ritmul de refresh.
- Actualizeaza iconita launcher cu noul simbol tip casa si adauga variante dedicate pentru shortcut-urile de Garaj si Poarta.
- Adauga suport `monochrome` pentru iconita adaptiva, pentru afisare mai buna pe lansatoarele Android moderne.

## APK-uri
- `thich-gateway-v1.1.0-universal.apk`: recomandat daca nu stii ABI-ul telefonului.
- `thich-gateway-v1.1.0-arm64-v8a.apk`: pentru majoritatea telefoanelor Android moderne pe 64-bit.
- `thich-gateway-v1.1.0-armeabi-v7a.apk`: pentru telefoane Android mai vechi pe 32-bit.

## Instalare
1. Descarca APK-ul potrivit.
2. Verifica fisierul in `SHA256SUMS.txt`.
3. Permite instalarea din surse necunoscute daca telefonul cere asta.
4. Instaleaza APK-ul si deschide aplicatia.

## Observatii
- Preview-ul camerei foloseste HTTP in reteaua locala, deci telefonul trebuie sa fie conectat la aceeasi retea cu controllerul.
- Pentru majoritatea telefoanelor, varianta `universal` este cea mai simpla alegere.
