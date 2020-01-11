# dswp
Repozytorium testowe przedmiotu "Warsztat badacza danych"
```python
def zadanie1():
    lista = []
    while True:
        wejscie = input("Podaj liczbe:")
        if wejscie == '':
            # koniec pętli
            break
        else:
            lista.append(int(wejscie))
    # podsumowanie
    print("Suma {0}".format(sum(lista)))
    print("Ilość liczb {0}".format(len(lista)))
    print("Średnia {0}".format(sum(lista)/len(lista)))
```
