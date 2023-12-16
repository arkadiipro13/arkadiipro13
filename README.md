<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Админ-панель</title>
</head>
<body>
    <h1>Админ-панель</h1>
    <form action="/pretend_bot" method="post">
        <label for="pretend_bot_mode">Режим 'притвориться ботом'</label>
        <input type="checkbox" id="pretend_bot_mode" name="pretend_bot_mode">
        <br>
        <button type="submit">Применить</button>
    </form>
    <form action="/history" method="post">
        <label for="user_id">История переписки с пользователем (user_id):</label>
        <input type="text" id="user_id" name="user_id" required>
        <br>
        <button type="submit">Показать историю</button>
    </form>
</body>
</html>
ke a look at your changes.
--->
