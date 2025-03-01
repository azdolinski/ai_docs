# File: T1D1 - Materiały dodatkowe - 1. Podsumowanie.md
## Podsumowanie Kursu: Podstawy Promptowania

Ten dokument zawiera szczegółowe notatki i podsumowanie kluczowych informacji z kursu "Podstawy Promptowania". Kurs koncentruje się na zrozumieniu **GenAI** i **LLM**, oraz na efektywnym tworzeniu `promptów`, aby osiągnąć pożądane rezultaty. Poniższe notatki pomogą Ci utrwalić wiedzę i zastosować ją w praktyce.

## Kluczowe Aspekty Podstaw Promptowania

### Wprowadzenie do GenAI i LLM

* **GenAI (Generative AI)**: To rodzaj sztucznej inteligencji, który generuje nowe treści – teksty, obrazy, muzykę, kod i inne dane. **GenAI** wykorzystuje **LLM (Large Language Models)** do tworzenia tych treści.
* **LLM (Large Language Models)**: To rozbudowane modele językowe, trenowane na ogromnych zbiorach danych tekstowych. Dzięki temu **LLM** rozumieją język naturalny i potrafią generować tekst, tłumaczyć języki oraz wykonywać inne zadania językowe, odpowiadając na zapytania w języku naturalnym.

### Inżynieria Promptów

* **Inżynieria promptów**: To proces projektowania skutecznych `promptów` (zapytań) dla **LLM**. Celem jest tworzenie `promptów`, które pozwolą uzyskać precyzyjne i pożądane wyniki z modeli językowych. Dobrze skonstruowany `prompt` jest kluczowy dla efektywnego wykorzystania **GenAI** i **LLM**.

### Pięcioetapowe Podejście do Tworzenia Efektywnych Promptów

Materiały kursu rekomendują pięcioetapowe podejście do tworzenia efektywnych `promptów`:

1. **Zadanie (Task)**: Zdefiniuj jasno zadanie, które ma wykonać model językowy. Określ cel `promptu`.
2. **Kontekst (Context)**: Dostarcz modelowi niezbędny kontekst, aby ułatwić mu zrozumienie zadania. Kontekst może obejmować dodatkowe informacje, tło tematyczne lub ograniczenia.
3. **Odniesienie (Reference)**: Wprowadź przykłady, wzorce lub preferowany styl odpowiedzi. Jest to szczególnie przydatne w podejściach `one-shot` i `few-shot`.
4. **Ocena (Evaluation)**: Przeanalizuj wyniki wygenerowane przez model. Sprawdź, czy odpowiedź jest zgodna z oczekiwaniami i czy realizuje cel zadania.
5. **Iteracja (Iteration)**: Na podstawie oceny, ulepsz `prompt` i powtórz proces. Iteracja jest kluczowa dla optymalizacji `promptów` i uzyskiwania coraz lepszych wyników.

### Człowiek w Pętli (Human-in-the-Loop)

* **Podejście z człowiekiem w pętli**: Jest niezwykle istotne, ponieważ **GenAI** i **LLM**, pomimo zaawansowania, mogą generować wyniki nieprecyzyjne, nieprawdziwe lub niepożądane. **Weryfikacja wyników przez człowieka jest niezbędna**, aby zapewnić jakość i poprawność generowanych treści. Człowiek odgrywa kluczową rolę w nadzorowaniu i korygowaniu pracy **AI**.

### Metody Tworzenia Promptów

* **Podejście Zero-shot**: Model jest pytany o coś, czego nie widział wcześniej w kontekście treningowym. Oczekuje się poprawnej odpowiedzi bez przykładów.
* **Podejście One-shot**: Dostarcza się jeden przykład zadania i oczekiwanej odpowiedzi, a następnie model jest proszony o wykonanie podobnego zadania.
* **Podejście Few-shot**: Dostarcza się kilka przykładów zadania i oczekiwanych odpowiedzi, aby model lepiej zrozumiał wzorzec i generował bardziej precyzyjne wyniki.

### Zaawansowane Techniki Promptowania

* **Łańcuch Promptów (Chain of Prompts)**: Metoda polegająca na dzieleniu złożonego zadania na sekwencję mniejszych, powiązanych `promptów`. Wynik jednego `promptu` staje się kontekstem dla kolejnego, co umożliwia modelowi bardziej skomplikowane i logiczne rozumowanie.
* **Łańcuch Myśli (Chain of Thought)**: Technika zachęcająca model do ujawnienia procesu myślowego prowadzącego do odpowiedzi. `Prompt` prosi model nie tylko o odpowiedź, ale także o krok po kroku wyjaśnienie, jak do niej doszedł. To poprawia jakość odpowiedzi w zadaniach wymagających rozumowania.

### Zastosowania GenAI i LLM

**GenAI** i **LLM** znajdują zastosowanie w wielu obszarach, w tym:

* **Podsumowywanie tekstów**: Automatyczne generowanie skrótów i streszczeń długich tekstów.
* **Tłumaczenie języków**: Przekład tekstu z jednego języka na drugi.
* **Generowanie pomysłów (Ideation)**: Wspomaganie kreatywności poprzez generowanie nowych koncepcji i inspiracji.
* **Tworzenie obrazów**: Generowanie grafik i ilustracji na podstawie opisów tekstowych.
* **Generowanie formuł do arkuszy kalkulacyjnych**: Automatyczne tworzenie formuł w programach typu Excel lub Google Sheets.
* **Klasyfikowanie informacji**: Automatyczne przypisywanie danych do odpowiednich kategorii.

### Rola Człowieka w Kontekście GenAI i LLM

* **Weryfikacja wyników**: Człowiek jest niezbędny do oceny i weryfikacji wyników generowanych przez **GenAI** i **LLM**, aby zapewnić ich poprawność, rzetelność i zgodność z oczekiwaniami.
* **Tworzenie lepszych promptów**: Doświadczenie i wiedza człowieka są kluczowe w iteracyjnym procesie ulepszania `promptów`. Analizując wyniki i identyfikując niedoskonałości, człowiek może tworzyć coraz skuteczniejsze zapytania, co przekłada się na lepszą wydajność modeli językowych.

## Podsumowanie

Kurs "Podstawy Promptowania" wprowadza w świat Generatywnej Sztucznej Inteligencji (**GenAI**) i Dużych Modeli Językowych (**LLM**). Kluczowym elementem efektywnego wykorzystania tych technologii jest inżynieria `promptów`, czyli umiejętność tworzenia skutecznych zapytań. Kurs podkreśla pięcioetapowe podejście do tworzenia `promptów`, metody `promptowania` (`zero-shot`, `one-shot`, `few-shot`) oraz zaawansowane techniki, takie jak łańcuch `promptów` i łańcuch myśli. Niezwykle istotna jest rola człowieka w pętli, który weryfikuje wyniki i udoskonala `prompty`. **GenAI** i **LLM** mają szerokie spektrum zastosowań, od podsumowywania tekstów po generowanie obrazów, a ich potencjał jest ogromny, pod warunkiem umiejętnego `promptowania` i ludzkiego nadzoru.
___
# File: T1D1 - Materiały dodatkowe - 2. Strategie promptowania.md
## Notatki i Podsumowanie Strategii Promptowania 🚀

## Wprowadzenie

Ten dokument zawiera szczegółowe notatki i podsumowanie strategii **promptowania**, przedstawionych w dalszej części. Strategie te mają na celu podniesienie jakości i precyzji odpowiedzi generowanych przez modele językowe, poprzez umiejętne formułowanie zapytań (promptów).  Niniejsze notatki bazują na tabeli, która omawia różnorodne strategie, prezentuje przykładowe elementy promptów oraz dostarcza dodatkowych informacji dotyczących ich efektywności.

## Szczegółowe Notatki Strategii Promptowania

### Echo-prompt 🗣️

#### Opis
Strategia **Echo-prompt** polega na zleceniu modelowi językowemu przeformułowania i rozwinięcia otrzymanego zadania, a następnie powtórzenia go na początku generowanej odpowiedzi.  Działa to jako mechanizm weryfikujący, czy model poprawnie zrozumiał intencję zapytania.

#### Przykładowy element prompta
`\"Przeformułuj i rozwiń pytanie, a następnie na nie odpowiedz.\"`

#### Dodatkowe informacje
*   Ułatwia modelowi **pełniejsze zrozumienie** zadanego pytania.
*   **Zwiększa dokładność** odpowiedzi nawet o **+100%**. 💯
*   Stanowi efektywną metodę upewnienia się, że model właściwie interpretuje intencje użytkownika.

### Zaplanuj i rozwiąż (Plan and Solve) ✍️

#### Opis
Strategia **Zaplanuj i rozwiąż** koncentruje się na skłonieniu modelu do rozbicia złożonego zadania na mniejsze, logicznie powiązane kroki. Model w pierwszej kolejności opracowuje plan działania, a następnie systematycznie go realizuje, często uwzględniając określone parametry.

#### Przykładowy element prompta
`\"Zacznijmy od analizy problemu i opracowania planu rozwiązania. Następnie, krok po kroku, zrealizujmy ten plan.\"`

#### Dodatkowe informacje
*   Gwarantuje **poprawę dokładności o +5-15.8%** w porównaniu do metody `zero-shot` (bez przykładów) `Chain-of-Thought`.
*   Sama metoda `Chain-of-Thought`  przynosi **wzrost dokładności o +13% do 41%** w stosunku do standardowego promptowania.
*   Strategia ta jest szczególnie wartościowa przy rozwiązywaniu problemów wymagających **logicznego myślenia** i **sekwencyjnego podejścia**.

### Element emocjonalny ❤️

#### Opis
Strategia **Element emocjonalny** polega na subtelnym wpleceniu aspektów emocjonalnych w prompt, aby zmotywować model do generowania odpowiedzi o wyższej jakości. Sugeruje się, że dodanie elementu emocjonalnego może pozytywnie wpłynąć na zaangażowanie modelu w zadanie.

#### Przykładowy element prompta
`\"To zadanie ma kluczowe znaczenie dla mojego rozwoju zawodowego.\"`

#### Dodatkowe informacje
*   Może skutkować **poprawą dokładności odpowiedzi** w zakresie **od +8% do +115%**.
*   Efektywność elementu emocjonalnego może być **zróżnicowana** i zależeć od specyfiki zadania oraz wykorzystywanego modelu.
*   Kluczowe jest **umiarkowane i rozważne** stosowanie elementów emocjonalnych.

### Podaj przykłady (Few-shot prompting) 💡

#### Opis
Strategia **Podaj przykłady**, znana również jako `few-shot prompting`, opiera się na włączeniu do promptu 3-5 przykładów pytań wraz z oczekiwanymi, prawidłowymi odpowiedziami.  Jej celem jest ukierunkowanie modelu na pożądany styl i format generowanych odpowiedzi.

#### Przykładowy element prompta
`P: \"Jaka jest stolica Włoch?\" O: \"Rzym.\"` (i kolejne przykłady)

#### Dodatkowe informacje
*   Zapewnia **+14% wzrost dokładności odpowiedzi**.
*   **Zwiększa spójność** odpowiedzi z oczekiwaniami użytkownika pod względem stylu i formatu.
*   Przykłady skutecznie pomagają modelowi **zrozumieć pożądany wzorzec odpowiedzi**.

### Przedrostki i separatory 🗂️

#### Opis
Strategia **Przedrostki i separatory** wykorzystuje przedrostki (np. `\"Rola:\"`) lub separatory (np. `###`, `\"\"\"`) w strukturze promptu.  Służy to **jasnemu oznaczaniu** poszczególnych części promptu i **poprawie jego czytelności**.

#### Przykładowy element prompta
`\"Rola: analityk ### Zadanie: Przeanalizuj poniższe dane\"`

#### Dodatkowe informacje
*   **Zwiększają klarowność** formułowanych promptów.
*   Pomagają modelowi w **lepszym zrozumieniu kontekstu** i poszczególnych elementów zadania.
*   Ułatwiają modelowi **rozróżnienie** między różnymi instrukcjami lub informacjami zawartymi w prompcie.

### Podsumowanie (Summarization) 📝

#### Opis
Strategia **Podsumowanie** polega na zwięzłym powtórzeniu kluczowych aspektów promptu, ze szczególnym uwzględnieniem ograniczeń i oczekiwanego formatu odpowiedzi. Jest to szczególnie istotne w przypadku dłuższych promptów, gdzie model może stracić orientację w kontekście.

