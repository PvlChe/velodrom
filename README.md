Портал по оказанию услуг по прайсу

    Админ может создавать новых юзеров (работников), задавать рабочие дни,
    видеть статусы заказов, оплачены-ли. Если оплачен то переводить в статус
    в работе к работникам. 

    Работники могут просматривать лист работ по дням (неделям) с адресами на
    карте беларуси. Построение маршрута. По выполнению работ подтверждает 
    готовность вместе с фото. Фото проверяются админом и отправляются заказчику
    после проверки.

    Заказчики могут регистрироваться и видеть статус работ, историю работ,
    добавлять по желанию даты выполнения работ. Существуют различные
    пакеты по оказанию услуг.

    Сайт аналог http://www.gravecare.ie/ только с онлайн сопровождением 
    (проверка статуса заказа в личном кабинете). 

    Цена без привязки дня дешевле, так как можно оптимизировать маршруты и 
    сделать поездку по РБ и выполнение работ когда есть рядом заказы.

Command line instructions
You can also upload existing files from your computer using the instructions below.
    
    Git global setup
    git config --global user.name "Vitaly Tolstik"
    git config --global user.email "vital.tol90@gmail.com"

Create a new repository
    
    git clone https://gitlab.com/VitalyTolstik/test-project.git
    cd test-git-project
    touch README.md
    git add README.md
    git commit -m "add README"
    git push -u origin master

Push an existing folder
    
    cd existing_folder
    git init
    git remote add origin https://gitlab.com/VitalyTolstik/test-project.git
    git add .
    git commit -m "Initial commit"
    git push -u origin master

Push an existing Git repository
    
    cd existing_repo
    git remote rename origin old-origin
    git remote add origin https://gitlab.com/VitalyTolstik/test-project.git
    git push -u origin --all
    git push -u origin --tags
