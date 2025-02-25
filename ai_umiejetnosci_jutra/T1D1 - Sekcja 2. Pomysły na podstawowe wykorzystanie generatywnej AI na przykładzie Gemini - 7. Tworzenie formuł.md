# Sekcja 2. Pomysły na podstawowe wykorzystanie generatywnej AI na przykładzie Gemini - 7. Tworzenie formuł

# 💡 Diagram

```mermaid
graph TD
    A[Gemini & Google Sheets] --> B[Wprowadzenie]
    A --> C[Problem: Analiza Danych Sprzedażowych]
    A --> D[Rozwiązanie z Gemini]
    A --> E[Praktyczny Przykład]
    A --> F[Podsumowanie i Eksperymentowanie]
    A --> G[Konkluzja]

    B --> B1[Wsparcie Gemini dla Arkuszy]
    B --> B2[Analiza Danych Sprzedażowych]
    B --> B3[Identyfikacja Kluczowych Informacji]

    C --> C1[Rozbudowany Arkusz Google Sheets]
    C --> C2[Tysiące Rekordów]
    C --> C3[Cel: Identyfikacja Dni z Zyskiem > 3000 zł]
    C --> C4[Zrozumienie Częstotliwości i Czynników]

    D --> D1[Dwa Podejścia]
    D --> D2[Podejście 1: Przesłanie Arkusza]
    D --> D3[Podejście 2: Zapytanie o Instrukcję (Wybrane)]

    D2 --> D2a[Zaleta: Precyzyjne Wskazówki]
    D2 --> D2b[Wada: Obawy o Prywatność Danych]

    D3 --> D3a[Zaleta: Ochrona Prywatności]
    D3 --> D3b[Skupienie Materiału na Podejściu 2]

    E --> E1[Zapytanie 1: Wyszukiwanie Dat]
    E --> E2[Zapytanie 2: Wizualne Oznaczanie]

    E1 --> E1a[Prompt: Jak znaleźć daty z zyskiem > 3000 zł?]
    E1 --> E1b[Odpowiedź Gemini: Propozycja Metod]
    E1 --> E1c[Wybór Metody przez Użytkownika]

    E2 --> E2a[Prompt: Jak wizualnie oznaczyć daty kolorem?]
    E2 --> E2b[Odpowiedź Gemini: Precyzyjna Instrukcja]
    E2 --> E2c[Wyróżnienie Komórek Kolorem]

    F --> F1[Usprawnienie Pracy z Arkuszami]
    F --> F2[Wskazówki i Sugestie]
    F --> F3[Wykorzystanie Bez Udostępniania Danych]
    F --> F4[Zachęta do Eksperymentowania]
    F --> F5[Opisz Arkusz i Cel AI]
    F --> F6[Pozwól Gemini Wskazać Metody]

    G --> G1[Wartościowe Narzędzie]
    G --> G2[Efektywne Wydobywanie Informacji]
    G --> G3[Wizualizacja Wyników]
    G --> G4[Przyspieszenie Analizy Danych]
    G --> G5[Zrozumienie Złożonych Danych]
    G --> G6[Umiejętności Jutra AI - Projekt Edukacyjny]
```

___

# 🗒️ Notatka


# Gemini i Arkusze Kalkulacyjne Google: Notatki i Podsumowanie

## Wprowadzenie

Niniejsze podsumowanie demonstruje, jak **Gemini** może wspierać pracę z arkuszami kalkulacyjnymi, w szczególności z Arkuszami Google.  Koncentruje się na scenariuszu, w którym użytkownik orientuje się w poszukiwanych danych, lecz potrzebuje pomocy w ich efektywnym wydobyciu lub doborze odpowiedniej formuły. Materiał przedstawia praktyczny przykład analizy danych sprzedażowych, ukazując, w jaki sposób Gemini może usprawnić identyfikację kluczowych informacji.

## Problem i Rozwiązanie z Wykorzystaniem Gemini

### Problem: Analiza Danych Sprzedażowych w Arkuszach Google

- Użytkownik dysponuje **rozbudowanym arkuszem Google Sheets zawierającym dane sprzedażowe** (obejmującym tysiące rekordów).
- Celem jest **sprawna identyfikacja dni**, w których **zysk przekroczył 3000 zł**.
- Istnieje potrzeba zrozumienia **częstotliwości** występowania takich dni oraz **czynników**, które na nie wpływają.

