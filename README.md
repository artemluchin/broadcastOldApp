## Приложение Broadcast Old

[Установочный файл](https://github.com/artemluchin/broadcastOldApp/releases) приложения.

Данное приложение представляет собой мое вступительное задание "Телепрограмма",
завернутое посредством phoneGap. В коде я ничего не менял, за исключением
некоторых стилей, чтобы улучшить вид приложения.

### Скриншоты приложения

Главный вид приложения.

<img src="https://github.com/artemluchin/broadcastOldApp/blob/master/screenshots/mainView.png" width="240"/>

Вид при работающих фильтрах.

<img src="https://github.com/artemluchin/broadcastOldApp/blob/master/screenshots/flterActive.png" width="240"/>

Вид иконки приложения.

<img src="https://github.com/artemluchin/broadcastOldApp/blob/master/screenshots/iconView.png" width="240"/>

### Трудности при реализации

1. Не читал json файл, хотя в `config.xml` стоял доступ ко всем ресурсам. Вылечилось путем добавления плагина `cordova-plugin-whitelist`.

Данное задание сделалось быстро и без особых трудностей. Поэтому я решил сделать
новое приложение, которое было бы похоже на нативное, используя какой-либо из фреймворков.
Выбор пал на Onsen UI. Таким образом появилось обновленное [приложение "Телепрограмма"](https://github.com/artemluchin/broadcastNewApp)