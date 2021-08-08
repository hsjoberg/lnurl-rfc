LNURL Documents
===============

These are all the individual documents describing each small piece of protocol that can be implemented under the LNURL umbrella. Different wallets and services may implement different sets of protocols.

| Number      | Description                                                 | Wallets    |
|-------------|-------------------------------------------------------------|-----|
| [01](01.md) | Base LNURL encoding and decoding.                           | [BLW][blw] [Blixt][blixt] [BlueWallet][bluewallet] [Breez][breez] [coinos][coinos] [LNbits][lnbits] [@lntxbot][lntxbot] [Muun][muun] [Phoenix][phoenix] [ShockWallet][shockwallet] [ThunderHub][thunderhub] [Wallet of Satoshi][wos] [Zap Android][zap] [Zap iOS][zap] [ZEBEDEE][zbd] [ZBD Telegram][zbd] [ZBD Discord][zbd] [ZBD Extension][zbd] [Zeus][zeus] |
| [02](02.md) | `channelRequest` base spec.                                 | [BLW][blw] [Breez][breez] [Zeus][zeus] |
| [03](03.md) | `withdrawRequest` base spec.                                | [BLW][blw] [Blixt][blixt] [BlueWallet][bluewallet] [Breez][breez] [coinos][coinos] [LNbits][lnbits] [@lntxbot][lntxbot] [Muun][muun] [Phoenix][phoenix] [ShockWallet][shockwallet] [ThunderHub][thunderhub] [Wallet of Satoshi][wos] [Zap Android][zap] [Zap iOS][zap] [ZEBEDEE][zbd] [ZBD Telegram][zbd] [ZBD Discord][zbd] [ZBD Extension][zbd] [Zeus][zeus] |
| [04](04.md) | Auth base spec.                                             | [BLW][blw] [Blixt][blixt] [coinos][coinos] [LNbits][lnbits] [@lntxbot][lntxbot] [Phoenix][phoenix] [ThunderHub][thunderhub] [Zeus][zeus] |
| [05](05.md) | BIP32-based seed generation for auth protocol.              |     |
| [06](06.md) | `payRequest` base spec.                                     |     |
| [07](07.md) | `hostedChannelRequest` base spec.                           |     |
| [08](08.md) | Fast `withdrawRequest`.                                     |     |
| [09](09.md) | `successAction` field for `payRequest`.                     |     |
| [10](10.md) | `aes` success action in `payRequest`.                       |     |
| [11](11.md) | Disposable and storeable `payRequest`s.                     |     |
| [12](12.md) | Comments in `payRequest`.                                   |     |
| [13](13.md) | LND-based seed generation for auth protocol.                |     |
| [14](14.md) | `balanceCheck`: reusable `withdrawRequest`s.                |     |
| [15](15.md) | `balanceNotify`: services hurrying up the withdraw process. |     |
| [16](16.md) | Paying to static internet identifiers.                      |     |
| [17](17.md) | Scheme prefixes and raw (non bech32-encoded) URLs.          |     |
| [18](18.md) | Proof-of-payer in `payRequest` protocol.                    |     |
| [19](19.md) | Mutually discoverable pay and withdraw links.               |     |

[blw]: https://google.com
[blixt]: https://google.com
[breez]: https://google.com
[bluewallet]: https://google.com
[phoenix]: https://google.com
[zbd]: https://google.com
[coinos]: https://google.com
[lntxbot]: https://google.com
[thunderhub]: https://google.com
[zeus]: https://google.com
[shockwallet]: https://google.com
[wos]: https://google.com
[zap]: https://google.com
[lnbits]: https://google.com
[muun]: https://google.com

Dependency Tree
---------------

[![dependencies](dependencies.png)](dependencies.dot)

How to add your own document
----------------------------

Open a pull request with your proposal. Pick the next unreserved number for your proposal. To be accepted it just have to be generally decent and make sense and be implemented or currently being implemented by 2 or more wallets.

Join https://t.me/lnurl if you just want to talk about your ideas or chat about LNURL protocols in general.
