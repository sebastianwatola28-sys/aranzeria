# Aranżeria — strona wizytówka

Dekoracje · Wypożyczalnia · Aranżacje — wynajem i produkcja ścianek okazjonalnych.

Cała strona to jeden plik `index.html`: bez frameworków, bez builda, bez zależności.
Wystarczy otworzyć w przeglądarce albo wrzucić na dowolny hosting.

## Pliki do uzupełnienia

Strona działa od razu, ale dwa elementy rysuje tymczasowo wektorowo. Gdy wrzucisz
prawdziwe pliki pod te ścieżki, podmienią się automatycznie:

| Ścieżka | Co to jest |
|---|---|
| `logo.png` | okrągłe logo Aranżerii (nagłówek, kurtyna, stopka) — najlepiej kwadratowy PNG, min. 512 × 512 px |
| `zdjecia/scianka-18-urodziny.jpg` | zdjęcie ścianki na 18. urodziny w sekcji Realizacje — ok. 1600 px szerokości |

Jeśli pliku nie ma, strona pokazuje rysunek zastępczy — nic się nie psuje.

## Co gdzie zmienić

Wszystko siedzi w `index.html`:

- **Cennik konfiguratora** — obiekty `TYPY`, `ROZMIARY` i `DODATKI` na początku sekcji `<script>`.
- **Dane kontaktowe** — sekcja `#kontakt` oraz przycisk telefonu w nagłówku.
- **Kolory marki** — zmienne CSS `--brass` / `--brass-2` w bloku `:root` (miedziany róż z logo).
- **Realizacje** — sekcja `#realizacje`.

## Do uzupełnienia w treści

- miejscowość bazy (sekcja Kontakt),
- link do profilu na Instagramie,
- weryfikacja cen w konfiguratorze — wartości są poglądowe.

## Publikacja na GitHub Pages

Settings → Pages → Source: `Deploy from a branch` → gałąź `main`, katalog `/ (root)`.
