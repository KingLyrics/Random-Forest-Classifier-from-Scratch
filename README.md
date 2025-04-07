# Random-Forest-Classifier-from-Scratch

# Dataset OverView
The *Shill Bidding Dataset* is for finding fradulent bidding behaviour in online auctions.

Dataset Link: https://archive.ics.uci.edu/dataset/562/shill+bidding+dataset

Contains: *6,321 samples/instances*  and has over *13 features*

## Dataset Field Descriptions

- **Record ID**: Unique identifier of a record in the dataset.

- **Auction ID**: Unique identifier of an auction.

- **Bidder ID**: Unique identifier of a bidder.

- **Bidder Tendency**: A shill bidder participates exclusively in auctions of a few sellers rather than a diversified lot. This is a collusive act involving the fraudulent seller and an accomplice.

- **Bidding Ratio**: A shill bidder participates more frequently to raise the auction price and attract higher bids from legitimate participants.

- **Successive Outbidding**: A shill bidder successively outbids themselves even though they are the current winner to increase the price gradually with small consecutive increments.

- **Last Bidding**: A shill bidder becomes inactive at the last stage of the auction (more than 90% of the auction duration) to avoid winning the auction.

- **Auction Bids**: Auctions with shill bidding activities tend to have a much higher number of bids than the average of bids in concurrent auctions.

- **Auction Starting Price**: A shill bidder usually offers a small starting price to attract legitimate bidders into the auction.

- **Early Bidding**: A shill bidder tends to bid pretty early in the auction (less than 25% of the auction duration) to get the attention of auction users.

- **Winning Ratio**: A shill bidder competes in many auctions but hardly wins any.

- **Auction Duration**: How long an auction lasted.

- **Class**: 
  - `0`: Normal bidding behavior  
  - `1`: Shill bidding or otherwise fraudulent behavior
