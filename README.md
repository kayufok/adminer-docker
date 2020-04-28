# adminer-docker
adminer-docker


## Create docker container using image "adminer"
```bat
sudo docker run -d --name adminer-container --network nginx-net adminer
```

### Kill and Deploy command in sequency
```bat
sudo docker container stop adminer-container
sudo docker container rm adminer-container
sudo docker run -d --name adminer-container --network nginx-net adminer
```