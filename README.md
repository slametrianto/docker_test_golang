# belajar-docker

bikin file dockerfile
 - touch Dockerfile
 
 - docker build --tag app-golang:1.0 .
 - docker images
 - docker container create --name app1 -p 8080:8080 app-golang:1.0
 - docker container ls -a
 - docker images
 - docker container ls --all
 - docker container start app1
 - docker container ls
 
 hapus container 
 docker container rm 1b04bc868f76 =>nama containernya
 
 hapus images
 docker rmi db26680a7319
 
 test docker dilocal : 
  http://192.168.100.15:8080/

