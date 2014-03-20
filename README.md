What is RudyCoin?
==============

An alternative cryptocurrency designed to make my cat Rudy rich. Until further notice, this is not a completed cryptocurrency but rather a fork of Maxcoin that I am working on. Do not download -- yet.

Technical Information

+ ~5,000,000 coins
+ 48 coins rewarded per block, halving every ~12 months
+ minimum reward of 1 coin per block
+ 30 second block times
+ difficulty retargeting using Kimoto Gravity Well

Notable differences from Bitcoin
-----------------------------

+ replacement of ECDSA with Schnorr signing
+ use of secp256r1 curve over secp256k1
+ requirement for public key when verifying transactions
+ modification to RPC interface s.t. public keys are Base64 encoded

Modifications to the RPC API
+ verifymessage <maxcoinaddress> <publickey> <signature> <message>
+ makekeypair [prefix]

Additional technical details can be found in the [Wiki](https://github.com/Max-Coin/maxcoin/wiki/_pages).

Forked from Bitcoin reference wallet 0.8.5 and Blakecoin

License
------

MaxCoin is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.
