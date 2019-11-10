# Token
Simple tokens for TON.
## Internal token
Token on internal messages. It only can process transfer requests from other contracts.
## External token
Token on external messages. It only can process transfer requests outside of blockchain (can not interact with contracts on chain). To pay fees "fee providers market" is used: mechanisms when pool of fee providers are formed (each with own price), then upon transfer best offer from pool is used, provider get tokens, user pay fee in tokens for the best price.

# Known issues
1. Storage fees handling (not handled at all)
2. Gas credit problems for high number of users

# Future work
1. Mixed token: token which can be used by both contracts and external users.
2. `get_uniq_token` issue, check memo in code

