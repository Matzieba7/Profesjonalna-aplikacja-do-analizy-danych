# Profesjonalna aplikacja do analizy danych  
## Analiza zanieczyszczeń powietrza
### Cele
#### Wizja projektu:  
Aplikacja będzie prostym oprogramowaniem na komputery osobiste z systemem Windows. Będzie umożliwiać analizę danych zanieczyszczeń powietrza.  
  
System umożliwiać będzie m.in. import danych z plików CSV/XLS w konkretnym formacie, ręczne dodawanie rekordów danych, edycję oraz usuwanie konkretnych rekordów danych, tworzenie raportów oraz diagramów na podstawie wysortowanych i przefiltrowanych danych.

Aktualnie istnieje kilka rozwiązań do analizy danych, jednakże większość z nich jest webowa, a nie desktopowa i raczej zawierają dane z wybranych obszarów i nie mają możliwości dodawania danych ręcznie.

Użytkownicy na podstawie otrzymanego poziomu dostępu do aplikacji, będą mogli (po zalogowaniu) uzyskać dostęp do poszczególnych funkcji systemu(np. dostęp typu admin, user). 

Celem biznesowym badania danych tego typu jest przyczynienie się do wyekstrahowania największych źródeł zanieczyszczeń w danym okresie czasu przez firmę czy dany zakres gospodarki.  
#### Zakres projektu:  
Tworzenie bazy danych:  
- Firebird  
- MSSQL  
- XML

Zdefiniowanie formatów grafów i raportów:  
- tabelaryczne    
- wykresy słupkowe i kołowe  
- opisowe  
- łączone

Sekcja graficzna aplikacji:
- Wyświetlanie zaimportowancych i dodanych danych    
- Mechanizm filtrowania i sortowania danych

#### Fazy projektu:
1. Stworzenie dokumentacji projektu  
2. Utworzenie nowego projektu w Delphi 10.3  
3. Zainicjowanie repozytorium na platformie GitHub  
4. Obróbka głównych danych  
5. Przygotowanie prototypu bazy danych  
6. Stworzenie wstępnej części graficznej aplikacji  
7. Utworzenie mechanizmu połączenia aplikacji z bazą danych  
8. Zaprojektowanie logiki importu danych z plików CSV/XLS do bazy danych poprzez aplikację  
9. Stworzenie procedur do pobierania, dodawania, updatu i usuwania danych  
10. Wstępne testy dotychczasowych funkcjonalności  
11. Utworzenie okna logowania użytkownika  
12. Dodanie tablic i procedur związanych z logowaniem użytkownika w bazie danych
13. Określenie mechanizmu tworzenia raportów  
14. Druga część testów funkcjonalności aplikacji na głównych danych z pliku CSV  
15. Kolejne etapy pracy nad aplikacją zostaną określone w trakcie późniejszych prac
  
### Wymagania Funkcjonalne     
1. Logika użytkowników - domyślne konto admina powinno umożliwiać zakładanie kont zwykłych użytkowników.  
2. Aktualizacja danych - aplikacja ma możliwość edycji istniejących danych oraz możliwość dodawania nowych.  
3. Generowanie raportów - ta funkcjonalność ma zapewnić użytkownikowi możliwość generowania raportów w konkretnych formatach.  
4. Wizualizacja danych - spełnienie tej funkcjonalności zapewnia wizualizacje danych za pomocą tabeli oraz grafów i wykresów.  
5. Analiza danych -  aplikacja powinna umożliwiać analizę danych biorącą pod uwagę wiele czynników

### Wymagania Niefunkcjonalne 
1. Skalowalność - system musi mieć możliwość skalowania w górę lub w dół w zależności od potrzeb.
2. Użyteczność - system musi być łatwy w obsłudze i intuicyjny.
3. Wydajność – aplikacja zapewnia wykonywanie swoich funkcji bez dużych opóźnień i przestojów niezależnie od mocy obliczeniowej komputera użytkownika
4. Kolorystyka aplikacji -  biały, szary, zielony.

### Diagram klas
![image](https://github.com/Matzieba7/Profesjonalna-aplikacja-do-analizy-danych/assets/80106851/a836b426-0ace-4587-9b58-08bd99e90dce)  
  
### Diagram obiektów
![image](https://github.com/Matzieba7/Profesjonalna-aplikacja-do-analizy-danych/assets/80106851/da3ccaaa-3d20-45a4-a79f-7095ab50dbd3)
  
### Wykorzystane technologie
1. IBExpert - narzędzie do tworzenia oraz zarządzania bazami danych oraz wykonywania zapytań SQL.  
2. Embarcadero Delphi 10.3 Rio - narzędzie do tworzenia oprogramowania.
3. Komponenty FastReport, DevExpress - komponenty dedykowane do narzędzia Delphi umożliwiające tworzenie raportów oraz grafów na podstawie zapytań do bazy danych.
  
### Autor: Zięba Mateusz nr. albumu: 13388
