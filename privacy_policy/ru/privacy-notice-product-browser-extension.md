# Уведомление о конфиденциальности: браузерное расширение AdGuard
*24 мая 2018*
> **Основная идея:** AdGuard не передаёт и не продаёт третьим лицам ваши личные данные. Главные принципы, которым мы привержены — бороться за приватность пользователей и быть максимально прозрачными.

Настоящая Политика конфиденциальности содержит информацию о данных, получаемых от Пользователя в процессе его работы с приложениями AdGuard, и их обработке. Мы собираем только ту личную информацию, которая необходима для полной функциональности продуктов AdGuard. Мы не используем данные в целях отслеживания действий Пользователя и не передаем информацию третьим лицам. Мы принимаем все необходимые технические и административные меры для защиты получаемой  о Пользователях информации.

Пожалуйста, ознакомьтесь с нашей политикой конфиденциальности, чтобы узнать, какая информация пересылается при использовании браузерного расширения AdGuard, как мы ее храним и обрабатываем в дальнейшем.

## Данные, пересылаемые при использовании браузерного расширения AdGuard

### При проверке обновлений рекламных фильтров

Расширение AdGuard обращается к нашим серверам, чтобы проверить наличие обновлений рекламных фильтров. При этом передается следующая информация:

- Тип браузера;
- Язык браузера;
- ID расширения;
- Версия расширения;
- Тип сборки расширения.

Проверка обновлений фильтров осуществляется раз в сутки. Мы агрегируем полученные данные с целью выявления числа активных пользователей.

### При сборе статистики использования правил рекламных фильтров 

Опция “Отправлять статистику использования рекламных фильтров” отключена по умолчанию. Ничего не будет пересылаться, если только Пользователь вручную не включит эту опцию, чтобы помочь нам улучшить рекламные фильтры. [Эта статья в Базе знаний](https://kb.adguard.com/general/filter-rules-statistics) рассказывает, как именно включение этой опции помогает нам.

Если Пользователь включил опцию “Отправлять статистику использования рекламных фильтров”, периодически пересылается следующая информация:

- Версия браузерного расширения;
- Тип браузера;
- Список идентификаторов включенных рекламных фильтров;
- Список, состоящий из следующих элементов:
    - Доменное имя сайта,
    - Количество просмотров страниц сайта за последнее время,
    - Список правил фильтрации и ID фильтров, сработавших на этом сайте,
    - Для URL-правил отправляется доменное имя заблокированного запроса. Список формируется на основе статистики посещения сайтов с момента последней отправки статистики.
    
С помощью сбора статистики используемых фильтров мы можем обнаружить устаревшие правила фильтров и удалить их. Таким образом, предоставляя данную информацию, вы помогаете всем пользователям AdGuard.

### При отправке жалобы на сайт
Пользователь может отправить отчёт о проблеме на сайте прямо из расширения. Расширение автоматически откроет страницу reports.adguard.com и передаст некоторую информацию о своих настройках. Пользователь получит возможность изменить или удалить эту информацию.

Пока Пользователь не согласится отправить эту информацию, нажав кнопку “Готово”, никакие данные не будут сохранены или отправлены куда-либо. В случае, если Пользователь нажимает эту кнопку, отчёт будет опубликован на [GitHub](https://github.com/adguardteam/adguardfilters/issues) (анонимно).

### При проверке, является ли посещаемый сайт фишинговым или вредоносным

Если включена опция «Защита от фишинговых и вредоносных сайтов», расширение AdGuard проверяет каждый веб-сайт перед тем, как Пользователь его посетит. При этом используется механизм Lookup API, информация передается серверу в форме префиксов хэшей. Это не позволяет нам определить, какой сайт посещает Пользователь.

### Антифишинг сообщество
Если Пользователь включил опцию «Принять участие в развитии антифишинга», программа будет время от времени отправлять следующую анонимную информацию:
- URL-адреса посещаемых веб-сайтов, которые AdGuard определяет как потенциально ненадежные, вместе с информацией о характере выявленных угроз;
- Язык браузера;
- Дополнительную статистическую информацию об угрозах, обнаруженных программным обеспечением AdGuard.

Указанная выше информация, получаемая AdGuard, не включает в себя личные данные Пользователя. Информация отправляется анонимно и обрабатывается с такой же информацией от других Пользователей расширения исключительно в статистических целях.

