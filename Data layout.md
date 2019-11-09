# Simple token
`sender_id` is hash of the slice with `MsgAddressInt` structure.
## Persistent storage
`init?` - 1bit initialisation flag
`balances` - dictionary `{sender_id -> balance}`

# External token (seqno style)
`sender_id` is pubkey
## Persistent storage
`init?` - 1bit initialisation flag
`description` - ref, cell with arbitrary content, contains data about token
`balances` - dictionary `{sender_id -> balance}`
`gas_per_send` - gas which should be bought by user for one send
`recent_orders` - dictionary `{query_id -> 1}`
`gas_providers` - dictionary `{bid_id -> (gram_balance, provider_id)}`, `bid_id` is price of nanograms per token




