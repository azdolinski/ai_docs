# File: T5D3 - Lekcje wideo - 1. Wprowadzenie.md
## Notatki i Podsumowanie Prezentacji Wideo: "Umiejętności Jutra AI"

## Wprowadzenie

Prezentacja Wojciecha Strzałkowskiego pt. "Umiejętności Jutra AI" analizuje różnice pomiędzy tradycyjnymi projektami IT a projektami wykorzystującymi **sztuczną inteligencję** (`AI`), koncentrując się szczególnie na **uczeniu maszynowym** (`Machine Learning` / `ML`). Prelegent, opierając się na swoim doświadczeniu, przedstawia kluczowe aspekty, na które należy zwrócić uwagę podczas wdrażania projektów `AI`, aby uniknąć typowych pułapek i osiągnąć sukces. Podkreśla istotę jasno zdefiniowanego celu, danych, infrastruktury technicznej i zespołu, a także omawia różnice w podejściu do projektów `ML` i `LLM` (`Large Language Models`).

## Projekty IT vs. Projekty AI – Różnice w Podejściu

### Przykład z życia: CRM vs. System Przewidywania Odpływu Klientów

* **Scenariusz:** Prezes firmy przedstawia dwa projekty:
    * Wdrożenie nowego systemu `CRM` (klasyczny projekt IT).
    * System przewidywania odpływu klientów wykorzystujący `AI`.
* **Założenia:** Ten sam budżet i termin realizacji.
* **Kluczowa Różnica:** Sposób realizacji tych projektów jest zasadniczo odmienny.

### Doświadczenie z Booking.com: Channel Recommender

* **Problem:** Jak optymalnie obsłużyć klienta (telefon 📞, e-mail 📧, czat 💬, samoobsługa)?
* **Ryzyko:**
    * Koszty związane z droższymi kanałami obsługi.
    * Potencjalna utrata rezerwacji wartej setki euro w wyniku nieprawidłowego przekierowania.
* **Pierwotne rozwiązanie:** System reguł oparty na logice "if-else" (drzewo decyzyjne).
    * Przykładowe reguły:
        * Rezerwacja > 7 dni: e-mail / czat.
        * Wartość rezerwacji > 1000 euro: telefon.
* **Przełom:** Decyzja o zastosowaniu `AI`.
* **Wyzwanie:** Zamiast reguł, kluczowe stają się dane.
    * Potrzeba tysięcy interakcji z klientami (historia rezerwacji, zapisy czatów, e-maili, rozmów telefonicznych).
    * Potencjalnie istotne zmienne: pora dnia 🕰️, kraj pochodzenia klienta 🌍, historia interakcji.

### Zaskoczenie i Efektywność Modeli AI

* **Pierwszy model AI:** Niska skuteczność (załóżmy 60%).
    * W tradycyjnym IT – katastrofa (np. system księgowy z 60% poprawnością).
    * W `AI` – to dopiero początek.
* **Kolejne miesiące:** Eksperymenty, optymalizacja parametrów.
* **Postęp:** Po kilku miesiącach – 82% skuteczności, ale tylko dla klientów z historią kontaktów.
* **Fundamentalna różnica IT vs. AI:**
    * **IT (Tradycyjne): Architekt 🏗️.** Planowanie, precyzyjne kroki, przewidywalność.
    * **AI (ML): Naukowiec 🔬.** Eksperymenty, hipotezy, testowanie, uczenie się na błędach, brak gwarancji dokładnej skuteczności w określonym czasie.
* **Analogia:**
    * **IT: Budowa domu 🏠.** Projekt, harmonogram, etapy.
    * **AI: Uprawa ogrodu 🌷.** Tworzenie warunków, pielęgnacja, nieprzewidywalność natury (zarówno pozytywne, jak i negatywne niespodzianki).

## Co jest Potrzebne do Wdrożenia Projektu AI? – 4 Kluczowe Elementy (Ważna Kolejność)

1. **Jasny cel i zakres.**
    * Unikaj wdrażania `AI` dla samego faktu wdrożenia.
    * Skoncentruj się na konkretnym problemie biznesowym do rozwiązania.
    * **Przykład Booking.com:** Nie automatyzacja obsługi klienta jako taka, lecz redukcja liczby połączeń telefonicznych przy zachowaniu satysfakcji klientów.
    * **Mierzalność sukcesu:** Zdefiniowanie wskaźników i kryteriów sukcesu projektu.

2. **Dane.**
    * **Częsty błąd:** Poszukiwanie `data scientist` przed dokonaniem analizy danych.
    * **Kluczowe:** Dostępność adekwatnych danych w odpowiedniej ilości i jakości.
    * **Analogia:** Próba przewidywania pogody ☀️ na cały rok na podstawie obserwacji z okna przez 3 miesiące.
    * **Weryfikacja danych:** Upewnij się, że dysponujesz odpowiednimi danymi, zanim pójdziesz dalej.

3. **Infrastruktura techniczna.**
    * **Nie chodzi o:** Inwestycję w najdroższy sprzęt i wszystkie możliwe narzędzia na starcie.
    * **Na początek wystarczy:** Laptop 💻 i dostęp do chmury ☁️.
    * **Istotne:** Infrastruktura umożliwiająca szybkie eksperymentowanie, sprawne trenowanie modeli, przechowywanie i przetwarzanie danych.

4. **Zespół.**
    * **Nie tylko:** `Data scientist`.
    * **Wymagane role:**
        * **Inżynierowie danych:** Przygotowanie i przetwarzanie danych.
        * **Product manager / Analityk biznesowy:** Zrozumienie specyfiki `AI`.
        * **Eksperci dziedzinowi:** Dogłębne zrozumienie biznesu.
            * **Przykład Booking.com:** Agenci obsługi klienta (wiedza o nietypowych i skomplikowanych przypadkach).

### Od Czego Zacząć?

* **Cel i Dane.**
    * Bez nich cała reszta traci sens.
    * Nawet najlepszy zespół i budżet nie przyniosą efektów bez jasno określonego celu i danych.

### Balans Elementów

* Wszystkie 4 elementy muszą być odpowiednio zbalansowane.
    * Doskonałe dane bez odpowiedniej infrastruktury – problem.
    * Wybitny zespół bez konkretnego celu – strata czasu i środków.
* **Analogia: Gotowanie obiadu 🍲.** Składniki, sprzęt kuchenny, przepis, kucharz 👨‍🍳. Brak któregokolwiek elementu skutkuje koniecznością zamówienia pizzy 🍕.

## ML vs. AI (Konkretnie ML vs. LLM) – Różnice w Podejściu

### Klasyczne Uczenie Maszynowe vs. Modele Językowe (np. GPT)

* **Przykład: Obsługa Klienta.**
* **Klasyczne ML (Booking.com):**
    * Uczenie modelu **konkretnego zadania** – przewidywanie preferowanego kanału komunikacji.
    * Określone zmienne wejściowe (czas do przyjazdu, wartość rezerwacji, typ pokoju).
    * Precyzyjna odpowiedź wyjściowa (telefon, e-mail, czat).
    * **Analogia:** Wyspecjalizowany pracownik (jedno zadanie, perfekcyjne wykonanie).

* **Modele Językowe (LLM):**
    * **Wszechstronny konsultant 🧑‍💼.** Różnorodne zadania bez potrzeby dedykowanego trenowania dla każdego z nich.
    * **Przykład: Asystent w obsłudze klienta.**
    * **Podejście:** `Prompt` (kontekst). "Jesteś asystentem firmy X, znasz procedury, zachowujesz określony `tone of voice`...".
    * **Wszechstronność ma swoją cenę:** Mniejsza kontrola i przewidywalność.

### Kontrola, Skuteczność i Projektowanie Projektów

* **Machine Learning:**
    * Pełna kontrola nad danymi treningowymi.
    * Precyzyjny pomiar skuteczności (model poprawnie/niepoprawnie przewidział kanał).
