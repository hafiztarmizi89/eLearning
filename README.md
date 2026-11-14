# Kiki Belajar - Versi 2.0 (Windows dan MacBook)

## Cara 1: GitHub Actions (tidak perlu pasang apa-apa)
1. Buat akaun GitHub percuma dan satu repositori baharu.
2. Muat naik semua fail dalam folder ini (termasuk folder .github).
3. Buka tab Actions, pilih "Build Kiki Belajar", tekan "Run workflow".
4. Selepas siap, muat turun fail .exe (Windows) dan .dmg (MacBook) di bahagian Artifacts.

## Cara 2: Bina sendiri
Perlu Node.js 20 atau lebih baharu.
- Windows: buka terminal dalam folder ini, jalankan `npm install` kemudian `npm run dist`. Fail .exe ada dalam folder dist.
- MacBook: langkah sama pada MacBook. Fail .dmg ada dalam folder dist. Fail .dmg hanya boleh dibina pada Mac.
- Untuk mencuba tanpa membina: `npm install` kemudian `npm start`.

## Amaran semasa memasang (aplikasi belum ditandatangani)
- Windows SmartScreen: tekan "More info" kemudian "Run anyway".
- Mac: klik kanan aplikasi, pilih Open. Jika mesej "rosak" muncul, jalankan `xattr -cr "/Applications/Kiki Belajar.app"` dalam Terminal.
- Untuk pengedaran kepada orang ramai tanpa amaran, aplikasi perlu ditandatangani (sijil Windows dan Apple Developer ID).

## Data
Akaun, kemajuan dan soalan import CSV disimpan dalam aplikasi pada komputer itu sahaja.
