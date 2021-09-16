(![ETKN](https://user-images.githubusercontent.com/77997949/133622443-32b40805-5d14-48e2-83ab-79a3974d15d3.png)


# EventTicket: Event Sales 

#### Team members:
#### Justin Gouin, Sinan Colpan, Carolina Corona, Chimdike Ihe, Dave Dwarakan
---


# Contents:

- [OBJECTIVE](#objective)

- [TECHNOLOGIES](#technologies)

- [VIDEO DEMO](#video-demo)
   
- [FUNCTIONS](#functions)

	- [Ticket Registration (Minting)](#minting)
	- [Buying a ticket from the vendor](#Buying-a-ticket-from-the-vendor)
	- [Buying a ticket from another user](#Buying-a-ticket-from-another-user)
	- [Collecting a refund](#Collecting-a-refund)
	- [Accepting an offer from another user](#Accepting-an-offer-from-another-user)
	- [Rejecting an offer](#Rejecting-an-offer)



### Objective:

EventTicket is a decentralized application that offers a blockchain solution for ticket providers. It offers customers the benefits and security of the ERC-721 standard. In our system, an NFT represents an event ticket (ETCKT token) which is essentially transferred to the purchaser. The system also allows potential buyers to purchase tickets that have already been purchased, directly from the owner. Purchase offers can be controlled by limiting the amount of resales for a particular event and the price increases can be set by the event organizers to limit or control ticket scalping. 

### Technologies, platforms and libraries used:

- Solidity
- Remix
- OpenZeppelin
- Python
- Jupyter notebook
- web3 py
- Infura
- Rinkeby testnet
- Ganache
- Metamask

(![z](https://user-images.githubusercontent.com/77997949/133622603-7ac4ceb1-8160-4dd7-b67b-e3f3042cb2b8.png)


---
## Video Demo
[HERE](https://youtu.be/Ih6cbqdMljA)

---

## UML:
(![UML](https://user-images.githubusercontent.com/77997949/133622707-5749b64b-01ff-4de6-860c-7532b3ddaa95.png)

---

## Process flow:

###  Minting
(![minting](https://user-images.githubusercontent.com/77997949/133622825-d371bfdc-6534-4e63-8c47-0f9d150b7210.png)

###  Buying a ticket from the vendor
(![buyingfromvendor](https://user-images.githubusercontent.com/77997949/133622865-6f817d24-fca9-4e8d-93ef-84f55eb20864.png)

###  Buying a ticket from another user
(![offertouser](https://user-images.githubusercontent.com/77997949/133622970-2b10324b-deb3-410f-8a9d-cbc609d586d2.png)

###  Collecting a refund
(![colecting-refund](https://user-images.githubusercontent.com/77997949/133623068-0e357f89-6bf4-4f25-84e1-44dd021a58d3.png)

###  Accepting an offer from another user
(![accepting_offer](https://user-images.githubusercontent.com/77997949/133623094-d7b847c7-9aef-4383-86c7-9e2a77a65394.png)

###  Rejecting an offer
(![rejecting_offer](https://user-images.githubusercontent.com/77997949/133623171-e88f91e5-06ae-4b3e-976d-eaa39c9ca4cc.png)


## Deployment:

1) Compile and deploy the [contract](EventTicket/EventTicket.sol) on the Rinkeby testnet using Remix.

2) Copy the address of the contract and paste it under EVENTTICKET_ADDRESS in [env.txt](EventTicket/env.txt).

3) Copy the private key of the account you used to deploy your contract and paste it under ACCT_PRIV_KEY in [env.txt](EventTicker/env.txt).

4) Rename the env.txt file to .env

5) Run jupyter notebook and open the [EventTicket](EventTicket/EventTicket.ipynb) notebook.

6) Once connected, try to run thorugh the purchase scenarios from the process flows above. Enjoy!

7) If interested in how web3 is helping us connect to the contract on the blockchain, have a look through our helper code [ticket.py](EventTicket/ticket.py) here.
