# currency_gbp

Данный проект представляет собой тестовое задание, выполненное в рамках подготовки к Golang Bootcamp Perm 2017.

Для загрузки исходного файла и зависимостей необходимо выполнить команду:

```
go get github.com/Aspirin4k/currency_gbp
```

Для установки исполнить:

```
go install github.com/Aspirin4k/currency_gbp
```

Программа принимает на вход 2 параметра:

```
currency_gbp --currency=RUB --value=100
```

Первый параметр устанавливает валюту (По умолчанию USD), второй - количество этой валюты (По умолчанию 10).
На выходе выводится список остальных валют и соответствующее значение (Например, 1 USD - это 59.13 RUB)
