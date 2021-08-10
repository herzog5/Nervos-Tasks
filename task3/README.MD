## 1. A screenshot of the console output immediately after you have successfully issued a smart contract call.
![](./CallContract.png)
## 2. The transaction hash from the console output (in text format).
0xbcbcadabf47af3f8295b8a2d6ca42cefc7c5283cd3c975957024b702ac683ab3
## 3. The contract address that you called (in text format).
0x97Fe42554dECc0806720A20234aC529cb9228f4b
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
