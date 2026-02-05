![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---
 ### Zrobić to rzeczywistością.

---
1. Przegląd
Kod Java definiuje klasę `Client`, która przyjmuje jako argument konstruktora obiekt `Service` i oferuje metodę nazwaną `greeting(String name)`. Metoda `greeting` sprawdza, czy dana ciąg `name` nie jest pusty lub pusta, a następnie wyznacza, czy długość ciągu `name` jest parzysta za pomocą metody `isEven()` obiektu `Service`. Jeśli długość ciągu `name` jest parzysta, zwraca witaminkę w wielkich literach; w przeciwnym razie zwraca witaminkę bez zmian.

2. Nazwa pakietu/modułu
Kod należy do pakietu `org.example`.

3. Szczegółowe Dokumentacja
- Klasa/plik: Client.java

   - Konstruktor (Client)
     - Opis: Inicjuje nowy obiekt klasy `Client` z podanym obiektem `Service`.
     - Parametry:
       - service (Service): Obiekt `Service`, który będzie używany przez klienta.
     - Wartości powrotne: Brak.
     - Logika ważna: Przypisuje podaną wartość obiektu `Service` do prywatnej zmiennej instancyjnej `service`.

   - Metoda (greeting)
     - Opis: Generuje witaminkę dla podanej nazwy i zwraca ją w formacie małych lub wielkich liter, w zależności od tego, czy długość nazwy jest parzysta.
     - Parametry:
       - name (String): Nazwa do generowania witaminki.
     - Wartości powrotne: Ciąg `String` zawierający wygenerowaną witaminkę.
     - Logika ważna:
       - Sprawdza, czy podany ciąg jest pusty lub pusty i rzuca wyjątek, jeśli tak jest.
       - Wyznacza, czy długość nazwy jest parzysta za pomocą metody `isEven()` obiektu `Service`.
       - Jeśli długość nazwy jest parzysta, konwertuje witaminkę na wielkie litery; w przeciwnym razie pozostawia ją bez zmian.

4. Pseudo Kod
```
// Klasa: Client

// Metoda: Client(Service service)
  1. Inicjuje obiekt klasy Client z podanym service
  2. Przypisuje service do prywatnej zmiennej

// Metoda: greeting(String name)
  1. Inicjuje zmienne
  2. Sprawdza, czy name jest puste lub puste
    - Jeśli tak, rzuca wyjątek
  3. Wyznacza, czy długość nazwy jest parzysta za pomocą Service's isEven method
  4. Konwertuje witaminkę na wielkie litery, jeśli długość jest parzysta; w przeciwnym razie pozostawia ją bez zmian
  5. Zwraca wygenerowaną witaminkę
```