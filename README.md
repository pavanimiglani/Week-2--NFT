Week 2 Assignment- Pavani Miglani
101517557

Using the instructions and files provided in the Teams Chat, create an NFT Minting DApp.
install hardhat as the development environment
connect to MetaMask and use Alchemy as your blockchain node provider
compile your smart contract and use deploy.js to deploy your smart contract to Ethereum Sepolia
implement a simple frontend UI to mint your NFT 

Project Structure

Files Included:
1. contracts/smartcontract.sol: Contains the Solidity smart contract for the NFT minting functionality.
2. hardhat.config.js: Configuration file for Hardhat setup, network connections, and deployment settings.
3. deploy.js: Script to deploy the smart contract to the Ethereum Sepolia test network.
4. nft_frontend/src/App.js
5. nft_frontend/public/index.html 
6. nft_frontend/app.css
7. nft_frontend/.env
8. nft_frontend/package.json 

Setup Instructions: 

1. Install Hardhat: npm install --save-dev hardhat 
2. Compile the smart contract using Hardhat: npx hardhat compile
3. Deploy the smart contract to Ethereum Sepolia using the deploy.js script and Hardhat: npx hardhat run deploy.js --network sepolia 
4. Run the frontend UI on the local server -npm start 

