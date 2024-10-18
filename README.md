# Lab-5
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <title>Задание 15</title>
</head>
<body>
    <div class="element">Element 1</div>
    <div class="element">Element 2</div>
    <div class="element">Element 3</div>
    <div class="element">Element 4</div>
    <div class="element">Element 5</div>
    <div class="element">Element 6</div>

    <script>
        const elements = document.getElementsByClassName('element');
        for (let i = 0; i < elements.length; i++) {
            if (i < 3) {
                elements[i].style.color = 'red';
            } else {
                elements[i].style.color = 'green';
            }
        }
    </script>
</body>
</html>
