This is a [MySQL](https://www.mysql.com) with [phpMyAdmin](https://www.phpmyadmin.net).

## Penggunaan

- build

      docker compose build

- create

      docker compose create

- start

      docker compose start

- one line => Builds, (re)creates, starts, and attaches to containers for a service.

      docker compose up
      docker compose up -d => --detach , -d		Detached mode: Run containers in the background

- cek image

      docker image ls
      atau menggunakan group
      docker image ls | grep nama => docker image ls | grep mysql

- cek container

      docker container ls -a
      atau
      docker compose ps

- stop

      docker compose down

- hapus image

      docker image rm IMAGE ID

- masuk ke dalam container

      docker exec -i -t phpMyAdmin /bin/bash

- inspect ke dalam container

      docker inspect phpMyAdmin

- list file

      ls -al

- masuk ke phpMyAdmin

      http://localhost:9000

- Server

      mysql_db => container_name
      atau
      ip address kalian => misal 192.168.1.18

## Informasi

- Boilerplate ini saya buat menggunakan MySQL + phpMyAdmin

## Donasi

- jika kalian suka dengan projek saya dan ingin support saya, bisa donasi via transfer
  - Jago/Jago Syariah bank digital 5055-6459-9169
