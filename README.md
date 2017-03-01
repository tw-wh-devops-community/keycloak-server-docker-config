## Requirement
### Tools

docker-machine

docker-compose

## Local development

docker-machine create -d virtualbox --virtualbox-memory 4096 --virtualbox-cpu-count 4 default
 
eval $(docker-machine env default)

docker-compose up

## usage
1. docker-machine ls

		display your virtual machine and remember your ip address.
2. Then navigate to [http://\<**virtual machine ip address**\>:8081](http://\<**virtual machine ip address**\>:8081) to see the application in action.
