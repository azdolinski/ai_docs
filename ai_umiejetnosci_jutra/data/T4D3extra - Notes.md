# File: T4D3extra - Lekcje wideo - 2. Podstawowe wykorzystanie AI.md
## Szczegółowe Notatki i Podsumowanie Transkrypcji Wideo o Sztucznej Inteligencji w Google Cloud ☁️

## Wprowadzenie

* **Prelegent:** Mike Skowron, AI GTM Lead, CEE + Google Cloud ☁️
* **Temat:** Budowanie aplikacji wykorzystujących `sztuczną inteligencję` (AI) 🤖 w chmurze.
* **Cel prezentacji:**
    * Wyjaśnienie, czym jest `AI`.
    * Omówienie historii badań nad `AI` w Google, w tym nagród Nobla 🏆.
    * Prezentacja przykładów wdrożeń `AI`.
    * Przekonanie o wartości eksperymentowania z `AI` 🧪.

## Aktualny Stan Sztucznej Inteligencji

* **Minęły dwa lata od momentu, gdy `duże modele językowe` stały się powszechnie dostępne.**
* **Uderzająca jest łatwość, z jaką `AI` posługuje się językiem naturalnym.**
* **Pytanie:** Czym różni się maszyna ⚙️ od człowieka, skoro rozmawia jak człowiek i myśli w pewnym stopniu podobnie?
* **Odpowiedź:** Maszyna ⚙️ nie jest organizmem żywym, nie jest zbudowana z białek.
* **Białka:**
    * Najmniejsze klocki budulcowe życia.
    * „Robotnicy” realizujący procesy życiowe (mięśnie, kości, odżywianie, walka z chorobami).

## DeepMind i Projektowanie Białek - Nagroda Nobla 🏆

* **DeepMind (Google) stworzył oparty na `AI` system do projektowania wiązań białek.**
* **Alpha Proteo:** Narzędzie `AI` przewidujące kształt wiązań pasujących do białek docelowych (np. białko kolca wirusa SARS-CoV-2, białka nowotworowe, powikłania cukrzycy).
* **Dennis Hassabis (prezes DeepMind) i John Jumper (dyrektor) zostali laureatami Nagrody Nobla 🏆 z chemii.**

## Historia Badań nad Sztuczną Inteligencją w Google

* **Lata 50-te:** Przekonanie, że kluczem do `AI` jest **symboliczne odwzorowanie świata.**
    * Wielkie zbiory danych (data sety) opisujące wszystko.
    * Wnioskowanie oparte na statystyce i regułach logicznych (`if then` - `symbolic AI`).
    * Systemy były użyteczne, ale **nie uczyły się jak ludzie.**

* **Inspiracja uczeniem biologicznym:**
    * **Alan Turing (twórca pierwszego komputera):** Intuicja, że `AI` będzie się uczyć jak organizmy żywe.
    * **Test Turinga:** Odrożnianie treści generowanych przez `AI` od prawdziwych.
    * **Psychologia behawioralna:** Miała wpływ na naukę o `AI`.
        * **Koty Thorndyke, Psy Pawłowa:** Uczenie na bazie prób i błędów, uczenie wzmocnione systemem nagrody (**Reinforcement Learning**).
        * **Iwan Pawłow:** Pierwszy użył terminu "**Reinforcement Learning**".
    * **Pierwszy warunek dla generatywnej `AI`:** Zrozumienie zachowań wzmacniających uczenie w przyrodzie.

* **Propagacja Wsteczna (Backpropagation):**
    * **Drugi warunek dla generatywnej `AI`:** Zrozumienie zmian zachodzących w mózgu 🧠 podczas uczenia.
    * **1986:** Imitacja neuroplastyczności mózgu 🧠 w sztucznych sieciach neuronowych.
    * **Modyfikacja wag połączeń między węzłami (neuronami) podczas treningu.**
    * **Mechanizm propagacji wstecznej:**
        * **Jeffrey Hinton (emerytowany profesor, badacz `AI` w Google):** Współautor mechanizmu.
        * **Nagroda Nobla 🏆 z fizyki w tym roku za dokonania w dziedzinie propagacji wstecznej.**

