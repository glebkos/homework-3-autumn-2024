## Бюджет
1. Бюджет. Транзакции. Эмптистейт. При открытии раздела с пустым списком транзакций показывается сообщение с заголовком «Транзакций пока нет», текстом «Пополните счёт, чтобы запустить рекламу», кнопкой «Пополнить счет» и показыается иконка VKUI `wallet_outline_56`
<img src=https://github.com/user-attachments/assets/60b0a599-ea97-4776-a595-fff3b072f9f1 width=300px>

2. Бюджет. Транзакции. Эмптистейт. При нажатии на кнопку «Пополнить счет» открывается модальное окно. Необходимо проверить, что оно соответствует макету 
<img src="https://github.com/user-attachments/assets/7d73637a-8c55-4223-b341-25da8181fd57" width=300px>

3. Бюджет. Транзакции. Эмптистейт. Модальное окно пополнения счета. Инпут с лейблом «Сумма, поступающая на ваш счёт» должен быть оганичен на ввод символов.
4. Бюджет. Транзакции. Эмптистейт. Модальное окно пополнения счета. Инпут с лейблом «Cумма к оплате» должен выдавать ошибку «Минимальная сумма 600,00₽» при вводе числа ниже 600₽, также, если в это поле ввели число ниже 600₽ или вообще ничего не ввели, то при нажатии на кнопку «Пополнить счет» должно появиться сообщение с ошибкой
5. Бюджет. Транзакции. Эмптистейт. Модальное окно пополнения счета. Проверяем подсказки рядом с лейблами, при наведении на них должен появляться тултип, текст внутри должен соответсвовать макету.
6. Бюджет. Транзакции. Эмптистейт. Модальное окно пополнения счета. Подсказки для лейблов. Проверяем, что ссылки внутри тултипа ведут на верные страницы
7. Бюджет. Транзакции. Эмптистейт. Модальное окно пополнения счета. Если ввести верную сумму, то после нажатия на «Пополнить счет» переносит на модалку с оплатой с помощью VK pay
8. Бюджет. Транзакции. Эмптистейт. Модальное окно оплаты. Проверяем, что компонент отображается корректно и проверяем, что разные спопсобы оплаты работают и можно испльзовать запомненые карты. Проверяем, что после завершения оплаты списывается правильная сумма
9. Бюджет. Транзакции. Эмптистейт. Модальное окно оплаты. Проверяем, что после оплаты транзакция отображается в списке. Проверяем, что данные совпадают
10. Бюджет. Транзакции. Проверяем, что кнопка «Пополнить счет» появляется, если транизации есть в списке.
11. Бюджет. Транзакции. Проверяем модальное окно пополнения счета
13. Бюджет. Бонусная программа. Эмптистейт. Проверяем, что в пустом состоянии экраны отображаются в соответсвие макетам
14. Бюджет. Бонусная программа. Эмптистейт. Проверяем, что если активировать промокод, то эмптистейт акций останется неизменным.
15. Бюджет. Бонусная программа. Эмптистейт. Проверяем, что если активировать акцию, то эмптистейт промокодов останется
16. Бюджет. Бонусная программа. Нажимаем на кнопку «Активировать промокод» и проверяем, что открывается модальное окно
17. Бюджет. Бонусная программа. Модальное окно активации промокода. Проверяем, что активанция кода по кнопке «Активировать» работает. Если ввести промокод, то он появится в списке и модалка закроется. Если в инпут ввести акцию, то она появится в соответсвующем списке.
18. Бюджет. Бонусная программа. Модальное окно активации промокода. Проверяем, что ошибки обрабатываются в форме. Если ввесит неверный код, то появится сообщение об ошибке и инпут покрасится в красный. Проверяем, что если оставить поле пустым, то повится сообщение об этом

## Центр коммерции
1. Центр коммерции. Эмптистейт. Проверяем, что если нет каталогов то показывается эмпитсейт, согласно макетам
<img src="https://github.com/user-attachments/assets/51e51257-63fe-4c88-8f8b-75d4581cc2e2" width=500px>

