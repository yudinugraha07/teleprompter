# CLAUDE.md

Teleprompter berbasis browser dalam satu file `index.html`, tanpa build dan tanpa dependency. Fitur dan cara pakai ada di `README.md`.

- Kamera butuh `localhost` atau HTTPS; uji dengan server lokal, misalnya `python3 -m http.server`.
- Token desain disalin inline di awal `<style>` dari Picaloid Web UI Kit (`picaloid/brand-identity/brand/web/tokens.css`); jaga tetap sinkron kalau brand kit berubah.
- Rekaman A-roll dari teleprompter ini (`teleprompter-*.mov`) dipakai sebagai input vidkit di `technology/picaloid-video-pipeline/`.
- Repo git dengan remote pribadi `yudinugraha07/teleprompter`; commit dan push hanya kalau diminta.
