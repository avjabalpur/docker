# docker help full command 
>> Start the docker service "sudo service docker start/stop/restart"

>> Build docker "docker build [OPTIONS] PATH | URL | -"

>> Checking the running container "docker ps"

>> Remove the running container "docker rm $(docker ps -a -q)"

>> Checking the running images "docker images"

>> Remove the running images "docker rmi $(docker images -q)"

>> Grep the process "ps -ax | grep processname"

>> Kill the process "sudo killall processname"

>> Check the open network "netstat -a | grep ':http'"

>> check the tree structure of the docker container "sudo docker exec  -it <container-id> /bin/sh"