#### Przykładowy element prompta
`\"Nie udzielaj odpowiedzi, zamiast tego przedstaw wskazówki. Sformatuj swoją odpowiedź w formacie Markdown.\"`

#### Dodatkowe informacje
*   Model może **stracić kontekst**, zwłaszcza gdy kluczowe informacje znajdują się w środkowej części rozbudowanego promptu.
*   Strategia podsumowania pomaga w **utrzymaniu kontekstu** i przypomnieniu modelowi najważniejszych instrukcji.
*   Poprawa dokładności może sięgać **+54%**.

## Podsumowanie Strategii Promptowania 🎯

Przedstawione strategie **promptowania** stanowią zbiór sześciu efektywnych metod, które mogą znacząco wpłynąć na jakość i dokładność odpowiedzi generowanych przez modele językowe.  Strategie te obejmują:

*   **Echo-prompt:**  Weryfikacja zrozumienia zadania przez model poprzez jego przeformułowanie.
*   **Zaplanuj i rozwiąż:**  Podział zadania na logiczne etapy i planowanie procesu rozwiązania.
*   **Element emocjonalny:**  Motywowanie modelu poprzez subtelne wplecenie aspektów emocjonalnych.
*   **Podaj przykłady:**  Dostarczanie modelowi przykładów oczekiwanych odpowiedzi.
*   **Przedrostki i separatory:**  Strukturyzacja promptu w celu zwiększenia jego klarowności.
*   **Podsumowanie:**  Powtarzanie kluczowych instrukcji w rozbudowanych promptach.

Wykorzystanie tych strategii może znacząco **udoskonalić interakcję** z modelami językowymi i umożliwić uzyskiwanie **bardziej precyzyjnych i satysfakcjonujących rezultatów**. Wybór optymalnej strategii powinien być podyktowany specyfiką konkretnego zadania i oczekiwanymi efektami.
___
# File: T1D1 - Materiały dodatkowe - 3. Google Prompting Essentials.md
## Google Prompting Essentials: Notatki i Podsumowanie

## Wprowadzenie

Ten dokument zawiera szczegółowe notatki i podsumowanie kluczowych informacji dotyczących efektywnego `promptowania` modeli generatywnej AI, zgodnie z materiałami Google Prompting Essentials. Materiał skupia się na praktycznych strategiach i schematach, które pomagają w tworzeniu skutecznych `promptów`, wykorzystaniu multimodalności oraz odpowiedzialnym korzystaniu z AI.

## Twórz prompty, które działają

### 5-etapowy schemat formułowania promptu

Aby tworzyć skuteczne `prompty`, warto zastosować 5-etapowy schemat:

* **Zadanie:** Dokładnie określ cel `promptu`, wskazując **personę** (do kogo ma mówić AI) i **format** odpowiedzi.
    * *Przykład:* „Wciel się w rolę doświadczonego copywritera i napisz krótki, chwytliwy slogan reklamowy dla nowej aplikacji mobilnej do nauki języków obcych.”

* **Kontekst:** Dostarcz **wszystkie istotne szczegóły**, które pomogą AI zrozumieć oczekiwania. Im więcej kontekstu, tym lepsza odpowiedź.
    * *Przykład:* „Aplikacja jest skierowana do osób w wieku 18–35 lat, które chcą uczyć się języka hiszpańskiego w sposób interaktywny i zabawny. Główną cechą aplikacji jest wykorzystanie gier i quizów.”

* **Przykład:** Jeśli to możliwe, podaj **przykłady** pożądanych odpowiedzi. To pomaga AI zrozumieć preferowany styl i treść.
    * *Przykład:* „Slogan powinien być krótki, zapadający w pamięć i pozytywnie nastawiony. Na przykład: 'Hiszpański? Z nami to gra!'”

* **Ocena:** **Sprawdź, czy odpowiedź AI jest wystarczająca** i spełnia Twoje oczekiwania.
    * *Kryteria oceny:* Czy slogan jest chwytliwy? Czy pasuje do grupy docelowej? Czy oddaje charakter aplikacji?

* **Modyfikacja:** Jeśli odpowiedź nie jest satysfakcjonująca, **doprecyzuj `prompt`** i wprowadzaj poprawki. Powtarzaj proces, aż uzyskasz pożądany rezultat.
    * *Przykładowa modyfikacja:* „Slogan powinien być jeszcze krótszy, maksymalnie 5 słów, i zawierać element zaskoczenia.”

### W razie wątpliwości — poprawiaj i próbuj dalej

Proces tworzenia `promptów` jest iteracyjny. Kluczowe jest ciągłe eksperymentowanie i udoskonalanie `promptów`. Schemat kołowy „W razie wątpliwości — poprawiaj i próbuj dalej” sugeruje następujące kroki:

* **Wprowadź ograniczenia dla narzędzia generatywnej AI.** Precyzuj zadanie, format, długość odpowiedzi itp.
* **Ponownie przeanalizuj schemat powyżej.** Sprawdź, czy każdy etap został dokładnie przemyślany i zastosowany.
* **Podziel swoje `prompty` na mniejsze części.** Zamiast jednego dużego `promptu`, spróbuj serii mniejszych, bardziej szczegółowych `promptów`.
* **Zmień sposób formułowania podpowiedzi lub przejdź do podobnego zadania.** Eksperymentuj z różnymi sformułowaniami, strukturami zdań, lub spróbuj podejść do problemu z innej strony.

## Znaczenie umiejętności AI w miejscu pracy

* **8 na 10 osób na świecie** uważa, że sztuczna inteligencja znacząco zmieni większość zawodów i branż w ciągu najbliższych 5 lat.¹
* **82% liderów** uważa, że pracownicy z umiejętnościami AI powinni otrzymywać **wyższe wynagrodzenie**.²
* **74% liderów** uważa, że pracownicy posiadający umiejętności AI powinni być **częściej awansowani**.³

Dane te podkreślają rosnące znaczenie umiejętności związanych z AI na rynku pracy. Inwestowanie w rozwój tych kompetencji może przynieść korzyści finansowe i zawodowe.

## Promptowanie multimodalne

**`Promptowanie multimodalne`** polega na łączeniu różnych typów formatów (tekst, obraz, dźwięk) w jednym `prompcie`, co umożliwia bardziej złożone i bogate interakcje z AI.

* **Twórz `prompty` z obrazami:**
    * Załącz **zdjęcie** do `promptu` i zadawaj pytania dotyczące jego treści.
    * **Wprowadź ograniczenia**, aby skupić się na konkretnych elementach obrazu.
    * *Przykład:* Załącz zdjęcie krajobrazu górskiego i zapytaj: „Opisz szczegółowo ten krajobraz, skupiając się na roślinności i typach skał.”

* **Twórz podpowiedzi z dźwiękami:**
    * Załącz **nagranie głosu lub muzyki** i poproś AI o jego opis.
    * Zapewnij **odpowiedni kontekst**, aby AI mogło jak najlepiej zrozumieć nagranie.
    * *Przykład:* Załącz nagranie dźwięku ptaków i zapytaj: „Jakie gatunki ptaków słyszysz na tym nagraniu? Opisz ich śpiew.”

* **Łącz różne formaty:**
    * Podziel się **przykładami w formie tekstu, obrazu lub dźwięku**, aby ukierunkować wynik.
    * **Wyjaśnij, dlaczego każdy z załączonych elementów jest istotny** dla pożądanej odpowiedzi.
    * *Przykład:* Załącz tekst opisujący styl architektoniczny, zdjęcie budynku w tym stylu i zapytaj: „Zaprojektuj budynek mieszkalny w tym stylu, uwzględniając nowoczesne materiały.”

* **Pogłębiaj swoją wiedzę:**
    * **Połącz pisemne `prompty` z dźwiękiem lub obrazami**, aby lepiej zrozumieć to, co widzisz lub słyszysz.
    * *Przykład:* Przeczytaj artykuł o historii sztuki, a następnie załącz zdjęcie obrazu z danej epoki i poproś AI o analizę stylu i technik malarskich.

## Zaprojektuj eksperta AI

Możesz zaprojektować **eksperta AI**, który będzie wspierał Cię w rozwoju umiejętności, współpracy przy projektach, otrzymywaniu feedbacku i wielu innych zadaniach.

* **Określ personę**, którą ma przyjąć narzędzie generatywnej AI (np. mentor, coach, ekspert w danej dziedzinie).
* **Podaj kontekst sytuacyjny** oraz szczegóły rozwoju konwersacji (np. temat projektu, cel rozmowy).
* **Sprecyzuj typ rozmowy** oraz rodzaje interakcji, które ma wspierać narzędzie generatywnej AI (np. udzielanie porad, generowanie pomysłów, krytyczna ocena).
* **Określ słowo-klucz**, którego możesz użyć, aby zakończyć rozmowę (np. „koniec”, „dziękuję”).
* **Poproś narzędzie o kluczowe wnioski z rozmowy** oraz o wskazówki dotyczące obszarów wymagających poprawy.

## Prompt Chaining: Zadania wieloetapowe

**`Prompt chaining`** polega na wykorzystaniu wyniku jednego `promptu` jako kontekstu w kolejnym `prompcie`, co umożliwia realizację zadań wieloetapowych.

* **Poproś narzędzie generatywnej AI o wyjaśnienie, jak doszło do danego wyniku.**
    * Użyj metody **`chain of thought`**, aby AI wyjaśniło swoje rozumowanie krok po kroku. Jest to szczególnie przydatne przy rozwiązywaniu problemów.
    * *Ikona tablicy/flipchartu sugeruje wizualizację procesu myślowego.*

* **Porównuj jednocześnie wyniki:**
    * Poproś narzędzie generatywnej AI, aby przedstawiło **różne opcje**, które rozważa podczas generowania wyniku.
    * Wykorzystaj schemat rozumowania oparty na **drzewie decyzyjnym**. Pozwala to na zrozumienie różnych ścieżek i możliwości.
    * *Ikona wagi szalkowej symbolizuje ważenie różnych opcji i podejmowanie decyzji.*

## Zasady odpowiedzialnego korzystania z AI

Korzystanie z AI powinno być odpowiedzialne i etyczne. Należy wziąć pod uwagę następujące zasady:

* **Weź pod uwagę skutki korzystania ze sztucznej inteligencji** w swojej sytuacji. Zastanów się nad potencjalnymi konsekwencjami i wpływem na innych.
* **Zdobądź zgodę na korzystanie z narzędzia generatywnej AI od osób decyzyjnych** w Twojej organizacji, zanim zaczniesz go używać przy projektach lub w pracy z klientami. Upewnij się, że jest to zgodne z polityką firmy.
* **Rozważ kwestie prywatności i bezpieczeństwa** związane z narzędziem AI, z którego korzystasz. Chroń dane poufne i unikaj naruszeń prywatności.
* **Oceń cały materiał przed jego wykorzystaniem** w swojej pracy lub udostępnieniem go innym. Nie polegaj wyłącznie na AI, zweryfikuj i poprawiaj wyniki.
* **Poinformuj swoich współpracowników i klientów o korzystaniu z narzędzi generatywnej AI** oraz mów otwarcie o tym, do czego Ci służą. Transparentność buduje zaufanie.

## Google Career Certificates

Materiał pochodzi z Google Career Certificates, co sugeruje jego edukacyjny i praktyczny charakter, mający na celu rozwijanie umiejętności zawodowych w zakresie AI.

## Źródła

¹ Google, Ipsos. *Our life with AI: The reality of today and the promise of tomorrow*. Google and Ipsos, January 2024.
² EdX. *Navigating the Workplace in the Age of AI*. EdX, 2023.

## Podsumowanie

Materiały Google Prompting Essentials stanowią kompleksowy przewodnik po efektywnym `promptowaniu` modeli generatywnej AI. Podkreślają znaczenie struktury `promptu` (5-etapowy schemat), iteracyjnego procesu udoskonalania, wykorzystania multimodalności, projektowania ekspertów AI oraz technik `prompt chaining`. Dodatkowo, zwracają uwagę na odpowiedzialne i etyczne korzystanie z AI. Umiejętności te są coraz bardziej cenione na rynku pracy, co potwierdzają statystyki dotyczące wynagrodzeń i awansów dla osób posiadających kompetencje w zakresie AI. Zrozumienie i zastosowanie tych zasad może znacząco zwiększyć efektywność korzystania z narzędzi AI i otworzyć nowe możliwości zawodowe.
___
# File: T1D1 - Sekcja 1. Wprowadzenie do generatywnej AI oraz jak promptować - 1. Podstawy Generatywnej AI.md
## Notatki i Podsumowanie Lekcji: Jak Działa Generatywna Sztuczna Inteligencja

