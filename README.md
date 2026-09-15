# Aranżeria — strona wizytówka

Dekoracje · Wypożyczalnia · Aranżacje — wynajem i produkcja ścianek okazjonalnych.

Cała strona to jeden plik `index.html`: bez frameworków, bez builda, bez zależności.
Wystarczy otworzyć w przeglądarce albo wrzucić na dowolny hosting.

## Pliki do uzupełnienia

Strona działa od razu, ale dwa elementy rysuje tymczasowo wektorowo. Gdy wrzucisz
prawdziwe pliki pod te ścieżki, podmienią się automatycznie:

| Ścieżka | Co to jest |
|---|---|
| `logo.jpg` | okrągłe logo Aranżerii (nagłówek, kurtyna, stopka) — kwadrat, min. 512 × 512 px |
| `monika.jpg` | zdjęcie Moniki w sekcji O mnie — kadr pionowy 4:5, ok. 800 px szerokości |
| `scianka.jpg` | zdjęcie ścianki na 18. urodziny (sekcja Realizacje) — ok. 1600 px szerokości |

Jeśli pliku nie ma, strona pokazuje rysunek zastępczy — nic się nie psuje.

## Co gdzie zmienić

Wszystko siedzi w `index.html`:

- **Cennik konfiguratora** — obiekty `TYPY`, `ROZMIARY` i `DODATKI` na początku sekcji `<script>`.
- **Dane kontaktowe** — sekcja `#kontakt` oraz przycisk telefonu w nagłówku.
- **Kolory marki** — zmienne CSS `--brass` / `--brass-2` w bloku `:root` (miedziany róż z logo).
- **Realizacje** — sekcja `#realizacje`.

## Do uzupełnienia w treści

- link do profilu na Instagramie,
- weryfikacja cen w konfiguratorze — wartości są poglądowe.

## Publikacja na GitHub Pages

Settings → Pages → Source: `Deploy from a branch` → gałąź `main`, katalog `/ (root)`.
