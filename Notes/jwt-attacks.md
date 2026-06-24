# JWT Attack Reference

## None Algorithm
- Set alg to "none", strip signature
- Header: {"alg":"none","typ":"JWT"}

## HS256 with public key (RS256 confusion)
- Server uses RS256, accepts HS256
- Sign with public key as HMAC secret

## Weak secret brute-force
hashcat -a 0 -m 16500 <token> wordlist.txt
