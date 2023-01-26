План автоматизации тестирования сценария перехода к форме записи и заполнения этой формы.

Перечень автоматизируемых сценариев:

1. Навигация к форме записи

Открыта главная страница Нетологии https://netology.ru/

Пользователь не зарегистрирован в системе.

Открыть список курсов по специальности “Программирование”. Варианты выполнения:

1.1. Нажать “Каталог курсов”. ОР - открывается каталог по специальностям. Выбрать “Программирование”.

1.2. В разделе “Направления обучения” на главной странице выбрать “Программирование”.

1.3. Прокрутить страницу вниз, в футере кликнуть на “Каталог курсов”. ОР - открывается каталог по специальностям. Выбрать “Программирование”.

1.4. Прокрутить страницу вниз, в футере выбрать “Программирование”.

1.5. Прокрутить страницу вниз, в футере кликнуть на “Популярные курсы”. ОР - открывается каталог по специальностям. Выбрать “Программирование”.

ОР: открывается список курсов по специальности “Программирование”.

2. Попасть на форму записи на курс. Варианты выполнения:

2.1. В строке ввода “Чему вы хотите научиться?” ввести запрос - открывается список программ по запросу. (Валидным считается запрос “тестирование”, “тестировщик”). ОР - В результатах поиска отображаются программы “Тестировщик ПО” и “Инженер по тестированию: с нуля до middle”. Кликнуть на программу “Тестировщик ПО”. ОР - открывается страница курса “Тестировщик ПО”.

2.2. Без ввода ключевого запроса в строку поиска кликнуть на программу “Тестировщик ПО”. ОР - открывается страница курса “Тестировщик ПО”.

2.3. Кликнуть “Записаться”:

а) на открывшейся странице курса, либо

б) прокрутить страницу вниз и найти там форму записи.

ОР - открывается форма записи.

Сценарий 2. Заполнение всех полей формы валидными данными отправка формы записи

Предусловие:

Открыта форма записи на курс “Тестировщик ПО”.

Пользователь не зарегистрирован в системе.

2.1. Заполнить поле “Имя” валидными данными.

Валидными данными считается пользовательский ввод, состоящий из букв кириллицы или латиницы, из символов допускается только тире; система не принимает буквы других алфавитов (за исключением кириллицы и латиницы), цифры, спецсимволы (за исключением тире).

ОР: поле принимает значение.

2.2. Заполнить поле “Телефон” валидными данными

Валидным считается ввод цифр, круглых скобок, тире, знака + на первой позиции, длина ввода номера телефона ограничена 22 символами.

ОР: поле принимает значение.

2.3. Нажать “Записаться”

ОР:

пользователь внесен в БД системы,

пользователь может войти в свой личный кабинет,

пользователь получает уведомление об успешной записи на курс,

открывается страница оформления оплаты,

курс добавлен в личный кабинет пользователя,

на емейл пользователя отправлено письмо с уведомлением о записи на курс.

3. Заполнение поля "Имя" невалидными данными


3.1. Открыть форму записи на курс “Тестировщик ПО”.

3.2. Пользователь не зарегистрирован в системе.

3.3. Поле "Телефон" заполнить валидными данными

3.4. Заполнить поле “Имя” невалидными данными.

Невалидными данными считается пользовательский ввод, состоящий из букв других алфавитов (за исключением кириллицы и латиницы), цифры, спецсимволы (за исключением тире).

ОР: система выводит сообщение об ошибке.

 4. Заполнение поля "Телефон" невалидными данными

Предусловие:

Открыта форма записи на курс “Тестировщик ПО”.

Пользователь не зарегистрирован в системе.

Поле "Имя" заполнено валидными данными.

Заполнить поле “Телефон” невалидными данными

Невалидными данными считаются буквы любого алфавита, любые символы, за исключение тире, + и круглых скобок ().

ОР: система выводит сообщение об ошибке.

 4. Оставление поля "Имя" пустым

4.1. Открыть форму записи на курс “Тестировщик ПО”.

4.2. Пользователь не зарегистрирован в системе.

4.3.Поле "Телефон" заполнить валидными данными

4.4. Оставить поле "Имя" пустым.

4.5. ОР: система выводит сообщение, что поле обязательно для заполнения.

5. Оставление поля "Телефон" пустым

5.1. Открыта форма записи на курс “Тестировщик ПО”.

5.2.Пользователь не зарегистрирован в системе.

5.3. Поле "Имя" заполннить валидными данными.*

5.4. Оставить поле “Телефон” пустым

5.5. ОР: система выводит сообщение, что поле обязательно для заполнения.

Перечень используемых инструментов:

 Gradle
 Selenide
 Allure
 Docker/Docker
 Compose Git
 GitHub 

Перечень необходимых разрешений, данных и доступов:
Разрешение на выполнение автоматизации тестирования от владельца сайта.

Доступ к базе данных с правами чтения, внесения и удаления записей.

Доступ к API сайта.

Перечень и описание возможных рисков при автоматизации:
Эмуляция и симуляция позволяют провести тестирование быстро, без затрат на закупку оборудования и сократить количество задействованных в тестировании людей, но все же не проверяет работу в реальных условиях.

Риск увеличения ресурсозатрат на автоматизацию тестирования и увеличения сроков проведения тестирования.

Риск непредоставления (либо несвоевременного предоставления) автотестировщику информации об изменениях в системе, что ведет к дополнительным временным затратам на анализ результатов тестирования и выявление причин выявленных ошибок.

Риск недостаточного покрытия тестами. Необходимо предусмотреть максимально возможное количество негативных тестов (проверить классы эквивалентности и граничные значения - для ввода номера телефона).

Высок риск тестирования на реальной БД системы и получения нерелевантных результатов при тестировании с использованием тестовой БД.

Перечень необходимых специалистов для автоматизации:
1 специалист AQA, уровень квалификации: junior+ / middle,

Разработчик(и) для разработки тестовой БД либо сопровождения тестирования на реальной БД системы.

Интервальная оценка с учетом рисков в часах:
Развертывание тестовой среды и разработка автотестов - до 32 часов (в зависимости от количества тестируемого окружения),

Прогон автотестов - до 14-16 часов (можно настроить прогон по времени и не занимать рабочее время сотрудников),

Анализ результатов - до 8 часов,

Актуализация автотестов и их исправление (при необходимости) - до 40 часов.
