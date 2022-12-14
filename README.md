# Command list

## General
brew install<br>
brew info<br>
brew update && brew upgrade<br>
history | grep ***[command]***<br>
sudo lsof -i ***[Port Number]***<br>
kill -9 ***[Process ID]***<br>
df -h<br>
cat ***[File Name]***<br>
asciinema rec<br>
asciinema play ***[File]***<br>


## Git
git help<br>
git init<br>
git config<br>
git add ***[File]***<br>
git commit -m ***[Comment]***<br>
git branch -M main<br>
git remove -v <br>
git remote add origin ***[URl]*** <br>
git push -u origin main<br>
git clone ***[URL]***<br>

## Docker
docker system<br>
docker system info<br>
docker system prune<br>
docker login<br>
docker ps<br>
docker image list<br>
docker search ***[Image]***<br>
docker container start<br>
docker container stop<br>
docker inspect<br>
docker exec -it ***[id]*** bash<br>
docker run -dit -p 8080:80 knawata/nginx:1.0<br>
docker comit 2714 knawata/nginx:0.1<br>
docker exec -it ***[id]*** bash<br>
docker push knawata/nginx:0.1<br>
docker pull knawata/nginx:0.1<br>
docker build . -t myfirstdocker:0.0.1<br>
docker tag [tag1] [tag2]<br>
docker port<br>


## Jenkins
brew services start jenkins<br>
brew services restart jenkins<br>
brew services stop jenkins<br>
curl http://127.0.0.1:8080/job/jenkins-cli-hello-world/build\?token\=KaoriApiToken<br>
java -jar jenkins-cli.jar -s http://localhost:8080/ -auth admin:af4a9cc696924daf9b1e215c5dccff42 -webSocket build 'jenkins-cli-hello-world'<br>

## Soner Qube
sonar start<br>
sonar console<br>
sonar stop<br>

## MVN

alias | grep maven
alias | grep mvn | wc -l
gist --login
gist
idea