## Eksperymenty DeepMind z Uzeniem Maszynowym 📚

* **Rok 2013:** DeepMind eksperymentuje z uczeniem maszynowym 📚 inspirowanym biologią.
* **Gry Atari:** Trenowanie sieci neuronowych w grach Atari.
* **Q Learning:**
    * Funkcja Q otrzymuje zadanie (`policy`) - zdobywanie punktów (nagród - `reward R`).
    * System obserwuje stan pikseli (`S`) i losowo dostosowuje akcje kontrolera (`A`).
    * **Efekty nauki:**
        * **10 minut:** Losowe ruchy, pierwsze punkty.
        * **120 minut:** System działa bezbłędnie.
        * **4 godziny:** Opracowanie strategii.
    * **Punkty jako zewnętrzna nagroda.**
    * **Dominacja `AI` w 7 grach Atari w 2013 roku (Pong, Breakout, Space Invaders).**

* **Montezuma's Revenge:**
    * Gra o złożonym środowisku, rzadkie zewnętrzne nagrody (punkty).
    * **Problem:** `Q Learning` z poprzednich gier nie działa z powodu braku zewnętrznych nagród.
    * **Rozwiązanie:** Inspiracja psychologią, **system wewnętrznej motywacji.**
    * **Ciekawość jako wewnętrzna nagroda:**
        * System śledzi nowość środowiska gry.
        * Nagradza agenta `AI` za eksplorację nowych obszarów.

## Architektura Transformer i Nauka Języka Naturalnego 🗣️

* **Google Brain (Mountain View, Kalifornia):** Praca nad architekturą **Transformer**.
* **Transformer:** Pomaga sieciom neuronowym uczyć się języka naturalnego.
* **Komponenty architektury Transformer:**
    * **Embedding (`Word to Vec` - 2013 w Google):** Zamiana słów na wektory w przestrzeniach wielowymiarowych.
    * **Positional Encoding:** Kodowanie kolejności słów w zdaniu.
    * **Mechanizm Atencji:** Wnioskowanie, która część mowy w zdaniu jest ważna.
* **2017:** Transformer na licencji Open Source w Google.
    * **Szturmem zdobywa świat `AI`.**
    * **Skalowalność i radzenie sobie z ogromnymi danymi 📊.**
    * **Startupy `AI` pre-trainują transformery.**
    * **Powstanie GPT (Generative Pre-trained Transformer).**

## Nauka Przez Imitację 🎭

* **Inspiracja z psychologii:** Dzieci uczą się przez obserwację i naśladowanie.
* **Waymo (Google):** Nauczenie `AI` imitować kierowcę auta 🚗.
* **IRL (Inverse Reinforcement Learning):** Sieć neuronowa obserwuje i imituje zachowania.
    * **Forma inżynierii odwrotnej (reverse engineering).**
    * **System obserwuje efekty i zachowanie eksperta.**
    * **Odgaduje funkcję nagrody wyjaśniającą zachowanie eksperta.**
    * **Przykład:** Punkty za dojazd do celu vs. unikanie kolizji, szybka vs. bezpieczna jazda.
* **Waymo (praca naukowa 2022):** Imitacja to za mało, dalszy rozwój technologii.
* **Komercyjne wdrożenia Waymo:** San Francisco, Phoenix, kolejne miasta USA.
* **Zespół Waymo zatrudnia ekspertów `AI` w Warszawie.**

## Podejście Google do Rozwoju AI 🤖

* **Rozwój `AI` od lat w Google.**
* **Badania Google przeniosły rozwój `AI` na nowy poziom.**
* **Transparentność rozwoju `AI`.**
* **Wsparcie dla Open Source community.**
* **Odpowiedzialne budowanie `AI`.**
* **Testowanie bezpieczeństwa `AI` 🛡️.**
* **Trening `AI` tylko na danych 📊, do których Google ma prawo.**
* **Wysokie standardy naukowe (dowód: 2 nagrody Nobla 🏆 w tym roku).**

