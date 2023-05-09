# Ethereum-Transactions
How transactions are done in Ethereum Blockchain? 

# Ethereum-Transactions
Ethereum is a decentralized blockchain platform that establishes a peer-to-peer network that securely executes and verifies application code, called smart contracts. Smart contracts allow participants to transact with each other without a trusted central authority.
Overview Transactions in Ethereum are cryptographically signed data messages that contain a set of instructions. These instructions can interpret to sending Ether from one Ethereum account to another or interacting with a smart contract deployed on the blockchain.

## Check contract execution status.
Return the status code of a contract execution.

# Resource Description
Contains information about returns the status code of a contract execution.

#Parameters
##Path Parameters

##Query String Parameters
| Query String Parameter | Required/Optional | Description | Type |
| ------ | ------ | ------ | ------ |
| txhash | Required | the string representing the transaction hash to check the execution status | string |

# Sample Request
```sh
https://api.etherscan.io/api?module=transaction&action=getstatus&txhash=0x15f8e5ea1079d9a0bb04a4c58ae5fe7654b5b2b4463375ff7ffb490aa0032f3a &apikey=YourApiKeyToken
```
(In the above code, replace 'APIKEY' with your actual key.)

## Check transaction receipt status.
Returns the status code of a transaction execution.

# Resource Description
Contains information about returns the status code of a transaction execution.

#Parameters
##Path Parameters

##Query String Parameters
| Query String Parameter | Required/Optional | Description | Type |
| ------ | ------ | ------ | ------ |
| txhash | Required | the string representing the transaction hash to check the execution status | string |

# Sample Request
```sh
https://api.etherscan.io/api?module=transaction&action=gettxreceiptstatus&txhash=0x513c1ba0bebf66436b5fed86ab668452b7805593c05073eb2d51d3a52f480a76&apikey=YourApiKeyToken
```
(In the above code, replace 'APIKEY' with your actual key.)
