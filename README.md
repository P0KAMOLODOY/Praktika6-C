1. Динамический ввод данных:
   - Программа принимает ввод до пустой строки или достижения максимального числа строк
   - Каждая строка сохраняется в массив `lines`

3. Обработка имени файла:
   - Первая строка считается именем файла
   - Выводится отдельно от содержимого

4. Объединение содержимого:
   - Все строки, кроме первой, объединяются в одну строку `content`
   - Между строками добавляются символы переноса

5. Поиск слова "Привет":
   - Используется стандартная функция `strstr()` для поиска подстроки
   - Результат поиска выводится пользователю
