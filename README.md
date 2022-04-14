# Pre-work Assignment

Congratulations!! Welcome to Artemis Academy's proof of concept pre-work stage! 

The admissions process for the Artemis bootcamp cannot continue until you pass the pre-work stage here. We expect you to work for about 20 - 30 hours on steps 1 and 2 as described below. **We ask you to submit your results within 2 weeks of receipt of this notice.**

1. Develop a practical solution for **one** of the Engineering Exercise options described **below**.
2. Write an essay, in your own words, explaining your thought process and what you felt were the hardest problems to solve.

We ask you to read the following statements clearly and to follow a couple of requirements.

* Carefully comment your code.
* Write some unit tests for your code where it makes sense.
* Deploy your contracts to Goerli testnet.
* Save the addresses of the deployed contracts of your final solution. 
* Publish your solution in a secret GitHub Gist.
* Be mindful of which GitHub account you use to create your Gist if you'd like to remain anonymous.
* Share the link to the GitHub Repository with your solution, the addresses of the deployed contracts and your essay.
* Feel free to use resources at your disposal such as Google, Solidity documentation, and/or any online learning tools.
* We recommend using RemixIDE to develop your solution. http://remix.ethereum.org.



# Engineering Exercise

**Important!**: Fully completing this exercise is **not** a requirement. We encourage you to submit the form with the work you've done regardless of its degree of quality or completion. The purpose of the pre-work is to challenge yourself and prove your individual approach from 0 to 1. **Please choose from one of the four options below.**



# Options

**1. Implement some form of on-chain quorum**

Implement a contract whose purpose is to serve as a shared wallet. This wallet contract should allow any of its authorized members to submit a transaction. The submitted transaction should need to be approved by a minimum number of authorized members in order to be executed on chain. Only the wallet’s members should be authorized to take part in the process of submitting, approving and executing transactions. Members must also be able to revoke their own approvals. A member must not be able to revoke other members’ approvals. The number of members as well as the minimum amount of approvals should be set at the time of contract deployment.



**2. Implement some form of staking contract**

Implement a contract that allows anyone to deposit a predefined token and earn more of that same token over time, for as long as it remains deposited. At the time of deposit the user should receive a “receipt” token that represents their claim on the deposited amount plus accrued rewards. The depositor can check their balance and exchange their receipt tokens for the deposited tokens plus the accrued rewards at any given time. Multiple users should be able to stake their tokens and claim their rewards. 



**3. Implement some form of voting ballot**

Implement a pair of contracts: one that serves as a voting ballot and another as a token. This voting ballot allows holders of the token to create proposals and to vote on said proposals. The voting period duration must be identical for all proposals and should be defined on the voting ballot contract. Proposals created on the voting ballot must include a predefined list of voting options. Any token holder can vote on any ongoing proposal or delegate their voting power to another holder. A proposal is only passed if a quorum, predefined in the voting ballot itself, is reached.



**4. Implement some form of escrow contract**

Implement an escrow contract. This contract should be able to hold any amount of a given token sent by a defined set of participants (senders). After a predefined time window a different set of participants (receivers) are able to withdraw the funds in a pro rata fashion based on predefined weights. Funds must not be withdrawn until the expiry time was reached. Any sender can file for a dispute.



---

_If you have any questions please feel free to reach out to admissions@artemis.education_
