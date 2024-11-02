Домашнее задание по теме "Форматирование строк".

Цель задания:

Освоить различные методы форматирования строк в Python.

Научиться применять эти методы в контексте описания соревнования. История: соперничество двух команд - Мастера кода и Волшебники данных.

Задание:

Создайте новый проект или продолжите работу в текущем проекте.

Напишите код, который форматирует строки для следующих сценариев.

Укажите переменные, которые должны быть вставлены в каждую строку:

Использование %:

Переменные: количество участников первой команды (team1_num).

Пример итоговой строки: "В команде Мастера кода участников: 5 ! "

Переменные: количество участников в обеих командах (team1_num, team2_num).

Пример итоговой строки: "Итого сегодня в командах участников: 5 и 6 !"

Использование format():

Переменные: количество задач решённых командой 2 (score_2).

Пример итоговой строки: "Команда Волшебники данных решила задач: 42 !"

Переменные: время за которое команда 2 решила задачи (team1_time).

Пример итоговой строки: " Волшебники данных решили задачи за 18015.2 с !"

Использование f-строк:

Переменные: количество решённых задач по командам: score_1, score_2

Пример итоговой строки: "Команды решили 40 и 42 задач.”

Переменные: исход соревнования (challenge_result).

Пример итоговой строки: "Результат битвы: победа команды Мастера кода!"

Переменные: количество задач (tasks_total) и среднее время решения (time_avg).

Пример итоговой строки: "Сегодня было решено 82 задач, в среднем по 350.4 секунды на задачу!."

Комментарии к заданию:

В русском языке окончания слов меняются (1 участник, 2 участника), пока что давайте не обращать на это внимания.

Переменные challenge_result, tasks_total, time_avg можно задать вручную или рассчитать. Например, для challenge_result:

if score_1 > score_2 or score_1 == score_2 and team1_time > team2_time:

result = ‘Победа команды Мастера кода!’

elif score_1 < score_2 or score_1 == score_2 and team1_time < team2_time:

result = ‘Победа команды Волшебники Данных!’

else:

result = ‘Ничья!’

Пример входных данных

team1_num = 5

team2_num = 6

score_1 = 40

score_2 = 42

team1_time = 1552.512

team2_time = 2153.31451

tasks_total = 82

time_avg = 45.2

challenge_result = 'Победа команды Волшебники данных!'
