# Sekcja 1. Wprowadzenie do generatywnej AI oraz jak promptować - 2. Metody promptowania

# 💡 Diagram

```mermaid
mindmap
  root((Efektywne Wykorzystanie AI i Techniki Promptowania))
    Wprowadzenie
      c[Wiele osób nie zna narzędzi AI (np. Jenny AI)]
      d[Mało osób używa AI regularnie w pracy]
      e[Skupienie na zaawansowanych technikach promptowania kluczowe]
    Prompt Chaining (Ciąg Podpowiedzi)
      a[Definicja: Wynik promptu jako kontekst dla kolejnego]
      b[Rozbija złożone problemy na mniejsze kroki]
      Kroki Utworzenia
        ba[1. Podziel zadanie na kroki]
        bb[2. Stwórz prompt dla każdego kroku]
        bc[3. Użyj wyjścia z promptu jako wejścia do następnego]
      Efektywne Wykorzystanie
        ca[Punkty kontrolne: Podsumowanie celu]
        cb[Praca z podzadaniami: Mniejsze podzadania]
        cc[Podsumuj i przekieruj: Korekta kursu]
    Chain of Thought (Łańcuch Myśli)
      a[Definicja: Sekwencja działań w jednym rozbudowanym promtpie]
      b[Model samodzielnie przechodzi kroki]
      c[Przydatne w zadaniach wymagających większego wysiłku intelektualnego]
      d[Vs Prompt Chaining: Jeden rozbudowany prompt vs Seria promptów]
    Generowanie Obrazów z AI
      a[Kluczowe Elementy Promptu]
        aa[Precyzyjny opis]
        ab[Styl obrazka (np. fotorealistyczny, akwarelowy)]
        ac[Kolorystyka (np. czarno-biała, pastelowa)]
        ad[Parametry (np. proporcje 16:9)]
        ae[Perspektywa (np. z lotu ptaka, z poziomu oczu)]
      b[Dodatkowe Możliwości Generatywnej AI]
        ba[Tabele]
        bb[Prezentacje]
        bc[Maile 📧]
        bd[Arkusze kalkulacyjne]
    Podsumowanie i Zakończenie
      a[Generatywna AI - potężne narzędzie]
      b[Umiejętność promptowania jest kluczowa]
        ba[Prompt Chaining]
        bb[Chain of Thought]
      c[Eksperymentowanie i iteracja z AI]
      d[Użytkownik musi zrobić pierwszy krok (napisać prompt)]
      e[Dostępny pięcioetapowy schemat promptowania do pobrania]
```

___

# 🗒️ Notatka


# Szczegółowe Notatki i Podsumowanie Wideo o AI

## Wprowadzenie

Prelegent rozpoczyna prezentację, zwracając uwagę, że wiele osób w branży może nie być zaznajomionych z narzędziami AI, takimi jak Jenny AI.  Zauważa, że choć niektórzy próbowali pisać proste `prompty`, regularne i zaawansowane wykorzystanie AI w pracy jest wciąż rzadkością. Prelegent zachęca do skupienia się na zaawansowanych technikach `promptowania`, aby osiągnąć mistrzostwo w korzystaniu z AI.

## `Prompt Chaining` - Ciąg Podpowiedzi

### Definicja i Zasada Działania

- **`Prompt chaining`**, czyli **ciąg podpowiedzi**, to technika wykorzystująca wynik jednego `promptu` jako kontekst dla kolejnego polecenia.
- Narzędzie AI jest prowadzone przez serię połączonych `promptów`, co umożliwia dodawanie kolejnych zadań i warstw kontekstowych.
- Technika ta pomaga modelowi AI w rozwiązywaniu **złożonych problemów** poprzez rozbicie ich na mniejsze, łatwiejsze do zarządzania kroki.

### Jak Utworzyć Ciąg Podpowiedzi - 3 Kroki

1. **Podziel złożone zadanie na logiczne kroki.**
2. **Stwórz `prompt` dla każdego kroku.**
3. **Wykorzystaj dane wyjściowe z jednego `promptu` jako dane wejściowe do następnego**, powtarzając proces aż do ukończenia zadania.

### Efektywniejsze Wykorzystanie `Prompt Chainingu` - Wskazówki

- **Używaj punktów kontrolnych:** Poproś model o krótkie podsumowanie ogólnego celu zapytania.
- **Pracuj z podzadaniami:** Rozdziel złożone zadania na jeszcze mniejsze podzadania.
- **Podsumowuj i przekierowuj:** Jeśli model oddala się od celu, podsumuj dotychczasowe informacje i skieruj go z powrotem na właściwe tory w kolejnym `prompcie`.

## `Chain of Thought` - Łańcuch Myśli

