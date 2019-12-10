# kubia
kubernetes in action book (practice)


```
docker build -t nixon89/kubia .
docker push nixon89/kubia
docker run --rm --name kubia-container -p 8080:8080 -d nixon89/kubia
docker stop kubia-container
```

Sample js app running in http://localhost:8080