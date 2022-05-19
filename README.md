# Another-1 NFT Marketplace Smart Contract
The Another-1 NFT marketplace smart contract provides a platform used for selling and buying CW721 tokens with anone native token.

Interacting with Anone marketplace with the following functions:

1. Listing your NFT with fixed price
2. Listing your NFT and start an auction after the very first bid (the very first bid must be greater than auction's floor price)
3. Buy any fixed price listed NFT
4. Update ask price (only for fixed price listed NFTs)
5. Update floor price
6. Withdraw NFT (remove listing fixed price NFT or remove auction NFT if it doesn't start)
7. Set bid - make an offer on any auction listed NFT (must be greater than the nearest offer)
8. Remove bid