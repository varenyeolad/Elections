# Election 

## Step 1. Clone the project

git clone https://github.com/varenyeolad/Elections.git

## Step 2. Install dependencies

$ npm install

## Step 3. Start Ganache

Open the Ganache GUI client that you downloaded and installed. This will start your local blockchain instance.

## Step 4. Compile & Deploy Election Smart Contract

$ truffle migrate --reset --network bscTestnet
You must migrate the election smart contract each time your restart ganache.

## Step 5. Configure Metamask

- Unlock Metamask
- Connect metamask to your local Etherum blockchain provided by Ganache.
- Import an account provided by ganache.

## Step 6. Run the Front End Application

$ npm run start
Visit this URL in your browser: http://localhost:3000
