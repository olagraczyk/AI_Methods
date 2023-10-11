# AI_Methods

**#Notes from classes

**9.10 
lab1_students****
1. Ściągnęłam anaconda, ściągnęłam jupyter notebook
2. dataset z kaagle ma być zapisany w tym samym folderze

df - data set
df.describe() - opisuje dane ilościowe. Warto wyświetlić, żeby zobaczyć czy nie ma braków danych
ogólnie nie wyświetla się wszystkich elementów z tabeli. ale można to zrobić pętlą jeśli szuka się jakiśgłupotek, jak np braków danych

**lab1_water**
NaN - wyświetli zarówno jak nic nie ma i jak spodziewa się liczby a ma coś innego.
żeby poradzić sobie z brakami danych można
    - zamienić je na medianę (ale zmieni nam si e rozkład, więc trzeba uważać)
    - wyrzucić te kolumny (ale minus bo my chcemy mieć jak najwięcj danych)
    
**lab1_1.4 sklearn i SVM - zadanie**
df['Species'].value_counts() - podsumowanie kolumny
dobrze, że zbiory są równoliczne, bo będą się tak samo uczyć.

**UCZENIE MASZYNOWE**
1. SVM
- chozi o to żeby znaleźć jak najlepszą linię która odseparuje różniące się dane od siebie. 
- jest dla danych binarnych, a żeby wykorzystać do więcej klas niż 2 to ściągamy SVC

- ważne jest żeby wyodrębnić dane uczące się oraz testowe (mamy do tego funkcję)

  Sprawdzając klasyfikator ustwiamy wartość random_state.
  Ten parametr kontroluje inicjalizację generatora liczb pseudolosowych, co ma wpływ na losowość wyników w wielu operacjach. Ustawiając random_state na konkretną liczbę (na przykład 42), uzyskasz deterministyczne wyniki, co oznacza, że te same operacje będą zawsze dawać te same wyniki, pod warunkiem, że pozostałe ustawienia i dane pozostaną takie same.
Warto dodać, że konkretna wartość random_state nie ma znaczenia; ważne jest tylko to, że jest ustawiona na określoną wartość, która jest taka sama w różnych miejscach w kodzie, aby uzyskać te same wyniki. W praktyce używa się różnych wartości, takich jak 42, ponieważ jest to liczba intuicyjna i często używana jako przykładowa wartość.

**Heart Attact Prediction**
Zadanie domowe
Stworzenie modelu sztucznej sieci neuronowej, która pozwala przewidzieć czy u osoby jest większe ryzyko wystąpienia ataku serca
