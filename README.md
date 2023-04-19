# NFT-based-voting

Here I create two smart contracts for the Ethereum Goerli testnet. 

Go to [remix IDE](remix.ethereum.org) and load the source files to compile and test the deployment yourself


## ERC721 Token Minting Contract
The token creation function (mint) will be publicly accessible and require a payment of 0.1 ETH;
The metadata is stored on IPFS and compliant with Opensea standards.

## ERC721 Token-based Voting Contract
The linked NFT contract address is hardcoded. 
Each address can only cast one vote, regardless of the number of NFTs owned;
Four receiving addresses are passed as a parameter in the contract constructor;
The voting process can be opened and closed by the administrator, who is not allowed to withdraw the funds.
Only the owner of the winning address can initiate funds withdrawal.
