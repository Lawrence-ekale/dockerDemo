# dockerDemo
This is a simple SpringBoot application dockerized.
That is creating a dockerFile and populating with target jar creating in maven install.
With the jar present and docker installed I created a docker image by "docker build -t [name of the jar] ."
I successfuly built that is docker reaching the target jar file and creating your image then you can check to see 
if listed by "docker image ls". Then runing it you simply run "docker run -p 9090:8084  [name of the jar file with extension]"
Port 8084 is what I exposed in the dockerfile and port 9090 is where the container runs.