* **Modele Językowe (LLM):**
    * Odpowiedź poprawna merytorycznie, ale niekoniecznie zgodna ze stylem firmy.
    * Odpowiedź poprawna, lecz nieoptymalna.
* **Sposób prowadzenia projektu:**
    * **ML:** Konkretny problem, dane, trening, pomiar wyników.
    * **LLM:** Projektowanie `promptów`, zabezpieczenia przed halucynacjami, integracja z procesami, testowanie scenariuszy.
* **Analogia:**
    * **ML: Robot 🤖 na linii produkcyjnej.** Konkretne zadanie, wysoka precyzja.
    * **LLM: Asystent 🤝.** Wszechstronny, wymaga briefingu i nadzoru.

### Projekty Machine Learningowe – Główny Temat Prezentacji

* Oba podejścia (`ML` i `LLM`) są wartościowe, ale wymagają odmiennego zarządzania projektem.
* Prezentacja koncentruje się na `ML` (ze względu na doświadczenie prelegenta).
* Doświadczenia z dużych (Booking.com – własne modele) i mniejszych projektów (rozwiązania zewnętrzne).
* **Zasady sukcesu są zbliżone:** Niezależnie od tego, czy budujesz własne modele, czy współpracujesz z dostawcą.
* **Rola Dostawcy:** Wsparcie techniczne, ale to firma musi wiedzieć, czego oczekuje i jak to zmierzyć.
* **Analogia: Remont mieszkania 🛠️.** Samodzielnie czy z ekipą – musisz mieć jasną wizję efektu końcowego.

### Unikanie Pułapek w Projektach Machine Learning

* Prezentacja ma na celu pokazanie, jak unikać typowych pułapek i na co zwracać szczególną uwagę.
* Wiedza ta jest przydatna w rozmowach zarówno z zespołami `Data Science`, jak i dostawcami `AI`.

## Podsumowanie / Konkluzja

Sukces projektów `AI`, a w szczególności **uczenia maszynowego** (`Machine Learning`), opiera się na zrównoważonym podejściu do czterech kluczowych elementów: jasno określonego celu i zakresu, danych, infrastruktury technicznej i zespołu. Istotne jest zrozumienie różnic między projektami IT i `AI`, jak również specyfiki projektów `ML` w kontekście `LLM`. Kluczowe znaczenie ma rozpoczęcie od precyzyjnego zdefiniowania celu i dogłębnej analizy dostępnych danych. Niezależnie od tego, czy tworzymy własne modele `ML`, czy korzystamy z zewnętrznych rozwiązań, fundamentalne zasady sukcesu pozostają niezmienne. Świadomość tych aspektów umożliwia efektywne zarządzanie projektami `AI` i unikanie powszechnych błędów.
___
# File: T5D3 - Lekcje wideo - 2. Cykl życia projektu AI Zdefiniuj problem.md
## Umiejętności Jutra AI - Notatki i Podsumowanie

## Wprowadzenie

Prezentacja "Umiejętności Jutra AI" prowadzona przez Wojciecha Strzałkowskiego omawia **cykl życia projektu AI** oraz **framework RIGC**, czyli narzędzie do oceny przydatności problemu biznesowego do rozwiązania za pomocą sztucznej inteligencji 🤖. Szkolenie to kładzie nacisk na praktyczne podejście do projektów AI, podkreślając **zdefiniowanie problemu biznesowego** jako fundamentalny pierwszy krok.

## Cykl Życia Projektu AI

Wojciech Strzałkowski prezentuje **praktyczny cykl życia projektu AI**, oparty na doświadczeniach z licznych wdrożeń.  Zaznacza, że **kolejność kroków** ma **kluczowe** znaczenie dla powodzenia projektu.

**Schemat Cyklu Życia Projektu AI (7 kroków):**

1. **Zdefiniuj problem:** Fundamentalny pierwszy krok. Wdrożenie AI samo w sobie nie stanowi problemu. Skoncentruj się na problemach biznesowych, takich jak redukcja zwrotów czy skrócenie czasu obsługi klienta ⏱️.
2. **Zdobądź dane:**  Weryfikacja dostępności i jakości danych. Brak danych może uniemożliwić realizację projektu, dlatego istotne jest sprawdzenie tego na wczesnym etapie.
3. **Spróbuj bez AI:** Rozważenie prostych rozwiązań, na przykład opartych na regułach `if else`. Często proste metody mogą przynieść znaczną część oczekiwanych rezultatów.
4. **Utwórz zatkę bezpieczeństwa:** (Krok wspomniany w cyklu, lecz nie omówiony szczegółowo w tym fragmencie).
5. **Wystaw model:** (Trening i wdrożenie modelu AI).
6. **Zdobądź feedback:**  Zbieranie opinii i danych zwrotnych po wdrożeniu modelu w celu jego ulepszenia.
7. **Monitoruj:**  Ciągłe monitorowanie działania modelu i osiąganych efektów.

**Ważne aspekty cyklu życia projektu AI:**

- **Model praktyczny, nie teoretyczny.** Bazuje na realnych doświadczeniach z wdrożeń.
- **Kolejność kroków jest kluczowa.**  Powszechny błąd to rozpoczęcie od trenowania modelu przed właściwym zdefiniowaniem problemu.
- **Cykl ma charakter iteracyjny.**  Często wymaga powrotu do wcześniejszych etapów i iteracji w celu dopracowania.
- **Punktem wyjścia jest zdefiniowanie problemu biznesowego.**

## RIGC Framework - Ocena Projektów AI

`RIGC Framework` to narzędzie stworzone przez Wojciecha Strzałkowskiego, służące do oceny, czy dany problem kwalifikuje się do rozwiązania z wykorzystaniem AI. Nazwa `RIGC` nawiązuje do memów o "rozum i godność człowieka", analogicznie mając na celu ocenę "rozumu" projektu AI 🤔.

**RIGC = Relevant + Impactful + Grounded in data + Compatible**

**Elementy Frameworku RIGC:**

- **R - Relevant (Istotność):**
    - Czy projekt jest **istotny** z punktu widzenia biznesu?
    - Czy **bezpośrednio przyczynia się** do realizacji kluczowych celów biznesowych firmy?

- **I - Impactful (Wpływ):**
    - Czy projekt przyniesie **znaczący wpływ**?
    - Czy można **wymiernie określić potencjalne korzyści** (np. oszczędności kosztów 💰, wzrost przychodów 📈, poprawa satysfakcji klienta 😊)?

- **G - Grounded in data (Oparcie w danych):**
    - Czy projekt jest **oparty na solidnych danych**?
    - Czy **dysponujemy danymi** niezbędnymi do realizacji projektu i wytrenowania modelu?

- **C - Compatible (Kompatybilność):**
    - Czy rozwiązanie AI będzie **kompatybilne** z istniejącą infrastrukturą i procesami w firmie?
    - Czy **łatwo zintegruje się** z bieżącą działalnością operacyjną?

**Zalety RIGC Framework:**

- **Prostota i praktyczność.**
- Nie wymaga złożonych analiz ani skomplikowanych kalkulacji.
- Umożliwia **szybką ocenę** potencjału projektu AI.
- Chroni przed **inwestycjami w nieefektywne rozwiązania**.
- Pełni rolę **mapy drogowej**, wskazując obszary wymagające dopracowania przed wdrożeniem.

## Przykłady Zastosowania RIGC Framework

### Przykład 1: Chatbot dla Firmy Telekomunikacyjnej

- **Problem:** Firma telekomunikacyjna planuje wdrożenie chatbota do obsługi klienta.

