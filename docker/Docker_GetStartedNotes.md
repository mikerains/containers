& "C:\Program Files\Docker\Docker\Resources\bin\docker-machine.exe" env myvm1 | Invoke-Exp
ression

docker-machine ssh myvm2 "docker swarm join --token SWMTKN-1-58udedfi4mbxtwsvgzor31vp7h3cqw0ko30j48tv6wsfzel09g-6qb4fez7l4gb02b1wu1wkabof 192.168.0.21"


add-content $PROFILE "Set-PSReadlineOption -BellStyle None"







https://docs.docker.com/get-started/part2/#apppy
says:
Accessing the name of the host when inside a container retrieves the container ID, which is like the process ID for a running executable.


https://docs.docker.com/get-started/part3/#run-your-new-load-balanced-app
says:
 "A single container running in a service is called a task. "




https://docs.docker.com/get-started/part4/#introduction
says:
the machines in a swarm can be physical or virtual. After joining a swarm, they are referred to as nodes.


