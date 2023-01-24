# BlockchainProject

These are the steps to get the project running:
1) Download and extract the Zip file
2) Install the dependencies 
3) Start the local network with the following command: npx hardhat node **Save the server address presented
4) Run the contracts with: npx hardhat run --network localhost scripts/deploy.js
5) Add a new local network via metamask the the server address
6) Import one of the minting signer to the network by copying the private key presented into the network via meta mask.
7) Import tokens from metamask by pasting token address generated into the imported account. Do this for all of the generated addresses. 
8) Start the React project from app/client by entering the following command: npm start. 

Following the above steps will start the project and will allow you to connect to the local network and created accounts. 
