# File: T4D1 - Lekcje wideo - 3. Narzędzia audio-video ViGenAir.md
## Notatki i Podsumowanie Transkrypcji Wideo: `Umiejętności Jutra AI`

## Wprowadzenie 🚀

Tematem lekcji jest wykorzystanie istniejących zasobów wideo za pomocą sztucznej inteligencji Gemini. Narzędzie **Visioner** umożliwia ponowne wykorzystanie, skracanie i modyfikację materiałów wideo, w tym dodawanie nowych ścieżek dźwiękowych lub zmianę języka ścieżki dźwiękowej na potrzeby rynków zagranicznych.

## Narzędzie `Visioner` ⚙️

- **Cel:** Efektywne wykorzystanie istniejących zasobów wideo.
- **Funkcje:**
    - Skracanie wideo z zachowaniem logicznej spójności.
    - Ponowne wykorzystanie istniejących materiałów.
    - Dodawanie nowej ścieżki dźwiękowej.
    - Zmiana języka ścieżki dźwiękowej.
- **Łatwość Obsługi:** Narzędzie jest intuicyjne i proste w użyciu.

## Wymagania Wstępne do Korzystania z `Visioner` 🔑

Aby rozpocząć pracę z Visionerem, niezbędne jest posiadanie:

- Użytkownika z dostępem do `Google Cloud Platform`.
- Projektu cloudowego z włączonym `Vertex AI API`.

### Aktywacja `Vertex AI API`

1. Przejdź na stronę `Google Cloud`.
2. W polu wyszukiwania wpisz "`Vertex API`" i naciśnij `Enter`.
3. W wynikach wyszukiwania wybierz "`Vertex AI API`".
4. Kliknij niebieski przycisk "`Enable`" (Włącz), aby aktywować API.

Po wykonaniu tych kroków projekt jest gotowy do pracy z Visionerem.

### Dostęp Użytkowników 👤

- Użytkownicy Visionera muszą posiadać odpowiednie uprawnienia dostępu do projektu cloudowego.
- Szczegółowe informacje na temat dostępu można znaleźć na stronie poświęconej rozwiązaniu Visioner.

## Interfejs `Visioner` 🖥️

Po zainstalowaniu Visionera (instrukcje dostępne na stronie), użytkownik zobaczy interfejs składający się z następujących sekcji:

1. **Wybór Wideo:**
    - Umożliwia wybór filmu wideo do edycji.
    - Dostępne jest rozwijane menu z wcześniej załadowanymi filmami.
    - Wykorzystanie wcześniej załadowanych wideo przyspiesza proces, ponieważ są one już przetworzone i gotowe do edycji w `backecie` cloudowym.

2. **Edycja (początkowo nieaktywna):**
    - Zakładka przeznaczona do edycji wideo.
    - Staje się aktywna po wybraniu i załadowaniu wideo.

3. **Renderowanie:**
    - Zakładka służąca do renderowania gotowego wideo po edycji.

## Praca z Filmami w `Visioner` 🎬

### Wybór Filmu

- Zalecana długość filmów: **około minuty lub więcej**.
    - Dłuższe filmy zapewniają AI wystarczającą ilość materiału do tworzenia lepszych kreacji.

### Opcja "`Analyze Voice Over`" 🎤

- **`Tickbox` "`Analyze Voice Over`" (Analizuj Ścieżkę Dźwiękową):**
    - Określa, czy Visioner ma dzielić sceny w oparciu o ścieżkę dźwiękową.
    - **Włączone:** Sceny dzielone są z uwzględnieniem ścieżki dźwiękowej, co pozwala zachować logiczną ciągłość.
        - Przykład: Scena zamykania drzwi samochodu i odchodzenia osoby zakończy się w momencie dźwięku zamykanych drzwi.
    - **Wyłączone:** Sceny dzielone są na podstawie wizualnych zmian w obrazie.
        - Przykład: Samochód i osoba odchodząca od samochodu będą stanowić oddzielne sceny.

### Przesyłanie Wideo ("`Upload wideo`") 📤

