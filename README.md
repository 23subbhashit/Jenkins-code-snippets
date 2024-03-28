# Jenkins-code-snippets
- To check status :
```
sudo service jenkins status

```

- To start :
```
sudo service jenkins start

```
- To stop :
```
sudo service jenkins stop
```

- To get admim password:(After starting jenkins)
```
sudo cat /var/lib/jenkins/secrets/initialAdminPassword
```
- To switch user to jenkins
```
sudo su - jenkins
```
- We will have all our projects in workspace directory.To reach there:
```
cd workspace
ls
```
- To  see build output
```
cd jobs
cd hello(project name)
cd builds
cd 1
cat  log
```
- Java excution Command
```
java -cp minispe-with-dependencies.jar org.example.Main
```
- Run the container
```
docker run -it  --name calculatorspe16 23subbhashit/minispe /bin/bash
```
- To get the images
```
docker images
```
- Start SSH:
```
sudo systemctl start ssh
```
- For executing for docker container
```
docker exec -it 27f9c38bf337 /bin/bash
```
- Start docker compose
```
sudo docker-compose up -d
```
- Stop docker compose
```
docker-compose down
```
