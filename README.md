# wordpress-site-with-docker-compose
WordPress is the most popular website content management system (CMS). It’s a PHP application that requires a MySQL or MariaDB database connection. Consequently, there are two containers to deploy with Docker:

WordPress application container – Serves WordPress using PHP and the Apache web server.

MySQL database container – Runs the database server that the WordPress container will connect to.

To launch the containers:
```
docker-compose up -d
```

To delete all the containers with volumes:
```
docker-compose down -v
```
