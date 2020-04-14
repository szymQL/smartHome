# Doorime - z nami nie zapomnisz o otwartych drzwiach.

Doorime jest projektem studenckim, mającym na celu stworzenie inteligentego urządzenia.

Projekt został podzielony na mniejsze grupy w celach organizacyjnych.

### 1. Hardware
### 2. Server Side
### 3. Mobile



## Podstawowy flow aplikacji - czyli jak to w ogóle ma działać?

### Flow ze strony Aplikacji
Otwieramy aplikację → Zestawiamy tunel ssh → Logujemy się za pomocą loginu i hasła otrzymując przy tym token → Dodajemy token do requesta zapewniając bezpieczną komunikację

### Flow ze strony Urządzenia
Drzwi są otwarte → Użytkownik rozłącza się z domowym WiFi → Urządzenie stwierdza, że opuścił mieszkanie → ESP informuje o tym Raspberry → Raspberry łączy się z bazą danych postgresa na VM → Baza danych z API → API przez tunel ssh wysyła push notyfikację → Push notyfikacja przypomina użytkownikowi o otwartych drzwiach


# Postęp poszczególnych części

# Hardware
- [x] Połączenie między ESP a RASPBERRY
- [x] Połączenie między ESP a RASPBERRY 
- [x] Połączenie między ESP a RASPBERRY 
- [x] Połączenie między ESP a RASPBERRY 

# Server Side
- [x] Wybór protokołu komunikacyjnego 
- [x] Przygotowanie Virtual Machine i Raspberry PI 
- [x] Połączenie między Raspberry a ESP 
- [x] Opracowanie komunikacji pomiędzy androidem a bazą danych na VM - tunel ssh, uwierzytelnianie
- [x] Konfiguracyjny DockerFile
- [x] Uwierzytelnianie do bazy danych na maszynie wirtualnej
- [x] Implementacja tunelu na androidzie
- [x] Stworzenie RESTful API w oparciu o Flask'a
- [x] Połączenie API z bazą danych

# Mobile 
- [x] Połączenie między ESP a RASPBERRY 
- [x] Połączenie między ESP a RASPBERRY 
- [x] Połączenie między ESP a RASPBERRY 
- [x] Połączenie między ESP a RASPBERRY 
