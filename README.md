# dPoW client _iguana_

This repository is based on the original SuperNET codebase - commit [f29913e92b117399cd42e2fd05ff0d69d152c8fa](https://github.com/ca333/SuperNET/commit/f29913e92b117399cd42e2fd05ff0d69d152c8fa)

Integration | Status 
-------------|------
CI build - Ubuntu (20.04, 22.04) | [![Build Status](https://github.com/komodoplatform/dpow/workflows/CI/badge.svg?maxAge=60)](https://github.com/KomodoPlatform/dPoW/actions)
Codefactor analysis | [![Grade](https://img.shields.io/codefactor/grade/github/komodoplatform/dpow)](https://www.codefactor.io/repository/github/komodoplatform/dpow)
Version | [![Version](https://img.shields.io/github/v/release/komodoplatform/dPoW)](https://github.com/KomodoPlatform/dPoW/releases)
Network Statistics | https://stats.kmd.io/

---


## Installation 

General [Setup instructions](https://docs.komodoplatform.com/notary/setup-Komodo-Notary-Node.html#setup-komodo-notary-node)

### Build instructions for NN operations:
`cd iguana`

#### Build iguana for notary operations
`make`

#### Start main-net notarizations:
`./m_notary_main`

#### Start 3rd party notarizations:
`./m_notary_3rdparty`

**Please note: Automatic UTXO split is deactivated by default.**


## dPoW asset status

### dPoW assets update requirements

**Please note:** All dPoW protected blockchain projects are required to open an issue ticket with upgrade details in this repository and at least 4 weeks prior to a mandatory update - in case of significant code changes (>2000 lines of code altered/added) open the issue ticket at least 8 weeks prior to the mandatory update. Send the official update announcement ref to `partners@komodoplatform.com`.

#### [Notary Node metrics](http://stats.kmd.io/) - http://stats.kmd.io/

#### [Notary Addresses](https://deckersu.github.io/notaries_addresses.html)

[![dPOW Status](https://badges.komodo.earth/svg/date_badge.svg?maxAge=60)](https://komodostats.com)
* active - last notarization less than 2.5 hours ago
* irregular - last notarization more than 2.5 and less than 24 hours ago
* inactive - last notarization more than 24 hours ago

Coin | src | Version/Tree | Status | dPoW 
--------|------|---|------|------
KMD | [komodo](https://github.com/komodoplatform/komodo) | [d456be3](https://github.com/KomodoPlatform/komodo/tree/d456be35acd1f8584e1e4f971aea27bd0644d5c5) | [![dPOW Status](https://badges.komodo.earth/svg/KMD_badge.svg?maxAge=60)](https://komodostats.com) | dPoW-Mainnet
LTC | [litecoin](https://github.com/litecoin-project/litecoin) | [0.16](https://github.com/litecoin-project/litecoin/tree/69fce744115a7d2889ff1b90e89582b83de405ad) | [![dPOW Status](https://badges.komodo.earth/svg/KMD_badge.svg?maxAge=60)](https://komodostats.com) | dPoW-Mainnet
CCL | [komodo](https://github.com/komodoplatform/komodo) | [d456be3](https://github.com/KomodoPlatform/komodo/tree/d456be35acd1f8584e1e4f971aea27bd0644d5c5) | [![dPOW Status](https://badges.komodo.earth/svg/CCL_badge.svg?maxAge=60)](https://komodostats.com) | dPoW-mainnet
CLC | [komodo](https://github.com/komodoplatform/komodo) | [d456be3](https://github.com/KomodoPlatform/komodo/tree/d456be35acd1f8584e1e4f971aea27bd0644d5c5) | [![dPOW Status](https://badges.komodo.earth/svg/CLC_badge.svg?maxAge=60)](https://komodostats.com) | dPoW-mainnet
DOC | [komodo](https://github.com/komodoplatform/komodo) | [d456be3](https://github.com/KomodoPlatform/komodo/tree/d456be35acd1f8584e1e4f971aea27bd0644d5c5) | [![dPOW Status](https://badges.komodo.earth/svg/MORTY_badge.svg?maxAge=60)](https://komodostats.com) | dPoW-mainnet
GLEEC | [komodo](https://github.com/komodoplatform/komodo) | [d456be3](https://github.com/KomodoPlatform/komodo/tree/d456be35acd1f8584e1e4f971aea27bd0644d5c5) | [![dPOW Status](https://badges.komodo.earth/svg/GLEEC_badge.svg?maxAge=60)](https://komodostats.com) | dPoW-mainnet
ILN | [komodo](https://github.com/komodoplatform/komodo) | [d456be3](https://github.com/KomodoPlatform/komodo/tree/d456be35acd1f8584e1e4f971aea27bd0644d5c5) | [![dPOW Status](https://badges.komodo.earth/svg/ILN_badge.svg?maxAge=60)](https://komodostats.com) | dPoW-mainnet
KOIN | [komodo](https://github.com/komodoplatform/komodo) | [d456be3](https://github.com/KomodoPlatform/komodo/tree/d456be35acd1f8584e1e4f971aea27bd0644d5c5) | [![dPOW Status](https://badges.komodo.earth/svg/KOIN_badge.svg?maxAge=60)](https://komodostats.com) | dPoW-mainnet
MARTY | [komodo](https://github.com/komodoplatform/komodo) | [d456be3](https://github.com/KomodoPlatform/komodo/tree/d456be35acd1f8584e1e4f971aea27bd0644d5c5) | [![dPOW Status](https://badges.komodo.earth/svg/MORTY_badge.svg?maxAge=60)](https://komodostats.com) | dPoW-mainnet
NINJA | [komodo](https://github.com/komodoplatform/komodo) | [d456be3](https://github.com/KomodoPlatform/komodo/tree/d456be35acd1f8584e1e4f971aea27bd0644d5c5) | [![dPOW Status](https://badges.komodo.earth/svg/NINJA_badge.svg?maxAge=60)](https://komodostats.com) | dPoW-mainnet
PIRATE | [komodo](https://github.com/komodoplatform/komodo) | [d456be3](https://github.com/KomodoPlatform/komodo/tree/d456be35acd1f8584e1e4f971aea27bd0644d5c5) | [![dPOW Status](https://badges.komodo.earth/svg/PIRATE_badge.svg?maxAge=60)](https://komodostats.com) | dPoW-mainnet
RICK | [komodo](https://github.com/komodoplatform/komodo) | [d456be3](https://github.com/KomodoPlatform/komodo/tree/d456be35acd1f8584e1e4f971aea27bd0644d5c5) | [![dPOW Status](https://badges.komodo.earth/svg/RICK_badge.svg?maxAge=60)](https://komodostats.com) | dPoW-mainnet
SUPERNET | [komodo](https://github.com/komodoplatform/komodo) | [d456be3](https://github.com/KomodoPlatform/komodo/tree/d456be35acd1f8584e1e4f971aea27bd0644d5c5) | [![dPOW Status](https://badges.komodo.earth/svg/SUPERNET_badge.svg?maxAge=60)](https://komodostats.com) | dPoW-mainnet
THC | [komodo](https://github.com/komodoplatform/komodo) | [d456be3](https://github.com/KomodoPlatform/komodo/tree/d456be35acd1f8584e1e4f971aea27bd0644d5c5) | [![dPOW Status](https://badges.komodo.earth/svg/THC_badge.svg?maxAge=60)](https://komodostats.com) | dPoW-mainnet
AYA | [aryacoin](https://github.com/KomodoPlatform/AYAv2) | [d40b0d7](https://github.com/KomodoPlatform/AYAv2/tree/d40b0d7682d1568fc4bb5a18c705c0681ecfaa85) | [![dPOW Status](https://badges.komodo.earth/svg/AYA_badge.svg?maxAge=60)](https://komodostats.com) | dPoW-3P
CHIPS | [chips](https://github.com/chips-blockchain/chips) | [f0dfd82](https://github.com/chips-blockchain/chips/tree/f0dfd82dd9f98626dd0045c3ed93102dfd5988fb) | [![dPOW Status](https://badges.komodo.earth/svg/CHIPS_badge.svg?maxAge=60)](https://komodostats.com) | dPoW-3P
EMC2 | [emc2](https://github.com/emc2foundation/einsteinium) | [c329ae6](https://github.com/emc2foundation/einsteinium/tree/c329ae64397bea743054d06b779bb4cbfdcdd25f) | [![dPOW Status](https://badges.komodo.earth/svg/EMC2_badge.svg?maxAge=60)](https://komodostats.com) | dPoW-3P
MCL | [marmarachain](https://github.com/marmarachain/marmara) | [c675fcb](https://github.com/marmarachain/marmara/tree/c675fcb5bce34b6bb2ae8032109302a7473035cb) | [![dPOW Status](https://badges.komodo.earth/svg/MCL_badge.svg?maxAge=60)](https://komodostats.com) | dPoW-3p
MIL | [mil](https://github.com/emc2foundation/mil) | [578bed7](https://github.com/emc2foundation/mil/tree/578bed7f403c4d4a16561317d356202ca60c605f) | [![dPOW Status](https://badges.komodo.earth/svg/MIL_badge.svg?maxAge=60)](https://komodostats.com) | dPoW-3P
TOKEL | [tokel](https://github.com/TokelPlatform/tokel) | [d2e98de](https://github.com/TokelPlatform/tokel/tree/d2e98de9d1ac6e26c20d540d5a8d7a493e2cf5fd) | [![dPOW Status](https://badges.komodo.earth/svg/TOKEL_badge.svg?maxAge=60)](https://komodostats.com) | dPoW-3P
VRSC | [verus](https://github.com/VerusCoin/VerusCoin) | [185d1a5](https://github.com/VerusCoin/VerusCoin/tree/185d1a54b8d890c95fd2ce5dd622f099a99aae6e) | [![dPOW Status](https://badges.komodo.earth/svg/VRSC_badge.svg?maxAge=60)](https://komodostats.com) | dPoW-3P

