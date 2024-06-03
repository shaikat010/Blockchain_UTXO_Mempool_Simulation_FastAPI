# Blockchain_UTXO_Mempool_Simulation_FastAPI
This is a core blockchain simulation made using python and fastapi alongside several algorithms for searching and selecting UTXO transactions as done in the original bitcoin blockchain. FastAPI is used for the Backend Api connection tool.

### Use Case Description:

The user submits a transaction using the fast api gateway. The transaction data is then stored in a file in the backend. The transaction is selected and the balance is analysed. Then suitable UTXOs are selected in order to make the transaction happen. This creates the actual transaction and the transaction is then sent to the blockchain to be mined. On successful mining of the block, the chain is updated and the new block is included in the chain. There will also be a wallet creation and connection module that will allow the users to sotre their public and private keys in a predetermined folder in the computer. 

Below is the diagram for process. 

![image](https://github.com/shaikat010/Blockchain_UTXO_Mempool_Simulation_FastAPI/assets/68814937/f8dec58c-4494-4416-816c-9b0314d1fa77)
