# Sekcja 1. Wprowadzenie do generatywnej AI oraz jak promptować - 1. Podstawy Generatywnej AI

# 💡 Diagram

```mermaid
mindmap
  root((Generative AI (GenAI) Lesson Summary))
    Introduction
      Prelegent: Łukasz Olejniczak
      Analogia do nauki obsługi komputera
      Cel: Działanie GenAI, Efektywne użycie, Zaawansowane techniki
      Kluczowe przesłanie: Nauka GenAI = Nauka Komputera

    Jak_Działa_GenAI[Jak Działa GenAI]
      Wykorzystuje LLM (Large Language Models)
      Kontrola Promptami (Pytania)
      Rola Człowieka: Tworzenie Promptów
      Weryfikacja Odpowiedzi (Merytoryczna poprawność)
      Ryzyko Halucynacji (Nieprawdziwe odpowiedzi)

    Czym_Jest_GenAI[Czym Jest GenAI]
      Definicja GenAI: Generuje nowe treści (tekst, obrazy, multimedia)
      Wykorzystuje LLM
      Definicja LLM: Trenowany na dużych zbiorach tekstu, rozpoznaje wzorce językowe
      Język Naturalny: Język codzienny
      Zdolności LLM: Rozpoznaje intencje, dostarcza odpowiedzi

    Co_Potrafią_LLM[Co Potrafią LLM]
      Podsumowywanie tekstów
      Rozwiązywanie problemów 💡
      Tłumaczenie 🌐
      Edytowanie tekstów ✍️
      Generowanie pomysłów ✨
      Klasyfikowanie treści

    Prompt_Engineering[Prompt Engineering]
      Definicja: Opracowanie optymalnych promptów
      Cel: Jasne polecenia i kontekst dla AI
      Przykłady Promptów: Popraw [tekst], Przetłumacz maila, Popraw tekst [w mailu]

    AI_vs_UczenieMaszynowe_vs_LLM[AI, Uczenie Maszynowe, LLM]
      AI (Sztuczna Inteligencja): Najszersze pojęcie
      Uczenie Maszynowe: Metoda AI, programy uczące się na danych
      LLM (Duży Model Językowy): Program nauczony na tekście, generuje tekst, przykład GenAI
      Prompt Engineering: Ulepszanie odpowiedzi GenAI

    Rola_Człowieka[Rola Człowieka]
      Niezbędny do: Promptowania, Weryfikacji, Wykorzystania odpowiedzi
      Unikanie Halucynacji: Zwiększa dokładność i trafność

    Halucynacje_w_GenAI[Halucynacje w GenAI]
      Występowanie: Nieprawdziwe, niedokładne wyniki
      Przyczyny: Nieprecyzyjny prompt, Brak wiedzy modelu, Generatywna natura
      Konieczność Weryfikacji: Każda odpowiedź

    Nauka_Obsługi_GenAI[Nauka Obsługi GenAI]
      Analogia do nauki obsługi komputera: Umiejętność do nabycia

    Jak_Stworzyć_Dobry_Prompt[Jak Stworzyć Dobry Prompt]
      Elementy: Opis zadania, Kontekst problemu, Przykład rozwiązania

    Iteracja_Promptów[Iteracja Promptów]
      Krytyczne podejście do odpowiedzi
      Ponowne zadawanie pytań
      Modyfikacja Promptu
      Proces Iteracyjny: Dialog z modelem

    Przykład_Promptów_Prezent[Przykład Promptów - Prezent]
      Zły Prompt: "Pomysły na prezent poniżej 100 zł" - Brak kontekstu, ogólne odpowiedzi
      Dobry Prompt: "Prezent urodzinowy dla 10-latki, fioletowy, konie i jednorożce, budżet 100 zł" - Konkretny, trafne propozycje

    Gdy_AI_Nie_Daje_Odpowiedzi[Gdy AI Nie Daje Odpowiedzi]
      Ponowne Pytanie
      Dodanie Kontekstu i Przykładów
      Iteracja Promptów
      Podobieństwo do Rozmowy

    Ocena_Odpowiedzi_GenAI[Ocena Odpowiedzi GenAI]
      Kluczowe Pytania: Dokładność, Kompletność, Związek z zadaniem, Spójność

    Modyfikacja_Promptu_Poprawa_Wyników[Modyfikacja Promptu - Poprawa Wyników]
      Rozwiązywanie Problemów
      Analogia do Gry Komputerowej 🎮: Próbuj do skutku

    Zaawansowane_Techniki_Promptowania[Zaawansowane Techniki Promptowania]
      "Kody" Promptowania: Legalne i efektywne metody
      Few-shot Prompting: Kilka przykładów
      Zero-shot Prompting: Bez przykładów
      One-shot Prompting: Jeden przykład

    Podsumowanie_Lekcji[Podsumowanie Lekcji]
      GenAI: Potężne narzędzie, nauka efektywnego wykorzystania
      Prompt Engineering: Kluczowy element sukcesu
      Iteracja Promptów i Krytyczna Ocena Odpowiedzi
      Weryfikacja Odpowiedzi i Ryzyko Halucynacji
      Zaawansowane Techniki Promptowania = Większa Efektywność
      Nauka GenAI = Nauka Komputera, Przynosi Korzyści
```

