
     git clone https://github.com/MathOliver98/Ac4_SqlAlchemy.git
     cd Ac4_SqlAlchemy/sqlalchemy
     docker pull mysql:5.7
     docker run --name mysql5 -e MYSQL_ROOT_PASSWORD=mudar123 -p 3306:3306 -d mysql:5.7
     docker ps
     docker exec -it (docker_id) /bin/bash
     mysql -uroot -p
     create schema teste;
     
      
    pip install sqlAlchemy
    pip install PyMySQL
    python3 -m examples.basic
    
    python3 -m examples.onetoone

    python3 -m examples.onetomany
