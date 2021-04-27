# Simple_Chat_Docker #



############ A- Project Details ####################

1- I used a youtube toutrial to implement the python code for the server.py and client.py:

https://www.youtube.com/watch?v=iXL-akeLTA4

2- I made a Dockerfile for each of the server and client and build an image for each and uploaded them to DockerHub
Link to DockerHub That Contain the images : 

https://hub.docker.com/repository/docker/mohamed1195/warm_up_assignment/general

############ B- Instruction to run the app #########

1- Download docker-compose.yml file

2- run the following command in directory that contain the yml file

$ docker-compose run client

enter USERNAME for your client

each time you want to add client repreat step 2 you can arbitary number of clients

if any conflicts for ip happend end process and use the following command to close all container

$ docker stop $(docker ps -a -q)

and repeat step 2 again
