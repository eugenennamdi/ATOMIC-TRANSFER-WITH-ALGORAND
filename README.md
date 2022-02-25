# PERFORMING ATOMIC TRANSFERS WITH ALGORAND BLOCKCHAIN 


Atomic transfers allow complete strangers to trade assets without the need for a trusted intermediary, all while guaranteeing that each party will receive what they agreed to.



### OVERVIEW
An Atomic Transfer is an operation that allows multiple transactions which are compiled as one to either succed or fail as a whole. 
On Algorand, atomic transfers are implemented as irreducible batch operations, where a group of transactions are submitted as a unit and all transactions in the batch either pass or fail. This also eliminates the need for more complex solutions like hashed timelock contracts that are implemented on other blockchains. 
Atomic transfers enable use cases such as:
Circular trades - Alice pays Bob if and only if Bob pays Claire if and only if Claire pays Alice.
Group payments - Everyone pays or no one pays.
Decentralized exchanges - Trade one asset for another without going through a centralized exchange.
Distributed payments - Payments to multiple recipients.
Pooled transaction fees - One transaction pays the fees of others.


### With ATOMIC SWAP, we can be able to 

(a) Loading two existing accounts...
(b) Create a new account
(c) Generate a mnemonic for the created account
(d) Expose the Initial balances of the two existing accounts
(e) Send a Transaction
(f) Sign the Transaction
(g) Display the Transaction Information in a json format 
(h) Show the transaction on AlgoExplorer
