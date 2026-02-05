![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---

Oto przetłumaczone dokumentacja i pseudokod w języku polskim, zgodnie z podanymi wytycznymi:

![Logo Capgemini](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Uczyń to rzeczywistym.

---

1. Przegląd
Podany kod Java definiuje klasę `Client`, która współdziała z obiektem `Service` w celu generowania spersonalizowanych powitań na podstawie długości wprowadzonego imienia. Metoda `greeting` sprawdza, czy długość imienia jest parzysta, i zwraca powitanie wielkimi literami, jeśli tak, w przeciwnym razie w oryginalnej formie.

2. Nazwa pakietu/modułu
```java
package org.example;
```
Kod należy do pakietu `org.example`.

3. Nazwa klasy/pliku
```java
public class Client {
    // ...
}
```
Klasa nazywa się `Client` i jest zdefiniowana w pliku `Client.java`.

4. Szczegółowa dokumentacja

   - Funkcja/metoda 1: Konstruktor
     - Opis: Inicjuje nową instancję klasy `Client` z podanym obiektem `Service`.
     - Parametry: 
       - `service` (Service): Obiekt usługi do wykorzystania w generowaniu powitań.
     - Wartości zwracane: Brak
     - Ważna logika: Przypisuje podany obiekt `Service` do pola `service`.

   - Funkcja/metoda 2: greeting(String name)
     - Opis: Generuje spersonalizowane powitanie na podstawie długości wprowadzonego imienia. Jeśli długość jest parzysta, powitanie jest zwracane wielkimi literami; w przeciwnym razie w oryginalnej formie.
     - Parametry: 
       - `name` (String): Imię, dla którego ma zostać wygenerowane powitanie.
     - Wartości zwracane: 
       - String: Spersonalizowane powitanie.
     - Ważna logika:
       1. Waliduje, czy wprowadzone `imię` jest null lub puste.
       2. Sprawdza, czy długość imienia jest parzysta za pomocą metody `isEven` obiektu `Service`.
       3. Formatuje ciąg powitania z wprowadzonym imieniem.
       4. Zwraca powitanie wielkimi literami, jeśli długość imienia jest parzysta, w przeciwnym razie w oryginalnej formie.

5. Pseudokod
```java
// Klasa: Client

// Metoda: Client(Service service)
  1. Zainicjuj pole 'service' podanym obiektem Service.

// Metoda: greeting(String name)
  1. Sprawdź, czy wprowadzone 'imię' jest null lub puste.
     - Jeśli true, rzuć wyjątek IllegalArgumentException.
  2. Użyj obiektu 'service', aby sprawdzić, czy długość 'imienia' jest parzysta.
  3. Sformatuj ciąg powitania z wprowadzonym 'imieniem'.
  4. Jeśli długość 'imienia' jest parzysta:
      - Przekonwertuj ciąg powitania na wielkie litery.
  5. Zwróć sformatowany ciąg powitania.
```