## Wprowadzenie do Generatywnej Sztucznej Inteligencji (Gen AI)

* **Łukasz Olejniczak** z Google Cloud Poland przedstawia lekcję o generatywnej sztucznej inteligencji.
* Nauka obsługi **Gen AI** jest porównywalna do nauki obsługi komputera – każdy może się jej nauczyć.
* **Cel lekcji:** Zrozumienie działania **Gen AI** i efektywne korzystanie z niej.
* **Kluczowe przesłanie:** **Gen AI** wykorzystuje **modele językowe (LLM)**, a odpowiednio sformułowane `prompty` pozwalają kontrolować i wykorzystywać wiedzę tych modeli. Kluczowa jest nasza rola w konstruowaniu pytań i weryfikacji odpowiedzi.

## 01 Jak Działa Generatywna Sztuczna Inteligencja?

* **Gen AI (Generative Artificial Intelligence)** – generatywna sztuczna inteligencja.
    * Rodzaj sztucznej inteligencji, który generuje nowe treści, takie jak teksty, obrazy i multimedia.
* **LLM (Large Language Models)** – duże modele językowe.
    * Stanowią podstawę **Gen AI**.
    * Są trenowane na ogromnych zbiorach tekstu.
    * Rozpoznają wzorce i zależności w języku naturalnym.
    * Umożliwiają komunikację w języku, którym posługujemy się na co dzień.

## Co Konkretnie Potrafią LLM-y?

* **Umiejętności LLM-ów:**
    * Podsumowywanie złożonych tekstów
    * Rozwiązywanie problemów
    * Tłumaczenie na różne języki
    * Edytowanie tekstów
    * Generowanie pomysłów
    * Klasyfikowanie treści

## Prompt Engineering – Klucz do Lepszych Odpowiedzi

* **Prompt engineering:** Proces opracowywania optymalnych podpowiedzi (`promptów`) dla modeli **Gen AI**.
* **Cel `prompt engineeringu`:** Dostarczanie jasnych i konkretnych poleceń oraz kontekstu dla asystenta AI.
* **Przykłady prostych `promptów`:**
    * „Popraw maila”
    * „Przetłumacz tekst”
    * „Skoryguj tekst”

## Podsumowanie Pojęć: AI, Uczenie Maszynowe, LLM, Gen AI, Prompt Engineering

* **AI (Sztuczna Inteligencja):** Najszersze pojęcie.
* **Uczenie Maszynowe:** Metoda **AI**, polegająca na tworzeniu programów uczących się na danych.
* **LLM (Duże Modele Językowe):** Programy trenowane na ogromnych zbiorach tekstów, generujące tekst.
* **Gen AI (Generatywna Sztuczna Inteligencja):** Rodzaj **LLM**, który generuje różnorodne treści.
* **Prompt Engineering:** Metoda ulepszania odpowiedzi **Gen AI** poprzez precyzyjne formułowanie `promptów`.

## Metody Promptowania

* **Różne metody `promptowania`:**
    * **Zero-shot prompting:** `Promptowanie` bez użycia przykładów.
        * Efektywne w przypadku prostych zapytań.
    * **One-shot prompting:** `Promptowanie` z wykorzystaniem pojedynczego przykładu.
    * **Few-shot prompting:** `Promptowanie` oparte na kilku przykładach rozwiązania podobnego problemu.
        * `Shot` = przykład.
        * Bardziej efektywne, gdy oczekujemy konkretnego wyniku i chcemy, aby model zrozumiał nasz sposób myślenia.
        * Dostarczenie kontekstu i przykładów znacząco poprawia jakość rezultatów.

## Praktyczny Przykład Promptowania w Gemini

* **Przykład 1: Zero-shot prompting (brak kontekstu)**
    * `Prompt`: „Podaj mi kilka pomysłów na prezent poniżej 100 zł.”
    * Wynik: Szeroki zakres pomysłów, brak konkretów.
* **Przykład 2: Few-shot prompting (dodanie kontekstu)**
    * `Prompt`: „Podaj mi 4 pomysły na prezent urodzinowy dla dziesięcioletniej dziewczynki, która lubi kolor fioletowy i jest fanką koni i jednorożców. Mój budżet to 100 zł.”
    * Wynik: Konkretne pomysły, dopasowane do zadanego kontekstu (zainteresowania, wiek, budżet).
    * Model wskazuje nawet potencjalne miejsca zakupu.

## Iteracyjne Promptowanie i Ocena Odpowiedzi

* **Iteracja `promptów`:** `Promptowanie` to interaktywny proces, przypominający rozmowę z modelem, który wymaga iteracji i doprecyzowania.
    * Nie należy rezygnować po pierwszej, niezadowalającej odpowiedzi.
    * Warto ponowić zapytanie, dodając więcej przykładów i kontekstu.
    * Czasami konieczne jest rozpoczęcie od nowa lub powrót do podstawowego `promptu`.
* **Kryteria oceny odpowiedzi:**
    * **Dokładność:** Czy uzyskany wynik jest precyzyjny?
    * **Wystarczalność informacji:** Czy odpowiedź zawiera kompletne informacje?
    * **Związek z zadaniem:** Czy wynik jest adekwatny w kontekście projektu/zadania?
    * **Spójność:** Czy odpowiedź jest spójna przy wielokrotnym zadawaniu tego samego pytania?
* **Modyfikacja `promptu`:** Jeśli ocena odpowiedzi ujawni niedociągnięcia, modyfikacja `promptu` może prowadzić do lepszych rezultatów.
* **Analogia do gry komputerowej:** Sukces rzadko przychodzi za pierwszym podejściem – warto próbować do skutku.
* „Kody” w `promptowaniu`: Metody `promptowania` można traktować jako „kody”, które ułatwiają efektywną pracę z **Gen AI**.

## Podsumowanie Lekcji

* Generatywna sztuczna inteligencja (**Gen AI**) opiera się na dużych modelach językowych (**LLM**).
* **Prompt engineering** – umiejętność tworzenia odpowiednich `promptów` – jest kluczem do efektywnego wykorzystania **Gen AI**.
* Istnieją różne metody `promptowania`: **zero-shot**, **one-shot**, **few-shot**.
* Dodawanie **kontekstu i przykładów** (metody **one-shot** i **few-shot**) znacząco podnosi jakość odpowiedzi.
* **Iteracyjne `promptowanie`** i **ocena odpowiedzi** są niezbędne w procesie uzyskiwania pożądanych rezultatów.
* `Promptowanie` to ciągła interakcja z modelem, wymagająca eksperymentowania i precyzji.

Lekcja podkreśla, że każdy może nauczyć się korzystać z generatywnej sztucznej inteligencji, podobnie jak opanował obsługę komputera. Kluczowe jest zrozumienie zasad `prompt engineeringu` i praktyczne stosowanie różnorodnych metod `promptowania`, aby w pełni wykorzystać potencjał **Gen AI**.
___
# File: T1D1 - Sekcja 1. Wprowadzenie do generatywnej AI oraz jak promptować - 2. Metody promptowania.md
## Notatki z lekcji o zaawansowanych technikach promptowania Gen AI

## Wprowadzenie do Gen AI i Promptowania

* Większość osób w branży może nie słyszała o Gen AI.
* Wiele osób próbowało pisać proste prompty, na przykład do maili.
* **Bardzo niewiele osób regularnie wykorzystuje AI w pracy i stosuje zaawansowane techniki promptowania.**
* Skupienie się na zaawansowanych technikach promptowania jest kluczowe, aby w pełni wykorzystać potencjał AI.

## Prompt Chaining - Łańcuch Podpowiedzi

### Definicja `Prompt Chaining`

* **`Prompt chaining`** (ciąg podpowiedzi) - wykorzystanie wyniku jednego prompta jako kontekstu w kolejnym poleceniu dla modelu AI.
* Pomaga modelowi rozwiązywać złożone problemy poprzez podzielenie ich na mniejsze, łatwiejsze do zarządzania kroki.
* Narzędzie AI jest prowadzone przez serię połączonych promptów, z dodawaniem kolejnych zadań i warstw kontekstowych.
* Metoda ta rozbija skomplikowane problemy na mniejsze części i umożliwia ich rozwiązanie krok po kroku.

### Kroki do Stworzenia `Prompt Chaining`

1. **Podziel zadanie na logiczne kroki.**
2. **Stwórz prompt dla każdego kroku.**
3. **Użyj wyników jako danych wejściowych do kolejnych promptów.** - Iteruj proces aż do ukończenia zadania.

### Efektywniejsze Wykorzystanie `Prompt Chaining`

* **Używaj punktów kontrolnych:**
    * Poproś model o krótkie podsumowanie ogólnego celu zapytania, aby upewnić się, że pozostaje na właściwym kursie.
* **Pracuj nad podzadaniami:**
    * Podziel złożone zadania na mniejsze, bardziej konkretne części.
    * Traktuj każde podzadanie jako odrębny etap, zanim przejdziesz do następnego kroku.
* **Podsumuj i przekieruj:**
    * Jeśli model zaczyna odbiegać od zamierzonego celu, podsumuj kluczowe informacje i skieruj go z powrotem na właściwe tory.

## Chain of Thought - Łańcuch Myśli

### Definicja `Chain of Thought`

* **`Chain of thought`** (łańcuch myśli) - sekwencja działań realizowana w ramach jednego, bardziej rozbudowanego prompta.
* Polega na przejściu przez sekwencję logicznych kroków w obrębie jednego zapytania, zamiast formułowania osobnych zapytań dla każdego kroku.
* W promcie przedstawiamy kroki i tok rozumowania potrzebny do rozwiązania podobnego problemu.
* Model ma zastosować analogiczny tok rozumowania i obsłużyć wszystkie kroki w ramach jednego, kompleksowego prompta.

### Korzyści `Chain of Thought`

* **Zwiększa szansę na uzyskanie poprawnej i satysfakcjonującej odpowiedzi.**
* **Szczególnie przydatna w zadaniach wymagających większego zaangażowania intelektualnego i logicznego myślenia.**

## Jak Stworzyć Dobry Prompt pod Obrazek? 🖼️

### Kluczowe Elementy Efektywnego Promptu Obrazkowego

* **Precyzyjny opis:** Jasno i szczegółowo określ, co chcesz uzyskać na obrazie.
* **STYL:**  Określ preferowany styl graficzny, np. fotorealistyczny, akwarelowy, malarski.
* **KOLORYSTYKA:** Zdefiniuj paletę kolorów, np. czarno-biała, pastelowa, jaskrawa.
* **PARAMETRY:** Ustal parametry techniczne, np. proporcje obrazu 16:9, rozdzielczość.
* **PERSPEKTYWA:** Określ punkt widzenia, np. z lotu ptaka, z poziomu oczu, zbliżenie.

## Generatywna AI - Dodatkowe Możliwości i Podsumowanie

* Generatywna AI potrafi generować znacznie więcej niż tylko tekst, w tym:
    * Tabele
    * Prezentacje
    * Maile
    * Arkusze kalkulacyjne
* Więcej informacji o kreatywnych zastosowaniach zostanie omówionych w dalszej części programu.

### Podsumowanie i Zachęta do Działania

* Wiedza o zaawansowanych technikach promptowania może początkowo wydawać się przytłaczająca.
* Dostępny jest pięcioetapowy schemat promptowania do pobrania, który ułatwi rozpoczęcie eksperymentów.
* **Generatywna sztuczna inteligencja sama nie podejmie inicjatywy i nie napisze pierwszego prompta.**
* Inicjatywa i chęć działania leżą po stronie użytkownika.
* Zachęcamy do aktywnego eksperymentowania, odkrywania nowych możliwości i iteracyjnego doskonalenia promptów w pracy z generatywną sztuczną inteligencją.

## Podsumowanie Lekcji