2. Центр коммерции. Эмптистейт. Что при нажатии на пройти обучение появляется модалка с тремя опциями.
3. Центр коммерции. Эмптистейт. Проверяем создание каталога с подчказками, при нажатии на нее откроется модалка создания каталога и будут появляться подсказки к его заполнению. Нужно проверить их содержание.
4. Центр коммерции. Эмптистейт. Проверяем просмотр видеоурока от экспертов, откроет модалку с видео в плеере VK видео.
5. Центр коммерции. Эмптистейт. Проверяем просмотр курса на обучающей платформе откроет ссылку с курсом. 
6. Центр коммерции. Эмптистейт. Создание каталога. Проверяем работу модалки, по клику вне модалки, на крестик или на кнопку «Отмена» модалка должна закрыться.
7. Центр коммерции. Создание каталога. Проверяем, что если не заполнить название каталога, то появится ошибка «Обязательное поле»
8. Центр коммерции. Создание каталога. Фид и сообщество. Проверяем работу формы, если все поля заполнены правильно, то создается католог с правльными параметрами и он отображается в списке с верными данными 
9. Центр коммерции. Создание каталога. Проверяем, что галочка удалить UTM-метки удаляет их из ссылки
10. Центр коммерции. Создание каталога. Проверяем, что если ссылка введена неверно, то появляется соответсвующая ошибка «Необходимо указать протокол http(s)» или «Не удалось выполнить запрос по HTTP»
11. Центр коммерции. Список каталогов. Проверяем, что при нажатии на три точки появляется меню, где можно перейти в настройки каталога и удалить аккаунт.
12. Центр коммерции. Настройки каталога. Проверяем, что из порталки можно выйти по крестику, нажатию вне или по кнопке отмены
13. Центр коммерции. Настройки каталога. Проверяем, что данные сохраняются по нажатию на кнопку «Сохранить»
14. Центр коммерции. Настройки каталога. Проверяем удаление диалога из этой модалки. Перед удаление появляется модальное окно, проверяем, что если отменить действие, то каталог останется, если нажать «Удалить» он пропадет из списка 
15. Центр коммерции. Настройки каталога. Основные. Проверяем, что в разделе отображаются верные данные и их можно поменять
16. Центр коммерции. Настройки каталога. Основные. Проверяем, что отображаются ошибки под полем Название, если то не введено
17. Центр коммерции. Настройки каталога. Доступы. Эмптистейт. Проверяем, что выглядит как на макетах, ссылка «Подробнее» кликабельна и ведет на станицу
18. Центр коммерции. Настройки каталога. Доступы. Проверяем, что добавление в каталог работает и добавляет пользователя с правами, которые выбраны
19. Центр коммерции. Настройки каталога. Доступы. Проверяем ошибки если не введен ID или введен неверно
20. Центр коммерции. Настройки каталога. Доступы. Проверяем отображение списка и управение им
21. Центр коммерции. Каталог. Проверяем элемент сверху, в нем отображается текущий каталог и раскрываемый список отображает другие каталоги. Количество товаров соответсвует катаогу и кнопка настройек открывает модалку с ними
22. Центр коммерции. Каталог. Список товаров. Все товары отображаются и они могут быть отсортированы по столбцу
23. Центр коммерции. Каталог. Список товаров. Проверяем поиск товаров в списке, показываются найденые товары
24. Центр коммерции. Каталог. Список товаров. Проверяем кнопку настроек, она должна открыть модальное окно «Настройка таблицы».
25. Центр коммерции. Каталог. Список товаров. Проверяем, что при изменении состояния чекбоксов, параметр пропадает/появляется в списке слева.
26. Центр коммерции. Каталог. Список товаров. Проверяем, что порядок определяет столбцы в таблице и проверяем поиск параметров.
27. Центр коммерции. Каталог. Список товаров. Проверяем кнопки сбросить приводят данные к исходному состоянию.
28. Центр коммерции. Каталог. Список товаров. Проверяем, что после нажатия «Принять» настройки применяются к таблице.
29. Центр коммерции. Каталог. Список товаров. Проверяем нажатие вне модалки, на крестик или на отмену закрывают модльное окно и не сохраняет настройки
30. Центр коммерции. Каталог. Список товаров. Нажатие на товар открывает модалку с информацие о ней проверяем, что данные соответствуют данным товара и проверяем, что модалка закрывается на крестик и нажатие извне
31. Центр коммерции. Каталог. Список товаров. Нажате на «Рекламировать» открывает страницу с формой из трех шагов «Настройка кампании», «Группы объявлений» и «Объявления».
Центр коммерции. Каталог. Список товаров. Рекламировать. Проверяем, что на каждом этапе происходит валидация данных, если данные неверные, то появляется сообщение об этом. 
Центр коммерции. Каталог. Список товаров. Рекламировать. Проверяем, что после завершения запустится реклама с параметрами указанными в форме
32. Центр коммерции. Каталог. Группы. Создание группы по фильтрам. Проверяем добавление фильтров, переключение фильтров работает и список товаров меняется в зависимости от них.
33. Центр коммерции. Каталог. Группы. Создание группы по фильтрам. Работает переключение соответсвует «всем условиям»/«хотя бы одному», нажатие по товару открывает информацию о нем.
34. Центр коммерции. Каталог. Группы. Создание группы по фильтрам. После нажатия на сохранить, группа появляется в списке
35. Центр коммерции. Каталог. Группы. Проверяем создание группы по выбору товаров, товары выбираются, если не выбрать ни одного, то сохранить не получится.
36. Центр коммерции. Каталог. Группы. Проверяем, что после выбора проверяем, что выбранные товары отображаются во вкладке «Выбранные», нажатие по товару открывает его.
37. Центр коммерции. Каталог. Группы. Проверяем, что при нажатии на сохранение группа создается и отображается в списке 
38. Центр коммерции. Каталог. Группы. Проверяем, что при нажатии на группу открывается список товаров в ней.
39. Центр коммерции. Каталог. Группы. Проверяем, что нажатие на товар открывает информацию о нем.
40. Центр коммерции. Каталог. Группы. Проверяем, что кнопка редактировать открывает настройки с фильтрами
41. Центр коммерции. Каталог. Группы. Выбираем группу и проверяем, что появляется меню при нажатии на три точки. В меню три действия: поделиться группой, создать похожую группу и удалить группу
42. Центр коммерции. Каталог. Группы. Поделиться группой. Проверяем, что при нажатии появляется модалка.
43. Центр коммерции. Каталог. Группы. Поделиться группой. Проверяем поле ID вводим неверные данные и проверяем ошибки.
44. Центр коммерции. Каталог. Группы. Поделиться группой. Проверяем, что при вводе верного ID пользователя проверяем, что при нажатии ему добавляется группа
45. Центр коммерции. Каталог. Группы. Создать похожую группу. Проверяем, что при нажатии появляется модальное окно с созданием новой группу в которой уже применены фильтры группы из которой мы нажали на опцию.
46. Центр коммерции. Каталог. Группы. Создать похожую группу. Проверяем, что фильтры верные
47. Центр коммерции. Каталог. Группы. Удалить группу. Проверяем, что при нажатии появляется модалка с подтверждением действия.
48. Центр коммерции. Каталог. Группы. Удалить группу. Проверяем что при нажатии Удалить, группа удаляется из списка.
49. Центр коммерции. Каталог. Группы. Удалить группу. Также проверяем кнопку отмены, она должна закрыть модалку без удаления
50. Центр коммерции. Каталог. Группы. Выбираем группу и нажимаем «Рекламировать» после нажатия должно появиться многоступенчатая форма для выкладывания группы в рекламу.
51. Центр коммерции. Каталог. Группы. Проверяем поля формы на обработку ошибок и проверяем, что форма обрабатывает запрос при верных данных
52. Центр коммерции. Каталог. Диагностика. Эмптистейт. Если лист пустой, проверяем эмтистейт на текстовки
53. Центр коммерции. Каталог. Диагностика. Проверяем, что ошибки или предупреждения прилетаю и отображаются в листе
54. Центр коммерции. Каталог. События. Для товаров сообщества ВКонтакте проверяем, что отображается экран со скрина
<img src="https://github.com/user-attachments/assets/401d894e-897c-4880-8f39-d9551d877026" width=500px>

