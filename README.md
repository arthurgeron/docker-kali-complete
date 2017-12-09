
# Kali Complete
Docker image with all the kali linux tools included.   
Docker Hub link: https://hub.docker.com/r/arthurgeron/kali-complete/

### Requirements
[Docker](https://docs.docker.com/engine/installation/)

### Tags
Note: all of the images includes aircrack-ng    
``arthurgeron/kali-linux:latest `` - Contains a kali-linux dist with all tools included (9.0 GB)   
``arthurgeron/kali-linux:latest `` - Contains a kali-linux dist with the top 10 tools included (3.5 GB)   
``arthurgeron/kali-linux:latest `` - Contains a kali-linux dist with basic tools included (1.5 GB)    

Click [here](https://www.kali.org/news/kali-linux-metapackages/) for more info
### Running
``docker run -it --net="host" --privileged arthurgeron/kali-complete /bin/bash``