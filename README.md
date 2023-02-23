mkdir NFT-Tutorial
cd  NFT-Tutorial
npm init --yes
npm install --save-dev hardhat @nomicfoundation/hardhat-toolbox
npx hardhat
npm install @openzeppelin/contracts

添加 NFTee.sol 

npx hardhat compile

安装npm install dotenv 
添加 deploy.js    .env   两个参数 QUICKNODE_HTTP_URL    PRIVATE_KEY

配置 hardhat.config.js

部署到链 npx hardhat run scripts/deploy.js --network goerli

