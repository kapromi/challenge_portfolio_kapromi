# TASK 1
## Subtask 1
10/10 punktów :nerd_face:
## Subtask 3
Cześć, nazywam się **Karolina** i w końcu dojrzałam do decyzji, żeby nieco zboczyć z dotychczasowej ścieżki zawodowej :upside_down_face: 

Lubię uczyć się nowych rzeczy i fascynują mnie nowe technologie. Już od jakiegoś czasu przeglądałam oferty kursów testerskich, więc gdy zobaczyłam informację w newsletterze Dare IT, to decyzję podjęłam praktycznie od razu. Zawsze staram się korzystać z okazji, które los podkłada mi pod nos. 

Moim głównym celem jest wykorzystanie możliwości kursu na maksa. To czas dla mnie. Wierzę, że w ramach projektu pogłębie wiedzę o testowaniu, może zdobędę nowe znajomości, ale jednocześnie miło spędzę czas dobrze się bawiąc (bo ja naprawdę lubię rozwiązywać zadania!:see_no_evil:).
## Subtask 4
### Do czego służy aplikacja? 
Aplikacja _**Scouts**_ umożliwia zbieranie danych o graczach piłki nożnej oraz ich przeglądanie i edytowanie.
### Funkcjonalności aplikacji i propozycje usprawnienia
1. Logowanie i wylogowanie do/z aplikacji.
2. Ustawienie języka aplikacji - polski lub angielski.
3. Podgląd ostatnich 5 aktywności w aplikacji.
4. Dodawania nowych graczy -  obecnie jest możliwe tylko ze strony głównej - dodałabym przycisk _dodaj gracza_ również z poziomu zakładki _Gracze_ gdzie mamy możliwość ich przeglądania (tak żeby nie trzeba było wracać za każdym razem do strony głównej).
5. Przeglądanie listy graczy wprowadzonych do bazy - w prawym dolnym rogu listy, gdzie mamy informację o ilości wyświetlanych wyników na stronie i ilości wszystkich wyników, dodałabym możliwość przejścia od razu do pierwszej bądź ostatniej strony oraz możliwość wpisania konkretnego numeru strony, żeby np. mieć możliwość od razu przenieść się na stronę 50, a nie "przeklikiwać" się 50 razy. Przydatna byłaby tez możliwość wyświetlania na jednej stronie więcej niż 10 wyników.
6. Wyszukiwanie graczy po dowolnym ciągu znaków.
7. Sortowanie listy graczy po wybranych parametrach.
8. Eksport listy graczy do pliku CSV - zmieniłabym bym to, żeby eksportowała się cała lista wyników (wszystkie podstrony, a nie tylko ta, którą widzimy).
9. Drukowanie listy graczy - wydruk listy graczy jest mało czytelny, moim zdaniem lepszym rozwiązaniem byłby wydruk listy graczy w takiej formie jaką widzimy na stronie, taki sam układ kolumn i wierszy. Obecnie nazwy kolumn przenoszą się do wierszy i są powtarzane dla każdego gracza. Przez to lista 10 graczy, która spokojnie zmieściła by się na stronie A4, drukuje się na 6 stronach.
10. Wyłączanie/włączanie poszczególnych kolumn z widoku listy graczy - w szczegółach gracza widać, że mamy tam dużo więcej parametrów, dodałabym więc tutaj możliwość włączania kolumn również z innymi istotnymi parametrami jak np. główna/alternatywna pozycja, dominująca noga, waga, wzrost, email, telefon, województwo.
11. Filtrowanie graczy po wybranych parametrach - dodałabym możliwość filtrowania po wszystkich parametrach jakie są dostępne. Obecnie nie ma możliwości filtrowania np. po ilości meczy czy ilości raportów.
12. Edytowanie istniejących graczy i zapisywanie zmian.
13. Przeglądanie listy meczy, w których brał udział dany zawodnik.
14. Dodawanie meczy dla danego gracza.
15. Edytowanie meczy dla danego gracza i zapisywanie zmian.
16. Tworzenie raportów dla meczu (do jednego meczu można stworzyć więcej niż jeden raport).
17. Przeglądanie listy raportów.
18. Edytowanie istniejących raportów i zapisywanie zmian.
19. Rozpoczynanie meczu.

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
### Błędy
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

# TASK 2
## Subtask 1
### [Pisanie przypadków testowych na podstawie User Story](https://docs.google.com/spreadsheets/d/1VCoaE2dRgetyU_NoNEZ7naqbTMhlM8Te/edit?usp=sharing&ouid=107944882906340188087&rtpof=true&sd=true)
Przypadki testowe do każdego User Story znajdują się w osobnych arkuszach.
## Subtask 2
### [Pisanie przypadków testowych na podstawie “własnych doświadczeń"](https://docs.google.com/spreadsheets/d/1_wQmoDmWLG3PKkCRIPzUGjysDMefc4K_/edit?usp=sharing&ouid=107944882906340188087&rtpof=true&sd=true)
## Subtask 3
### Po co piszemy test case’y?
Pisanie przypadków testowych pozwala:
* udokumentować w czytelny sposób różne możliwości obsłużenia modułów w ramach danej aplikacji,
* testować funkcjonalności,
* zaplanować scenariusz, który chcielibyśmy przetestować,
* tworzyć raporty z wykonywanych testów,
* tworzyć źródło informacji o danej aplikacji,
* wykorzystywać je później np. do testów akceptacyjnych,
* wielokrotnie uruchamiać testy regresji.

# TASK 3
## Subtask 1
### [Formatka do zgłaszania błędów](https://docs.google.com/spreadsheets/d/1-4lGA37yqhxEcCGebnjHd-BQaUX-NjgK/edit?usp=share_link&ouid=107944882906340188087&rtpof=true&sd=true)
## Subtask 2
### [Realizacja test case'ów](https://drive.google.com/drive/folders/1mwPniAh1h5bfJQiK4dxhk2rBqBBpoDLr?usp=share_link)
## Subtask 3
### [Raport z wykonanych testów](https://drive.google.com/file/d/10pS4h_8xw_9-x6jY3wR6UB_p3k_2fu36/view?usp=share_link)

# TASK 4 
## Subtask 2
### Testowanie eksploracyjne i raportowanie błędów
## Subtask 3
### Do czego służy aplikacja?