55. Центр коммерции. Каталог. История загрузок. Проверяем что в разделе отображаются верные данные о загрузке товаров и все соответсвует настройкам каталога.
56. Центр коммерции. Каталог. История загрузок. Проверяем, что данные в поле следующего обновления соответсвуют настройка каталога.
57. Центр коммерции. Каталог. История загрузок. Проверяем, что список обновлений составлен верно и содержит правильные данные
58. Центр коммерции. Каталог. История загрузок. Проверяем, что при нажатии на «Обновить сейчас» происходит принудительная загрузка фида.
59. Центр коммерции. Каталог. История загрузок. Нажатие на «Обновить сейчас». Проверяем, что после прохождения появляется новая запись в листе, а данные в разделе обновляются 

## Лид-формы и опросы
1. Лид-формы и опросы. Лид-формы. Эмптистейт. Проверяем содержимое эмптистейта, в нем должна нходиться кнопка создать лид-форму и ссылка на прохождение обучения
<img src="https://github.com/user-attachments/assets/c1efa71c-64cb-4f0b-a138-6073397c4ca1" width=500px>

2. Лид-формы и опросы. Лид-формы. Эмптистейт. Нажимаем на пройти обучение. Проверяем, что появилась модалка с четырмя опциями: «Настроить кампанию с подсказками», «Создать лид-форму с подсказками», «Смотреть видеоурок от экспертов VK» и «Смотреть курс на обучающей платформе»
3. Лид-формы и опросы. Лид-формы. Эмптистейт. Обучение. Проверить, что «Настроить кампанию с подсказками» запускает обучение по создании компании, при закрытии подсказки появляется модалка с вопросом «Прервать обучение?», если нажать прервать, то обучающие подсказки пропадут
4. Лид-формы и опросы. Лид-формы. Эмптистейт. Обучение. Проверить, что «Создать лид-форму с подсказками» запустит создани формы с подсказками, надо проверить содержание этих подсказок. При закрытии подсказки появляется модалка с вопросом «Прервать обучение?», если нажать прервать, то обучающие подсказки пропадут
5. Лид-формы и опросы. Лид-формы. Эмптистейт. Обучение. «Смотреть видеоурок от экспертов VK» возвращает модалку с видеоуроком в VK видео
6. Лид-формы и опросы. Лид-формы. Эмптистейт. Обучение. «Смотреть курс на обучающей платформе» перенаправляет на сайт с курсом
7. Лид-формы и опросы. Лид-формы. Создание формы. Проверяем, что запускается многошаговая форма на каждом этапе проверяем отображение данных в инпуте. При неверных данных под полем должна появиться ошибка.
8. Лид-формы и опросы. Лид-формы. Создание формы. Проверяем что черновики работают. Если ввести данные и попытаться выйти из модалки появится попап с предложением сделать черновик. Сохраняем и заходим в форму еще раз, появится окно с предложением испльзовать черновик, проверяем, что если согласиться, то значения в полях востановятся, если отказаться то форма останется пустой
9. Лид-формы и опросы. Лид-формы. Создание формы. После прохождения формы проверяем, что она отобразилась в списке и данные верны
10. Лид-формы и опросы. Лид-формы. Список форм. Проверяем, что форму можно редактировать и, что ее можно удалить
11. Лид-формы и опросы. Лид-формы. Формы YCLIENTS. Эмптистейт. Проверяем, что эмптистейт выглядит как на скрине. Кнопка с инструкцией должна вести на внешиний ресурс
<img src="https://github.com/user-attachments/assets/87290aad-a2fe-4c3c-baa1-c6708f3dfd7f" width=500px>

