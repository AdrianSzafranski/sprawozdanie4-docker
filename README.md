# Zadanie2

Podanie poleceń:<br />
a) uruchamiających Stack: ```sudo docker compose up -d```, gdzie  ```-d``` to działanie w tle<br />
![polecenie1](https://github.com/AdrianSzafranski/sprawozdanie4-docker/blob/main/ssy/polecenie1.png)<br />
b) uruchamiających PhpMyAdmin: ```sudo docker compose up -d phpmyadmin```<br />
![polecenie2](https://github.com/AdrianSzafranski/sprawozdanie4-docker/blob/main/ssy/polecenie2.png)<br />
c) tworzących testową bazę ```docker exec <nazwa-kontenera> mysql --execute="CREATE DATABASE <nazwa-bazy-danych>" --user=<uzytkownik> --password=<haslo>```<br />
![polecenie3_1](https://github.com/AdrianSzafranski/sprawozdanie4-docker/blob/main/ssy/polecenie3_1.png)<br />
![polecenie3_2](https://github.com/AdrianSzafranski/sprawozdanie4-docker/blob/main/ssy/polecenie3_2.png)<br />

Wygenerowanie pliku, ilustrującego strukturę projektu komendą ```docker container run --rm -it --name mgraph -v $(pwd):/input pmsipilot/docker-compose-viz render -m image docker-compose.yml```:<br />
![docker_compose.png](https://github.com/AdrianSzafranski/sprawozdanie4-docker/blob/main/docker-compose.png)<br />
