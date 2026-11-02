# Bluebird – terminal policyjny (makieta)

Makieta terminalu Bluebird: ekran blokady z godziną, ekran główny z aplikacjami (Legitymowanie, Sprawdź pojazd, Mandat, Notatki służbowe, Wpisane) i prosta baza osób zapisywana w przeglądarce.

## Jak opublikować na GitHub Pages

1. Wejdź na github.com i kliknij **New repository**. Nazwij je np. `bluebird`, ustaw **Public**, kliknij **Create repository**.
2. Kliknij **uploading an existing file** i wgraj pliki `index.html` oraz `README.md`. Kliknij **Commit changes**.
3. Wejdź w **Settings → Pages**.
4. W sekcji **Build and deployment** wybierz **Source: Deploy from a branch**, branch **main**, folder **/ (root)**, kliknij **Save**.
5. Po 1–2 minutach strona będzie pod adresem: `https://TWOJA-NAZWA.github.io/bluebird/`

## Uwagi

- Wszystko jest w jednym pliku `index.html` (zdjęcie telefonu jest w środku), więc nie potrzeba nic więcej.
- Dane z bazy zapisują się w przeglądarce (localStorage), osobno na każdym urządzeniu.
- To makieta. Nie łączy się z żadną prawdziwą bazą ani systemem policyjnym.