## Google Cloud Platform - Vertex AI Model Garden 🪴

* **Modele DeepMind dostępne w chmurze Google ☁️ - Model Garden.**
* **Model Garden:** Platforma z tysiącami modeli Open Source (integracja z Hugging Face i Kaggle).
* **Dostępne modele:**
    * Duże modele (Antropic, Mistral, Meta).
    * Modele wyspecjalizowane (Medlem - medyczne, SecLM - Cyber Security 🔒).
* **Vertex AI:** Element platformy Google Cloud ☁️.
* **Google Cloud ☁️:**
    * Platforma do budowania rozwiązań biznesowych (nie konsumenckich jak Gemini, Google AI Studio).
    * Uruchamianie, fine-tuning, ewaluacja, testy AB modeli.
    * Integracja z systemami i aplikacjami.
    * Bezpieczeństwo danych 📊 i skalowalność infrastruktury.
* **Cel:** Rozwiązywanie rzeczywistych problemów za pomocą `AI`.

## Podsumowanie

Prezentacja Mike'a Skowrona z Google Cloud ☁️ przedstawiała historię rozwoju `sztucznej inteligencji` w Google, podkreślając kluczowe momenty i inspiracje z biologii i psychologii. Od `symbolicznego AI`, przez uczenie wzmocnione i propagację wsteczną, aż po architekturę Transformer i uczenie przez imitację 🎭. Google kładzie nacisk na transparentność, odpowiedzialność i bezpieczeństwo 🛡️ w rozwoju `AI`, udostępniając swoje osiągnięcia poprzez platformę Google Cloud Vertex AI Model Garden 🪴. Prezentacja podkreśla, że `AI` w Google Cloud ☁️ jest narzędziem do rozwiązywania rzeczywistych problemów biznesowych, oferując szeroki wybór modeli i infrastrukturę do ich wdrażania i skalowania. Dwie nagrody Nobla 🏆 dla badaczy z Google są dowodem na wysoki poziom naukowy i innowacyjność firmy w dziedzinie `sztucznej inteligencji`.
___
# File: T4D3extra - Lekcje wideo - 3. Zaawansowane wykorzystanie AI.md
## Umiejętności Jutra AI - Szczegółowe Notatki i Podsumowanie

## Wprowadzenie

Prezentacja omawia wykorzystanie sztucznej inteligencji (AI), a konkretnie generatywnej AI, w celu tworzenia nowej wartości w różnych branżach. Mówca przedstawia przykłady i pomysły na zastosowanie AI, opierając się na osiągnięciach badaczy AI w Google.

## HCA Healthcare - Usprawnienie Opieki Zdrowotnej za Pomocą AI 🏥

### Problem w Sektorze Opieki Zdrowotnej 🚑

* **Rozproszone dane pacjentów:** Informacje o pacjentach są często rozproszone w różnych systemach, a znaczna część danych nadal istnieje w formie papierowej.
* **Obciążenie pracą administracyjną:** Personel medyczny poświęca zbyt dużo czasu na zarządzanie danymi i dokumentacją.
* **Frustracja i wypalenie zawodowe:** Przeciążenie pracą administracyjną prowadzi do frustracji i wypalenia wśród personelu medycznego. Badania wskazują, że:
    * Prawie **60%** personelu medycznego zgłasza przemęczenie.
    * Niemal **połowa** rozważa zmianę branży.

### Rozwiązanie HCA Healthcare z Wykorzystaniem Generatywnej AI 💡

