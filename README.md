# Solidity: Smart Contracts

The two sample smart contracts that I completed were the Associate Profit Splitter and Deferred Equity Splitter contracts. Each of these contracts has a purpose for automating the delivering of funds to designated recipients.

The Associate Profit Splitter is designed to deposit funds in each of the specified accounts when ether is sent to the smart contract. The Deferred Equity Splitter sends shares to the specified individuals over time. 

Interacting with the Associate Profit Splitter happens as follows. Compile and Deploy the solidity file on remix. www.remix.ethereum.org ![](./resources/Remix0.png)

Afterwards, deploy the contract by enterring three test addresses where you wish to send funds like so and then click transact ![](./resources/Remix1.png)

After that, all interaction takes place through metamask. In order to send funds to the contract, navigate to the Metamask icon and select a test account that is not one of the main accounts about to be paid. ![](./resources/Metamask1.png)

Next, click on the send icon and enter the contract's address. ![](./resources/Metamask2.png)

You can find the contract's address in your Ganache's transaction tab. This contract is located at ![](./resources/Metamask4.png)

The click next and confirm in Metamask. ![](./resources/Metamask3.png)

Now, head on over to your Ganache's account page and see the funds that you've just moved! ![](./resources/Metamask5.png)

Follow the same steps to compile and deploy the Deferred Equity Splitter smart contract on Remix and interact with the smart contract on Remix's UI. ![](./resources/Remix3.png)