# BDB2022 Week 4 Exercise

For Week 4, you will be developing smart contracts using REMIX IDE and Rinkeby Testing network. Week 4 will consist of one project you can work on. This project will give you a kickstart to make your smart contract upgradable when you need to.

## Activity

Week 3 will compose of one activity in total.

1.  **Proxy contract with Eternal Storage Activity** 
  
This activity will teach you how you make a simple logic contract upgradable. An upgradeable contract allows you to update its logic along the run. This is especially useful if you plan on adding new functions or fixing bugs whenever they arrises.
  
### Setup

You are given an initial file that you can initially work on and at the end of the project, you will arrive at a working code. After that, you need to deploy it to Rinkeby Explorer so that we can check your work.

Clone or download zip this repository to your local device to get started.

The initial files are located inside the contract folder. Inside the folder you can find two files namely, EternalStorageProxy.sol and LogicContract.sol. The EternalStorageProxy contract will hold the source code for the proxy contract. There is no need to edit this contract as this is a working code. And the LogicContract will house the source code for our simple functions. And these functions will be called through the EternalStorageProxy contract.

You can use [REMIXD](https://remix-ide.readthedocs.io/en/latest/remixd.html), a popular extension of the REMIX IDE where in you can connect directly to your local storage and start coding. Or if you are not confident, you can manually copy-paste the smart contract code to REMIX IDE, then paste it back to your local repository whenever you are done coding. This way you can still commit your changes to GitHub and have them checked by the mentors.

## Proxy contract with Eternal Storage Activity

##### /contract/EternalStorageProxy.sol
##### /contract/LogicContract.sol

#### Grading Metrics

The following are the Grading Metrics on how well the student was able to complete the project. Each item correspond to a point/s which perfect points is 10.

1. Complete the Logic contract from the video (3 points)
2. Deploy the EternalStorageProxy and LogicContract to Rinkeby (2 points)
3. A published smart contract code in Rinkeby Explorer (1 point)
4. EternalStorageProxy must point to the address of your LogicContract (1 point)
5. "Is this a proxy"/Proxy contract verification completed (1 point)
6. Be able to save "Hello world" string using setTestVariable() and getTestVariable()  functions through the EternalStorageProxy contract (2 point)

 