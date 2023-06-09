# Гузь Даниил - “Perfect body - стань лучшей версией себя”
# Пользовательские сценарии
### Группа: 10 - М
### Электронная почта: danilguz@yandex.ru
### VK: https://vk.com/eeexdeee

### [ Сценарий 1 - Регистрация пользователя ]

1. Пользователь вводит логин, с которым он будет заходить в систему
2. Пользователь вводит пароль, с которым он будет заходить в систему
3. Пользователь вводит адрес электронной почты или номер телефона, который будет использоваться в системе
4. Если выбранный логин уже существует в системе, то пользователю сообщается об этом и предлагается придумать новый логин
5. Если второй логин уже занят, система дает рекомендации по придумыванию уникального логина
6. Если пароль содержит менее 8 символов, система сообщает, что пароль должен быть от 8 до 30 символов и пользователь должен придумать новый пароль
7. Если введённый адрес электронной почты не соответствует формату, то система выводит сообщение об ошибке и просит ввести адрес еще раз
8. Если все введенные данные соответствуют требованиям регистрации, то система отправляет на почту письмо для подтверждения почты
После подтверждения e-mail'а система приветствует пользователя и переходит в диалог выбора режима работы и тарифного плана.
Запускается Сценарий 2 - Выбор режима работы и тарифного плана.

### [ Сценарий 2 - Выбор режима работы / тарифного плана ]

1. Пользователь вводит свои физические данные (рост, вес, возраст; в случае прохождения специального анализа на количество жира или мышц в теле будет специальное поле для ввода)
2. Пользователю предлагается выбрать цель использования приложения:
   1. Потеря веса
   2. Набор мышечной массы
   3. Поддержка своего тела в форме
Помимо этого, пользователь выбирает цель тренировок (набор n кг мышечной массы или потеря m кг жира)
3. Пользователя ознакамливают с тарифами:
   1. Стандарт
   2. Продвинутый
   3. Премиум
Тарифы отличаются доступными функциями (пользователю доступно сравнение тарифных планов) и ценой ежемесячной / годовой подписки.
4. После выбора тарифа осуществляется переход к сценарию 3 - Создание и изменение собственного профиля

### [ Сценарий 3 - Создание и изменение собственного профиля ]

1. У пользователя спрашивается, хочет ли он персонализировать свой профиль: добавить фотографию / создать аватара. В случае согласия пользователь выбирает “Да, хочу”, в случае отказа - “Нет, спасибо” и запускается сценарий 4 - выбор активности.
2. В случае согласия пользователь нажимает кнопку “Да, хочу” и переходит в режим создания и изменения персонажа.
3. Пользователь выбирает картинку профиля: собственное фото или аватар
4. В случае выбора своего фото пользователь делает фотографию или выбирает фото из галереи
5. В случае выбора аватара пользователь переходит в редактор персонажа, где он выбирает его внешность (цвет кожи, прическа, глаза, нос и пр.)
6. После завершения создания или изменения профиля пользователь оказывается на вкладке “Профиль”, где будет доступен график изменения его веса в течение месяца и график потребленных и сожженных им калорий, а также процентный показатель его прогресса к цели

### [ Сценарий 4 - Выбор активности ]

В зависимости от выбранного тарифа пользователю доступны 2 режима работы приложения:
   1. Тренировка. При выборе запускается сценарий 5 - Тренировка 
   2. Питание. При выборе запускается сценарий 6 - Счет калорий

### [ Сценарий 5 - Тренировка ]

1. Пользователь выбирает удобные для тренировки дни (приложение будет уведомлять пользователя о том, что у него в этот день тренировка)
2. Пользователь выбирает группы мышц, на которые он хочет получить нагрузку
3. После выбора группы мышц приложение составляет пользователю подходящую тренировку и открывается предпросмотр тренировки (названия упражнений, количество/ время подходов, время отдыха между подходами и количество сожженных калорий за тренировку). Пользователю предлагается начать тренировку и при нажатии кнопки “Начать” запускается процесс тренировки
4. В процессе тренировки пользователь показывает видео с правильной техникой выполнения упражнений и интерактивным таймером / счетчиком подходов
5. В конце тренировки приложение поздравляет пользователя с окончанием тренировки, показывает итоги тренировки (сожженные калории) и график следующих тренировок.

### [ Сценарий 6 - Счет калорий ]

1. С учетом введенных данных приложение определяет необходимое количество потребляемых и сжигаемых калорий.Приложение дает возможность пользователю посчитать количество калорий, которое он употребил во время приема пищи. Для этого пользователь должен открыть раздел “Прием пищи”.
2. В “Приеме пищи” пользователь ищет продукты в каталоге продуктов, которые он употребил / употребляет во время еды. Пользователю отображается калорийность продукта(-ов) и количество БЖУ в нем (них), причем он также получает информацию о том, сколько % суточной нормы калорий и БЖУ пользователь употребил.
3. В конце каждого дня приложение будет предоставлять отчет о потребленных и сожженных калориях и анализ их количества по сравнению с прошлым днём или указанным целевым количеством калорий.

### [ Сценарий 7 - Ежемесячный отчет о прогрессе пользователя ]

1. В конце каждой недели пользователю предоставляется возможность обновить свои данные для отслеживания прогресса
2. Приложение автоматически запрашивает у пользователя его данные во всплывающем окне, если же данные не изменились, пользователь выбирает соответствующую кнопку “мои данные не изменились”.
3. В конце каждого месяца приложение оповещает пользователя о подготовленных итогах месяца. При просмотре пользователь видит отчет о всех тренировках в календаре (при невыполненных запланированных тренировках они будут отмечаться красным цветом, при выполнении - зеленым), а также график изменения его веса (по неделям) и график употребленных калорий.
После предоставления пользователю итогов месяца приложение предлагает пользователю изменить или оставить цель использования приложения и тарифа, то есть выполняется сценарий 2 - Выбор режима работы / тарифного плана (но все пункты, кроме п. 1 и 4)
