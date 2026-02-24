![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---

Oto przetłumaczone dokumentacja zgodnie z podanymi wytycznymi:

![Logo Capgemini](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Uczyń to rzeczywistym.

---

## Przegląd
Dostarczony `pom.xml` jest skryptem budowania Maven dla projektu Java o nazwie "dummy-java-project" z grupy "org.example". Skrypt konfiguruje zależności projektu, ustawienia kompilatora i framework testowy. Wykorzystuje JUnit 5 jako framework testowy wraz z bibliotekami Mockito i AssertJ.

## Narzędzie budowania
Maven (Apache Maven)

## Nazwa skryptu/pliku
`pom.xml` (Plik Modelu Projektu)

## Szczegółowa dokumentacja

### Zadanie 1: Konfiguracja projektu
- **Opis:** Definiuje podstawowe informacje o projekcie, takie jak identyfikator grupy, identyfikator artefaktu i wersję.
- **Parametry:** Brak
- **Ważna logika:** Ustawia wersję modelu projektu na 4.0.0, co określa strukturę i składnię pliku POM.

### Zadanie 2: Konfiguracja właściwości
- **Opis:** Konfiguruje różne właściwości dla procesu budowania, takie jak wersje źródłowe i docelowe kompilatora Java oraz kodowanie UTF-8 projektu.
- **Parametry:**
  - `maven.compiler.source`: 17 (Java 17)
  - `maven.compiler.target`: 17 (Java 17)
  - `project.build.sourceEncoding`: UTF-8
- **Ważna logika:** Zapewnia, że skompilowany kod jest zgodny z Java 17 i używa kodowania UTF-8.

### Zadanie 3: Zarządzanie zależnościami
- **Opis:** Wymienia zależności wymagane przez projekt, w tym biblioteki Mockito, AssertJ i JUnit 5, wszystkie w zakresie testowym.
- **Parametry:**
  - `mockito-core`: 5.6.0
  - `assertj-core`: 3.24.2
  - `junit-jupiter-engine`: 5.10.0
  - `junit-jupiter-api`: 5.10.0
  - `mockito-junit-jupiter`: 5.6.0
- **Ważna logika:** Zarządza wersjami frameworka testowego i powiązanych bibliotek, aby zapewnić zgodność i prawidłowe działanie.

### Zadanie 4: Konfiguracja budowania
- **Opis:** Konfiguruje Maven Surefire Plugin do testowania projektu.
- **Parametry:**
  - `maven-surefire-plugin`: 3.0.0
- **Ważna logika:** Zapewnia, że testy projektu są wykonywane przy użyciu pluginu Surefire.

## Wersja języka
Java 17 (określona przez `maven.compiler.source` i `maven.compiler.target`)

## Wersje zależności
- Mockito Core: 5.6.0
- AssertJ Core: 3.24.2
- JUnit Jupiter Engine: 5.10.0
- JUnit Jupiter API: 5.10.0
- Mockito JUnit Jupiter: 5.6.0

## Pseudokod
```plaintext
/* Skrypt budowania Maven dla "dummy-java-project" */

1. Zdefiniuj strukturę projektu i wersję:
   - groupId: org.example
   - artifactId: dummy-java-project
   - version: 1.0-SNAPSHOT
   - modelVersion: 4.0.0

2. Skonfiguruj ustawienia kompilatora:
   - source: Java 17
   - target: Java 17
   - encoding: UTF-8

3. Dodaj zależności do testowania:
   - Mockito Core (5.6.0)
   - AssertJ Core (3.24.2)
   - JUnit Jupiter Engine (5.10.0)
   - JUnit Jupiter API (5.10.0)
   - Mockito JUnit Jupiter (5.6.0)

4. Skonfiguruj testowanie z Maven Surefire Plugin:
   - plugin: maven-surefire-plugin (3.0.0)
```

## Odpowiedniki zależności i wtyczek
- Maven Surefire Plugin: W Gradle użyj Test Implementation plugin; w npm użyj jest lub Mocha
- JUnit 5: Dla Gradle użyj org.junit.jupiter:junit-jupiter-engine; dla npm użyj jest lub Mocha z bibliotekami assert