- Po wybraniu opcji analizy ścieżki dźwiękowej (lub pominięciu jej), kliknij "`Upload wideo`" (Prześlij wideo).
- Rozpocznie się proces ładowania i analizy wideo.

## Korzyści z Wykorzystania `Visioner` ✨

- Efektywne wykorzystanie istniejących zasobów wideo.
- Możliwość skracania wideo do krótszych formatów.
- Potencjalna poprawa jakości tworzonych materiałów.
- **`Assessment ABCD`:** Każda kreacja stworzona za pomocą Visionera podlega ocenie w frameworku `ABCD`, co pomaga w weryfikacji spełnienia wymogów jakościowych.

## Podsumowanie 📝

Visioner to narzędzie oparte na sztucznej inteligencji Gemini, które umożliwia efektywne wykorzystanie i modyfikację istniejących zasobów wideo. Pozwala na skracanie filmów, zmianę ścieżek dźwiękowych i potencjalne podniesienie jakości kreacji. Aby korzystać z Visionera, niezbędne jest konto `Google Cloud Platform` z aktywnym `Vertex AI API`. Narzędzie oferuje prosty interfejs i opcje dostosowania analizy wideo do potrzeb użytkownika, co czyni je użytecznym rozwiązaniem do **repurposingu** treści wideo.
___
# File: T4D1 - Lekcje wideo - 4. Narzędzia audio-video Ariel.md
## Umiejętności Jutra AI - Ariel: Notatki i Podsumowanie

## Wprowadzenie do **Ariel**

- **Ariel** to narzędzie oparte na **sztucznej inteligencji (AI)** 🤖, które umożliwia zaawansowaną manipulację ścieżkami dźwiękowymi w wideo 🎬.
- **Dwa główne zastosowania Ariela:**
    - Dodawanie ścieżki dźwiękowej do wideo, które pierwotnie jej nie zawierało.
    - Zmiana istniejącej ścieżki dźwiękowej w wideo na inny język, na przykład dubbing z polskiego na czeski lub angielski.
- To intuicyjne narzędzie pozwala na szybką i efektywną zmianę języka audio w filmach.

## Technologia **Ariel**

- **Ariel** wykorzystuje zaawansowane technologie **AI** do generowania i modyfikacji ścieżek dźwiękowych:
    - **Gemini:** Wykorzystywany do **Text to Speech (TTS)**, czyli syntezy mowy z tekstu.
    - **Platformy open source:** Dodatkowe platformy open source wspierają **Gemini**, aby zapewnić najwyższą jakość **AI voice over**.
    - **Hugging Face:** Biblioteka open source, z której korzysta **Ariel**. Wymaga tokena dostępu.
    - **Eleven Labs** (opcjonalnie): Platforma umożliwiająca klonowanie głosów lektorów. Opcja dla użytkowników preferujących niestandardowe głosy zamiast domyślnych głosów Google. **Eleven Labs** wymaga rejestracji i abonamentu do użytku komercyjnego 💰.

## Obsługiwane Języki 🌐

- **Ariel** aktualnie obsługuje **46 języków**.
- Pełna lista wspieranych języków jest dostępna na **GitHub** w instrukcji instalacji Ariela.
- **Kluczowe:** **Ariel** wspiera języki Europy Środkowo-Wschodniej, w tym:
    - Polski 🇵🇱
    - Czeski 🇨🇿
    - Słowacki 🇸🇰
    - Węgierski 🇭🇺
    - Niemiecki 🇩🇪
    - oraz inne języki regionu.
- Dzięki temu **Ariel** jest niezwykle użyteczny na rynkach lokalnych.

## Wymagania do Korzystania z **Ariel**

- Aby rozpocząć pracę z Arielem, potrzebne są następujące elementy:
    - **Dostęp do Google Cloud Platform (GCP):** Podobnie jak w przypadku poprzedniego rozwiązania (nie sprecyzowano w tym fragmencie).
    - **Biblioteki open source:**
        - **Hugging Face:** Wymagany token dostępu. Instrukcja uzyskania tokena znajduje się na GitHubie.
        - **Eleven Labs** (opcjonalnie): Dla niestandardowych głosów lektorskich. Wymaga rejestracji i abonamentu komercyjnego.