### Definicja i Porównanie z `Prompt Chainingiem`

- **`Chain of thought`**, czyli **łańcuch myśli**, to technika, w której cała sekwencja działań potrzebnych do rozwiązania problemu jest zawarta w **jednym, bardziej rozbudowanym `prompcie`.**
- W przeciwieństwie do serii oddzielnych `promptów` (jak w `prompt chaining`), `chain of thought` **zakłada, że model zastosuje podobny tok rozumowania** i samodzielnie przejdzie przez logiczne kroki w ramach jednego zapytania.
- Ta technika jest szczególnie przydatna w zadaniach wymagających **większego wysiłku intelektualnego**.

### Zastosowanie Technik `Promptowania`

- Zarówno `prompt chaining`, jak i `chain of thought` **zwiększają szansę na uzyskanie prawidłowej odpowiedzi** w przypadku złożonych zadań.
- Są szczególnie przydatne w zadaniach wymagających **większego wysiłku intelektualnego**.

## Generowanie Obrazów z AI - Jak Stworzyć Dobry `Prompt`

### Kluczowe Elementy Dobrego `Promptu` do Obrazka

1. **Precyzyjny opis:** Jasno określ, co chcesz uzyskać.
2. **Styl obrazka:** Określ preferowany styl, np. `fotorealistyczny`, `akwarelowy`.
3. **Kolorystyka:** Wybierz preferowaną kolorystykę, np. `czarno-biała`, `pastelowa`.
4. **Parametry:** Ustal dodatkowe parametry, np. `proporcje obrazu 16:9`.
5. **Perspektywa:** Zdefiniuj perspektywę, z jakiej ma być przedstawiony obraz, np. `z lotu ptaka`, `z poziomu oczu`.

### Dodatkowe Możliwości Generatywnej AI

- Generatywna AI potrafi tworzyć nie tylko obrazy, ale także:
    - **Tabele**
    - **Prezentacje**
    - **Maile** 📧
    - **Arkusze kalkulacyjne**
- Więcej informacji na temat kreatywnego wykorzystania AI zostanie przedstawione w dalszej części programu.

## Podsumowanie i Zakończenie

- Generatywna sztuczna inteligencja oferuje szerokie możliwości i stanowi potężne narzędzie w pracy.
- Kluczem do efektywnego wykorzystania AI jest **umiejętność tworzenia odpowiednich `promptów`**, w tym zaawansowanych technik takich jak `prompt chaining` i `chain of thought`.
- Prelegent zachęca do **eksperymentowania i iterowania** z AI, podkreślając, że to użytkownik musi wykonać **pierwszy krok** i napisać pierwszy `prompt`.
- Dostępny jest **pięcioetapowy schemat `promptowania`** do pobrania, który może pomóc w rozpoczęciu pracy z AI.

---

**Podsumowanie:**

Prezentacja wideo koncentruje się na efektywnym wykorzystaniu sztucznej inteligencji, ze szczególnym uwzględnieniem `promptowania`. Prelegent omawia dwie zaawansowane techniki: **`prompt chaining` (ciąg podpowiedzi)** i **`chain of thought` (łańcuch myśli)**. `Prompt chaining` polega na dzieleniu złożonych zadań na mniejsze etapy i wykorzystywaniu wyników jednego `promptu` jako kontekstu dla kolejnego. `Chain of thought` to technika, w której cała logika rozwiązania problemu jest zawarta w jednym, rozbudowanym `prompcie`. W dalszej części prezentacji omówiono kluczowe elementy skutecznego `promptowania` przy generowaniu obrazów, takie jak precyzyjny opis, styl, kolorystyka, parametry i perspektywa. Podsumowując, prelegent podkreśla szerokie możliwości generatywnej AI, zachęca do eksperymentowania i przypomina, że inicjatywa w korzystaniu z AI należy do użytkownika. Dostępny schemat `promptowania` ma ułatwić rozpoczęcie pracy z tą technologią.


___

