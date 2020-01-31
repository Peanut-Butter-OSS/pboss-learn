# Dockerfiles
We are using the Bitnami Docker images for Moodle. 

Please see their docs at https://hub.docker.com/r/bitnami/moodle/


### To Start for the first time

```
docker-compose up
```

This does a whole bunch of things, including the initial Moodle install, so be patient.

Once this is complete, you can open at http://localhost:8080

### If something goes wrong

If something fails and you need to re-run, you may need to clear the volumes that were created in docker

run the following

```
docker-compose down
docker volume rm dockerfiles_moodle_data
docker volume rm dockerfiles_mariadb_data
```