___

# 🗒️ Notatka


# Notatki i Podsumowanie Lekcji o Generatywnej Sztucznej Inteligencji

## Wprowadzenie do Generatywnej Sztucznej Inteligencji (`GenAI`)

* **Prelegent:** Łukasz Olejniczak, Customer Engineer for Smart Analytics and AI, Google Cloud Poland.
* **Analogia do nauki obsługi komputera:** Nikt nie rodzi się z umiejętnością korzystania z komputera, ale każdy może się tego nauczyć. Podobnie jest z generatywną sztuczną inteligencją.
* **Cel lekcji:** Wyjaśnienie działania `GenAI`, efektywnego korzystania z niej w 5 krokach oraz zaawansowanego użytkowania.
* **Kluczowe przesłanie:** Tak jak nauczyliśmy się obsługiwać komputery, możemy i powinniśmy nauczyć się obsługi `GenAI`.

## Jak Działa Generatywna Sztuczna Inteligencja?

* **Wykorzystanie Modeli Językowych (`LLM`):** `GenAI` wykorzystuje **duże modele językowe (`LLM`)**, trenowane przy użyciu technik uczenia maszynowego inspirowanych działaniem ludzkiego mózgu 🧠.
* **Kontrola za Pomocą Promptów:** Modele `LLM` można kontrolować i wykorzystywać ich wiedzę oraz zdolności generatywne do uzyskiwania odpowiedzi poprzez odpowiednie zadawanie pytań, zwanych **promptami**.
* **Kluczowa Rola Człowieka:** To my tworzymy pytania (`prompty`) w sposób, który umożliwia modelowi zrozumienie kontekstu zapytania.
* **Weryfikacja Odpowiedzi:** Istotne jest weryfikowanie merytorycznej poprawności odpowiedzi generowanych przez model, ponieważ modele `GenAI` mogą generować odpowiedzi nawet wtedy, gdy nie mają pewności co do ich prawdziwości.
* **Ryzyko Halucynacji:** Modele `GenAI` mogą generować nieprawdziwe lub niedokładne odpowiedzi, co określa się mianem **halucynacji**.

## Czym Jest Generatywna Sztuczna Inteligencja (`GenAI`)?

* **Definicja `GenAI`:** **Generatywna Sztuczna Inteligencja (`GenAI`)** to rodzaj sztucznej inteligencji, który generuje nowe treści, takie jak teksty, obrazy lub multimedia.
* **Wykorzystanie `LLM`:** `GenAI` wykorzystuje **Large Language Models (`LLM`)**, czyli **duże modele językowe**.
* **Definicja `LLM`:** **Duże Modele Językowe (`LLM`)** to rodzaj sztucznej inteligencji trenowany na ogromnych zbiorach tekstu. Dzięki temu `LLM` rozpoznają wzorce i zależności między słowami, pojęciami i wyrażeniami w języku naturalnym.
* **Język Naturalny:** Język, którym posługujemy się na co dzień w rozmowach.
* **Zdolności `LLM`:** `LLM` potrafią nie tylko rozpoznawać intencję pytania, ale także dostarczać odpowiedzi.

## Co Potrafią Modele `LLM`?

* **Podsumowywanie** złożonych i długich tekstów.
* **Rozwiązywanie problemów** 💡.
* **Tłumaczenie** na różne języki 🌐.
* **Edytowanie tekstów** ✍️.
* **Generowanie pomysłów** ✨.
* **Klasyfikowanie treści**.

