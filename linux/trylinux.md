# Как попробовать линукс

Дата: 08-03-2022

- выбираем дистрибутив и de
- Скачиваем iso образ
- Первый способ
	- При помощи программы rufus записываем на какую-нибудь флешку. Размер флешки начиная с 2Гб. Лучше 4Гб
	- После успешной записи на флешку перезагружаем компьютер и заходим в boot меню. Для этого при запуске нажимаем клавишу входа в boot-меню. Иногда это F2 иногда F11, зависит от материнской платы вашего устройства. Часто при запуске компьютера можно увидеть подсказку)))
	- Попадаем в меню GRUB-загрузчика.
		- Try Ubuntu without installing необходимый нам пункт.
	- Система немного подумает, выгрузится в память и будет доступна к использованию.
	- _Все настройки сделанные в live-режиме не сохраняются нигде_
- Второй способ
	- Скачиваем программу VirtualBox. Данная программа позволит вам создать виртуалный компьютер прямо в вашей системе.
	- Устанавливаем наш скачанный образ)))
	- Не буду отбирать хлеб у людей, которые написали эту шикарную [статью](https://losst.ru/ustanovka-linux-na-virtualbox)