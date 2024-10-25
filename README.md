# recsys_hw

Репозиторий с домашним заданием по рекомендательным системам

В ноутбуке implicit_scores.ipynb рассчитываются скоры с помощью библиотеки **implicit** (https://benfred.github.io/implicit/), а именно:

- AlternatingLeastSquares
- Bayesian Personalized Ranking
- Logistic Matrix Factorization

В ноутбуке surprise_scores.ipynb рассчитываются скоры с помощью библиотеки **surprise** (https://surprise.readthedocs.io/en/stable/), а именно:

- Singular Value Decompostion
- User-based kNN
- Item-based kNN

Плюс посчитал отдельно базовые штуки аля кол-во просмотренных фильмов, средний рейтинг фильма, любимые жанры юзера

В ноутбуке final.ipynb с помощью этих скоров строятся разные кэтбусты, чтобы получить разные предсказания

В этом же порядке их и стоит прогонять (на ваш страх и риск)

Плюс пытался в трансформеры с помощью библиотеки **transformers** от Microsoft, но слишком много дедлайнов и работы и я забил :(
Хотелось 10, но уж 9 не подавимся!

Ссылка на скоры:
https://drive.google.com/file/d/14VclA7VIkjlRMv5AZeb5oeDX9XljOZS_/view?usp=sharing
