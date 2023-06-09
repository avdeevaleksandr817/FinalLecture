# FinalLecture

# Внедрение автоматизации
## Предусловия, как перейти в форму записи на курс
<details>
<summary>Вариант первый</summary>

На странице https://netology.ru/ выбрать "Каталог курсов"

![25-03-2023 17-23-58](https://user-images.githubusercontent.com/97477540/227719906-c7dad535-e07f-4cbe-ba17-0bd4a1abf9bd.jpg)

в каталоге курсов выбрать  "Программирование - Тестировщик ПО"

![25-03-2023 17-26-58](https://user-images.githubusercontent.com/97477540/227720057-70413eb3-a9ed-4203-8384-98b24db9a95c.jpg)

откроется страница тестировщик, нажать кнопку "записаться", вас переместит на форму записи

![25-03-2023 17-31-01](https://user-images.githubusercontent.com/97477540/227720320-1edcb0e8-0eee-4b40-bff9-76f788091fa8.jpg)
![25-03-2023 17-34-12](https://user-images.githubusercontent.com/97477540/227720396-fe902205-f417-4274-9c56-3af6906f4708.jpg)
</details>
<details>
<summary>Вариант второй</summary>

На странице https://netology.ru/ выбрать "Направление обучения - Программирование"

![25-03-2023 19-21-40](https://user-images.githubusercontent.com/97477540/227726399-58672ac3-5bad-497c-a1da-9b739721421a.jpg)

в каталоге курсов выбрать  "Программирование - Тестировщик ПО"

![25-03-2023 17-26-58](https://user-images.githubusercontent.com/97477540/227720057-70413eb3-a9ed-4203-8384-98b24db9a95c.jpg)

откроется страница тестировщик, нажать кнопку "записаться", вас переместит на форму записи

![25-03-2023 17-31-01](https://user-images.githubusercontent.com/97477540/227720320-1edcb0e8-0eee-4b40-bff9-76f788091fa8.jpg)
![25-03-2023 17-34-12](https://user-images.githubusercontent.com/97477540/227720396-fe902205-f417-4274-9c56-3af6906f4708.jpg)
</details>
<details>
<summary>Вариант третий</summary>
 
На странице https://netology.ru/ , перейти в самый низ страницы, выбрать "Обучение - Каталог курсов"

![25-03-2023 19-34-27](https://user-images.githubusercontent.com/97477540/227727042-268a7641-be94-41f2-88d6-fc54f97dc18c.jpg)

На странице "Все курсы" выбрать "Тестировщик ПО"

![25-03-2023 19-35-52](https://user-images.githubusercontent.com/97477540/227727184-74355c5a-357c-4382-b6e7-32e44282cde6.jpg)

откроется страница "Тестировщик", нажать кнопку "записаться", вас переместит на форму записи

![25-03-2023 17-31-01](https://user-images.githubusercontent.com/97477540/227720320-1edcb0e8-0eee-4b40-bff9-76f788091fa8.jpg)
![25-03-2023 17-34-12](https://user-images.githubusercontent.com/97477540/227720396-fe902205-f417-4274-9c56-3af6906f4708.jpg)
</details>
<details>
<summary>Вариант четвертый</summary>

На странице https://netology.ru/ кликнуть по рекламному баннеру "Скидки до 60 процентов" кликнуть "Выбрать курс"

![25-03-2023 19-53-58](https://user-images.githubusercontent.com/97477540/227728024-6bfc0a7f-5ef3-4fbc-ae2f-bd619384d7c2.jpg)

На странице "Все курсы" выбрать "Тестировщик ПО"

![25-03-2023 19-35-52](https://user-images.githubusercontent.com/97477540/227727184-74355c5a-357c-4382-b6e7-32e44282cde6.jpg)

откроется страница "Тестировщик", нажать кнопку "записаться", вас переместит на форму записи

![25-03-2023 17-31-01](https://user-images.githubusercontent.com/97477540/227720320-1edcb0e8-0eee-4b40-bff9-76f788091fa8.jpg)
![25-03-2023 17-34-12](https://user-images.githubusercontent.com/97477540/227720396-fe902205-f417-4274-9c56-3af6906f4708.jpg)

</details>

## 1 Перечень автоматизируемых сценариев.

* Валидные значения:
Успешная отправка валидно заполненной формы записи на курс "Тестировщик ПО", включая проверку ввода действующего промокода (с изменением стоимости курса)
и перехода на страницы с условиями политики и пользовательского соглашения

1. "Имя": латиница, кириллица, пробел и дефис/тире, заполненный минимум двумя буквами
1. "Телефон": цифры, круглые скобки, пробел и дефис/тире в формате +9 (999) 999-99-99, от 9 до 14 символов включительно
1. "Промокод": латиница, кириллица, цифры и спецсимволы, кроме пробела
1. "Электронная почта": должно содержать локальную часть адреса, "собачку" ( @ ) и доменную часть имени с точкой ( . ).

* Сценарии тестирования UI:

1. У поля "Имя" появление сообщение "Должно состоять из букв" при заполнение его спецсимволами в форме записи на курс
1. У поля "Имя" появление сообщение "Должно состоять из букв" при заполнение его цифрами в форме записи на курс
1. У поля "Имя" появление сообщение "Должно быть не короче 2 символов" при заполнение его одной буквой в форме записи на курс 
1. У поля "Имя" появление сообщение "Обязательное поле" при оставление поля пустым в форме записи на курс 
1. У поля "Телефон" появление сообщение "Номер в формате +9 (999) 999-99-99" при заполнение поля 8 цифрами в форме записи на курс 
1. У поля "Телефон" появление сообщение "Номер в формате +9 (999) 999-99-99" при заполнение поля 15 цифрами в форме записи на курс 
1. У поля "Телефон" появление сообщение "Обязательное поле" при оставление поля пустым в форме записи на курс 
1. У поля "Электронная почта" появление сообщения "Неверный email" при заполнении не валидными данными в форме записи на курс 
1. У поля "Электронная почта" появление сообщения "Обязательное поле" при оставление поля пустым в форме записи на курс 
1. У поля "Промокод" появление сообщение "Устаревший промокод" при вводе устаревшего валидного промокода в форме записи на курс 
1. У поля "Промокод" появление сообщение "Промокод не найден" при вводе не валидного промокода в форме записи на курс 
1. Запись на курс возможна при заполнении всех полей валидными данными, если любое из полей заполнено не правильно под полем появление сообщение "Обязательное поле"
1. Форма заполнена валидными данными, нажимаем "Записаться" появляется сообщение "Ваша заявка успешно отправлена. Подробная информация выслана на email".
В электронной почте видим письмо от Нетологии с успешной записью на курс.
1. Получить консультацию возможно при заполнении всех полей валидными данными, если любое из полей заполнено не правильно под полем появление сообщение "Обязательное поле"
1. Форма заполнена валидными данными, нажимаем "Получить консультацию" появляется сообщение "Ваша заявка успешно отправлена. Скоро с Вами свяжется наш менеджер".
1. Если у пользователя уже есть аккаунт на сайте, нажимаем кнопку "Войти", после успешного входа в форма записи на курс заполняется данными действующего аккаунта
1. Сценарии для зарегистрированоого и незарегистрированного пользователя одинаковые

* Сценарии тестирования API:

1. Проверка статуса 200 и совпадения валидных* данных отправленных через UI формы записи на курс "Тестировщик ПО" с данными в body POST-запроса к серверу и новыми данными из БД.
1. Проверка статуса 500 и отсутствие новых записей в БД при отправке пустого body в POST-запросе отправки формы записи на курс "Тестировщик ПО"
1. Проверка статуса 500 и отсутствие новых записей в БД при отправке пустого значения у атрибута phone в body в POST-запросе отправки формы записи на курс "Тестировщик ПО"
1. Проверка статуса 500 и отсутствие новых записей в БД при отправке пустого значения у атрибута name в body в POST-запросе отправки формы записи на курс "Тестировщик ПО"

## 2 Перечень используемых инструментов с обоснованием выбора.

1.	IDE: IntelliJ IDEA удобная популярная среда Java-разработки с богатым набором инструментов и плагинов, в т.ч. для подготовки автотестов;
1.	Java JDK 11 или выше – мощный объектно-ориентированный язык программирования с обширным набором библиотек, общепринятое базовое средство автоматизации тестирования;
1.	Система сборки: Gradle (легче настраивать зависимости)
1.	Тестовая среда: JUnit Jupiter, инструмент тестирования, наиболее популярная библиотека для проведения модульного тестирования в Java;
1.	Фреймворк для UI тестирования: Selenide, очень удобен при тестировании веб-интерфейса;
1.	Фреймворк для API тестирования: REST Assured для тестирования отправки email вместе с JSON Schema Validator (для отправки необходимых запросов и валидации JSON схемы)
1.	Appveyour для использования CI
1.	Система репортинга: Allure (более сложные системы репортинга будут излишни)
1.	Фреймворки для управления данными: 
*	Java Faker (для генерации данных
*	Gson (для генерации body запросов при API тестирования)
*	Git – система контроля версий разрабатываемого ПО, взаимодействует с Github;
*	Github – облачная среда для хранения версий проекта с тестами и для ведения разработки ПО;
*	Docker и Docker Compose для запуска контейнера с базой данных
*	Database Navigator, Клиент для работы с БД;

## 3 Перечень необходимых разрешений, данных и доступов.

1.	Необходимо письменное разрешение на проведение тестирования администрации веб-сайта Нетологии
1.	Доступ на чтения БД (действующей или тестовой)
1.	Доступ к существующим тестовым данным (если они есть)
1.	Доступы к API сайта
1.	Логин и пароль зарегистрированного тестового пользователя
1.	Необходимо решить вопрос с корректным удалением тестовых данных.
1.	Если невозможно использовать действующую систему нужна копия SUT, готовая к интеграции с пустой базой данных 
1.	Docker-контейнер серверной СУБД с базой данных, пустой или заполненной тестовыми данными, если запрещено использование основного сервера.

## 4 Перечень и описание возможных рисков при автоматизации.

1.	Недоступность сайта netology.ru;
1.	Недоступность сервера с СУБД 
1.	"Ложные" запросы к менеджерам на обратный звонок
1.	Дополнительная нагрузка на сервер
1.	Появление "мусорных" записей в БД
1.	Уничтожение ценных данных в рабочей БД при некорректной реализации удаления данных.
1.	Зависимость авто-тестов от текущей реализации веб-элементов, даже не значительное их изменение может привести к падению авто-тестов;
1.	Авто-тесты не проверяют графическую составляющую, а именно едет ли верстка при тех или иных действиях, комфортна ли выбранная цветовая схема оформления и тд.
1.	Изменение дизайна и верстки страниц могут привести к изменению селекторов, используемых в тестах
1.	Добавление новых блоков на главную страницу сайта: появляются новые пользовательские сценарии, не охваченные тестами
1.	Удаление / добавление полей в форму: тесты падают / уменьшается охват тестирования отправки формы
1.	Трудности с поиском локаторов тестируемых элементов на страница
1.	Недоступность страницы профессии с формой на сайте netology.ru;
1.	Изменение дизайна сайта и/или web-элементов, задействованных в автотестах;

## 5 Перечень необходимых специалистов для автоматизации.

1.	Данный проект не сложный, при доступе к реальной базе данных, поэтому будет достаточно junior QA engineer по автоматизации, который знаком с основами необходимого инструментария, основами UI и API тестирования и базовыми навыками написания автотестов с использованием паттерна Page Object.
1.	При работе с копией SUT, необходим системный администратор или DevOps-инженер который его подготовит, при необходимости предоставит данные для развертывания SUT и интеграции с базой данных.

## 6 Интервальная оценка с учётом рисков в часах.

1.	После согласования всех необходимых соглашений и доступов, у junior специалиста написание тестов займет  24 часа.
1.	Исправление и поддержка тестов - 10 часов в месяц.
