# Agencja_nieruchomosci_KP
Projekt z przedmiotu Analiza Danych Paweł oraz Kacper pozdro
#summary(data)
# Znajdź liczbę brakujących wartości w każdej kolumnie
colSums(is.na(data))
# Znajdź wiersze z brakującymi wartościami
which(rowSums(is.na(data)) > 0)
# Całkowita liczba brakujących wartości
sum(is.na(data))
#dodałem sprawdzenie danych, aby upewnić się czy nie ma braków N/A itp. Żadnych braków nie wykyto, dane są kompletne. Plik zawiera 545 wierszy i 13 kolumn z danymi dotyczącymi nieruchomości.
