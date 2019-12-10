# kubia
kubernetes in action book (practice)


```
docker build -t kubia .
docker run --rm --name kubia-container -p 8080:8080 -d kubia
docker stop kubia-container
```

Sample js app running in http://localhost:8080