## Demonstracja **Ariel** w **Colab**

- **Ariel** działa na platformie **Colab**, przypominającej stronę internetową z interaktywnym formularzem i komendami.
- Poniżej przedstawiono proces korzystania z Ariela krok po kroku:

    ### Podstawowa Konfiguracja (**Setup**)

    - Pierwszym krokiem jest **podstawowy setup**.
    - Należy kliknąć przycisk "play" ▶️ i poczekać na zakończenie procesu.
    - **Setup** jest wykonywany jednorazowo, co oszczędza czas podczas demonstracji.

    ### Konfiguracja Inputu

    - Kolejny etap to **konfiguracja inputu**, czyli danych wejściowych.
    - Wymagane pola:
        - **Projekt Cloud'owy (Google Cloud Project):** Należy wprowadzić ID projektu **GCP**.
        - **Region:** Wybór regionu **Google Cloud**.
            - Dostępna rozwijana lista regionów.
            - Dla projektów **multi-regionalnych** zalecane są regiony amerykańskie 🇺🇸.
            - Dla projektów z danymi w **Europie** rekomenduje się wybór europejskich centrów danych: Frankfurt 🇩🇪, Londyn 🇬🇧, Belgia 🇧🇪, Finlandia 🇫🇮.
        - **Nazwa reklamodawcy:** Wpisanie nazwy reklamodawcy (np. Google Pixel).
            - Informuje **Gemini'a**, aby nie tłumaczył tej nazwy.
        - **Język ścieżki dźwiękowej wejściowej:** Wybór języka oryginalnej ścieżki dźwiękowej (np. angielski 🇬🇧).
            - Rozwijana lista języków i akcentów (np. angielski brytyjski).
        - **Język ścieżki dźwiękowej docelowej:** Wybór języka, na który ma zostać przetłumaczona ścieżka (np. polski 🇵🇱).
        - **Liczba speakerów (mówców) w wideo:** Określenie liczby osób mówiących w wideo (np. 1 speaker).
        - **Hugging Face Token:** Wklejenie tokena pobranego z platformy **Hugging Face**. Instrukcja dostępna na GitHubie.
    - Po wypełnieniu wszystkich pól, należy kliknąć "play" ▶️ i poczekać na zakończenie procesu.
    - Pojawi się okno z prośbą o dostęp do credentiali Google'owych – należy kliknąć "Allow" i wybrać konto Google.
    - Po pomyślnej autoryzacji pojawi się zielony "tick" ✅.

    ### Konfiguracja Dubbingu

    - **Dla wideo bez oryginalnej ścieżki dźwiękowej:**
        - Należy podać **link do Google Sheets** zawierającego sekwencje tekstowe do wypowiedzenia.
        - Przykładowe linki i format tabeli są dostępne na GitHubie.
        - Tabele przygotowane dla **Google Speech** (syntezatory mowy Google) i **Eleven Labs**.
    - **Struktura tabeli Google Sheets:**
        - **Start time:** Czas rozpoczęcia sekwencji dźwiękowej.
        - **End time:** Czas zakończenia sekwencji dźwiękowej.
        - **Text:** Tekst do wypowiedzenia.
        - **Speaker ID:** ID mówcy (ważne przy dialogach, mniej istotne przy jednym mówcy, ale wymagane).
        - **Płeć:** Płeć mówcy (kobieta/mężczyzna).
        - **Głos:** Nazwa głosu (np. Charlie). W przypadku własnego głosu z **Eleven Labs**, należy wkleić ID głosu.
        - **Speed adjustment (dostosowanie prędkości):**  `true` lub `false`.
            - `true` - dostosowanie prędkości mowy, aby tekst zmieścił się w danej ramie czasowej (kluczowe przy tłumaczeniach, gdzie długość tekstu może się różnić).
        - **Style:** Ustawienie stylu głosu (zalecane ustawienia domyślne).
        - **User speaker boost:** Wzmocnienie głosu użytkownika (zalecane ustawienia domyślne).

    ### Wyświetlanie Outputu

    - Po wyrenderowaniu wideo, **Ariel** zapyta, czy wyświetlić output.
    - Po potwierdzeniu, wideo zostanie odtworzone bezpośrednio w **Colab**.
    - Umożliwia to natychmiastowe obejrzenie efektów dubbingu.
    - Przykład wideo: reklama Google Pixel 6 z dubbingiem.

