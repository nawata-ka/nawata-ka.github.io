# Command list

This page is a list of command that I found useful.

To Prasanna
Thank you for letting me know many new commands! I try to add new commands to this page day by day!

## [General](https://www.hostinger.com/tutorials/linux-commands)
brew install<br>
brew info<br>
brew update && brew upgrade<br>
history | grep ***[command]***<br>
chmod ***[Authority type]*** ***[File path]*** [Link](https://www.computerhope.com/unix/uchmod.htm) <br>
sudo lsof -i ***[Port Number]***<br>
kill -9 ***[Process ID]***<br>
df -h<br>
cat ***[File Name]***<br>

## [asciinema](https://asciinema.org/docs/usage)
asciinema rec<br>
asciinema play ***[File]***<br>

## [Git](https://docs.github.com/en/get-started/using-git/about-git)
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

## [Docker](https://docs.docker.com/engine/reference/commandline/cli/)
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
docker run -dit -p ***[Host port]***:***[Container port]*** --mount type=bind,***[Host dir]***,target=***[Container dir]*** ***[Image name]***:***[Version]***<br>
docker commit ***[Target]*** ***[New image]***<br>
docker exec -it ***[ID]*** bash<br>
docker push ***[Image name]***:***[Version]***<br>
docker pull ***[Image name]***:***[Version]***<br>
docker build . -t ***[Image name]***:***[Version]***<br>
docker tag ***[Target]*** ***[New tag]***<br>
docker port<br>

## [Jenkins](https://www.jenkins.io/doc/book/managing/cli/)
brew services start jenkins<br>
brew services restart jenkins<br>
brew services stop jenkins<br>
curl ***[Job URL]***\?token\=***[Api key]***<br>
java -jar jenkins-cli.jar -s http://localhost:8080/ -auth ***[User ID]***:***[Key]*** -webSocket build ***[Job name]***<br>

## [Sonar Qube](https://docs.sonarqube.org/latest/analyzing-source-code/scanners/sonarscanner/)
sonar start<br>
sonar console<br>
sonar stop<br>

## [MVN](https://jenkov.com/tutorials/maven/maven-commands.html)
mvn -v<br>
mvn install<br>
mvn clean<br>
mvn sonar:sonar -Dsonar.login=***[Token]***<br>

## [Gradle](https://docs.gradle.org/current/userguide/command_line_interface.html)
gradle -v<br>
gradle build sonarqube -Dsonar.login=***[Token]***<br>
gradle dependencyCheckAnalyze<br>
gradle build<br>
which gradle<br>