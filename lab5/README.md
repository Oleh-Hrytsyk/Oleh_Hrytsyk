# Лабораторна робота №5

##### 1-5. Прочитав про docker-compose, бібліотеку Flask, створив папку my_app та tests і скопіював туди файли.
##### 6. Ініціював середовище для програми та тестів командами 
###### pipenv --python 3.7
###### pipenv install -r requirements.txt
##### та переконався що все працює
##### 7-8. Створив два Dockerfile та Makefile, в якому директиви виконують наступні дії
##### - STATES := app tests змінні яким динамічно присвоюються значення
##### - REPO := tarasshynkler/firstrepos:lab5 репозиторій на Docker Hub
##### - .PHONY: $(STATES) несправжні цілі
##### - run виконує команди
##### - docker-prune очищує ресурси
##### 9. запустив команди sudo make app та sudo make tests, після чого запустив команду sudo make run і відкрив нове вікно терміналу де запустив команду sudo make test-app
##### результати виконання команд
![image alt](img/4.png)
![image alt](img/5.png)
##### сторінки браузера
![image alt](img/1.png)
![image alt](img/2.png)
![image alt](img/3.png)
##### 10-12. зупинив проект, почистив все командою sudo make docker-prune та додав директиви в  makefile
