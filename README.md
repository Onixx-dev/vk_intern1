# coins api

## О проекте

Простой конвертер валют, использующий бесплатное АПИ - https://freecurrencyapi.com  <br />
Основная ветка - master <br />
Визуальная часть реализована на xml верстке. <br />
Проект разделен на три основные части: <br />
data - источники данных. Содержит реализацию репозитория и интерфейс для retrofit2 <br />
domain - содержит модели данных, интерфейс для репозитория и обьекты юзКейсов <br />
app - слой презентации и настроек. Содержит в себе активности и фрагменты + единую ViewModel, первичную настройку приложения и модули DI <br />

## Стек

Базис - Kotlin, coroutines, ViewModel + LiveData <br />
Сеть - Retrofit2 <br />
DI - Koin <br />

## Разработчики

- [Onixx13](https://github.com/Onixx-dev)

## Лицензия

Проект распространяется по лицензии MIT.
