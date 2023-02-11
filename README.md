# 3.1Docker
1. через PuTTY открыть выиртуальную машину
2. в терминале PuTTY залогиниться
3. склонировать туда свой проект с git-сервера: git clone *name of repository*
4. перейти в директорию склонированного проекта: cd *name of repository*
5. скопировать в свой терминал и запустить конейнер в терминале PuTTY: *docker container run --first postgres*
6. запустить в терминале Docker: *docker-compose up*
7. локально в своей IDEA заменить **loclahost** на ip виртуальной машины:
*spring.datasource.url=jdbc:postgresql://89.223.70.43:5432/db*
8. тамже, локально запустить jar-ник

Запрос в POSTMAN:

]![POSTMAN GET request](https://user-images.githubusercontent.com/106382299/218275263-8482690e-bf5b-46e0-bd41-2b5002183514.png)
