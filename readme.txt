1.Start cmd
docker-compose up -d --build


2.Pour tester la communication, connectez-vous au conteneur client avec la commande :"
docker exec -it tp5_client_1 /bin/bash
Puis exécutez : curl http://tp5_reverse_proxy_1/db_script.php

3.stop cmd 
docker-compose up -d --build

4.pour ce connecte avec MySQL
docker exec -it tp5_db_1 mysql -u user -p    => apres il vas te demande password: userpassword
