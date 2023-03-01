# Лабораторная работа 2
Необходимо написать простое приложение с использованием контейнеризации
# Run

git clone https://github.com/anastasiavalevich/lab2

docker build . -t laba2

docker run -ti -p 80:80 isis2
