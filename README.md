# DockerDemos
<h3>This repository contains all the demo projects I made using docker to fully understand and master this eveolving technology.</h3>

<h3>
Projects:
</h3>
<h4>
1) Dockerizing networks-starting-setup using networks:<br>
  Commands:<br>
  1) docker network create |network name| <br>
  Initially creating the container for the server<br>
  2) docker build -t |image name| . <br>
  3) docker run --name <container name> --network <network name> --rm -d -p 3000:3000 <container name> <br> ( You can add bind mounts , anonymous or named volumes to it)
  
  Container for the database - (mongodb)
  1) docker run --rm -d --network | network name (common for shared containers) | --name <container name> mongo <br>
 (It's preferred to containerize the database first , you can even expose the ports if u want to do)
  </h4>
