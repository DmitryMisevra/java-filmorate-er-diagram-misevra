# Это ER-диаграмма для проекта Java-Filmorate
![](https://github.com/DmitryMisevra/java-filmorate-er-diagram-misevra/blob/593cc1facbcbdfb82eb9dbbb413bfd17cfdb2a0d/er_diagram_misevra.png)
**В схеме отражены следующие сущности:**
1. _user_. Отвечает за хранение данных пользователей
2. _film_. Отвечает за хранение данных о фильме
3. _genre_. Хранит список жанров и отражен в film
4. _rating_. Хранит список рейтингов фильма и также отражен в film
5. _film-likes_. Хранит все лайки для всех фильмов
6. _friendship_. хранит данные о дружеских связях между пользователями
7. _friendship_status_. Хранит статусы дружбы между пользователями и отражен в таблице friendship
