# On-chain-wallet-contracts
Security evaluation of on-chain wallet contracts in Ethereum blockchain platform  
This reporsitory has on-chain smart contract wallet data in SmartContractWallets.xls file.  
It contains security analysis result and evaluations.  
## Used four popular security analysis tools to scan on-chain wallet contracts
To set up a docker environment to execute these analysis tools, we pulled the latest docker images of Oyente, Osiris, Maian, and Mythril tools.  
Each docker container has configured with required dependencies, including Python, Solidity compiler Solc, Z3 theorem prover, Web3 library, Go Ethereum client Geth, and other external libraries to run these tools with accuracy and error-free.  
Oyente: https://github.com/melonproject/oyente  
Osiris: https://github.com/christoftorres/Osiris  
Maian: https://github.com/ivicanikolicsg/MAIAN  
Mythril: https://github.com/ConsenSys/mythril    
The scanned result and analysis data from these tools for each wallet contract is stored in ScanResult folder.
