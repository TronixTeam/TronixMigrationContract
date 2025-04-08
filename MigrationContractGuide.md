![image](https://github.com/TronixFoundation/documentation/assets/169593036/f8b7fa90-56c1-42f1-91be-a863f82b36ed)

We have started migrating Tron tokens from the old ERC20 standard to the new TRX20 (also known as TRC20) standard. New Tron tokens serve an important role as native tokens used on the Tron Mainnet. Tron holders should swap their old legacy ERC20 TRX for the new TRC20 using a migration contract.

> This is a 1:1 swap, which means that anyone who holds the ERC20 token will receive the same amount of TRX20 tokens. There is no reduction in the token supply.

## How to migrate TRX tokens from the Ethereum tokens to the Tron Mainnet?

For any remaining TRX ERC20 tokens that have not yet been migrated, we have decided to conduct the migration directly using **migration smart contract**, rather than using a migration user interface that is no longer supported. This makes the migration process for the remaining old Tron ERC20 token holders **simple**.

The migration smart contract, created solely for migration purposes, allows you to migrate your TRX tokens without connecting to any external platforms. The migration smart contract address is **open-source**, meaning the code can be checked by anyone.

Using the migration contract requires users to **pay the gas fee** on the Ethereum Blockchain. This means every user who wants to perform migration needs to have ETH in their wallet. The migration process is similar to any other transaction on the Ethereum Blockchain, and the gas fee is the same as any other transaction. We recommend choosing the average (normal) gas fee to avoid any inconvenience.

## Steps to Start Migration Process

**1. Access Your Wallet:** Check your TRX balance in the list of Ethereum tokens.

**2. Send Tokens:** Send your old ERC20 TRX tokens to the migration smart contract address `0xB46354Aa6eC5f9980B41c6cF91E64F92bE58aE85`. The migration smart contract address begins with `0xB4` and ends with `aE85`. The case of letters does not matter (lower case or upper case).
Choose to send the **entire balance** of TRX tokens. The migration contract will wait for the **full balance** to arrive before initiating the migration process to optimize due to high Ethereum gas fees, partially covered by the Tron Foundation.

**3. Confirmation:** After the transaction is confirmed and broadcasted to the blockchain, the migration process will start, and your wallet will be credited with new TRX tokens. Depending on network usage, it may take 5–30 minutes to process the migration.

## Post-Migration

Your wallet will **automatically recognize** the new Tron Mainnet, and TRX will be credited to your wallet once the migration is complete. The public address of your Tron Mainnet wallet will look different from your Ethereum address where ERC20 TRX was stored, due to different hash algorithms used by Tron Mainnet. However, the migration contract will still know where to send the new migrated tokens. Your new Mainnet TRC20 TRX tokens will be tied to the same private key and seed.

Once the migration is complete, you will have new TRX tokens in your wallet. These tokens can be sold on any exchange that lists Tron, as all exchanges now support the new Tron Mainnet.

Congratulations, you have successfully performed the migration.

![image](https://github.com/user-attachments/assets/37c85aaf-1cd3-4d04-8a9f-9abb6aa6b5cb)

