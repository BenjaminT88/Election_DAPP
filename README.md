Election - DAPP

This is a decentralized app (DAPP) that I created following the tutorial of Dapp University.

Full Free Video Tutorial: https://youtu.be/3681ZYbDSSk

Dependencies

Install these prerequisites to follow along with the tutorial. See free video tutorial or a full explanation of each prerequisite.

  NPM: https://nodejs.org
  Truffle: https://github.com/trufflesuite/truffle
  Ganache: http://truffleframework.com/ganache/
  Metamask: https://metamask.io/

Step 1. Install Dependencies
  ```$ cd ELECTION_DAPP```
  ```$ npm install```

Step 2. Start Ganache
  Open the Ganache GUI client that you downloaded and installed. This will start your local blockchain instance.

Step 3. Compile & Deploy Election Smart Contract
  ```$ truffle migrate --reset```
  You have to migrate the election smart contract every time you restart Ganache or make changes to the code.

Step 4. Configure Metamask
  Unlock Metamask.
  Connect metamask to your local Etherum blockchain provided by Ganache.
  Import an account provided by ganache.

Step 5. Run the Front End Application
  ```$ npm run dev```
  If the application doesn't automatically open, go to: http://localhost:3000
  