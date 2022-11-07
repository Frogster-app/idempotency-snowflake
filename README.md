# idempotency-snowflake
Generate unique IDs for idempotency processes 

## Binary breakdown
```
Unix timestamp                   Proccess       User ID                          Endpoint
11111111111111111111111111111111 11111111111111 11111111111111111111111111111111 11111111
32                               14             12                               8        0
```
```
01100011010101010000110011101001 00001001001011 00000000000000000000000001101100 00000001
1666518249                       587            108                              1

Unix timestamp: Sun Oct 23 09:44:09 2022 UTC
Endpoint:       Register (/auth/register)
Proccess:       587
Device ID:      108
```
