# Video_Player
![image](https://user-images.githubusercontent.com/39197265/186574789-0b9dbd75-5b49-4c44-8a05-6e7e7dc7dda6.png)
## Демо:
 Демо можно посмотреть [тут](https://alonerd.github.io/Video_Player/)
## Как учтановть
1. Скачай программу себе на компьютер.
```
git clone https://github.com/AloneRD/Video_Player.git
```
2. Создай виртуальное окружение для проекта. Установи зависимости.
```
pip install -r requirements.txt
```
3.Ввести адрес видео в файле index.html.
```
<script type="text/javascript">
    createPlayer({
      elementId: 'player',
      src: 'Тут ссылка на видео',
    });
  </script>
```
4.Запустить скрипт.
```
python render_page.py
```
