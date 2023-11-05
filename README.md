# Пр 5

Вариант 11: Мебель.

## Инструкция по запуску

Убедитесь в наличии на вашем устройстве [JDK](https://www.oracle.com/java/technologies/downloads/#jdk17-windows)

```
git clone https://github.com/infern397/RKIS-5.git
cd RKIS-5
psql -U postgres -h localhost -f furniture_bd.sql
sh mvnw package
java -jar target/mvc-0.0.1-SNAPSHOT.jar
```
Открываем в браузере [главную страницу] http://127.0.0.1:8080
_Для сборки необходим [Maven](https://maven.apache.org/download.cgi)_
