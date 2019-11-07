# Token
Simple tokens for TON.
## Internal token
Token on internal messages. It only can process transfer requests from other contracts.
## External token
Token on external messages. It only can process transfer requests outside of blockchain (can not interact with contracts on chain). Specified upon creation static fee (nominated in tokens) is subtracted from sender on each transfer.

# Known issues
1. Storage fees handling (not handled at all)

# Future work
0. Fift scripts
1. Mixed token: token which can be used by both contracts and external users.
2. Fee providers market: mechanisms when pool of fee providers are formed (each with own price), then upon transfer best offer from pool is used, provider get tokens, user pay fee in tokens for the best price.

