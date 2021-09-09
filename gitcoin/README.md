## About

TrueBlocks is a user-centric data indexer, querying and caching layer, and monitoring tool for any EVM-based blockchain.

Users can extract and view data across multiple addresses and smart contracts using their own local node (or third-party node-providers if they must).

Trueblocks treats blockchain data as a “public good” and unlike other indexers retains the key benefits of blockchains:

- it limits dependency on a central gatekeeper, as it runs local-first
  - there are no centralized front-end web 2.0 websites
- it retains the integrity of the chain data
  - no need for arbitrators or trust
- it provides complete privacy
  - no web 2.0 website to undermine this
- it promotes cheap, equitable, and easy access to all chain data
  -   no rivalrous fee system, no spinners, no rate limiting, no truncated or unreconcilable data. 

TrueBlocks' current and future capabilities: 

- View a complete history of address(es) from any desktop (via TrueBlocks’ Explorer)
- Export fully reconciled transaction histories by account/token over any period
- Export to QuickBooks, Excel, RStudio, CSV, etc.
- Monitor tokens (Where are my tokens? How many do I have? How many have I approved?)
- Manage and secure NFT collections (using IPFS directly)
- Receive off-chain email notifications/triggers of activity on addresses (future)
- Duplicate the indexing provided by coin incentivized indexers such as theGraph
- Watch DAO activity (What proposals are active? Do I have to vote on something?)
- Build testing algorithms (e.g. "digital twins") to facilitate smart contract testing, auditing, ongoing monitoring, and simulation

TrueBlocks already indexes Ethereum mainnet and Rinkeby, but we are actively looking at other chains (such as Optimism).

## Results from Previous Rounds

Thank you to our supporters from previous GitCoin Grant rounds. We appreciate the support you’ve provided to keep this mostly self-funded project going.

We've been busy since the last Grant round:

- Recieved a [grant from the Moloch DAO](https://docs.google.com/document/d/1IFXYAzSDtMSKQTuY2kos07ZLJLkRJy_eh8fFwMaciBE/edit) for our work on Trueblocks
- We [spoke at the ETHCC4](https://www.youtube.com/watch?v=7KjhQPwKGdQ) Conference in July about TrueBlocks
- Dawid Szlachta joined the TrueBlocks team as a fullstack developer; Matt Dodson joined on a parttime basis to help with communication and documentation
- Completed migration to use the Erigon node as our primary node
- Began complete re-write of Front End App
- Completed first beta release of docker version
- Automated most of the testing and documentation generation
- Helped multiple people index two different Ethereum chains (mainnet and Rinkeby)
- Made major progress on our [documentation website](https://trueblocks.io/docs)
- Made some videos explaining [new features in the Explorer](https://www.youtube.com/channel/UCAnakN-bJv_OsopuKVJCs3g)
- Created a landing page for some [white papers](https://trueblocks.io/papers/) we've written


## How Future Contributions Will Help

We’ve accomplished a lot with your support, but there’s more work to do:

- Working on reference implementation (in paralellized GOlang) and whitepaper documenting indexing and querying layers 
- Continuing to investigate custome stage for Erigon
- Finalizing the dAppNode docker package 
- Continue to engage with users for feedback
- Continue re-design of frontend 
- Continue to investigat other chains including L2s 
- Completing full documentation for backend, API, and frontend 

Please help us finalize the only true data query tool which is completely local to your own machine, perfectly private, uncensorable and immutable.