Lekcja koncentruje się na zaawansowanych technikach promptowania w Gen AI, wykraczających poza podstawowe polecenia. Przedstawiono dwie główne techniki: **`prompt chaining`** (ciąg podpowiedzi) i **`chain of thought`** (łańcuch myśli). `Prompt chaining` polega na dzieleniu złożonych zadań na mniejsze kroki i wykorzystywaniu wyników jednego prompta jako kontekstu dla kolejnego. `Chain of thought` to technika, w której cały proces rozwiązywania problemu jest zawarty w jednym, rozbudowanym promcie, naśladując tok rozumowania. Dodatkowo, lekcja omawia kluczowe elementy skutecznego promptowania przy generowaniu obrazów, takie jak precyzyjny opis, styl, kolorystyka, parametry i perspektywa. Podkreślono, że aktywne eksperymentowanie i inicjatywa użytkownika są kluczowe dla efektywnego wykorzystania potencjału generatywnej AI.
___
# File: T1D1 - Sekcja 2. Pomysły na podstawowe wykorzystanie generatywnej AI na przykładzie Gemini - 1. Wstęp.md
## Notatki i Podsumowanie Transkrypcji Wideo "Umiejętności Jutra AI"

## Wprowadzenie

Ten dokument zawiera szczegółowe notatki i podsumowanie transkrypcji wideo zatytułowanego "Umiejętności Jutra AI", zorganizowanego przez Google we współpracy z SGH i pod honorowym patronatem Ministra Cyfryzacji. Wideo koncentruje się na praktycznym wykorzystaniu generatywnej AI, w szczególności modeli językowych, w codziennej pracy. Prezentacja jest prowadzona przez Cezarego Jaroniego i Michała Domagałę, Product Marketing Managerów z Google.

## Główne Tematy i Kluczowe Punkty

### 1. Efektywne `Promptowanie` i `Use Case'y` Generatywnej AI

*   **Kontynuacja tematu promptowania:** Prelegenci zakładają u widzów podstawową wiedzę na temat efektywnego `promptowania`.
*   **Znalezienie odpowiednich `use case'ów`:** Kluczowym zadaniem staje się identyfikacja wartościowych i powtarzalnych przypadków użycia (`use case'ów`) generatywnej AI. Te `use case'y` mają stanowić fundament praktycznego zastosowania AI.
*   **Obszary zastosowań:** Wideo skupia się na trzech obszarach, w których duże modele językowe mogą wspierać codzienną pracę:
    *   Uczenie się i rozumienie
    *   Analizowanie
    *   Tworzenie i innowacje

### 2. Podejście do Wdrażania Generatywnej AI

*   **Unikanie wymuszonych zastosowań:** Praca z dużymi modelami językowymi nie powinna polegać na poszukiwaniu zastosowań "na siłę".
*   **Podejście zadaniowe:** Należy rozpocząć od określenia konkretnych zadań, a następnie rozważyć, w jaki sposób generatywna AI może je wspomóc.
*   **Praktyczna aplikacja:** Chodzi o identyfikację realnych problemów i zadań, które AI może usprawnić lub rozwiązać.

### 3. Narzędzia i Aplikowalność

*   **Gemini od Google:** Przykłady i demonstracje bazują na modelu `Gemini` firmy Google.
*   **Uniwersalność koncepcji:** Prezentowane koncepcje i metody można zastosować również w innych narzędziach generatywnej AI, takich jak Claude czy Chat GPT.

### 4. Praktyczne Rady dotyczące Pracy z Generatywną AI

*   **Proste `prompty` na start:** Zaleca się rozpoczęcie od prostych, nieskomplikowanych `promptów`.
*   **Stopniowa rozbudowa:** `Prompty` powinny być stopniowo rozwijane i ulepszane w miarę potrzeb.
*   **Eksperymentowanie i złożoność:** W razie potrzeby można wprowadzać bardziej złożone `prompty` i eksperymentować z nimi.
*   **Upraszczanie w przypadku problemów:** Jeśli jakość odpowiedzi spada lub pojawiają się trudności, warto uprościć `prompty`.
*   **Nauka przez praktykę:** Praca z AI to proces uczenia się, co działa efektywnie, a co nie. Eksperymentowanie i iteracja są kluczowe.
*   **Klucz do sukcesu: Dobre dane wejściowe:**  Wysokiej jakości dane wejściowe, czyli dobrze sformułowane `prompty`, są fundamentalne dla uzyskania wartościowych rezultatów z AI.

### 5. Podsumowanie Dalszych Kroków

*   **Praktyczne lekcje:** Kolejne lekcje będą miały charakter praktyczny i skupią się na tworzeniu efektywnych `promptów`.
*   **Dobre `prompty` = Dobre dane wejściowe:** Ponowne podkreślenie, że dobre `prompty` są niezbędne do efektywnej pracy z generatywną AI.

## Podsumowanie

Wideo "Umiejętności Jutra AI" stanowi wprowadzenie do praktycznego wykorzystania generatywnej AI w codziennej pracy, z naciskiem na identyfikację konkretnych `use case'ów`. Prelegenci z Google, Cezary Jaroni i Michał Domagała, akcentują zadaniowe podejście –  rozpoznawanie problemów i poszukiwanie wsparcia w AI, zamiast  wymuszania zastosowań. Istotną wskazówką jest rozpoczynanie od prostych `promptów` i ich stopniowe rozwijanie, a także ciągłe eksperymentowanie i uczenie się poprzez interakcję z modelami językowymi. Prezentowane przykłady bazują na `Gemini`, lecz zasady te są uniwersalne i odnoszą się również do innych narzędzi AI. Dalsze kroki koncentrują się na praktycznym tworzeniu efektywnych `promptów`, co stanowi fundament sukcesu w pracy z generatywną AI.
___
# File: T1D1 - Sekcja 2. Pomysły na podstawowe wykorzystanie generatywnej AI na przykładzie Gemini - 2. Uporządkowanie listy zadań.md
## Notatki i Podsumowanie Transkrypcji Wideo: Wykorzystanie Gemini Advanced do Ekstrakcji Esencji z Dokumentów

## Wprowadzenie

Ten materiał wideo prezentuje, w jaki prosty sposób narzędzie **Gemini Advanced** może być użyte do **ekstrakcji esencji z obszernych dokumentów i raportów** oraz **przekształcania ich w zwięzłe scenariusze prezentacji**. Jest to nieocenione, zwłaszcza gdy czas nagli, a szybkie przyswojenie dużej ilości informacji jest kluczowe – na przykład przed ważnym spotkaniem, prezentacją, lub po prostu w celu zrozumienia złożonego tematu, takiego jak rozwój **AI**.

## Demonstracja Praktycznego Zastosowania Gemini Advanced

### Scenariusz Demonstracyjny

Prezentacja skupia się na przygotowaniu do spotkania z zarządem, podczas którego zostanie przedstawiony raport dotyczący wdrożenia **AI** w firmie oraz wynikających z tego korzyści.

### Krok 1: Streszczenie Raportu

1.  **Uruchomienie Gemini Advanced:** Demonstracja rozpoczyna się od otwarcia przeglądarki z aktywnym **Gemini Advanced**.
2.  **Wprowadzenie Promptu:** Użytkownik wprowadza następujące polecenie (prompt) do **Gemini Advanced**:

    > Działasz jako analityk danych. Twoim zadaniem jest sporządzenie streszczenia załączonego raportu, które zostanie zaprezentowane zarządowi.  Przygotuj je w formie 10 punktów, akcentując korzyści z wdrożenia AI dla rozwoju naszej firmy.

3.  **Załączenie Raportu:** Raport jest dołączany do **Gemini Advanced** z **Dysku Google** lub bezpośrednio z dysku komputera.
4.  **Uzyskanie Streszczenia:** **Gemini Advanced** generuje **streszczenie raportu w postaci 10 punktów**. Te punkty zawierają kluczowe informacje i najważniejsze dane z raportu, **koncentrując się na korzyściach płynących z wdrożenia AI**.

### Krok 2: Tworzenie Scenariusza Prezentacji

1.  **Wprowadzenie Kolejnego Promptu:** Po otrzymaniu punktów streszczających raport, użytkownik wprowadza kolejne polecenie, aby **przekształcić te punkty w scenariusz prezentacji**. Celem tego promptu jest wygenerowanie treści na slajdy prezentacji oraz propozycji tytułów.

    > Na podstawie opracowanych punktów, przygotuj treść na slajdy prezentacji, która potrwa maksymalnie 7 minut i zostanie przedstawiona zarządowi. Dla zarządu kluczowe są dane i rekomendacje. Dodatkowo, zaproponuj skrypt do każdego slajdu.

2.  **Otrzymanie Propozycji Scenariusza, Tytułów i Podtytułów:** **Gemini Advanced** generuje:
    *   **Propozycje scenariusza** prezentacji na slajdy.
    *   **Propozycje tytułów** prezentacji.
    *   **Podtytuły** do slajdów.

### Etapy Finalizacji Prezentacji

1.  **Umieszczenie Tytułów na Slajdach:** Użytkownik przenosi zaproponowane tytuły na odpowiednie slajdy prezentacji.
2.  **Dodanie Elementów Wizualnych:** Prezentacja zostaje wzbogacona o **wykresy i dane z raportu**, co uatrakcyjnia ją wizualnie i wzmacnia przekaz.
3.  **Prezentacja Gotowa do Użycia:** Po wykonaniu tych kroków, prezentacja jest w zasadzie gotowa do przedstawienia.

## Podsumowanie i Zachęta do Działania

Wideo demonstruje, jak **Gemini Advanced** może być skutecznym narzędziem do **szybkiego przyswajania dużych ilości danych** i **przygotowywania efektywnych prezentacji**. Proces ten umożliwia **ekstrakcję kluczowych informacji z dokumentów** i **przekształcenie ich w zwięzłą oraz przekonującą formę prezentacji**.

**Zachęta do działania:** Widzowie są zaproszeni do **przetestowania Gemini Advanced** na własnych raportach i dokumentach, które ich interesują, lecz na których analizę dotychczas brakowało czasu. To sposób na **efektywne wykorzystanie narzędzi AI** w celu **oszczędności czasu** i **podniesienia produktywności** w obszarze analizy informacji i tworzenia prezentacji.

## Kluczowe Kompetencje Przyszłości

Prezentacja wpisuje się w koncepcję **`Umiejętności Jutra`**, podkreślając wagę **efektywnego wykorzystania narzędzi AI** w codziennej pracy i edukacji. Umiejętność **szybkiego przyswajania informacji** oraz **efektywnej komunikacji** (na przykład poprzez prezentacje) jest fundamentalna w dynamicznie zmieniającym się świecie.

---
**Organizator:** Google
**Partner Edukacyjny:** SGH
**Patronat Honorowy:** Minister Cyfryzacji
---
___
# File: T1D1 - Sekcja 2. Pomysły na podstawowe wykorzystanie generatywnej AI na przykładzie Gemini - 3. Analiza raportów.md
## Notatki i Podsumowanie Transkrypcji Wideo: Wykorzystanie AI do Ekstrakcji Informacji z Wiadomości

## Wprowadzenie

Ten film instruktażowy prezentuje wykorzystanie sztucznej inteligencji (`AI`), a konkretnie narzędzia `Gemini`, do szybkiego i efektywnego wyciągania kluczowych informacji z wiadomości e-mail, nawet tych bardzo złożonych. Demonstracja skupia się na praktycznym przykładzie analizy oferty oprogramowania, ukazując, jak `AI` może usprawnić proces przetwarzania informacji i przygotowania odpowiedzi.

## Scenariusz Użycia AI w Analizie Wiadomości E-mail

### Problem: Przeciążenie Skrzynki Mailowej i Potrzeba Szybkiej Analizy

- W intensywny dzień pracy, skrzynka mailowa jest przepełniona.
- Szybkie odnalezienie kluczowych informacji w długich wiadomościach od klientów lub partnerów biznesowych jest trudne.
- **Typowy problem:** Potrzeba sprawnego zrozumienia treści oferty oprogramowania dla e-commerce.

### Rozwiązanie: Wykorzystanie Gemini do Analizy Oferty Oprogramowania

- **Narzędzie:** `Gemini` (dostępne na stronie gemini.google.com/app).
- **Przykład:** Analiza wiadomości e-mail z ofertą nowego oprogramowania dla e-commerce.

## Krok 1: Analiza Oferty za Pomocą Gemini

