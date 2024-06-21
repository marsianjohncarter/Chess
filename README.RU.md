# Шахматы
Это улучшенная версия [almatrass/chess-site](https://github.com/almatrass/chess-site)
В этой версии содержится улучшенная CSS-стилизация и механизм проверки JS-кода игры.

**Этот проект не работает на мобильных устройствах**

> *Был протестирован на веб-браузерах **Google Chrome**, **Edge**, **FireFox**, **Chromium**, и **Opera**.*

<hr>

### Инструкции (использования): 

> Живая страница: https://chess-website-completed.onrender.com/
> 
> **Примечание: Это может занять до минуты для загрузки**

Создайте игру, введя случайный код игры и нажав "Создать игру".

<img src="https://github.com/marsianjohncarter/Chess/assets/116607327/0efccd5f-902c-4189-a5c6-5e57de7a500c" width="500" height="200">

Присоединитесь к игре, введя случайный код игры, который вы ввели ранее, и нажав "Присоединиться к игре".

<img src="https://github.com/marsianjohncarter/Chess/assets/116607327/013506ec-bfeb-4c55-8635-b467e08a94d8" width="500" height="200">


Теперь вы сможете играть в шахматы с тем, кто подключится к вашей игре.
<img src="https://github.com/marsianjohncarter/Chess/assets/116607327/bd160133-6e9b-4b57-98b3-2b7783ae8bb1" width="500" height="550">
<hr>

## Зависимости:

|    Библиотека     |    Версия     |
|-------------------|----------------|
|dotenv             | ^16.3.1        |
|express            | ^4.18.2        |
|express-handlebars | ^7.0.7         |
|http               | ^0.0.1-security|
|path               | ^0.12.7        |
|socket.io          | ^4.7.2         |

### Инструкции (сборка и развертывание на локальной сети):

```
npm i
```

To start:

```
node ./server/server.js
```