# GTA Garage Manager v0.4

Prywatny katalog samochodów, motocykli i garaży GTA Online. Statyczna aplikacja PWA: bez backendu, logowania i synchronizacji.

## Publikacja na GitHub Pages

1. **Przed aktualizacją** otwórz obecną aplikację i wykonaj **Eksport** kolekcji.
2. W repozytorium GitHub podmień pliki w katalogu głównym na zawartość tego folderu: `index.html`, `styles.css`, `app.js`, `sw.js`, `manifest.webmanifest`, ikony oraz folder `assets`.
3. W **Settings → Pages** ustaw **Deploy from a branch → main → /(root)**, jeśli nie było wcześniej skonfigurowane.
4. Otwórz `https://TWOJ-LOGIN.github.io/gta-garage-manager/` i odśwież. Zainstalowana aplikacja PWA może wymagać zamknięcia i ponownego uruchomienia, aby pobrać aktualizację.
5. Jeżeli dane nie pojawiły się, użyj **⚙ → Import** i wskaż kopię zapasową.

**Ważne:** ta wersja zachowuje nazwę i wersję IndexedDB (`gta-garage-manager`, wersja 1) oraz obsługuje eksport JSON wersji 1 z poprzednich wersji. Dane są powiązane z adresem strony i profilem przeglądarki. Nie publikuj kopii zapasowych i prywatnych screenshotów w repozytorium.

## Funkcje

- Startowy widok kafelków garaży z opcjonalnym zdjęciem nieruchomości, licznikiem zajętości i trzema podglądami aut.
- Widok wybranego garażu, lista wszystkich pojazdów, ulubione, wyszukiwanie, filtry, statystyki.
- Liczniki samochodów, motocykli i garaży w nagłówku.
- Dodawanie i edycja garaży, pojazdów i screenshotów, przenoszenie między garażami, opcjonalny numer miejsca.
- Eksport/import kolekcji z własnymi zdjęciami.
- Instalacja jako PWA i obsługa offline po pierwszym pełnym załadowaniu przez HTTPS.

Zdjęcia garaży i samochodów dodaje użytkownik; aplikacja nie zawiera cudzych screenshotów ani katalogowych zdjęć pojazdów. Panorama nagłówka to lokalny plik SVG. Katalog modeli jest na razie przykładowy, niepełny.
