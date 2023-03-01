# Лабораторная работа 2
Необходимо написать простое приложение с использованием контейнеризации
# Run

git clone https://github.com/anastasiavalevich/lab2.git

docker build . -t laba2

docker run -ti -p 80:80 laba2