### Prompt 1: Sformułowanie Zapytania do Gemini

- **Wprowadzenie kontekstu:** Użytkownik wciela się w rolę specjalisty ds. oprogramowania w firmie e-commerce.
- **Zadanie dla Gemini:** Podsumowanie załączonej wiadomości e-mail z ofertą oprogramowania w formie listy, z uwzględnieniem potrzeb pięcioosobowego zespołu i poszukiwania optymalnego rozwiązania.
- **Pełny Prompt:** "Jesteś specjalistą do spraw oprogramowania w firmie e-commerce. Otrzymałeś załączony email od dostawcy oprogramowania z nową ofertą. Podsumuj główne punkty oferty w formie listy. Uwzględnij, że poszukujemy optymalnego rozwiązania dla pięcioosobowego zespołu."

### Działanie Użytkownika w Gemini

1. Otwarcie strony gemini.google.com/app.
2. Wprowadzenie sformułowanego promptu.
3. Załączenie zrzutu ekranu wiadomości e-mail z ofertą jako pliku.

### Wynik Działania Gemini

- `Gemini` analizuje ofertę na podstawie promptu i załączonego pliku (zrzutu ekranu wiadomości e-mail).
- **Rezultat:** Przygotowanie podsumowania oferty, uwzględniającego plany subskrypcji oprogramowania i potrzeby pięcioosobowego zespołu.
- **Rekomendacja:** `Gemini` wskazuje konkretny plan subskrypcji jako najbardziej optymalny w danym kontekście.

## Krok 2: Przygotowanie Odpowiedzi na Maila Dostawcy

### Cel: Dalsza Komunikacja z Dostawcą

- Przygotowanie do rozmowy z dostawcą oprogramowania.
- Wykorzystanie `Gemini` jako wsparcia w przygotowaniu odpowiedzi na wiadomość e-mail.
- Określenie kluczowych kwestii, o które należy dopytać dostawcę na tym etapie.

### Prompt 2: Generowanie Propozycji Odpowiedzi i Pytań

- **Kontynuacja Konwersacji z Gemini:** Powrót do okna konwersacji z `Gemini`.
- **Zadanie dla Gemini:** Zaproponowanie pytań do dostawcy w odpowiedzi oraz przygotowanie propozycji treści wiadomości e-mail.
- **Wymagania dotyczące maila:** Utrzymanie tonu korespondencji dostawcy.
- **Pełny Prompt:** "Zaproponuj, o co warto dopytać dostawcę w odpowiedzi. Następnie przygotuj propozycję treści maila, utrzymaną w tonie, w jakim pisał dostawca."

### Wynik Działania Gemini (Krok 2)

- **Kluczowe Kwestie do Poruszenia:** `Gemini` generuje listę kluczowych kwestii, o które warto dopytać dostawcę.
- **Propozycja Maila:** `Gemini` przygotowuje profesjonalną propozycję wiadomości e-mail, gotową do wysłania, utrzymaną w odpowiednim tonie.

## Podsumowanie i Zachęta do Działania

- **Korzyści z Wykorzystania AI (Gemini):** Szybka analiza długich i złożonych wiadomości e-mail, efektywne wyciąganie kluczowych informacji, wsparcie w przygotowaniu odpowiedzi i dalszej komunikacji.
- **Zachęta:** Wykorzystanie `AI` do obsługi zaległych odpowiedzi na maile, ofert współpracy i tym podobnych.
- **Uniwersalność Zastosowania:** Metoda znajduje zastosowanie w analizie różnych typów wiadomości i w rozmaitych kontekstach biznesowych.

## Konkluzja

Film demonstruje praktyczne zastosowanie `AI` (`Gemini`) w codziennej pracy, w szczególności w obszarze zarządzania informacjami w skrzynce mailowej. Ukazuje, w jaki prosty sposób można wykorzystać `AI` do analizy ofert i przygotowania odpowiedzi, oszczędzając czas i zwiększając efektywność. Narzędzia `AI`, takie jak `Gemini`, stanowią znaczące wsparcie dla specjalistów w sprawnym przetwarzaniu informacji i podejmowaniu decyzji.

---
*Materiały edukacyjne "Umiejętności Jutra AI" przygotowane we współpracy z Google, SGH i Ministerstwem Cyfryzacji.*
___
# File: T1D1 - Sekcja 2. Pomysły na podstawowe wykorzystanie generatywnej AI na przykładzie Gemini - 4. Analiza maili.md
## Analiza Danych z Arkuszy Google za pomocą Gemini: Notatki i Podsumowanie

## Wprowadzenie

Ten film instruktażowy pokazuje, jak wykorzystać **Gemini** do analizy danych z arkuszy Google, koncentrując się na wydobywaniu kluczowych informacji. Prezentacja skupia się na analizie feedbacku poszkoleniowego, ale technika ta ma szersze zastosowanie – można ją wykorzystać na przykład do analizy sentymentu opinii o produktach lub firmach.

## Analiza Feedbacku Poszkoleniowego z Gemini

### Krok 1: Przygotowanie Promptu dla Gemini – Rola Analityka Danych

*   Otwórz **Gemini Advanced**.
*   Wpisz **prompt**, w którym **Gemini** wciela się w rolę **analityka danych**.
*   **Zadanie dla Gemini:** Analiza załączonego pliku PDF z odpowiedziami z ankiety feedbackowej po szkoleniu.
*   **Oczekiwane wyniki analizy:**
    *   Stworzenie **podsumowania** feedbacku.
    *   Obliczenie **średniej oceny** szkolenia.
    *   Wskazanie docenionych przez uczestników **mocnych stron** szkolenia.
    *   Wskazanie **obszarów do usprawnienia** w przyszłości.

> "Wciel się w rolę analityka danych. Twoim zadaniem jest analiza załączonego pliku z odpowiedziami na ankietę feedbackową dotyczącą szkolenia. Na podstawie tych danych stwórz podsumowanie, które uwzględni średnią ocenę szkolenia, wskaże mocne strony oraz obszary warte usprawnienia w przyszłości."

### Krok 2: Załączanie Pliku z Feedbackiem

*   W interfejsie **Gemini** wybierz opcję **dodania pliku**.
*   Załącz plik **Ankieta.pdf** z feedbackiem, wybierając go z Dysku Google lub komputera.
*   Plik **Ankieta.pdf** zostanie załadowany do **Gemini**.

### Krok 3: Analiza Danych przez Gemini i Wyniki

*   Po wysłaniu promptu i załączeniu pliku, **Gemini** rozpocznie **analizę danych**.
*   Pojawi się komunikat: "Analizuje... Piszę kod do analizy".
*   **Wyniki analizy** przedstawione przez **Gemini**:
    *   **Średnia ocena szkolenia**.
    *   Informacje o **mocnych stronach** szkolenia, docenionych przez uczestników.
    *   Wskazanie **elementów do usprawnienia** w przyszłości.

> "Jak widać, otrzymaliśmy średnią ocenę szkolenia, informacje o mocnych stronach docenionych przez uczestników oraz wskazówki, co warto usprawnić."

## Wizualizacja Danych Ankietowych – Propozycje Wykresów

### Krok 4: Prompt dla Gemini – Ekspert od Wizualizacji Danych

*   Sformułuj **kolejny prompt** dla **Gemini**, tym razem w roli **eksperta od wizualizacji danych**.
*   **Zadanie dla Gemini:** Przygotowanie propozycji wykresów, które efektywnie zwizualizują dane z ankiety i zależności między nimi.
*   **Ważne:** **Gemini** ma **zaproponować wykresy**, a nie od razu je wygenerować.

> "Jesteś ekspertem od wizualizacji danych. Przygotuj propozycje wykresów, które dobrze zwizualizują dane z ankiety i powiązania między nimi."

### Krok 5: Propozycje Wykresów od Gemini

*   **Gemini** przedstawi **propozycje różnych typów wykresów**, które można wykorzystać do zobrazowania danych z ankiety.
*   Te propozycje pomogą użytkownikowi zrozumieć, jakie wizualizacje będą najbardziej efektywne w prezentacji zebranych danych.

> "Jak widać, otrzymaliśmy propozycje kilku rodzajów wykresów, które możemy wykorzystać do zobrazowania danych uzyskanych z ankiety."

## Zastosowanie Analizy Gemini do Opinii Klientów – Przykład z Google Maps

### Krok 6: Analiza Sentymentu Opinii z Google Maps

*   **Przykładowe ćwiczenie:** Analiza ogólnego sentymentu klientów wobec firmy lub produktów.
*   **Proces:**
    1.  **Skopiuj opinie z Google Maps** dotyczące firmy.
    2.  **Wklej opinie do arkusza Google**.
    3.  **Zapisz arkusz jako plik PDF**.
    4.  **Poproś Gemini o analizę i syntezę** opinii z pliku PDF.
*   **Cel:** Zrozumienie ogólnego nastawienia klientów do firmy lub produktów na podstawie opinii z Google Maps.

> "Jeśli chcesz sprawdzić ogólny sentyment klientów wobec Twojej firmy lub produktów, możesz wykonać przykładowe ćwiczenie: skopiuj opinie z Google Maps na temat firmy, umieść je w arkuszu, zapisz jako PDF, a następnie poproś Gemini o analizę i syntezę, aby dowiedzieć się, co klienci myślą o Twojej firmie lub produktach."

## Podsumowanie

Film instruktażowy demonstruje efektywne wykorzystanie **Gemini** do analizy danych z arkuszy Google. Proces ten obejmuje:

*   **Formułowanie precyzyjnych promptów** dla **Gemini**, definiujących rolę i zadanie (np. analityk danych, ekspert od wizualizacji).
*   **Załączanie plików z danymi** (np. PDF z feedbackiem, PDF z opiniami).
*   **Otrzymywanie analiz i podsumowań** danych, w tym średnich ocen, identyfikacji pozytywnych aspektów i obszarów do usprawnień.
*   **Uzyskiwanie propozycji wizualizacji danych** w postaci sugestii odpowiednich wykresów.

**Gemini** staje się potężnym narzędziem do szybkiej analizy danych i wydobywania z nich kluczowych informacji, co znajduje zastosowanie w różnych kontekstach biznesowych – od analizy feedbacku poszkoleniowego po monitorowanie sentymentu klientów.
___
# File: T1D1 - Sekcja 2. Pomysły na podstawowe wykorzystanie generatywnej AI na przykładzie Gemini - 5. Analiza sentymentu.md
## Notatki i Podsumowanie Lekcji "Umiejętności Jutra AI": Tworzenie Skutecznych Maili Biznesowych z Generatywną AI

## Wprowadzenie

Lekcja "Umiejętności Jutra AI" prezentuje, jak wykorzystać generatywną AI, a konkretnie **Gemini**, do tworzenia skutecznych i angażujących wiadomości e-mail w kontekście biznesowym.  Celem lekcji jest wzmocnienie relacji biznesowych poprzez profesjonalną i efektywną komunikację mailową. Skupia się ona na praktycznym zastosowaniu AI w różnorodnych scenariuszach, takich jak nawiązywanie kontaktu po konferencji, wysyłanie przypomnień oraz przygotowanie do spotkań.

## Tworzenie Pierwszego Maila po Konferencji z Gemini

### Scenariusz:

* Uczestnik konferencji branżowej wraca z wizytówkami i nowymi pomysłami.
* Chce napisać maila do potencjalnego klienta agencji marketingowej.

### Wykorzystanie Gemini:

1. **Uruchom Gemini Advanced.**
2. **Wprowadź `prompt` (polecenie):**
   > "Jesteś specjalistą ds. komunikacji. Potrzebuję pomocy w napisaniu maila do menadżera hotelu w Gdańsku, którego poznałem na konferencji branży hotelarskiej. Rozmawialiśmy o potencjalnej współpracy z moją agencją marketingową. Chciałbym podtrzymać kontakt i zaproponować spotkanie online w celu omówienia szczegółów. Proszę o przyjacielski ton, ale bez natarczywości."

### Rezultat:

* Gemini generuje treść maila w kilka sekund, dostosowaną do kontekstu.
* Wygenerowany mail jest niemal gotowy do wysłania, wymagając jedynie ewentualnych, drobnych korekt.
* **Kluczowe zalety:** szybkość działania i precyzyjne dostosowanie do kontekstu.

## Wysyłanie Maila Przypominającego (Reminder)

