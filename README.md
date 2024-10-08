# cryptopals-rust
This repository contains solutions to all of the [cryptopal challenges](https://cryptopals.com/) written in Rust.

## Usage
Simply execute the following commands after cloning the repository:
```
cd cryptopals-rust/
cargo run --bin cXX
```
This will run the code for challenge XX.

## Challenges

### Set 1 - Basics

- [ ] Challenge 1: Convert hex to base64
- [ ] Challenge 2: Fixed XOR
- [ ] Challenge 3: Single-byte XOR cipher
- [ ] Challenge 4: Detect single-character XOR
- [ ] Challenge 5: Implement repeating-key XOR
- [ ] Challenge 6: Break repeating-key XOR
- [ ] Challenge 7: AES in ECB mode
- [ ] Challenge 8: Detect AES in ECB mode

### Set 2 - Block Crypto

- [ ] Challenge 9: Implement PKCS#7 padding
- [ ] Challenge 10: Implement CBC mode
- [ ] Challenge 11: An ECB/CBC detection oracle
- [ ] Challenge 12: Byte-at-a-time ECB decryption (Simple)
- [ ] Challenge 13: ECB cut-and-paste
- [ ] Challenge 14: Byte-at-a-time ECB decryption (Harder)
- [ ] Challenge 15: PKCS#7 padding validation
- [ ] Challenge 16: CBC bitflipping attacks

### Set 3 - Block and Stream Crypto

- [ ] Challenge 17: The CBC padding oracle
- [ ] Challenge 18: Implement CTR, the stream cipher mode
- [ ] Challenge 19: Break fixed-nonce CTR mode using substitutions
- [ ] Challenge 20: Break fixed-nonce CTR statistically
- [ ] Challenge 21: Implement the MT19937 Mersenne Twister RNG
- [ ] Challenge 22: Crack an MT19937 seed
- [ ] Challenge 23: Clone an MT19937 RNG from its output
- [ ] Challenge 24: Create the MT19937 stream cipher and break it

### Set 4 - Stream crypto and randomness

- [ ] Challenge 25: Break "random access read/write" AES CTR
- [ ] Challenge 26: CTR bitflipping
- [ ] Challenge 27: Recover the key from CBC with IV=Key
- [ ] Challenge 28: Implement a SHA-1 keyed MAC
- [ ] Challenge 29: Break a SHA-1 keyed MAC using length extension
- [ ] Challenge 30: Break an MD4 keyed MAC using length extension
- [ ] Challenge 31: Implement and break HMAC-SHA1 with an artificial timing leak
- [ ] Challenge 32: Break HMAC-SHA1 with a slightly less artificial timing leak

### Set 5 - Diffie-Hellman and friends

- [ ] Challenge 33: Implement Diffie-Hellman
- [ ] Challenge 34: Implement a MITM key-fixing attack on Diffie-Hellman with parameter injection
- [ ] Challenge 35: Implement DH with negotiated groups, and break with malicious "g" parameters
- [ ] Challenge 36: Implement Secure Remote Password (SRP)
- [ ] Challenge 37: Break SRP with a zero key
- [ ] Challenge 38: Offline dictionary attack on simplified SRP
- [ ] Challenge 39: Implement RSA
- [ ] Challenge 40: Implement an E=3 RSA Broadcast attack

### Set 6 - RSA and DSA

- [ ] Challenge 41: Implement unpadded message recovery oracle
- [ ] Challenge 42: Bleichenbacher's e=3 RSA Attack
- [ ] Challenge 43: DSA key recovery from nonce
- [ ] Challenge 44: DSA nonce recovery from repeated nonce
- [ ] Challenge 45: DSA parameter tampering
- [ ] Challenge 46: RSA parity oracle
- [ ] Challenge 47: Bleichenbacher's PKCS 1.5 Padding Oracle (Simple Case)
- [ ] Challenge 48: Bleichenbacher's PKCS 1.5 Padding Oracle (Complete Case)

### Set 7 - Hashes

- [ ] Challenge 49: CBC-MAC Message Forgery
- [ ] Challenge 50: Hashing with CBC-MAC
- [ ] Challenge 51: Compression Ratio Side-Channel Attacks
- [ ] Challenge 52: Iterated Hash Function Multicollisions
- [ ] Challenge 53: Kelsey and Schneier's Expandable Messages
- [ ] Challenge 54: Kelsey and Kohno's Nostradamus Attack
- [ ] Challenge 55: MD4 Collisions
- [ ] Challenge 56: RC4 Single-Byte Biases
      
### Set 8 - Abstract Algebra

- [ ] Challenge 57: Diffie-Hellman Revisited: Small Subgroup Confinement
- [ ] Challenge 58: Pollard's Method for Catching Kangaroos
- [ ] Challenge 59: Elliptic Curve Diffie-Hellman and Invalid-Curve Attacks
- [ ] Challenge 60: Single-Coordinate Ladders and Insecure Twists
- [ ] Challenge 61: Duplicate-Signature Key Selection in ECDSA (and RSA)
- [ ] Challenge 62: Key-Recovery Attacks on ECDSA with Biased Nonces
- [ ] Challenge 63: Key-Recovery Attacks on GCM with Repeated Nonces
- [ ] Challenge 64: Key-Recovery Attacks on GCM with a Truncated MAC
- [ ] Challenge 65: Truncated-MAC GCM Revisited: Improving the Key-Recovery Attack via Ciphertext Length Extension
- [ ] Challenge 66: Exploiting Implementation Errors in Diffie-Hellman


## Disclaimer
As the purpose of these challenges is educational, I have reimplemented a lot of functionality instead of using library functions or crates. Of course these reimplementations are in no way supposed to be used for anything serious and you should always refer to an official library instead.

In particular the implementations of cryptographic algorithms found in this repository are completely insecure, in many cases even on purpose because it is part of the challenges to break those broken implementations.
