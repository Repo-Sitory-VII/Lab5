# Lab5
<p align = "center">МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ<br>
РОССИЙСКОЙ ФЕДЕРАЦИИ<br>
ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ<br>
ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ<br>
«САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</p>
<br><br><br><br><br><br>
<p align = "center">Институт естественных наук и техносферной безопасности<br>Кафедра информатики<br>Панихин Андрей Алексеевич</p>
<br><br><br>
<p align = "center"><br><strong>Лабораторная работа №1.</strong><br>01.03.02 Прикладная математика и информатика</p>
<br><br><br><br><br><br><br><br><br><br><br><br>
<br><br><br>
<p align = "center">г. Южно-Сахалинск<br>2024 г.</p>
<br><br><br><br><br><br>

<h1 align = "center">Введение</h1>
HTML — это язык разметки гипертекстовых документов. Он нужен, чтобы отображать в браузере специальным образом отформатированный документ с множеством вложенных элементов: заголовками, абзацами, списками, гиперссылками, медиаисточниками, расположением изображений, видео и аудио.

<h1 align = "center">Цели и задачи</h1>

Решение задач с помощью языка JavaScript

<h1 align = "center">Решение</h1>
<h2 align = "center">Файл 5.1.html</h2>

~~~html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p id="output"></p>
    <script>
        var str = "hdfgv";
        document.getElementById("output").innerHTML = str[0] + str[1] + str[4];
    </script>
</body>
</html>
~~~
<h2 align = "center">Файл 5.2.html</h2>

~~~html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p id="output"></p>
    <script>
        document.getElementById("output").innerHTML = 60*60;
    </script>
</body>
</html>
~~~
<h2 align = "center">Файл 5.3.html</h2>

~~~html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p id="output"></p>
    <script>
        var num = 1;
        document.getElementById("output").innerHTML += num + '\n';
        num += 12;
        document.getElementById("output").innerHTML += num + '\n';
        num -= 14;
        document.getElementById("output").innerHTML += num + '\n';
        num *= 5;
        document.getElementById("output").innerHTML += num + '\n';
        num /= 7;
        document.getElementById("output").innerHTML += num + '\n';
        num += 1;
        alert(num);
    </script>
</body>
</html>
~~~
<h2 align = "center">Файл 5.4.html</h2>

~~~html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p id="output"></p>
    <script>
        var num = 3;
        alert(num);
    </script>
</body>
</html>
~~~
<h2 align = "center">Файл 5.5.html</h2>

~~~html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p id="output"></p>
    <script>
        var a = 10, b = 2;
        document.getElementById("output").innerHTML += "a + b = " + (a + b);
        document.getElementById("output").innerHTML += "a - b = " + (a - b);
        document.getElementById("output").innerHTML += "a * b = " + (a * b);
        document.getElementById("output").innerHTML += "a / b = " + (a / b);
    </script>
</body>
</html>
~~~
<h2 align = "center">Файл 5.6.html</h2>

~~~html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p id="output"></p>
    <script>
        var c = 15, d = 2, result = c + d;
        document.getElementById("output").innerHTML = result;
    </script>
</body>
</html>
~~~
<h2 align = "center">Файл 5.7.html</h2>

~~~html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p id="output"></p>
    <script>
        var a = 10, b = 2, c = 5;
        document.getElementById("output").innerHTML = a + b + c;
    </script>
</body>
</html>
~~~
<h2 align = "center">Файл 5.8.html</h2>

~~~html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p id="output"></p>
    <script>
        var a = 17, b = 10, c = a - b, d = 7, result = c + d;
        document.getElementById("output").innerHTML = result;

    </script>
</body>
</html>
~~~
<h2 align = "center">Файл 5.9.html</h2>

~~~html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p id="output"></p>
    <script>
        document.getElementById("output").innerHTML += "Час:" + (60*60) + " с";
        document.getElementById("output").innerHTML += "Сутки:" + (60*60*24) + " с";
        document.getElementById("output").innerHTML += "Месяц:" + (60*60*24*30) + " с";
    </script>
</body>
</html>
~~~
<h2 align = "center">Файл 5.10.html</h2>

~~~html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p id="output"></p>
    <script>
        var now = new Date(), hour = now.getHours(), minute = now.getMinutes(), second = now.getSeconds();
        document.getElementById("output").innerHTML = (hour < 10 ? "0" : "") + hour + ":" + (minute < 10 ? "0" : "") + minute + ":" + (second < 10 ? "0" : "") + second;
    </script>
</body>
</html>
~~~
<h2 align = "center">Файл 5.11.html</h2>

