# online-store-api
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FAndreyCh1989%2Fonline-store-api.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2FAndreyCh1989%2Fonline-store-api?ref=badge_shield)

В этом репозитории хранится API для интернет-магазина с заглушками. API возвращает тестовые данные. 

Пожалуйста, используйте это API на курсах по frontend-разработке на языке Javascript, а также при разработке мобильного приложения для интернет-магазина. С его помощью вы получите работающий интернет-магазин с тестовыми данными.

Описание соглашений по работе API содержится в файле [API Description.xlsx](https://github.com/GeekBrainsTutorial/online-store-api/blob/master/API%20Description.xlsx) в корне репозитория. 

# Правила использования статических JSON-файлов
Для получения статического JSON-ответа можно обращаться по URL-адресу 

https://raw.githubusercontent.com/GeekBrainsTutorial/online-store-api/master/responses/имяФайла.json

Это вернет чистый JSON-ответ согласно прилагающейся документации.

Обратите внимание, что кросс-доменные запросы не поддерживаются браузерами, ниже IE9. В случае использования такового
рекомендуется разместить репозиторий локально на компьютере, где производится тестирование.

Для кросс-доменных запросов установка свойства content в что-то отличное от application/x-www-form-urlencoded, multipart/form-data или text/plain приведет к тому, что
браузер отправит дополнительный предварительный OPTIONS-запрос на сервер.


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FAndreyCh1989%2Fonline-store-api.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2FAndreyCh1989%2Fonline-store-api?ref=badge_large)