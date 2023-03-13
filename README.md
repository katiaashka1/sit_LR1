# Устанавливаем Docker

Docker Desktop установливаем на ubuntu в соответствии с инструкцией: https://docs.docker.com/desktop/install/ubuntu/  
1. Настраиваем репозиторий пакетов Docker.  
2. Загружаем последний пакет DEB.  
3. Устанавливаем пакет с помощью apt.  

![Nginx](https://user-images.githubusercontent.com/59118314/224723568-5fe6a978-9299-4777-85b2-bb2af2bdd2b6.png)

# Создание Dockerfile 

![vim Docker](https://user-images.githubusercontent.com/59118314/224725243-c2d8f509-b1c6-42c2-8089-555ecbe36040.png)



# Создание образа с Nginx  


# Запуск базового веб-сервера

`$ docker run -it --rm -d -p 8080:80 --name web nginx`
