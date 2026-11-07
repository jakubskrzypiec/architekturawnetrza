# Architektura & Wnętrza — koncepcja strony głównej

Wstępna wersja strony typu one-page dla pracowni Moniki Kowalewskiej, przygotowana jako samodzielny plik `index.html` (HTML, CSS, JavaScript).

## Układ
1. Hero z fotografią wnętrza, animowanymi cieniami i dwoma przyciskami.
2. O mnie — opis pracowni i miejsce na portret klientki.
3. Szeroki przerywnik z cytatem i animacją światła.
4. Realizacje — bezszwowa karuzela 10 pustych kafelków ze wstępnymi podpisami, przewijanie automatyczne, ręczne i przeciąganiem.
5. Oferta — trzy karty usług.
6. Proces — cztery etapy z dużym przerywnikiem fotograficznym.
7. Trzy autentyczne krótkie opinie z poprzedniej strony.
8. Formularz kontaktowy, kontakt bezpośredni, miejsca na profile społecznościowe, stopka.

## Styl
- Montserrat do nagłówków, geometryczny styl zbliżony do referencji „AZURITE”.
- Manrope do tekstów.
- Wszystkie napisy tylko czarne lub białe, bez kursywy.
- Kolory tła inspirowane: trawertynem, ciemnym dębem, weneckim tynkiem, szczotkowanym mosiądzem.
- Pełna responsywność, `prefers-reduced-motion`, mobilne menu.

## Przed pokazaniem strony jako finalnej
- **Logo:** w headerze/footerze jest tymczasowy podpis typograficzny A&W. Podmienić na oryginalne logo z pliku źródłowego klientki; nie odrysowywać go z domysłu.
- **Portret:** w sekcji „O mnie” jest świadomy placeholder.
- **Realizacje:** 10 pustych kafelków należy zastąpić prawdziwymi zdjęciami projektów i konkretnymi tytułami. Aktualne nazwy są przykładowe i nie przypisują klientce fikcyjnych projektów.
- **Zdjęcia klimatyczne:** hero, cytat i sekcja procesu korzystają na razie z poglądowych zdjęć z Unsplash; podmienić po zatwierdzeniu.
- **Formularz:** obecnie po wypełnieniu otwiera klientowi program pocztowy (`mailto:`), nie korzysta z backendu. Przed uruchomieniem finalnej domeny podpiąć wybraną usługę wysyłania formularzy i przetestować.
- **Instagram i Facebook:** podane jako etykiety bez linków. Wstawić potwierdzone adresy profili po otrzymaniu ich od klientki.
- **Opinie:** pochodzą z publicznej strony dotychczasowej pracowni. Przed finalnym wydaniem warto potwierdzić wybrane fragmenty.
- **SEO:** koncepcyjny podgląd ma `noindex,nofollow`. Po zatwierdzeniu docelowej domeny należy usunąć to oznaczenie i przygotować indeksację.
- **Telefon/adres/e-mail:** przepisane z dotychczasowej strony pracowni, do potwierdzenia przed finalną publikacją.

## Podgląd przez GitHub Pages
W GitHub przejdź do **Settings → Pages → Build and deployment**, ustaw **Deploy from a branch**, `main` oraz `/(root)`. Adres po aktywacji:
https://jakubskrzypiec.github.io/architekturawnetrza/

Projekt nie wymaga kompilacji ani instalowania zależności.
