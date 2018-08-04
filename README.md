# project-skeleton-docker
Skeleton project setup using Docker dev environments


From CLI issue the command to for Docker Compose.

```bash
$ docker-compose up
```

When the 2 docker containers (web and mysql) are completed use this command to get into a terminal of the web container.

```bash
$ docker exec -i -t {container-id} /bin/bash
```

Now attemp to connect to mysql in the mysql container.

```bash
$ mysql -u root -p 127.0.0.1:6603
```

Enter password when prompted. (mypwd)

Witness error.
