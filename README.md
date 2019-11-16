# DockerProjer1
Installation Wordpress via Docker 
Le but de ce projet est de faire fonctionner le cms Wordpress sous docker avec une
vm Ubuntu. Pour se faire, nous allons donc créer un premier container pour pour
installer WordPress, un autre pour sa base de données et enfin un dernier pour
PhpMyAdmin. Il nous sera également possible de créer un autre container pour
installer Portainer qui est un petit utilitaire graphique Docker.
Il va donc falloir lier les deux containers (base de données et le cms) afin de faire
fonctionner correctement WordPress.
Il nous est également possible d’installer Nginx et faire une redirection
(« 127.0.0.1 » ou « localhost » vers « wordpress-docker.co ») par exemple.
Deux méthodes sont possibles pour créer des container (ligne de commande ou
docker-compose). Un peu plus dans cette procédure, je montre comment utiliser
docker-compose.
