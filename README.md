# dorahacks_hackathon
Bounty messaging feature for crowd funding application

## Quick start


### deploy smart contract

* Pre requisite

    * Run a local Ethereum client with RPC port 8545 connected to private or test network

*   Perform truffle migrate to deploy the contract

    * Navigate to folder `./crowd-fund-fe`

    * `truffle migrate`

    *   Copy the generate ABI file `./migrations/Voting.json` to `./src/contracts`
    
* Run the React application    
    * Go to root folder

    * `npm install`

    * `npm start`

* Deploy and run the middleware backend application 
    
    * Open new window

    * `cd api`

    * `pip install -r requirement.txt`

    * `python app.py`
