# TASK 1: Testy eksploracyjne
## Subtask 1 - Wyciągamy karteczki...
10/10 punktów :nerd_face:
## Subtask 2 - Dodawanie repozyterium do GitHub
[Moje pierwsze repozyterium](https://github.com/kapromi/challenge_portfolio_kapromi)
## Subtask 3 - Dlaczego zdecydowałaś się na udział w QA Challenge?
Cześć, nazywam się **Karolina** i w końcu dojrzałam do decyzji, żeby nieco zboczyć z dotychczasowej ścieżki zawodowej :upside_down_face: 

Lubię uczyć się nowych rzeczy i fascynują mnie nowe technologie. Już od jakiegoś czasu przeglądałam oferty kursów testerskich, więc gdy zobaczyłam informację w newsletterze Dare IT, to decyzję podjęłam praktycznie od razu. Zawsze staram się korzystać z okazji, które los podkłada mi pod nos. 

Moim głównym celem jest wykorzystanie możliwości kursu na maksa. To czas dla mnie. Wierzę, że w ramach projektu pogłębie wiedzę o testowaniu, może zdobędę nowe znajomości, ale jednocześnie miło spędzę czas dobrze się bawiąc (bo ja naprawdę lubię rozwiązywać zadania!:see_no_evil:).
## Subtask 4 - Testy eksploracyjne - poznaj aplikację _**Scouts**_
### Do czego służy aplikacja? 
Aplikacja _**Scouts**_ umożliwia zbieranie danych o graczach piłki nożnej oraz ich przeglądanie i edytowanie.
### Funkcjonalności aplikacji i propozycje usprawnienia
1. Logowanie i wylogowanie do/z aplikacji.
2. Ustawienie języka aplikacji - polski lub angielski.
3. Przypominanie hasła do konta.
4. Podgląd ostatnich 5 aktywności w aplikacji.
5. Dodawania nowych graczy -  obecnie jest możliwe tylko ze strony głównej - dodałabym przycisk _dodaj gracza_ również z poziomu zakładki _Gracze_ gdzie mamy możliwość ich przeglądania (tak żeby nie trzeba było wracać za każdym razem do strony głównej).
6. Przeglądanie listy graczy wprowadzonych do bazy - w prawym dolnym rogu listy, gdzie mamy informację o ilości wyświetlanych wyników na stronie i ilości wszystkich wyników, dodałabym możliwość przejścia od razu do pierwszej bądź ostatniej strony oraz możliwość wpisania konkretnego numeru strony, żeby np. mieć możliwość od razu przenieść się na stronę 50, a nie "przeklikiwać" się 50 razy. Przydatna byłaby tez możliwość wyświetlania na jednej stronie więcej niż 10 wyników.
7. Wyszukiwanie graczy po dowolnym ciągu znaków.
8. Sortowanie listy graczy po wybranych parametrach.
9. Eksport listy graczy do pliku CSV - zmieniłabym bym to, żeby eksportowała się cała lista wyników (wszystkie podstrony, a nie tylko ta, którą widzimy).
10. Drukowanie listy graczy - wydruk listy graczy jest mało czytelny, moim zdaniem lepszym rozwiązaniem byłby wydruk listy graczy w takiej formie jaką widzimy na stronie, taki sam układ kolumn i wierszy. Obecnie nazwy kolumn przenoszą się do wierszy i są powtarzane dla każdego gracza. Przez to lista 10 graczy, która spokojnie zmieściła by się na stronie A4, drukuje się na 6 stronach.
11. Wyłączanie/włączanie poszczególnych kolumn z widoku listy graczy - w szczegółach gracza widać, że mamy tam dużo więcej parametrów, dodałabym więc tutaj możliwość włączania kolumn również z innymi istotnymi parametrami jak np. główna/alternatywna pozycja, dominująca noga, waga, wzrost, email, telefon, województwo.
12. Filtrowanie graczy po wybranych parametrach - dodałabym możliwość filtrowania po wszystkich parametrach jakie są dostępne. Obecnie nie ma możliwości filtrowania np. po ilości meczy czy ilości raportów.
13. Edytowanie istniejących graczy i zapisywanie zmian.
14. Przeglądanie listy meczy, w których brał udział dany zawodnik.
15. Dodawanie meczy dla danego gracza.
16. Edytowanie meczy dla danego gracza i zapisywanie zmian.
17. Tworzenie raportów dla meczu (do jednego meczu można stworzyć więcej niż jeden raport).
18. Przeglądanie listy raportów.
19. Edytowanie istniejących raportów i zapisywanie zmian.
20. Rozpoczynanie meczu.

Ponadto uzupełniłabym aplikację o poniższe funkcjonalności, które mogłyby być przydatne:
1. Możliwość kasowania graczy/meczy/raportów.
2. Możliwość sortowania/filtrowania meczy/raportów.
3. Funkcja zapisywania wersji roboczych przy dodawaniu graczy/meczy/raportów.
### Ocena interfejsu aplikacji
1. Interfejs jest bardzo prosty, ale dla mnie mało atrakcyjny :wink:
2. Strona główna z poziomu przeglądarki komputera zawiera bardzo dużo pustej przestrzeni, poszczególne "kafelki" usytuowane są głównie w górnej części panelu.
3. Menu po lewej stronie nie jest przejrzyste, wszystko jest wypisane jedno pod drugim. Wydaje mi się, że czytelniej byłoby jakby poszczególne zagnieżdzenia były wcięte z lewej strony, żeby widać było, że są podstroną.
4. Tekst w polach wyświetlanych na listach nie zawija się/nie przenosi do kolejnej linijki (np. długa nazwa klubu gracza powoduje, że cała kolumna robi się bardzo szeroka, co powoduje, że musimy przesuwać całą listę w prawo/w lewo, a przez to źle się ją czyta i źle to wygląda).
5. Zakładki dotyczące meczy i raportów są mało czytelne jeśli przeglądamy je z poziomu telefonu (dużo przesuwania na boki, część kolumn np. z datami ściska się i data jest w trzech wierszach co jest nieczytelne, albo odwrotnie rozciąga się za bardzo, co również utrudnia przeglądanie danych).
### Czy aplikacja jest intuicyjna?
Moim zdaniem to zależy. Część rzeczy faktycznie jest intuicyjna (np. ikony lupy, kosza czy gwaizdki w polach wymaganych), ale sporo jest rzeczy, które na pierwszy rzut oka ciężko rozgryźć. Według mnie poniższe miejsca NIE są intuicyjne:
1. Strona główna zawiera kafelki ze statystykami, ale brakuje opisów. Nie jest oczywiste czym jest _Ilość akcji_? Skąd jest ta liczba?
2. Po wybraniu akcji _Rozpocznij mecz_ przenosimy się do strony, gdzie nie ma żadnej instrukcji jak się poruszać, brakuje opisu poszczególnych przycisków.
3. W trakcie rozgrywania meczu można wysłać raport - pojawia się komunikat _Wysłano poprawnie raport_, ale ciężko stwierdzić gdzie ten raport został wysłany. Nie widać go na liście raportów danego gracza.
4. Brakuje przycisku do edycji graczy - nie każdy domyśli się, że trzeba kliknąć w wiersz z danym graczem aby rozpocząć edycję. 
5. Edytownie bądź dodawania gracza:
    * Nie ma żadnego przycisku _Anuluj_ czy _Wróć_, intuicyjnie byłoby mieć taki przycisk żeby wrócić do poprzedniej strony.
    * Przycisk _Clear_ - sugeruje wyczyszczenie całego formularza, ale tak się nie dzieje w momencie gdy np. edytujemy gracza. Czyszczone są tylko dane, które dodaliśmy przed chwilą. Więc nie do końca jestem przekonana o intuicyjności tego przycisku.
    * Pola _Łączy nas piłka_ oraz _90 minut_ - nie rozumiem do czego one służą :slightly_smiling_face:
    * Pole _Telefon_ - nie wiadomo w jakiej formie ma zostać wpisany, czy jako ciąg znaków czy z kierunkowym kraju czy bez. Zasugerowałabym tu sztywny format, w którym należy wprowadzić numer telefonu.
6. Pole _Search_ w widoku listy graczy szuka we wszystkich parametrach gracza - nawet tych widocznych dopiero w szczegółach. Na początku nie było to dla mnie jasne i myślałam, że wyszukiwarka źle działa, bo w pokazanych wynikach na pierwszy rzut oka nie było tego czego szukałam.
7. Pola _Web match_, _General_ czy _Rating_ w zakładce edycji/dodawania meczy - nie rozumiem co należy wpisać w tych polach, brakuje objaśnienia.
### Błędy znalezione podczas testowania eksploracyjnego
1. Podczas logowania, mimo wybrania języka polskiego komunikat o wprowadzeniu błędnego hasła lub nie wprowadzeniu go w ogóle pojawia się w języku angielskim.
2. Mimo tego, że wybrany mamy język polski, to w zakładce _Gracze_ w prawym górnym rogu listy opisy ikon są po angielsku tj. _Download CSV, Print, View Columns, Filter Table_.
3. Po wyeksportowaniu listy graczy do pliku CSV widać, że dane w pliku nie zawierają polskich znaków.
![screen](https://user-images.githubusercontent.com/115890906/202542759-a267bfac-5da3-4711-bb1a-dda6b8936101.png)
4. Po wyeksportowaniu listy graczy do pliku CSV widać, że "wypluwa" również dane, które nie są prezentowane w tabeli. W pliku CSV widać to jako [object Object], a w Devtoolsach można zobaczyć, że są to dane jeszcze bardziej zagnieżdżone.
![screen](https://user-images.githubusercontent.com/115890906/202544080-c8a1b714-2ee3-45ca-bb35-e409fb51e470.png)
5. W widoku listy graczy, kolumna _Pozycja_ - brak ujednoliconego nazewnictwa, nie wiadomo do którego pola się odnosi - czy do _Pozycja główna_ czy _Pozycja alternatywna_.
6. W widoku listy graczy, po przejściu do _Filter Table_ mamy wymieszane dane/filtry w różnych językach - część jest po polsku (imię, nazwisko, pozycja, klub), a część po angielsku (age, rate). Przyciski na górze okna  _Filters_ i _Reset_ też są po angielsku, pomimo, że mamy wybrany język polski w menu po lewej stronie.
![screen](https://user-images.githubusercontent.com/115890906/202544148-9a99338e-0e75-428d-bdf7-1fd8176d62f7.png)
7. W widoku listy graczy, po przejściu do _Filter Table_ mamy pole _Rate_ natomiast w tabeli nagłówek brzmi _Rating_. Nazwy nie są spójne.
8. W widoku listy graczy mimo wyboru języka polskiego w polu do wyszukiwania wciąż jest angielskie _Search_.
9. Jeżeli skorzystamy z funkcji wyszukiwania graczy (widok listy graczy) i otrzymamy więcej wyników niż 10, to w momencie jak chcemy przejść na kolejną stronę wyszukanych wyników, to aplikacja zamiast pokazać kolejne wyniki dopasowane do tego czego szukaliśmy przeskakuje na pełną listę graczy nie uwzględniając naszego wyszukiwanego słowa.
10. W widoku listy graczy nie można sortować po parametrach wyszukanych wyników. Tzn. jak zawęzimy wyniki do wyszukanego parametru to przy próbie posortowania ich po np. wieku, wskakują znowu wszystkie rekordy z bazy.
11. Sortowanie graczy - sortując graczy np. po wieku od najstarszego do najmłodszego (bądź odwrotnie), w momencie jak zrestartujemy sortowanie strzałka z ostatnim naszym sortowaniem dalej jest wyświetlana mimo tego, że aplikacja już nie sortuje wyników. Dopiero odświeżenie strony sprawia, że strzałka "znika".
![screen](https://user-images.githubusercontent.com/115890906/202544819-a2789ade-d171-4e15-b9f6-959a98ca0907.png)
12. Edytowanie/dodawanie nowego gracza:
    * Pomimo wybranego języka polskiego przyciski _Submit_ i _Clear_ są w języku angielskim.
    * Pomimo wybranego języka polskiego w momencie nie uzupełnienia wymaganych pól z gwiazdką, komunikat na czerwono pojawia się w języku angielskim.
    * Pomimo wybrania języka angielskiego pola _Łączy nas piłka_ i _90 minut_ są wciąż w języku polskim.
    * Pole _Waga_ - brakuje informacji o jednostce w jakiej powinniśmy podać wagę gracza.
    * Apliakcja pozwala w polach wpisać tylko spację i traktuje to już jak uzupełnione pole. W ten spoób można obejść i tak naprawdę nie uzupłenić pól wymaganych.
13. Klikając przycisk _Dodaj raport_ w zakładce z raportami strona przenosi nas do zakładki z meczami, a powinna otworzyć nam okno do tworzenia raportu.
14. Tworzenie raportu z poziomu listy meczy:
    * W pierwszym oknie, które pojawia się po kliknięciu w przycisk _Dodaj raport_ mamy dwa przyciski _Submit_ i _Clear_ - po pierwsze są po angielsku, a mamy ustawiony język polski, a po drugie przycik _Clear_ nie wywołuje żadnej akcji.
    * Pomimo wybranego języka polskiego, w arkuszu mamy angielskie nazewnictwo - wszystkie opisy ikon dotyczących formatowania teksu + informacja o wpisaniu tekstu (_Enter some text…_).
15. Dodawanie/edytowanie meczu dla gracza:
    * Przyciski _Clear_ i _Submit_ niezmiennie są w języku angielskim, pomimo wybrania w menu języka polskiego.
    * Mimo wybranego języka polskiego pola _Web match_ oraz _General_ są po angielsku.
    * Pomimo wybranego języka polskiego w momencie nie uzupełnienia wymaganych pól z gwiazdką, komunikat na czerwono pojawia się w języku angielskim.
    * Pole _Czas gry_ pozwala na wprowadzenie ujemnych wartości, brakuje jednostki, w której należy wprowadzić czas (sekundy? minuty? godziny?).
    * Pole _Numer_ pozwala na wprowadzenie ujemnych wartości
    * Jeżeli wybierzemy język angielski to w kolumnie _Akcje_ pod ikoną piłki widnieje opis _Start report_, zaś w polskiej wersji mamy _Rozpocznij mecz_. Opisy nie są tożsame.
    
    ![screen](https://user-images.githubusercontent.com/115890906/202544224-35dd72c3-627d-4352-80db-2afeec1bf2d2.png)
16. Literówki na pierwszej stronie po zalogowaniu.

      ![screen](https://user-images.githubusercontent.com/115890906/202570385-3d596499-c8af-42a1-b332-f2a162627395.png)

Ponadto poniżej wypisałam punkty, które może nie dotyczą błędów, ale warto byłoby je poprawić, bo wpływają na jakość aplikacji:
1. Edytowanie/dodawanie gracza:
    * W momencie gdy system nie pozwala zapisać formularza, ponieważ jest w nim błąd wyświetla się jedynie komunikat _Nie udało się zaktualizować gracza_, ale żadne pole się nie podświetla, więc użytkownikowi ciężko będzie namierzyć gdzie jest błąd/w którym polu. Dotyczy to błędu w polach, które nie są wymagane.
    * W polach _Imię_ i _Nazwisko_ można wprowadzać również cyfry, raczej powinno być ograniczenie do liter.
    * Pole _Telefon_ nie ma żadnego sztywnego formatu, żeby ujednolicić formę wprowadzania numeru telefonu dla każdego gracza.
    * Pole _Waga_ i _Wzrost_ nie ma ograniczeń, można wprowadzić ujemną wartość bądź nierealnie wysoką
    * Pole _Data urodzenia_ nie ma ograniczeń, można podać datę urodzenia dzisiejszą, z przyszłości albo sprzed kilkuset lat.
    * Pole _Główna pozycja_ i _Pozycja alternatywna_ - zrobiłabym tu listy rozwijane z możliwością wyboru konkretnej opcji, żeby nie wpisywać tej samej pozycji na różne sposoby.
    * Pole _Link do YouTube_ - dobrze żeby było faktycznie linkiem tzn. klikamy w link i przenosi nas od razu na stronę, a nie, że musimy go skopiować i wkleić w oknie przeglądarki.
2. Pole _Recenzja_ przy tworzeniu raportów czy meczy powinno być z gwiazdką jako pole wymagane, bo potem w kolumnie _Recenzja_ wyświetlanej na liście graczy jest średnia recenzji uzyskanych w meczach. Więc żeby ta dana miała jakąś wartość moim zdaniem powinna być wymagana. 
3. Do zastanowienia czy faktycznie możliwość tworzenia kilku raportów do jednego meczu jest prawidłowa.
4. Do zastanowienia czy pola podczas edycji/dodawaniu graczy/meczy/raportów nie powinny mieć ograniczonej liczby znaków.

# TASK 2: Przypadki testowe (Test cases)
## Subtask 1 - Pisanie przypadków testowych na podstawie User Story
### [Przypadki testowe stworzone na podstawie User Story US_01 oraz US_02](https://docs.google.com/spreadsheets/d/1VCoaE2dRgetyU_NoNEZ7naqbTMhlM8Te/edit?usp=sharing&ouid=107944882906340188087&rtpof=true&sd=true)
Test cases do każdego User Story znajdują się w osobnych arkuszach.
## Subtask 2 - Pisanie przypadków testowych na podstawie “własnych doświadczeń"
### [Przypadki testowe stworzone na podstawie "własnych doświadczeń"](https://docs.google.com/spreadsheets/d/1_wQmoDmWLG3PKkCRIPzUGjysDMefc4K_/edit?usp=sharing&ouid=107944882906340188087&rtpof=true&sd=true)
## Subtask 3 - Po co piszemy test case'y?
### Pisanie przypadków testowych pozwala:
* udokumentować w czytelny sposób różne możliwości obsłużenia modułów w ramach danej aplikacji,
* testować funkcjonalności,
* zaplanować scenariusz, który chcielibyśmy przetestować,
* tworzyć raporty z wykonywanych testów,
* tworzyć źródło informacji o danej aplikacji,
* wykorzystywać je później np. do testów akceptacyjnych,
* wielokrotnie uruchamiać testy regresji.

# TASK 3: Raportowanie błędów
## Subtask 1 - Utworzenie formatki do zgłaszania błędów
### [Błędy w aplikacji webowej _Scouts_](https://docs.google.com/spreadsheets/d/1-4lGA37yqhxEcCGebnjHd-BQaUX-NjgK/edit?usp=share_link&ouid=107944882906340188087&rtpof=true&sd=true)
## Subtask 2 - Testowanie aplikacji webowej 
### [Realizacja test case'ów](https://drive.google.com/drive/folders/1mwPniAh1h5bfJQiK4dxhk2rBqBBpoDLr?usp=share_link)
Testowanie aplikacji webowej _Scouts_odbyło się zgodnie z utworzonymi w ramach taska 2 przypadkami testowymi. Stworzone test case'y opierają się zarówno o User Story jak i o "własne doświadczenia".
## Subtask 3 - Raport z wykonanych testów
### [Krótki raport z wykonanych testów aplikacji webowej _**Scouts**_](https://drive.google.com/file/d/10pS4h_8xw_9-x6jY3wR6UB_p3k_2fu36/view?usp=share_link)

# TASK 4: Testowanie aplikacji mobilnych
## Subtask 1 i 2 - Testowanie eksploracyjne i raportowanie błędów
### [Błędy w aplikacji mobilnej _Focusly_](https://docs.google.com/spreadsheets/d/11947aPg4jHtUeIBJJhDxFLuqKBvjF7U4/edit?usp=share_link&ouid=107944882906340188087&rtpof=true&sd=true)
## Subtask 3 - Aplikacja _**Focusly**_
### 1. Do czego służy aplikacja _**Focusly**_? Jaki jest jej cel?
Aplikacja _**Focusly**_ ma na celu wspierać na co dzień użytkowników w osiągnięciu wewnętrznej równowagi oraz edukować w wybranych przez nich obszarach. Aplikacja głównie służy do:
* Przeglądania treści z wybranych kategorii
* Praktykowania ćwiczeń oddechowych
* Słuchania relaksacyjnej muzyki 
* Monitorowania swoich postępów
### 2. Kto ma być użytkownikiem końcowym aplikacji?
* Osoby żyjące w ciągłym stresie.
* Osoby, które chcą osiągnąć wewnętrzny spokój/ciszę/równowagę.
* Osoby, które poszukują pozytywnych zmian w swoim życiu.
* Osoby, które chcą nad sobą pracować.
### 3. Czy według Ciebie aplikacja jest user-friendly?
Moim zdaniem aplikacja jest przyjazna użytkownikowi, łatwo i intuicyjnie można się po niej poruszać. Przyciski znajdują się w standardowych miejscach. Wydaje mi się, że osoba posługująca się na co dzień smartfonem i korzystająca z jakichkolwiek innych aplikacji nie powinna mieć problemu z poruszaniem się po _Focusly_. Wykorzystane kolory są przyjemne dla oka, zgaszone i wyciszające, tym samym nawiązują do idei aplikacji. 
Jedyną rzeczą, która mi osobiście przeszkadza, to to, że pomiędzy ekranami można przechodzić również przesuwając palcem z prawej do lewej strony (bądź odwrotnie). W związku z tym, że na poszczególnych ekranach znajdują się również inne treści, które można przesuwać "w poziomie", to czasami chcąc przejrzeć coś w ramach jednego ekranu, przeskakujemy do kolejnego ekranu (dokładnie widać to na **[tym filmiku](https://drive.google.com/file/d/128csSK3PX7p1QGazWJBzk-lJV4wUstDq/view?usp=share_link)**).
### 4. Jak byś usprawnił aplikację? Co byś poprawił? Czy masz pomysł na dodatkową funkcjonalność?
Dodałabym możliwość rejestrowania się/logowania kontem Google - obecnie bardzo dużo aplikacji posiada taką możliwość, a to dużo przyspiesza i usprawnia proces rejestracji użytkownikom Google.
### 5. Jakie dostrzegasz różnice pomiędzy testowaniem aplikacji internetowej, a natywnej?
* Korzystamy z innych narzędzi - przy testach aplikacji internetowej mamy dostęp np. do DevTools, dzięki, którym widzimy chociażby wysyłane przez stronę requesty. Przy testowaniu aplikacji natywnej nie mamy takich możliwości, dostęp do takich informacji jest ograniczony.
* Przy testach aplikacji natywnych mamy o wiele więcej urządzeń do przetestowania - mamy różne platformy, ale też różne ich wersje oraz także każdy producent ma dodatkowo jeszcze swoje nakładki.
* Przy aplikacjach natywnych wchodzi w grę bardzo dużo zmiennych takich jak chociażby zasięg operatora w danym urządzeniu czy aktualne obciążenie samego urządzenia.
* Przy testowaniu aplikacji webowej adres aplikacji wpisujemy do przeglądarki, zaś przy aplikacjach natywnych pobieramy aplikacje na urządzenie.
## Subtask 4 - Testy aplikacji mobilnej i webowej _**SwipeTo**_ w grupie
### [Błędy zgłoszone z wykorzystaniem Jiry](https://qa768.atlassian.net/jira/software/projects/QAC/boards/1)

# TASK 5: SQL part 1
## Subtask 1 - Krótki kurs podstaw SQL
## Subtask 2 i 3 - Konfiguracja środowiska, wgranie bazy danych i kilka zadań na rozgrzewkę
Poniżej znajduje się tersć zadania, użyte zapytanie oraz prt screen z uzyskanym wynikiem.
1. Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.

   SELECT * FROM actors
   
   ORDER BY surname
   
   ![wynik1](https://user-images.githubusercontent.com/115890906/204157075-5c0e11ea-4a4c-4c13-9c72-41dc6f5ce767.jpg)

2. Wyświetl film, który powstał w 2019 roku.

   SELECT * FROM movies
   
   WHERE year_of_production = 2019
   
   ![wynik2](https://user-images.githubusercontent.com/115890906/204157087-b59c2e34-79aa-4718-8f26-4d5931627e82.png)

3. Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.

   SELECT * FROM movies
   
   WHERE year_of_production BETWEEN 1900 AND 1999
   
   ![wynik3](https://user-images.githubusercontent.com/115890906/204157115-6d23d6e2-3146-49ec-96fd-ec38c9d5eb13.png)

4. Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$

   SELECT title, price	FROM movies

   WHERE price < 7
   
   ![wynik4](https://user-images.githubusercontent.com/115890906/204157118-e183bd1d-00f5-42ef-8d35-87c34cab4e9b.png)

5. Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.

   SELECT * FROM actors
   
   WHERE actor_id >= 4 AND actor_id <=7
   
   ![wynik5](https://user-images.githubusercontent.com/115890906/204157123-5ee57d37-5c90-4ce5-aed3-e3eb39b85af6.png)

6. Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.

   SELECT * FROM customers
   
   WHERE customer_id = 2 OR customer_id = 4 OR customer_id = 6
   
   ![wynik6](https://user-images.githubusercontent.com/115890906/204157131-b36bc551-649b-4939-bc48-be109f6cdeee.png)

7. Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.

   SELECT * FROM customers
   
   WHERE customer_id IN (1,3,5)
   
   ![wynik7](https://user-images.githubusercontent.com/115890906/204157136-21bf81a6-b061-4258-82b5-1caeb666ed78.png)

8. Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.

   SELECT * FROM actors
   
   WHERE name LIKE 'An%'
   
   ![wynik8](https://user-images.githubusercontent.com/115890906/204157143-bb60743e-4061-465d-8429-03e24968a32f.png)

9. Wyświetl dane klienta, który nie ma podanego adresu email.

   SELECT * FROM customers
   
   WHERE email IS NULL
   
   ![wynik9](https://user-images.githubusercontent.com/115890906/204157151-03705977-a4ca-474c-89d4-95cd71081d9c.png)

10. Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.

      SELECT * FROM movies
   
      WHERE price >9 AND movie_id BETWEEN 2 AND 8
   
      ![wynik10](https://user-images.githubusercontent.com/115890906/204157167-4be82b16-b65b-410d-a53f-0769a677bbbe.png)
