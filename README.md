# My Planner DI V1 — PWA

## Fail
- `index.html`: planner dan panduan pemasangan.
- `manifest.webmanifest`: metadata Progressive Web App.
- `sw.js`: service worker dan cache app shell asas.
- `icons/`: ikon 192px, 512px dan maskable.
- `README.md`: panduan ini.

## Push ke GitHub
1. Ekstrak ZIP.
2. Muat naik fail dan folder di dalam ZIP ke root repo `ellcloudoffice-ui/my-planner`. Pastikan `index.html` berada terus di root.
3. Commit dan push ke branch `main`.
4. Tunggu deployment Cloudflare Pages berjaya.
5. Buka domain HTTPS dan uji pemasangan pada iOS dan Android.

## Pemasangan
- iPhone/iPad: buka laman HTTPS dalam Safari → Share → Add to Home Screen.
- Android: buka laman HTTPS dalam Chrome → menu ⋮ → Install app atau Add to Home screen. Prompt bergantung pada sokongan browser.
- Service worker dan pemasangan PWA memerlukan HTTPS; `file://` tidak mencukupi.

## Had prototaip
Planner menyimpan rekod dalam `localStorage` setempat, bukan pangkalan data awan. Rekod tidak disegerakkan antara peranti. Service worker cache app shell asas sahaja. Uji pada Safari iOS dan Chrome Android sebelum penggunaan umum.

## Auto-suggest Theme dan Learning Outcome
Pilih Theme, kemudian pilih kemahiran (Listening, Speaking, Reading, Writing atau Language Arts/Vocabulary) untuk mengisi draf LO secara automatik. LO ialah cadangan umum yang boleh diedit, bukan salinan rasmi DSKP. Semak dengan DSKP dan RPT semasa sebelum menggunakannya. Untuk tema/topik lain, pilih Custom Theme dan edit medan yang berkaitan.
