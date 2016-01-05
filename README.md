# Hortonworks Data Platform

## Automated Install with Ambari 

* Launch the container running Ambari Server and Ambari Agent
```
docker run  -p 8080:8080 --rm -ti --privileged --name hdp -h hdp torusware/hdp
```
* Open your browser and go to http://localhost:8080
* Access a running container through ssh
```
$ sshpass -p 'torus' ssh root@<container IP>
```
