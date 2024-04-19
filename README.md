# Docker-Compose: docker-wordpress-mysql
Wordpress with MYSQL Database

# Description
This Docker Compose configuration defines a multi-container environment for deploying a WordPress application with a MySQL database backend. The db service uses the latest MySQL image and sets up the necessary environment variables for the database, including the root password, a user account (user), and a database (employee). The wordpress service depends on db and uses the latest WordPress image, mapping port 8000 on the host to port 80 in the container. It also sets up environment variables for the WordPress database connection, pointing to the db service at port 3306, using the same database (employee), user, and password (user). This configuration ensures that the WordPress application can communicate with the MySQL database to function correctly.

# Running docker-compose.yml 
![Screenshot 2024-04-19 130733](https://github.com/A1iw4r3/docker-wordpress-mysql/assets/124252109/84dff503-6816-4e83-9305-1d663b427655)

# Login Pannel
![Screenshot 2024-04-19 130757](https://github.com/A1iw4r3/docker-wordpress-mysql/assets/124252109/d9769392-e23e-4e79-87e3-e865d59b262d)

# Home Page
![Screenshot 2024-04-19 130650](https://github.com/A1iw4r3/docker-wordpress-mysql/assets/124252109/5b9a700f-8434-4733-a0fc-792a4beedadb)
