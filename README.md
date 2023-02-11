# OPRIC - ОПРИС - Электронное учебное пособие (ЭУП) по основам программирования на С++ #
## Кроссплатформенность ##
Проект выполнен с помощью платформы Xamarin.Forms, поэтому его можно запустить на различных платформах:
| Платформа | Минимальная версия системы | Доступная версия приложения
| -- | -- | -- |
| Android | 6.0 (API 23) | 1.1.0 |
| iOS | 10 | Preview |
| Windows | 10 (Universal Windows Platform) | 1.1.0 |
| macOS | Mojave (10.14) | Preview |
## Установка и запуск ##
Установочный файл для своей целевой платформы можно найти во вкладке "Релизы" (*Releases*), которая расположена по [ссылке](https://github.com/LeoKhariton/Mobile-Cpp-Tutorial/releases).
### Android ###
Скачайте установочный файл .apk из раздела "Релизы" и запустите его на устройстве Android.  
Возможно, при установке приложение потребует дополнительное разрешение - доступ в интернет.  
Предпочтительно, чтобы системная тема Andriod была *светлая*.  
После открытия приложения загрузится главная страница - страница выбора раздела:  
![a1](https://github.com/LeoKhariton/Opric/blob/main/Setup/Android/a1.jpg)  
В верхнем левом углу есть значок "гамбургер", который открывает всплывающее меню:
![a2](https://github.com/LeoKhariton/Opric/blob/main/Setup/Android/a2.jpg)  
Кликнув по соответствующему названию раздела, открывается страница с вкладками, на которой располагается содержимое раздела. На нижних вкладках можно выбрать "Лекцию", "Тест" или "Практическое занятие". На верхних вкладках можно выбрать конкретный подраздел лекции:  
![a3](https://github.com/LeoKhariton/Opric/blob/main/Setup/Android/a3.jpg)  
или задание для практической/лабораторной работы:  
![a4](https://github.com/LeoKhariton/Opric/blob/main/Setup/Android/a4.jpg)  
После открытия вкладки "Тест" появится начальное уведомление, оповещающее пользователя о начале тестирования. При положительном ответе начнется тестирование, при отрицательном - совершится переход к началу раздела.  
![a5](https://github.com/LeoKhariton/Opric/blob/main/Setup/Android/a5.jpg)  
Следующее уведомление напоминает количество времени, отведенного под тестирование:  
![a6](https://github.com/LeoKhariton/Opric/blob/main/Setup/Android/a6.jpg)  
Вопросы в тесте загружаются в случайном порядке.  
Отвечать можно, нажимая на кнопки с соответствующими вариантами ответа. При верном ответе кнопка загорится зеленым цветом:  
![a7](https://github.com/LeoKhariton/Opric/blob/main/Setup/Android/a7.jpg)  
При неверном ответе выбранная кнопка загорится красным цветом:  
![a8](https://github.com/LeoKhariton/Opric/blob/main/Setup/Android/a8.jpg)  
После нажатия на кнопку "Завершить сейчас!", ответа на последний вопрос теста либо при окончании времени, отведенного для тестирования, подводятся его итоги: появляется соответствующее уведомление:  
![a9](https://github.com/LeoKhariton/Opric/blob/main/Setup/Android/a9.jpg)
### Universal Windows ###
Это приложение является универсальным приложением Windows (т.е. доступно как на десктопных платформах, так и на Windows Phone). Поэтому установочный файл имеет не привычное расширение .exe, а .APPX или .APPXBUNDLE.  
1. Скачайте файл .appxbundle из раздела "Релизы"  
2. Откройте окно свойств установочного файла и перейдите к вкладке "Цифровые подписи". Выберите единственную подпись из списка и нажмите "Сведения":  
![w1](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w1.png)  
3. В открывшемся окне "Состав цифровой подписи" выберите "Просмотр сертификата":  
![w2](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w2.png)  
4. В открывшемся окне нажмите "Установить сертификат":  
![w3](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w3.png)  
5. Сертификат нужно установить для всего локального компьютера. Нажмите "Далее" от имени администратора:  
![w4](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w4.png)  
6. Выберите "Доверенные корневые центры сертификации", нажмите "ОК":  
![w5](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w5.png)  
7. А затем "Далее":  
![w6](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w6.png)  
8. Нажмите "Готово":  
![w7](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w7.png)  
9. Появится следующее уведомление:  
![w8](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w8.png)  
10. Закройте окно свойств. Запустите установщик - для этого кликните дважды по скачанному файлу .appxbundle:  
![w9](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w9.png)  
11. Откроется главная страница приложения:  
![w10](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w10.jpg)  
12. Опять же, предпочтительная тема операционной системы для наиболее корректного отображения графики - светлая. Дизайн приложения во многом такой же, как и на Android. Основное отличие заключается в том, что если запуск производится с компьютера (а не с Windows Phone), то доступны две дополнительные вкладки - онлайн-компилятор и редактор блок-схем, которые могут помочь при решении задач.  
![w11](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w11.jpg)  
![w12](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w12.jpg)  
## Публикации ##
1. [Приложение для кроссплатформенного компьютерного тестирования (XIX Международная конференция НИТиС-2022: Пенза, 17-18 ноября 2022)](https://vt.pnzgu.ru/files/vt.pnzgu.ru/nitis_sb_2022_vyp_xix_tir_a4_doc_1_.pdf)
