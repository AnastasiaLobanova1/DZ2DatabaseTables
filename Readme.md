## Теория Баз данных
## ДЗ №2 Лобановой Анастсии
Создана база данных, содержащая таблицы с информацией о Группах (Groups), Кафедрах (Departments), Факультетах (Faculties) и Учителях (Teachers).

1. Таблица Groups
- Структура таблицы Groups![ссылка](https://thumb.cloud.mail.ru/weblink/thumb/xw1/xSiG/1QEeSKeRA)
- Ограничение параметра Year![ссылка](https://thumb.cloud.mail.ru/weblink/thumb/xw1/L44S/zbcTcGumv) При Year=0 - ошибка ![ссылка](https://thumb.cloud.mail.ru/weblink/thumb/xw1/Mgse/VKe2ZxeM1) 
- Ограничение параметра Rating ![ссылка](https://thumb.cloud.mail.ru/weblink/thumb/xw1/NbVx/K7x2iDwbd). 
При Rating=6 - ошибка ![ссылка](https://thumb.cloud.mail.ru/weblink/thumb/xw1/nHkA/3jmr9b4Vo)
- Запрос и результат ![ссылка](https://thumb.cloud.mail.ru/weblink/thumb/xw1/EucS/uiiVNW93E)
2. Таблица Departments
- Структура таблицы Departments ![ссылка](https://thumb.cloud.mail.ru/weblink/thumb/xw1/b3aL/Ranm1YVWP)
- Ограничение параметра Financing ![ссылка](https://thumb.cloud.mail.ru/weblink/thumb/xw1/vU5y/LD5jhiXJy). При Financing=-1 ошибка ![ссылка](https://thumb.cloud.mail.ru/weblink/thumb/xw1/a74h/qJ8FRnXis)
- Уникальность имени. При совпадении имен - ошибка ![ссылка](https://thumb.cloud.mail.ru/weblink/thumb/xw1/xDZB/k1QCi84xK)
- Запрос и результат  ![ссылка](https://thumb.cloud.mail.ru/weblink/thumb/xw1/y6QT/xc5Jdq9Sa)
3. Таблица Faculties
- Структура таблицы Faculties ![ссылка](https://thumb.cloud.mail.ru/weblink/thumb/xw1/ou1j/mqD9JjpUN)
- Уникальность имени. При совпадении имен - ошибка ![ссылка](https://thumb.cloud.mail.ru/weblink/thumb/xw1/8Wvt/LHPNUjaNd)
- Запрос и результат ![ссылка](https://thumb.cloud.mail.ru/weblink/thumb/xw1/hfYB/Mj85SW8SX)
4. Таблица Teachers
- Структура таблицы Teachers![ссылка](https://thumb.cloud.mail.ru/weblink/thumb/xw1/ZYjw/S2sdej2C2)
- Ограничение параметра Date ![ссылка](https://thumb.cloud.mail.ru/weblink/thumb/xw1/7v6R/5i1GA1doX) При Date=01.01.1989 ошибка ![ссылка](https://thumb.cloud.mail.ru/weblink/thumb/xw1/2gn2/5tdLKpLdk)
- Ограничение параметра Premium![ссылка](https://thumb.cloud.mail.ru/weblink/thumb/xw1/FppF/CXVPGmBXs) При Premium=-2 ошибка ![ссылка](https://thumb.cloud.mail.ru/weblink/thumb/xw1/FppF/CXVPGmBXs)
- Ограничение параметра Salary
![ссылка](https://thumb.cloud.mail.ru/weblink/thumb/xw1/tdbH/avnVhXG3g) При Salary=0 ошибка ![ссылка](https://thumb.cloud.mail.ru/weblink/thumb/xw1/DXws/BUPiN1tdz)
- Запрос и результат ![ссылка](https://thumb.cloud.mail.ru/weblink/thumb/xw1/kF6h/3pzQzFpVC)



