# Self-study Hyperledger

This repository is dedicated to the study of Hyperledger technologies. It contains useful resources and samples for self-study.

## Resources

- [**Hyperledger Study Guide on HackMD**](https://hackmd.io/@cnsrl/H1wHzaQk_): This is a sample project demonstrating the use of Hyperledger Fabric.

## Hyperledger Fabric Sample
### Some Useful Command
#### Create Network
```
#Create network with creating channel
./network.sh up crerateChannel

#Create network with ca 
./network.sh up -ca
```
#### Clear Previous Running Container
```
./network.sh down
```

## Smart Contact Location
```
fabric-samples/asset-transfer-basic/chaincode-{Language}
```