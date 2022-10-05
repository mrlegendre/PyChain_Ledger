# PyChain_Ledger
Module 18 Homework - Build a blockchain-based ledger system, complete with user-friendly web interface.  This ledger should allow partners to conduct financial transactions, and to verify the integrity of the data in the ledger.

This streamlit application stores a value amount in a ledger.  
The sender and receiver can be changed as well as the value amount.  These three values - sender, receiver, and amount are recorded in the blockchain pychain ledger under 'record'.  

It is encoded and the previous hash is displayed.  The sidebar shows the block difficulty which will change the value of the 'nonce', and each transaction is timestamped.  For a greater block difficulty the nonce value will be increased.  

## PyChain Ledger
![](/Images/pychain1.png)

There is a validate chain button which ensures the blockchain has not been tampered with by checking the hash values, and ensures the proof of Work algorithm has run correctly.

### Successful transaction will show balloons
![](/Images/pychain_balloons.png)

## PyChain Ledger Dataframe of Transactions
![](/Images/pychain_df.png)

