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