### Dwa Podejścia do Wykorzystania Gemini

1. **Przesłanie Arkusza do Gemini:**
    - Użytkownik ma możliwość **przekazania całego arkusza danych sprzedażowych** do Gemini.
    - Może poprosić Gemini o **szczegółowe instrukcje** dotyczące procesu analizy.
    - **Zaleta:** Gemini uzyskuje bezpośredni dostęp do danych, co umożliwia dostarczenie precyzyjnych wskazówek.
    - **Potencjalna Wada:** Niektórzy użytkownicy mogą mieć obawy związane z udostępnianiem danych zewnętrznemu narzędziu.

2. **Zapytanie o Instrukcję Bez Udostępniania Danych:**
    - Użytkownik **nie udostępnia danych** Gemini.
    - Zamiast tego **prosi Gemini o instrukcję**, jak samodzielnie przeprowadzić analizę w Arkuszach Google.
    - **Zaleta:** Ochrona prywatności danych.
    - **Prezentowane w materiale podejście:** Materiał skupia się na **drugiej opcji**, czyli uzyskaniu instrukcji bez konieczności udostępniania danych.

## Praktyczny Przykład Zastosowania Gemini - Krok po Kroku

### Zapytanie 1: Wyszukiwanie Dat z Wysokim Zyskiem

- **Scenariusz:** Użytkownik wciela się w rolę analityka analizującego arkusz danych sprzedażowych z ostatniego roku.
- **Zapytanie (prompt) do Gemini:**
    > Jestem analitykiem analizującym arkusz danych sprzedażowych z ostatniego roku. Chciałbym szybko odnaleźć daty, w których zysk przekroczył 3000 zł. Jak mogę to zrobić w Arkuszach Google?
- **Odpowiedź Gemini:** Gemini **proponuje szereg metod** na zlokalizowanie odpowiednich komórek w Arkuszach Google. Użytkownik może wybrać sposób, który uzna za najprostszy lub najbardziej adekwatny.

### Zapytanie 2: Wizualne Oznaczanie Danych

- **Kolejne zadanie:** Użytkownik pragnie **wizualnie wyróżnić** dni z wysokim zyskiem, aby ułatwić ich identyfikację.
- **Zapytanie (prompt) do Gemini:**
    > Jak mogę wizualnie oznaczyć te daty w arkuszu, używając koloru?
- **Odpowiedź Gemini:** Gemini dostarcza **precyzyjną instrukcję**, jak wizualnie zmodyfikować arkusz, aby **wyróżnić komórki z wysokim zyskiem za pomocą koloru**. Dzięki temu użytkownik może łatwo zlokalizować i oznaczyć interesujące go dane.

## Podsumowanie i Zachęta do Eksperymentowania

- **Gemini usprawnia pracę z Arkuszami Google** poprzez dostarczanie wskazówek i sugestii dotyczących analizy i wizualizacji danych.
- Możliwe jest jego wykorzystanie **bez udostępniania poufnych danych**, poprzez prośbę o ogólne instrukcje.
- **Zachęcamy do eksperymentowania z Gemini** na własnych arkuszach danych.
    - **Opisz swój arkusz i cel analizy** dla generatywnej AI.
    - **Pozwól Gemini wskazać optymalne metody osiągnięcia zamierzonego celu** w arkuszu kalkulacyjnym.

## Konkluzja

Materiał demonstruje praktyczne zastosowanie Gemini w analizie danych w Arkuszach Google.  Ukazuje, że Gemini stanowi wartościowe narzędzie dla osób pracujących z danymi, wspomagając efektywne wydobywanie informacji i wizualizację wyników, nawet bez zaawansowanej wiedzy o formułach arkuszy kalkulacyjnych. Narzędzie to może znacząco przyspieszyć proces analizy danych i ułatwić zrozumienie złożonych zbiorów informacji.

---

**Umiejętności Jutra AI** - Projekt edukacyjny wspierany przez Google, SGH i Ministerstwo Cyfryzacji.


___

