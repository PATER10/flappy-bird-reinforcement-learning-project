# Zastosowanie uczenia ze wzmocnieniem w grze typu Flappy Bird

## Opis projektu
Projekt polega na rozwiązaniu problemu nieskończonego horyzontu (survivalowego) w dynamicznym środowisku przewijanym bocznie (2D). Cel projektu to stworzenie agenta sterującego obiektem, który uczy się autonomicznie omijać przeszkody (rury) i unikać kolizji z podłożem, wykorzystując metody uczenia ze wzmocnieniem (RL).

Środowisko fizyczne gry zostało oparte na silniku Unity, z którym agent komunikuje się za pomocą dedykowanego interfejsu API, otrzymując w czasie rzeczywistym stan środowiska (współrzędne ptaka i rur) i podejmując decyzje o skoku lub swobodnym opadaniu.

## Struktura repozytorium
* `src/` - Kod źródłowy środowiska oraz agentów (bazowego i uczącego się)
* `experiments/` - Skrypty i konfiguracje do przeprowadzania eksperymentów
* `report/` - Pliki źródłowe sprawozdania w systemie LaTeX
* `results/` - Zapisane modele, wykresy i tabele z wynikami

## Instrukcja uruchomienia
*(Instrukcja zostanie uzupełniona w kolejnych etapach prac nad projektem)*
