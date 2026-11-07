# Architektura & Wnętrza — koncepcja v2

Wstępny one-page dla pracowni Moniki Kowalewskiej. Projekt w `index.html`, bez frameworków i bez podstron.

## Potwierdzony kierunek

- Paleta: **Smoky Black** `#11120D`, **Olive Drab** `#565449`, **Bone** `#D8CFBC`, **Floral White** `#FFFBF4`.
- Napisy wyłącznie czarne lub białe, bez kursywy.
- Duży hero **bez nagłówka i opisów**, z ruchomym światłem/cieniami oraz dwoma przyciskami „Zobacz realizacje” i „Skontaktuj się”.
- „O mnie”: jeden duży ozdobny nagłówek (Montserrat / geometryczny styl AZURITE), średniej długości tekst oraz całkowicie białe pole na zdjęcie klientki.
- Pełnoszeroki fotograficzny przerywnik z cytatem i animacją światła.
- Karuzela realizacji wzorowana układem na przesłanym screenie Moniki Serbisty: ciemne tło, **10 pustych białych kafli**, podpisy w dolnym obszarze, w pełni płynna pętla, pauza po najechaniu, przeciąganie, **bez strzałek**.
- Oferta przebudowana na materiałową fotografię i prostą numerowaną listę usług — bez kafelków.
- Sekcja procesu: wizualny przerywnik + cztery kroki.
- Opinie: trzy karty na spokojnym, czystym tle.
- Kontakt: formularz, następnie odrębna sekcja „Bądź na bieżąco” z dużą fotografią, Instagramem i Facebookiem.

## Grafiki koncepcyjne

Kod używa obrazów poglądowych jako **awaryjnych tłach**. Po dodaniu tych plików do katalogu `assets/` loader automatycznie je włączy:

```
assets/hero.webp
assets/quote.webp
assets/process.webp
assets/offer.webp
assets/social.webp
```

Wygenerowane grafiki dostarczono osobno w archiwum `architekturawnetrza_grafiki_koncepcyjne.zip`, zawierającym te 5 plików. Fotografie są **koncepcyjne, a nie realizacjami klientki**.

## Do uzupełnienia

- Oryginalny plik logo zamiast podpisu A&W.
- Zdjęcie Moniki Kowalewskiej.
- Fotografie 10 realizacji i rzeczywiste tytuły projektów.
- Potwierdzone linki do Instagrama i Facebooka.
- Docelowa obsługa wysyłania formularza: obecnie jest `mailto:` otwierające program pocztowy.
- Przed produkcją sprawdzić dane kontaktowe, treści i opinie oraz usunąć `noindex,nofollow`.

## Podgląd

GitHub Pages: https://jakubskrzypiec.github.io/architekturawnetrza/

Projekt responsywny, z obsługą `prefers-reduced-motion`.
