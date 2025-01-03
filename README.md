# Программирование Систем Искусственного Интеллекта

Програмимрование систем искусственного интеллекта (ПСИИ) суть дисциплина,
преподаваемая в РТУ МИРЭА.

В этом репозитории можно найти Jupyter-тетради составленные на основе тех, что
даются в курсе ПСИИ. Содержание тетрадей сильно отличается
и в значительной степени выполнены в соответствии с видением автора.

## Содержание

Предметом курса в основном является работа с алгоритмами машинного обучения для
изображений (свёрточные нейронные сети, обнаружение объектов и прочее).

Ниже можно видеть соответствие названия тетради с темой, которая в ней
разобрана.

1. featuregen — признаки и дескрипторы с OpenCV;
2. dimred — алгоритмы понижения размерности с Scikit-Learn;
3. featfilter — фильтрации признаков на основе дисперсии и корреляции;
4. crossval — перекрёстная валидация с Scikit-Learn;
5. bestmods — алгоритмы отбора моделей с Scikit-Learn.

В каждой тетради довольно общо поясняется, что и зачем было сделано.

## Пользование

Чтобы попробовать выполнить код самостоятельно, просто клонируйте данный
репозиторий с помощью Git CLI следующим образом:

```shell
git clone https://github.com/mkashirin/pais
```

Создайте виртуальное окружение на основе файла «pyproject.toml». Вот пример с
использованием пакетного менеджера UV (учитывая, что Вы находитесь в
рабочей директории с проектом):

```shell
uv venv .venv
source .venv/bin/activate
uv pip install .
```

Теперь запустите Jupyter Lab, чтобы начать работу:

```shell
jupyter lab
```

Либо откройте проект в VSCode:
```shell
code .
```

Также Вы можете добавить свои изображения в директорию «images», чтобы
применить к ним представленные алгоритмы.
