# Sistem Analisis Markah — SMK Satak (K11)

## Publish melalui GitHub Pages
1. Ekstrak ZIP ini.
2. Muat naik index.html, .nojekyll dan README.md ke direktori utama repositori.
3. Di Settings > Pages, pilih Deploy from a branch, branch main dan / (root), kemudian Save.
4. Buka pautan GitHub Pages selepas penerbitan selesai.

Hanya Sheet ID, URL Apps Script, tiga URL CSV, nama sekolah dan lencana ditukar. Fungsi lain dan PDF landskap dikekalkan.

Sheet ID: 1_WIupOCNzkKhrPmH6BvP99HqPTxJHqTYsYxFYJZzGkE
CSV murid: gid 0
CSV pentaksiran/subjek: gid 564963003
CSV analisis/slip: gid 452162334

Pastikan Apps Script yang telah dideploy turut menggunakan Sheet ID baharu dan menyokong permintaan asal action saveMarks serta payload. Perubahan ID dalam HTML tidak mengubah kod pelayan Apps Script.

Semakan kod dan sintaks dibuat. Sambungan CSV dan penyimpanan Apps Script belum diuji secara langsung. Tiada data percubaan dihantar.