- **Analiza RIGC:**
    - **Relevant:** **Tak**. Poprawa satysfakcji klienta i skrócenie czasu reakcji to kluczowe cele biznesowe. Chatbot bezpośrednio wspiera te założenia.
    - **Impactful:** **Tak**. Analiza wykazuje, że chatbot może odciążyć zespół obsługi klienta i podnieść satysfakcję poprzez natychmiastowe odpowiedzi. Każda zaoszczędzona minuta w czasie odpowiedzi ma realny wpływ.
    - **Grounded in data:** **Tak**. Firma zgromadziła wieloletnią historię interakcji z klientami (czaty, rozmowy), co stanowi solidną bazę danych (wymagającą jednak oczyszczenia).
    - **Compatible:** **Tak**. Istniejąca platforma obsługi klienta może zostać zintegrowana z chatbotem, choć będzie to wymagało pewnych modyfikacji.

- **Wniosek:** Projekt chatbota dla telekomunikacji **pozytywnie przechodzi** ocenę `RIGC`.

### Przykład 2: Wyszukiwanie Produktów Obrazem w E-commerce

- **Problem:** Wdrożenie funkcji wyszukiwania produktów za pomocą obrazów w sklepie internetowym 🛍️.

- **Analiza RIGC:**
    - **Relevant:** **Tak**. Wpisuje się w strategiczny cel firmy – podniesienie satysfakcji i konwersji poprzez personalizację oferty.
    - **Impactful:** **Wątpliwe**. Innowacyjne rozwiązanie, lecz **brak danych**, które potwierdzałyby, że użytkownicy będą z niego korzystać i że przełoży się to na wzrost sprzedaży.
    - **Grounded in data:** **Nie**. Firma posiada zdjęcia produktów, ale **brakuje kluczowych metadanych** niezbędnych do efektywnego trenowania modelu rozpoznawania obrazów.
    - **Compatible:** (Kwestia kompatybilności nie jest szczegółowo omawiana, głównym problemem są dane).

- **Potencjalne rozwiązanie problemu z danymi:** Integracja z zewnętrznym API, np. Vertex AI, w celu automatycznego tagowania produktów. **Wady:** wzrost złożoności projektu i kosztów operacyjnych 💸.

- **Wniosek:** Projekt wyszukiwania obrazem **nie przechodzi pozytywnie** oceny `RIGC` z powodu braku danych.  Wskazane jest skupienie się najpierw na budowie bazy metadanych produktowych, zanim wdroży się tak zaawansowane rozwiązanie.

## Reguły Kciuka - Szybka Ocena Projektów Machine Learning

Trzy proste reguły, które ułatwiają szybką ocenę, czy dany problem nadaje się do rozwiązania za pomocą `machine learning`.

1. **Personalizacja czy Customizacja?**
    - **Customizacja:** Użytkownik samodzielnie dostosowuje ustawienia. `Machine learning` prawdopodobnie **nie jest potrzebny**.
    - **Personalizacja:** System automatycznie dostosowuje się do zachowań użytkownika. Dobry kandydat dla **`machine learning`**.
    - **Przykład:** Netflix - personalizacja rekomendacji filmów (ML) vs. ręczne ustawienia preferencji (brak ML) 🎬.

2. **Rozpoznawanie lub Łączenie Wzorów.**
    - `Machine learning` jest efektywny w **rozpoznawaniu wzorców**, zwłaszcza tych subtelnych i złożonych, trudnych do identyfikacji manualnie.
    - **Przykład:** Filtr antyspamowy - ML rozpoznaje wzorce w treści, nagłówkach i zachowaniu nadawców, aby identyfikować spam 📧.

3. **Powtarzalna Sekwencja Akcji.**
    - Jeśli proces decyzyjny jest **skomplikowany i uwzględnia wiele czynników**, a jednocześnie **powtarza się** na dużą skalę, `machine learning` może okazać się przydatny.
    - **Przykład:** Obsługa klienta w Uberze - decyzja o rekompensacie dla klienta zależy od wielu czynników (historia klienta, rodzaj problemu, lokalizacja 📍, pogoda ☀️, etc.). ML może wspomóc podejmowanie decyzji na podstawie analizy tysięcy podobnych przypadków.

## Podsumowanie

Prezentacja "Umiejętności Jutra AI" koncentruje się na **praktycznym podejściu do projektów AI**, podkreślając **fundamentalną rolę zdefiniowania problemu biznesowego** oraz **dostępności danych**. Przedstawiony **cykl życia projektu AI**  precyzyjnie prowadzi przez proces wdrożenia krok po kroku.  `RIGC Framework` stanowi proste, lecz efektywne narzędzie do **oceny projektów AI**, pomagając uniknąć inwestycji w rozwiązania, które nie przyniosą oczekiwanych korzyści. Dodatkowo, **trzy reguły kciuka** oferują szybką metodę weryfikacji, czy dany problem jest odpowiedni dla `machine learning`.  Całość materiału akcentuje **rozważne i strategiczne podejście do AI**,  zaczynając od **jasno określonych celów biznesowych** i **solidnych fundamentów danych** 📊.
___
# File: T5D3 - Lekcje wideo - 3. Cykl życia projektu AI Znajdź dane.md
## Umiejętności Jutra AI: Przygotowanie Danych - Notatki i Podsumowanie

## Wprowadzenie

Prezentacja "Umiejętności Jutra AI" koncentruje się na kluczowym aspekcie projektów sztucznej inteligencji (AI) – **przygotowaniu danych**. Wojciech Strzałkowski podkreśla, że **przygotowanie danych jest najważniejszym krokiem we wdrażaniu AI**, stanowiącym przejście od teorii do praktycznych zastosowań. Celem prezentacji jest wyjaśnienie, w jaki sposób modele uczenia maszynowego przyswajają wiedzę oraz jakie kryteria muszą spełniać dane, aby były adekwatne dla modeli AI.

## Cykl Życia Projektu AI i Rola Danych

Prezentacja rozpoczyna się od przedstawienia schematu **cyklu życia projektu AI**, składającego się z siedmiu etapów:

1. Określenie problemu
2. **Zebranie danych** (etap kluczowy)
3. Konfiguracja bazy AI
4. Utworzenie zatwierdzenia bezpieczeństwa
5. Wdrożenie modelu
6. Zbieranie informacji zwrotnej (feedback)
7. Monitorowanie

Etap **"Zebranie danych"** został wyróżniony jako fundamentalny, co podkreśla istotną rolę danych w całym procesie.

## Jak Uczą Się Modele Uczenia Maszynowego? - Analogia Egzaminu 📝

Wojciech Strzałkowski, aby objaśnić proces uczenia modeli, posługuje się analogią nauczyciela przygotowującego ucznia do egzaminu:

- **Zbiór Treningowy:**  Przyrównany do **starych egzaminów z poprzednich lat**. Model (uczeń) uczy się na ich podstawie rozpoznawania wzorców i podejmowania decyzji.
- **Zbiór Testowy:** Porównany do **próbnego egzaminu, którego uczeń wcześniej nie widział**. Służy do weryfikacji, czy model (uczeń) rzeczywiście przyswoił wiedzę, a nie tylko zapamiętał odpowiedzi.

## Przykład Praktyczny: Model Kredytowy Banku 🏦

Aby zilustrować znaczenie danych, zaprezentowano przykład banku, który chce stworzyć model prognozujący, czy klient zaciągnie kredyt.

- **Dane Wejściowe (Kolumny A):** Informacje o kliencie: **wiek, dochód roczny, stan cywilny, historia kredytowa**.
- **Etykiety / Labels (Kolumna B):**  To, co model ma przewidywać: **Czy klient wziął kredyt? (1 = Tak, 0 = Nie)**. Są to tak zwane **etykiety (labels)**.

Model uczy się zależności pomiędzy danymi wejściowymi (A) a etykietami (B). Następnie, dla nowego klienta (dysponując jedynie danymi z kolumn A), model ma za zadanie przewidzieć wartość B – prawdopodobieństwo zaciągnięcia kredytu.

**Kluczowe wnioski z przykładu:**

- Jakość i reprezentatywność **danych treningowych** są **fundamentalne**.
- Jeśli dane treningowe są **jednorodne** (np. obejmują tylko młode osoby), model może nauczyć się **błędnych wzorców**.

