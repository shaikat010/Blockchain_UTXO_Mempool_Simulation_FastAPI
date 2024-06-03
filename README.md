# Blockchain_UTXO_Mempool_Simulation_FastAPI
This is a core blockchain simulation made using python and fastapi alongside several algorithms for searching and selecting UTXO transactions as done in the original bitcoin blockchain. FastAPI is used for the Backend Api connection tool.

### Use Case Description:

The user submits a transaction using the fast api gateway. The transaction data is then stored in a file in the backend. The transaction is selected and the balance is analysed. Then suitable UTXOs are selected in order to make the transaction happen. This creates the actual transaction and the transaction is then sent to the blockchain to be mined. On successful mining of the block, the chain is updated and the new block is included in the chain. There will also be a wallet creation and connection module that will allow the users to sotre their public and private keys in a predetermined folder in the computer. 

1. There will be some predetermined UTXO's in the genesis block containing the transactions. This is to allow for the first batch of UTXO's to be made.
2. On successful ming of the block the miner will be given a reward in the form of a single UTXO. This can be one single UTXO that will be added to the existing set of UTXOs
3. Also the used up UTXOs will be removed from the UTXO list and be put into a used_UTXOs list
4. There will be a mechanism for locking the UTXOs if they are being used by some other transaction. 


Below is the diagram for process. 

![image](https://github.com/shaikat010/Blockchain_UTXO_Mempool_Simulation_FastAPI/assets/68814937/6db939dd-d01b-47e7-a5b2-a80b03a01611)