### Scenariusz:

* Trzy dni po wysłaniu pierwszego maila – brak odpowiedzi.
* Konieczność wysłania uprzejmego przypomnienia.

### Wykorzystanie Gemini:

1. **Dwie opcje:**
   * **Nowy wątek:** Utworzenie nowego `promptu`, ponownie wprowadzając kontekst pierwszego maila.
   * **Kontynuacja konwersacji:** Powrót do wcześniejszej rozmowy z Gemini i dodanie kolejnego `promptu` (opcja zalecana w lekcji).
2. **Wprowadź `prompt` w istniejącej konwersacji:**
   > "Minęły trzy dni od mojego maila, a ja wciąż nie otrzymałem odpowiedzi. Napisz proszę kulturalne przypomnienie, zachęcające do odpowiedzi na moją poprzednią wiadomość."

### Rezultat:

* Gemini generuje mail przypominający, który:
   * Jest spójny z tonem poprzedniej wiadomości.
   * Zachowuje uprzejmy i nienachalny charakter.
* **Kluczowe zalety:** utrzymanie spójności komunikacji i unikanie nachalności.

## Przygotowanie do Spotkania Online z Gemini

### Scenariusz:

* Otrzymano odpowiedź z propozycją spotkania online.
* Potrzeba efektywnego przygotowania się do rozmowy.

### Wykorzystanie Gemini:

1. **Wprowadź `prompt` w konwersacji:**
   > "Otrzymałem odpowiedź i propozycję spotkania online. Jak najlepiej się do niego przygotować? Zaproponuj proszę kilka tematów, które warto poruszyć, oraz strategie wyróżnienia mojej oferty agencji marketingowej na tle konkurencji."

### Rezultat:

* Gemini generuje konkretne rekomendacje dotyczące:
   * Kluczowych tematów do omówienia podczas spotkania.
   * Sposobów na wyróżnienie oferty agencji marketingowej.
* **Kluczowe zalety:** oszczędność czasu poświęconego na przygotowania, wzrost pewności siebie i profesjonalizmu, a w efekcie – skuteczniejsza komunikacja.

## Podsumowanie i Zachęta do Działania

* Generatywna AI, taka jak **Gemini**, to potężne narzędzie do tworzenia efektywnych maili biznesowych.
* Umożliwia szybkie generowanie wiadomości, precyzyjnie dopasowanych do kontekstu.
* Pomaga w utrzymaniu profesjonalnej i konsekwentnej komunikacji.
* Stanowi wsparcie w przygotowaniu się do kolejnych etapów, takich jak spotkania.
* **Zachęta:** Wypróbuj **Gemini** w praktyce, aby nawiązać nowe kontakty i wzmocnić istniejące relacje biznesowe poprzez tworzenie profesjonalnych wiadomości e-mail.

---

**Podsumowanie lekcji w punktach:**

* **Temat:** Wykorzystanie generatywnej AI (**Gemini**) do tworzenia skutecznych maili biznesowych.
* **Cel:** Wzmocnienie relacji biznesowych poprzez profesjonalną komunikację mailową.
* **Narzędzie:** Gemini Advanced.
* **Scenariusze użycia:**
    * Tworzenie pierwszego maila po konferencji.
    * Wysyłanie maila przypominającego.
    * Przygotowanie do spotkania online.
* **Zalety Gemini:**
    * Szybkość generowania treści.
    * Dostosowanie do kontekstu.
    * Spójność komunikacji.
    * Wsparcie w przygotowaniu i profesjonalizacji działań.
* **Zachęta do działania:** Praktyczne zastosowanie **Gemini** w tworzeniu maili biznesowych.

---

**Kluczowe wnioski:**

> Generatywna AI, w tym **Gemini**, znacząco usprawnia i przyspiesza proces tworzenia skutecznych maili biznesowych, oszczędzając czas i zwiększając efektywność komunikacji. Umożliwia profesjonalne budowanie i podtrzymywanie relacji biznesowych.
___
# File: T1D1 - Sekcja 2. Pomysły na podstawowe wykorzystanie generatywnej AI na przykładzie Gemini - 6. Projektowanie maili.md
## Notatki i Podsumowanie Wideo o Wykorzystaniu AI

## Wprowadzenie do Generatywnej AI

*   W dyskusjach o AI często pojawia się pytanie: **„Jak generatywna AI może nam pomóc?”**
*   Kluczowa zmiana w podejściu do AI:
    *   **Nie chodzi o poszukiwanie na siłę zastosowań** dla GenAI.
    *   **Kluczem jest zrozumienie własnych zadań** i zidentyfikowanie obszarów, w których AI może być wsparciem.
    *   **Współpraca z AI** ma na celu uproszczenie, przyspieszenie i podniesienie jakości pracy.
*   **Cel:** Usprawnienie i podniesienie jakości pracy, a nie wymuszone szukanie zastosowań dla AI.
*   **Wykorzystanie sprawdzonych frameworków organizacji pracy** jest niezwykle istotne.
*   Generatywna AI jest **bardzo przydatna w planowaniu zadań**.

## Praktyczne Zastosowanie Gemini w Planowaniu Zadań

*   **Praktyczne testowanie** wykorzystania AI w organizacji pracy.
*   Przygotowana **lista zadań typowa dla MŚP**.
*   Zadanie dla AI (Gemini):
    *   Wskazanie zadań, w których AI może pomóc.
    *   Uporządkowanie i ustalenie priorytetów zadań dla zwiększenia efektywności.
*   **Wykorzystanie Gemini** (gemini.google.com/app):
    *   Wprowadzenie **promptu**: „Wciel się w rolę eksperta zarządzania czasem i pomóż mi usystematyzować załączoną listę zadań.”
    *   Dodanie **kontekstu**:
        *   „Mam dziś bardzo dużo na głowie i nie wiem, od czego zacząć.”
        *   „Co powinienem zrobić najpierw, a co może poczekać?”
        *   „Wykorzystaj proszę skuteczny framework do priorytetyzacji.”
        *   „Pracę zaczynam o 8:00 i chciałbym uporać się z obowiązkami do 15:00.”
        *   „Podpowiedz, z którym zadaniem i w jaki sposób możesz mi pomóc.”
    *   Załączenie listy zadań (niewidoczna w materiale).
    *   Wysłanie zapytania do Gemini.

## Odpowiedź Gemini i Macierz Eisenhowera

*   **Odpowiedź Gemini**:
    *   Analiza listy zadań.
    *   Zaproponowanie **Macierzy Eisenhowera** jako metody priorytetyzacji.
    *   Podział zadań na cztery kategorie:
        *   **Ważne i Pilne**
        *   **Ważne, ale Niepilne**
        *   **Nieważne, ale Pilne**
        *   **Nieważne i Niepilne**
    *   Dodatkowe wskazówki (nieujęte w materiale).
*   **Korzyści z odpowiedzi Gemini**:
    *   **Zaplanowanie dnia pracy** z użyciem frameworku.
    *   **Wskazanie zadań, w których AI może być pomocne** i sposobu tej pomocy – **szczególnie interesujące i wartościowe** dla użytkownika.

## Dalsza Optymalizacja z AI

*   **Pytanie o dalsze usprawnienia**: „Jak mogę pracować jeszcze efektywniej?”
*   **Prompt do Gemini**: „Jak mogę usprawnić moją pracę? Czy da się coś połączyć, zautomatyzować lub komuś zlecić? Jak mogę zaoszczędzić czas 🕰️?”
*   **Odpowiedź Gemini (sugestie)**:
    *   **Automatyzacja pracy**.
    *   **Delegowanie zadań**.
*   **Ważne**: Sugestie Gemini są **propozycjami** – można je modyfikować i dopasowywać do indywidualnych potrzeb.

## Podsumowanie i Zachęta

*   **Konieczność użycia własnej listy zadań** – w dowolnej formie (zdjęcie, arkusz kalkulacyjny, screen).
*   **Praktyczne sprawdzenie, jak AI może pomóc w zadaniach i ich priorytetyzacji** na własnych przykładach.
*   **Zachęta do eksperymentowania** z AI w organizacji pracy.

## Podsumowanie

Materiał wideo prezentuje praktyczne zastosowanie generatywnej AI, konkretnie narzędzia Gemini, w organizacji pracy. Kluczowym przesłaniem jest zmiana perspektywy na AI: zamiast na siłę szukać zastosowań, należy skupić się na identyfikacji zadań, w których AI może realnie usprawnić pracę, podnosząc jej jakość i tempo. Wideo demonstruje, jak z pomocą Gemini i **Macierzy Eisenhowera** można efektywnie planować dzień, priorytetyzować zadania i wskazywać obszary, gdzie AI może wspierać realizację obowiązków. Sugeruje również dalszą optymalizację poprzez automatyzację i delegowanie zadań. Głównym celem jest zachęcenie do praktycznego wykorzystania AI w codziennej pracy, zaczynając od analizy własnej listy zadań.
___
# File: T1D1 - Sekcja 2. Pomysły na podstawowe wykorzystanie generatywnej AI na przykładzie Gemini - 7. Tworzenie formuł.md
## Notatki i Podsumowanie Wideo: Gemini i Arkusze Kalkulacyjne

## Wprowadzenie

Ten film demonstruje, jak **Gemini** może efektywnie wspierać korzystanie z arkuszy kalkulacyjnych, takich jak Arkusze Google. Głównym celem jest ukazanie, jak szybko i łatwo analizować dane, nawet bez zaawansowanej wiedzy o formułach i funkcjach arkuszy kalkulacyjnych.

## Problem: Analiza Danych Sprzedażowych w Arkuszach Google

- **Scenariusz:** Dysponujemy obszernym arkuszem Google zawierającym dane sprzedażowe (tysiące rekordów).
- **Cel:** Sprawna identyfikacja dni, w których zysk przekroczył określoną wartość, na przykład 3000 zł.
- **Dodatkowe Cele:**
    - Ustalenie liczby takich dni.
    - Zrozumienie czynników wpływających na wysoki zysk w tych dniach.

## Dwa Sposoby Wykorzystania Gemini

Istnieją dwie podstawowe metody wykorzystania **Gemini** do analizy danych z arkuszy kalkulacyjnych:

1. **Przesyłanie Arkusza Danych do Gemini:**
    - Opcja przesłania kompletnego arkusza z danymi sprzedażowymi bezpośrednio do **Gemini**.
    - Możliwość poproszenia **Gemini** o przeprowadzenie krok po kroku przez proces analizy.
    - **Zaleta:** **Gemini** uzyskuje bezpośredni dostęp do danych, co umożliwia dostarczanie precyzyjnych i spersonalizowanych instrukcji.
    - **Potencjalna Wada:** Zagadnienia związane z prywatnością i bezpieczeństwem danych – niektórzy użytkownicy mogą mieć obawy dotyczące udostępniania danych zewnętrznemu narzędziu.

2. **Zapytanie o Instrukcje Bez Udostępniania Danych:**
    - Opcja zwrócenia się do **Gemini** o ogólne wskazówki, jak samodzielnie przeprowadzić analizę w Arkuszach Google.
    - **Zaleta:** Większa kontrola nad danymi i ochrona prywatności, dane pozostają w arkuszu użytkownika.
    - **Wada:** Instrukcje mogą być nieco bardziej ogólne, lecz nadal bardzo przydatne.
    - **Ta opcja jest prezentowana w filmie.**

## Demonstracja Użycia Gemini Advanced (Opcja nr 2)

### Krok 1: Uruchomienie Gemini Advanced i Sformułowanie Zapytania (Promptu)

- Użytkownik korzysta z **Gemini Advanced**.
- Wprowadza **prompt** (zapytanie) do **Gemini**, wcielając się w rolę analityka analizującego arkusz danych sprzedażowych z ostatniego roku.
- **Prompt 1:**
    > Jestem analitykiem i analizuję arkusz z danymi sprzedażowymi z ostatniego roku. Chciałbym szybko odnaleźć daty, w których zysk przekroczył 3000 zł. Jak mogę to zrobić w Arkuszach Google?

### Krok 2: Odpowiedź Gemini i Wybór Metody

- **Gemini** proponuje **kilka sposobów** na zlokalizowanie komórek spełniających kryteria (zysku powyżej 3000 zł).
- Użytkownik może wybrać metodę, która wydaje się najprostsza lub najbardziej odpowiednia do jego potrzeb.

