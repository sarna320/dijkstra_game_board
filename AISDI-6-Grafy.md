## Algorytmy i struktury danych – grafy

### Problem

Dana jest plansza o dowolnych wymiarach. Na dwóch polach planszy znajduje się cyfra 0. Na pozostałych polach planszy znajdują się cyfry z przedziału od 1 do 9. Na przykład:

~~~
111122
104122
942111
996411
990411
991111
~~~

Przyjmijmy teraz, że po polach można się przemieszczać w kierunkach prawo-lewo i góra-dół (lecz nie na skos), a cyfry oznaczają koszt **opuszczenia** (zejścia z) pola. Zadanie polega na napisaniu programu, który:

1. wczyta planszę z pliku (nazwa pliku przekazana jako argument wywołania programu);

2. korzystając z algorytmu Dijkstry, znajdzie dowolną z najmniej kosztownych tras przejścia pomiędzy polami z cyfrą 0;

3. wyświetli pola planszy (cyfry znajdujące się na tych polach), które leżą na znalezionej trasie.

Przykładowo, zakładając, że plik `graf1.txt` zawiera powyższą planszę, wynikiem działania programu powinno być:

~~~
$ python program.py graf1.txt
 111
 0 1
   11
    1
  0 1
  111
~~~

### Wyniki

Rezultatem powinny być:

* kod źródłowy programu;

* 3 pliki tekstowe z przykładowymi planszami (innymi niż plansza z treści zadania) o różnych wymiarach;

* trzy zrzuty ekranu z wynikami działania programu dla przykładowych plansz.

### Ocena

Zadanie oceniane jest w skali 0-6 pkt.