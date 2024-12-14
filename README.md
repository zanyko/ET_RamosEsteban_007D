cuenta docente: docente2,
    contraseña: viceraes

Dependencias necesarias para correr en android

( se debe trabajar con Ionic 6 para evitar problemas )

npm install angularx-qrcode --save
npm install swiper@latest

npm install @capacitor/android
npx cap add android
ionic capacitor sync android
ionic capacitor copy android
ionic capacitor open android
