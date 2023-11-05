# Пр 5

Вариант 11: Мебель.

## Инструкция по запуску

Убедитесь в наличии на вашем устройстве [JDK](https://www.oracle.com/java/technologies/downloads/#jdk17-windows)

```
git clone https://github.com/infern397/RKIS-5.git
cd RKIS-5
psql -U postgres -h localhost -f furniture_bd.sql
mvnw package
java -jar target/fourth-1.0.jar
```

_Для сборки необходим [Maven](https://maven.apache.org/download.cgi)_
