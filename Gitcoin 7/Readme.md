# Nervos Hackerthon - Gitcoin 7

1. Screenshots or video of your application running on Godwoken.
![-](ckb_01.gif)
2. Link to the GitHub repository with your application which has been ported to Godwoken. This must be a different application than the one covered in this guide.
```
https://github.com/food/hangmanOnNervos
```
3. If you deployed any smart contracts as part of this tutorial, please provide the transaction hash of the deployment transaction, the deployed contract address, and the ABI of the deployed smart contract. (Provide all in text format.)

Transaction hash: ```0x962f3cbca4379eddc28488d3a921c6f6b6fbb44f4303e1dbf487beaaa76b9222```<br/>
Deployed contract address: ```0xbb7d017ab5Ad5C5646f045EC73ffdFE6e3f976F7```

ABI:
```"abi": [
    {
      "inputs": [],
      "name": "gameStatus",
      "outputs": [
        {
          "internalType": "enum Hangman.GameStatus",
          "name": "",
          "type": "uint8"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "trysLeft",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "winner",
      "outputs": [
        {
          "internalType": "enum Hangman.Winner",
          "name": "",
          "type": "uint8"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "bytes32",
          "name": "_bytes32",
          "type": "bytes32"
        }
      ],
      "name": "bytes32ToString",
      "outputs": [
        {
          "internalType": "string",
          "name": "",
          "type": "string"
        }
      ],
      "stateMutability": "pure",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "gameIsWonCheck",
      "outputs": [
        {
          "internalType": "bool",
          "name": "",
          "type": "bool"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "string",
          "name": "word",
          "type": "string"
        }
      ],
      "name": "createGame",
      "outputs": [],
      "stateMutability": "nonpayable",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "string",
          "name": "_letter",
          "type": "string"
        }
      ],
      "name": "guessALetter",
      "outputs": [],
      "stateMutability": "nonpayable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "burnedLettersLength",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "position",
          "type": "uint256"
        }
      ],
      "name": "burnedLetterFromPostion",
      "outputs": [
        {
          "internalType": "string",
          "name": "",
          "type": "string"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "prizeWordLength",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "position",
          "type": "uint256"
        }
      ],
      "name": "prizeWordCharFromPostion",
      "outputs": [
        {
          "internalType": "string",
          "name": "",
          "type": "string"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    }
  ]
```