# dIM : Inventory Management with Blockchain


> dIM --- "distributed Inventory Management"

A distributed application based on campus network which can be used by clubs to have campus-wide transparency and hence security while they issue their valuable items.

## Description
Well the ease of issuing items, returning them, keeping track, *blah, blah*. We are not addressing those issues here by making some yet another Inventory Management system.
The issues which we target here would be the security and transparency of this whole process, which is most desired to be there in every inventory which is owned by a public community, and in our case, the students.
### Existing Protocol
If someone needs something, he asks the captain or any other PoR holder of that given club for the required item. The captain then checks if the given item is there in the existing inventory or not, if not then the captain pushes this request in an upcoming tender if necessary, and if yes then the request is entertained on the availability criteria of the item.
### Problems in Existing Protocol
This works good, the whole process is there for a long time and has given its result without any issues, until, if in some case the item goes *"missing"*. 
The thing is that there is a lot of trusts involved here like we have to trust the captain to not do any mistake or the issuer that he returns the item in time, again the captain that he has taken the entry of the item at return, and where not? Why do we have to put in our *trust* or *faith* ? When we can dive in **blockchain** ?
### Proposed Solution
***Blockchain***
Now everyone, who maintains a ledger ( a type of register ), which everyone would, who is connected to the LAN or IITJ_WLAN, would have knowledge of who gave which item to whom, which item was requested in tender, which item was deprecated, which request got accepted, which one got declined, and everything... now would you have to put your faith in some server, or the person controlling it? Noooo. Because it is not a centralized system where we have to put faith in, everyone is looking it, storing it, taking care of it constantly, *the decentralized network*. the blockchain.
And hence the transparency and security of the publics' valuable belongings.
___
##### Proposed Tech. Stack
- MERN `MongoDB, ExpressJS, NodeJS, ReactJS`
- [Ganache](https://github.com/trufflesuite/ganache-cli) / [Geth](https://geth.ethereum.org/)
- [web3.js](https://web3js.readthedocs.io/en/v1.2.6/)
- [MetaMask](https://metamask.io/)

## Team

|Name|Year|Department|
|--|--|--|
|Kunal Tawatia| Sophomore|Computer Science and Engineering|
