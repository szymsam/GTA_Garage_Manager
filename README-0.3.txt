GTA GARAGE MANAGER 0.3 — GALERIA WŁASNYCH AUT

NOWOŚCI
- Duże, spójne pola zdjęć 16:9 bez przycinania i bez zmiany tła.
- Kliknięcie zdjęcia otwiera pełnoekranowy podgląd z opcją edycji.
- Filtr „ze zdjęciem / bez zdjęcia”.
- Garaże mają podgląd do 3 zdjęć i pasek zajętości.
- W edycji auta można usunąć albo zastąpić zdjęcie.
- Zdjęcia są skalowane do maksymalnie 1600 x 1200 px i zapisywane w WebP (gdy przeglądarka wspiera).
- Zachowano lokalną bazę IndexedDB i eksport/import JSON ze zdjęciami.

URUCHOMIENIE
Aplikacja PWA wymaga jednorazowego udostępnienia przez HTTPS (np. GitHub Pages),
a następnie zainstalowania z Chrome lub Edge. Później uruchamia się z ikony.
Na komputerze do lokalnych testów można też użyć dowolnego prostego serwera HTTP
(np. python -m http.server 8000), ale NIE jest to wymagane po instalacji PWA.

WAŻNE
Dane są lokalne dla konkretnej przeglądarki i adresu aplikacji. Nie ma synchronizacji.
Eksportuj kopie zapasowe regularnie, szczególnie przed czyszczeniem danych przeglądarki.
Przy aktualizacji pod tym samym adresem HTTPS baza pozostaje ta sama.
Przy zmianie adresu należy użyć eksportu i importu.
