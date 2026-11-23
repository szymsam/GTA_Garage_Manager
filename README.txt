GTA GARAGE MANAGER — wersja 0.1

URUCHOMIENIE:
1. Rozpakuj archiwum.
2. Otwórz terminal w folderze z plikiem index.html.
3. Uruchom: python3 -m http.server 8000
4. Otwórz w przeglądarce: http://localhost:8000
5. Dodaj garaż, a następnie pojazdy.

DANE:
- IndexedDB w przeglądarce na tym urządzeniu.
- Kliknij Eksport, by pobrać kopię JSON wraz ze zdjęciami.
- Import ZASTĘPUJE bieżącą kolekcję. Zrób eksport przed importem.
- Nie czyść danych witryny / profilu przeglądarki bez kopii zapasowej.

OBECNE FUNKCJE:
- Dodawanie, edycja i usuwanie garaży
- Dodawanie, edycja i usuwanie samochodów i motocykli
- Limit miejsc, przenoszenie pojazdów między garażami
- Wyszukiwanie, sortowanie, filtrowanie
- Własne zdjęcia (kompresowane przy dodawaniu)
- Mały przykładowy katalog modeli z autouzupełnianiem (bez zdjęć katalogowych)
- Eksport i import pełnej kolekcji

OGRANICZENIA:
- Nie ma synchronizacji między urządzeniami.
- Nie ma jeszcze kompletnej bazy modeli i zdjęć GTA Online.
- Zdjęcia dodaje użytkownik; domyślnie widoczny jest symbol pojazdu.
- To prototyp: importuj wyłącznie zaufane pliki kopii zapasowych.