### Krok 3: Kolejne Zapytanie o Wizualizację Danych

- Użytkownik pragnie **wizualnie wyróżnić** znalezione daty w arkuszu, aby ułatwić ich identyfikację.
- Formułuje **kolejny prompt** dotyczący wizualizacji.
- **Prompt 2:**
    > Jak mogę wizualnie oznaczyć te daty kolorem w arkuszu?

### Krok 4: Odpowiedź Gemini z Instrukcjami Wizualizacji

- **Gemini** dostarcza **szczegółowe instrukcje**, jak wizualnie zmodyfikować arkusz.
- Te instrukcje umożliwiają łatwe odnalezienie i zaznaczenie istotnych danych poprzez **pokolorowanie komórek**.

## Podsumowanie i Zachęta do Działania

- **Gemini** umożliwia **łatwą i szybką analizę danych** w arkuszach kalkulacyjnych, nawet dla osób bez specjalistycznej wiedzy.
- Możliwe jest uzyskanie wsparcia w **wyszukiwaniu konkretnych danych** oraz ich **wizualizacji**.
- **Zachęta:** Użytkowników zachęca się do opisywania swoich arkuszy i celów analizy generatywnej AI (**Gemini**), aby otrzymać wskazówki, jak lepiej zrozumieć posiadane dane.
- **Umiejętności Jutra AI:** Projekt edukacyjny (logo widoczne na końcu) związany z rozwojem umiejętności cyfrowych i AI, wspierany przez Google, SGH i Ministerstwo Cyfryzacji.

## Kluczowe Punkty Podsumowania

- **Gemini** wspomaga analizę arkuszy kalkulacyjnych.
- Dwa sposoby użycia: z przesłaniem danych lub bez.
- Demonstracja na przykładzie wyszukiwania dni z zyskiem powyżej 3000 zł i wizualizacji tych dni.
- **Gemini** oferuje instrukcje krok po kroku.
- Upraszcza analizę danych dla osób bez specjalistycznej wiedzy.
- Zachęta do wykorzystania **Gemini** w celu lepszego zrozumienia własnych danych w arkuszach.
___
# File: T1D1 - Sekcja 3. Szersze spojrzenie na AI i bezpieczeństwo - 1. Co poza chatbotami.md
## Sztuczna Inteligencja w Google: Szczegółowe Notatki i Podsumowanie

## Wprowadzenie

Prezentacja Olgi Sztuby z Google omawia sztuczną inteligencję (`AI`) i jej zastosowania, koncentrując się na osiągnięciach i podejściu Google do tej technologii. Celem prezentacji jest demistyfikacja `AI`, ukazanie jej jako narzędzia rozwijanego przez Google od ponad 20 lat, które znajduje zastosowanie w wielu codziennych produktach, przełomowych badaniach naukowych i medycynie.

## Sztuczna Inteligencja w Produktach Google - Długoletnie Doświadczenie

*   **Początki `AI` w Google:** Sztuczna inteligencja nie jest dla Google nowością. Firma rozwija ją już od ponad 20 lat.
*   **Produkty wykorzystujące `AI`:** Wiele popularnych produktów Google korzysta z `AI`:
    *   **Obiektyw Google, Tłumacz Google:** Wykorzystanie systemów uczących się do rozpoznawania znaków i języka.
    *   **Wyszukiwarka Google, Gmail, Mapy:** Elementy `AI` sprawiają, że te narzędzia stają się bardziej intuicyjne i użyteczne dla miliardów użytkowników.
*   **Przykłady zastosowań `AI` w produktach Google:**
    *   **Mapy Google:**
        *   Analiza natężenia ruchu drogowego w czasie rzeczywistym.
        *   Pomoc w unikaniu korków oraz wyszukiwanie tras oszczędnych paliwowo i przyjaznych dla środowiska.
    *   **Gmail:**
        *   Filtry antyspamowe oparte na `AI`.
        *   Skuteczność filtrów antyspamowych na poziomie 99% – wychwytywanie niechcianych i niebezpiecznych wiadomości e-mail 📧.

## Architektura Transformer - Podstawa Sukcesu `AI`

*   **Transformer:** Architektura opracowana przez inżynierów Google w 2017 roku.
*   **Znaczenie Transformera:** Umożliwił stworzenie zaawansowanych modeli językowych zdolnych do rozwiązywania złożonych zadań, takich jak:
    *   Tłumaczenia między językami.
    *   Odpowiedzi na trudne pytania.
    *   Szczegółowe wyjaśnianie rozwiązań krok po kroku.
*   **Powiązanie z GPT:** Litera "T" w skrócie GPT pochodzi od architektury `Transformer`.

## Odpowiedzialne i Pomocne `AI` od Google

*   **Podejście Google do `AI`:** Tworzenie technologii w sposób:
    *   Odpowiedzialny.
    *   Odważny.
    *   Pomocny dla każdego.
*   **`AI` to więcej niż technologie generatywne:** `AI` to szeroka dziedzina wiedzy, wykraczająca poza generowanie tekstu czy obrazów.
*   **`AI` jako dziedzina wiedzy:** Analogia do biologii – `AI` to rozległa dziedzina, obejmująca poddziedziny, takie jak:
    *   Uczenie maszynowe.
    *   Robotyka 🤖.
    *   Sieci neuronowe.
*   **`AI` jako narzędzie:** Przede wszystkim, `AI` jest narzędziem służącym do rozwiązywania problemów, z którymi ludzkość zmaga się od lat, a nawet stuleci.

## `AI` w Nauce - Zmiana Zasad Gry

*   **Białka - Podstawowy Budulec Ciała:**  Pełnią kluczowe funkcje w organizmach żywych.
*   **Struktura Białek:** Zrozumienie trójwymiarowej struktury białek jest kluczowe dla zrozumienia ich działania. Sposób zwijania się białka determinuje jego funkcję, a nieprawidłowe zwijanie może prowadzić do chorób.
*   **Problem Zwijania Białek:** Naukowcy przez 50 lat próbowali przewidzieć sposób zwijania się białek, co stanowiło ogromne wyzwanie.
*   **AlphaFold - Przełom Google DeepMind (2020):** Model `AI`, który rozwiązał problem przewidywania struktury białek.
*   **Biblioteka Białek AlphaFold:** W ciągu kilku miesięcy stworzono bibliotekę 200 milionów struktur białek, obejmującą praktycznie wszystkie znane nauce.
*   **Wykorzystanie AlphaFold:** Baza danych AlphaFold jest wykorzystywana przez ponad milion badaczy na całym świecie w ich pracach.
*   **Nagroda Nobla:** Zespół Google DeepMind pracujący nad AlphaFold otrzymał Nagrodę Nobla w dziedzinie chemii jesienią 2024 roku.
*   **Konkretne Korzyści AlphaFold:** Przyspieszenie prac nad nową szczepionką na malarię oraz postęp w odkrywaniu leków przeciwnowotworowych.

## `AI` Ratujące Życie Tu i Teraz - Medycyna ⚕️

*   **`AI` w Medycynie:** Szczególnie istotne zastosowanie `AI`, przynoszące szybką i wymierną pomoc społeczeństwu.
*   **Retinopatia Cukrzycowa:**
    *   Powikłanie cukrzycy i jedna z głównych przyczyn utraty wzroku 👀.
    *   Rozwija się niemal bezobjawowo.
    *   Wczesne wykrycie stanowi wyzwanie, zwłaszcza w miejscach o ograniczonym dostępie do specjalistów.
*   **`AI` w Diagnostyce Retinopatii Cukrzycowej:** `AI` potrafi wykrywać retinopatię cukrzycową z ponad 90% dokładnością, dorównując, a nawet przewyższając ludzkich ekspertów.
*   **Wdrożenie Algorytmów Google:** Algorytmy `AI` do diagnostyki retinopatii są stosowane w Indiach i Tajlandii, gdzie dostęp do specjalistów jest ograniczony.
*   **Efekt Wdrożenia:** Tysiące przypadków wczesnej diagnozy i szansa na uratowanie wzroku.
*   **Diagnostyka Raka Piersi:** `AI` wspiera również diagnostykę raka piersi poprzez analizę mamografii.
*   **Dokładność `AI` w Diagnostyce Raka Piersi:** Technologia Google osiąga 94% dokładności, wspomagając lekarzy w wykrywaniu nawet najmniejszych zmian.
*   **Zmniejszenie Fałszywie Ujemnych Wyników Mamografii:** `AI` zredukowało liczbę wyników fałszywie ujemnych o 9%.
*   **Skala Problemu Raka Piersi:** Rak piersi jest diagnozowany u 2 milionów osób rocznie na świecie.
*   **Wpływ 9% Redukcji Fałszywie Ujemnych Wyników:** 9% to blisko 200 tysięcy osób rocznie, co odpowiada populacji miasta wielkości Torunia lub Radomia.

## `AI` w Walce z Problemami Globalnymi 🌍

*   **Zmiany Klimatyczne:** `AI` wspiera walkę z globalnymi problemami związanymi ze zmianami klimatycznymi.
*   **Przewidywanie Powodzi i Pożarów Lasów:**
    *   **Flood Hub:** Narzędzie pomagające prognozować powodzie z wyprzedzeniem.
    *   **Wildfire `AI`:** Lokalizuje zagrożenia pożarowe zanim się rozprzestrzenią.
*   **Prognozowanie Pogody ☀️:**
    *   **Jen Cast:** Najnowszy model Google prognozuje pogodę z dokładnością do 97%.
    *   **Zastosowanie Jen Cast:** Kluczowe znaczenie przy przewidywaniu huraganów i cyklonów tropikalnych.
*   **Ochrona Społeczności:** Narzędzia `AI` nie tylko ratują życie, ale także chronią całe społeczności przed katastrofami.

## Zakończenie

*   **`AI` to Więcej Niż Chatboty:** Podkreślenie, że `AI` to znacznie więcej niż tylko chatboty i generatywna sztuczna inteligencja.
*   **Potencjał `AI`:** `AI` to narzędzie dające szansę na rozwiązanie problemów, które jeszcze niedawno wydawały się nie do pokonania.
*   **Ograniczenie `AI`:** Jedynym ograniczeniem w wykorzystaniu `AI` jest ludzka wyobraźnia i pomysłowość w aplikowaniu tej technologii.

## Podsumowanie

Prezentacja Olgi Sztuby skutecznie przedstawia sztuczną inteligencję jako dojrzałą i wszechstronną technologię, rozwijaną przez Google od ponad 20 lat. Podkreślono, że `AI` stanowi integralną część wielu codziennych produktów Google, czyniąc je bardziej intuicyjnymi i użytecznymi. Kluczowym elementem prezentacji jest architektura `Transformer`, będąca fundamentem nowoczesnych modeli językowych. Google akcentuje odpowiedzialne i pomocne podejście do `AI`, demonstrując jej zastosowania w nauce (AlphaFold i przewidywanie struktur białek, Nagroda Nobla), medycynie (diagnostyka retinopatii cukrzycowej i raka piersi) oraz w walce z globalnymi problemami (przewidywanie powodzi, pożarów, pogody). Prezentacja kończy się optymistycznym przesłaniem o ogromnym potencjale `AI` jako narzędzia do rozwiązywania największych wyzwań ludzkości, gdzie jedynym ograniczeniem jest ludzka wyobraźnia. Sztuczna inteligencja jest prezentowana nie tylko jako technologia przyszłości, lecz jako realne i działające narzędzie, które już teraz przynosi wymierne korzyści w wielu dziedzinach życia.
___
# File: T1D1 - Sekcja 3. Szersze spojrzenie na AI i bezpieczeństwo - 2. Zagadnienia w obszarze bezpieczeństwa i prywatności danych.md
## Prywatność i Bezpieczeństwo Danych w Narzędziach AI

## Wprowadzenie

Prezentacja Artura Kulińskiego, Customer Engineer w Google Cloud Security, omawia kluczowe aspekty `prywatności` i `bezpieczeństwa danych` w kontekście narzędzi `sztucznej inteligencji` (AI). Podkreśla znaczenie świadomego korzystania z AI oraz ochrony danych osobowych w aplikacjach AI, zarówno w życiu prywatnym, jak i zawodowym.

## Co to jest Prywatność i Bezpieczeństwo?

