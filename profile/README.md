# Hey 👋

This is our participation in the [Encode x Multivers Hackathon](https://www.encode.club/multiversx-hackathon)!

## Developments steps

### 1. Getting data to train the IA
To train our AI, we used data from all wallets on the MultiversX blockchain with more than 50 transactions. 
This encompasses over 150,000 wallets, providing a comprehensive dataset for our advanced learning processes.

We created this [tool](https://github.com/MVX-TKYC/tools/blob/main/wallets_data_scrapper/README.md) to download the data

#### Choices

##### Getting data as fast as possible
The faster we get the data, the faster we can train the IA.
So we choose to ignore wallets with less than 50 transactions.

##### Scraping method
Instead of API, we used Elastic Search which has no rate limit.
