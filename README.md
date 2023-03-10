 **Планирование вероятности наступления событий по форме и полному учету этой формы**.
# **Перечень автоматизируемых реакций**:

# ***Навигация к форме записи***

* Открыть главную страницу Нетологии https://netology.ru/

* Пользователь не зарегистрирован в системе.

* Открыть список курсов по специальности «Программирование». 

**Варианты выполнения**:

 1. Нажать «Каталог курсов».

*Ожидаемый результат*: Открывается каталог по специальностям. Выбрать "Программирование".

 2. В разделе «Направление обучения» на главной странице выберите «Программирование».

 3. Прокрутить страницу вниз, в футере нажать на «Каталог курсов».

 *Ожидаемый результат*: Открывается каталог по специальностям. Выбрать "Программирование".

 4. Прокрутите страницу вниз, в футере выберите «Программирование».

  *Ожидаемый результат*: Открывается каталог по специальностям. Выбрать "Программирование".

 *Ожидаемый результат*: Открывается список курсов по специальности «Программирование».

**Попасть на форму записи на курс**. 

*Варианты выполнения*:

 1. Вы хотите начать ввод «Чему вы научились?» ввести запрос - открыть список программ по запросу.
     (Действительный запрос «тестирование», «тестировщик»).

*Ожидаемый результат*: В учреждении просмотра программы "Тестировщик ПО" и "Инженер по 
                        естированию: с нуля до середины". Кликнуть на программу «Тестировщик ПО».

*Ожидаемый результат*: Открывается страница курса "Тестировщик ПО".

 2. Без ввода запроса в поисковую строку нажмите на программу «Тестировщик ПО». 

*Ожидаемый результат*: Открывается страница курса "Тестировщик ПО".

 3. Кликнуть «Записаться»:

  а) на открывшейся курсы, либо

  б) прокрутить страницу вниз и найти там форму записи.

*Ожидаемый результат*: Открывается форма записи.

**Заполнение всех полей форм действительными данными отправки формы записи**

 1. Открыть форму записи на курс «Тестировщик ПО».

 2. Пользователь не зарегистрирован в системе.

 3. Заполните поле «Имя» действительными данными.

      Валидными данными вычисляется действующий ввод, вычисляется из буквы кириллицы или латиницы, из числа значений только тире; система не принимает буквы       букв других букв (за исключением кириллицы и латиницы), цифры, спецсимволы (за исключением тире).

*Ожидаемый результат*: Поле принимает значения.

 4. Заполнить поле «Телефон» действительными данным.

     Действительный ввод цифр, круглых скобок, шины, знака + на первую позицию, длина ввода номера телефона ограничена 22 символами.

*Ожидаемый результат*: Поле принимает значение.

 5. Нажать “Записаться”

*Ожидаемый результат*:  Пользователь внесен в БД системы:

* Пользователь может войти в свой личный кабинет,

* Пользователь получает об успешной записи на курс,

* Открывается страница оформления оплаты,

* Курс добавлен в личный кабинет пользователя,

* На почту электронной почты пользователя отправлено письмо с записью на курс.

**Заполнены поля "Имя" недействительными данными**

 1. Открыть форму записи на курс «Тестировщик ПО».

 2. Пользователь не зарегистрирован в системе.

 3. Поле "Телефон" заполнено достоверными данными

 4. Заполнить поле «Имя» недействительными данными.

     Недействительными данными считаются вводимые данные, вычисленные из букв других букв (за исключением кириллицы и латиницы), цифр, спецсимволов (за            исключением тире).

*Ожидаемый результат*: Система выводит сообщение об оплате.

**Заполнение поля "Телефон" недействительными данными**

 1. Открыть форму записи на курс «Тестировщик ПО».

 2. Пользователь не зарегистрирован в системе.

 3. Поле "Имя" заполняет достоверными данными.

 4.Заполнить поле «Телефон» недействительными данными

    Недопустимые данные вычисления букв любого алфавита, любых символов, за исключением шины, + и круглых скобок ().

*Ожидаемый результат*: Система выводит сообщение о деньгах.

**Оставление поля "Имя" пустым**

 1. Открыть форму записи на курс «Тестировщик ПО».

 2. Пользователь не зарегистрирован в системе.

 3. Поле "Телефон" заполнено достоверными данными

 4. Оставить поле "Имя" пустым.

*Ожидаемый результат*: Система выводит сообщение, что поле обязательно для заполнения.

**Оставление поля "Телефон" пустым**

 1. Открыть форму записи на курс «Тестировщик ПО».

 2.Пользователь не зарегистрирован в системе.

 3. Поле "Имя" заполните достоверными данными.*

 4. Оставить поле «Телефон» пустым

*Ожидаемый результат*: Система выводит сообщение, что поле обязательно для заполнения.

**Перечень инструментов**:

* JAVA - удобный язык для написания тестов с множеством возможностей;
* Gradle - для быстроты сборки и простоты в настройки компонентов;
* Selenide - для простотыя настройки и большого выбора локаторов;
* Allure - для детальных и понятных отчетов автотестов;
* Docker/Docker Compose - для разворачивания окружения например, для тестировани на другой ОС;
* Git - для сохранения всех версий тестов;
* GitHub - для удобства удаленного хранения кода;
* JUnit - для упрощения процесса модульного тестирования.

**Перечень разрешений, данных и доступа**: 

* Разрешение на обеспечение безопасности от владельца сайта.

* Доступ к базе данных с правами чтения, внесения и удаления записей.

* Доступ к API сайта.

**Перечень и описание возможных рисков при попадании**: 

* Эмуляция и симуляция позволяют проводить тестирование быстро, без затрат на закупку оборудования и     сокращение количества задействованных в тестировании   людей, но все же не связано с работой в           предполагаемых условиях.

* Риск увеличить ресурсозатрат на автоматизацию тестирования и длительность проведения тестирования.

* Риск непредоставления (или несвоевременного предоставления) автотестировщику информации об изменениях   в системе, что связано с выявленными временными       затратами на анализ результатов и выявление            выявленных причин выявленных ошибок.

* Риск недостаточного покрытия тестами. Необходимо предусмотреть максимальное количество негативных      тестов (проверить классы эквивалентности и граничные   значения - для ввода номера телефона).

* Высок риск тестирования по реальной системе БД и получение нерелевантных результатов при тестировании   с использованием тестовой БД.

**Перечень необходимых специалистов для автоматизации**: 

* 1 специалист AQA, уровень квалификации: младший+/средний,

* Разработчик(и) для разработки тестов БД либо сопровождения испытаний на реальных БД-системах.

**Интервальная оценка с учетом рисков в часах**: 

* Развертывание тестовой среды и разработка автотестов - до 32 часов (в зависимости от количества        тестируемого окружения),

* Прогон автотестов - до 14-16 часов (можно настроить прогон по времени и не заниматься постоянным       временем сотрудников),

* Анализ результатов - до 8 часов,

* Актуализация автотестов и их исправление (при необходимости) - до 40 часов.
