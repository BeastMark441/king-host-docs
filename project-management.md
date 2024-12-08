---
description: >-
  Расскажем как работает управление проектом со стороны хостинга и несколько
  рекомендаций.
icon: gear
---

# Управление Проектом

{% hint style="info" %}
Так как хостингом по большей части пользуются для создания Minecraft сервером, рассматривать будем их, но многие части будут применимы так же и для остальных видов серверов на панели управления Pterodactyl.
{% endhint %}

## Создание сервера

Чтобы создать сервер, его нужно заказать в билинг панели, для этого нужно пройти несколько шагов:

1. [Зарегистрироваться или Авторизоваться](regiater-and-settings.md)
2. Перейти на вкладку Minecraft Хостинг
3. Выбрать интересующий тариф и кликнуть "Купить"
4. В окне пополнения выбрать удобный тип оплаты и нажать кнопку "Пополнить"
5. Завершить оплату по инструкциям банка, сохранить чек и вернуться в  магазин.
6. Сервер активирован и готов к использованию

{% hint style="warning" %}
В случае возникновения проблем с оплатой или активацией сервера попробуйте произвести оплату снова, в случае повторной неудачи обратитесь в поддержку
{% endhint %}

Теперь вы можете перейти в панель управления серверами и настроить Ваш сервер.

Чтобы это сделать, Вам нужно перейти по адресу [https://panel.king-host.ru](https://panel.king-host.ru) или во вкладке продуктов нажать на "Управление Сервером".

После перехода вам нужно будет произвести авторизацию пользователя.\
Данные для авторизации точно такие же как и для билинг панели.

После авторизации на странице вы увидите Ваш сервер, в случае если он ещё не успел установиться, вы увидите у него соответствующий статус.

<div align="left"><figure><img src=".gitbook/assets/изображение (4).png" alt="Статус установки &#x22;Выполняется установка&#x22;" width="313"><figcaption></figcaption></figure> <figure><img src=".gitbook/assets/изображение (2).png" alt="Статус сервера &#x22;Установка&#x22;"><figcaption></figcaption></figure></div>

## Запуск minecraft сервера

После покупки сервера, его стоит настроить.

Вот несколько шагов которые стоит сделать в первую очередь.

* Остановить сервер
* Перейти во вкладку "версии" и выбрать необходимое вам ядро и версию. Либо самостоятельно как это сделать рассказали в  ["Работа с файлами"](project-management.md#rabota-s-failami).

{% hint style="warning" %}
Если вы уже использовали смену версий и ставили например Forge или Fabric ядро, а затем решили использовать обычные ядра для плагинов и загрузить их самостоятельно, то нужно запустить единожды процесс установки такого ядра (например Paper) через функцию панели.&#x20;



Делается это для изменения параметров запуска.\
\
В противном случае у вас останутся параметры запуска для запуска forge или fabric ядра, которые обычно не совместимы с другими ядрами.
{% endhint %}

* После выборка и установки версии. Единожды запустите, а затем остановите сервер.
*   Во время 1-го запуска Вам нужно будет согласится с пользовательским соглашением minecraft. Вы увидите специальную кнопку для этого.

    <figure><img src=".gitbook/assets/изображение (1).png" alt=""><figcaption></figcaption></figure>
* После выполнения этих действий Вы можете перейти на вкладку "Запуск" и выбрать некоторые параметры, такие как:
  * Версия Java
  * Онлайн Мод _(Проверка на лицензию у игроков)_
  * По необходимости номер сборки и версию Minecraft
  * Имя файла сервера для запуска _(jar файл ядра)._

Самая базовая настройка сервера на этом завершается, теперь для редактирования файлов сервера переходим в раздел ["Работа с Файлами"](project-management.md#rabota-s-failami)



***

## Работа с файлами

На хостинге поддерживаются функции загрузки из браузера, но у них есть некоторые ограничения, например нельзя загрузить папку, нельзя загружать файлы размером более 200 мегабайт.\
Чтобы избежать эти ограничения прочитайте пункт ["Загрузка через SFTP клиент"](project-management.md#zagruzka-cherez-sftp-klient)

Иногда функция загрузки из браузера может быть удобным и быстрым решением в совокупности с функцией Drag-and-drop.

### Загрузка через браузер

В панели управления во вкладке "Файлы" у вас есть кнопки Создания каталога, Нового файла и Загрузка.

При нажатии кнопки загрузки у вас откроется окно проводника в котором вы сможете выбрать, какой файл хотите загрузить.

Так же вы это можете сделать не нажимая кнопку, просто перетащив файл в зону загрузки которая автоматически подсветится.



### Загрузка через SFTP клиент

Есть несколько достаточно популярных SFTP клиентов

Рассмотрим как подключиться к серверу на примере FileZilla и WinSCP

{% tabs %}
{% tab title="FileZilla" %}

{% endtab %}

{% tab title="WinSCP" %}

{% endtab %}
{% endtabs %}


