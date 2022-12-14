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
docker container ***[ID]*** start<br>
docker container ***[ID]*** stop<br>
docker inspect<br>
docker exec -it ***[ID]*** bash<br>
docker run -dit -p 8080:80 ***[Image name]***:***[Version]***<br>
docker comit ***[Target]*** ***[New image]***<br>
docker exec -it ***[ID]*** bash<br>
docker push ***[Image name]***:***[Version]***<br>
docker pull ***[Image name]***:***[Version]***<br>
docker build . -t ***[Image name]***:***[Version]***<br>
docker tag ***[Target]*** ***[New tag]***<br>
docker port<br>


## Jenkins
brew services start jenkins<br>
brew services restart jenkins<br>
brew services stop jenkins<br>
curl ***[Job URL]***\?token\=***[Api key]***<br>
java -jar jenkins-cli.jar -s http://localhost:8080/ -auth ***[User ID]***:***[Key]*** -webSocket build ***[Job name]***<br>

## Soner Qube
sonar start<br>
sonar console<br>
sonar stop<br>

## MVN

alias | grep maven
alias | grep mvn | wc -l
gist --login
gist
