# Nornickel
NornickelHack


__Решение кейса "Флотомашина времени"__

__Команда DataDrive__


__Схема решения:__  для каждой из 6 флотомашин делается прогноз минимального и максимального значения диапазонов для каждого металла, по сетке из 9 параметров с 5 фолдами кроссвалидации (GridSearchCV) выбирается лучшая модель (Catboost) для текущих данных