# 🔉 Transcript
File: Sekcja 2. Pomysły na podstawowe wykorzystanie generatywnej AI na przykładzie Gemini - 7. Tworzenie formuł.mp4<br>
[00:00:05] Teraz dowiesz się, jak Gemini może ci pomóc w korzystaniu z arkuszy kalkulacyjnych. Na przykład, gdy wiesz jakich danych szukasz, ale nie wiesz jak je efektywnie wyciągnąć lub po prostu jaką formułę wykorzystać.
[00:00:17] Wyobraź sobie, że masz przed sobą arkusz Google z danymi sprzedażowymi, ale lista jest bardzo długa, kilka tysięcy rekordów. A my chcemy po prostu szybko zidentyfikować dni, w których zysk przekroczył, na przykład 3000 zł.
[00:00:30] Aby móc zrozumieć ile takich dni było, a potem postarać się lepiej zrozumieć co na to wpłynęło.
[00:00:36] Możemy to zadanie wykonać na dwa sposoby. Albo wrzucając do Gemini cały arkusz z danymi sprzedażowymi i poprosić go o przeprowadzenie nas przez cały proces krok po kroku, jak to zrobić.
[00:00:47] Lub, jeśli nie chcemy wrzucać naszych danych sprzedażowych do Gemini, możemy poprosić o instrukcję, jak samodzielnie to zrobić.
[00:00:55] Teraz sprawdźmy tą drugą opcję.
[00:00:57] (The screen shows the Gemini Advanced interface. On the left side, there is a menu with options like "New Chat," "Recent," and "Settings." In the center, a text field displays "Hello, Specialist!")
[00:00:58] Jesteś analitykiem i przeglądasz arkusz z danymi sprzedażowymi z ostatniego roku.
[01:04] (The screen shows the Gemini Advanced interface. On the left side, there is a menu with options like "New Chat," "Recent," and "Settings." In the center, a text field displays "Hello, Specialist!")
[01:05] Chciałbym szybko znaleźć daty, w których zysk osiągnął powyżej 3000 zł.
[01:10] Zaproponuj, jak mogę to zrobić w arkuszach Google.
[01:15] (The screen shows the Gemini Advanced interface. On the left side, there is a menu with options like "New Chat," "Recent," and "Settings." In the center, a text field displays "Hello, Specialist!" The text box is empty.)
[01:15] Teraz jak widzimy, Gemini podał nam kilka sposobów na znalezienie odpowiednich komórek i możecie wybrać taki, które najbardziej wam odpowiada albo wydaje się po prostu najprostsze.
[01:26] (The screen shows the Gemini Advanced interface. On the left side, there is a menu with options like "New Chat," "Recent," and "Settings." In the center, a text field displays "Hello, Specialist!")
[01:27] A co jeśli chciałbym zrobić coś innego? Na przykład wizualnie oznaczyć i wyróżnić komórki z tym wyższym zyskiem?
[01:34] Mogę wpisać kolejny prompt.
[01:36] Jak mogę wizualnie oznaczyć te daty w arkuszu kolorem?
[01:41] (The screen shows the Gemini Advanced interface. On the left side, there is a menu with options like "New Chat," "Recent," and "Settings." In the center, a text field displays "Hello, Specialist!" The text box is empty.)
[01:41] No i otrzymałem dokładną instrukcję, jak wizualnie dostosować arkusz, dzięki czemu będę mógł w łatwy sposób odnaleźć interesujące mnie dane i zaznaczyć konkretne komórki.
[01:52] Co dalej? Na pewno macie jakieś arkusz albo dane, które chcielibyście lepiej zrozumieć.
[01:57] Opiszcie generatywnej AI, jak ten arkusz wygląda i co chcielibyście zrozumieć i niech wskaże wam jak możecie to zrobić.
[02:04] (The screen shows the logo of "Umiejętności Jutra AI," with logos of Google, SGH, and Ministerstwo Cyfryzacji.)

___
# 🏷️ Tags
#gemini #arkusze_google #google_sheets #arkusze_kalkulacyjne #dane_sprzedażowe #analiza_danych #wizualizacja_danych #identyfikacja_danych #instrukcje #krok_po_kroku #wysoki_zysk #oznaczanie_danych #prywatność_danych #prompt #analityk #metody_analizy #wizualne_oznaczanie #eksperymentowanie #optymalne_metody #narzędzie_ai #efektywne_wydobywanie #złożone_informacje #umiejętności_jutra_ai #ministerstwo_cyfryzacji #sgh #edukacja_ai #formuły_arkuszy_kalkulacyjnych
