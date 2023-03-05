# Opencast Uploader


## Установка

Клонируйте репозиторий к себе на устройство:
```
git clone git@github.com:monticola145/Opencast_Files_Uploader.git
```

Перейдите в папку с программой:
```
cd opencast_uploader
```

Разверните виртуальное окружение и установите зависимости
```
python -m venv venv && source venv/Scripts/activate && pip install -r requirements.txt
```
Программа готова к запуску

## Команды

Команда для ознакомления с программой:
```
python video_uploader.py --help
```

- Пример использования:
```
python video_uploader.py 504 cam228 2022 10 18 10 30 D://...//file.mp4 D://...//file2.mp4
```
Где 504 - номер аудитории; cam228 - название камеры; 2022/10/18/10/30 - год/месяц/день/час/минута начала; D:/.../file.mp4 - путь к загружаемому файлу №1; D://...//file.mp4 - путь к загружаемому файлу №2 (опционально)

(Юзеры Виндовса, обратите внимание на использование // вместо \ при указании пути к файлу)

- Ожидаемый вывод:

Программа вернёт код ответа сервера. Если в терминале высвечивается "201" -- программа успешно запостила эвент и загрузила файл

Найдите эвент в опенкасте по названию: 
```
504_cam228_2022.10.18_10:30
```

### Автор:

[Monticola]
Git - https://github.com/monticola
Email - ```jandiev2001@yandex.ru```


# Opencast Uploader


## Installation.

Clone the repository to your device:
```
git clone git@github.com:monticola145/Opencast_Files_Uploader.git
```

Navigate to the folder with the program:
```
cd opencast_uploader
```

Deploy the virtual environment and install the dependencies
```
python -m venv venv && source venv/Scripts/activate && pip install -r requirements.txt
```
The program is now ready to run

## Commands

A command to learn the program:
```
python video_uploader.py --help
```

- Example usage:
```
python video_uploader.py 504 cam228 2022 10 18 10 30 D://...//file.mp4 D://...//file2.mp4
```
Where 504 - audience number; cam228 - camera name; 2022/10/18/10/30 - year/month/day/hour/minute start; D:/.../file.mp4 - path to uploaded file #1; D://...//file.mp4 - path to uploaded file #2 (optional)

(Windows users, pay attention to using // instead of \ when specifying the file path)

- Expected output:

The program will return the server response code. If terminal shows "201" - program has successfully posted event and uploaded file

Find event in Opencast by name: 
```
504_cam228_2022.10.18_10:30
```


### Author:

[Monticola]
Git - https://github.com/monticola
Email - ``jandiev2001@yandex.ru``
