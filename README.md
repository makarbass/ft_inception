# Туториал по проекту ft_inception

### Цели данного проекта:
- Расширение знаний в области системного администрирования с помощью Docker
- Виртуализация нескольких образов Docker на виртуальной машине
## Обязательная часть
### Теоретический материал простым языком:
1. [A beginner’s guide to Docker — how to create your first Docker application](https://www.freecodecamp.org/news/a-beginners-guide-to-docker-how-to-create-your-first-docker-application-cc03de9b639f) 
2. [How to Deploy MariaDB Server to a Docker Container](https://severalnines.com/blog/how-deploy-mariadb-server-docker-container)
3. [Руководство по Docker Compose для начинающих](https://habr.com/ru/company/ruvds/blog/450312/)
4. [Nginx, Php-Fpm и что это вообще?](https://perfect-inc.com/journal/nginx-php-fpm-i-chto-eto-voobshche/)
5. [MariaDB](https://ru.wikipedia.org/wiki/MariaDB)
6. [**Установка WordPress с помощью Docker Compose**](https://www.digitalocean.com/community/tutorials/how-to-install-wordpress-with-docker-compose-ru)
7. [Running MariaDB in a Docker Container](https://quebit.com/askquebit/quebit-products/running-mariadb-in-a-docker-container/#:~:text=Now%20that%20my,the%20bash%20shell%3A)
>Последняя статья пригодится во время сдачи проекта при проверке базы данных (см. [Checklist](https://github.com/mharriso/school21-checklists/blob/master/ng_3_inception.pdf))
### Руководство по реализации <img height="20" width="20" src="https://unpkg.com/simple-icons@v6/icons/virtualbox.svg" /> VirualBox - <img height="20" width="20" src="https://unpkg.com/simple-icons@v6/icons/debian.svg" /> Debian 10.12 (buster), <img height="20" width="20" src="https://unpkg.com/simple-icons@v6/icons/linuxcontainers.svg" /> Containers - debian:buster:
1. [Как установить Debian в VirualBox. Полная пошаговая инструкция](https://poznyaev.ru/debian-v-virualbox/)
>Скачать образ debian-10.12.0-amd64-xfce-CD-1.iso можно [здесь](https://cdimage.debian.org/cdimage/archive/10.12.0/amd64/iso-cd/debian-10.12.0-amd64-xfce-CD-1.iso)
<details>
<summary>Если вы работаете на школьных <img height="20" width="20" src="https://unpkg.com/simple-icons@v6/icons/apple.svg" /> Mac, не забудьте выбрать папку goinfre</summary>

![](https://user-images.githubusercontent.com/90090114/169686068-c054eef9-8d84-4684-84d1-2f4d92a590eb.png)
</details>

>Чтобы увеличить размер окна виртуальной машины в MacOS, либо нажмите на окно виртуальной машины, затем на панели основной ОС в верхей левой части экрана нажмите View->Virtual Screen 1->Scale to 200% (autoscaled output), либо измените разрешение экрана в настройках виртуальной машины (возможно, появление торможения виртуальной машины)


## Добавляем пользователя в sudo
### Заходим под superuser
```
su
```
### Устанавливаем sudo
```
apt-get install sudo
```
### Добавляем пользователя в sudo 
```
/sbin/adduser username sudo
```
Настройки применятся после перезагрузки

## Устанавливаем vim
```
sudo apt install vim
```

## Устанавливаем make
```
apt-get install build-essential
```

## Устанавливаем git
```
sudo apt install git
```

