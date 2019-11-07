# Simple token
`sender_id` is hash of the slice with `MsgAddressInt` structure.
## Persistent storage
`init?` - 1bit initialisation flag
`balances` - dictionary `{sender_id -> balance}`

# External token (seqno style)
`sender_id` is pubkey
## Persistent storage
`init?` - 1bit initialisation flag
`balances` - dictionary `{sender_id -> balance}`
`fee_per_send` - fee in tokens for every send
`recent_orders` - dictionary `{query_id -> 1}`




