# Проект по программированию ФиКЛ-2022 "ТГ-бот с кружочками"

Адрес бота: http://t.me/PoseBot_bot

Этот бот обрабатывает видео-сообщения в Телеграме и опознает на них 4 позы: две сидячие (на корточках и на стуле) и три стоячие (Т-поза, поза с вытянутыми вверх руками и поза со свободным расположением рук). Бот работает **только** при присутcтвии одного человека в кадре.

Для работы с ботом нужно просто отправить ему кружочек - бот обработает его (в среднем на 15-секундное видео уходит 20 секунд) и выдает один из следующих ответов:
- 'Не понимаю, что происходит :(' в случае, если произошла какая-то ошибка и видео даже не обрабатывалось;
- 'Вы стоите, как буква Т!!!';
- 'Вы стоите с вытянутыми вверх руками!!!';
- 'Говорят, в ногах правды нет...' - стоячая поза со свободным положением рук;
- 'Вы сидите на корточках!!!';
- 'Вы сидите на стуле!!!';
- 'Что Вы делаете?..' если поза не подходит ни под одно из описаний.
