# Typeguru 👋
---
> *Пользователь печатает....*

## Описание функциональных моделей        
* [functions.md](docs/functions.md)     
## Описание структурных моделей        
* [functions.md](docs/struct.md) 
## Поведенческие модели              
* [functions.md](docs/behaviour.md)     

## Суть сервиса 👾
Пользователь может набирать случайный осмысленный текст на скорость. Система считает точность и скорость печати. Пользователь может смотреть статистику каждой попытки, а также смотреть глобальную статистику в своём профиле, например активность за последние 7 дней, топ пользователей на сервере, средняя скорость и точность печати за всё время. Также в сервисе есть система оценивания. В зависимости от определённых критериев за каждую попытку пользователю начисляется определённое кол-во очков. В разделе статистики пользователю может посмотреть его лучшую попытку и топ попыток на сервере.

## Возможность расширения 😎
Сервис расширяем. Из глобальных идей: возможность добавить книгу для того, чтобы читать и печатать одновременно.       

## Стэк технологий 💀
Front: HTML/CSS, SCSS, JavaScript, Webpack     
Backend: NodeJS, Express     

## Описание функциональностей
Новый пользователь должен зарегистрироваться в системе:       
	- Пользователь заполняет данные для регистрации: имя, почта, пароль, подтверждение пароля, и попадает в систему     
Пользователь, имеющий аккаунт:     
	- Пользователь вводит данные для входа и попадает в систему      
После регистрации/авторизации пользователь попадает в главное меню игры, где он может:     
	- начать игру        
	- посмотреть статистику      
	- в настройках изменить своё имя, почту, включить/выключить фоновую музыку, выйти из системы       
При нажатии кнопки "Играть", пользователю будет предложено выбрать уровень сложности игры: лёгкий, средний, сложный. Уровень сложности высчитывается отностительно количества символов, времени на печать текста и точность печати.      
После выбора сложности начинается игра. Перед пользователем появляется случайный осмысленный текст и ему необходимо за ограниченное время (в зависимости от сложности игры) успеть набрать текст.        
После истечения времени перед пользователем появляется статистика текущей попытки: успешность, точность печати, скорость печати, символы, на которых пользователь допускал большее число ошибок.      
Статистика после каждой попытки сохраняется и доступна пользователю. Пользователь может посмотреть свои результаты на главной странице, нажав кнопку "Статистика".

## Функциональные возможности      
- Регистрация      
- Авторизация      
- Главное меню игры      
- Личный кабинет      
- Режим игры      
- Меню статистики
