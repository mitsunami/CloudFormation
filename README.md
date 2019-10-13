# CloudFormation
Deploy a high-availability web app using CloudFormation 

## How to build and deploy
```
./create.sh projinfra network.yml network-paramters.json 
./create.sh projserver server.yml server-paramters.json 
```

## How to update
```
./update.sh projinfra network.yml network-paramters.json 
./update.sh projserver server.yml server-paramters.json 
```

## How to delete
```
./destroy.sh projinfra
./destroy.sh projserver
```