## Jakie Dane Nadają Się do Modelu AI? - Cztery Kluczowe Kryteria ✅

Podkreślono, że **dane stanowią absolutny fundament każdego projektu AI**.  Nawet najlepszy zespół i budżet nie компенсуют braku odpowiednich danych. Dane muszą spełniać cztery kluczowe kryteria:

1. **Relewantne**
2. **Opisane (Olabelkowane)**
3. **Kompletne**
4. **Zróżnicowane**

### 1. Relewantność Danych 🎯

- Dane muszą być **ściśle powiązane z problemem**, który zamierzamy rozwiązać.
- **Błąd:** Tworzenie systemów rekomendacji w oparciu o logi systemowe zamiast analizy zachowań użytkowników (analogia kliknięć w menu vs. dokonanych zakupów).
- **Wiedza ekspercka jest kluczowa** dla określenia relewantnych danych. Należy korzystać z wiedzy:
    - **Ekspertów dziedzinowych:** Co wpływa na skuteczność sprzedaży? (np. białe tło zdjęć produktów).
    - **UX researcherów i obsługi klienta:** Jakie problemy zgłaszają użytkownicy? (np. szczegóły produktu ważniejsze niż kliknięcia).
    - **Trendów i badań naukowych:** Czy istnieją potwierdzone wzorce?
- **Należy unikać:** Wprowadzania do modelu wszystkich dostępnych danych w nadziei, że AI samo wyciągnie wnioski. **Większa ilość danych nie zawsze przekłada się na lepszą jakość.**  Lepiej skoncentrować się na **mniejszej liczbie istotnych sygnałów**.
- **Praktyka:**  Konieczna jest ścisła współpraca zespołu Machine Learning z ekspertami biznesowymi już na etapie definiowania danych treningowych.

### 2. Opisane (Labelled) Dane 🏷️

- Dane muszą być **opatrzone etykietami (olabelkowane)**, co oznacza, że **musimy wiedzieć, co te dane faktycznie reprezentują**.
- **Przykład reCaptcha:** Rozwiązywanie reCaptcha **trenuje modele AI Google** (digitalizacja Google Books, archiwum New York Times). **Crowdsourcing w oznaczaniu danych**.
- **Istotne:** Oznaczenia muszą mieć **znaczenie z punktu widzenia problemu biznesowego**.
- **Przykład z obrazami kotów i psów:** 🐈 🐕
    - **Podstawowa Klasyfikacja (Mało Użyteczne):**  \"Pies\", \"Kot\" - proste, lecz mało przydatne biznesowo.
    - **Oznaczenie Konkretnych Cech (Użyteczne):** Waga zwierząt (np. 18 funtów, 14 funtów) - dane metryczne, bardziej wartościowe (analogicznie do rozmiaru, materiału, stylu bluzki w e-commerce).
    - **Brak Oznaczeń (Problem):**  Masy nieopisanych danych - realność wielu firm. **Sztuka efektywnego oznaczania** polega na etykietowaniu tylko danych, które mają istotne znaczenie.
- **Ponownie podkreślono:** Wiedza ekspercka (dziedzinowa, UX, trendy) pomaga określić, **które dane są naprawdę istotne** i jak je efektywnie oznaczać.

### 3. Kompletność Danych (i Jakość) 💯

