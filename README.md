# Why Graph?
Our project utilizes The Graph to efficiently index and query user data from our GaslessAnonAadhaarCrud smart contract on Polygon Amoy Testnet. We've created a custom subgraph that captures key events like 'UserAdded', 'RelayerAdded', and 'RelayerRemoved'.

This subgraph allows our dApp to:
1. Retrieve user and relayer data quickly using GraphQL queries
2. Avoid costly on-chain calls, improving performance
3. Maintain real-time data synchronization with the blockchain
4. Enable complex queries and filtering of user data

By leveraging The Graph, we've created a scalable and efficient data layer for our identity verification dApp, enhancing its performance and user experience while maintaining decentralization and security.
heres the demo subgraph for omelette: 
[click me](https://tinyurl.com/omelette-graph)