## Konfiguracja Dubbingu (Dodatkowe Wyjaśnienie)

- Dodatkowe objaśnienie konfiguracji dubbingu na przykładzie tłumaczenia tekstu.
- Możliwość wpisania tekstu do przetłumaczenia bezpośrednio w **Colab** (bez nawiasów klamrowych i cudzysłowów, np. "translated text").
- Wykorzystanie **Gemini** do tłumaczenia tekstu (np. prompt "yes").
- Prezentacja przetłumaczonego tekstu (np. "make this phone what it is" -> "zrób z tego telefonu to, czym jest").
- Wyświetlenie sekwencji ścieżek dźwiękowych w formie tabeli:
    - **Czas startu i końca:** Moment rozpoczęcia i zakończenia danej frazy.
    - **Tekst (rozumiany przez Gemini):** Tekst oryginalnej ścieżki dźwiękowej rozpoznany przez **AI**.
    - **For dubbing (Prawda/Fałsz):** Flaga określająca, czy dana sekwencja ma być dubbingowana (`true`) czy pominięta (`false`).
        - Umożliwia wyłączenie dubbingu dla konkretnych fraz (np. nazw własnych jak "Google Pixel").
    - **Speaker ID:** ID mówcy.
    - **Płeć:** Płeć mówcy.
    - **Tłumaczony tekst:** Przetłumaczona wersja tekstu.
    - Przykłady tłumaczeń: "this" -> "to", "This is about you" -> "To jest o tobie", "And you're you're not so routine" -> "i nie jesteś tak rutynowy".

## Podsumowanie

- **Ariel** to zaawansowane, a zarazem proste w obsłudze narzędzie **AI** do dodawania i zmiany ścieżek dźwiękowych w wideo 🎬.
- Wykorzystuje najnowocześniejsze technologie, takie jak **Gemini**, **Hugging Face** i **Eleven Labs**, gwarantując wysoką jakość dubbingu.
- Obsługuje **szeroki wachlarz języków** 🌐, w tym języki Europy Środkowo-Wschodniej.
- Wymaga dostępu do **Google Cloud Platform** i tokena **Hugging Face**. Opcjonalnie, dla niestandardowych głosów, można skorzystać z **Eleven Labs**.
- Narzędzie dostępne jest na platformie **Colab**, co znacząco ułatwia jego użycie i konfigurację.
- **Ariel** oferuje **bogaty zestaw opcji konfiguracyjnych**, w tym regulację prędkości mowy i wybór głosów, co pozwala na precyzyjne dostosowanie dubbingu do indywidualnych potrzeb użytkownika.
- Stanowi idealne rozwiązanie dla osób i firm poszukujących **szybkiego i efektywnego dubbingowania wideo** na różnorodne języki.
___
# File: T4D1 - Lekcje wideo - 5. Narzędzia generowania obrazów Adios BackgroundR.md
## Umiejętności Jutra: Notatki i Podsumowanie - Sztuczna Inteligencja w Kreacjach Displayowych

## Wprowadzenie

Prezentacja \"Umiejętności Jutra\" omawia wykorzystanie **sztucznej inteligencji (AI)** 🤖 do tworzenia kreacji displayowych, a konkretnie obrazków reklamowych 🖼️. Przedstawiono dwa rozwiązania oparte na **AI**, które wspierają generowanie i personalizację grafik reklamowych: **Adios** i **Backgrounder**. Narzędzia te działają w oparciu o platformę **Google Cloud Platform** i arkusze **Google Sheets**.

## Adios - Generowanie Obrazków do Reklam Displayowych

### Co to jest Adios?

*   **Adios** to narzędzie wspomagane **AI**, które ułatwia tworzenie obrazków do reklam displayowych, szczególnie dla grup reklam w kampaniach **Responsive Search Ads**.
*   Usprawnia generowanie obrazków na podstawie **keywordsów** i grup reklam.
*   Może być wykorzystywane zarówno do tworzenia nowych obrazków, jak i do przypisywania istniejących zdjęć stockowych do grup reklam.