## `Prompt Engineering` - Sztuka Tworzenia Promptów

* **Definicja `Prompt Engineeringu`:** **`Prompt engineering`** to proces opracowywania optymalnych podpowiedzi (`promptów`) dla modelu `GenAI`.
* **Cel `Prompt Engineeringu`:** Dostarczanie **jasnych, konkretnych poleceń i kontekstu** dla asystenta AI.
* **Przykłady Prostych Promptów:**
    * Popraw [tekst].
    * Przetłumacz maila [na język].
    * Popraw tekst [w mailu].

## Sztuczna Inteligencja (`AI`), Uczenie Maszynowe i `LLM` - Podsumowanie Pojęć

* **`AI` (Sztuczna Inteligencja):** Najszersze pojęcie, ogólna dziedzina.
* **Uczenie Maszynowe:** Metoda `AI`, polegająca na tworzeniu programów uczących się na danych.
* **`LLM` (Duży Model Językowy):** Program nauczony na ogromnych ilościach tekstu, który generuje tekst. Jest przykładem **generatywnej sztucznej inteligencji (`GenAI`)**.
* **`Prompt Engineering`:** Stosowany w celu uzyskiwania i ulepszania odpowiedzi od `GenAI`.

## Rola Człowieka w Procesie `GenAI`

* **Niezbędność Człowieka:** Człowiek jest niezbędny do:
    * **Promptowania** (konstruowania pytań).
    * **Weryfikowania odpowiedzi** od AI.
    * **Wykorzystywania otrzymanych odpowiedzi**.
* **Unikanie Halucynacji:** Podejście z udziałem człowieka pomaga minimalizować negatywne skutki halucynacji, co przekłada się na większą dokładność i trafność wyników generowanych przez AI.

## Halucynacje w `GenAI`

* **Występowanie Halucynacji:** `GenAI` czasami generuje **nieprawdziwe, niedokładne wyniki** (halucynacje).
* **Przyczyny Halucynacji:**
    * **Nieprecyzyjny prompt.**
    * **Brak wiedzy modelu** na dany temat.
    * Generatywna natura modelu, który zawsze dąży do udzielenia odpowiedzi.
* **Konieczność Weryfikacji:** **Każda odpowiedź od `GenAI` powinna być zweryfikowana przez człowieka.**

## Nauka Obsługi `GenAI`

* **Analogia do Nauki Obsługi Komputera:** Nauka obsługi `GenAI` przypomina naukę obsługi komputera – jest umiejętnością, którą można nabyć.

## Jak Stworzyć Dobry Prompt?

* **Elementy Dobrego Promptu:**
    * **Opis zadania.**
    * **Kontekst problemu.**
    * **Przykład rozwiązania** zbliżonego zadania (przykłady).

## Iteracja i Modyfikacja Promptów

* **Krytyczne Podejście do Odpowiedzi:** Należy podchodzić krytycznie do każdej odpowiedzi generowanej przez `GenAI`.
* **Ponowne Zadawanie Pytań:** Jeśli odpowiedź nie jest satysfakcjonująca, warto spróbować zadać pytanie ponownie.
* **Modyfikacja Promptu:** Należy zastanowić się, czego brakuje w odpowiedzi i zmodyfikować prompt, aby model skupił się na konkretnych aspektach.
* **Iteracja Promptów:** `Promptowanie` to proces iteracyjny, przypominający dialog z modelem, wymagający ciągłego doprecyzowywania.

## Przykład Złego i Dobrego Promptu - Prezent dla Siostrzenicy

### Zły Prompt:

* **Prompt:** \"Podaj mi kilka pomysłów na prezent poniżej 100 zł.\"
* **Problem:** Brak kontekstu, odpowiedź zbyt ogólna, model proponuje uniwersalne pomysły.

### Dobry Prompt:

* **Prompt:** \"Podaj cztery pomysły na prezent urodzinowy dla dziesięcioletniej dziewczynki, która interesuje się kolorem fioletowym oraz jest fanką koni 🐴 i jednorożców 🦄. Mój budżet wynosi 100 zł.\"
* **Zalety:** Zawiera kontekst (dla kogo, zainteresowania, budżet).
* **Wynik:** Model wygenerował konkretne i trafne propozycje, uwzględniając preferencje dziewczynki i budżet.