* **Cel:** Uproszczenie pracy administracyjnej, aby personel medyczny mógł poświęcić więcej czasu pacjentom.
* **Technologia:** HCA Healthcare wykorzystuje generatywną AI w Google Cloud oraz technologię przetwarzania mowy na tekst w medycynie, we współpracy z Augmedix.
* **Korzyści:**
    * **Więcej czasu z pacjentem:** Automatyzacja dokumentacji klinicznej pozwala lekarzom i pielęgniarkom poświęcić więcej czasu na bezpośrednią opiekę.
    * **Wyższa efektywność pracy:** Usprawnienie zadań, takich jak sporządzanie notatek i generowanie raportów.
    * **Lepsze wyciąganie wniosków:** Badanie zastosowań medycznych dużych modeli językowych (LLM) do analizy złożonych tekstów medycznych.
* **Cytat Michaela J. Schlossera, SVP, Care Transformation and Innovation, HCA Healthcare:**
    > Generatywna sztuczna inteligencja i inne nowoczesne technologie pomagają nam zmieniać sposób współpracy zespołów, optymalizować procesy oraz zagwarantować, że odpowiedni zespół, w odpowiednim czasie, dysponuje informacjami niezbędnymi do opieki nad pacjentami.

### Przykład Użycia AI w Praktyce - Aplikacja dla Pielęgniarki Kelly 👩‍⚕️

* **Scenariusz:** Pielęgniarka Kelly rozpoczyna dyżur i korzysta z aplikacji na tablecie.
* **Aplikacja "Cymbal Health":**
    * Kelly przegląda listę pacjentów i wybiera kolejnego - 71-letniego Juana po operacji kolana.
    * **AI podsumowuje najważniejsze informacje o pacjencie.**
* **Model "Med-PaLM":**
    * Wyspecjalizowany model AI, wytrenowany na danych medycznych.
    * Potrafi:
        * Ułożyć historię pacjenta chronologicznie.
        * Wnioskować i rozumieć medyczny żargon, nazwy leków i zabiegów.
* **Korzyści dla Kelly i Pacjenta:**
    * AI działa w tle, umożliwiając Kelly skupienie się na rozmowie z pacjentem.
    * AI pomaga przetłumaczyć medyczny żargon na proste instrukcje dla pacjenta.
    * **Wielojęzyczność:** AI tłumaczy informacje na dowolny język (przykład: hiszpański w USA, ukraiński w Polsce).
    * **Multimodalność:** AI potrafi odczytać tekst głośno. Modalności obejmują: tekst, audio 🎧, obrazy 🖼️, wideo 📹.
    * **Wsparcie w procesie wypisu:** AI pomaga w wypisaniu recepty 📝, znalezieniu przychodni na rehabilitację (integracja z Google Maps 🗺️), sprawdzeniu ubezpieczenia.
* **Wdrożenie:** Elementy demonstracyjnej aplikacji są wdrażane w HCA i innych firmach z sektora zdrowia na całym świecie.

## Puma - Hiperpersonalizacja w Handlu Detalicznym 🛍️

### Zwiększenie Współczynnika Klikalności (CTR) w E-commerce 📈

* **Branża:** Handel detaliczny.
* **Firma:** Puma.
* **Wynik:** Zwiększenie CTR o **10%**.
* **Technologia:** Model generowania obrazów **Imagen 3** od Google.
* **Personalizacja Tła Produktów:** Tworzenie spersonalizowanych teł do zdjęć produktów, dostosowanych do lokalizacji i zainteresowań użytkowników.
    * Przykład: Biegacz w Europie zobaczy buty na tle leśnym 🌲, biegacz w Japonii - na tle góry Fuji 🗻.

### Zmiana Świata Cyfrowego 🌐

* Coraz trudniej jest odróżnić treści generowane przez AI od tradycyjnych kreacji.
* Świat cyfrowy zmienia się w bardzo szybkim tempie 🚀.

## Synth ID - Bezpieczeństwo i Znakowanie Treści AI 🛡️

### Test Turinga i Bezpieczeństwo AI 🔒

