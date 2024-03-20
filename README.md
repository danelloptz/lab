# Тут будет название будущего сервиса👋
---
> *Пользователь печатает....*

## Суть сервиса 👾
Пользователь должен за ограниченное время набрать случайный (осмысленный) текст. Пользователь может менять  уровень сложности - выбирать время на набор текста и его объём. Рыба-текст генерируется на стороннем сервере (fish-text api).

## Плюшки 👀
Полная статистика: точность печати (в процентах), средняя скорость, символы, в печати которых пользователь ошибается ччаще всего, кол-во успешных и неудачных попыток, лучшие результаты в скорости и точности печати.

## Возможность расширения 😎
Сервис расширяем. Возможность, добавить диаграммы или прочую визуализацию статистики.

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
