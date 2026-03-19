# Płatności za zajęcia – PWA pod GitHub Pages

Prosta aplikacja webowa do wpisywania płatności za zajęcia.

## Co potrafi
- dodawanie płatności: imię i nazwisko, grupa, kwota, data
- zakładki dla grup
- zapis danych lokalnie w przeglądarce
- eksport CSV dla bieżącej grupy
- eksport wszystkich grup do osobnych plików CSV
- instalacja na iPhonie przez `Udostępnij -> Do ekranu początkowego`

## Pliki
- `index.html` – aplikacja
- `manifest.webmanifest` – konfiguracja PWA
- `sw.js` – service worker
- `icons/` – ikony

## Jak wrzucić na GitHub Pages
1. Utwórz nowe repozytorium na GitHubie.
2. Wgraj wszystkie pliki z tego folderu do repo.
3. Wejdź w `Settings -> Pages`.
4. W sekcji `Build and deployment` ustaw:
   - `Source`: `Deploy from a branch`
   - `Branch`: `main` i folder `/root`
5. Zapisz.
6. Po chwili aplikacja będzie dostępna pod adresem GitHub Pages.

## iPhone
Najlepiej działa po otwarciu linku w Safari i dodaniu do ekranu początkowego.

## Uwaga
CSV nie ma zakładek jak Excel, więc każda grupa eksportuje się do osobnego pliku CSV.