* **Test Turinga (1950):** Metoda sprawdzania, czy mamy do czynienia z maszyną, czy człowiekiem.
* **Synth ID (Google DeepMind, październik 2024):** System znakowania treści generowanych przez AI.
    * **Otwarta licencja Open Source 🔓.**
    * **Znak wodny:** Umieszczanie znaku wodnego w każdej wygenerowanej treści.
* **Znaczenie Bezpieczeństwa AI:** Kluczowe znaczenie społeczne i biznesowe.
* **Korzyści dla Biznesu (Przykład Puma):**
    * Puma może udowodnić, jakim modelem i kiedy wygenerowano tła dla zdjęć produktów.
    * Kontrola nad prawami autorskimi.
    * Implementacja bezpieczeństwa w skali produkcyjnej.

## Biznes Potrzebuje Więcej - Wykorzystanie Potencjału AI 💼

### Oczekiwania wobec Liderów 🎯

* Zrozumienie i umiejętność wykorzystania AI do wniesienia wymiernej wartości w bezpieczny sposób.

### Oczekiwania Konsumentów 🛍️

* Konsumenci mają wysokie oczekiwania wobec AI.
* Firmy, które potrafią wykorzystać AI, mają większe szanse na zwiększenie udziału w rynku.

### Realia Wdrożeń AI ⚙️

* **Szybkie i bezpieczne prototypowanie.**
* **Testowanie rozwiązań.**
* **Skalowanie rozwiązań przynoszących wartość.**
* **Szybkie zakończenie eksperymentów bez wartości, zmiana założeń i ponowne testowanie.**

## GenAI - Zwiększenie Produktywności i Rentowności 💰

### Obietnica Generatywnej AI ✨

* Wdrożenie generatywnej AI w całym cyklu życia użytkownika ma znaczący wpływ na biznes.
* Potężne możliwości: generowanie treści, podsumowywanie informacji, konwersacyjne wyszukiwanie.

### Przewidywany Wzrost Wydajności 🚀

* **Marketing i sprzedaż:** +5-15%
* **Obsługa klienta:** +30-45%
* **Wydajność wykwalifikowanych pracowników:** do +40%

### Przekształcenie Centrów Kosztów w Centra Zysków 📈

* Automatyzacja rutynowych zadań.
* Uwolnienie czasu na pracę strategiczną.

### Zwrot z Inwestycji (ROI) w GenAI - Badanie National Research Group 📊

* Badanie 2500 liderów z globalnych firm (przychody > 10 mln USD).
* **Wyniki:**
    * **2/3 organizacji, które wdrożyły GenAI, już odnotowuje ROI lub spodziewa się go w najbliższych miesiącach.**
    * Dotyczy wszystkich przypadków użycia, dane dostępne w podziale na branże i regiony.
    * Link do danych za kodem QR.

## Wypróbuj Generatywną AI Teraz - Vertex AI 💻

### Innowacje z Generatywną AI 🌟

* Możliwość tworzenia innowacji, o których świat jeszcze nie słyszał.

### Vertex AI na Chmurze Google ☁️

* Narzędzia dające kontrolę nad całym procesem AI.
* Zachęta do testowania i tworzenia.

## Podsumowanie 📝

Prezentacja podkreśla potencjał generatywnej sztucznej inteligencji w transformacji różnych branż, w szczególności opieki zdrowotnej i handlu detalicznego. Przykłady HCA Healthcare i Puma ilustrują, jak AI może usprawnić procesy, zwiększyć efektywność i personalizację. Ważnym aspektem jest bezpieczeństwo AI, reprezentowane przez system `Synth ID`. Prezentacja zachęca firmy do szybkiego prototypowania, testowania i skalowania rozwiązań AI, podkreślając obietnicę wzrostu produktywności i rentowności. Narzędzia Google Cloud, takie jak `Vertex AI`, są przedstawione jako kluczowe w realizacji tych innowacji. Głównym przesłaniem jest to, że firmy, które skutecznie wdrożą generatywną AI, zyskają znaczącą przewagę konkurencyjną i sprostają rosnącym oczekiwaniom konsumentów.