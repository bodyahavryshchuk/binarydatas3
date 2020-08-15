
Это REST-сервис для хранения бинарных данных на облачном сервисе S3

Для запуска:

1 Клонируйте репозиторий
```java
git clone https://github.com/bodyahavryshchuk/binarydatas3.git
```
2 Установите зависимости
```java
pip install -r requirements.txt
```
3 Запуститe сервер
```java
python -m flask run
```

Приложение:

1 Метод GET - get_data
```java
 http://127.0.0.1:5000/api/v1/data
```
2 Метод PUT - put_data
```java
 http://127.0.0.1:5000/api/v1/add-data/<key>/<value>
```
  где key - ключ, value - значение
  

