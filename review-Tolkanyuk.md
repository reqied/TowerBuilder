# Прикольчики:
- Хорошая идея игры
- Простое управление, не требующее пояснений)
- В принципе код разбит на основные логические классы, но можно, повыделять громоздкие блоки кода в методы, чтобы было проще ориентироваться в том, что делает конкретный большой кусок кода.
# Не прикольчики:
- В этой игре в любом случае довольно частно нужно начинаться заново, поэтому постоянно откатывать весь код и запускать заново напрягает. Было бы лучше сделать рестарт.
- Моментами скорость как-то странно меняется, сильно замедляется, потом внезапно увеличивается
- Возможно стоило вынести в какой-то класс работы с текстом методы showHint, hideHint, showGameOver, printScore, чтобы в классе TowerBuilder остались только функции, отвечающие за логику игры. (а может это и лишнее)