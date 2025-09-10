# AUTH-CRYPT: A Block Based And Cryptographical Solution To Saftey Document Authentication/Storage

AuthCrypt, a full-stack decentralized application to combat document forgery using blockchain for secure, tamper-proof verification.
Leveraged a Solidity smart contract on the Polygon network with IPFS and a web3.js frontend to provide instant and reliable document authentication.

## Features

- Secure document verification using Blockchain and IPFS technologies
- Decentralized system, with no central authority or single point of failure
- Fast and easy verification process, with no need for intermediaries or third-party services
- User-friendly interface for document upload and verification
- Support for multiple document types and formats

## Requirements

- Node.js and npm installed on your system
- MetaMask Wallet
- IPFS API (key and secret) I used Pinata- you can get by creating one

## Installation

1. Clone this repository: 
   ``https://github.com/sparkyharsh/Auth-Crypt.git``

2. Install the required packages:
  ``cd Auth-Crypt``
  `` npm install``

4. deploy the contract.sol using remixe online ide
   after the deployment complete copy the contract address from remix and paste it in the app.js contract address field
   you also need to specify the network url and the network explorer url you are working on ( you can get them from metamask network settings)
   
5. Open the application in your browser using Live Server Extension .
6. if you need to view the actual documents you have to create new Pinata account at ``https://pinata.cloud/`` and use the api id and secret provided by Pinata and paste them in the app.js where is the uploadToPinata function

## Usage

1. The owner of the system must first add an exporter to the list of authorized parties. This is done by clicking on the "Add Exporter" button and entering the exporter's Metamask address.
2. Upload a document to the system by clicking on the "Upload Document" button and selecting a file from your computer. The document will be encrypted and stored in the IPFS network, and its hash will be recorded in the Blockchain.

3. Verify a document by clicking on the "Verify Document" button and choose the document and click verify button. The system will retrieve the document from the IPFS network, decrypt it, and compare its hash with the one recorded in the Blockchain.

4. The system will display a message indicating whether the document is authentic or not.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.