# 🔉 Transcript
File: Sekcja 1. Wprowadzenie do generatywnej AI oraz jak promptować - 2. Metody promptowania.mp4<br>
[00:00:05] Speaker: Większość osób z waszej branży, otoczenia, czy nawet miejsca pracy może nawet nie słyszało o Jenny AI.
[00:00:12] Speaker: Wiele z nich spróbowało napisać jakiegoś prompta i użyć tego do maila.
[00:00:19] Speaker: Bardzo mało osób jednak jeszcze używa AI regularnie w pracy, a jeszcze mniej stosuje zaawansowane techniki promptowania, o których zaraz opowiem.
[00:00:31] Speaker: Jeśli chcecie być najlepsi w korzystaniu z AI, to teraz warto się skupić.
[00:00:36] Speaker: Jedną z technik jest wykorzystanie wyniku jednego prompta jako kontekst w kolejnym poleceniu dla modelu.
[00:00:44] Speaker: Nazywamy to prompt chainingiem, inaczej ciągiem podpowiedzi.
[00:00:44] Screen: (A slide is displayed. The title reads "Prompt chaining - ciąg podpowiedzi". Two bullet points are listed: "Wykorzystanie wyniku jednego prompta jako kontekstu w kolejnym poleceniu" and "Pomaga modelowi rozwiązywać złożone problemy, dzieląc je na mniejsze kroki")
[00:00:50] Speaker: Prompt chaining prowadzi narzędzie AI przez serię połączonych ze sobą promptów, dodając kolejne zadania i warstwy kontekstowe.
[00:01:02] Speaker: Połączone prompty sprawiają, że pomagamy modelowi rozwiązać skomplikowane problemy, rozbijając je na mniejsze części.
[00:01:11] Speaker: I rozwiązując je później krok po kroku.
[00:01:14] Speaker: Taki ciąg podpowiedzi tworzy się w trzech krokach.
[00:01:19] Speaker: Zacznij od podzielenia złożonego zadania na logiczne kroki.
[00:01:24] Speaker: Skonstruuj prompt do każdego kroku i użyj danych wyjściowych z jednego promptu jako danych wejściowych do następnego, iterując po drodze, aż do ukończenia zadania.
[00:01:40] Speaker: Zróbmy to razem.
[00:01:40] Speaker: Chain prompting to świetna technika na bardziej zaawansowane problemy.
[00:01:46] Speaker: Oto parę podpowiedzi ode mnie na temat tego, jak wycisnąć z chain promptingu więcej.
[00:01:53] Speaker: Po pierwsze, zdefiniuj sobie punkty kontrolne, czyli określ proś model o krótkie podsumowanie ogólnego celu twojego pytania.
[00:01:53] Screen: (A slide is displayed. The title reads "Jak efektywniej wykorzystać chain prompting". The first bullet point reads "Używaj punktów kontrolnych" and the second reads "Określono proś model o krótkie podsumowanie ogólnego celu")
[00:02:05] Speaker: Po drugie, praca z podzadaniami.
[00:02:09] Speaker: Podziel bardzo złożone zadania na jeszcze mniejsze podzadania.
[00:02:15] Speaker: Po trzecie, podsumowanie i przekierowanie.
[00:02:20] Speaker: Jeśli zauważysz, że model odbiega od pierwotnego celu twojego pytania, podsumuj najważniejsze informacje, które model zebrał do tej pory i przekieruj je w kolejnym prompcie z powrotem do głównego celu.
[00:02:36] Speaker: Istnieje również technika promptowania chain of thought, łańcuch myśli, w której sekwencja, którą przed chwilą przeszliśmy, jest obsłużona jednym, bardziej rozbudowanym promptem.
[00:02:36] Screen: (A slide is displayed. The title reads "Jak efektywniej wykorzystać chain prompting". The first bullet point reads "Podziel złożone zadania na mniejsze części. Traktuj każde podzadanie jako krótkotrwały zarin przydzielić się do następnego kroku" and the second reads "Podsumuj i przekieruj: Jeśli model odbiega od celu, podsumuj kluczowe informacje i skieruj go z powrotem do głównego celu")
[00:02:52] Speaker: W prompcie tym podajemy kroki i pewien tok rozumowania potrzebny do rozwiązania podobnego problemu.
[00:03:02] Speaker: Rozwiązanie tego podobnego problemu również polegało będzie na przejściu sekwencji logicznych kroków, które w poprzedniej technice wykonywaliśmy jako osobne prompty.
[00:03:18] Speaker: W technice chain of thought zakładamy, że model zastosuje podobny tok rozumowania i obsłuży wszystkie kroki jednym promptem.
[00:03:31] Speaker: Stosując te sposoby, zwiększamy szansę na uzyskanie prawidłowej odpowiedzi w przypadku zadań wymagających większego wysiłku intelektualnego.
[00:03:31] Screen: (A slide is displayed. The title reads "Chain of Thought - łańcuch myśli". The first bullet point reads "Łańcuch myśli, w którym sekwencja działań jest obsłużona jednym, bardziej rozbudowanym promptem" and the second reads "Przejście przez sekwencję logicznych kroków w ramach jednego promptu, zamiast wykonywać je jako osobne zapytanie")
[00:03:41] Speaker: Na koniec zostawiłem dla was coś specjalnego, czyli obrazy.
[00:03:41] Screen: (A slide is displayed. The title reads "Stosując te techniki:". The first bullet point reads "Zwiększamy szansę na uzyskanie prawidłowej odpowiedzi" and the second reads "Sprawdzamy się w zadaniach wymagających większego intelektualnego")
[00:03:46] Speaker: A dokładniej generowanie obrazów, ilustracji, czy też zdjęć do dowolnego zastosowania.
[00:03:46] Screen: (A slide is displayed. The title reads "Jak stworzyć dobry prompt pod obrazek?". The first bullet point reads "Precyzyjny opis: Jasno określ, co chcesz uzyskać")
[00:04:01] Speaker: Dobry prompt pod obrazek zawiera to wszystko, co już wiecie, czyli precyzyjny opis czego oczekujemy.
[00:04:09] Speaker: Plus cztery dodatkowe rzeczy.
[00:04:12] Speaker: Styl obrazka, na przykład chcemy, żeby nasze zdjęcie było wygenerowane jako fotorealistyczne.
[00:04:12] Screen: (A slide is displayed. The word "STYL" is in a yellow box. The word "fotorealistyczny, akwarelowy" is listed below)
[00:04:20] Speaker: Drugie to preferowana kolorystyka.
[00:04:20] Screen: (A slide is displayed. The word "KOLORYSTYKA" is added to the slide in a green box. The words "czarno-biała, pastelowa" are listed below)
[00:04:27] Speaker: Na przykład chcemy, żeby nasze zdjęcie było czarno-białe.
[00:04:27] Speaker: Trzecie to dodatkowe parametry, jak na przykład chcemy, żeby zdjęcie było w proporcjach 16:9.
[00:04:27] Screen: (A slide is displayed. The word "PARAMETRY" is added to the slide in a blue box. The words "proporcje obrazu 16:9" are listed below)
[00:04:35] Speaker: I czwarte perspektywa.
[00:04:37] Speaker: Chcemy, żeby nasze zdjęcie było z lotu ptaka.
[00:04:37] Screen: (A slide is displayed. The word "PERSPEKTYWA" is added to the slide in a red box. The words "z lotu ptaka, z poziomu oczu" are listed below)
[00:04:42] Speaker: Generatywna AI może wygenerować, oczywiście, o wiele wiele więcej.
[00:04:49] Speaker: Mowa tutaj między innymi o tabelach, prezentacjach, mailach oraz arkuszach.
[00:04:56] Speaker: Więcej o nich i innych kreatywnych elementach dowiecie się w dalszej części programu.
[00:05:03] Speaker: Gratulacje.
[00:05:05] Speaker: Dotarliście do końca.
[00:05:06] Speaker: Zdaję sobie sprawę, że niektórym mogą głowy parować od ilości wiedzy i nowych pojęć.
[00:05:12] Speaker: Dlatego, gdy już ochłoniecie i będziecie chcieli poeksperymentować z, to możecie zajrzeć do przygotowanego dla was pięcioetapowego schematu promptowania.
[00:05:24] Speaker: Możecie go teraz pobrać na swoje telefony, komputery, tablety, by mieć go pod ręką.
[00:05:31] Speaker: Możecie też wrócić do tej lekcji w dowolnym czasie.
[00:05:35] Speaker: Generatywna sztuczna inteligencja może zrobić dla was bardzo wiele rzeczy, ale jednej na pewno nie zrobi.
[00:05:43] Speaker: Nie zrobi pierwszego kroku, nie napiszę pierwszego prompta.
[00:05:47] Speaker: Tutaj piłka jest po waszej stronie.
[00:05:50] Speaker: Dziękuję za waszą uwagę i życzę jak najwięcej frajdy z odkrywania, eksperymentowania i iterowania z generatywną sztuczną inteligencją.
[00:06:00] Screen: (The "Umiejętności Jutra AI" logo appears)

___
# 🏷️ Tags
#ai #sztuczna_inteligencja #prompt #prompt_engineering #prompt_chaining #ciąg_podpowiedzi #chain_of_thought #łańcuch_myśli #generatywna_ai #generowanie_obrazów #prompt_do_obrazka #precyzyjny_opis #styl_obrazka #kolorystyka #parametry_obrazu #perspektywa_obrazu #punkt_kontrolny #podzadania #podsumowanie #przekierowanie #zaawansowane_techniki_promptowania #efektywne_wykorzystanie_ai #eksperymentowanie_z_ai #iterowanie_z_ai #narzędzia_ai #jenny_ai #złożone_problemy #logiczne_kroki #większy_wysiłek_intelektualny #tabele #prezentacje #maile #arkusze_kalkulacyjne #pięcioetapowy_schemat_promptowania #fotorealistyczny #akwarelowy #czarno-biała #pastelowa #proporcje_obrazu_16:9 #z_lotu_ptaka #z_poziomu_oczu