## Co, Gdy AI Nie Daje Odpowiedniej Odpowiedzi?

* **Ponowne Pytanie:** Zamiast rezygnować, należy spróbować zapytać ponownie.
* **Dodanie Kontekstu i Przykładów:** Wzbogacić prompt o więcej przykładów i dodatkowy kontekst.
* **Iteracja Promptów:** Kontynuować iterację promptów, prowadząc dialog z modelem.
* **Podobieństwo do Rozmowy:** `Promptowanie` przypomina naturalną rozmowę, z pauzami, doprecyzowaniami i modyfikacjami.

## Ocena Odpowiedzi `GenAI` - Kluczowe Pytania

* **Dokładność:** Czy wynik jest dokładny?
* **Kompletność Informacji:** Czy wynik jest wyczerpujący?
* **Związek z Zadaniem:** Czy wynik jest adekwatny do mojego projektu lub zadania?
* **Spójność:** Czy uzyskuję spójne wyniki, zadając wielokrotnie to samo pytanie?

## Modyfikacja Promptu w Celu Poprawy Wyników

* **Rozwiązywanie Problemów:** Jeśli ocena odpowiedzi ujawnia niedociągnięcia, modyfikacja promptu może pomóc w ich eliminacji i uzyskaniu lepszych rezultatów.
* **Analogia do Gry Komputerowej:** Podobnie jak w grze komputerowej 🎮, rzadko udaje się przejść poziom za pierwszym podejściem. Warto próbować do skutku.

## Zaawansowane Techniki Promptowania - \"Kody\"

* **\"Kody\" Promptowania:** Legalne i efektywne metody `promptowania`, ułatwiające pracę z `GenAI`.
* **`Few-shot Prompting`:** `Promptowanie` oparte na **kilku przykładach** rozwiązania zbliżonego problemu.
* **`Zero-shot Prompting`:** `Promptowanie` **bez użycia jakichkolwiek przykładów**.
* **`One-shot Prompting`:** `Promptowanie` z **jednym przykładem**.

## Podsumowanie Lekcji

* Generatywna sztuczna inteligencja (`GenAI`) to potężne narzędzie, którego efektywnego wykorzystania możemy się nauczyć.
* Kluczowym elementem sukcesu jest **`prompt engineering`** - umiejętność tworzenia precyzyjnych i kontekstowych promptów.
* Istotna jest **iteracja promptów** oraz **krytyczna ocena odpowiedzi** generowanych przez model.
* Należy pamiętać o **weryfikacji odpowiedzi** i ryzyku wystąpienia **halucynacji**.
* Wykorzystując zaawansowane techniki `promptowania`, takie jak **`few-shot`, `zero-shot` i `one-shot prompting`**, możemy znacząco zwiększyć efektywność naszej pracy z `GenAI`.
* Nauka obsługi `GenAI` jest możliwa i przyniesie wiele korzyści, podobnie jak nauka obsługi komputera.


___

