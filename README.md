
1  apt update -y
    2  docker version
    3  apt install docker.io
    4  docker version
    5  uname
    6  uname -a
    7  docker info
    8  docker images
    9  docker pull httpd
   10  dockers images
   11  docker images
   12  docker pull tomcat
   13  docker images
   14  docker pull mysql
   15  docker images
   16  docker run -it -d -p 82:80  httpd
   17  docker ps
   18  docker exec -it386827bc5bb5 /bin/bash
   19  docker exec -it 386827bc5bb5 /bin/bash
   20  sudo s-
   21  apt install -y
   22  docker version
   23  clear
   24  docker run -it -d -p 83:80 htttpd
   25  docker run -it -d -p 83:80 httpd
   26  docker ps
   27  docker rm -f 386827bc5bb5
   28  docker ps
   29  pwd
   30  cd /
   31  mkdir project1
   32  cd project1
   33  pwd
   34  touch Dockerfile
   35  vi Dockerfile
   36  docker exec -it 18e61ba678d7 /bin/bash
   37  docker ps
   38  docker rm -f 18e61ba678d7
   39  docker ps
   40  docker ps -a
   41  vi Dockerfile
   42  touch index1.html
   43  vi index1.html
   44  ls -l
   45  apt update -y
   46  docker version
   47  docker images
   48  docker run -it -d -p 83:80 httpd
   49  docker ps
   50  pwd
   51  cd /
   52  mkdir project2
   53  cd project2
   54  touch Dockerfile
   55  vi Dockerfile
   56  docker ps
   57  docker exec -it 738d298d8a24 /bin/bash 
   58  docker ps
   59  docker rm  -f 738d298d8a24
   60  docker ps
   61  docker ps -a
   62  vi Dockerfile
   63  touch index1.html
   64  vi index1.html
   65  ls -l
   66  docker build . -t httpd1
   67  docker images
   68  docker run -itd -p 83:80 httpd1:latest
   69  docker ps
   70  docker exec -it 6f73652a280f /bin/bash
   71  vi index1.html
   72  history
   73  cat Dockerfile
   74  cat index1.html
   75  docker ps
   76  docker exec -it 6f73652a280f /bin/bash
   77  docker volume ls
   78  docker volume create simpli-volume
   79  docker volume ls
   80  docker ps
   81  docker rm -f 6f73652a280f
   82  docker run -it -d --mount source=simple-volume,target=/usr/local/apache2/htdocs -p 83:80 httpd1
   83  docker ps
   84  docker exec -it d3aff392d4ec  /bin/bash
   85  docker run -it -d --mount source=simple-volume,target=/usr/local/apache2/htdocs -p 84:80 httpd1
   86  docker ps
   87  docker exec -it 965cece08593 /bin/bash
   88  history
