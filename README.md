# Rock Paper Scissors Game - Variant 25

## Опис репозиторію
Цей репозиторій містить реалізацію гри "Камінь, Ножиці, Папір" для студентів відповідно до варіанта 25 із таблиці завдань. У проєкті реалізовано серверну частину гри на базі мікроконтролера Arduino R3, а клієнтська частина написана на Python.

## Деталі завдання
Завдання: Реалізувати гру "Камінь, Ножиці, Папір", де серверна частина працює на Arduino, а клієнтська — на Python. Сервер повинен отримувати команди від клієнта, обробляти їх і повертати результат.

## Інформація про студента
- **Студент:** Федусь Назарій Володимирович  
- **Номер варіанту:** 25

## Технології та мови програмування
- **Мови програмування:** C++ (Arduino), Python
- **Технології:**
  - Arduino для реалізації серверної частини, що приймає команди через послідовний інтерфейс UART.
  - Python для створення клієнтської програми, що надсилає команди на сервер і отримує результати.
  - Використання серійної передачі даних для взаємодії між клієнтом і сервером.

## Вимоги до апаратного та програмного забезпечення
- **Апаратне забезпечення:** Arduino R3, USB-кабель для підключення
- **Операційна система:** Windows 10 / 11, Linux або macOS для клієнтської частини
- **RAM:** мінімум 2 GB
- **Програмне забезпечення:**
  - Arduino IDE для програмування серверної частини
  - Python 3.x для клієнтської програми
  - Бібліотека `pySerial` для реалізації серійної комунікації

## Майбутні завдання
У майбутніх завданнях планується розширення функціональності, наприклад, додавання додаткових режимів гри, таких як "Камінь, Ножиці, Папір, Ящірка, Спок", та вдосконалення алгоритму обробки команд на стороні сервера. Також передбачено можливість інтеграції з графічним інтерфейсом для клієнтської частини.