- **Kompletność danych jest kluczowa**.
- **Porównanie:** Zestaw danych \"uporządkowany\" (kompletny, jednolity) kontra \"bałagan\" (braki, niejasne znaki, nieprawidłowe wartości).
- **Oczywiste:** Zestaw \"uporządkowany\" umożliwi modelowi podejmowanie **trafniejszych decyzji**.
- **Analogia:** Niekompletne dane są jak kucharz bez kompletu składników. 🧑‍🍳
- **Skutki:**  Błędne decyzje AI, bazujące na niekompletnych danych, mogą generować **poważne straty finansowe** (przykład banku).
- **Rozwiązania w zakresie kompletności danych:**
    - **Walidacja na wejściu:** Weryfikacja danych już w momencie ich gromadzenia.
    - **Standaryzacja:** Ujednolicenie formatów danych (np. \"kawaler\" vs. \"kaw.\").
    - **Automatyczna detekcja anomalii:** Systemy identyfikujące braki i nieprawidłowe wartości.
    - **Świadomość:** Uświadomienie zespołu, że złe dane = złe decyzje.

### 4. Zróżnicowanie Danych 🌍

- **Zróżnicowanie danych jest kluczowe, aby uniknąć błędów poznawczych i stronniczości.**
- **Przykład błędu poznawczego:** Model rozpoznawania obrazów. Trenowany na zbiorze danych, w którym większość zdjęć osób gotujących przedstawia kobiety. Model błędnie klasyfikuje mężczyzn gotujących również jako kobiety.
- **AI działa w oparciu o wzorce obecne w danych.** Jeśli dane są obciążone stronniczością, AI powieli i wzmocni te błędy.
- **Konsekwencje braku zróżnicowania:** Dyskryminacja, błędne decyzje, potencjalne zagrożenia dla ludzi.
- **Rozwiązania w zakresie zróżnicowania danych:**
    - **Weryfikacja reprezentacji różnych grup użytkowników** w danych przez zespół.
    - **Testowanie modelu na danych, które nie były wykorzystane do treningu**, w celu wykrycia potencjalnych błędów.
    - **Nadzór ludzki:** AI nie może być jedynym decydentem w sytuacjach wysokiego ryzyka. Modele muszą być **nadzorowane i regularnie aktualizowane**.
- **Zróżnicowanie danych to fundament odpowiedzialnych systemów AI.** Brak zróżnicowania może prowadzić do logicznych, lecz katastrofalnie błędnych decyzji.

## Podsumowanie Kryteriów Danych i Kluczowe Pytanie 🤔

Przed rozpoczęciem procesu trenowania modelu, należy zadać sobie **fundamentalne pytanie:** **Czy nasze dane w ogóle nadają się do tego celu?**

**Cztery podstawowe kryteria danych (przypomnienie):**

1. **Relewantność:** Czy dane odnoszą się do rozwiązywanego problemu?
2. **Opisanie:** Czy rozumiemy, co dane oznaczają?
3. **Kompletność:** Czy dane są pełne i pozbawione braków?
4. **Zróżnicowanie:** Czy dane reprezentują różnorodne grupy i scenariusze?

**Rada:** **Skonsultuj się z zespołem Data Science.** Ich wiedza pomoże przeanalizować, zweryfikować jakość i udoskonalić dane.

**Ważne przesłanie końcowe:** **Im wcześniej rozpoczniecie dyskusję o danych, tym lepiej.** Nie czekajcie, aż pojawią się problemy. Złe dane = złe wyniki.

## Podsumowanie Prezentacji 📝

Prezentacja Wojciecha Strzałkowskiego "Umiejętności Jutra AI" skupia się na **przygotowaniu danych jako fundamentalnym etapie w projektach AI**.  Podkreśla, że **jakość danych ma większe znaczenie niż ich ilość**.  Przedstawiono **cztery kluczowe kryteria**, które dane muszą spełniać, aby były odpowiednie dla modeli uczenia maszynowego: **relewantność, opisanie, kompletność i zróżnicowanie**.  Prezentacja zawiera praktyczne przykłady i analogie, ułatwiające zrozumienie omawianych koncepcji, a także akcentuje znaczenie **współpracy z ekspertami dziedzinowymi i zespołem Data Science** w procesie przygotowania danych.  Głównym przesłaniem jest **świadome podejście do danych** i zrozumienie, że **dobre dane stanowią fundament skutecznej i odpowiedzialnej AI**.
___
# File: T5D3 - Lekcje wideo - 4. Cykl życia projektu AI Spróbuj bez AI.md
## Notatki i Podsumowanie Prezentacji Wideo: "Umiejętności Jutra AI"

## Wprowadzenie

Prezentacja wideo pt. "Umiejętności Jutra AI", zorganizowana przez Google 🔍 i SGH, koncentruje się na praktycznym podejściu do wdrażania sztucznej inteligencji (`AI`) 🤖.  Kluczowym przesłaniem jest **zweryfikowanie, czy dany problem można rozwiązać za pomocą prostszych metod, zanim zainwestuje się w złożone rozwiązania `AI`**.  Podkreśla się, że często najbardziej efektywne i opłacalne jest rozpoczęcie od rozwiązań deterministycznych, opartych na jasnych regułach, a nie probabilistycznych modelach `AI`.

## Główna Teza: Zacznij od Rozwiązań Bez `AI`

*   Często postrzegamy `AI` jako magiczne rozwiązanie, lecz warto rozważyć prostsze metody na początku.
*   **Kluczowe pytanie:** Czy problem da się rozwiązać bez użycia `AI`?
*   **Korzyść:** Oszczędność czasu ⏱️ i pieniędzy 💰.
*   **Zasada:** Przed wdrożeniem `AI`, spróbuj rozwiązać problem prostszymi sposobami.

## Przykład Amazona: Just Walk Out

*   **Technologia Just Walk Out Amazona:**  Miała bazować na zaawansowanej `AI` i umożliwiać zakupy bez kas.
*   **Rzeczywistość:** System był wspierany przez **1000 pracowników w Indiach 🇮🇳**, ręcznie weryfikujących transakcje.
*   **Wniosek:**  Technologia `AI` była reklamowana, ale w praktyce zadanie wykonywali ludzie. To przykład, jak **implementacja `AI` w rzeczywistości odbiega od obietnic marketingowych.**

## Weryfikacja Hipotezy Bez `AI`: System Deterministyczny

*   **Najbardziej kosztowo efektywna metoda pracy z `AI`.**
*   Budowa systemu **deterministycznego** (nie probabilistycznego) umożliwia weryfikację kluczowych hipotez przed inwestycją w `AI`.
*   **System deterministyczny:** Funkcjonuje w oparciu o konkretne, zdefiniowane reguły.

### Cztery Kluczowe Hipotezy do Weryfikacji

1.  **Hipoteza dotycząca sygnałów z danych:**
    *   **Pytanie:** Czy dane w ogóle zawierają użyteczne sygnały?
    *   **Przykład:** Prognozowanie rezygnacji klientów (`churn`).
    *   **Weryfikacja:** Sprawdzenie, czy w danych widoczne są wzorce związane z rezygnacją, zanim zastosuje się `AI`.
    *   **Możliwy wynik:** Może okazać się, że **brak wyraźnych zależności** i `AI` nie przyniesie oczekiwanej wartości.

2.  **Hipoteza dotycząca wpływu biznesowego:**
    *   **Pytanie:** Czy rozwiązanie (nawet z `AI`) realnie wpłynie na działalność biznesową?
    *   **Weryfikacja:** Ustalenie, czy rozwiązanie przełoży się na **oszczędności lub zwiększenie przychodów.**
    *   **Możliwy wynik:** Nawet doskonały model `AI` może okazać się nieprzydatny, jeśli nie generuje korzyści biznesowych.

3.  **Hipoteza dotycząca zdolności organizacji do wdrożenia:**
    *   **Pytanie:** Czy organizacja jest przygotowana na wdrożenie `AI`?
    *   **Wymagania `AI`:** Dostępność danych, odpowiednia infrastruktura, kompetencje zespołu.
    *   **Weryfikacja:** Sprawdzenie, czy organizacja dysponuje zasobami i umiejętnościami potrzebnymi do wdrożenia i **monitorowania `AI`.**
    *   **Możliwy problem:** Brak kompetencji w zakresie monitorowania `AI` może **przynieść więcej szkody niż pożytku.**

4.  **Hipoteza dotycząca `UX` (User Experience) / akceptacji użytkowników:**
    *   **Pytanie:** Czy użytkownicy zaakceptują nowe rozwiązanie?
    *   **Przykład:** Chatbot obsługi klienta.
    *   **Weryfikacja:** Zbadanie, czy użytkownicy będą chętnie korzystać z nowego rozwiązania.
    *   **Możliwy wynik:**  Nawet najlepszy chatbot może ponieść klęskę, jeśli klienci preferują tradycyjne kanały kontaktu (np. infolinia 📞).

## Przykłady Weryfikacji Hipotez Bez `AI`

*   **Spersonalizowane rekomendacje:**
    *   **Zamiast `AI`:** Prezentowanie **bestsellerów, popularnych w lokalizacji danego użytkownika.**
    *   **Cel:** Proste rozwiązanie, które może zaspokoić potrzebę rekomendacji bez angażowania skomplikowanego systemu `AI`.

*   **ChatBot obsługi klienta:**
    *   **Zamiast zaawansowanego ChatBota `AI`:**  Wykorzystanie **prostego chatbota z predefiniowanymi odpowiedziami.**  (Określony jako "Też chatbot, tylko że głupi :)").
    *   **Cel:** Weryfikacja, czy prosty chatbot jest w stanie rozwiązać podstawowe problemy użytkowników.

*   **Wykrywanie rezygnacji klienta (`churn`):**
    *   **Zamiast modelu `AI`:**  **Monitorowanie klientów, którzy nie logowali się od miesiąca.**
    *   **Cel:** Prosty wskaźnik potencjalnej rezygnacji, łatwy we wdrożeniu i monitorowaniu.

## Podsumowanie i Wnioski

*   **Zasada:** Jeżeli problem można rozwiązać prostszą metodą, **`AI` staje się zbędne.**
*   **Weryfikacja bez `AI`:** Najbardziej ekonomiczny i szybki sposób na ocenę, czy warto inwestować w uczenie maszynowe.
*   **Kluczowe pytanie przed wdrożeniem `AI`:** Czy `AI` jest naprawdę niezbędne?
*   **Wartość prostoty:** Niekiedy **najlepsze rozwiązania okazują się prostsze, niż przypuszczamy.**
*   **Rekomendacja:** Przed rozpoczęciem trenowania modelu `AI`, **zweryfikujmy hipotezy za pomocą prostszych, deterministycznych metod.**

## Zakończenie Prezentacji "Umiejętności Jutra AI"

*   Organizator: Google 🔍
*   Partner edukacyjny: SGH
___
# File: T5D3 - Lekcje wideo - 5. Cykl życia projektu AI Utwórz siatkę bezpieczeństwa.md
## Notatki i Podsumowanie: Zarządzanie Ryzykiem w Projektach AI

## Wprowadzenie

Niniejsze notatki dotyczą **zarządzania ryzykiem** w projektach **sztucznej inteligencji (AI)**. Podkreślono, że tworzenie modeli AI to nie tylko kwestia danych i algorytmów, ale przede wszystkim odpowiedzialność za potencjalne konsekwencje ich działania w rzeczywistych warunkach. W materiale omówiono koncepcję `siatki bezpieczeństwa` oraz **macierzy ryzyka AI**, które pomagają kontrolować i minimalizować ryzyko związane z wdrażaniem systemów AI.

## Kluczowe Zagadnienia

### 1. Ryzyko Związane z AI ⚠️

* Tworzenie modeli AI to nie tylko kwestia danych i algorytmów, ale przede wszystkim **zarządzanie ryzykiem**.
* AI, mimo poprawnego działania w środowisku testowym, może generować **błędy w rzeczywistych warunkach**, niosące za sobą konsekwencje, takie jak:
    * **Straty finansowe** 💰
    * **Utrata reputacji** 📉
    * **Zagrożenie życia ludzkiego** 🚑 (w skrajnych przypadkach)
* Przed wdrożeniem modelu AI niezbędne jest stworzenie **`siatki bezpieczeństwa`** – zespołu mechanizmów kontroli i minimalizacji ryzyka błędnych decyzji.

### 2. `Siatka Bezpieczeństwa` w Cyklu Życia Projektu AI 🔄

* **Cykl życia projektu AI** (schemat blokowy):
    1. **Zdefiniowanie problemu** 🎯
    2. **Gromadzenie danych** 📊
    3. **Rozważenie alternatyw dla AI** (analiza rozwiązań innych niż AI) 🤔
    4. **Stworzenie `siatki bezpieczeństwa`** (kluczowy etap przed wdrożeniem) 🛡️
    5. **Wdrożenie modelu** 🚀
    6. **Zbieranie informacji zwrotnej** (feedback po wdrożeniu) 👂
    7. **Monitorowanie** (ciągłe śledzenie działania modelu) 👁️
* **Przykład Lekarza i Diagnozy AI:** 🧑‍⚕️
    * Lekarz korzysta z systemu AI, który sugeruje diagnozy na podstawie milionów przypadków.
    * **AI sugeruje, ale ostateczna decyzja należy do człowieka (lekarza).**
    * Lekarz **ponosi odpowiedzialność** za potwierdzenie diagnozy, konsultację z pacjentem i decyzję o leczeniu.
    * W kwestiach zdrowia i życia **AI nie może działać autonomicznie**.
    * **Kontrola eksperta (człowieka) jest niezbędna.**

### 3. Zróżnicowane Poziomy Kontroli w Zależności od Kontekstu ⚖️

* Nie każdy system AI wymaga tak **rygorystycznej kontroli**, jak w przypadku zastosowań medycznych.
* **Przykład Podpowiedzi w Czacie:** 💬
    * AI proponuje odpowiedzi w oknie czatu, bazując na kontekście rozmowy.
    * Błędy AI w tym scenariuszu mają **minimalne konsekwencje**.
    * Użytkownik ma możliwość **zignorowania sugestii** i wprowadzenia własnej wiadomości.

### 4. **Macierz Ryzyka AI** - Dostosowanie Nadzoru do Znaczenia Decyzji 📐

* **Macierz ryzyka AI** (matryca) pomaga dopasować poziom nadzoru do wagi decyzji podejmowanych przez AI.
* **Osie matrycy:**
    * **Oś pionowa: Stawka (Wysoka/Niska)** - konsekwencje błędnej decyzji.
    * **Oś pozioma: Dokładność (Niska/Wysoka)** - pewność modelu AI.
* **Cztery pola matrycy:**
    * **Wysoka stawka, Niska dokładność: WERYFIKUJ (Verify)** ✅
        * AI sugeruje decyzję, **człowiek musi ją zatwierdzić**.
        * **Przykład:** AI prognozuje reakcje pacjentów na leki, lekarz zatwierdza zmiany w terapii.
    * **Wysoka stawka, Wysoka dokładność: CO-PILOT (CoPilot)** 🧑‍✈️
        * AI działa bardziej autonomicznie, lecz nadal **pod nadzorem człowieka**.
        * **Przykład:** Systemy detekcji oszustw finansowych. AI identyfikuje i blokuje transakcje, analityk weryfikuje przed zamrożeniem konta.
    * **Niska stawka, Niska dokładność: IGNORUJ (Disregard)** ❌
        * **Ignoruj wyniki AI**, polegaj na decyzjach ludzi.
        * **Przykład:** Systemy odpowiadające na komentarze w mediach społecznościowych, które błędnie interpretują ton wypowiedzi.
    * **Niska stawka, Wysoka dokładność: AUTOMATYZUJ (Automate)** 🤖
        * **Pełna automatyzacja procesu.**
        * **Przykład:** AI rekomendujące utwory w serwisach streamingowych. Błąd ma znikome konsekwencje (pominięcie utworu).

## Podsumowanie

Wdrażanie modeli AI wiąże się z ryzykiem, którym należy aktywnie zarządzać. Kluczowym elementem jest **stworzenie `siatki bezpieczeństwa`**, zapewniającej kontrolę nad działaniem AI. Poziom nadzoru nad systemem AI powinien być **dostosowany do wagi podejmowanych decyzji oraz dokładności modelu**. **Macierz ryzyka AI** stanowi narzędzie pomocne w określeniu adekwatnego poziomu kontroli – od weryfikacji decyzji AI przez człowieka, poprzez model działający jako co-pilot, aż po pełną automatyzację w sytuacjach niskiego ryzyka. Zrozumienie i stosowanie zasad **zarządzania ryzykiem** jest fundamentalne dla odpowiedzialnego i bezpiecznego wdrażania technologii AI.
___
# File: T5D3 - Lekcje wideo - 6. Cykl życia projektu AI Wytrenuj model.md
## Notatki i Podsumowanie: Trenowanie Modeli AI 🤖

## Wprowadzenie

Ten materiał omawia kluczowy etap w tworzeniu sztucznej inteligencji - **trenowanie modeli AI**. Podkreśla powszechny błąd polegający na rozpoczynaniu procesu od zbyt skomplikowanych modeli. Promuje podejście **Minimum Viable Model (MVM)**, czyli rozpoczęcie od prostych modeli w celu szybkiej weryfikacji danych i założeń.

## Trenowanie Modeli AI - Kluczowe Aspekty

### Najczęstszy Błąd: Zbyt Skomplikowane Modele na Start

- Wiele zespołów **błędnie zakłada**, że im bardziej zaawansowany model (np. wielowarstwowe sieci neuronowe), tym lepsze rezultaty osiągną.
- **Prawda jest inna**: Rozpoczynanie od złożonych modeli typu "czarna skrzynka" jest ryzykowne i nieefektywne.
- **Zalecenie**: Przyjęcie metodycznego podejścia krok po kroku, zaczynając od prostych rozwiązań.

### Minimum Viable Model (MVM)

- **Definicja MVM**: Najprostszy model, który umożliwia sprawdzenie, czy dane w ogóle pozwalają na przewidywanie interesujących nas zjawisk.
- **Analogia do MVP (Minimum Viable Product)** ze świata startupów 🚀: MVM jest odpowiednikiem MVP w dziedzinie AI.
- **Przykłady prostych modeli**:
    - Regresja liniowa
    - Drzewa decyzyjne
    - Proste sieci neuronowe
- **Cel MVM**: Szybkie zrozumienie, czy dane są wartościowe i czy dalsze prace mają sens.

### Zalety MVM

MVM oferuje **trzy kluczowe korzyści**, które pomagają uniknąć błędnych inwestycji czasu 🕰️ i zasobów:

#### 1. Jakość Danych 📊

- **Sprawdzenie jakości danych**: MVM pozwala ocenić, czy dane są wystarczająco dobre, zanim zainwestuje się w bardziej złożone modele.
- **Problemy z danymi**: Mogą obejmować niekompletność, błędy, niespójność oraz brak istotnych cech.
- **Działania naprawcze**:  Koncentrują się na uzupełnianiu brakujących wartości, standaryzacji formatów i lepszym opisie zmiennych.
- **Kluczowe pytanie**: Czy dane faktycznie niosą wartość predykcyjną?

#### 2. Zrozumienie Kluczowych Czynników 🔍

- **Zrozumienie mechanizmów decyzyjnych modelu**: MVM umożliwia identyfikację czynników (zmiennych) o największym wpływie na predykcje.
- **Demistyfikacja "czarnej skrzynki"** 🪞: Na początkowym etapie kluczowe jest zrozumienie, jak model podejmuje decyzje.
- **Weryfikacja intuicji**: Może okazać się, że zmienne uważane za istotne, wcale takie nie są, podczas gdy inne, mniej oczywiste cechy, mają większy wpływ.
- **Przykład**: W modelu oceny ryzyka kredytowego 🏦, historia kredytowa może być mniej istotna niż miesięczne wydatki.
- **Wartość wiedzy**: Pozyskana wiedza umożliwia ulepszanie modelu i przynosi korzyści dla biznesu.

#### 3. Ocena Sensowności Dalszych Prac 🤔

- **Ocena możliwości predykcji**: MVM pozwala zweryfikować, czy dany problem w ogóle da się skutecznie rozwiązać za pomocą AI.
- **Chaotyczna natura danych**: Zależności w danych bywają niestabilne lub chaotyczne, co uniemożliwia skuteczną predykcję.
- **Sygnał ostrzegawczy** ⚠️: Jeśli prosty model nie wykazuje żadnej struktury w danych, bardziej zaawansowane metody prawdopodobnie również nie przyniosą poprawy.
- **Przykład**: Przewidywanie rynku finansowego 📈 –  często charakteryzuje się brakiem powtarzalnych informacji w danych.
- **Decyzja**: Na podstawie MVM można podjąć świadomą decyzję, czy kontynuować projekt i rozwijać model, czy zrezygnować i poszukać alternatywnego podejścia.

### Proces Trenowania Modeli to Nie "Czarna Skrzynka" 💡

- **Zaangażowanie stakeholderów biznesowych**: Proces trenowania modelu nie jest magiczną "czarną skrzynką", lecz wymaga współpracy.
- **Współpraca Data Science i Biznesu** 🤝: Wymaga zaangażowania zarówno ekspertów technicznych, jak i osób zorientowanych biznesowo.
- **Wiedza biznesowa**: Stakeholderzy biznesowi posiadają wiedzę niezbędną do oceny, czy model faktycznie odpowiada na potrzeby firmy i rozwiązuje realne problemy.

## Podsumowanie

Rozpoczęcie trenowania modeli AI od **Minimum Viable Model (MVM)** jest kluczowe dla efektywnego i oszczędnego podejścia. Zamiast inwestować od razu w skomplikowane sieci neuronowe, zaleca się start od prostych modeli, takich jak regresja liniowa czy drzewa decyzyjne. MVM umożliwia **szybką weryfikację jakości danych**, **zrozumienie kluczowych czynników wpływających na predykcje** oraz **ocenę sensowności dalszych prac**.  Co więcej, proces trenowania modeli AI powinien być transparentny i angażować **stakeholderów biznesowych**, aby zapewnić jego adekwatność do potrzeb firmy. Podejście MVM to **oszczędność czasu 🕰️ i pieniędzy 💰**, a przede wszystkim **lepsza droga do zbudowania skutecznie działającego AI** ✅.
___
# File: T5D3 - Lekcje wideo - 7. Cykl życia projektu AI Zdobądź feedback.md
## Notatki i Podsumowanie: Ocena Modeli AI poprzez Feedback Użytkowników

## Wprowadzenie

Ta notatka omawia kluczowy aspekt weryfikacji modeli sztucznej inteligencji (AI) - **feedback użytkowników**. Podkreśla, że wdrożenie modelu i osiągnięcie dobrych metryk (jak `accuracy` i `precision`) to za mało. Najważniejsza jest **użyteczność** modelu i generowanie wartościowych wyników dla użytkowników. Materiał koncentruje się na ocenie, czy model realnie spełnia swoje zadanie w praktyce.

## Kluczowe Pytanie: Czy Model Działa Efektywnie? 🤔

*   Po stworzeniu modelu AI, pojawia się fundamentalne pytanie: **\"Jak zweryfikować, czy model efektywnie spełnia swoje zadanie?\"**
*   Nie wystarczy polegać wyłącznie na metrykach technicznych.
*   Kluczowe jest skupienie się na **interakcji użytkowników** z modelem i oceną jego wyników.

## Wyzwania Wdrożenia AI i Akceptacja Użytkowników

*   Samo wdrożenie AI nie gwarantuje sukcesu.
*   **Użytkownicy muszą chcieć korzystać** z modelu i jego rekomendacji.
*   Przykład: Model wspierający agentów obsługi klienta 🧑‍💼.
    *   Jeśli agenci **nie korzystają** z rekomendacji modelu, sygnalizuje to problem.
    *   Potencjalne przyczyny:
        *   Model generuje **nietrafne odpowiedzi**.
        *   Agenci preferują **tradycyjne metody pracy**.

## Przykłady Praktyczne: Netflix i TikTok 🎬📱

### Netflix - Model Rekomendacji Filmów i Seriali 🍿

*   Model rekomendacji Netflixa jest uznawany za skuteczny, ale jak to potwierdzić?
*   **Analiza statystyk** jest pomocna, lecz **najprostszym testem** jest sprawdzenie, czy użytkownicy **klikają w proponowane tytuły**.
*   **Negatywne sygnały:**
    *   Użytkownik **ignoruje rekomendacje** w danej kategorii.
    *   Użytkownik **ręcznie wyszukuje treści**.
    *   Użytkownik **długo przegląda listę** bez wyboru.
*   Te zachowania wskazują, że model **nie dostarcza wartości** i **nie personalizuje rekomendacji**.

### TikTok - Dynamiczny Model Rekomendacji Wideo 📹

*   TikTok to jeszcze bardziej dynamiczny przykład.
*   Model AI **decyduje o kolejnym wyświetlanym wideo**.
*   **Feedback jest natychmiastowy i bezkompromisowy.**
*   **Negatywny feedback:**
    *   Użytkownik **szybko przewija** nietrafne wideo.
    *   Użytkownik **opuszcza aplikację**.
*   **Pozytywny feedback:**
    *   Użytkownik **ogląda wideo do końca**, **interaguje** (lajkuje 👍, komentuje 💬, udostępnia 📤).
*   TikTok pokazuje, że **AI musi angażować i przyciągać uwagę odbiorców**.

## Interfejs Białkowy - Ludzka Weryfikacja Wyników AI 🧠

*   Feedback to nie tylko dane ilościowe. Ważna jest **ludzka ocena** wyników AI, tzw. **\"interfejs białkowy\"**.
*   Należy **osobiście analizować predykcje modelu** i ocenić ich **sensowność**.
*   Przykłady sytuacji, gdzie ludzka ocena jest kluczowa:
    *   Model rekomenduje **absurdalne filmy**.
    *   Chatbot udziela **dziwnych odpowiedzi**.
    *   Algorytm scoringowy **faworyzuje nieodpowiednie osoby**.
*   W takich przypadkach **interwencja człowieka jest niezbędna** ("stop! ✋").

## Podsumowanie i Kluczowe Wnioski 📝

*   **Zbieranie feedbacku** to więcej niż analiza metryk.
*   Najważniejsza jest **praktyczna ocena**, czy użytkownicy:
    *   **Angażują się** w interakcję z modelem.
    *   Uznają **wyniki modelu za wartościowe**.
*   **AI funkcjonuje w realnym świecie**, nie w izolacji.
*   Ignorowanie predykcji AI to **sygnał problemu**, który wymaga interwencji.
*   **Feedback użytkowników jest fundamentalny** dla weryfikacji i doskonalenia modeli AI.

---

*Logo \"Umiejętności Jutra AI\" z logotypami Google i SGH.*
___
# File: T5D3 - Lekcje wideo - 8. Cykl życia projektu AI Monitoruj.md
## Notatki i Sumaryzacja Prezentacji Wideo: Umiejętności Jutra AI - Efektywność Modeli AI

## Wprowadzenie

Prezentacja "Umiejętności Jutra AI" zorganizowana przez Google i SGH koncentruje się na kluczowym aspekcie projektów AI: **monitorowaniu i ocenie efektywności wdrożonych modeli**. Wojciech Strzałkowski wyjaśnia, że wytrenowanie i wdrożenie modelu to dopiero początek. Kluczowe jest zrozumienie, czy model działa zgodnie z założeniami i przynosi realną wartość biznesową.

## Monitorowanie i Cykl Życia Projektu AI

*   **Wdrożenie to początek, a nie koniec procesu.** Po implementacji modelu AI, ciągłe monitorowanie jego działania jest niezbędne.
*   **Sprawdzanie zgodności z oczekiwaniami:** Czy model funkcjonuje zgodnie z pierwotnymi założeniami?
*   **Generowanie wartości biznesowej:** Czy model realnie przyczynia się do realizacji celów firmy?
*   **Cykl życia projektu AI jest iteracyjny.** Monitorowanie stanowi punkt wyjścia dla kolejnych iteracji i ulepszeń.

## Problem z Metryką `Accuracy`: Przykład Zwrotów w E-commerce 🛍️

*   **Przykład z firmy e-commerce:** Model predykcji prawdopodobieństwa zwrotu produktu.
*   **Średnia stopa zwrotów:** 10%.
*   **Cel modelu:** Identyfikacja zamówień z wysokim ryzykiem zwrotu, w celu optymalizacji logistyki i redukcji kosztów.
*   **Wytrenowany model z `accuracy` na poziomie 90%.** Na pierwszy rzut oka, wynik wydaje się obiecujący.
*   **Brak poprawy wskaźnika zwrotów po wdrożeniu.** Pomimo wysokiej `accuracy`, model nie generuje oczekiwanych rezultatów biznesowych.
*   **Analiza `Accuracy`:**
    *   `Accuracy` mierzy procent poprawnych predykcji we **wszystkich** przypadkach.
    *   Model z 90% `accuracy` przewiduje brak zwrotu w 100% przypadków, myląc się w 10% (co odpowiada średniej stopie zwrotów).
    *   Model **nie identyfikuje ryzykownych zamówień**, a jedynie powiela statystykę, zakładając, że klienci nie będą zwracać produktów.
*   **Wniosek:** Wysoka `accuracy` nie zawsze przekłada się na efektywność modelu w kontekście konkretnego problemu biznesowego. `Accuracy` może być **myląca** i **nadużywana** przez dostawców rozwiązań AI.

## `Precision` i `Recall`: Bardziej Adekwatne Metryki Efektywności

*   **Alternatywne metryki:** `Precision` (precyzja) i `Recall` (czułość).
*   **Wzajemna zależność:** `Precision` i `Recall` opisują różne aspekty skuteczności modelu i są ze sobą powiązane.
*   **Definicje:**
    *   **`Precision` (Precyzja):**  Procent poprawnych **pozytywnych** predykcji. Określa, na ile możemy polegać na pozytywnych wskazaniach modelu.
        > Innymi słowy: Jeśli model przewidział zwrot, jak często miał rację?
    *   **`Recall` (Czułość):** Procent **rzeczywiście** wykrytych przypadków pozytywnych. Informuje nas, ile rzeczywistych pozytywnych przypadków model poprawnie zidentyfikował.
        > Innymi słowy: Czy model skutecznie wykrywa większość problematycznych zamówień (zwrotów)?
*   **W kontekście zwrotów e-commerce:**  `Recall` nabiera **większego znaczenia**. Zależy nam, aby model wychwytywał **większość** potencjalnych zwrotów, nawet kosztem ewentualnych fałszywych alarmów. Niska czułość oznacza, że model ignoruje zwroty, co uniemożliwia podjęcie działań zapobiegawczych.

## Kontekstowe Znaczenie `Precision` i `Recall`

*   **Zastosowanie determinuje istotność metryk.** Wybór ważniejszej metryki zależy od konkretnego zastosowania modelu.
*   **Modele antyfraudowe w bankowości:** `Precision` staje się **kluczowa**.
    > Lepiej wskazać mniej transakcji jako podejrzane, ale mieć pewność, że są to rzeczywiste oszustwa. Fałszywe alarmy mogą być bardzo problematyczne dla klientów.
*   **Diagnostyka medyczna 🩺:** `Recall` jest **decydująca**.
    > Lepiej skierować kilka zdrowych osób na dodatkowe badania, niż przeoczyć pacjenta z poważną chorobą. Przeoczenie choroby niesie poważniejsze konsekwencje niż dodatkowe badania dla osób zdrowych.

## Metryki Biznesowe Mają Najwyższy Priorytet 🥇

*   **`Precision` i `Recall` to istotne wskaźniki, ale nie jedyne.** Warto o nie pytać, jednak to **metryki biznesowe** ostatecznie decydują o sukcesie wdrożenia modelu.
*   **Przykłady metryk biznesowych:**
    *   System rekomendacji: Czy **zwiększa sprzedaż 📈**?
    *   Model oceny ryzyka kredytowego: Czy usprawnia **proces podejmowania decyzji kredytowych 🏦**?
    *   Chatbot obsługi klienta: Czy **oszczędza czas 🕰️**, **podnosi jakość obsługi klienta**, czy generuje wzrost liczby połączeń na infolinię?
*   **Monitorowanie AI to proces ciągły.** Zmiany w danych i zachowaniach użytkowników wymagają stałej analizy wyników. Bez monitorowania, model może stracić **użyteczność biznesową**, nawet przy poprawnym działaniu technicznym.

## Iteracyjny Cykl Życia AI i Doskonalenie Modeli

*   **Monitorowanie inicjuje kolejną iterację.** Analiza wyników stanowi podstawę do wprowadzania ulepszeń.
*   **AI to system dynamiczny, uczący się.** Musi adaptować się do zmieniających się danych i preferencji użytkowników.
*   **Powrót do definicji problemu:**
    *   Czy model nadal efektywnie rozwiązuje pierwotny problem?
    *   Czy ewoluowały potrzeby biznesowe?
    *   Czy zidentyfikowano nowe wzorce w danych lub zmiany w zachowaniu użytkowników?
*   **Uczenie się na błędach i udoskonalanie:**
    *   Optymalizacja danych wejściowych.
    *   Dostrajanie hiperparametrów.
    *   Modyfikacja funkcji kosztu.
    *   Zmiana podejścia do problemu.
*   **Cykl iteracyjny:** Testowanie, ulepszanie, dostosowywanie - **niekończąca się pętla 🔄**.
*   **Szybkość iteracji ma kluczowe znaczenie.** Im szybszy cykl iteracji, tym lepiej.
*   **AI najefektywniej funkcjonuje jako dynamiczny system uczący się.**

## Kreatywność i Zrozumienie Biznesowe w AI 💡

*   **Kluczowa myśl:** **Bądź kreatywny!**
*   **AI to nie tylko matematyka i kod 💻.** To **narzędzie do rozwiązywania problemów** w biznesie, nauce i życiu codziennym.
*   **Nie trzeba być ekspertem matematyki, aby pracować z AI.** Istotne jest **zrozumienie problemów** i **umiejętność zadawania trafnych pytań**.
*   **Najbardziej wartościowe projekty AI:** Rodzą się z połączenia **wiedzy technicznej** z **intuicją biznesową** i **kreatywnym myśleniem**.
*   **Zachęta do działania:** Eksperymentuj, ucz się, kwestionuj wyniki, iteruj.
*   **AI to narzędzie, a nie magia ✨.** Najlepiej działa, gdy rozumiemy jego potencjał i ograniczenia.
*   **Kluczowe jest inteligentne wykorzystanie technologii AI.**

## Podsumowanie

Prezentacja podkreśla, że **wdrożenie modelu AI to dopiero początek drogi 🚀**. Kluczowe staje się **ciągłe monitorowanie i ocena efektywności**, uwzględniająca nie tylko aspekty techniczne, ale przede wszystkim **wartość biznesową**. Metryka `accuracy` może wprowadzać w **błąd**, a bardziej miarodajnymi wskaźnikami są `precision` i `recall`, których waga zależy od **konkretnego zastosowania**. Najistotniejsze pozostają jednak **metryki biznesowe**, które realnie odzwierciedlają, czy model przynosi oczekiwane korzyści. Projekty AI mają charakter **iteracyjny**, wymagając nieustannego **udoskonalania i adaptacji** do zmieniających się danych i potrzeb. Ostatecznie, w pracy z AI kluczową rolę odgrywa **kreatywność, intuicja biznesowa oraz umiejętność mądrego korzystania z technologii**, a nie tylko zaawansowana wiedza matematyczna.