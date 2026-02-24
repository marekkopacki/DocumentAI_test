![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---

Oto przetłumaczone dokumentacja zgodnie z podanymi wytycznymi:

![Logo Capgemini](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Uczyń to rzeczywistym.

---

1. Przegląd
Podany kod Java definiuje klasę `Client`, która współdziała z obiektem `Service` w celu generowania spersonalizowanych powitań na podstawie długości wprowadzonego imienia. Metoda `greeting` sprawdza, czy imię nie jest null ani puste, a następnie określa, czy długość imienia jest parzysta czy nieparzysta. Jeśli długość jest parzysta, zwraca powitanie wielkimi literami; w przeciwnym razie zwraca powitanie w oryginalnej formie.

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
### Funkcja/metoda 1: Konstruktor
- Opis: Inicjuje nowe wystąpienie klasy `Client` z referencją do obiektu `Service`.
- Parametry:
  - `service` (Service): Obiekt usługi, który będzie używany do określenia, czy długość imienia jest parzysta.
- Wartości zwracane: Brak
- Ważna logika: Konstruktor przypisuje podany obiekt `Service` do pola klasy `service`.

### Funkcja/metoda 2: greeting
- Opis: Generuje spersonalizowane powitanie na podstawie wprowadzonego imienia i długości imienia.
- Parametry:
  - `name` (String): Imię używane w powitaniu.
- Wartości zwracane:
  - String: Spersonalizowane powitanie, albo wielkimi literami, albo w oryginalnej formie w zależności od długości imienia.
- Ważna logika:
  1. Sprawdź, czy wprowadzone `imię` jest null lub puste i rzuć wyjątek `IllegalArgumentException`, jeśli tak.
  2. Użyj obiektu `Service`, aby sprawdzić, czy długość imienia jest parzysta.
  3. Sformatuj ciąg powitania z wprowadzonym imieniem.
  4. Zwróć powitanie wielkimi literami, jeśli długość jest parzysta; w przeciwnym razie zwróć powitanie w oryginalnej formie.

5. Pseudokod
```java
// Klasa: Client

// Metoda: Client(Service service)
  1. Zainicjuj pole 'service' klasy, przypisując podany obiekt Service.

// Metoda: greeting(String name)
  1. Sprawdź, czy wejściowe 'imię' jest null lub puste
    - Jeśli true, rzuć wyjątek IllegalArgumentException z komunikatem "'name' must not be null or empty"
  2. Użyj usługi, aby sprawdzić, czy długość imienia jest parzysta
  3. Sformatuj ciąg powitania z wprowadzonym imieniem
  4. Jeśli długość jest parzysta, przekonwertuj powitanie na wielkie litery
  5. Zwróć sformatowane powitanie (albo wielkimi literami, albo w oryginalnej formie)
```