# 🔉 Transcript
File: Sekcja 1. Wprowadzenie do generatywnej AI oraz jak promptować - 1. Podstawy Generatywnej AI.mp4<br>
[00:00:05] Speaker: Cześć.
[00:00:06] Screen: Łukasz Olejniczak, Customer Engineer for Smart Analytics and AI, Google Cloud Poland.
[00:00:06] Speaker: To marzenie takie oczywiste, ale nikt z nas nie urodził się z umiejętnością korzystania z komputera.
[00:00:13] Speaker: Każdy miał ten moment, kiedy po raz pierwszy posadzony przed klawiaturą i ekranem musiał odpalić komputer, stworzyć pierwszy folder, a potem właściwie nie wiedząc kiedy, grał w skomplikowane gry, pisał pracę dyplomową i z komputerem już się nie rozstawał.
[00:00:32] Speaker: I tak jak każde z nas był w stanie nauczyć się obsługi komputera, tak samo możemy, a nawet powinniśmy nauczyć się obsługi generatywnej sztucznej inteligencji.
[00:00:44] Speaker: W tej lekcji opowiem wam jak działa generatywna sztuczna inteligencja, jak korzystać z niej skutecznie w pięciu krokach, jak korzystać z niej lepiej niż inni, czyli jak używać jej na poziomie zaawansowanym.
[01:01:01] Speaker: I gdybym miał podsumować wszystko, co powinniście wiedzieć po tej lekcji w jednym zdaniu, to brzmiałoby ono tak: wykorzystuje modele językowe, tak zwane LLM-y, które używają różnych technik uczenia maszynowego inspirowanych sposobem działania ludzkiego mózgu.
[01:24:01] Speaker: Odpowiednio zadając pytania, tak zwane prompty, jesteśmy w stanie przejąć kontrolę nad tymi modelami, niczym pilot nad samolotem i wykorzystać wiedzę zapisaną w modelu w trakcie jego trenowania oraz jego generatywne zdolności do uzyskania odpowiedzi na nasze pytania.
[01:46:54] Speaker: Nasza rola jest tutaj kluczowa.
[01:49:37] Speaker: To my będziemy konstruować pytania w sposób, który pozwoli modelowi rozpoznać co się za tym pytaniem kryje, tak zwany kontekst pytania.
[02:01:49] Speaker: Na koniec będziemy musieli zweryfikować czy odpowiedź jest merytorycznie poprawna, bowiem tego typu modele są stworzone do generowania i generują nawet wtedy, kiedy nie są pewne odpowiedzi.
[02:18:08] Speaker: I mówimy wtedy o ryzyku halucynacji.
[02:21:51] Speaker: Prawda, że proste?
[02:23:35] Speaker: Przeróbmy to na spokojnie.
[02:25:58] Speaker: Zacznijmy od GenAI, skrótowca od generative Artificial Intelligence, a po polsku generatywnej sztucznej inteligencji.
[02:35:54] Speaker: GenAI to rodzaj sztucznej inteligencji, która generuje nowe treści, na przykład teksty, obrazy lub inne multimedia.
[02:47:34] Speaker: GenAI wykorzystuje LLM-y, czyli Large Language Models, a po polsku duże modele językowe.
[02:56:23] Speaker: To rodzaj sztucznej inteligencji trenowanej na dużej ilości tekstu, co sprawia, że może rozpoznawać pewne wzorce i zależności pomiędzy słowami i pojęciami, a także wyrażeniami w języku naturalnym.
[03:13:55] Speaker: Czyli w takim języku, jakim posługujemy się na co dzień w rozmowach między sobą.
[03:21:39] Speaker: Może nie tylko rozpoznawać, o co nam chodzi, ale też dostarczać odpowiedzi.
[03:28:23] Speaker: Co konkretnie potrafią LLM-y?
[03:29:45] Screen: Co konkretnie potrafią LLM-y?: podsumowywać złożone i długie teksty, rozwiązywać problemy, tłumaczyć na różne języki, edytować teksty, generować pomysły, klasyfikować.
[03:32:05] Speaker: Potrafią podsumowywać złożone i długie teksty, rozwiązywać problemy, tłumaczyć na różne języki, edytować teksty, generować pomysły lub klasyfikować treści.
[03:50:29] Speaker: Modele GenAI dają lepsze odpowiedzi, jeśli posiadamy umiejętność z zakresu tak zwanego prompt engineeringu.
[03:57:39] Speaker: Brzmi skomplikowanie?
[03:59:00] Speaker: Niekoniecznie.
[04:01:20] Speaker: Prompt engineering polega na opracowaniu jak najlepszych podpowiedzi dla modelu.
[04:07:13] Speaker: Chodzi o to, żeby ten nasz AI asystent po prostu otrzymywał jasne, konkretne polecenia i kontekst.
[04:17:48] Speaker: Parę promptów przed chwilą widzieliście.
[04:21:08] Speaker: Popraw, przetłumacz maila, popraw tekst.
[04:24:41] Speaker: To proste prompty.
[04:27:11] Speaker: Da się lepiej, ale to za chwilę.
[04:31:15] Speaker: Podsumujmy.
[04:32:18] Speaker: Sztuczna inteligencja, czyli AI, to najszersze pojęcie.
[04:37:06] Speaker: Jedną z metod AI jest uczenie maszynowe, czyli tworzenie programów uczących się na danych.
[04:45:11] Speaker: A LLM to program, który nauczony jest na ogromnych ilościach tekstu.
[04:51:29] Speaker: A do tego sam generuje tekst, przez co jest przykładem tak zwanej generatywnej sztucznej inteligencji.
[04:58:58] Speaker: Aby uzyskiwać i ulepszać odpowiedzi od GenAI, stosujemy prompt engineering.
[05:06:24] Speaker: Na czym polega nasza rola w tym procesie?
[05:09:13] Speaker: Człowiek jest niezbędny do promptowania, weryfikowania odpowiedzi od AI i na koniec to on będzie wykorzystywać otrzymane odpowiedzi.
[05:20:24] Speaker: Takie podejście pozwala na uniknięcie potencjalnych negatywnych skutków halucynacji, przez co wyniki generowane przez AI mają szansę być bardziej dokładne i trafne.
[05:35:10] Speaker: Wspomniane halucynacje mogą zdarzyć się każdemu.
[05:39:17] Speaker: Również GenAI czasami podaje nieprawdziwe, niedokładne wyniki.
[05:45:11] Speaker: Może to być spowodowane nieprecyzyjnym promptem albo faktem, że model nie posiada wiedzy na dany temat, ale jego generatywna natura sprawia, że zawsze próbuje odpowiedzieć na zadany prompt.
[06:01:02] Speaker: Dlatego każda odpowiedź od GenAI powinna być weryfikowana przez człowieka.
[06:09:20] Speaker: Tak jak komputer, GenAI potrzebuje człowieka, ale też człowiek, tak jak uczy się obsługi komputera, tak samo potrzebuje nauczyć się obsługi GenAI.
[06:31:53] Speaker: Wiecie już jak działają duże modele językowe.
[06:32:30] Speaker: Czas przekuć teorię w praktykę.
[06:33:17] Speaker: Dobry prompt zawiera opis zadania, kontekst problemu i przykład rozwiązania zbliżonego zadania, tak zwane przykłady.
[06:42:58] Speaker: Dobrze by było, gdybyś podszedł krytycznie do każdej odpowiedzi i jeśli nie jest ona wystarczająco dokładna lub satysfakcjonująca, spróbował zadać pytanie jeszcze raz, ale zanim to zrobisz, zastanów się czego tej odpowiedzi brakuje i zmodyfikuj swoje zapytanie tak, żeby model wiedział, że na tych zagadnieniach powinien się skupić.
[07:08:34] Speaker: Zobaczmy różnicę między dobrze i źle napisanym promptem.
[07:13:04] Speaker: Przed nami niezwykle skomplikowane i trudne zadanie, które chcieli, gdybyśmy chcieli wykonać sami, mogłoby oznaczać noce i dnie wyrywania sobie włosów z głowy.
[07:25:58] Speaker: Czyli co kupić na prezent dla dziesięcioletniej siostrzenicy?
[07:29:15] Speaker: Użyjemy jednak do tego Gemini.
[07:32:10] Speaker: Podaj mi kilka pomysłów na prezent poniżej 100 zł.
[07:37:03] Speaker: Jak widzicie, brakuje kontekstu, więc model poda różne pomysły dla osób z różnymi zainteresowaniami, dorosłych i dzieci.
[07:40:53] Speaker: Trochę zbyt szeroko, prawda?
[07:50:27] Speaker: Spróbujmy z innym promptem.
[07:52:58] Speaker: Podaj mi cztery pomysły na prezent urodzinowy dla dziesięcioletniej dziewczynki, która lubi kolor fioletowy i jest fanką koni i jednorożców.
[08:04:25] Speaker: Mój budżet to 100 zł.
[08:08:37] Screen: Podaj mi 4 pomysły na prezent urodzinowy dla dziesięcioletniej dziewczynki, która lubi kolor fioletowy i jest fanką koni i jednorożców. Mój budżet to 100 zł. Super, że podałaś mi więcej szczegółów! Oto 4 pomysły na prezent urodzinowy dla 10-latki, fanki koni i jednorożców, w kolorze fioletowym, do 100 zł: 1. Zestaw kreatywny do tworzenia biżuterii z motywami koni/jednorożców: Zestaw koralików, sznurków, zawieszek w kształcie koni i jednorożców pozwoli dziewczynce stworzyć własną, unikalną biżuterię. Upewnij się, że w zestawie dominuje kolor fioletowy lub, że koraliki są w różnych kolorach, w tym fioletowym.
[08:15:15] Speaker: Zobaczcie, że tutaj podaliśmy już kontekst.
[08:17:25] Speaker: Prezent jest dla dziewczynki, której obiektem zainteresowania są konie i jednorożce.
[08:20:26] Speaker: W tym obszarze Gemini wygenerował nam mnóstwo pomysłów, od zabawek po książki.
[08:27:48] Speaker: Mamy w czym wybierać.
[08:28:41] Speaker: Zauważcie, że model wskazał również konkretne miejsca, gdzie możecie kupić dany prezent.
[08:37:17] Speaker: Chwila i zrobione.
[08:39:33] Speaker: No dobrze, ale może się zdarzyć, że AI nie poda nam od razu odpowiedzi, która nam pasuje.
[08:47:10] Speaker: W końcu no nie zda naszej siostrzenicy.
[08:50:37] Speaker: W takiej sytuacji, zamiast porzucić to wszystko, wystarczy zapytać ponownie.
[08:55:52] Speaker: Podać więcej przykładów, dodatkowy kontekst.
[08:59:15] Speaker: Inaczej mówiąc, iterować prompty.
[09:03:45] Speaker: Bo promptowanie to ciągła rozmowa z modelem.
[09:06:59] Speaker: Gdy z kimś rozmawiacie, naturalne są zatrzymania, przerywniki, dopowiadanie czy strumień myśli.
[09:14:30] Speaker: Podobnie jest z promptowaniem.
[09:17:52] Speaker: Czasem będziecie musieli zacząć od nowa lub wrócić do bardzo podstawowej wersji promptu.
[09:24:14] Speaker: To też jest w porządku.
[09:27:05] Speaker: Na co zwrócić uwagę przy ocenie odpowiedzi i tego w którą stronę warto pokierować rozmową czy też zmienić kolejny prompt?
[09:37:11] Speaker: W ocenie pomocne mogą być następujące pytania.
[09:42:39] Speaker: Czy wynik jest dokładny?
[09:45:47] Speaker: Czy wynik zawiera wystarczające informacje?
[09:50:13] Speaker: Czy wynik jest związany z moim projektem lub zadaniem?
[09:56:46] Speaker: W końcu czy uzyskuję spójny wynik zadając wielokrotnie to samo pytanie?
[10:03:40] Speaker: Jeśli podczas oceny wyników zauważysz jakiekolwiek problemy, modyfikowanie początkowego promptu może często pomóc w ich rozwiązaniu i uzyskaniu dużo lepszego rezultatu.
[10:17:50] Speaker: Tak jak podczas gry komputerowej.
[10:20:37] Speaker: Rzadko przechodzi się ją za pierwszym razem.
[10:23:20] Speaker: Warto się nie poddawać i próbować aż do skutku.
[10:27:57] Speaker: Oczywiście tak jak w grze można też grać na kodach i znacząco ułatwić sobie pracę.
[10:35:07] Speaker: W tym przypadku nasze kody to w pełni legalne i skuteczne metody promptowania.
[10:41:49] Speaker: Pierwszą z nich jest few shot prompting.
[10:45:26] Speaker: Co to jest?
[10:47:10] Speaker: Otóż słowa shot czasem używamy jako synonim słowa przykład.
[10:54:39] Speaker: Zatem few shot prompting to promptowanie na podstawie kilku przykładów rozwiązania zbliżonego problemu.
[11:02:26] Speaker: Analogicznie zero shot prompting to promptowanie bez użycia jakichkolwiek przykładów.
[11:10:24] Speaker: Natomiast one shot prompting jest użyciem podpowiedzi z jednym przykładem.
[11:17:31] Speaker: Proste.

___
# 🏷️ Tags
#GenAI
#generatywna_sztuczna_inteligencja
#sztuczna_inteligencja
#AI
#LLM
#large_language_models
#duże_modele_językowe
#uczenie_maszynowe
#machine_learning
#prompt
#prompty
#prompt_engineering
#język_naturalny
#halucynacje
#weryfikacja_odpowiedzi
#iteracja_promptów
#opis_zadania
#kontekst_problemu
#przykład_rozwiązania
#few-shot_prompting
#zero-shot_prompting
#one-shot_prompting
#modele_językowe
#Customer_Engineer
#Google_Cloud_Poland
#Łukasz_Olejniczak
