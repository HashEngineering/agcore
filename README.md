ABCore - Android Bitcoin Core
=============================

[![Build Status](https://travis-ci.org/greenaddress/abcore.svg?branch=master)](https://travis-ci.org/greenaddress/abcore)

<a href="http://abco.re"> <img src="http://abco.re/assets/images/schema.png" alt="Infographic" width="650" height="650"></a>

Web site: <a href="http://abco.re">abco.re</a>

Warning: This app is still in a very Proof of Concept/Alpha stage.


<a href="https://play.google.com/apps/testing/com.greenaddress.abcore"> <img src="http://abco.re/assets/images/playstore.png" alt="Play Store" width="200" height="60"></a>

If you want to try it get it from the Play Store or directly from GitHub https://github.com/greenaddress/abcore/releases/tag/v0.43alphaPoC

What is Android Bitcoin Core?
-----------------------------

Android Bitcoin Core is an Android app that fetches bitcoin core daemon and dependencies and is meant to make it easier 
to run Bitcoin Core daemon node on always on Android set top box devices and home appliances.

The dependencies are fetched from either a Debian or Arch mirror (Arch providing 0.12.0 while Debian providing 0.11.2) and the node is meant to be used as a personal node when on the go (either by using a mobile wallet that allows to connect to a remote and specific node or even directly on your mobile device).

ABCore works on x86, x86_64, armhf and arm64 Android (any version from 4.0.0 onwards - sdk 16). Mips is not supported.

License
-------

ABCore is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Privacy
-------

ABCore doesn't do any kind of phone home, doesn't have In-App Purchase or advertising.

During the initial configuration connects to a user selectable Debian or Arch Linux mirror to fetch the required dependencies and once it is installed it only communicates with the rest of the Bitcoin network like any normal full node.

Limitations
-----------

ABCore requires a fair amount of ram (tested with 2GB) and a fair amount of disk space (tested with 100GB) as well as a decent always on connection - 3G or 4G is not adviced.

We also do not advice to use this as a wallet, we advice to use this as your personal blockchain anchor when on the go with wallets that support to set a personal node.

The contributors of ABCore are not liable for any cost or damage caused by the app including but not limited to data charges/penalties.

Acknowledgement
---------------

- Development

Lawrence Nahum
twitter.com/LarryBitcoin

- Graphic Content

Ottavio Fontolan
otta88.box (at) gmail (dot) com

- Testing & UX

Gabriele Domenichini
twitter.com/gabridome

- Community Manager

Timothy Redaelli
twitter.com/drizztbsd
timothy.redaelli (at) gmail (dot) com

Special thanks to the [Bitcoin Core dev team](https://bitcoincore.org/), the [Debian](https://debian.org) and [Arch Linux](https://www.archlinux.org/) teams and to [Alessandro Polverini](https://github.com/Polve) for the [Java RPC client](https://github.com/Polve/JavaBitcoindRpcClient).


