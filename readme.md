Hello, this repo is a boilerplate for fast development with containers mysql, phpmyadmin, wordpress!

You can run this with:
'''
docker-compose build && docker-compose up -d
'''

Wait until download complete and enjoy your fast development environment

MySQL credentials:
user: root
password: root

Ports:
MySQL: 3306
WordPress: 8081
PhpMyAdmin: 8090

You can edit the code of your wordpress site from dir wordpress.
Folder db is a backup of your mysql image.
(The folders are empty since you build and run the docker-compose commands.)