12. Лид-формы и опросы. Лид-формы. Формы YCLIENTS. Проверяем, что по нажатию на «перейти в YCLIENTS» переносит на https://www.yclients.com/
13. Лид-формы и опросы. Лид-формы. Формы YCLIENTS. Проверяем, что после вставки кода появляется данные появляются в списке и ими можно управлять
14. Лид-формы и опросы. Лид-формы. Опросы. Эмптистейты. Проверяем, что эмптистейт выглядит как на скрине
<img src="https://github.com/user-attachments/assets/2cd3b2d0-8fba-46d3-82ab-7aa704e6ee4d" width=500px>

15. Лид-формы и опросы. Лид-формы. Опросы. Создание опроса. Проверяем, что при нажатии на создать опрос открывается многошаговая форма и при вводе данных в поля обрабатываются ошибки в них
16. Лид-формы и опросы. Лид-формы. Опросы. Создание опроса. Проверяем, работу черновиков. Если ввести данные и попытаться выйти из модалки появится попап с предложением сделать черновик. Сохраняем и заходим в форму еще раз, появится окно с предложением использовать черновик, проверяем, что если согласиться, то значения в полях востановятся, если отказаться то форма останется пустой
17. Лид-формы и опросы. Лид-формы. Опросы. Создание опроса. После создания опроса, проверяем, что он появился в списке и им можно управлять в этом списке 

## Общие компоненты
1. Меню. Проверяем, что нажатие на кнопку в меню переносит в соответсвующий раздел
2. Меню. Промо. Проверяем, что в пустом месте появляестя промо. При нажатии редеректит на внешнюю страницу и пропадает, при нажати на крестик просто пропадает
3. Хедер. Лого. Проверяем, что по клинку на лого происходит редирект на Главную страницу
4. Хедер. Профиль. При нажатии на профиль появляется выпдающее меню с аккаунтами
5. Хедер. Профиль. При нажатии в выпадающм меню на все кабинеты происходит редирект на вкладку в настройках
6. Хедер. Баланс. Проверяем, что данные отображаются верно
7. Хедер. Баланс. Проверяем, что при нажатии появляется модалка с пополнением счета
8. Хедер. Баланс. Проверяем, что поля в модалке отдают ошибку при неверных данных и, что само пополнение через нее работает
9. Хедер. Уведомления. Проверяем, что при нажатии на знчок появляется список всех уведомлений или эмптистейт, как на скрине, если уведомлений нет
<img src="https://github.com/user-attachments/assets/daec3761-bbf4-45c0-ac35-9943542c4c0b" width=300px>

10. Хедер. Уведомления. Проверяем, что нажатие на «три точки» -> «отметить все как прочитанное» отмечает уведомления прочитанными
11. Хедер. VKID. Проверяем, что при нажатии раскрывается подробная информация о профиле VKID
12. Хедер. VKID. При нажатии на профиль редиректит на страницу профиля VKID
13. Хедер. VKID. Проверить, что при нажатии на выйти, происходит выход из профиля VKID 
