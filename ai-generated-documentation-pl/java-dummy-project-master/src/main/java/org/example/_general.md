![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---
 ### Dokumentacja ogólna dla pakietu example
Opis powinien zawierać co najmniej 500 znaków. Dokumentacja została wygenerowana na podstawie plików Markdown. Zebraj wszystkie opisy z tych plików.

Pakiet `example` zawiera dwie klasy Java, `Client` i `Service`, które prezentują funkcje podstawowe i zaawansowane. Klasa `Client` przyjmuje obiekt `Service` jako argument konstruktora i oferuje metodę nazwaną `greeting(String name)`. Klasa `Service` zawiera metody do sprawdzenia, czy liczba całkowita jest parzysta (`isEven(int input)`) oraz drukujące znaki trzech liczb (`highComplexityMethod(int a, int b, int c)`).

## Spis Treści
- [Client.md](Client.md)
  - **Opis:** Ten plik zawiera szczegółową dokumentację dla klasy `Client`, w tym konstruktora i metody `greeting`. Wyjaśnia, jak utworzyć nowy obiekt klasy `Client` z obiektem `Service` i wygenerować wiadomość powitania na podstawie długości nazwy wejściowej.
- [Service.md](Service.md)
  - **Opis:** Ten dokument zawiera szczegółową dokumentację dla klasy `Service`, w tym metod `isEven(int input)` i `highComplexityMethod(int a, int b, int c)`. Wyjaśnia, jak sprawdzić, czy liczba całkowita jest parzysta oraz drukuje znaki trzech liczb za pomocą metod dostępnych.

## Client
### Konstruktor
- **Opis:** Tworzy nowy obiekt klasy `Client` z podanym obiektem `Service`.
- **Parametry:**
  - `service` (`Service`): Obiekt klasy `Service`, który będzie używany przez obiekt `Client`.
- **Wartości powrotne:** Brak.
- **Logika ważna:** Utworzenie nowego obiektu klasy `Client` z podanym obiektem `Service`.

### greeting(String name)
- **Opis:** Wygeneruje wiadomość powitania na podstawie długości nazwy wejściowej.
- **Parametry:**
  - `name` (`String`): Nazwa, dla której ma zostać wygenerowana wiadomość powitania.
- **Wartości powrotne:** `String`: Wiadomość powitania.
- **Logika ważna:** Sprawdzenie długości nazwy wejściowej i generowanie odpowiedniej wiadomości powitania.