~~~html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p id="output"></p>
    <script>
        var a = 5;
        document.getElementById("output").innerHTML = a*a;
    </script>
</body>
</html>
~~~
<h2 align = "center">Файл 5.12.html</h2>

~~~html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p id="output"></p>
    <script>
        [1,2,3,4,5].forEach((element) => document.getElementById("output").innerHTML += element*element + '\n')
    </script>
</body>
</html>
~~~
<h2 align = "center">Файл 5.13.html</h2>

~~~html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p id="output"></p>
    <script>
        var str = "hdfgv";
        document.getElementById("output").innerHTML = 1.15 + 2.30;
    </script>
</body>
</html>
~~~
<h2 align = "center">Файл 5.14.html</h2>

~~~html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p id="output"></p>
    <script>
        let x = 5;
        alert(x++);
    </script>
</body>
</html>
~~~
<h2 align = "center">Файл 5.15.html</h2>

~~~html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p id="output"></p>
    <script>
        document.getElementById("output").innerHTML = [] + false - null + true;
    </script>
</body>
</html>
~~~
<h2 align = "center">Файл 5.16.html</h2>

~~~html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p id="output"></p>
    <script>
        let y = 1;
        let x = y = 2;
        console.log(x);
    </script>
</body>
</html>
~~~
<h2 align = "center">Файл 5.17.html</h2>

~~~html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p id="output"></p>
    <script>
        document.getElementById("output").innerHTML = [] + 1 + 2;
    </script>
</body>
</html>
~~~
<h2 align = "center">Файл 5.18.html</h2>

~~~html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p id="output"></p>
    <script>
        var a6 = 5 % 3, a7 = 3 % 5, a8 = 5 + '3', a9 = '5' - 3, a10 = 75 + 'кг';
        document.getElementById("output").innerHTML = a6 + '\n' + a7  + '\n' + a8 + '\n' + a9 + '\n' + a10;
    </script>
</body>
</html>
~~~
<h2 align = "center">Файл 5.19.html</h2>

~~~html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p id="output"></p>
    <script>
        var height = 23, width = 10, s = height * width;
        document.getElementById("output").innerHTML = s;
    </script>
</body>
</html>
~~~
<h2 align = "center">Файл 5.20.html</h2>

~~~html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p id="output"></p>
    <script>
        var heightC = 10, dC = 4, v = Math.pi * dC*dC/4 * heightC;
        document.getElementById("output").innerHTML = v;
    </script>
</body>
</html>
~~~
<h2 align = "center">Файл 5.21.html</h2>

~~~html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p id="output"></p>
    <script>
        s = 2000000, p = 0.1, years = 5, perepl = s * Math.pow(p,years);
        document.getElementById("output").innerHTML = perepl;
    </script>
</body>
</html>
~~~
<h2 align = "center">Файл 5.22.html</h2>

~~~html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p id="output"></p>
    <script>
        var str = "Привет", num = 123, flag = true, txt = "true";
        document.getElementById("output").innerHTML = typeof str + '\n' + typeof num + '\n' + typeof flag + '\n' + typeof txt;
    </script>
</body>
</html>
~~~
<h2 align = "center">Файл 5.23.html</h2>

~~~html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p id="output"></p>
    <script>
        var num = 5;
        document.getElementById("output").innerHTML = -num;
    </script>
</body>
</html>
~~~

<h1 align = "center">Codewars</h1>

<h2 align = "center">Determine offspring sex based on genes XX and XY chromosomes</h2>
~~~
function chromosomeCheck(sperm) {
  return "Congratulations! You\'re going to have a " + (sperm == "XY" ? "son." : "daughter.");
}
~~~

<h2 align = "center">Simple multiplication</h2>
~~~js
function simpleMultiplication(number) {
    return number * (number % 2 == 1 ? 9 : 8)
}
~~~

<h2 align = "center">Find Nearest square number</h2>
~~~js
function nearestSq(n){
  return Math.pow(Math.round(Math.sqrt(n)), 2);
}
~~~

<h2 align = "center">Count the number of cubes with paint on</h2>
~~~js
function countSquares(cuts){
  return cuts == 0 ? 1 : (cuts+1)**3 - (cuts-1)**3
}
~~~

<h2 align = "center">Is your period late?</h2>
~~~js
function periodIsLate(last, today, cycleLength) {
  return (today-last)/86400000 > cycleLength;
}
~~~

<h2 align = "center">Remove String Spaces</h2>
~~~js
function noSpace(x){
  return x.replaceAll(" ","");
}
~~~

<h1 align = "center">Решение</h1>

![](assets/site.png)

<h1 align = "center">Вывод</h1>

Научился базовому функционалу HTML создав простой вебсайт.