### Wymagania do Używania Adiosa

*   **Google Sheets**: Arkusze Google stanowiące środowisko pracy narzędzia.
*   **Google Cloud Platform (GCP)**: Platforma chmurowa Google.
    *   **Projekt Cloudowy**: Wymagany projekt w **GCP**.
    *   **Vertex AI API**: W projekcie **GCP** musi być włączone **API Vertex AI**.

### Szablon Adiosa

*   Gotowy szablon **Google Sheets** jest dostępny na **GitHubie**.
*   Przed rozpoczęciem pracy należy **skopiować** szablon na swój **Google Drive**.
*   Szablon składa się z trzech zakładek:
    *   **Konfiguracja (Configuration)**: Ustawienia narzędzia.
    *   **Mock**: Zakładka przeznaczona do testowania i przykładów (danych mockowych).
    *   **Policies**: Ustawienia wytycznych dla **AI** podczas generowania obrazków.

### Zakładka Konfiguracja (Configuration)

*   **Sekcja Pomarańczowa (Linie 2-5)**: Dane konta **Google Ads**.
    *   Miejsce na wprowadzenie danych konta **Google Ads** (opcjonalne, dla integracji z kontem reklamowym).
*   **Sekcja Szara**: Ustawienia promptowania **AI**.
    *   **Generowanie na podstawie**: Wybór opcji generowania obrazków na podstawie grupy reklam lub **keywordsów**.
    *   **Tekst Prompt Context**: Szablonowy prompt wysyłany do modelu **Gemini**. Użytkownik ma możliwość modyfikacji promptu.
    *   **Suffixy**: Opcjonalne suffixy dodawane do każdego promptu, np. rozmiar obrazka, brak tła.
    *   **Ilość obrazków**: Ustawienie liczby obrazków generowanych dla każdej grupy reklam.
    *   **Policy Checker**: Ustawienia sprawdzania zgodności wygenerowanych obrazków z wytycznymi z zakładki **Policies**.
*   **Sekcja Niebieska**: Konfiguracja **Google Cloud Platform**.
    *   **Google Cloud Project ID**: ID projektu **GCP**.
    *   **Bucket**: Nazwa `bucketu` w **Google Cloud Storage**, gdzie będą przechowywane obrazki.
    *   **Model**: Wybór modelu **Gemini** do generowania obrazków (Pro lub Flash).
    *   **Region**: Wybór regionu **GCP** (np. US Central 1, Europa).
    *   **Zakładka Mock (Linia 20)**: Opcjonalne użycie zakładki **Mock** do testowania bez podłączania konta **Google Ads**. Wymaga wpisania nazwy zakładki Mock.
*   **Nazwy Folderów**: Ustawienia nazw folderów w `buckecie` **Google Cloud Storage**.
    *   `generated`: Folder na wygenerowane obrazki.
    *   `validated`: Folder na zwalidowane obrazki.
    *   `rejected`: Folder na odrzucone obrazki.

### Generowanie Obrazków za Pomocą Adiosa

1.  Po konfiguracji, w menu **Google Sheets** pojawia się przycisk **Adios**.
2.  Kliknij **Adios** -> **Adios Run** -> **Image Generation**.
3.  Przy pierwszym uruchomieniu skrypt poprosi o autoryzację dostępu do konta Google 🔑.
4.  Po autoryzacji, obrazki zostaną wygenerowane i zapisane w `buckecie` **Google Cloud Storage**.

### Walidacja Obrazków

1.  Aby obejrzeć i zwalidować obrazki, kliknij **Extensions** -> **Apps Script**.
2.  W nowej zakładce **Apps Script** wybierz **Deploy** -> **Test Deployments**.
3.  Kliknij wygenerowany **URL**.
4.  Otworzy się interfejs użytkownika (UI) do walidacji obrazków.
5.  Obrazki są wyświetlane dla każdej grupy reklam.
6.  Można **zwalidować** (Validate) obrazki, które są akceptowalne ✅.
7.  Można **odrzucić** (Reject) obrazki, które nie pasują ❌. Odrzucone obrazki są oznaczone czerwonym krzyżykiem.
8.  Istnieje możliwość poproszenia o **regenerację** odrzuconych obrazków (nie zostało to pokazane w demonstracji, ale wspomniano o tej funkcji).

