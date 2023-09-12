## Elementy niezbędne przy zgłaszaniu błędu:

### Tytuł 
Krótki i treściwy, na samym początku powinien zawierać słowo klucz (co nie działa)
np.

– Po naciśnięciu przycisku „Save” na ekranie pojawia się komunikat z błędem

– Dodając produkt do koszyka, jego ilość zwiększa się dwukrotnie i nie można go usunąć

– Po wprowadzeniu złego formatu danych w polach rejestracji, nie podkreślają się pola, które są wypełnione błędnymi danymi.


### Priorytet

Pozwala określić, jak szybko dany problem musi zostać rozwiązany, czy jest to błąd blokujący, krytyczny, ważny czy może mało istotny z biznesowego punktu widzenia i nie wpływa on na resztę serwisu.


### Środowisko / Wersja / Zespół / Urządzenie

- na jakim środowisku wystąpił dany błąd, czy było to środowisko testowe produkcyjne, czy jeszcze inne
  
-  w jakiej wersji naszej aplikacji dany błąd wystąpił i dodatkowo w jakiej wersji powinien on zostać naprawiony
  
- przypisanie błędu do danego zespołu (zespół, który zajmował się daną funkcjonalnością, szybciej naprawi błąd)
  
- wpisanie urządzenia, na którym występuje dany błąd, jest dużym ułatwieniem dla programistów
  
### Opis

Krótki, konkretny, pomoże zdobyć szybką informację na temat tego, o co chodzi w tym błędzie i być może nakierować programistę, z czego dany błąd wynika.


### Kroki

Dokładnie opisana instrukcja krok po kroku, co należy zrobić, aby dany błąd wystąpił, jest ogromnym ułatwieniem zarówno dla programistów, jak i testerów, którzy będą testować poprawiony błąd. Dobą praktyką jest wykorzystywanie kroków zawartych w często powtarzających się błędach do napisania do nich Test Cases i dzięki temu obszar narażony na występowanie w nim poważnych błędów może być sprawdzany cyklicznie np. w ramach regresji.


### Rzeczywisty rezultat
Czyli wytłumaczenie co dokładnie jest dla nas błędem, czy pokazujący się nadmierny komunikat, czy też może brak walidacji na polu itp.

### Oczekiwany rezultat
Krótki opis tego, jak po wykonaniu opisanych wyżej kroków aplikacja powinna się zachować i jeśli posiadamy dokumentację opisującą daną część -> pokazanie, jak według dokumentacji lub wytycznych powinno to działać.

### Załączniki
Wszelkiego rodzaju zrzuty ekranu, filmiki, logi z konsoli, wszystko to, co może pomóc w określeniu miejsca, gdzie dany błąd występuję i co jest jego przyczyną.


