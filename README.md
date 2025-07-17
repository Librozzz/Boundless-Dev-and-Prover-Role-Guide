# Boundless-Dev-and-Prover-Role-Guide
This guide shows how to claim the Dev and Prover role in the Boundless Guild
You can do this in your PC with just $1. Note this does not grants you any Berry of Tokens. It's just to claim the Dev & Prover Roles in Boundless Server.

Create a burner wallet and send $0.01 worth of USDC and $1.1 worth of Base ETH. (We are creating a burner wallet because we need to provide the private keys in the command later. Its always safe to use burner rather than main wallet.


> 1. Follow these steps
>    
Go to https://guild.xyz/boundless-xyz and log in to guild.

Now go to the Guild setting and link the burner wallet address in the Guild. Do not remove your main EVM, simply add another address in the Guild.

Now go to https://www.alchemy.com, Sign in using google and create an Alchemy Base Mainnet RPC URL

You can get the Base Mainnet RPC URL by creating a new app for Base Mainnet.

After you are done, copy the Network URL you just created. It should look something like this https://base-mainnet.g.alchemy.com/(YOUR API KEYS)

> 2. Installation Steps
>    
a. Connect to your server ( skip step (a) if you are doing this on your PC or Laptop locally) - ssh root@your-server-ip

Install dependencies on Ubuntu using WSL

sudo apt update && sudo apt install -y curl git

Download and run the script

bash <(curl -s https://raw.githubusercontent.com/morsyxbt/boundless-prover-dev/main/boundless-prover.sh)

Once the process is completed, it will ask for the following"

Alchemy Base RPC URL (which you just created on Alchemy)

Your wallet private (you can copy and paste from wallet, the input will be hidden)

After that it will ask you to select the role and show the amount required for each role. Select role: 1, 2, or click 3 if you need both

It will check your wallet balance and start processing. It will take some time.

After everything is successfully processed, you will see this message : GUILD QUEST COMPLETED! 🎉 Welcome to the Boundless Network!

You can go back to the Guild and get the roles then.

Hope this helps.