### Dodatkowe Informacje o Adios

*   Więcej szczegółów dostępnych jest na **GitHubie** (link w materiałach pomocniczych).

## Backgrounder - Dodawanie Tła do Packshotów Produktowych

### Co to jest Backgrounder?

*   **Backgrounder** to narzędzie **AI** przeznaczone do tworzenia teł do `packshotów` produktowych 📦.
*   Umożliwia personalizację reklam poprzez dodawanie kontekstowych teł do zdjęć produktów.
*   Pozwala na generowanie różnorodnych wariacji tła.

### Wymagania do Używania Backgroundera

*   **Google Cloud Platform (GCP)**: Platforma chmurowa Google.
    *   **Vertex AI API**: W projekcie **GCP** musi być włączone **API Vertex AI**.
*   **Google Sheets**: Arkusze Google, w których działa szablon narzędzia.

### Szablon Backgroundera

*   Szablon **Google Sheets** jest dostępny na **GitHubie**.
*   Należy **skopiować** szablon na swój **Google Drive**.

### Konfiguracja Backgroundera

1.  Po skopiowaniu szablonu, w menu **Google Sheets** pojawia się przycisk `backgrounder`.
2.  Kliknij `backgrounder` -> **Open**.
3.  Przy pierwszym uruchomieniu skrypt poprosi o autoryzację 🔑.
4.  Po prawej stronie arkusza pojawi się panel konfiguracji.
5.  Uzupełnij konfigurację:
    *   **Google Cloud Project ID**: ID projektu **GCP**.
    *   **Region**: Wybór regionu **GCP** (np. Europe West 3).
    *   **Image Generation Model**: Wybór modelu (aktualnie dostępny jeden model).
    *   **Drive Folder ID**: Ścieżka do folderu na **Google Drive**, z którego będą pobierane `packshoty`.

### Pobieranie Ścieżki Drive Folder ID

*   Instrukcja pobierania ścieżki **Drive Folder ID** znajduje się w zakładce **Getting Started** w szablonie **Google Sheets**.
*   Ścieżkę można znaleźć w **URL** folderu na **Google Drive**, po ostatnim slaszu `/`.

### Wariacje Tła (Background Variations)

*   Możliwość ustawienia wariacji tła poprzez podanie **tytułu** i **opisu**.
*   Opis stanowi prompt dla **AI** generującego tło. Im bardziej szczegółowy opis, tym lepsze rezultaty.
    *   Przykład: \"Living Room\", \"Office\", \"coffee table with a sofa\", \"office desk\".

### Generowanie Obrazków z Tłem

1.  Po konfiguracji i ustawieniu wariacji tła, obrazki z tłem zostaną wygenerowane w kolumnie A arkusza.
2.  Jeśli wygenerowane tła nie spełniają oczekiwań, można **doprecyzować opis** wariacji tła.
3.  Po doprecyzowaniu opisu, można ponownie wygenerować obrazki.

### Używanie Backgroundera na Skalę (Run Scaled)

*   Do przetwarzania dużej liczby `packshotów` dostępna jest opcja **Run scaled**.
*   **Backgrounder** -> **Run scaled** umożliwia przetworzenie całego folderu z assetami produktowymi.
*   Pozwala na przetworzenie setek, a nawet tysięcy `packshotów`.

### Dodatkowe Informacje o Backgrounder

*   Więcej informacji dostępnych jest na **GitHubie** (link w materiałach pomocniczych).

## Podsumowanie i Zachęta

Narzędzia **Adios** i **Backgrounder** to praktyczne rozwiązania wykorzystujące **sztuczną inteligencję** do generowania i personalizacji obrazków reklamowych 🖼️. Ułatwiają tworzenie kreacji displayowych na dużą skalę, oszczędzając czas ⏱️ i zwiększając efektywność działań marketingowych 🚀. Zachęcamy do korzystania z tych narzędzi i eksplorowania ich możliwości.