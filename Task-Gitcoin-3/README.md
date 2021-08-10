## 1. A screenshot of the console output immediately after you have successfully issued a smart contract call.
![](./CallContract.png)
## 2. The transaction hash from the console output (in text format).
0x48989498372095472eb3869b916de055a85696aa5d1bf1f3223dd75e81a8b9f4
## 3. The contract address that you called (in text format).
0x550A4A995490df1D6057e78b13b320C7424c32cc
## 4. The ABI for contract you made a call on (in text format).
```json
[
    {
      "inputs": [],
      "stateMutability": "payable",
      "type": "constructor"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "x",
          "type": "uint256"
        }
      ],
      "name": "set",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "get",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    }
]
```
