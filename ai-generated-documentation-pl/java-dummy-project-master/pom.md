![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---

### Dokumentacja dla pliku `pom.xml` projektu Java "dummy-java-project"

#### 1. Przegląd
Podany `pom.xml` to skrypt budowania Maven dla projektu Java o nazwie "dummy-java-project" z grupy "org.example". Skrypt konfiguruje zależności projektu, ustawienia kompilatora oraz frameworki testowe. Wykorzystuje wtyczki Maven do zarządzania procesem budowania.

#### 2. Narzędzie Budujące
Maven

#### 3. Nazwa Skryptu/Pliku
`pom.xml` (Plik Modelu Projektu)

#### 4. Dokumentacja Szczegółowa

### Sekcja 1: Konfiguracja Projektu
- **Opis:** Definiuje podstawowe informacje o projekcie, takie jak identyfikator grupy, identyfikator artefaktu i wersję.
- **Parametry:**
  - `groupId` (String): Unikalny identyfikator dla organizacji projektu.
  - `artifactId` (String): Nazwa projektu.
  - `version` (String): Numer wersji projektu.
- **Ważna Logika:** Brak

### Sekcja 2: Konfiguracja Właściwości
- **Opis:** Ustawia właściwości dla procesu budowania, takie jak wersje kompilatora Java i kodowanie UTF-8.
- **Parametry:**
  - `maven.compiler.source` (Integer): Wersja Java do kompilacji.
  - `maven.compiler.target` (Integer): Wersja Java do wykonania.
  - `project.build.sourceEncoding` (String): Kodowanie znaków dla plików źródłowych.
  - `junit.jupiter.version` (String): Wersja zależności JUnit Jupiter.
- **Ważna Logika:** Używa określonej wersji Java do kompilacji i wykonania oraz ustawia kodowanie znaków źródłowych na UTF-8.

### Sekcja 3: Konfiguracja Zależności
- **Opis:** Listuje zależności projektu, w tym Mockito, AssertJ i JUnit Jupiter.
- **Parametry:**
  - `groupId` (String): Unikalny identyfikator dla organizacji zależności.
  - `artifactId` (String): Nazwa zależności.
  - `version` (String): Wersja zależności.
  - `scope` (String): Zakres, w którym używana jest zależność (np. compile, test).
- **Ważna Logika:** Obejmuje zależności testowe dla Mockito, AssertJ i JUnit Jupiter z określonymi wersjami.

### Sekcja 4: Konfiguracja Budowania
- **Opis:** Konfiguruje wtyczki Maven do użycia podczas procesu budowania.
- **Parametry:**
  - `groupId` (String): Unikalny identyfikator dla organizacji wtyczki.
  - `artifactId` (String): Nazwa wtyczki.
  - `version` (String): Wersja wtyczki.
- **Ważna Logika:** Używa wtyczki Maven Surefire (wersja 3.0.0) do testowania.

#### 5. Wersja Języka
Java 17 (określona przez `maven.compiler.source` i `maven.compiler.target`)

#### 6. Wersje Zależności
- Mockito: 5.6.0
- AssertJ: 3.24.2
- JUnit Jupiter: 5.10.0 (mockito-junit-jupiter: 5.6.0)

#### Pseudo Kod
```plaintext
/* Skrypt Budowania Maven dla "dummy-java-project" */

1. Zdefiniuj informacje o projekcie:
   - groupId: org.example
   - artifactId: dummy-java-project
   - version: 1.0-SNAPSHOT

2. Ustaw właściwości budowania:
   - kompilator źródłowy i docelowy: Java 17
   - kodowanie źródłowe: UTF-8
   - wersja JUnit Jupiter: 5.10.0

3. Skonfiguruj zależności:
   - Mockito (5.6.0) - zakres testowy
   - AssertJ (3.24.2) - zakres testowy
   - JUnit Jupiter Engine (5.10.0) - zakres testowy
   - JUnit Jupiter API (5.10.0) - zakres testowy
   - Mockito JUnit Jupiter (5.6.0) - zakres testowy

4. Skonfiguruj wtyczki budowania:
   - Wtyczka Maven Surefire (3.0.0) do testowania

/* Koniec skryptu budowania Maven */
```

#### 8. Odpowiedniki Zależności i Wtyczek
- Mockito: Brak bezpośredniego odpowiednika w Gradle lub npm, ale można zastąpić innymi bibliotekami mockującymi, takimi jak Sinon.js (npm) lub @Mockito/core (Gradle).
- AssertJ: Brak bezpośredniego odpowiednika w Gradle lub npm, ale można zastąpić innymi bibliotekami asercji, takimi jak Chai (npm) lub AssertJ (Gradle).
- JUnit Jupiter: JUnit jest obsługiwany w Gradle i npm. Dla Gradle użyj wtyczki JUnit; dla npm użyj pakietów jest lub mocha.