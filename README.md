# Aplikacja webowa do HarcApo 2.0

Aplikacja stworzona jako wsparcie do prowadzenia akcji harcerskiej HarcApo 2.0 przez
Zielonogórski Hufiec Harcerzy Topór (Związek Harcerstwa Rzeczypospolitej).

## Uruchomienie

Instrukcja przygotowana pod Linuxa, Python w wesji 3.6 bądź wyższej.

Stworzenie środowiska:

```shell
make venv
```

Przygotowanie bazy danych i dodanie przykładowych wartości do bazy (przed pierwszym startem i po każdej zmianie modeli aplikacji):

```shell
make dev-prepare
```

Uruchomienie aplikacji (na adresie 127.0.0.1:8000 bądź innym, podanym w terminalu)

```shell
make run
```

Uruchomienie testów

```shell
make test
```