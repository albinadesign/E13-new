# E13-new
-> Установить и настроить webpack-dev-server.

-> Настроить hot module replacement.

-> Сделать возможность запуска на разных окружениях (dev, prod) c разной конфигурацией (например, убрать HMR на проде).

-> Настроить JSON-server и отображать полученные с него данные.

-> Добавить запуск линтера при комите.


чтобы клонировать проект: 
1) окрываем новый проект в IDE
2) в терминале git clone https://github.com/albinadesign/E13-new.git
3) переходим в папку с проектом cd E13-new
4) npm i

запуск в режиме development npm run dev

запуск в режиме production: npm run prod

запуск JSON server: json-server --watch database.json

запуск линтера: npm run lint
