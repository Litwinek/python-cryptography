### Dokumentacja 11.12.23
# Skrypt który tworzy szyfr cezara.
### Język programowania który zastosowałem to Python z uwagi na prostotę i niski próg wejścia.

```python
ALPHABET = ' !ABCDEFGHIJKLMNOPQRSTUVWXYZ'
KEY = 3
```
###### Na samym początku zobowiązani jesteśmy do zadeklarowania 2 zmiennych, jedna z nich będzie w sposób statyczyny przechowywać angielski alfabet, druga zaś klucz potrzebny do szyfrowania.
###### Szyfr Cezara jest szyfrowaniem symetrycznym, a więc potrzebujemy jednego klucza który będzie nam potrzebny do szyfrowania naszej wiadomości oraz odszyfrowywania jej, ten klucz jest zwany kluczem prywatnym (private key).
###### Szyfrowanie odbywa się za pomocą zastępowania znaków naszej wiadomości znakami zadeklarowanymi w zmiennej o nazwie ALPHABET. Jednak najpierw musimy wyznaczyć wzór według którego algorytm będzie szyfrował nasze wiadomości.
![równanie-szyfr-cezara](encryption-equation.png)