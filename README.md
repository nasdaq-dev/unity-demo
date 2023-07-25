# Unity Demo
Данный репозиторий предназначен для демонстрации базовых возможностей в построении интерактивных 3D пространств с помощью Unity Engine.

# Содержимое проекта

Проект представляет собой одну сцену с демонстрацией базовых механик:
- Движение игрового персонажа (бесплатный StarterAsset)
- Помещение на сцену кастомных изображений
- Реализация аудио проигрывателя
- Реализация видео проигрывателя

# Изображения

Для того, чтобы вставить в сцену собственное изображение, можно воспользоваться следующим методом:
1. Создать 3D-объект, который станет холстом для вашего изображения, и задать ему необходимый размер
2. Создать материал (1), в поле Albedo (2) которого перенести нужное вам изображение
3. Применить материал к объекту-холсту (3)
<img width="800" alt="image" src="https://github.com/nasdaq-dev/unity-demo/assets/24631969/13bb886a-260f-47a7-8564-ca4915489634">

# Видео и аудио проигрыватели

В сцене реализован запуск аудио и видео при приближении игрока к объектам-проигрывателям
1. Для воспроизведения видео на объекте необходимо настроить компонент Video Player
<img width="180" alt="Screenshot 2023-07-25 at 16 21 15" src="https://github.com/nasdaq-dev/unity-demo/assets/24631969/5190cd3c-ad12-4c17-9f68-64bdaa149532">

2. Для воспроизведения аудио необходим компонент Audio Source
<img width="180" alt="Screenshot 2023-07-25 at 16 22 04" src="https://github.com/nasdaq-dev/unity-demo/assets/24631969/a0cd81c1-9772-46a2-9c54-85b1c4fc47d9">

3. Механика воспроизведения при приближении игрока реализована через скрипты VideoOnCollision и AudioOnCollision
4. Для объектов воспроизведения необходимо настроить BoxCollider в режиме IsTrigger, которые будут определять приближение игрока к объектам
<img width="180" alt="Screenshot 2023-07-25 at 16 22 39" src="https://github.com/nasdaq-dev/unity-demo/assets/24631969/891bdc1e-b36c-4582-8be6-5074a9029499">

# Полезные ссылки
1. Playing Video In Unity - https://www.youtube.com/watch?v=KG2aq_CY7pU
2. 3D Sound - https://www.youtube.com/watch?v=md7wCkkv_g4
3. Teleporting Player - https://www.youtube.com/watch?v=I7M8T3qU-_E
4. Interact with Objects - https://www.youtube.com/watch?v=K06lVKiY-sY
