# Statusnik: pliki aktualizacji

Repozytorium służy wyłącznie do publikacji plików aktualizacji przez GitHub Pages:

- `manifest.json`: najnowsze wydanie,
- `statusnik-aktualizacja-X.Y.Z.zip`: paczka wydania.

Każdy plik paczki ma w manifeście SHA-256 i podpis Ed25519 klucza producenta. Serwer Statusnik sprawdza podpis przed rozpakowaniem, więc plik zmieniony poza producentem zostanie odrzucony.

Kodu programu tu nie ma.
