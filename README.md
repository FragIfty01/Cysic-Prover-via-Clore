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

## Get eth RPC

- Check this guide : https://timemeansalots-organization.gitbook.io/docs.cysic.xyz/tutorial-docs/how-to-run-a-prover-node#get-free-rpc-endpoint-used-by-eth-proof

## 📥 Installation

- Open a screen session
```
screen -S cysic
```

- Install `curl` command
```
apt update && apt install -y curl
```

- Install ETH prover ( Make sure to replace with your reward address including 0x and RPC )

  
```
curl -L https://github.com/cysic-labs/cysic-phase3/releases/download/v1.0.0/setup_prover.sh \
> ~/setup_prover.sh && \
bash ~/setup_prover.sh Your_evm_address(including 0x) Your_RPC_URL
```
## Should look like this after the prover is online 

![Image](https://github.com/user-attachments/assets/ec85ed72-e1b0-4bb3-9fd4-97475f754e79)

## Remarks

- Getting tasks are random
- Active prover number in dashboard is wrong , it should be max 2-3K .
- If you face any issue , head over to DC : https://discord.gg/R7F2pu86 . Use testnet-support channel there. You can ping me as well.




