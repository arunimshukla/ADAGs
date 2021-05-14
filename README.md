## The Argennon Decentralized Autonomous Governance <br>system (ADAGs /eɪ-dagz/)

Argennon is a new innovative smart contract platform which tries to solve many shortcomings of existing platforms. The
Argennon Virtual Machine is designed to be secure and efficient. Security issues such as reentrancy, complexities of
integer arithmetic errors, and authorization problems does not exist for Argennon programmers. The Argennon Virtual
Machine is scalable and very efficient at data storage. It is optimized for using a zero knowledge database as its
persistence layer, seamlessly and efficiently by taking advantage of a smart data clustering algorithm.

On the other hand, Argennon blockchain uses a truly decentralized and secure proof of stake consensus protocol. Thanks
to the efficient design of the AVM, participation in the Argennon consensus protocol does not require huge computational
resources, and normal personal computers with limited computational power can actively participate in the Argennon
consensus protocol. Check the initial draft of the Argennon white
paper [here](https://github.com/aybehrouz/AVM/blob/main/pdf/A.pdf).

### The Argennon ERC20 token

The Argennon token (ARG) is an ERC20 token intended to represent an investor's share in the Argennon project. The
functionality of the ARG token is as follows:

- After the launch of the Argennon blockchain the ARG token will be convertible in 1:1 ratio to the main currency of the
  Argennon blockchain.
- The ARG ERC20 contract is a profit distributor. That means when an amount of an ERC20 token which is registered as a
  profit source in the contract, is sent to the contract address, that amount will be distributed between all ARG
  holders, proportional to their ARG balance.
- Holders of the ARG token are eligible to vote in the Argennon Decentralized Autonomous Governance system (ADAGs). The
  ADAGs /eɪ-dagz/ is a smart contract which is able to perform *governance actions*. Actions such as starting a new
  crowdfunding campaign, minting new ARG tokens and deploying a new governance system.
    - In order to vote, a user needs to lock his ARG tokens for at least 6 months. During this period he will not be
      able to transfer his tokens.
    - Any proposal that gets more than 60% (3/5) of the total ARG supply votes will be accepted by the ADAGs.

### Crowdfunding Campaigns

Several crowdfunding campaigns may be held before the launch of the Argennon blockchain, all of them will follow these
rules:

- Every crowdfunding is conducted using a smart contract: the *CF contract*, and it has its own token: the *ICO token*.
  Users may buy ICO tokens from the CF contract. A user can burn his ICO tokens and convert them to the ARG token in 1:1
  ratio using the CF contract at any time.
- The ICO token is redeemable. This means that anyone can redeem his ICO tokens by using the CF contract and get a
  refund. The redemption price depends on the time since the start of the crowdfunding and the amount of funds the
  crowdfunding has raised so far:
    - If the amount of raised funds has not yet reached the threshold defined in the CF contract, a user may redeem at
      100% price.
    - If the amount of raised funds has reached the threshold, then the redemption price will drop to the price defined
      in the CF contract, which is determined by the ADAGs and usually is 90%. It is guaranteed that a user can redeem
      at that price for a configured time interval, which again is determined by the ADAGs and usually is one year.
      After that time interval, the ICO token will not be redeemable, and user should only convert them to the ARG
      token.
- When a crowdfunding is done, the earnings of the crowdfunding will automatically be sent to the ARG ERC20 contract
  address and hence, it will be distributed between ARG holders.

### Token Dynamics

The final total supply of the Argennon currency will be 100 billion. The ARG ERC20 token on the other hand, will have a
50 billion cap. Consequently, 50 billion Argennons will be minted only after the launch of the Argennon blockchain.
These Argennons will be mainly used as staking rewards.

The minting of the ARG ERC20 token will follow these rules:

- **5 billion:** founder's share.
- **5 billion:** founder's initial reserve which will be granted to early contributors. **All these grants are
  documented [here](https://github.com/aybehrouz/ADAGs/blob/main/grants.md).**
- **1 billion:** first crowdfunding which will be sold for 100,000$.

The minting of ARG ERC20 tokens will be decided by the ADAGs, but it has to be limited by the maximum supply defined by
the ARG ERC20 contract. This maximum allowed supply is a function of time. For the first year a maximum supply of 10
billion is allowed, and after that, the maximum allowed supply increases 5 billion per year until it reaches the 50
billion cap. It should be noted that this is a hard limit on the **maximum** supply of the ARG ERC20 token and the
actual supply may be lower than this amount.

After the launch of the Argennon blockchain, all unminted ARG ERC20 tokens with respect to the 50 billion cap, will be
considered as the reserve of the ADAGs counterpart on the Argennon blockchain.
