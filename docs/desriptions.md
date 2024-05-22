## Тест №1.1 login (позитивный)
Цель: Проверка успешного входа пользователя с корректными данными.

Входные данные: Форма входа с действительными данными пользователя (например, существующий email и пароль).

Ожидаемый результат: Перенаправление на страницу лобби игры  и сохранение данных пользователя в localStorage.

Описание процесса: Используется стандартный вызов функции login с контролем перенаправления и сохранения данных в localStorage. Предварительной подготовки не требуется.

## Тест №1.2 login (отрицательный)
Цель: Проверка поведения при попытке входа с неверными данными.

Входные данные: Форма входа с недействительными данными пользователя (например, неверный email или пароль).

Ожидаемый результат: Отображение сообщения об ошибке.

Описание процесса: Используется стандартный вызов функции login с контролем отображения сообщения об ошибке. Предварительной подготовки не требуется.

## Тест №2.1 registr (позитивный)
Цель: Проверка успешной регистрации нового пользователя.

Входные данные: Форма регистрации с действительными данными пользователя (например, имя, email и пароль).

Ожидаемый результат: Перенаправление на страницу лобби игры и сохранение данных пользователя в localStorage.

Описание процесса: Используется стандартный вызов функции registr с контролем перенаправления и сохранения данных в localStorage. Предварительной подготовки не требуется.

# Тест №2.2 registr (отрицательный)
Цель: Проверка поведения при попытке регистрации с повторяющимися данными.

Входные данные: Форма регистрации с уже зарегистрированным email и паролем.

Ожидаемый результат: Отображение сообщения об ошибке.

Описание процесса: Используется стандартный вызов функции registr с контролем отображения сообщения об ошибке. Предварительной подготовки не требуется.