- **Prywatność:** Prawo do kontroli nad sposobem, w jaki dane są zbierane, przechowywane i wykorzystywane.
- **Bezpieczeństwo:** Ochrona danych przed nieautoryzowanym dostępem, modyfikacją lub utratą. Obejmuje zapobieganie atakom, kradzieży danych i wprowadzaniu szkodliwych danych do systemów AI.

## Podstawowe Zasady Ochrony Danych w Narzędziach AI

### Konieczność i Bezpieczeństwo Udostępniania Danych

- Zastanów się, czy wprowadzenie danych do narzędzia online jest **konieczne** i **bezpieczne**.
- Dotyczy to także narzędzi AI.
- Nie wprowadzaj danych **niepotrzebnych** do uzyskania wyniku lub skorzystania z funkcji.

### Szczególna Uważność na Dane Osobowe i Wrażliwe

- Zachowaj szczególną ostrożność w przypadku **danych osobowych i wrażliwych**, takich jak:
    - Imię i nazwisko
    - Dane adresowe
    - Numer telefonu 📞
    - Dokumenty medyczne 🩺
    - Numery kart kredytowych 💳

- **Dlaczego to ważne?** Aby uniknąć:
    - Ujawnienia danych w wyniku wycieku
    - Nieautoryzowanego wykorzystania
    - Podszywania się
    - Oszustw ⚠️

### Zapoznanie się z Polityką Prywatności

- Jeśli podanie danych jest **uzasadnione i konieczne**:
    - **Koniecznie** zapoznaj się z **polityką prywatności** i zasadami wykorzystywania danych.
    - W przypadku **wątpliwości** co do wiarygodności autorów lub treści polityki:
        - **Zrezygnuj** z korzystania z aplikacji.
        - Poszukaj **alternatywnego rozwiązania**.

## Jak Narzędzia AI Wykorzystują Wprowadzane Dane?

### Brak Uniwersalnej Odpowiedzi

- Nie istnieje uniwersalna odpowiedź na pytanie o to, co dzieje się z danymi wprowadzonymi do AI.
- Wiele zależy od **twórców aplikacji**.

### Znaczenie Polityki Prywatności

- **Konieczne jest zapoznanie się z polityką prywatności** obowiązującą dla używanych narzędzi.
- Polityka prywatności powinna **dokładnie opisywać**, co dzieje się z danymi.

### Gwarancje Polityki Prywatności

- Zasady prywatności powinny gwarantować, że:
    - Dane **nie są automatycznie udostępniane innym użytkownikom**.
    - Modele AI **nie wykorzystują danych użytkowników do trenowania** bez ich wiedzy i zgody.

### Przykłady Wykorzystania Danych

- **Przetwarzanie Zapytania:** Wprowadzone dane (np. opis projektu, preferencje) są używane **wyłącznie do przetworzenia danego zapytania**.
    - Dane są przechowywane w ramach interakcji z narzędziem AI.
    - **Nie powinny być udostępniane innym osobom** ani trafiać do publicznych baz danych.

- **Ulepszanie Jakości Odpowiedzi (Odpowiedzialne Trenowanie Modeli AI):**
    - Modele AI mogą korzystać z danych użytkowników w celu ulepszania jakości odpowiedzi.
    - Dzieje się to **bez łączenia danych z indywidualnym kontem** i **bez umieszczania ich w bazach danych dostępnych dla innych**.

## Bezpieczeństwo Danych i Konsekwencje Wycieków

- Nieodpowiednio chronione dane mogą zostać ujawnione w wyniku **kradzieży lub wycieku**.
- Poważne konsekwencje to m.in.:
    - Kradzież tożsamości
    - Nadużycia finansowe 💸

- **Dbanie o bezpieczeństwo danych w aplikacjach AI jest kluczowe.**

## Co Możesz Zrobić w Zakresie Bezpieczeństwa Danych?

### Czytaj Polityki Prywatności

- **Przed rozpoczęciem korzystania z aplikacji AI**:
    - Sprawdź, **jakie dane są zbierane**.
    - Sprawdź, **w jaki sposób dane są wykorzystywane**.

- **Przykład Gemini (Google):**
    - Google informuje, że przechowuje dane przez określony czas i umożliwia ich usuwanie.
    - Szczegółowe informacje są dostępne w **centrum prywatności** aplikacji Gemini.

### Używaj Odpowiednich Ustawień Prywatności

- Aplikacje, które szanują prywatność danych, zazwyczaj pozwalają na **pełną kontrolę** nad danymi.

### Unikaj Wprowadzania Danych Wrażliwych

- **Ogranicz do minimum** przekazywanie prywatnych danych (takich jak adresy e-mail 📧, dane finansowe).
- W miarę możliwości używaj **danych ogólnych**, które nie stanowią zagrożenia w przypadku potencjalnego wycieku.

## Różnice w Odpowiedzialności za Dane: Konsument vs. Przedsiębiorstwo

### Rozdzielenie Sfery Prywatnej i Zawodowej w Świecie Cyfrowym

- **Unikaj łączenia życia prywatnego i zawodowego** w sferze cyfrowej.
- **Nie używaj kont prywatnych i aplikacji do przetwarzania danych biznesowych**.

### Różnice w Regulacjach i Wymaganiach

- Dane biznesowe mogą podlegać **odrębnym regulacjom prawnym**.
- Dane biznesowe mogą **nie stanowić Twojej własności**.
- Dane biznesowe mogą wymagać **innych standardów bezpieczeństwa i prywatności** niż dane prywatne.

### Rozwiązania AI dla Biznesu

- Rozwiązania AI dla biznesu często oferują **bardziej zaawansowane mechanizmy gromadzenia i przetwarzania danych** niż rozwiązania konsumenckie.
- **Przykład: Google Cloud Vertex AI** – oferuje zaawansowane metody kontroli suwerenności danych.

### Prywatność Generatywnej AI w Google Workspace

- Technologie Google Workspace zostały zaprojektowane tak, aby treści (wiadomości e-mail, dokumenty) **nie były udostępniane bez zgody użytkownika**.
- Dotyczy to **wszystkich produktów Google Workspace** (Gmail, Dokumenty Google, Arkusze, Dysk, Kalendarz 📅).
- **Dane pozostają w Workspace i nie są wykorzystywane do trenowania ani ulepszania generatywnej AI**, w tym dużych modeli językowych.

## Podsumowanie i Kluczowe Działania

### Bezpieczeństwo i Prywatność Kluczowe w Kontekście AI

- Aktywne dbanie o dane jest kluczowe dla każdego użytkownika.
- Ważne jest zrozumienie, w jaki sposób narzędzia AI zbierają i wykorzystują informacje.
- Minimalizacja ryzyka utraty kontroli i niepożądanego ujawnienia danych.

### Proste i Szybkie Działania dla Lepszej Ochrony Danych

1. **Zaktualizuj hasła** i **włącz weryfikację dwuetapową**.
    - Ochrona tożsamości cyfrowej to priorytet.
2. **Sprawdź ustawienia prywatności** w aplikacjach AI.
    - Wyłącz funkcje zbierające niepotrzebne dane.
3. **Dowiedz się o zasadach stosowania AI w firmie** i dostosuj się do nich.
4. **Przejrzyj dokumentację prywatności**.
    - Zapoznaj się z polityką prywatności i warunkami użytkowania **przed** rozpoczęciem korzystania z nowych narzędzi AI.
    - Dowiedz się, jakie dane są zbierane i jak są wykorzystywane.
5. **Regularnie usuwaj historyczne dane**.
    - W sekcji zarządzania danymi aplikacji AI usuń zbędne rozmowy, dane i aktywności.
    - Ograniczenie ilości przechowywanych informacji zwiększa bezpieczeństwo.

## Podsumowanie

Prezentacja Artura Kulińskiego podkreśla kluczową rolę `prywatności` i `bezpieczeństwa danych` w erze narzędzi AI. Świadome korzystanie z tych technologii, zrozumienie zasad gromadzenia i wykorzystywania danych oraz aktywne działania na rzecz ochrony informacji są niezwykle istotne. Zaleca się szczególną ostrożność przy udostępnianiu danych osobowych, regularne zapoznawanie się z politykami prywatności, korzystanie z dostępnych ustawień prywatności oraz rozdzielenie sfery prywatnej i zawodowej w kontekście danych cyfrowych. Wdrożenie prostych kroków, takich jak aktualizacja haseł i regularne usuwanie danych, może znacząco zwiększyć poziom bezpieczeństwa i kontroli nad naszymi danymi w świecie AI.
___
# File: T1D1 - Wyzwanie - Zadania dla Ciebie.md
## Notatki i Podsumowanie do Zadania Praktycznego z Kursu

Niniejszy dokument zawiera szczegółowe notatki i podsumowanie zadania praktycznego przedstawionego w transkrypcji. Zadanie ma na celu utrwalenie wiedzy z kursu poprzez samodzielne ćwiczenie kluczowych zagadnień związanych z generatywną sztuczną inteligencją, konkretnie z narzędziem **Gemini**.

## Wprowadzenie do Zadania Praktycznego

Zadanie praktyczne zostało przygotowane, aby umożliwić uczestnikom kursu samodzielne przećwiczenie kluczowych zagadnień. Jego realizacja krok po kroku ma na celu utrwalenie wiedzy teoretycznej oraz nauczenie praktycznego wykorzystania zdobytych umiejętności.

## Wyzwanie Pierwsze: Identyfikacja Zadań

### Krok 1: Zidentyfikuj swoje zadania

- **Zastanów się nad swoimi codziennymi lub tygodniowymi zadaniami.**
- Jakie czynności wykonujesz regularnie?
- Przykładowe zadania:
    - Analiza danych w arkuszach kalkulacyjnych
    - Redagowanie e-maili
    - Podsumowywanie raportów
    - Zarządzanie listami zadań

### Krok 2: Wybierz trzy zadania

- **Wybierz trzy różnorodne zadania**, które chciałbyś zoptymalizować za pomocą generatywnej sztucznej inteligencji.
- **Idealnym wyborem będą zadania** z co najmniej dwóch z trzech obszarów:
    - **Uczenie się i rozumienie**
    - **Analizowanie**
    - **Tworzenie i wymyślanie**

### Krok 3: Wykorzystaj **Gemini** do pomocy

- **Wykorzystaj narzędzie Gemini** w każdym z trzech wybranych zadań.
- **Postępuj zgodnie z zaleceniami z materiałów szkoleniowych:**
    - Zacznij od **prostych promptów**.
    - **Stopniowo rozwijaj** prompty.

### Krok 4: Sposoby wykorzystania **Gemini**

- **Przykładowe zastosowania Gemini:**
    - **Podsumowanie i analiza**
    - **Formuły i dane** (arkusze kalkulacyjne)
    - **Redagowanie i komunikacja** (np. e-maile)
    - **Organizacja i planowanie**

### Krok 5: Udokumentuj proces

- **Zapisuj używane prompty oraz odpowiedzi** uzyskane od **Gemini**.
- **Skup się na procesie, a nie tylko na wynikach.**
- Refleksja nad przebiegiem pracy jest kluczowa dla procesu uczenia się.

### Krok 6: Podsumuj i podziel się doświadczeniami

- **Przygotuj się do podzielenia się swoimi doświadczeniami.**
- **Zastanów się, czego nauczyłeś się** o wykorzystaniu narzędzi AI do zwiększenia produktywności.

## Podsumowanie Zadania Praktycznego

Zadanie praktyczne polega na wykorzystaniu narzędzia **Gemini** do optymalizacji trzech wybranych zadań z życia codziennego lub zawodowego. Kluczowe kroki obejmują: identyfikację zadań, wybór trzech z nich z różnych obszarów (uczenie się, analiza, tworzenie), użycie **Gemini** do wsparcia ich realizacji, dokumentowanie procesu poprzez zapisywanie promptów i odpowiedzi, a na koniec – podsumowanie i dzielenie się zdobytymi doświadczeniami. Ważne jest eksperymentowanie z różnymi promptami, rozpoczynając od prostych i stopniowo je rozbudowując. Należy skupić się na procesie uczenia się i zrozumieniu możliwości narzędzia **Gemini**, a nie tylko na osiągnięciu konkretnych rezultatów.  Celem zadania jest praktyczne zastosowanie wiedzy z kursu oraz zrozumienie, w jaki sposób AI może zwiększyć produktywność w różnych dziedzinach.