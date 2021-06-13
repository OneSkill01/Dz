<!DOCTYPE HTML ">
<html>
 <head>
  <meta http-equiv=" Content-Type" content="text/html; charset=utf-8">
<title>Анкета</title>
</head>

<body>

    <script>
        var lastName = prompt('Ваше фамилия?');
        var firstName = prompt('Ваша имя?');
        var potranimic = prompt('Ваше отчество?');
        var age = parseInt(prompt('Ваш возраст в годах?'));
        var agedays = age * 365;
        var agefive = age + 5;
        var sex = confirm('Нажмите ок если ваш пол мужской')
        if (sex) sex = 'мужской';
        else sex = 'женский';
        if (age > 65) var pensioner = 'да';
        else pensioner = 'нет';


        alert('ваше ФИО:' + ' ' + lastName + ' ' + firstName + ' ' + potranimic + '\n' + 'ваш возраст в годах:' + ' ' + age + '\n'
            + 'ваш возраст в днях:' + ' ' + agedays + '\n' + 'через 5 лет вам будет:' + ' ' + agefive + '\n' + 'ваш пол' + ' ' + sex + '\n'
            + 'вы на пенсии:' + ' ' + pensioner)
    </script>

</body>

</html>
