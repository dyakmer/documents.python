# Новый репозиторий | Python

<a href = "https://docs.google.com/spreadsheets/d/1eN8P9HQpH9n6_x4Ts2xBy0fJD45iX4RfyjOejpU06qE/edit?usp=sharing"> Ссылка на test case, Check-list </a>

# Пример автотеста по документации

        1. Проверить, что поле ввода государственного номера РФ имеет маску ввода.
        input_field.clear() - Очищает поле ввода
        input_field.send_keys("A 000 AA") - Вводит строку "А 000 АА" в поле вода
        self.assertEqual(input_field.get_attribute("value"), "A 000 AA") - Проверяет, что значение поля ввода равно "А000АА"
