# DLE Billing

[![Version](https://img.shields.io/badge/Version-0.7.4-blue.svg?style=flat-square "Version")](https://github.com/Japing/dle-billing/releases)
![DLE](https://img.shields.io/badge/DLE-13.0--13.3-green.svg?style=flat-square "DLE")
![Charset](https://img.shields.io/badge/Charset-utf--8-red.svg?style=flat-square "Charset")
![jQuery](https://img.shields.io/badge/jQuery-1.11+-yellow.svg?style=flat-square "jQuery")

Автоматизируйте приём платежей на сайте с помощью модуля DLE Billing. Предоставте пользователям возможность оплачивать различные товары и услуги вашего сайта.

 **Автор модуля:** mr_Evgen (evgeny.tc@gmail.com)  
 **Адаптировал:** Japing

### **Плагины для DLE Billing**
- [Платный переход в группу](https://github.com/Japing/Paygroup-DLE-Billing)
- [Оплата скрытого текста](https://github.com/Japing/Payhide-DLE-Billing)

### **Системные требования**
- Версия DataLife Engine 13.0 - 13.3
- jQuery v1.11 и выше
- ЧПУ (mod_rewrite)
- Кодировка по умолчанию: UTF-8

### **Установка и настройка модуля:**
1. [Скачать архив](https://github.com/Japing/dle-billing/releases "Скачать архив") с модулем
2. Заходить в **Админ панель** -> **Утилиты** -> **Управление плагинами** и загрузить скачанный архив
3. Открыть страницу Ваш_Сайт.ру/admin.php?mod=billing
4. Выполнить инструкции установщика
5. Настроить модуль

### **Обновление:**
1. Обновите модуль через систему плагинов
2. Войдите в админ.панель модуля для автоматического обновления бд и файла настроек.

P.S Выкладываю модуль с согласия автора **mr_Evgen** (evgeny.tc@gmail.com)

------------
### Список изменений

#### v0.7.4 (25.08.2019)
- Модуль полностью адаптирован к системе плагинов.
- В личный кабинет пользователя добавлен раздел **«Квитанции»**, в котором отображается список всех квитанций.
- В настройках модуля добавлен новый пункт, указывающий максимальное количество неоплаченных квитанций которые может создать пользователь.
- В личный кабинет пользователя добавлена возможность удалять неоплаченные квитанции.
- Исправлена ошибка при отображении статистики в админ панель модуля.
- Изменён принцип создание новых квитанций: теперь создается квитанция и её можна оплачивать любой платежной системой.

#### v0.7.3 (06.06.2019)
- Модуль адаптирован под DLE 13.0 и выше .
- Изменены иконки в админ панель модуля.
