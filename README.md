# InitVerse-Miner
![image](https://github.com/user-attachments/assets/904fe552-9d55-4560-ac13-a5311095f006)

## Hardware Requirements:
◽️ RAM: 8 GB
## faucet
https://faucet-testnet.iniscan.com/

## Commands 
```shell
wget https://github.com/Project-InitVerse/ini-miner/releases/download/v1.0.0/iniminer-linux-x64
```

```shell
chmod +x iniminer-linux-x64
```

```shell
sudo apt update
sudo apt install screen
screen -S initverse
```

```shell
./iniminer-linux-x64 --pool stratum+tcp://<YOUR_WALLET_ADDRESS>.Worker001@pool-core-testnet.inichain.com:32672 --cpu-devices 1 --cpu-devices 2
```

replace YOUR_WALLET_ADD... with your wallet address 
![image](https://github.com/user-attachments/assets/49ed1f3e-5c49-4343-8a43-b86016912fd0)

you can also increase the number of cpu

when you see this, you are mining 
![Uploading image.png…]()
