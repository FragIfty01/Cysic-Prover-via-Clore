# Cysic Prover Walkthrough

## 💻 System Requirements

| Requirement                         | Details                                                     |
|-------------------------------------|-------------------------------------------------------------|
| **CPU**                             | `8 cores`                                                   |
| **RAM**                             | 32 GB                                                       |
| **GPUs**                            | 3090 , 4090                                                 |
| **Disk/Storage**                    | 50-100 GB                                                   |
| **Operating System**                | Ubuntu 24                                                   |

## Rent GPU

- Check my previous GPU setup guide here : [Clore setup guide ](https://github.com/FragIfty01/Gensyn-via-Clore-ai)

## Sign up 

- Use any evm wallet 
- Import that same evm wallet to Keplr 
- Join : https://app.cysic.xyz/dashboard 
- Code : 528a1
- You can complete the social tasks as well

## 📥 Installation

- Open a screen session
```
screen -S cysic
```

- Install `curl` command
```
apt update && apt install -y curl
```

- Install ETH prover ( Make sure to replace with your reward address and RPC )

  
```
curl -L https://github.com/cysic-labs/cysic-phase3/releases/download/v1.0.0/setup_prover.sh \
> ~/setup_prover.sh && \
bash ~/setup_prover.sh 0x-YourRewardAddressHere Your_RPC_URL
```
## Should look like this after the prover is online 

![Image](https://github.com/user-attachments/assets/ec85ed72-e1b0-4bb3-9fd4-97475f754e79)

## Remarks

- Getting tasks are random
- Prover number in dashboard is wrong , it should be only around 2-3K .
- If you face any issue , head over to DC : https://discord.gg/R7F2pu86 . Use testnet-support channel there. You can ping me as well.




